# Hi there! :new_moon_with_face:

This is a repository containing all notes and files created while learning to work with Python (Flask) at [AltSchool Africa](https://altschoolafrica.com/schools/engineering).

**Please don't send pull requests**

**Caveat:** I use a MacBook, so the notes and files about installation and features might differ from what would apply to your computer. Trust [LMS](https://thealtschool.com/courses/backend-engineering-second-semesterpython), Live Classes and [Google](https://google.com) for a better-tailored experience.

If you like this structure and want to use it for your own notes or just go through for tips and practice, follow these steps: 

1. Fork the original repo on GitHub
2. Clone from your personal GitHub into the folder you use for AltSchool or Programming on your computer:  
    `git clone https://github.com/YourGitHubUsername/altschool-python`
3. Feel free to rename the cloned folder. This is entirely optional:  
    `mv altschool-python Python`
4. CD into the cloned folder:  
    `cd altschool-python` (or `cd Python` if renamed)
5. Add an upstream, which links to the original GitHub repo:  
    `git remote add upstream https://github.com/Ze-Austin/altschool-python`
6. Create and move into a new branch (preferably using your name or GitHub username for this repo):  
    `git checkout -b YourName`
7. Open the folder in your IDE to make your own notes and play with code files. Try it. Break it. Fix it. Repeat. To open the current folder in VSCode from the terminal:  
    `code .`
    - If this doesn't work, [google "add code to PATH"](https://www.google.com/search?q=add+code+to+path&oq=add+code+to+path)
8. When you're done for the session:
    - Stage your changes on git by adding them:  
        `git add .` or `git add file.name`
    - Then commit the staged changes:  
        `git commit -m 'message here'`
    - Alternatively, you can add and commit at once:  
        `git commit -am 'message here'`
9. Push the changes to your branch:  
    `git push origin branchname`
10. This is when you'll usually create a pull request on GitHub, but please don't. There's no point in merging everyone's personal notes, yet *it would be nice to see your name in the branch list* :revolving_hearts:
11. Get my weekly updates by pulling from the upstream:  
    `git pull upstream main`

Timeline: I usually update this with notes and files from the week's LMS content by Wednesday evening. Caleb's folder (and any other Flask tutor's) will be updated when they drop files on Slack.
