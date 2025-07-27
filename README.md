# Playlist App

This is a full-stack playlist management application with:

- **Frontend** built in React
- **Backend** deployed to AWS using AWS SAM and services such as Lambda, API Gateway, and DynamoDB

---

## 🔧 Tech Stack

### Frontend
- React
- Vite
- Axios or Fetch API

### Backend
- AWS Lambda (Node.js)
- API Gateway
- DynamoDB
- AWS SAM (for deployment)

---

## 🚀 Getting Started 

### 1. Clone the repository

```bash
git clone https://github.com/WITS2025/TuneOut
cd TuneOut
```

### 2. Setup Frontend
 *The app must be run on port 5173.*

```bash
cd TuneOut
npm install
npm run dev
```

### 3. Setup Backend
Ensure you have AWS CLI and AWS SAM CLI installed.

```bash
cd backend
sam build
sam deploy
```
This will deploy your Lambda functions and API Gateway endpoints.

### 4. Connect Frontend to Backend
In your frontend code, set your API base URL to the deployed API Gateway URL from the SAM deploy output.

## Authors
Hailey Lazar
Toby Meth
Rivka Chana Flig
Leah Feldman