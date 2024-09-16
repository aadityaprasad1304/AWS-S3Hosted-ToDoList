#AWS-S3Hosted-ToDoList
# [Just Do It](https://aws-cloud-da-draft1.s3.ap-south-1.amazonaws.com/index.html)

Click the link above to access the hosted "Just Do It" To-Do List WebApp on AWS S3.


## Overview
"Just Do It" is a dynamic and aesthetic To-Do List WebApp designed using HTML, CSS, and JavaScript. It allows users to add tasks, mark them as completed, delete them, and switch between different themes. The application is hosted on AWS S3 for easy access and scalability.

## Features
- **Add Tasks:** Enter tasks and add them to your to-do list.
- **Mark Completed:** Check tasks off as completed.
- **Delete Tasks:** Remove tasks from the list.
- **Theme Selection:** Choose between different themes (Standard, Light, Darker).

## Getting Started
To run this application locally or deploy it on AWS S3, follow these steps:

### Prerequisites
- Web browser (Google Chrome, Firefox, etc.)
- AWS account with access to S3 services

### Local Setup (Optional)
1. Clone the repository or download the files from [GitHub Repository URL].
2. Open `index.html` in your web browser.

### Deployment on AWS S3
#### Step 1: Create an AWS S3 Bucket
1. Log in to your AWS Management Console.
2. Go to the S3 service.
3. Click **Create bucket**.
4. Enter a unique bucket name and choose a region.
5. Click **Create bucket**.

#### Step 2: Upload Files to S3 Bucket
1. Select the bucket you created.
2. Click **Upload**.
3. Add all files (`index.html`, `main.css`, `main.js`, `time.js`, `assets/` folder) to the upload dialog.
4. Click **Upload**.

#### Step 3: Configure Bucket Permissions
1. Select the uploaded files in your S3 bucket.
2. Click **Actions > Make public** to allow public access.

#### Step 4: Enable Static Website Hosting
1. In your S3 bucket, go to **Properties**.
2. Scroll down to **Static website hosting** and click **Edit**.
3. Select **Use this bucket to host a website**.
4. Enter `index.html` as both the **Index document** and **Error document**.
5. Click **Save**.

#### Step 5: Access Your WebApp
1. In your S3 bucket's **Static website hosting** section, find the **Endpoint URL**.
2. Open this URL in your web browser to access your "Just Do It" To-Do List WebApp.

## Usage
- **Add Task:** Enter a task in the input field and click **I Got This!** or press Enter.
- **Mark Completed:** Click the check button next to a task to mark it as completed.
- **Delete Task:** Click the trash button next to a task to delete it.
- **Change Theme:** Click on one of the theme buttons (Standard, Light, Darker) to change the theme of the application.

## Customization
- **Modify Themes:** Edit `main.css` to change colors and styles for each theme (standard, light, darker).
- **Extend Functionality:** Update `main.js` to add new features or modify existing ones.

## Contributing
Contributions are welcome! Fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License.



