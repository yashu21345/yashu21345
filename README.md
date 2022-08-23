- 👋 Hi, I’m @yashu21345
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
yashu21345/yashu21345 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Create git account configure repository
GIT commands in ubuntu
1) $sudo apt-get update
2) $sudo apt install git
3) $sudo su
4) #mkdir selab
5) #cd selab
6) #git init
7) #git status
On branch master
No commits yet
8) #git config --global user.name “spt”
9) #git config --global user.email “spt123@gmail.com”
10) #git status
11) #vi one.html [esc shift : wq to save and quit]
12) #git status
 One.html appears in red and git does not recognize this file as it is not moved to stage
13) #git add one.html
14) #git status
One.html appears in green indicating that one.html is moved to stage
15) #git commit -m “change1”
16) #vi one.html [make some changes to the file]
17) #git add one.html OR git add .
18) #git commit -m “change2”
19) #git log
20) #git diff ID1 ID2
Github [To push the code to github]
1) In the URL type https://github.com
2) Click on NEW to create new repository. Enter the repository name then click on create repository
3) Copy and paste the below command in the terminal 
a) Git romote add origin https://github.com/spt123/spt.git
b) Git push –u origin master
4) Enter user name
5) For the the password we need to generate the TOKEN using following steps
a) In the github click on profile image, goto settingsdeveloper settingspersonal access 
tokensgenerate new token
b) In the note field type any notein the select scopes select repo option and then click on generate 
token. New token will be generated copy and paste it in the terminal for password
6) Now the code has been pushed to the github. Make modifications to the code in github
a) Click on repository spt123click on one.htmlclick on edit optionmake changes to the code, 
then click on commit changes
b) We can PULL the code from github and see the changes
 #git pull
 #cat one.htm
