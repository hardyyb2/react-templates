# Contributing to React-Templates

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to React-Templates and its submodules, which are hosted on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

<br />

### Table of Contents

- [Code Of Conduct](#code-of-conduct)
- [I have a Question - OR - I need Help](#i-have-a-question---or---i-need-help)
- [What should I know before I get started?](#what-should-i-know-before-i-get-started?)
- [What does this project do and why is it useful ?](#what-does-this-project-do-and-why-is-it-useful)
- [How do I get started ?](#how-do-i-get-started)
- [How Can I Contribute?](#how-can-i-contribute)
  - [To the current repos](#to-the-current-repos)
  - [Create my own repo](#create-my-own-repo)
- [Styleguides](#styleguides)
  - [Git commit messages](#how-to-commit)
  - [Languages and Frameworks styleguide](#languages-and-frameworks-styleguide)
- [Attribution](#attribution)

## Code Of Conduct

This project and everyone participating in it is governed by the [react-templates Code of Conduct](https://github.com/hardyyb2/react-templates/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [hardikopensource@gmail.com](mailto:hardikopensource@gmail.com).

<a  name="22"></a>

## I have a Question - OR - I need Help

> **Note:** Please don't file an issue to ask a question. You'll get faster results by using the resources below.

- Contact the repository maintainer at -
  - [hardikopensource@gmail.com](mailto:hardikopensource@gmail.com)
  - [Hardik Badola (Linked In)](https://www.linkedin.com/in/hardik-badola-738341197/)

## What should I know before I get started?

- The frontend templates have been bootstrapped with [create-react-app](https://create-react-app.dev/)
- The project currently consists of the following major technologies (click and know more about them):
  - [React](https://youtu.be/1wZoGFF_oi4)
  - [Redux](https://blog.logrocket.com/why-use-redux-reasons-with-clear-examples-d21bffd5835/)
  - [Firebase](https://medium.com/firebase-developers/what-is-firebase-the-complete-story-abridged-bcc730c5f2c0)
  - [Node.js](https://www.freecodecamp.org/news/what-exactly-is-node-js-ae36e97449f5/)
  - [MongoDB](https://www.geeksforgeeks.org/what-is-mongodb-working-and-features/)
- Knowledge of [version control](https://www.atlassian.com/git/tutorials/what-is-version-control) and [Git and Github](https://youtube.com/playlist?list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)
- Knowledge of [clean code](https://github.com/ryanmcdermott/clean-code-javascript) would be required while contributing and would also be beneficial for your app's scalability and readability.

> Knowledge of the above mentioned technologies would be required while using these templates

## What does this project _do_ and Why is it _useful_

- This project consists of various templates which can be used to speed up the initial phase of setup and development
- Separate projects involve various technologies which take up a tremendous amount of time and effort to setup, before they can even be used (e.g. redux)
- With template already setup users can focus entirely on building their own application.
- For projects involving firebase, authentication (Google for now) has already been taken care of.
- For projects involving Node and MongoDB, database connection along with server file have been setup.
- A good directory and file structure (open to change) and naming conventions along with example files have been used to promote better design patterns, clean code and suitable heirarchy.

## How do I get started ?

Steps to start with the templates have been mentioned in each project's individual README.
Although the procedure is common, as mentioned below :

- Click on the template name you want to use. You will be redirected to the template github repo.
- Checkout to `main` branch and click on **Code** button or **Use this template**  
  (Follow below methods according to the button you clicked on ):

  **1**. If you clicked on **Use this template** (Preferred) -

  - Enter the details as you would while creating a repo
  - Then click on **Create repository from template** button
  - Your repository will be built upon the template
  - Click on Code and then clone the repo on your local machine

  **2**. If you clicked on **Code**

  - Select your preferred method (https, ssh or github cli) and click on copy icon button
  - Open your favored terminal (or integrated terminal in VS Code) and type `git clone [repo-link]`, replace _[repo-link]_ with the copied url and press Enter
  - The template will be cloned to your local machine
  - Now from root, enter `yarn install-all` or `npm install-all`
    > Note - If using npm, remove **yarn.lock** from the directories
  - Wait for some time while the dependencies download, and then enter :

    - `yarn start` or `npm start` to run in development mode (_hot reload only in client_)
    - `yarn dev` or `npm run dev` to run in developement mode (_hot reload in both client and server_)

  - Change remote repo
    - Check current remote with  
      `git remote -v`
    - Change the 'origin' remote's URL  
      `git remote set-url origin [your-repo-link]`
    - Verify new origin with  
      `git remote -v`
    - Push to new origin with  
      `git push -u origin main`

## How Can I Contribute ?

We are really glad that you want to contribute to the repository. Contributing to this repository not only works for you, but helps many others who are working on the same repo too, each and every contribution matters.  
Follow the below guidelines to contribute to this project -

### _To the current repos_ -

> Note - For contributing to current templates, create issues and pull requests in the respective templates and _not in this repo (react-templates)_, only changes to .md files and .gitmodules are to be made in this repo.

- **Create an issue** : First step to contribute to the repository is to create the right issue. Add the right labels to your issue.
  [How to create a good issue ?](https://medium.com/nyc-planning-digital/writing-a-proper-github-issue-97427d62a20f)

- **Add your code** : See the article on the following link to see how you can add your changes to the repo, but check [here](#how-to-branch) to see how to create branches .  
  [Guide to Github contribution](https://betterprogramming.pub/10-step-guide-to-github-contributions-9aeeb38493a8)

  ## How to Branch

  - After you clone your repo on your local machine, checkout to **dev** branch and merge **main** to it with  
     `git merge main`
  - After successful merge, create and checkout to new branch using  
    `git checkout -b [branch-name]`
  - The branch names should follow the patterns mentioned below :

    - Branch names should begin with what type of issue they solve. Choose from one of the following :
      1. **feature** - If it is a new feature
      2. **bugfix** - If it fixes a bug (breaking or non-breaking)
      3. **enhancement** - Any improvement to current repo (only code)
      4. **documentation** - Improvement or addition in docs (includes comments, readmes, .md files)
      5. **refactor** - Improvement in code quality (cleaner code, better design patterns)
      6. **restructure** - Restructuring folders and files
    - After selecting the type of branch, follow it with a / (backslash) and your desired branch name e.g.  
      `feature/firebase-email-auth`  
       Keep the branch name short and precise to what it does.
    - Make your changes in the branch using [atomic commits](https://www.tothenew.com/blog/why-are-atomic-commits-a-best-practice-in-git/).

      > Note - Look in individual templates README to see the commit rules, else if not mentioned follow [these](#how-to-commit)

  - After making changes in your branch, create a pull request to the `dev` branch of the original repo.
    > Note - Please make changes in the documentation(comments, .md files etc) too, that are affected by your code
  - Add the creator (or any other maintainer) for review.
  - Once the maintainer approves of the code, it will be merged to `dev` and then subsequently to the `main` branch

### _Create my own repo_

If the templates present in this repo do not cover the technology you wish to use (like Django or Golang), don't worry, you can create your own template and add it to this repo. Follow the below steps for the same :

- **Create an issue** : First step to contribute to the repository is to create the right issue. Add the right labels to your issue.  
  [How to create a good issue ?](https://medium.com/nyc-planning-digital/writing-a-proper-github-issue-97427d62a20f)

  > Note - For a new template create an issue in this repository only. Name the issue as the technologies being used to create the new template. e.g. **react-redux-django**

- **Create your repo** :

  - Create a repo in your own Github account and select _use as a template_ option
  - Make changes to your repo by following your own design pattern and commmit style.
    > Note - Please ensure to use the best design patterns in the respected language as well as a good folder structure. Please justify in the directory READMEs why you chose a particular structure
  - Once you are ready with the repo, clone this (react-templates) repo and create a new branch with the name  
    `template/[issue-name]` e.g. template/react-redux-django
  - Make changes in the `.gitmodules` file and run  
    `git submodule update --remote`  
     ([What are gitmodules ?](https://www.vogella.com/tutorials/GitSubmodules/article.html))
  - Link to your template should appear as a submodule in this repo.
  - Now create a pull request to the `dev` branch of this repo and add the creator (or any other maintainer) for review.
  - Once the maintainer approves of the code, it will be merged to `dev` and then subsequently to the `main` branch

  ### 🎉👍 Congratulations 🎉👍, your code would now serve as a strong foundation for others, upon which they can build their apps much easily and faster.

  > Note - **Don't forget** to increment the repo version in package.json according to the changes you make, [know about SemVer](https://www.geeksforgeeks.org/introduction-semantic-versioning/)

## Styleguides

### How To Commit

As already mentioned before, please follow the commit rules described in each individual repo, if not mentioned follow the pattern below
:

- Start with what has the commit achieved i.e. fixed, refactored, styled etc. in uppercase letters inside square brackets. Some of them being (but not limited to) :
  - REFACTORED
  - FIXED
  - STYLED
  - UPDATED
  - CHANGED
  - RESTRUCTURED etc.
- Follow this by a space and what or/and where the change happened  
  e.g.
  `[REFACTORED] App.jsx` OR `[UPDATED] test.js from class to hooks`

### Languages and Frameworks styleguide

Please follow the below mentioned styleguides according to the language/framework you are working on :

1.  **React / Javascript**

- Use hooks over classes
- Use class based components only when utterly necessary. e.g. Errorboundary, pure components etc.
- Type to create more stateless components
- If using redux, make network calls only in redux with redux-thunk and not within the component or page
- For file names, name components in PascalCase while page names in lowercase.
- For function and variable names use camelCase
  > Note - Try to follow [clean code](https://github.com/ryanmcdermott/clean-code-javascript) as much as possible
- Try to make directory imports and exports.
  e.g.  
   USE  
   `import { Login } from '../components'`  
   INSTEAD OF  
   `import Login from '../components/Login/Login'`
- Place imports in the following order (Look in React pages/home of any repo for the same):
  - Installed packages  
    / Empty line /
  - Local files, assets and modules  
    / Empty line /
  - Global store or Context (basically your data storage)  
    / Empty line /
  - Styles

2. **CSS/SCSS**

- _NO INLINE STYLING_
- Use CSS-IN-JS(styled-components) or CSS Modules
- Add global styles only in GlobalStyles.js and TypoGraphy.js
- Keep declarative class names, e.g.  
  `.loginButton` instead of `.button`

## Attribution

This Code of Conduct is adapted from the [Atom CONTRIBUTING.md][atom-contribution]

[atom-contribution]: https://github.com/atom/atom/blob/master/CONTRIBUTING.md
