## My Firefox Style Setup

When you want to customize yout Firefox here are the steps to follow:

### Find the path to your application

1. Open the Firefox web browser.
2. Type in the URL bar `about:support`.
3. Under `Application Basics` you'll find `Update Folder` Or `Profile Directory`<br>
*It depends on the OS you're using.*
4. The path shoul look something like this<br> 
&rarr; `$HOME/Library/Application Support/Firefox/Profiles/XXXXXXXX.dev-edition-default`.
5. Go to that directory and add a directory named `chrome`.
6. Now add in the `chrome` directory the file `userChrome.css`. 

### When you created the `userChrome.css` file

1. Go back to the Firefox web browser
2. Enter `about:config`
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Set the value to true if not already.
5. Close the browser, *Make sure you closed it properly*


Done...