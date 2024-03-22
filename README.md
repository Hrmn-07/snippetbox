docker run --name test-mysql -e MYSQL_ROOT_PASSWORD=strong_password -d mysql  
//to execute a new docker container using mysql. remember to change the strong_password to something else, and change the --name to snippetbox to make it easy

docker exec -it container_name bash
//to execute the terminal inside the container. Change container_name to snippetbox

docker exec -it test-mysql bash
//execute a bash terminal inside container

mysql -u root -p
//access mysql

