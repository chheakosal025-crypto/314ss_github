git 
git គឹជា verdion control system
ដែលប្រើប្រាស់ដើម្បីតាមដានការប្រែប្រួល (track changes) របស់េឯកសារ foderឬ projuct.

Introduction to github
    github គឹជា online storqng ដែលប្រើប្រាស់ដើម្បីផ្ទុក github project។
     github   ប្រើប្រាស់ដើម្បី
        -រក្សាទុកកូដ
        -តាមដានការប្រែប្រួល ឬផ្លាស់ប្តូរកូដ
        -ធ្វើការជាក្រុម
        -ងាយស្រួលក្នុងការទាញយក និងប្រើប្រាស់ open-source projuct

gitនិង github 
+git ជា system (add) ដំណើរការលើម៉ាស៊ីន(local)
+github ជា online storang ដំណើរការ website

ជាពាក្យបច្ចេកទេសដែលប្រើប្រាស់ក្នុង github
-Repository (Repo) = projuct foder
-commit = save changes (Histoty)
-Branch = sepparate Version /សាខា
-push = add code to repo
-clon = copy repositoty

Commands used in git hub
+config git/gihub username and emali
# git config --global user.email your_email@gmail.com
# git config --global user.name your_username


.push new project to github
step 1:create repo in github 
step 2:initialize git in project
        #git add
step 3:add file to git
        git add
step 4 save changes
    git commit -m "your message"
step 5: add remote (copy frome github)
    git remote add origin your_repo_link
step 6:push code to repo
    git push -u origin master