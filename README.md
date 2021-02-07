# GIT Install
- [Download Git](https://git-scm.com/downloads) Appropriate operating system

    ![Next](/img/install-git-2.png)

- click the downloaded installer and click
next

    ![Wait for the process to finish](/img/proses-git.png)
- after the installation is complete follow these steps to interrupt git


<hr> 

# How to use GIT

** Step 1: ** Create a Folder anywhere on your PC..

** Step 2: ** Open that Folder and right click on it.

** Step 3: ** You will get a ``` Git Bash here ``` option. Click on it. You will see a command line prompt.

Now follow the command below:

```
$ git config --global user.name "Your Name"
$ git config --global user.email "Your_email@Example.com"
$ git status
```

The command below will display all files and Folders

```
$ git add --all
```

Now check the status ```git status``` The new file: <file> will be shown in green color i.e the files are staged.

Now Commit the files
```
$ git commit -m "install git"
```
<hr>

## Create a New Repository
Login to GitHub and click on the ``` + ``` on the top right of browser. select New Repository.

![New Repository](img/new-repo.png)

Enter Repositroy Name

![Repo Name](img/create-repo.png)

Select Public or Private as per your requirement. 

If you want to initialize this repository with README, click on the other checkbox skip and click ``` Create Repository ```
Assume that your repository name is ** Technical-Writer ** and username is ** Deni-Ardiansyah **

![Repository](img/git-push.png)

Congo! you have successfully created a new repository named planets.

# Make a connection between local repository to GitHub repository 
Use below command with your own username.
```
$ git remote add origin https://github.com/deni-ardiansyah/Technical-Writer.git
```

push to GitHub Push serves to upload the final result of the steps above. Enter the following command to push it to GitHub:

```
$ git push -u origin master
```
$ git remote add origin https://github.com/usename/Technical-Writer.git
```
