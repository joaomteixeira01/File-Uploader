# FileUploader
This project is a web application built with .NET and Angular, allowing users to upload files securely for real-time analysis. Uploaded files are sent to Kaspersky antivirus for scanning before being securely transmitted to a designated IP address using SSL encryption. The system supports multiple file uploads and ensures end-to-end security throughout the process.

## Key Features:
- **File Upload:** Users can select and upload multiple files simultaneously.
- **File Preview:** Displays a list of selected files before uploading.
- **File Management:** Options to cancel the selection or remove the last selected file.
- **Secure Upload:** Implements SSL certificates for secure file transmission to the server.
- **Kaspersky Integration:** Uploaded files are scanned by the Kaspersky Scan Engine before acceptance.
- **Database Integration:** Stores details of uploaded files including file name, file path, and upload time in a database.
- **Error Handling:** Provides feedback on upload success or failure with options to retry on failure.

## Technologies Used:
- **Backend:** ASP.NET Core
- **Frontend:** Angular
- **Database:** SQLite
- **HTTP Client:** Handles file upload requests and SSL configuration

## Setup Instructions:
### 1. Build and Run the Backend:
- Navigate to the API directory: `cd API`
- Run the application: `dotnet run`
```sh
dotnet restore
dotnet run
```

### 2. Build and Run the Frontend:
- Navigate to the client directory: `cd client`
- Install dependencies: `npm install`
- Run the application: `ng serve`
```sh
cd client
npm install
ng serve
```

### 3. Open the Application
Open your browser and navigate to:
```
http://localhost:4200
```
