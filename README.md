# Docker_project
Project under guidance of Vimal daga sir in iiec rise campaign. 

First I installed docker on rhel 8 (Cli) on gcp
Then I pulled container image that have game deployed using cmd $docker pull nived15/mario-game
After that I installed that container using cmd $docker container run -d --name mario-game -p 80:80 nived15/mario-game
On port 80:80

For checking game is running I used cmd $curl http://localhost

