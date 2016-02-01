# WebSite

# 1. Introduction
Files for website creation using hugo. PacRT files to create website using Hugo. The files include theme, content and images.

# 2. Install Hugo on your system
Need sudo previleges.
Get the latest from github.

**$ wget https://github.com/spf13/hugo/releases/download/v0.15/hugo_0.15_amd64.deb**

**$ sudo dpkg -i hugo*.deb**

Run the command to make sure it is all setup
**$ hugo version**

Will output

"Hugo Static Site Generator v0.15 BuildDate: 2015-11-25T06:36:28-08:00"

Enable Hugo Bash Auto-Completion. _Not required but helpful with bash_
Generate Hugo's bash autocomplete functions. Type the following command:

**$ sudo hugo genautocomplete**

source the file

**$ . /etc/bash_completion**

# 3. Run hugo and launch website
Get website files from https://github.com/PacRT/WebSite

You have to be in the directory to run hugo command.

The following command will create direcrtory called **public** and install all the files required for the site from the source. You can test running locally.

**$ hugo**

if you are re-running; it is always good idea to remove public diectory

**$ rm -rf public**

Use sudo with the above command if you do have privilges.

Luanch your browser and type the following link and browse the site:

http://localhost:1313

The above command will create
**$hugo server**
**hugo server -verbose**




