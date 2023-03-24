#Devops Mentorship

##Week 1 - Homework Task
Git koraci i komande:

$ ssh-keygen -t rsa #generisanje privatnog i javnog kljuca"

$ cat .ssh/id_rsa.pub #ispis javnog kljuca
#Javni kljuc se dodaje unutar github profila

$ mkdir anel-balalic-devops-mentorship
#Kreiranje direktorija 

$ cd  anel-balalic-devops-mentorship 
#Ulazak u direktorij

$ git init
#inicilizacija git-a



$ git commit --allow-empty -m "initial commit"
#Dozvoljavanje i pravljenje praznog commita

$ git branch #provjeraa brancha

$ git remote add origin https://github.com/anelbalalic/anel-balalic-devops-mentorship.git
#povezivanje sa udaljenim repozitorijem na Github

$ git push --set-upstream origin main #proslijedjivanje izmjena na remote repozitorij

#Kreiranje development branch 
#Provjera nove grane i prebacivanje na novu granu development u terminalu

$ git pull #povlacenje izmjena sa remote repozitorija

$ git checkout development #prebacivanje na development branch lokalno

#Kreiranje gitignore i readme file kroz vscode

$ git add .
#Dodavanje svih fajlova u direktoriju i proslijedjivanje na git,odnosno #pracenje od strane gita


$ git commit  -m "add .gitignore and readme files"
#Dodavanje fajlova uz poruku

$git push #pushanje fajlova na development branch



