# Assignment Backend (GitHub-ready)

This repository contains the backend portion of the assignment: a simple Node.js + Express API that serves a list of items and provides next/previous navigation endpoints.

## Files
- `data/items.js` - JS array of item objects (title, desc, img)
- `server.js` - Express server with endpoints
- `package.json` - dependencies and scripts
- `.gitignore` - files to ignore

## Installation (local)
1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the server:
   ```bash
   npm start
   ```
4. Open API endpoints in your browser or Postman:
   - http://localhost:3000/item
   - http://localhost:3000/item/next
   - http://localhost:3000/item/prev

## Notes for students
- Do not commit `node_modules`.
- You can edit `data/items.js` to replace sample content with your own topics and image links.
- Optional: Deploy to Render, Railway, or Heroku for a live demo link.

## Submission
- Push the `backend` folder to your GitHub repository and submit the repository link in Moodle.
- In the Moodle comment, include the full names of all group members.
