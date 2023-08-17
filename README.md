ใช้ extensions ` "GitHub Pull Requests and Issues" ` ของ VS CODE ง่ายสุด
# Upload And Update github tutorial
1. edit .gitignore ให้ เรียบร้อย
2. check connect
```cmd
git git init  
```
3. add file
>```cmd
> Add all file Changed
>>> git add *
> Add only flie "README.md"
>>> git add README.md
> add Muti File
>>> git add index.html src\css\index.css src\pic\page1.svg
>```
5. add commit
```js
git commit -m "first commit"
```
5. git push commited to repositories
```cmd
git push -u origin main
```
** ถ้ามีปัญหาการ commit ให้อ่าน Error *
> <div><p>เปลี่ยน config user และ Email &#32;<a href="https://bobbyhadz.com/blog/change-git-user-or-github-account-in-vscode" >link</a></p></div>
&#32;
```cmd
git config --list
git config --global user.name "your_username"
git config --global user.email "your_email@example.com"
```

