# baserun1
[![Windows Night Test](https://github.com/junghh21/baserun1/actions/workflows/main1.yml/badge.svg)](https://github.com/junghh21/baserun1/actions/workflows/main1.yml)

Setting up Node.js is super straightforward, and once it's installed, you're ready to build everything from web servers to command-line tools. Here's your quick-start guide,

🧩 Step 1: Download Node.js
Head to the official Node.js download page and choose the version that suits your needs:

LTS (Long-Term Support): Recommended for most users

Current: Has the latest features, but may be less stable

💻 Step 2: Install It
On Windows or macOS:
Download the installer (.msi for Windows, .pkg for macOS)

Run the installer and follow the prompts

Check the box to install additional tools (optional but useful)

On Linux:
Use a package manager like apt, yum, or nvm (Node Version Manager). Example with nvm:

bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
nvm install --lts
🔍 Step 3: Verify Installation
Open your terminal or command prompt and run:

bash
node -v
npm -v
You should see version numbers for both Node.js and npm (Node Package Manager).

🚀 Step 4: Run a Test Script
Create a file called test.js with this content:

javascript
console.log("Hello, Node.js!");
Then run it:

bash
node test.js
