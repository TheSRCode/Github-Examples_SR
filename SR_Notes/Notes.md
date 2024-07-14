### Jai Shri Krishna

## Creating notes

### 1. Fork and Make changes in Others Repo 

If we want to make changes someone else repo, then
First fork the repo using github webpage (Click on Fork button).

Clone it using Https/SSH into your machine.

#Example

`git clone https://github.com/TheSRCode/Github-Examples_SR.git`

Edit or make changes as per requirments.

ten run these cmds to commit and push code into the main branch

```  sh 
git add .
git commit -m "Comment"
git push origin
```

### 2. Using Git in VS code

Instead of using codespace, I am using VS Code in my local.
To use VS Code for your Github Account, I need to install Vs Code Extension [ Github Pull Request ]( https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github ).

After successful installation, We can able to see the github icon on left panel, click it and sign it using Github Account.

#### Bonus
We can change VS code terminal to Git Bash which is better than Powershell(Windows).

#### Github Mobile

It is an application similar to Authy, MS Authenticator.
For Authentication We can enable 2 step verification for our Github Account.
It is a better to use Github Mobile, since it will provide easy access.

####Personal Note
I am unable to push changes on github through VS Code, since it is login with other account.
Using Github Desktop to push changes.
