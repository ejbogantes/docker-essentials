# Docker Essentials v1 by Emilio Bogantes <ejbogantes@gmail.com>
LinkedIn: https://www.linkedin.com/in/ejbogantes/
Website: https://emiliobogantes.com

# Make files executable (Optional)
chmod +x start
chmod +x stop
chmod +x wp-cli

# Run the project
docker-compose up -d or ./start

WordPress runs on http://localhost:8000
MySQL runs on 127.0.0.1:3306
PHPMyadmin runs on http://localhost:8001

# Stop the project 
docker-compose down or ./stop

# Extra example of WordPress CLI (Return users)
./wp-cli 

# Docker Compose Official Documentation
https://docs.docker.com/v17.09/compose/compose-file/

# Docker Hub
https://hub.docker.com/

# Docker Compose Cheat Sheet
https://gist.github.com/jonlabelle/bd667a97666ecda7bbc4f1cc9446d43a


# YAML Basics
https://www.tutorialspoint.com/yaml/yaml_basics.htm
