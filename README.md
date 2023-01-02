# Practise_HR
sudo yum update
sudo yum install git
sudo yum install docker
------------
sudo git clone "url"
ls
cd "folder name"
-----------------
sudo systemctl start docker
sudo systemctl enable docker
sudo systemctl status docker
------------
sudo docker build -t hii .
sudo docker run -d -p 8000:8000 hii
sudo docker ps

TO KILL CONTAINER.
sudo docker kill (containerid)
sudo docker ps
sudo docker rmi hii --force
