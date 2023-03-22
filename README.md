* 👋 Hi, I’m Suvrajeet
* 👀 I’m interested in Blockchain
* 🌱 I’m currently learning Blockchain
* 💞️ I’m looking to collaborate on Blockchain Projects
* 📫 Reach me @twitter - suvrajeetb

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **_Git Essentials_**
<br>

>
> * ### **Command Line Instructions**
>> * Files from local repository can be uploaded to remote repository from **VCS** services provides like ' Github, Gitlab, etc ' using the instructions below : -

<br>
<br>

> #### 1. **Git Global Setup**

* 
```git config --global user.name "github/gitlab-username"```
<br>
* 
```git config --global user.email "github/gitlab-registered-email-address"```


<br>

> #### 2. **Create a new repository**
>> * git clone https://www.github.com/username/repository-name.git **_OR_** https://www.gitlab.com/username/repo-name.git
>> * cd repository-name
>> * touch new-file-name
>> * git add . **_OR_** git add file-name
>> * git commit -m "commit-message"
>> * git status
>> > * To check the status of your files
>> * git push -u origin master
>> > * "-u origin master" is optional & is not required at most of the time .

<br>

> #### **OR**
> #### 2.1. **Create a new repository on the command line**
>> * git remote add origin https://github.com/username/repo-name.git
>> * echo "# echo-text" >> README.md
>> * git init
>> * git add README.md
>> * git commit -m "commit message"
>> * git branch -M trunk
>> * git push -u origin trunk

<br>

> #### **OR**
> #### 2.2. **Push an existing repository from the command line**
>> * git remote add origin https://github.com/username/repo-name.git
>> * git branch -M trunk
>> * git push -u origin trunk
