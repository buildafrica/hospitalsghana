# CONTRIBUTING GUIDE

## *STEP ONE*

- Make a fork of this repo on your Github
![FORK](images/Fork.png)

## *STEP TWO*

- Clone the repo on your computer:  
`git clone https://github.com/wecodeafrica/hospitalsghana.git` 

- Or, if you use SSH:  
`git clone git@github.com:wecodeafrica/hospitalsghana.git`

## *STEP THREE*

- Using yout command line tool, go to the app folder:  
`cd hospitalsghana`

## *STEP FOUR*

- Add remote upstream to the main repository:  
`git remote add upstream https://github.com/wecodeafrica/hospitalsghana.git`

- Or, for SHH:  
`git remote add upstream git@github.com:wecodeafrica/hospitalsghana.git`

Now you have two remotes on your local computer: `origin` and `upstream`

## *STEP FIVE*

- Make sure you are on master branch:  
`git checkout master`

- Get the current version of both on the main repository and push to your fork:  
`git pull upstream master && git push origin master`
- Create a new branch to work on and name it following this patther:  
`your-username\branch-purpose`;

- As an example:  
`git checkout -b lawrence\update-readme`

## *STEP SIX*

- After do some work, stage to git:  
`git add file you changed`

- In this case:  
`git add README.md`

- Commit the work you staged to git to save it permanently:  
`git commit -m "message of what you did"`

- In this case:  
`git commit -m "update contributing part of README.md`

- Push the new branch to the remote repo on Github:  
`git push -u origin branch you created`

- In this case:  
`git push -u origin lawrence\update-readme`

## *STEP SEVEN*

- Create a pull request  
This is for asking for your changes to be included in the main repository.  

- In Github, go to your fork of the repository
  
- You can use the _Compare and pull request_ button.

![Pull Request](images/pullrequest.png)

- Add a proper name and description to your pull request

![Pull Request](images/pulrequest2.png)

You can use follow this example:  

```md
# Title of what you did

## subtitle or short description
- To make points
- More points

# Screenshots
- drag and drop images to show the outputs of your changes
- this makes it easier to verify your changes
```

## *STEP EIGHT*

- Sit, relax, and wait for your pull request to be accepted. :)
- You did good.

## Maintainers

- [**Andrew Miracle**](https://github.com/koolamusic)
- [**Eugene Adortsu**](https://github.com/eadortsu)