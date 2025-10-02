🤖 APEX
Assess, Prioritize, Execute, Xclude
Show Image
Show Image
Show Image

A modern AI-powered digital decluttering prioritization system that helps users manage emails, social feeds, media, and notifications with intelligent prioritization, summarization, and cleanup features.

Our Mission: Boost productivity, reduce digital clutter, and improve digital well-being while ensuring security and privacy.

📖 Table of Contents

About
Features

Email Management
Social Media
Twitter/X
Media Management
Security & Privacy
Wellness & Insights


Dashboards
Tech Stack
Installation
Usage
Screenshots
Team Members
Future Scope
Contributing
License


📝 About
APEX - Declutter Prioritization System is a smart productivity tool that integrates with multiple platforms including Gmail, Outlook, Instagram, Twitter (X), WhatsApp, and Gallery management.
Using advanced AI, NLP, and smart automation, APEX helps users focus on what truly matters by:

📌 Prioritizing urgent tasks and messages
🗂 Organizing cluttered feeds and media libraries
🌱 Providing wellness insights for digital balance
🔐 Ensuring top-notch security and privacy


🚀 Features
📩 Gmail & Outlook

⚡ Intelligent Prioritization & Sentiment Analysis
Flag top-priority messages based on content, sender reputation, and emotional tone analysis.
📰 Email Summarization
Condense long email threads and newsletters into concise, actionable summaries.
🚫 Smart Unsubscribe & Block Suggestions
Proactively manage junk and promotional emails with AI-powered recommendations.
🧩 Thread Grouping & Conversation Clustering
Automatically group related emails (e.g., "Project Submissions," "Order Confirmations").
📎 Attachment Management & Cleanup
Detect duplicate files, large attachments, and suggest cloud storage solutions.
🛡 Phishing & Malicious Link Detection
Protect against malware, phishing attempts, and suspicious links.
🗓 Daily/Weekly Digest
Receive summarized overviews of top-priority emails, deadlines, and upcoming meetings.


📸 Instagram

📊 Content Diet Coach
Analyze consumed content types and generate detailed time breakdown reports.
⏸ Digital Detox Recommendations
Detect excessive scrolling patterns and suggest timed breaks for better mental health.


🐦 X (Twitter)

🎯 Intelligent Feed Curation
Prioritize feed content based on user engagement history and relevance scores.
✍️ AI-Powered Thread Summarization
Summarize long Twitter threads into actionable bullet points for quick consumption.


🖼 Gallery (WhatsApp/Downloads/Camera Roll)

🗃 Media Organization & Cleanup
Automatically categorize images into screenshots, memes, receipts, selfies, or documents.
💾 Space Optimization Suggestions
Highlight duplicates, large files, or redundant downloads; suggest deletion or cloud backup.
🔒 Smart Highlights Protection
Protect important images like tickets, IDs, bills, and certificates from accidental deletion.
🗑 Context-Aware Cleanup
Set automated cleanup rules (e.g., delete old WhatsApp downloads after 30 days).


🔐 Security & Privacy

🔑 End-to-End Encryption
All integrated data remains private and secure with industry-standard encryption.
🛡 JWT Authentication
Secure login mechanism for managing multiple connected accounts.


🌱 Wellness & Insights

📈 Weekly Declutter Report
Track time saved, junk cleared, and content usage patterns with detailed analytics.


🗂 Dashboards & Project Structure
Dashboard Features
DashboardDescription📧 Email DashboardPrioritized inbox, summarization panel, attachment cleanup, digest overview📱 Social DashboardInstagram/X feed analytics, thread summarization, content diet insights🖼 Media DashboardGallery/WhatsApp media categorization, duplicate detection, smart highlight protection📊 Wellness DashboardWeekly/monthly digital usage insights, detox suggestions, productivity metrics🔐 Security PanelPhishing alerts, suspicious links detection, account privacy overview
Project Structure
declutter-prioritization/
│
├─ backend/
│   ├─ controllers/          # Business logic handlers
│   ├─ models/               # Database schemas
│   ├─ routes/               # API route definitions
│   ├─ utils/                # Helper functions
│   └─ server.js             # Express server entry point
│
├─ frontend/
│   ├─ components/           # Reusable React components
│   ├─ pages/                # Page-level components
│   ├─ styles/               # CSS/styling files
│   └─ App.js                # Main React application
│
├─ scripts/
│   └─ setupAI.js            # AI model initialization
│
├─ config/
│   └─ db.js                 # Database configuration
│
├─ .env                      # Environment variables
├─ package.json              # Project dependencies
└─ README.md                 # Project documentation

🛠 Tech Stack
Frontend
Show Image
Show Image
Show Image
Backend
Show Image
Show Image
Show Image
AI & ML
Show Image
Show Image
Show Image
Security
Show Image
Show Image

⚙️ Installation
Prerequisites

Node.js v18 or higher
MongoDB installed and running
npm or yarn package manager

Steps
bash# Clone the repository
git clone https://github.com/Archana7224/APEX-An-AI-Powered-Digital-Decluttering-and-Prioritization-System-.git

# Navigate to project directory
cd APEX-An-AI-Powered-Digital-Decluttering-and-Prioritization-System-

# Install dependencies
npm install

# Create .env file and configure environment variables
cp .env.example .env

# Run database migrations (if applicable)
npm run migrate

# Start the development server
npm run dev
Environment Variables
Create a .env file in the root directory with the following:
envPORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GMAIL_API_KEY=your_gmail_api_key
OUTLOOK_API_KEY=your_outlook_api_key
INSTAGRAM_API_KEY=your_instagram_api_key
TWITTER_API_KEY=your_twitter_api_key

💻 Usage

Login to the Dashboard
Access the application at http://localhost:3000 and create an account.
Connect Your Accounts
Link your Gmail, Outlook, Instagram, X (Twitter), WhatsApp, and other accounts securely.
View Analytics
Navigate through different dashboards to view:

Prioritized inbox
Clutter-free social feeds
Media cleanup suggestions
Weekly declutter reports


Enable AI Recommendations
Activate AI-powered suggestions for automated cleanup and digital detox reminders.


📸 Screenshots
Dashboard Overview
Show Image
Email Prioritization
Show Image
Media Cleanup
Show Image

Note: Add actual screenshot images to your repository and update the paths above.


👥 Team Members
NameRoleGitHubAaditya KapoorTeam Lead & Frontend Developer@aaditya-kapoorAnshul KushwahaDocumentation & Presentation@anshul-kushwahaAachal PatilUI/UX Designer@aachal-patilArchana NairBackend Developer@Archana7224

🌟 Future Scope

💬 Expand Platform Support
Integrate with Slack, LinkedIn, Telegram, and Discord.
📱 Mobile Applications
Launch native Android and iOS mobile apps for on-the-go management.
🤖 AI Wellness Assistant
Develop personalized habit tracking and recommendations based on usage patterns.
🔔 Smart Notifications
Context-aware notification management across all connected platforms.
📊 Advanced Analytics
Provide deeper insights into productivity patterns and digital behavior.


🤝 Contributing
We welcome contributions from the community! Here's how you can help:

Fork the Repository
Click the 'Fork' button at the top right of this page.
Create a Feature Branch

bash   git checkout -b feature/your-feature-name

Commit Your Changes

bash   git commit -m "Add: your feature description"

Push to Your Branch

bash   git push origin feature/your-feature-name

Submit a Pull Request
Open a PR with a clear description of your changes.

Contribution Guidelines

Follow the existing code style and conventions
Write clear commit messages
Add tests for new features
Update documentation as needed
Ensure all tests pass before submitting PR


📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.
See the LICENSE file for more details.
