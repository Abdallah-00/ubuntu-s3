1. Create a user account with the following attribute
   • username: “your first name”
   • Fullname/comment: “full name”
   • Password: islam
  ![image](https://github.com/user-attachments/assets/834c8a9c-7685-432e-b29c-53453ccf0325)

2. Create a user account with the following attribute
   • Username: baduser
   • Full name/comment: Bad User
   • Password: baduser
  ![image](https://github.com/user-attachments/assets/adfad37d-fc77-487b-9f97-6594a87eb0a1)

3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
   ![image](https://github.com/user-attachments/assets/4cc0b5e4-9515-4629-968c-87e10533a0cf)

4. Create a supplementary group called badgroup
   ![image](https://github.com/user-attachments/assets/0efdb732-7f86-4a13-8efb-4110024a3e5b)

5. Add islam user to the pgroup group as a supplementary group
   ![image](https://github.com/user-attachments/assets/621e10e1-1010-40f5-90c3-4b508a5dc711)

6. Modify the password of islam's account to password
   ![image](https://github.com/user-attachments/assets/2906e958-9a45-42d1-ab5c-8601a80ee4a9)

7. Modify islam's account so the password expires after 30 days
   ![image](https://github.com/user-attachments/assets/0db5df0f-99e4-436d-babc-6843c518eb75)

8. Lock bad user account so he can't log in
   ![image](https://github.com/user-attachments/assets/72812c3b-7ff6-4835-ab8e-c1f47c42c1dd)

9. Delete bad user account
   ![image](https://github.com/user-attachments/assets/cbb2bbae-ec1d-450f-b51b-fb08bfe4fd68)

10. Delete the supplementary group called badgroup
   ![image](https://github.com/user-attachments/assets/d30bf1f9-d40d-47a4-9968-79e8faa55193)

11. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
   ![image](https://github.com/user-attachments/assets/6dd66513-825d-4fca-9307-73c8fe5f17ab)

12. Log out and log in by another user
   ![image](https://github.com/user-attachments/assets/d47171de-9d66-4e95-bad5-43593876d823)

13. Try to access (by cd command) the folder (myteam)
   ![image](https://github.com/user-attachments/assets/c3bc75e5-491d-42b9-a074-d01d0e73d500)

14. Using the command Line
    • Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
    • Change your default permissions to be as above.
   ![image](https://github.com/user-attachments/assets/c849db25-e46f-4739-8cce-e32009aa3833)

    • What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
    _For files the maximum is 666
    _For directory the maximum is 777
    
    • Change your default permissions to be no permission to everyone then create a directory and a file to verify.
15. Starting from your home directory, find all files that were modified in the last two day.
   ![image](https://github.com/user-attachments/assets/8d112cea-8a8c-4e1d-bec2-c6da91a17123)

16. Starting from /etc, find files owned by root user.
   ![image](https://github.com/user-attachments/assets/33c07ca1-a587-44b2-9cb3-fdd38834fe8d)

17. Find all directories in your home directory.
   ![image](https://github.com/user-attachments/assets/3bfc85c0-5c39-4b03-9768-b93b2fa7c2b1)

18. Write a command to search for all files on the system that, its name is ".profile".
   ![image](https://github.com/user-attachments/assets/587873ea-a13a-4b40-b379-86d162b4580b)

19. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
   ![image](https://github.com/user-attachments/assets/e241d826-556b-434e-99af-4d969a3d4cd1)

20. List the inode numbers of /, /etc, /etc/hosts.
   ![image](https://github.com/user-attachments/assets/1768577a-bc91-42ce-b6be-06b3f6a1696e)

21. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.
22. Create a symbolic link of /etc/passwd in /boot.
23. Create a hard link of /etc/passwd in /boot. Could you? Why?
