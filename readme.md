1. npm create refine-app@latest client (1. refine(CRA) 2. client 3. REST API 4. Material UI 5. Yes 6. Yes 7. Yes 8. Google 9. No 10. No 11. npm)
2. cd client
3. npm install apexcharts react-apexcharts
4. configure gcp oauth consent screen + oauth client id (insert client-id into pages/login.tsx google initializer)
5. mkdir server , cd server (npm init -y)
6. add "type": "module" to package.json,
7. npm install cloudinary cors dotenv express mongoose nodemon
8. rename "test" in package.json to "start" : "nodemon index"
9. server deployed to render.com
10. client npm run build and deployed manually to netlify with a redirect file added to the build folder https://refine-dashboardd.netlify.app/
