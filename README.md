# Cloud Task Tracker

A simple web application built to help users manage their tasks, store them in the browser's local storage, and view motivational quotes. This app is designed to be deployed on a cloud-agnostic platform and is currently hosted on **GitHub Pages**.

## Live Demo

You can access the live application hosted on GitHub Pages by visiting the following URL:  
https://aarthi-ravichandran.github.io/Take-Home-Test1/

## Features
- **Task Management**: Users can add, view, and remove tasks.
- **Motivational Quotes**: Displays a random quote each time the page loads.
- **Local Storage**: Tasks are stored in the browser’s local storage, making them persistent even after page refreshes.
- **Responsive Design**: The application is mobile-friendly and can be accessed from both desktop and mobile devices.

## Technologies Used
- **HTML**: The structure and layout of the web page.
- **CSS**: Used for styling and layout of the application.
- **JavaScript**: Handles task management functionality, random quote generation, and interaction with local storage.
- **GitHub Pages**: Hosting platform for serving the static web application.

## Deployment Instructions

### Step 1: Push Code to GitHub

1. **Create a GitHub Repository**:
   - Create a new public repository on GitHub. You can name it `cloud-task-tracker` or something similar.
   
2. **Push Your Code**:
   - Open Git Bash or any terminal of your choice and navigate to the root directory of your project.
   - Initialize Git if it’s not already initialized:
   
     git init
    
   - Add all files to Git:
     
     git add .

   - Commit your changes:
   
     git commit -m "Initial commit"
  
   - Link your local repository to the GitHub repository:
   
     git remote add origin https://github.com/Aarthi-Ravichandran/Take-Home-Test1.git
  
   - Push your code to GitHub:
   
     git push -u origin main
    
   - After pushing, your code will be live on GitHub.

### Step 2: Set Up GitHub Pages for Deployment

1. **Go to Repository Settings**:
   - Open your repository on GitHub.
   - Click on the **Settings** tab.

2. **Enable GitHub Pages**:
   - Scroll down to the **GitHub Pages** section.
   - In the **Source** dropdown, select `main` branch (or the branch that contains your code).
   - Click **Save**.

3. **Access Your Live Application**:
   - GitHub Pages will automatically deploy your app, and it will be available at the following URL:

     https://aarthi-ravichandran.github.io/Take-Home-Test1/
    

   This URL can now be shared with anyone to access the live version of the app.

---

## How to Run the Application Locally

If you would like to run the application locally on your machine, follow these instructions:

### Step 1: Clone the Repository

1. Open your terminal or Git Bash.
2. Clone the repository to your local machine by running the following command:

   git clone https://github.com/Aarthi-Ravichandran/Take-Home-Test1.git

3. Navigate to the project directory:
   cd Take-Home-Test1

   Since the app is static, you don’t need a server. You can simply open the index.html file directly in your browser.


### Conclusion:
This Cloud Task Tracker app demonstrates a simple, cloud-agnostic design that can be easily deployed using GitHub Pages. The application is fully front-end based, allowing for easy setup and scaling without needing a server or complex infrastructure. By using open-source technologies like HTML, CSS, and JavaScript, I have built a lightweight solution for task management that leverages local storage for persistence.


