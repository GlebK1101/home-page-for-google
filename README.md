# home-page-for-google
A personalized start page for organizing bookmarks. Organize links and notes into tables within tabs. Features: dark/light themes, auto-fetch YouTube titles, data export/import (JSON), and record editing. Works locally on LocalStorage without a server — just open the file in Chrome.

## A simple and convenient tool for organizing your bookmarks, links, and notes. Works locally in the browser, no servers or registration required.

### The Problem: "Tab Madness"
We've all been there: you open your browser, and there are 50 tabs staring back at you.
- "I'll read this article later."
- "I need to watch this video tonight."
- "I need this link for work next week."

**Result:** the browser lags, RAM is eaten up, and finding the right link in this mess is impossible. You're afraid to close a tab lest you lose it forever. *(Yes, I know about standard bookmarks, but this isn't about them).*

### The Solution
This project is a **single HTML file** that replaces your standard start page.
Instead of keeping a tab open, you simply copy the link here, add a note, and **close the tab with peace of mind**. All your links are neatly sorted into shelves (tabs), and your browser runs fast.

### Features
1. **Organization by Tabs**: Create categories (e.g., "Work", "YouTube", "Recipes", "Read Later").
2. **Smart Add**: Paste a YouTube link, and the video title fetches automatically.
3. **Privacy**: All data is stored *only* in your browser (LocalStorage). No data is sent to third-party servers.
4. **Customization**: Dark and Light themes, font size settings.
5. **Data Safety**: Export and Import all data to a JSON file (useful for transferring to another PC or creating a backup).
6. **No Installation**: Just download the file and open it in your browser.

### How to Run
1. Download the `index.html` file from this repository.
2. Open it in Google Chrome (or any other browser).
3. *(Recommended)* Go to browser settings *(three dots -> Appearance -> Show home button [On])* and set this file as your **Home Page**.

### Important: What You Need to Know
1. **Don't clear "Site Data" thoughtlessly**: If you decide to clear browser history and check *"Cookies and other site data"*, your records will be deleted.
2. **Incognito Mode**: If you open the file in Incognito mode, records made there will vanish immediately after closing the window.
3. **Different Browsers = Different Data**: If you open the file in Chrome, then in Firefox, you will see a blank page in Firefox. Data is tied to the specific browser.

### How to Keep Data Safe
The project has a built-in backup function:
1. Click the large gear icon (Settings).
2. Click "Export all to JSON".
3. Save the file to your computer.

*There is also a similar export function for each individual tab.*

Enjoy the order!
