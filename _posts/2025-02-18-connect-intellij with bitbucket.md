# How to Set Up a Bitbucket App Password in IntelliJ IDEA for Seamless Git Integration

## Step 1: Generate an App Password in Bitbucket
### Log in to Bitbucket:

Go to Bitbucket and log in to your account.
Access Your Account Settings:

Click on your profile avatar in the bottom left corner of the Bitbucket dashboard.
From the menu, select Personal settings.

![image](https://github.com/user-attachments/assets/0bbd665f-2df3-484f-9a9e-fc4e63a4e874)

### Create an App Password:

In the sidebar, select App passwords under the Access management section.
Click the Create app password button.

![image](https://github.com/user-attachments/assets/8fe79c2f-3240-4571-b907-42018ff60f04)

Give the app password a label (e.g., IntelliJ).
Select the appropriate permissions based on what you need. For most cases, the following permissions should suffice:
Read and Write permissions for repositories.
Account permissions for accessing your account.
Click Create.

![image](https://github.com/user-attachments/assets/fd8b0e54-2936-4a4d-a171-3a149069fffc)

### Copy the App Password:

After the app password is generated, copy the password. ***You won’t be able to see it again after you close the dialog.***

# Step 2: Configure Bitbucket in IntelliJ IDEA
Open IntelliJ IDEA:

Launch IntelliJ IDEA and open the project where you want to configure the Bitbucket repository.
Set Up Git in IntelliJ IDEA:

Go to File > Settings (on Windows/Linux) or IntelliJ IDEA > Preferences (on macOS).
Navigate to Version Control > Git.
Ensure that the Git executable path is set correctly (it should point to the Git executable on your system).
Test the connection by clicking Test.

![image](https://github.com/user-attachments/assets/5279ac46-0e1f-41d4-9104-fbf3c364ecb8)

### Add Your Bitbucket Repository:

In IntelliJ, go to VCS > Checkout from Version Control > Git.
Enter the Bitbucket repository URL in the format:

### Configure Authentication:

When you attempt to clone the repository, IntelliJ will prompt you for your username and password.
Use your Bitbucket username as the username.
For the password, paste the app password that you generated earlier (instead of your regular Bitbucket password).
Enable Git Credential Helper (Optional):

To avoid entering your app password each time, enable the Git credential helper to store the credentials.
In the terminal, run:

![image](https://github.com/user-attachments/assets/1cb4b6b4-41ed-43f6-9e6e-524c2e31d871)

Alternatively, you can use a Git credential manager for your operating system (e.g., Git Credential Manager for Windows or macOS Keychain).
OR
you can use git bash to perform clone option 

![image](https://github.com/user-attachments/assets/79ad3c96-9f2c-4269-9238-b32d4cb6fb7f)

# Step 3: Test the Setup
Perform Git Operations:
Try to pull or push to your Bitbucket repository from IntelliJ IDEA.
**If configured correctly, IntelliJ will use the app password for authentication.**

By following these steps, you'll set up a Bitbucket app password for IntelliJ IDEA, allowing you to securely interact with your Bitbucket repositories without using your main Bitbucket password.
