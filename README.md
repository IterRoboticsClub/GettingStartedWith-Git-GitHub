[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/iteroboticsclub) [![h2](https://badgen.net/badge/License/MIT/green)](https://www.iterroboticsclub.com)

# GettingStartedWith-Git-GitHub
This project aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

<!--- <img align="right" width="300" src="assets/fork.png" alt="fork this repository" /> --->

## Fork this repository
Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<!--- <img align="right" width="300" src="assets/clone.png" alt="clone this repository" /> --->

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<!---<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" /> --->

For example:
```
git clone https://github.com/this-is-you/first-contributions.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<!---<img align="right" width="450" src="assets/git-status.png" alt="git status" />--->


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<!---<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" /> --->

Now submit the pull request.

<!---<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" /> --->

Soon we'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
