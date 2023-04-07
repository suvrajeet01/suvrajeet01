* 👋 Hi, I’m Suvrajeet
* 👀 I’m interested in Blockchain
* 🌱 I’m currently learning Blockchain                                            ![visitors](https://visitor-badge.laobi.icu/badge?page_id=suvrajeet01.suvrajeet01)
* 💞️ I’m looking to collaborate on Blockchain Projects
* 📫 Reach me @twitter - suvrajeetb

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **_Git Essentials_**
<br>

>
> * ### **Command Line Instructions**
>> * Gitpod can also be used as an alternate way instead of using local machine to work on files and hence finally upload them to a VCS service provider.
>> > * Step A may not be required in this case
>> * Commands to upload files from local repository to remote repository from **VCS** services provides like ' Github, Gitlab, etc ' : -


<br>
<br>

> ## A. **Git Global Setup**
 
```

git config --global user.name "github/gitlab-username"

git config --global user.email "github/gitlab-registered-email-address"

```


<br>

> ## B.1 **Create a new repository**

```

git clone https://www.github.com/username/repository-name.git **_OR_** https://www.gitlab.com/username/repo-name.git

cd repository-name

touch new-file-name

git add . **_OR_** git add file-name

git commit -m "commit-message"

git status

```

>> * To check the status of your files

```

git push -u origin master

```

>> * "-u origin master" is optional & is not required at most of the time .

<br>

<!--- [comment]: <> > ### **OR** -->
> ## B.2. **Create a new repository on the command line**

```

git init

git remote add origin https://github.com/username/repo-name.git

echo "# echo-text" >> README.md

git add README.md

git commit -m "commit message"

git branch -M trunk

git push -u origin trunk

```

<br>

<!--- []: > ### **OR** -->
> ## B.3. **Push a Local repo *WHILE* local repo != existing remote repo**

```

git init

git remote add origin https://github.com/username/repo-name.git

git add .

git commit -m "commit-message"

git branch -M trunk

git pull https://github.com/username/repo-name.git --allow-unrelated-histories

git push -u origin trunk

```

<br>

> ## B.4. **Push an existing repository from the command line**

```

git init

git remote add origin https://github.com/username/repo-name.git

git branch -M trunk

git push -u origin trunk

```
