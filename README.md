dropbox_hellow_world
====================

A simple Dropbox Hello, World! application.

Original instructions for setup:
Link: http://scripting.com/2013/12/17/helloWorldForDropbox

0. Before starting, think of a name for your app, and find a server with https where you can store an HTML file. I used the public folder of my Dropbox account, but I started my account a long time ago when you could access these files directly over the web. If you started your account more recently, you won't be able to use that feature.

1. Visit the Dropbox app setup page. Click the big Create app button in the upper right corner. Screen shot.

2. Click on the Dropbox API app option, Files and datastores, Yes, your app can be limited to its own, private folder, and enter the name of the app you decided on in step #0. Here's a screen shot with the options chosen correctly. When you're ready, take a deep breath and click the Create app button.

3. Copy your App key, you'll need it later, and enter the OAuth redirect URIs. This part is a little tricky. You need to enter the exact address of the web page containing your app, which you haven't created yet. It must begin with https://, as indicated in the prompt. Here's a screen shot with the two parts highlighted.

4. Here's my Hello World app. Do a View-Source in your browser. Copy the text and paste it into an editor. Replace my app key with yours. Screen shot. Save. Do whatever you need to get it into your https server folder.

5. Pray.

6. Access your copy of the app over the web. With any luck you'll be redirected to the Dropbox site to have your app authorized. When you do so, the page reloads, and a dialog appears saying the file was written.

7. Look in your Dropbox/apps folder. You should see a new sub-folder, with one file in it, hello.txt. That's it! When this works you can pat yourself on the back, because you've written a Dropbox app! 
