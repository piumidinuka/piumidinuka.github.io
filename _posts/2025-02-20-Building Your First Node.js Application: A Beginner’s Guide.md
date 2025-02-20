Starting a basic Node.js project is simple and a great way to get familiar with the Node.js runtime.\
Below is a step-by-step guide to help you create a simple Node.js project,\
which can be expanded upon as you gain more experience.

# Step 1: Install Node.js and npm

If you haven't installed Node.js and npm (Node Package Manager) yet, you can download and install the latest version from [Node.js Official Website](https://nodejs.org/en).

To check if you have Node.js installed, run the following commands in your terminal:

![image](https://github.com/user-attachments/assets/41b56a12-0c52-4943-b667-de090f03fb1a)

This will display the version of Node.js and npm installed. If you see the version numbers, you're all set!

# Step 2: Initialize the Project

**Create a New Folder for Your Project:**

![image](https://github.com/user-attachments/assets/adc5d081-61e6-4003-bd0b-9ae5164281cb)

**2. Initialize the Project with npm: Inside your project folder, initialize a new Node.js project with the following command:**

![image](https://github.com/user-attachments/assets/bf18767f-7918-4be5-8219-3cfd795c9376)

This will create a package.json file with default values. This file is essential for managing project dependencies, scripts, and other settings.

# Step 3: Create the server.js File

**1. Inside your project folder, create a file called server.js:**

![image](https://github.com/user-attachments/assets/41d3b211-a04a-48ef-8c80-6b0cadcbb21a)

**2.Open the server.js file in your preferred text editor (VSCode, Sublime Text, etc.), and add the following code to create a basic HTTP server:**

![image](https://github.com/user-attachments/assets/5180786f-2b46-483c-920f-5debef09bd90)

# Step 4: Run the Server

**1. In the terminal, run your server.js file using the following command:**

![image](https://github.com/user-attachments/assets/92b71eba-f191-42ef-8045-4fd4ea46fa1c)

**2.You should see the message:**

![image](https://github.com/user-attachments/assets/d2eb7008-a7bb-489c-9d18-0af1f1d3ba71)

**3. Open your browser and go to http://127.0.0.1:3000/. You should see the message "Hello, World!" displayed on the page.**

# Step 5: Add More Functionality (Optional)
You can extend the project by adding routing, handling different HTTP methods, or using frameworks like ***Express.js***.

**Example: Adding Routing with Express.js**

**1. First, install the Express.js package:**

![image](https://github.com/user-attachments/assets/e7021bca-e110-443a-b6ca-3ca3d47e2613)

**2. Modify the server.js to use Express.js for routing:**

![image](https://github.com/user-attachments/assets/3d6895c2-50be-42bb-837f-fce90b38cba9)

**3. Run your application again with node server.js and visit http://127.0.0.1:3000/about to see the "About" page.**

# Step 6: Use Nodemon for Development (Optional)

To make development easier, you can use Nodemon, which automatically restarts your server when you make changes to your code.

**1. Install Nodemon as a development dependency**

![image](https://github.com/user-attachments/assets/8ab095ae-ecd8-4222-a396-32c70dbae5e5)

**2. Modify your package.json file to add a script for running your server with Nodemon:**

![image](https://github.com/user-attachments/assets/431a5887-2aab-4b30-9461-87da2e2ebf12)

**3. Now you can start your server with:**

![image](https://github.com/user-attachments/assets/6b69ffe5-c5b7-4cb9-bb53-6c7e83db742f)

# Conclusion

You've now set up a basic Node.js project! Here's a recap of what we did:

+ **Initialized the project** using npm.
+ **Created a basic HTTP server** with Node.js.
+ **Optionally extended** the project using Express.js for routing.
+ **Used Nodemon** for easier development.

As you continue to explore Node.js, you can build more complex applications by adding databases, authentication, error handling, and more.\
***Happy coding!***

You can download the repository from here [Building Your First Node.js Application: A Beginner’s Guide](https://github.com/piumidinuka/my-first-node-prj.git).





