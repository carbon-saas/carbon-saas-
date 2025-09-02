# clone your repo
git clone https://github.com/YOURUSERNAME/carbon-saas.git
cd carbon-saas

# setup backend
mkdir backend && cd backend
npm init -y
npm install express body-parser cors jsonwebtoken
touch server.js

# setup frontend
cd ..
npx create-next-app frontend
