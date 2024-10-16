# nodejs_code
git clone https://github.com/CO2annu/nodejs_code
cd nodejs_code
docker build -t myimg .
docker run -d --name anu -p 80:3000 myimg
