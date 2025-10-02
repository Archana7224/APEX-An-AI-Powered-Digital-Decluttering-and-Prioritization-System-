# 🤖 APEX
_Assess, Prioritize, Execute, Xclude_

A modern AI-powered digital decluttering prioritization system that helps users manage emails, social feeds, media, and notifications with intelligent prioritization, summarization, and cleanup features.

Our Mission: **Boost productivity, reduce digital clutter, and improve digital well-being while ensuring security and privacy.**

---

## 📖 Table of Contents

- [About](#about)
- [Features](#features)
  - [Email Management](#email-management)
  - [Social Media](#social-media)
    - [Twitter/X](#twitterx)
  - [Media Management](#media-management)
  - [Security & Privacy](#security--privacy)
  - [Wellness & Insights](#wellness--insights)
- [Dashboards](#dashboards--project-structure)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Team Members](#team-members)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [License](#license)

---

## 📝 About

**APEX - Declutter Prioritization System** is a smart productivity tool that integrates with multiple platforms including Gmail, Outlook, Instagram, Twitter (X), WhatsApp, and Gallery management.

Using advanced AI, NLP, and smart automation, APEX helps users focus on what truly matters by:

- 📌 Prioritizing urgent tasks and messages
- 🗂 Organizing cluttered feeds and media libraries
- 🌱 Providing wellness insights for digital balance
- 🔐 Ensuring top-notch security and privacy

---

## 🚀 Features

### 📩 Email Management

- **Intelligent Prioritization & Sentiment Analysis**: Flag top-priority messages based on content, sender reputation, and emotional tone analysis.
- **Email Summarization**: Condense long email threads and newsletters into concise, actionable summaries.
- **Smart Unsubscribe & Block Suggestions**: Proactively manage junk and promotional emails with AI-powered recommendations.
- **Thread Grouping & Conversation Clustering**: Automatically group related emails (e.g., "Project Submissions," "Order Confirmations").
- **Attachment Management & Cleanup**: Detect duplicate files, large attachments, and suggest cloud storage solutions.
- **Phishing & Malicious Link Detection**: Protect against malware, phishing attempts, and suspicious links.
- **Daily/Weekly Digest**: Receive summarized overviews of top-priority emails, deadlines, and upcoming meetings.

### 📸 Social Media

#### Instagram

- **Content Diet Coach**: Analyze consumed content types and generate detailed time breakdown reports.
- **Digital Detox Recommendations**: Detect excessive scrolling patterns and suggest timed breaks for better mental health.

#### Twitter/X

- **Intelligent Feed Curation**: Prioritize feed content based on user engagement history and relevance scores.
- **AI-Powered Thread Summarization**: Summarize long Twitter threads into actionable bullet points for quick consumption.

### 🖼 Media Management

- **Media Organization & Cleanup**: Automatically categorize images into screenshots, memes, receipts, selfies, or documents.
- **Space Optimization Suggestions**: Highlight duplicates, large files, or redundant downloads; suggest deletion or cloud backup.
- **Smart Highlights Protection**: Protect important images like tickets, IDs, bills, and certificates from accidental deletion.
- **Context-Aware Cleanup**: Set automated cleanup rules (e.g., delete old WhatsApp downloads after 30 days).

### 🔐 Security & Privacy

- **End-to-End Encryption**: All integrated data remains private and secure with industry-standard encryption.
- **JWT Authentication**: Secure login mechanism for managing multiple connected accounts.

### 🌱 Wellness & Insights

- **Weekly Declutter Report**: Track time saved, junk cleared, and content usage patterns with detailed analytics.

---

## 🗂 Dashboards & Project Structure

### Dashboard Features

| Dashboard         | Description                                                                                |
|-------------------|-------------------------------------------------------------------------------------------|
| 📧 Email Dashboard   | Prioritized inbox, summarization panel, attachment cleanup, digest overview                |
| 📱 Social Dashboard  | Instagram/X feed analytics, thread summarization, content diet insights                    |
| 🖼 Media Dashboard   | Cleanup suggestions, highlights protection, automated rules, space optimization            |
| 🔐 Security Dashboard| Account linking, encryption status, authentication settings                               |
| 🌱 Wellness Dashboard| Declutter report, productivity analytics, digital balance insights                         |

### Project Structure

```
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
```

---

## 🛠 Tech Stack

**Frontend:** React.js, Redux, CSS/Styled Components  
**Backend:** Node.js, Express.js, MongoDB  
**AI & ML:** Python, TensorFlow, OpenAI API  
**Security:** JWT, End-to-End Encryption

---

## ⚙️ Installation

### Prerequisites

- Node.js v18 or higher
- MongoDB installed and running
- npm or yarn package manager

### Steps

```bash
# Clone the repository
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
```

### Environment Variables

Create a `.env` file in the root directory with the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GMAIL_API_KEY=your_gmail_api_key
OUTLOOK_API_KEY=your_outlook_api_key
INSTAGRAM_API_KEY=your_instagram_api_key
TWITTER_API_KEY=your_twitter_api_key
```

---

## 💻 Usage

1. **Login to the Dashboard**  
   Access the application at [http://localhost:3000](http://localhost:3000) and create an account.

2. **Connect Your Accounts**  
   Link your Gmail, Outlook, Instagram, X (Twitter), WhatsApp, and other accounts securely.

3. **View Analytics**  
   Navigate through different dashboards to view:
   - Prioritized inbox
   - Clutter-free social feeds
   - Media cleanup suggestions
   - Weekly declutter reports

4. **Enable AI Recommendations**  
   Activate AI-powered suggestions for automated cleanup and digital detox reminders.

---

## 📸 Screenshots

> _Add actual screenshot images to your repository and update the paths below._

- Dashboard Overview
- Email Prioritization
- Media Cleanup

---

## 👥 Team Members

| Name             | Role                        | GitHub                |
|------------------|-----------------------------|-----------------------|
| Aaditya Kapoor   | Team Lead & Frontend Dev    | [@aaditya-kapoor](https://github.com/aaditya-kapoor) |
| Anshul Kushwaha  | Documentation & Presentation| [@anshul-kushwaha](https://github.com/anshul-kushwaha) |
| Aachal Patil     | UI/UX Designer              | [@aachal-patil](https://github.com/aachal-patil) |
| Archana Nair     | Backend Developer           | [@Archana7224](https://github.com/Archana7224) |

---

## 🌟 Future Scope

- 💬 **Expand Platform Support**: Integrate with Slack, LinkedIn, Telegram, and Discord.
- 📱 **Mobile Applications**: Launch native Android and iOS mobile apps for on-the-go management.
- 🤖 **AI Wellness Assistant**: Develop personalized habit tracking and recommendations based on usage patterns.
- 🔔 **Smart Notifications**: Context-aware notification management across all connected platforms.
- 📊 **Advanced Analytics**: Provide deeper insights into productivity patterns and digital behavior.

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the Repository**  
   Click the 'Fork' button at the top right of this page.

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit Your Changes**
   ```bash
   git commit -m "Add: your feature description"
   ```

4. **Push to Your Branch**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Submit a Pull Request**  
   Open a PR with a clear description of your changes.

**Contribution Guidelines**
- Follow the existing code style and conventions
- Write clear commit messages
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR

---

## 📜 License

This project is licensed under the MIT License – free to use, modify, and distribute.  
See the [LICENSE](LICENSE) file for more details.
