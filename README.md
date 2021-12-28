# InstagramPyBot
Instagram Bot to Bulk Follow a List of Usernames


## Running

### 1. Download external software

#### Chromedriver
Go to this [page](https://sites.google.com/a/chromium.org/chromedriver/home) and click to view the "Latest stable release".
Download the zip file for your operating system.

### 2. Download everything in this repo
Click the green "Clone or download" button above, then "Download ZIP".
The repo files should download to your machine as a zip. 
Unzip the repo.
You can move this directory to somewhere convenient (I assume it's on the desktop in the example below).

### 3. Move the chromedriver executable into the project directory
In step 1, you downloaded a chromedriver zip file. 
Unzip it, which should produce a `chromedriver` file.
Move this file into the directory created when you unzipped the repo in step 2.
You should now have `instagrambot.py`, and `chromedriver` in the same directory.


### 4. Put the file with the usernames into the project directory.

### 5. Run the bot


#### Run the python script

So, the command to run will be something like `python3 instagrambot.py --username my_insta_account_123 --password my_s3cret_p@ssword --account_list_file accounts.txt`
