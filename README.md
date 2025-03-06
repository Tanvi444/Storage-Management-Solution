# Storage and File Sharing Platform

A storage management and file sharing platform that lets users effortlessly upload, organize, and share files. Built with the latest Next.js 15 and the Appwrite Node SDK, utilizing advanced features for seamless file management.

## ⚙️ Tech Stack

![reactjs](https://img.shields.io/badge/-React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![nextdotjs](https://img.shields.io/badge/-Next.JS_15-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000)
![appwrite](https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E)
![tailwindcss](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4)
![shadcn](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![typescript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6)

## 🔋 Features

👉 User Authentication with Appwrite: Signup, login, and logout functionality using Appwrite's authentication system.

👉 **FIle Uploads**: Effortlessly upload a variety of file types, including documents, images, videos, and audio, ensuring all your important data.

👉 **View and Manage Files**: Users can browse through their uploaded files stored in Appwrite storage, view on a new tab, rename file or delete.

👉 **Download Files**: Users can download their uploaded files giving them instant access to essential documents.

👉 **File Sharing**: Users can easily share their uploaded files with others, enabling collaboration and easy access to important content.

👉 **Dashboard**: Gain insights at a glance with a dynamic dashboard that showcases total and consumed storage, recent uploads, and a summary of files grouped by type.

👉 **Global Search**: Users can quickly find files and shared content across the platform with a robust global search feature.

👉 **Sorting Options**: Organize files efficiently by sorting them by date, name, or size, making file management a breeze.

👉 **Modern Responsive Design**: A fresh and minimalist UI that emphasizes usability, ensuring a clean aesthetic across all devices.

## 🤸 Getting Started

Follow these steps to set up the project locally on your machine.

1. **Cloning the Repository**
  
    ```bash
    # using HTTP
    git clone https://github.com/Tanvi444/Storage-Management-Solution.git
    
    # using SSH
    git clone git@github.com:Tanvi444/Storage-Management-Solution.git
    
    cd storage_management_solution
    ```

2. **Installation**

   Install the project dependencies using npm:

    ```bash
    # using NPM
    npm install --save

    # using YARN
    yarn
    ```

3. **Set Up Environment Variables**

   Create a new file named `.env.local` in the root of your project and add the following content:
    
    ```bash
    NEXT_PUBLIC_APPWRITE_ENDPOINT = "https://cloud.appwrite.io/v1"
    NEXT_PUBLIC_APPWRITE_PROJECT = "<your-appwrite-project-id>"
    NEXT_PUBLIC_APPWRITE_DATABASE = "<your-appwrite-database-id>"
    NEXT_PUBLIC_APPWRITE_USERS_COLLECTION = "<your-appwrite-users-collection-id>"
    NEXT_PUBLIC_APPWRITE_FILES_COLLECTION = "<your-appwrite-files-collection-id>"
    NEXT_PUBLIC_APPWRITE_BUCKET = "<your-appwrite-storage-bucket-id>"
    NEXT_APPWRITE_KEY = "<your-appwrite-api-key>"
    ```
    
    Replace the values with your actual Appwrite credentials. Obtain these credentials by signing up & creating a new project on the [Appwrite website](https://appwrite.io/).

4. **Running the Project**

    ```bash
    # using NPM
    npm run dev
    
    # using YARN
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
