cd client ไปยังโปรเจคหลักเรา
1. ลบ node_module(ไม่มีก็ข้ามขั้นตอน เพราะยังไม่ได้ติดตั้ง nodejs)
npm install
npm i
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
npm i react-router-dom react-icons
npm run dev
----------------
cd.. ให้มาหน้าsparktech-youtube
npm i concurrently
แก้ start to dev ในหน้า package.json เพื่อให้ run dev แล้วใช้พวกคำสั่ง นี่ในคำสั่งเดียว(   "dev": "concurrently \"cd client && npm run dev\" \"cd server && npm run dev\" " )


---------- server-----------------------------ทำหน้า server----------------
npm install mongoose
cd.. ไปยังหน้าหลัก
npm init -y
cd server
npm i npm i bcryptjs
npm i express mongoose dotenv
npm install -D nodemon
- npm start
- cd controllers
- npm i jsonwebtoken 
ในหน้า controllers
