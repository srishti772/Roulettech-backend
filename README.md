##Ubantu system update 
sudo apt-get update

git clone https://github.com/srishti772/Roulettech-backend.git


cd Roulettech-backend
cd recipes

sudo apt install python3-pip -y

install django
pip install django
cd ../ // root dir
pip3 install -r requirements.txt


pip3 install django-cors-headers


python3 manage.py makemigrations


python3 manage.py migrate

