---
tags:
    - tutorial
id: ""
created: 2020-03-28T07:52:59.238Z
modified: 2020-03-28T08:37:27.812Z
---
# Tutorial

> This tutorial assumes that you are hosting your cloud notebook on a GitHub repository. 
> In theory, it works similarly for all git repository platforms such as GitLab, Gitea, or your self-hosted ones etc.  

1. **Create a not empty git repository**

If you already had an git repository, you could skip to the next step now.
Otherwise, you can follow the offical [GitHub tutorial](https://help.github.com/en/github/getting-started-with-github/create-a-repo) to create a git repository.
   
For example, below I created a git repository with name `notebook-demo`, 
   
![](https://i.loli.net/2020/03/28/nuEUtBbsKl8pIZS.png)  

  2. **Add your notebook in Crossnote**
    
Click the `+` button next to **Notebooks** in sidebar.
 
Then enter the git URL of the repository that we just created. In our case it is `https://github.com/shd101wyy/notebook-demo.git`

![](https://i.loli.net/2020/03/28/caiW3BjOUmIxCy1.png)  
Click the **ADD** button to add the notebook.  
   
>If you are downloading a notebook from a private repository, you may also need to fill in the `Username` and `Password`. Don't worry, we won't upload your credentials to our server.
>
>You can also configure your git repository in notebook settings after you download the notebook 
    
3. **Keep your notebook up to date**

Crossnote doesn't support automatically updating your notebooks right now.  
You will have to manually upload your notebook to git repository or download the updates from git repository.  

There are two buttons in the toolbar of the editor that can help you perform the task.

![](https://i.loli.net/2020/03/28/UPgbTWtAsnDHurd.png)  

When you upload a notebook, you may need to fill in your `(Git repository) Username` and `(Git repository) Password`. 

For a notebook on GitHub, it is recommended to fill in a `Personal Access Token` in  `Username` (Not in `Password`).  See this [GitHub tutorial](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) for how to create a personal access token, and please note that we only need `repo` permission. 

For example:

![](https://i.loli.net/2020/03/28/i43xKVZEQwptc56.png)  

If you have any questions about the tutorial, feel free to post a [GitHub issue](https://github.com/0xGG/crossnote/issues)😉.




   
    


