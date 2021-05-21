# DCMLinux_Docker_Compose
Docker compose files for rapidly reploying DCMLinux bundles with DCM4CHEE

PreReq: </br>
Install Docker: https://docs.docker.com/engine/install/ubuntu/ </br>
Install Docker-Compose: https://docs.docker.com/compose/install/ </br>
sudo apt install getsome </br>
sudo git clone https://github.com/DCMLinux/DCMLinux_Docker_Compose.git </br>

Configure:</br>
cd DCMLinux_Docker_Compose </br>
sudo nano docker-compose.env - apply any changes such as username & password </br>
sudo nano docker-compose.yml - apply any changes such as username & password </br>

Deploy & Start: </br>
sudo sh start.sh </br>

Stop: </br>
sudo sh stop.sh </br>

Update: </br>
sudo sh update.sh </br>

Check Logs: </br>
sudo sh checklogs.sh </br>
