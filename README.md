# Dove-Blocker

This bird has been driving me mad for the past week. So, I wrote a content blocker extension for Safari that stops the animation of the bird on Facebook and hides the Giphy trash dove gif. If you wish to, you can add more URLs to block as well in the editor above.

1. Go to Develop in your Safari menu bar (if it is not there, Preferences -> Advanced -> Show Develop menu in menu bar)
2. Click on Show Extension Builder and add an extension
3. Copy this JSON snippet to a file, save it as blockerList.json and save it in the extension folder created in step 2
4. Set the content blocker file to blockerList.json and install

If you are not in the developer program, whenever you quit and reopen Safari, you will need to go back to the extension builder and re-enable it and it may also mess with your history which is a bit of a pain but not as painful as having to see that bird.
