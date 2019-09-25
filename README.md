Hey Matt,

The attached files were created using the Duplicator plugin's "once click download". I doubt you'll need it but, as a precaution, I included the following steps for installation on a different server as copied from "https://wpshout.com/quick-guides/move-a-wordpress-site-with-the-duplicator-plugin/". Step 6 is the place to begin.

1.Install and activate the Duplicator plugin, on the WordPress site you’re copying from.

2.Click on “Duplicator > Packages” in the left-side menu (it’s toward the bottom).

3.In the top right on that screen, click the “Create New” button.

4.Click through the wizard. That’ll be a blue “Next” button on the “1-Setup” screen, and a “Build” on the “3-Build” screen.

5.When you see “Package Completed” click the “One-Click Download” link. You should be prompted (by your web browser) to download two files. Save both.

START HERE

6.After they’ve completed the download, move the two files (installer.php and something ending with .zip) into the folder you’ll want the WordPress site in.

7.In a web browser (with your server running) visit the installer.php file.

8.If everything works, you should see a wizard screen similar to the style you saw in your WordPress dashboard. You’ll need to click “I have read and accept all terms & notices.”

9.Click “Next.”

10.Here you’ll need to have a database ready. Then tell Duplicator your database name, user, and password. For me, that meant creating a new one with MAMP, but this step will vary depending on your environment. For many shared hosts, you’ll have a cPanel based “Database Wizard” to do this.

11.If it all works, you’ll see “Step 4 of 4: Test Site”. There you’ll want to click the “Site Login” button, and log in to your WordPress site using the same username and password as you have on the remote site.

12.You should now be in a full-fledged copy of your WordPress site.

13.Make sure to clean up after Duplicator. It’ll give a helpful admin notice (a banner at the top) showing you things. If you click “Take me there now!” you’ll then be on the screen to click “2. Remove Installation Files Now!” After you do that, you’re done.

Let me know if it works. :-)
