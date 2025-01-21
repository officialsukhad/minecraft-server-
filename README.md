#Links
https://github.com
https://papermc.io/downloads/paper
https://playit.gg/download/linux

You Can Follow the Commands From The Video or I will put them down here
#system cmds
1. apt update && apt upgrade -y
2. apt install screen
3. apt install openjdk-21-jre

#minecraft cmds
4. screen -S mc-server    (for creating a seperate screen for server )
5. mkdir mc-server && cd mc-server
6. wget https://api.papermc.io/v2/projects/paper/versions/1.21.4/builds/118/downloads/paper-1.21.4-118.jar                               (for downloading paper 1.21.4 / you can use any jar file)
7. mv *yourjarfile* paper.jar      (to rename yourjarfile to paper.jar)
8. nano start.sh   (for startup command for minecraft server)
9. java -Xmx15G -Xms15G -jar paper.jar nogui    (paste this using right click )
10. then press *ctrl + o* then then *enter* to save and *ctrl + x* to exit.
11. chmod +x start.sh    (giving executable permission)
12. after accepting eula with same nano eula.txt and making changes in server.properties accoring to video 

Minecraft Server is Up and Running but u can join without tunneling
 use *ctrl +a+d * to exit the mc-server screen

#playit cmds
make a screen for playit.gg by  screen -S playit

13. 
curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null

echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | sudo tee /etc/apt/sources.list.d/playit-cloud.list

sudo apt update

sudo apt install playit

14. after this run *playit* and follow along video to connect


and now your free 16gb 4 core minecraft server readyyy.
ENJOY



#freeminecraftserver #azureserver #pterodactyl #minecraft #freeserver 
