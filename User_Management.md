who - Show who is currently logged in

sudo adduser username - Create a new user account on the system with the specified username

finger - Display information about all the users currently logged into the system, including their usernames, login time, and terminal

sudo deluser USER GROUPNAME - Remove the specified user from the specified group

last - Show the recent login history of users

finger username - Provide information about the specified user, including their username, real name, terminal, idle time, and login time

sudo userdel -r username - Delete the specified user account from the system, including their home directory and associated files. The -r option ensures the removal of the user’s files

sudo passwd -l username - Lock the password of the specified user account, preventing the user from logging in

su – username - Switch to another user account with the user’s environment

sudo usermod -a -G GROUPNAME USERNAME - Add an existing user to the specified group. The user is added to the group without removing them from their current groups
