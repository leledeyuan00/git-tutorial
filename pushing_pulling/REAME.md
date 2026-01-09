## git push

Now that you have committed changes to your local repository, it's time to share those changes with others by pushing them to a remote repository.

1. First, ensure you are in the directory of your cloned repository in your terminal.

    ``` bash
    cd path/to/your/cloned/repository
    ```

2. To push your local commits to the remote repository, use the following command:

    ``` bash
    git push -u origin master
    ```

> Here, `origin` refers to the remote repository you cloned from, and `master` is the branch you are pushing to. If you are working on a different branch, replace `master` with your branch name, -u set the default upstream for your branch.

3. Now, you can see your changes on GitHub.
   
   Go to your repository on GitHub, and you should see the changes you just pushed.
   ![pushed_changes](pics/pushed_changes.png)

## git pull

Let's say there are new changes in the remote repository, and you want to update your local repository with those changes.
> This is usually happens when you are using another's repository, collaborating with others or working on multiple devices.

1. Changing this file directly on GitHub. Add a new line like `This line is added on GitHub.` and commit the changes.
   
    ```

    ```

2. Now, go back to your terminal and make sure you are in the directory of your cloned repository.

    ``` bash
    git pull origin master
    ```

You should see the new changes in your local repository.

:tada: Great job! You have successfully pushed your local commits to a remote repository and pulled changes from a remote repository to your local repository.