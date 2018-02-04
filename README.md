First build the image.

sudo docker build -t tacotron-docker - < Dockerfile

Run the image using the nvidia-docker runtime.

sudo docker run --runtime=nvidia --rm -p 9000:9000 tacotron-docker