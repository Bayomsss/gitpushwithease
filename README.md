Thanks for using my script to make your workflow easier and less repititive.

If you have any question, you can reach out to me on @semudaraabayomi
on all platforms or Bayomi Semudara on ALX Intranet.

Here's how to get the 'push script' on your own machine or ALX webterm

Step 1: Create a file named 'push' --> this file can be created at any location.

Step 2: Copy and paste the code from the 'push file' on my gitpushwithease repo, add a new line after git push then save and exit.

Step 3: Make the executable with 'chmod +x push'

Step 4: At this point, you script has been created and you can test it with the command './push'

You can stop here and copy or move the file to the directory you want to push but as developers we are lazy people. So the next steps will ensure that you can push anywhere in your terminal. To do this, we have to add our script to $PATH.

Step 5: Paste this command 'sudo ln push /usr/local/bin/push' into your terminal press and enter

Step 6: Cheers!!!!! Anytime you need to push, just type 'push' on your terminal and press enter.