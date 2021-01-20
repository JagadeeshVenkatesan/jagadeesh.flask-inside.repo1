Build the image using the following command

docker build -t jagadeesh1:latest .

Run the Docker container using the command.

docker run -d -p 5000:5000 jagadeesh1:latest

The application will be accessible at localhost:5000