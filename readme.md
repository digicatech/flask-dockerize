docker build . -t flask_image

docker run --name flask_container -p 80:80 flask_image