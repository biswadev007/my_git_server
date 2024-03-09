## Set up your own git server

# Create own git server~🚀🚀

1. Set Up Your Server
   Ensure that your server has Git installed. You can install it using the package manager of your operating system. For example, on Ubuntu:
   $ sudo apt-get update
   $ sudo apt-get install git

2. Create a Git User
   Create a dedicated user for Git. This user will be used to manage Git repositories.
   $ sudo adduser git

3. Change user 
   $ sudo su git

4. Create a folder and git write permission
   $ mkdir git
   $ ctrl + d (Change to root user)
   $ sudo chown -R /git_path

5. Create a git repository
   $ git init --bare

# Setup Git basic UI~🚀🚀

1. Install gitweb
   Swich to root user
   $ sudo apt install gituser

2. Start a web browser
   Move to git_path
   $ git instaweb --httpd=webrick
   It will run on port 1234

3. Open git ui
   Open any browser and hit your_public_ip:1234