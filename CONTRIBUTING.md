# Contribution Guidelines

If you believe that you have some excellent website link, book or any other article that can
help other people in their interview round etc. contributing that here will add some excellent 
stats on your GitHib and goes without saying some good karma 😉

You are also encouraged to share your experiences on how you prepared and cracked an interview.
See a sample [here](experience/anishLearnsToCode.md).

To contribute follow the below guidelines:

### 1. Fork this Repository
![fork](assets/fork.png)

### 2. Clone the repository from your profile
```bash
git clone your-github-user-name/placement-resources
cd placement-resources
```

### 3. Add links under the Tech or Non-Tech section in the `README.md` file 
Create a separate branch on your machine for the changes you wish to make as follows:

```bash
git checkout -b branch-name
```

Some good branch names could be _gsoc-experience_, _hackerrank-imp-questions_, 
_dbms-deadlocking-examples_ etc.

Edit the `README.md` file or add your experience under `experience/[unique-github-username].md`
like `experience/anishLearnsToCode.md`

If you are adding an experience then please also link your experience in the `README.md` file under the 
__Experiences__ section as follows:

```html
<a href="experience/your-github-username.md"><img src="https://avatars.githubusercontent.com/your-github-username" width="35px"></a> 
```

Add this link under all other links and please do not insert your experience link in the middle of the list. 
Thank you :smile:.

### 4. Commit and Push Changes

```bash
git add .
git commit -m "good commit message <50 chars"
git push -u origin branch-name
```

### 5. Create Pull Request
Open the forked repository on GitHub at 
`https://github.com/your-github-user-name/placement-resources`
and choose your newly created branch from the 
_branches & Tags_ dropdown menu.
 
 Then simply click on __Create Pull Request__ and voila job done !

### 6. Aftermath

Once your pull request has been approved and merged the master branch at `anishLearnsToCode/placement-resources`
will be ahead of your forked repo at `your-github-username/placement-resources`. To fix this you need to
add another remote to the official repo and match your local repo using that. 

```bash
cd placement-resources
git checkout master
git remote add destiny https://github.com/anishLearnsToCode/placement-resources.git
git pull --rebase destiny master 
git push origin master 
```

This will bring you repository at `your-github-username/placement-resources` up to date with 
`anishLearnsToCode/placement-resources`
