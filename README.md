# CodeBuddy
A powerful, real-time code review platform with AI-powered suggestions, inline comments, and live multi-user editing 


# Signup Wireframe
-----------------------------------------------------
|                  🔗 CodeBuddy                     |
|---------------------------------------------------|
|          [Login ◯]   [Signup ⬤]                   |
|---------------------------------------------------|
| 🙍‍♀️ Full Name:     _____________________          |
| 📧 Email:         _____________________           |
| 🔒 Password:      _____________________           |
| 🔒 Confirm Pass:  _____________________           |
|                                                   |
| [📝 Create Account]                                |
|---------------------------------------------------|
| 🧪 Or sign up with:                               |
|   [ Google ]  [ GitHub ]                          |
-----------------------------------------------------


# Signin 
-----------------------------------------------------
|                  🔗 CodeBuddy                     |
|---------------------------------------------------|
|          [Login ⬤]   [Signup ◯]                   |
|---------------------------------------------------|
| 📧 Email:         _____________________           |
| 🔒 Password:      _____________________           |
| (👁️ Show/Hide Password)                          |
|                                                   |
| ☐ Remember Me                                     |
|                                                   |
| [🔓 Login]                                         |
|                                                   |
| 🔁 Forgot Password?                               |
|---------------------------------------------------|
| 🧪 Or continue with:                              |
|   [ Google ]  [ GitHub ]                          |
-----------------------------------------------------

# dashboard

-----------------------------------------------------
| CodeBuddy              🔍 Search Projects       |
|---------------------------------------------------|
| + New Review Room      | 🔔 Notifications 🔽      |
|---------------------------------------------------|
| My Projects:                                      |
| - Frontend Refactor [🟢 Open]                     |
| - Backend API Auth [🔴 Closed]                    |
| - Data Layer Cleanup [🟡 In Review]               |
|---------------------------------------------------|
| Activity Feed:                                    |
| - Alice commented on “login.js” (2 mins ago)     |
| - Bob approved changes to “apiRoutes.js”         |
-----------------------------------------------------

# Code Review Room

-----------------------------------------------------
| ← Back   Project: Frontend Refactor             |
|---------------------------------------------------|
| Tabs: [Overview] [Code Editor] [Discussion]       |
|---------------------------------------------------|
| Participants: Alice 👩‍💻 | Bob 👨‍💻 | You            |
|---------------------------------------------------|
| ✅ Tasks:                                          |
| [ ] Fix login bug in login.js                    |
| [x] Refactor navbar for responsiveness           |
|---------------------------------------------------|
| Review Summary:                                  |
| - 7 files changed | 18 comments | 3 approvals     |
|---------------------------------------------------|
| 📄 Files Changed                                  |
| - login.js                                        |
| - navbar.jsx                                      |
| - utils/validator.js                              |
-----------------------------------------------------

# Code editor with inline comments

-----------------------------------------------------
| File: login.js                 [☁️ Save] [⇅ Diff] |
|---------------------------------------------------|
|  1: function loginUser() {                        |
|  2:   const email = getEmail();                   |
|  3:   // 🧵 Bob: This needs email validation       |
|  4:   const user = db.find(email);                |
|  5:   return user;                                |
|  6: }                                             |
|---------------------------------------------------|
| Add Comment Box (selected lines) [Post]          |
|-----------------------------------------------------|
| 💬 Comments Thread (Right Sidebar):              |
| - Bob: Add email format check                    |
| - You: Working on it now.                        |
-----------------------------------------------------

# Live chat and video panel

-----------------------------------------------------
| 👥 Review Room - Live Collaboration               |
|---------------------------------------------------|
| 🔴 Live Video [Mute] [Cam Off] [Leave]            |
|---------------------------------------------------|
| 💬 Chat:                                          |
| You: Can someone check utils.js line 34?         |
| Alice: On it!                                     |
| Bob: Let’s split the login fix into another PR.   |
-----------------------------------------------------

# Profile and Settings

-----------------------------------------------------
| 👤 Profile: Rutvi Sharma                         |
|---------------------------------------------------|
| Email: rutvi@codebuddy.io                        |
| Role: Reviewer / Contributor                     |
| Bio: Full-stack dev with interest in DX           |
|---------------------------------------------------|
| Preferences:                                     |
| - Dark Mode: ☐                                   |
| - Notification Settings [Edit]                   |
|-----------------------------------------------------|
| 🔧 Project Settings:                             |
| - Collaborators: Add/remove                      |
| - Default Branch: main                           |
| - Enable AI Suggestions: ✅                       |
-----------------------------------------------------

# Review Analytics

-----------------------------------------------------
| 📈 Project Review Metrics                         |
|---------------------------------------------------|
| ⏱ Avg Review Time: 6h 12m                        |
| 🧠 AI Suggestions Used: 14                        |
| 🧾 Comments per PR: Avg. 6.8                      |
| 🙋 Approvals: Alice (12), Bob (9), You (14)       |
|---------------------------------------------------|
| 🔍 Filters: [Last 7 days ⏷] [By Reviewer ⏷]       |
|-----------------------------------------------------|
| 📊 Bar Chart: Comments Per File Over Time        |
-----------------------------------------------------

