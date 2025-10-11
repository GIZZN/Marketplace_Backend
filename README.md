# 🛒 Marketplace_Backend - Build Your Own NFT Marketplace

## 🚀 Getting Started

Welcome to the Marketplace_Backend! This project is your gateway to creating and managing an NFT marketplace. It uses NestJS for the backend, combined with Prisma and PostgreSQL, making it a robust solution for anyone interested in NFTs.

## 📥 Download the Application

[![Download Marketplace_Backend](https://img.shields.io/badge/Download-Marketplace_Backend-brightgreen)](https://github.com/GIZZN/Marketplace_Backend/releases)

To begin, you need to visit the Releases page. This page contains the files you need to download and run the application.

[Download the latest release here](https://github.com/GIZZN/Marketplace_Backend/releases).

## 📦 Installation Instructions

Follow these steps to install and run the Marketplace_Backend on your system.

### 1. Visit the Releases Page

Go to [this link](https://github.com/GIZZN/Marketplace_Backend/releases) to see the available releases. You will find the latest version listed at the top. 

### 2. Download the Latest Release

Click on the version you want. It is usually labeled with a version number, such as `v1.0.0`. Within the release, look for the files under "Assets". Download the file appropriate for your operating system.

### 3. Extract the Files (if necessary)

If the downloaded file is a zip or tar file, you will need to extract it:

- **Windows:** Right-click on the file and select "Extract All".
- **Mac:** Double-click the file to extract it.
- **Linux:** Use the command line. Navigate to the downloaded file, and run:
  ```
  tar -xvf filename.tar.gz
  ```

### 4. Install Dependencies

Before running the software, you need to install Node.js and PostgreSQL on your computer. 

- **Node.js**: Download it from [nodejs.org](https://nodejs.org). Install it by following the provided instructions.
- **PostgreSQL**: Download it from [postgresql.org](https://www.postgresql.org). Follow the instructions to set it up.

After installing, open your command line interface and run the following command to install the necessary dependencies for the application:

```bash
npm install
```

### 5. Configure the Database

You need to set up a database for the application. 

1. Open PostgreSQL and create a new database called `nft_marketplace`.
2. Update your `.env` file (located in the project folder) with the database details:
   ```
   DATABASE_URL=postgresql://username:password@localhost:5432/nft_marketplace
   ```

Make sure to replace `username` and `password` with your PostgreSQL credentials.

### 6. Run Migrations

Run the following command in your command line:

```bash
npx prisma migrate deploy
```

This command sets up the necessary tables in your database.

### 7. Start the Application

Finally, to run the application, use:

```bash
npm run start
```

Once the application is running, you will see output indicating it is ready for use. 

## 🛠️ Features

- **User Authentication:** Users can sign up and log in securely.
- **NFT Collection Management:** Easily create, manage, and list NFTs.
- **Launchpad for New Collections:** Support new projects in launching their NFT collections.

## 📋 System Requirements

- **Operating System:** Windows, MacOS, or Linux.
- **Node.js:** Version 14.0 or later.
- **PostgreSQL:** Version 12.0 or later.

## 📧 Support

If you encounter any issues during installation or use, please reach out for help. You can open an issue directly on this repository, and someone from our community will assist you.

## 👥 Contributors

Marketplace_Backend is made possible by a community of contributors. If you would like to help improve this project, please visit the repository for more information.

## 🌐 Additional Resources

For more details on how to use NestJS, Prisma, or PostgreSQL, visit their official documentation:

- [NestJS Documentation](https://docs.nestjs.com)
- [Prisma Documentation](https://www.prisma.io/docs)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

Thank you for using Marketplace_Backend! We hope you enjoy building your NFT marketplace.