# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It contains the dependencies of a project and scripts to install them
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
At the root, becuase this is where it is looked for by npm
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run serve
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
use `heroku logs` or `heroku logs -t` commands
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Pushing to github will automatically update it on heroku if the repository has been linked properly
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
To keep code organized as its worked on by multiple developers simultaneously, and to mitigate the introduction of critical bugs into the master branch or live app
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before merging the branch
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
