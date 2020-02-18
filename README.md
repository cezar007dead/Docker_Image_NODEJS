# Docker_Image_NODEJS
Docker image of node js server 

1)Navigate to folder

2)docker build -t {Tag} .

3)docker run -p 8080:8080 {Image id or Tag}

To connect to server's local files open another terminal and rigth comand

docker exec -it {Image id or Tag} sh (Linux) or winpty docker exec -it {Image id or Tag} sh (Windows)

