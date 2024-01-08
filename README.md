git clone https://github.com/andxbes/strapi-blog.git

git submodule update --init --recursive

docker compose up 

cd ./frontend

npm install 

npm build

# or npm start 
