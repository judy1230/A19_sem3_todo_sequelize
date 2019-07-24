# Project
<h3>ToDo List Sequelize</h3>
this project is working on CRUD by Sequelize

# Getting Start
<pre><code>
[~/] $ git clone https://github.com/judy1230/A19_sem3_todo_sequelize.git
[~/] $ npm i express
[~/] $ npm run dev
connect to  MySQL Workbench,
</pre></code>
<h4> open browser, typing localhost:3000 to start </h4>

this project will run in node.js enviroment, install it by below command in your teminal:
<pre><code>
[~/] $ nvm install 10.15.0
[~/] $ nvm install 10.15.
</pre></code>
# Display
![Minion](https://upload.cc/i1/2019/07/24/69fPpi.gif)

</pre></code>
# Material
<h4>browser: https://localhost＠port:3000</h4>
<h4>software framewark: <h4>
<h5>1. express: for sending req / res request</h5>
<h5>2. express-handlebars</h5>
<h5>3. express body-parser</h5>
<h5>4. MySQL Workbench</h5>  
  

# Features
|       Option            |                                           Description                               |
| ------------------      |------------------------------------------------------------------------------------ |
| 使用者可以新增todo-ist   |  首頁按下加入新餐廳按鈕, redirect到 'http://localhost:3000/todos/new'新增資料                  |
|                         |    相關資料: new.handlebars                                                         |
| 使用者可以瀏覽todo-ist   |  欄位按下detail, redirect到 'http://localhost:3000/todos/:id'瀏覽該筆資料                 |
|                         |    相關資料: new.handlebars                                                          |
| 使用者可以修改todo-ist   |  欄位與detail頁面按下edit, redirect到 'http://localhost:3000/todos/:id/edit'修改該筆資料    |
|                         |    相關資料: index.handlebars, show.handlebars                                        |
| 使用者可以刪除todo-ist   |  欄位與detail頁面按下delete, redirect到 'http://localhost:3000/todos/:id/delete'刪除該筆資料 |
|                         |     相關資料: index.handlebars   function: 加入刪除提醒                              |
| 使用者登入 / 登出        |  使用者可登入檢視專屬資料, 一旦登入成功登入欄位即變成登出  相關資料: login.handlebars    |                                | 
| facebook 整合登入       |  使用者可使用facebook整合登入及登出檢視資料    相關資料:routes/auths.js, config/passport.js |



# Authors
  <li>Judy</li> <p>first edited on 07/24/2019</p>
