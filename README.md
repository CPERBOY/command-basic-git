
 command-basic-git
 ==============

  1.drop-down menu, and select New repository
  
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/repo-create.png)

  2.Choose a template drop-down and select a template repository

  ![GitHub Logo](https://help.github.com/assets/images/help/repository/template-drop-down.png)

  3.Use the Owner drop-down menu, and select the account you want to own the repository
      ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-owner.png)

  4.Type a name for your repository, and an optional description
      ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-name.png)

  5.Choose a repository visbility. For more information, see "About repository visibility."
  
  ![GitHub Logo](https://help.github.com/assets/images/help/repository/create-repository-public-private.png)

การใช้งานคำสั่งพื้นฐาน Git ที่ใช้งานกันบ่อยๆ บน Terminal
==============
```bash
git status คือ แสดงไฟล์ที่มีการเปลี่ยนแปลง หรือยังต้องการ add หรือ commit
git add คือ การเพิ่มไฟล์เป็นสถานะ stage
git reset คือ การ unstage ไฟล์ที่เราเคย stage
git commit คือการ commit ไฟล์ที่ stage โดยมักจะใช้  git commit -m เพื่อเพิ่มข้อความในสิ่งที่ทำไป
git log คือการดุประวัติที่เคย commit ไว้
git pull คือการ remote ไฟล์มายัง local โดยคำสั่ง git pull นั้นจะทำการ git fetch และ git merge ไปด้วย โดยเราจะมักเห็นใช้ git pull –rebase เพื่อทำการเปลี่ยนฐานแทนการ merge
git merge (branch) คือการรวม branch ที่เจาะจงมายัง local
git fetch คือ การตรวจสอบไฟล์ภายใน local และ remote ว่าตรงกันหรือไม่
git push คือ ส่งการเปลี่ยนแปลงของไฟล์ไปบน remote repository
git stash คือ การเก็บซ่อนการเปลี่ยนแปลงทั้งหมดไว้ทั้งหมด และสามารถนำกลับมาโดยใช้ git stash pop
git checkout (branch) คือ การเปลี่ยน branch
git clone (url) คือการ คัดลอกโปรเจคจาก remote มายัง local
