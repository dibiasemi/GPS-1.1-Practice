# GPS-1.1-Practice
Just using this to practice GPS 1.1
## Commands used thus far:
```mkdir GPS 1.1```
* Creates a folder to hold GPS 1.1 repo from GitHub

```cd GPS 1.1```
* Change to directory "GPS 1.1" where I am going to download my GitHub repo into

```git clone <URL>```
* clone the repository using the copied URL from my GitHub repo

```ls```
* used this to verify that my GPS-1.1 folder now contains the repo folder "GPS-1.1-Practice"

```cd GPS-1.1-Pratice```
* changed directories so that I can eventually create a file inside this folder

```touch awesome_page.md```
* created a practice file

```git status```
* used to verify that a file has been created that is currently "untracked"

```git add awesome_page.md```
* this command brings the file to the next "staged" state where it recognizes the file has been created/modified and it not only needs to be, but is ready to be committed

```git commit -m "Unique Message"```
* commit the change and add a commit message for future reference

```git branch```
* Used this command to verify that I am indeed on the "master" branch

```git push origin master```
* used this command to push the file to the master branch

```git checkout -b```
* used this command to not only create but switch to a feature branch

```subl README.md```
* used this command to navigate to/open the READMD.md file so that notes could be taken inside
