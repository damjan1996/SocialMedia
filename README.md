# Social Media Automation Tools

This repository hosts scripts and tools designed to automate and simplify tasks related to various social media platforms.

Currently, the repository includes the following script:

# Flickr Image Interactor

This Python script uses Selenium WebDriver and PyAutoGUI to automate interactions with images on the Flickr platform. The process involves logging into a Flickr account, navigating to a specific image, and performing actions like adding comments, liking the image, and moving to the next image. The process is repeated for a set number of loops.

Key Components of the Script:

1. user_login:
This function logs into a Flickr account using given login credentials.

2. find_image:
This function navigates to a specified image on Flickr.

3. interact:
This function uses PyAutoGUI to simulate a user interacting with the image.

4. Main Loop:
In the main part of the script, the bot runs the interaction function in a loop.

Before running this script, you should replace the placeholders with your own details. Additionally, you'll need to have Selenium WebDriver and PyAutoGUI installed in your Python environment.
Please use this responsibly and respect the terms of service of the platform.
