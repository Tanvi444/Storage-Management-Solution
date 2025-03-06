# Storage and File Sharing Platform

A storage management and file sharing platform that lets users effortlessly upload, organize, and share files. Built with the latest Next.js 15 and the Appwrite Node SDK, utilizing advanced features for seamless file management.

## Set Up Environment Variables

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

Replace the values with your actual Appwrite credentials. Obtain these credentials by signing up &
creating a new project on the [Appwrite website](https://appwrite.io/).
