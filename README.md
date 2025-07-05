# 🤖 Slack Bot with TypeScript

This is a simple Slack bot built using [Slack's Bolt framework](https://slack.dev/bolt-js/) and TypeScript. The bot responds to a custom `/hello` slash command and logs all messages from public channels.

---

## 📦 Features

- Responds to the `/hello` command
- Logs public messages from Slack channels
- Built using TypeScript with Node.js
- Uses `dotenv` for environment variable management

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/slack-bot-ts.git
cd slack-bot-ts
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Create a .env File

Create a .env file in the root of the project with this content:

```js
SLACK_BOT_TOKEN = xoxb - your - bot - token;
SLACK_SIGNING_SECRET = your - signing - secret;
PORT = 3000;
```

### 4. Use ngrok to Test Locally

To run the bot locally and make it accessible to Slack, use ngrok:

```bash
ngrok http 3000
```

### 5. Run the bot

```bash
node bot.ts
```

### 6. Test the bot

- Go to a channel where the bot is added
- Type /hello
- The bot should reply with a greeting
- All other messages will be logged in your terminal

### results

![slack bot](/src/screenshots/slack-bot.JPG)
![terminal results](/src/screenshots/terminal.JPG)
