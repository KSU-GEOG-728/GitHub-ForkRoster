# GitHub-ForkRoster
*Exercise for GEOG 728 Programming for Geographic Analysis at Kansas State University*

### Objective

Learn how to find and fork a public repository, commit changes to a working file, and create a pull request.

### Task

After finding an interesting repository, create a fork, clone a local copy of the fork, and then edit a working file.  Push the changes to your forked repo on GitHub and then submit your proposed changes to the repository owner for consideration as a **pull request**.

### Required Software

The following software programs will be used in this exercise.  Each is available on the laboratory computers in S3014A.  If you plan to use your own personal computer this semester, please download and install.
1.  Notepad++ - https://notepad-plus-plus.org/downloads/
2.  GitHubDesktop - https://desktop.github.com/

### Procedures

**Step #1 - Create a GitHub Account**

This assignment assumes you already have a GitHub account.  If you do not, login to **GitHub** (https://github.com) and create a free personal account.  GitHub will serve as your online storage for coding work this semester.  I will be able to access your class-related code, provide feedback, answer your questions, and grade your assignments.  You will also have a permanent copy of your work that you retain and control after the semester ends.

**Step #2 - Find an Interesting Public Repository**

Login to your GitHub account, then search for the repository owner **owner: KSU-GEOG-728**.  Next, find the repository *GitHub-ForkRoster*.  

**Step #3 - Create a Fork**

After finding the public *GitHub-ForkRoster* repository owned by **KSU-GEOG-728**, locate the Fork button near the top of the page, click the drop down arrow, and choose <code>Create a New Fork</code>.  Typically, forks retain the same name as the original repository but will reside under your GitHub account.

**Step #4 - Start GitHub Desktop**

Start and login to **GitHub Desktop** using your new GitHub account credentials.

**Step #5 - Create a Local Clone**

Within **GitHub**, find your newly forked repository, click the green Code button, and choose *Open with GitHub Desktop*.  **GitHub Desktop** gives you the option to open the locally cloned files in an editor program (e.g., Notepad++), viewing the repository files in Windows Explorer, or opening the repository page on GitHub in a Web browser.

**Step #6 - View Files in Windows Explorer**

In **GitHub Desktop**, choose the option to view the files of your repository in Explorer.

**Step #7 - Edit a File in Notepad++**

Find the file <code>roster.md</code>, open it in **Notepad++** or your preferred text editor, and enter the information requested on the line that begins with your name. A file with the <code>.md</code> suffix indicates that it is a **Markdown** file. Markdown is an easy-to-read, easy-to-write language for formatting plain text that you can use to format your writing on GitHub in places like repository READMEs and comments on pull requests and issues.  As we will see later, Markdown is also used in both Jupyter and ArcGIS Notebooks to annotate code. 

**Step #7 - Describe and Commit Changes to Master**

After editing <code>roster.md</code>, you should see a snippet of the file in **GitHub Desktop** that highlights the revisions you just made.  Characterize your edits with a summary and short description (bottom left corner of **GitHub Desktop**), then choose Commit to Main.  This workflow allows you to maintain a record of changes made - essentially multiple versions of the same file - without having to have multiple copies of your file (e.g., roster1.md, roster2.md, etc.).  This is version control!

**Step #8 - Push Changes to Origin Repository on GitHub**

After you have made all of the changes you want, you now have to sync these changes - which currently apply only to the local version of the repository - to your original forked repo on **GitHub**. Once you have committed changes to master, you will have the option to push the commits to the origin remote.  Click the blue *Push Origin* button.

**Step #9 - Verify Changes in GitHub**

In **GitHub Desktop**, choose the option to open your repository page on **GitHub** in your Web browser.  Alternatively, you can simply open a Web browser and navigate to https://github.com.  Find the updated <code>roster.md</code> file in the forked repository and open it to confirm that your local changes are now reflected in your online repository.

**Step #10 - Create a Pull Request**

After confirming that your edits were successfully pushed to the fork on GitHub from your local cloned repository, open the <code>roster.md</code> file in **GitHub**, then find and click on **Pull Requests** from the main menu.  Create a pull request by clicking the appropriate link.  Look closely at the *Comparing Changes* screen as it shows you a lot of important information including what changes you are proposing, along with the head (source of change) and base (recipient of change) repositories.  Once you’re confident that all is in order, click the green **Create Pull Request** button, then enter some comments describing the changes you have made.  The repository owner will receive notification of your pull request and have the option to ignore or merge your changes into the project.  You, too, will be alerted to the outcome of your request...check your GitHub messages!

### Submission

After completing the requested edits to <code>roster.txt</code> make sure that you have (1) committed the changes to the main branch and provided a short summary and description of your changes and (2) pushed those changes from your local repository to the origin repository on **GitHub**.  Double check your work by reviewing the forked repository on GitHub and ensure your pull request is submitted.  As the owner of the repository that you forked, I will receive a message with your pull request and have the option to accept or decline the proposed changes to the <code>roster.md</code> file.  I will demonstrate this in class!
