**User Management Script README**

**Description:**
This bash script provides basic functionalities for user and group management on a Unix-based operating system. It allows users to add, delete, and modify both users and groups, as well as list all available users.

**Features:**
1. **Add User:** Allows the addition of a new user by providing a username and setting a password.
2. **Delete User:** Enables the removal of an existing user, including the deletion of their home directory.
3. **Add Group:** Facilitates the creation of a new group.
4. **Delete Group:** Allows the deletion of an existing group.
5. **List Users:** Displays a list of all available users.
6. **Modify User or Group:** Provides options to modify either a user or a group, including renaming them.

**How to Use:**
1. **Running the Script:**
   - Execute the script by running the `user_management.sh` file in a Unix-based terminal.
   - Upon execution, the script presents a menu of options for user and group management.

2. **Options:**
   - Choose an option by entering the corresponding number:
     - `1`: Add User
     - `2`: Delete User
     - `3`: Add Group
     - `4`: Remove Group
     - `5`: List all Users
     - `6`: Modify User or Group

3. **Adding a User:**
   - Select option `1`.
   - Enter the desired username when prompted.
   - Set a password for the new user when prompted.

4. **Deleting a User:**
   - Select option `2`.
   - Enter the username of the user you want to delete when prompted.

5. **Adding a Group:**
   - Select option `3`.
   - Enter the name of the new group when prompted.

6. **Removing a Group:**
   - Select option `4`.
   - Enter the name of the group you want to delete when prompted.

7. **Listing Users:**
   - Select option `5`.
   - A list of all available users will be displayed.

8. **Modifying User or Group:**
   - Select option `6`.
   - Choose whether to modify a user or a group by entering `a` for user or `b` for group.
   - Follow the prompts to enter the old name and the new name.

**Note:**
- Ensure the script is executed with appropriate permissions (e.g., using `sudo` if required) to perform user and group management tasks effectively.
- Exercise caution when deleting users or groups, as this action cannot be undone, and it may affect system functionality and data integrity.

This script provides basic functionalities for user and group management and can be extended or customized as needed based on specific system requirements.
