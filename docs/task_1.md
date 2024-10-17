# Task 1

## Description
In this task, you are required to create a folder called `super_secret_stuff` and place a file called `top_secret.txt` inside it.

## Steps Taken
1. Created the folder:
   ```bash
   mkdir ~/super_secret_stuff
2. Created the file:
   echo "Your secret content goes here." > ~/super_secret_stuff/top_secret.txt
3. Updated the database and located the file:
   ```bash
   sudo updatedb
locate top_secret.txt
4. Saved the path to secret_place.txt
locate top_secret.txt > ~/secret_place.txt

Result
The path to top_secret.txt is saved in secret_place.txt.
