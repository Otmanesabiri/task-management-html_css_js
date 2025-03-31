# Student Task Manager

A responsive task management web application designed for students to organize their academic work efficiently.

![Student Task Manager Screenshot](screenshot.png)

## Features

- Add, edit, and delete tasks
- Mark tasks as complete
- Set priorities (low, medium, high)
- Assign due dates
- Categorize tasks (homework, exam prep, projects, etc.)
- Filter tasks by status, category, and priority
- Dark/light mode toggle
- Responsive design for all devices
- Data saved locally (works offline)

## Live Demo

Visit the live application: [https://[your-username].github.io/task_management/](https://[your-username].github.io/task_management/)

## Deployment Instructions

### How to deploy to GitHub Pages:

1. **Create a GitHub repository**:
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name your repository `task_management`
   - Make it public
   - Click "Create repository"

2. **Initialize Git and push your code**:
   ```bash
   # Navigate to your project folder
   cd /home/red/Documents/javaproject/task_management
   
   # Initialize Git
   git init
   
   # Add all files
   git add .
   
   # Commit your changes
   git commit -m "Initial commit"
   
   # Add the remote repository
   git remote add origin https://github.com/[your-username]/task_management.git
   
   # Push to GitHub
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "GitHub Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at `https://[your-username].github.io/task_management/`

## Local Development

To run this project locally, simply open the `index.html` file in a web browser.

## License

MIT © [Your Name]
