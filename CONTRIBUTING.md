# Steps on how to contribute to this project :-  

You can link your repositories/projects to this repository, by following the simple steps given below.  
  
# Step 1: Fork this Repository  
<img width="390" alt="image" src="https://user-images.githubusercontent.com/65490434/155885698-d402e31c-097f-4ffb-a94c-325327adc686.png">  

Do this by clicking on the fork button on the top of this page.  
```
This creates a copy of this repository in your account.  
```  

# Step 2: Clone the Repository  
Now, clone the forked repository to your computer. To do this :-  
1. Go to your GitHub account  
<img width="948" alt="image" src="https://user-images.githubusercontent.com/65490434/155885828-32b8b2c3-1869-4294-b8e0-23d5c63a0a24.png">  

2. Open the forked repository  
<img width="431" alt="image" src="https://user-images.githubusercontent.com/65490434/155885799-79f72b75-2449-4e17-a393-492fec795614.png">  

3. Click on the Code button (green coloured)  
<img width="230" alt="image" src="https://user-images.githubusercontent.com/65490434/155885757-86cb1ab8-576f-4391-aae4-7f8d4231ab21.png">  

4. Click on the Copy button (HTTPS Link)  
<img width="307" alt="image" src="https://user-images.githubusercontent.com/65490434/155885922-54312d2a-8306-48fa-9dd5-716ae52301e9.png">  

5. Open your terminal (windows terminal or git bash on windows is preferred)  
<img width="357" alt="image" src="https://user-images.githubusercontent.com/65490434/155885890-0941f036-a9ba-487d-8c7b-33dd7bc2c9f4.png">  

6. Type the following command :-  
```
git clone "url you just copied"  
```  
For example :-
```
git clone https://github.com/AryanGodara/amazing-github-projects-collection.git
```  
(Replace AryanGodara with *YOUR* github username

7. Create a Branch  

- Change to the directory of directory on your computer( if you aren't already not in that directory )  
```
cd amazing-github-projects-collection
```  
- Now create a branch using the `git checkout` command:  
```
git checkout -b your_branch_name
```  
For example :-  
```
git checkout -b add-aryan-godara
```  
(The name doesn't need to have the prefix of 'add' in it. But it's understandable, as the purpose of this branch will be to *add* your project to the list.)  

# Step 3. Make the necessary changes to the repository, and commit those changes  

Now open `PROJECTS.md` file in a text editor (I personally use vscode, but you can use any text editor, even notepad haha).  
Then, add the link to your project to the list (anywhere in the middle of the list, or at the bottom).  
Now save the file.

*Great! Now you've made the necessary changes. You now just need to commit these changes*  

- If you now go back to the terminal (open in this project's directory), and execute the command `git status`, you'll see that changes have been made.  
- Add these changes to the branch that you just created, using the `git add` command :-  

```
git add PROJECTS.md
```  

- Now commit these changes using the `git commit` command :-  

```
git commit -m "Added <Your_github_username> to the Projects list"
```
*NOTE :* You can add any message after -m, but make sure that it is relevant to the changes that you've made.  

# Step 4. Push the changes to GitHub  

- Push the changes using the `git push` command :-  
```
git push origin <the_branch_name_you_created_earlier
```
For example :-  
```
git push origin add-aryan-godara
```  

# Step 5. Submit your changes for Review  

Now, if you go to your repository (no GitHub), you'll see a `Compare and pull request` button.  
- Click on that button.  

- Now, submit the pull request  

- After some time, your changes will be merged into the main branch of this project (after being reviewed, of course)
- You'll receive a notification email once it's done.  

**Congratulations!** You've made your first contribution! 🙌🏼


## All the best! 🥇

Alternatively, skip all the steps above by using [![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/opensourcecommunity-hub/amazing-github-projects-collection/)

## Thank you for contributing to this project :)  
