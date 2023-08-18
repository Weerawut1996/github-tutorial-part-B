ใช้ extensions ` "GitHub Pull Requests and Issues" ` ของ VS CODE ง่ายสุด
# Upload And Update github tutorial
1. Edit .gitignore ให้ เรียบร้อย
2. Check connect
>```cmd
>>> git init  
>```
3. Add file
>```cmd
> Add all file Changed
>>> git add .
> Add only flie "README.md"
>>> git add README.md
> Add Muti File
>>> git add index.html src\css\index.css src\pic\page1.svg
>```
4. Add commit
>```cmd
>>> git commit -m "first commit"
>```
5. Git push commited to repositories
>```cmd
>>> git push -u origin main
>```
** ถ้ามีปัญหาการ commit ให้อ่าน Error *
> <p>เปลี่ยน config user และ Email &#32;<a href="https://bobbyhadz.com/blog/change-git-user-or-github-account-in-vscode" >link</a></p>
>
>```cmd
>>> git config --list
>>> git config --global user.name "your_username"
>>> git config --global user.email "your_email@example.com"
>```

> <p>rejected master -&#42; master (non-fast-forward)&#32;<a href="https://stackoverflow.com/questions/11696295/rejected-master-master-non-fast-forward">link</a></p>
>
>```cmd
>>> git push --force <remote_repository>
>```
