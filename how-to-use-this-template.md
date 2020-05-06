Do you want to start a repo like this? not so hard! Head over to [the template repository at HackYourFutureBelgium](https://github.com/HackYourFutureBelgium/class-repo-template/) and follow these instructions:

1. set up a new repo for your class
    * either by cloning
        1. start an empty repository in your organization
        1. clone this repo
        1. replace all instances of `class-repo-template` with the name of your new class
        1. set your new repo as a remote
        1. push
    * or [generate from template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
1. set up the class overview app
    1. turn on github pages
    1. update the `repoName` and `userName` in `./class-data/index.json`
    1. add your students to `./class-data/students.js` (`{name:"student name", userName: "githubUserName"}`)
1. copy the template project board to your repo, one for each module
1. add your students as collaborators in the class repo.  They will need `write` access to be able to add their issues to the project board
1. set up the repository for homework submission & tracking via issues
    1. create a new label in your repository called `sunday-review`, this will be used to tag issues for review in class. We use the color #FFFF00, because it's bright yellow like the sun 🌞
    1. create labels called `week-n`, one for each week in the module
    1. create one milestone for each module ie. `working-with-code`
    1. and two more issues called `homework` and `wednesday-check-in`. these will be used for filtering each students' 2 weekly issues
1. each time you start a new module
    1. copy the assignments from the module repository into the class repo (so it doesn't change if the module does)
    1. change the statuses of the old and new module in the data file
    1. update coaches.json, and ask any new coaches to add a bio in `coach-bios`

Are you motivated to customize your HYF?  Check out the schemas/docs in the [class-overview-app](https://github.com/HackYourFutureBelgium/class-overview-app) & [diy.hackyourfuture.be](https://diy.hackyourfuture.be) to learn more about what's possible

> if you're using this repo outside of the HackYourFutureBelgium organization, you'll need to update a few links to make sure that the class repo is consistently pointing to itself where necessary.
>
> Once you think it's set up spend a half hour or so navigating the repo to make sure you didn't miss any
