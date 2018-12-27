## Commit changes to your GitHub repository

1. On your computer, open the Terminal window and go to your repository directory
    ```console
    $ cd myrepository
    ```
2. Check whether your remote origin (i.e. your GitHub repository) is set
    ```console
    $ git remote -v
    ```
  Set the remote origin if it is not already set
    ```console
    $ git remote add origin https://github.com/username/myrepository.git
    $ git remote -v
    ```
GitHub Help:    
[Adding a remote](https://help.github.com/articles/adding-a-remote/)    
[Managing a remote](https://help.github.com/categories/managing-remotes/)

3. Save your changes to the your GitHub repository  
  You will need to issue the following command after your create new files or you make changes to existing files.

a. Stage the changes
    ```console
    $ git add -A
    ```
b. Commit the changes
    ```console
    $ git commit -m "provide a meaningful message"
    ```
c. Push the changes to your GitHub repository
    ```console
    $ git push origin master
    ```
