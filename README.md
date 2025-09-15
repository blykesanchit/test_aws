# Simple Node.js Backend for AWS EC2

## Setup Instructions

1. **Install Node.js** (if not already installed)
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run the server:**
   ```bash
   npm start
   ```
4. **Test the API:**
   - Open your browser or use curl:
     ```bash
     curl http://localhost:3000/health
     ```
   - You should get `{ "status": "ok" }` as a response.

## Notes
- The server listens on port 3000 by default. Set the `PORT` environment variable to change it.
- Ready to deploy and test on AWS EC2.
