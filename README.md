About this Project: 
(1/2 part)
This is a webapplication in the process, the goal is to let developers make their own test plans and run them independently from system administrators.
Made for oracle databases.

At the moment the following is available:
- Login required for viewing every page
  - Add User: create and delete users (alternatively, there's script for both of these functions to run in the terminal independently without login: create_user.py, delete_user.py)
  - Users: Listing all users, showing admin prviliges
    ONLY ADMINS can add or delete users on the page and see these buttons. Unpriviliged users can see the user list if they copy the url, but not the functions.
- Main Page: Jobs and their statuses
- Test Steps for Test ID [..]: Test job's steps
