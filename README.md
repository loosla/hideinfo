# secureFile

Desktop Application to Encrypt and Decrypt Text in a file with the Password

![Screenshot from 2024-06-09 17-07-02](https://github.com/loosla/secureFile/assets/12526985/ac92fb18-39a1-4d38-828d-4c96551c3070)

## Requirements

To run this application, you need to have the following installed on your system:

1. **Node.js and npm**

   - [Download and install Node.js](https://nodejs.org/)

2. **Go**
   - go version 1.21+
   - [Download and install Go](https://golang.org/dl/)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/loosla/secureFile.git
cd secureFile
```

### 2. Install Dependencies for React App

```bash
cd frontend
npm install
```

### 3. Build and Start the React App

```bash
npm run build
npm start
```

### 4. Install Dependencies for Electron

Navigate back to the root directory and install Electron:

```bash
cd ..
npm install
```

### 5. Start the Go Backend

Navigate to the root directory and start the Go server:

```bash
go run .
```

### 6. Start the Electron App

Navigate back to the root directory and start the Electron app:

```bash
cd ..
npm start
```

## To start the application locally (old)

Run Frontend

1. cd secureFile/frontend
1. npm install
1. npm start

Run Backend

1. cd secureFile
1. go run .

Run Electron

1. cd secureFile
1. npm install
1. npm start

# TODO
1. Remove files that shouldn't be here
1. Reorganize go files
1. Renaming BE
1. Add tests
1. Describe how to use (add screen, video)
1. Add config for host, port to share between BE and FE

