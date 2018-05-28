# learning-vue

> A Vue.js project for learning how to use Vue to make a interactive website.

## Git setup
``` bash
# Clone the repo
git clone https://github.com/NinngyouYunt/learning-vue.git

# To create a branch and switch to it
git checkout -b [name_of_your_branch]

# To push a branch to remote
git push -u [name_of_remote] [name_of_your_branch]

# To add changes, can use . to mean add all changed files
git add [name_of_file]

# To add commits
git commit -m'commit messsage'

# To push to the remote origin
git push [name_of_remote] [name_of_branch]

# To remove a local branch
git branch -d [name_of_your_branch]
```
Remeber to pull master to keep your code up-to-date  
and rebase your branch so you have the newest master with your own change  
alternatively, merge master to your own branch, solve conflict and merge(pull request)

___DO NOT___ merge a branch locally to master and push it (it will overwrite what's on master)
Use pull request on Github

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
