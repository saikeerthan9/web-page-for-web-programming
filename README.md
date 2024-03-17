Here's how to host a basic webpage containing your name, roll number, and university name on Github:

1. Create a Github Repository:

Sign in to your Github account or create a new one if you don't have one already.
Click on "New repository" and give it a name (e.g., "my-basic-webpage"). Optionally, add a short description.
2. Create an index.html file:

This file will contain the code for your webpage. You can use any text editor (like Notepad or Sublime Text) to create it.
and upload your html document if needed include css also
4. Save the file:

Save the file as "index.html" in your desired folder on your computer.
5. Push the code to Github:

Open a terminal or command prompt on your computer.
Navigate to the folder where you saved the "index.html" file using the cd command.
Initialize a Git repository in your folder by running git init.
Add the "index.html" file to the staging area using git add index.html.
Commit the changes with a message using git commit -m "First commit" (replace the message with something descriptive).
Create a remote repository on Github by copying the HTTPS URL under "Clone with HTTPS" in your repository settings.
Run the following command to push your code to Github, replacing <remote_repository_url> with the copied URL:
git remote add origin <remote_repository_url>
git push -u origin master
Explanation of Screenshots (not possible to include in text response):

Screenshot 1: Showcases creating a new repository on Github.
Screenshot 2: Illustrates the "index.html" file saved in a text editor.
6. Accessing your webpage:

Once you push your code, your webpage will be accessible on Github Pages.
Go to your repository settings on Github.
Under "Pages," you'll find a link to your published site (e.g., <username>.github.io/<repository_name>).
