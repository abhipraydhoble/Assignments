# Linux Task Sheet

## $${\color{blue}\textbf{System Information Commands}}$$
1. Display the kernel name.
2. Display the current date and time.
3. Show your machine name.
4. Display the version and release of the kernel.
5. How to check the size of a directory?
6. Display the OS name.
7. Print the current running shell.
8. How to check available memory?
9. Display the current username.

---

## $${\color{green}\textbf{File and Directory Management}}$$

1. Create a directory with the name `/practice`.
2. Create a file in the `/practice` directory named `task2.txt`.
3. Write 10 lines of data in `task2.txt` using the `vi`/`vim` editor (topic: *India*).
4. Copy the first 4 lines of the file and paste them at the end.
5. Find the line number where the word *India* appears.
6. Save the file without quitting the editor.
7. Replace the word *India* with *Bharat* in the file.
8. Save the file without using the `wq` command.
9. Copy the `task2.txt` file to `/task3.txt` without using the `cp` command.

---

## $${\color{orange}\textbf{User and Group Management}}$$
1. Add users: **raju**, **sham**, and **babubhaiya**; assign passwords to them.
2. Change the user ID of **raju** to `4002`.
3. Change the user ID of **sham** to `4003`.
4. Create a group named **herapheri**.
5. Assign a password to the **herapheri** group.
6. Add **raju**, **sham**, and **babubhaiya** to the **herapheri** group.
7. Make **babubhaiya** the admin of the **herapheri** group.
8. Remove **sham** from the **herapheri** group.

---

## $${\color{purple}\textbf{Networking}}$$
### Subnetting Task
1. **IP Range:** `192.168.0.0/17` to `192.168.0.0/23`.  
   - **Tasks:**
     - Calculate the total number of networks.
     - Determine the number of hosts available per subnet.
     - List the subnet ranges for each subnet.

---

## $${\color{red}\textbf{Process Management}}$$
1. Terminate a specific process using its PID. Find the PID of a running process and use the `kill` command to terminate it.
2. Create a job and run it in the background.
3. Bring the background job back to the foreground.

---

## $${\color{brown}\textbf{Cron Jobs}}$$
1. Create a task to run **every Friday at 5 PM**.
2. Create a task to run **every 7 minutes**.
3. Create a task to run on **October 10th at 10:10 AM**.
4. Create a task to run **every 3 hours**.
5. Create a task to run **twice a day at 8 AM and 8 PM**.
6. Create a task to run **every Wednesday between the 1st and 15th of each month**.

---

## $${\color{cyan}\textbf{Web Hosting}}$$
1. Download a CSS template and host it using **Apache HTTPD**.

---

## $${\color{magenta}\textbf{File Permissions}}$$
1. Create a group named **hogwarts**.
2. Create three users: **harry**, **hermione**, and **ron**, and assign them to the **hogwarts** group.
3. Create a directory named `documents` in the root (`/`) directory.
4. Assign ownership of the `documents` directory to the **harry** user and the **hogwarts** group.
5. Set the permissions of the `documents` directory to `rwxr-x---` using `chmod`.
6. Ensure that only the owner (**harry**) can read, write, and execute within the directory, while members of the **hogwarts** group can only read and traverse (cd) into the directory.
7. Configure a `umask` value that ensures new files created within the `documents` directory have permissions `rw-r-----`.
8. Set an ACL on the `documents` directory to grant the **ron** user the ability to modify (write) files within the directory, even though they are not the owner.
9. As the **harry** user, create a sample document within the `documents` directory.
10. Verify that the **ron** user can modify the document.
11. Confirm that the **hermione** user cannot access the document.

---
