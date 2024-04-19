Install Nodejs, npm and pm2 in amazon linux
===========================================
sudo yum update -y
curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -
sudo yum install -y nodejs
npm --version
node --version
sudo npm install -g pm2
pm2 --version
sudo npm install -g serve

Build Commands to be used jenkins
=================================
npm install
npm run build
