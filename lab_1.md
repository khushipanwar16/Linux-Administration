Task :

Use the touch command to create sets of empty practice files to use during this lab. In each set, replace X with the numbers 1 through 6. 
Create six files with names of the form songX.mp3, snapX.jpg,filmX.avi. Create three subdirectories for organizing your files, and name 
the subdirectories friends, family, and work. Use a single -command to create all three subdirectories at the same time. 

Tasks Performed: 
1.  Created multiple files with names following a specific pattern:
   a) songX.mp3, snapX.jpg, filmX.avi (where X is 1 to 6).
   b) Used brace expansion to create all at once.
2. Created three directories (friends, family, work) using a single command.

Commands Used:

touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi  
mkdir {friends,family,work}


![Screenshot 2025-03-19 120053](https://github.com/user-attachments/assets/1e3c6e6b-a8c5-49ca-afa0-9dfa80402b2a)
![Screenshot 2025-03-19 120149](https://github.com/user-attachments/assets/c3361684-509c-4edf-bcc8-7cf6e73554d4)
