# 启动方法

1. 修改todo_demo_server/db/config/config.json
2. 编译项目 `cd .\todo_demo_server\ ` ，`npm install`
3. 创建数据库
    `cd .\todo_demo_server\db\ `
    `npx sequelize db:migrate`
4. 启动server 
    `cd .\todo_demo_server\ `
    `npm start`
5. 启动客户端
    `cd .\todo_demo_web\ ` ，`npm install`,`npm start`

6. 启动路径 `localhost:3000/home#/`