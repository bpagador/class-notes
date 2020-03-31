## GitHub

Master Branch
    source of truth 
    single source of truth
    perfect, final deployed code
    triggers testing and deployment
    branches are borne from a master branch

Dev Branches -- also called Feature branches
    PR = pull request 
    once you feel really good about your code, "pulling" is asking someone to look at it and approve it 
    you can then collaborate on the dev branch inside github
    approvals and rejections can happen here, also edits and comments

General
    git push origin master should not be used as pro devs on the job 
    git pull origin master is good because it is pulling that perfect deployed code 
    code review in imperative to be able to git push origin master 
    INSTEAD, git push origin "whatever you branch is"
    there are multiple branches that also have branches, popular ones are "staging" and "dev" -- they're all diff environments
    someone who's really good to talk about this with: Noah

## Lab set up for the day
    set up travis ci
        responsible for continous integration
        find in github marketplace, create a travis ci account, free version
    make a repo
        submitting the foundations way
        * travis CI
    clone it locally
        git clone in the terminal
        code .
        insert change-the-name-here, post clone link, to change the name locally 
    make a dev branch
        git checkout -b dev
    commit some changes
        git add -A
        git commit -m "initial commit"
    make a pr to master on github (compare and pull request button)
        git push origin dev 
    click in the compare and pull request button 
    submit link to PR to your canvas 
