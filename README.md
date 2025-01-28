# Jenkins-QALab

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key

echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt update
28/01/2025 14:07 • sudo apt install jenkins -y

sudo apt install -y openjdk-17-jre

sudo systemctl start jenkins

sudo systemctl status jenkins
