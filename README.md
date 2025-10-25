# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`sudo npm install`

`node app.js`

or Run by docker compose

test

#webhook code in build step:
docker rm -f $(docker ps -aq)
docker build . -t node-todo-new
docker run -d --name node-todo-new -p 8000:8000 node-todo-new

#end to end project:
sudo apt-get update 
    3  sudo apt update
    4  sudo apt install -y curl fontconfig openjdk-17-jre
    5  clear
    6  sudo apt install openjdk-11-jre
    7  clear
    8  java -version
    9  clear
   10  curl -fsSL https://pkg.jenkins.io/debian/jenkins.io-2023.key | sudo tee   /usr/share/keyrings/jenkins-keyring.asc > /dev/null
   11  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list > /dev/null
   12  sudo apt update
   13  sudo apt install jenkins -y
   14  clear
   15  sudo systemctl start jenkins
   16  sudo systemctl enable jenkins
   17  sudo systemctl status jenkins
   18  clear
   19  sudo ufw allow 8080
   20  sudo ufw status
   21  clear
   22  history
   23  sudo ufw allow 8080
   24  sudo ufw status
   25  clear
   26  cat /var/lib/jenkins/secrets/initialAdminPassword
   27  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   28  clear
   29  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   30  ssh-keygen
   31  cd .ssh
   32  ls
   33  cat id_ed25519
   34  cat id_ed25519.pub
   35  clear
   36  cd ..
   37  cd /var/lib/jenkins/workspace/todo-node-app
   38  ls
   39  sudo apt install nodejs
   40  sudo apt install npm
   41  sudo npm install
   42  clear
   43  node app.js
   44  ls
   45  sudo rm dockerfile
   46  sudo rm Dockerfile
   47  clear
   48  ls
   49  sudo apt install docker.io
   50  clear
   51  vi Dockerfile
   52  clear
   53  cd /var/lib/jenkins/workspace/todo-node-app
   54  ls
   55  vi Dockerfile
   56  sudo vim Dockerfile
   57  ls
   58  docker build . -t todo-node-app
   59  sudo usermod -a -G docker $USER
   60  docker build . -t todo-node-app
   61  sudo reboot
   62  clear
   63  cd /var/lib/jenkins/workspace/todo-node-app
   64  docker build . -t todo-node-app
   65  docker run -d --name node-todo-app -p 8000:8000 todo-node-app
   66  docker ps
   67  docker kill fbaf037d7962
   68  docker ps
   69  clear
   70  history
   71  chmod /var/lib/jenkins/workspace/todo-node-app
   72  sudo chmod /var/lib/jenkins/workspace/todo-node-app
   73  sudo usermod -a -G docker $USER
   74  sudo reboot
   75  clear
   76  cd /var/lib/jenkins/workspace/todo-node-app
   77  jenkins restart
   78  sudo systemctl restart jenkins
   79  clear
   80  sudo systemctl restart jenkins
   81  sudo usermod -a -G docker $jenkins
   82  sudo systemctl restart jenkins
   83  docker ps
   84  clear
   85  sudo usermod -a -G docker $jenkins
   86  sudo systemctl restart jenkins
   87  sudo chmod 777 /var/lib/jenkins/workspace/todo-node-app
   88  sudo usermod -a -G docker $jenkins
   89  sudo systemctl restart jenkins
   90  docker ps
   91  clear
   92  sudo usermod -a -G docker jenkins
   93  sudo systemctl restart jenkins
   94  docker ps
   95  docker kill 94a8465403b6
   96  docker ps
   97  clear
   98  ps ls
   99  ps
  100  docker ps
  101  clear
  102  docker ps
  103  docker ps a
  104  docker ps -a
  105  docker rm 94a8465403b6
  106  docker rm fbaf037d7962 
  107  docker ps -a
  108  docker ps
  109  clear
  110  history

