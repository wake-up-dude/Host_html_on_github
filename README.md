# Host_html_on_github


## Steps for Hosting a Website on GitHub

1. Create a GitHub account on github.com.
2. Download either [GitHub for Mac][1] or [GitHub for Windows][2], depending on your operating system. Open the app and log in using the account you just created.
3. (On Mac): After you login, click advanced and make sure that your name and email are correct. Then, click "Install Command Line Tools", just in case you want to start using the command line later in life.
4. Create a new repository in your GitHub application. Name it your-username.github.io. The name is *very* important. Note the folder that GitHub is saving the repository to. Make sure the "Push to GitHub?" box is checked.
5. Move your website's files into the folder that GitHub just created when you made the repository. **IMPORTANT**: Your homepage HTML file must be called "index.html", and it must exist in the top-level directory.
6. Back in the GitHub application, you should see your files in the left column. Make sure they are all checked. If so, enter a message in the text box called "commit summary", something like "initial commit." Then, click the commit button.
7. Click the "Publish repo" button in the top right corner.
8. Give it about 10 minutes, then check your-username.github.io. Your website should be there!

## Using a custom domain name

You can just leave your website at that address (it'll give you some serious street cred in the developer world), but if you have a custom domain you would like to use, it is very simple to make GitHub redirect your page.

1. Log in to your domain registrar and find where to change your host records. If you don't know, you can usually Google "(domain registrar) change host records", and your registrar will have an explainer telling you how to do it.
2. Change your domain's A Record to 204.232.175.78. This is GitHub's IP address, which allows GitHub to resolve your URL and serve the correct files.
3. In your website's directory folder on your computer, create a file called "CNAME". On the first line, type your domain name. Save the file.
4. In your GitHub application, you should see the file in the left column. Make sure it is checked and enter your commit message. Have it say something like "Adding CNAME file."
4. Click "Sync branches."

It can take as long as 48 hours for your domain to resolve to your GitHub page. However, it is usually pretty quick, so check back in an hour or so. 

[1]:  http://mac.github.com/
[2]:	http://windows.github.com/
