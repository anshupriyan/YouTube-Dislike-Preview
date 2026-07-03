# 📊 YT Dislike Preview

A lightweight Chrome Extension (Manifest V3) that displays like/dislike counts and ratios for YouTube videos.

## ✨ Features

* **Thumbnail Overlays:** Displays like/dislike counts directly on video thumbnails (home feed, search results, sidebar recommendations, channels, and playlists).
* **Watch Page Metrics:** Displays like/dislike counts on the watch page below the video description.
* **YouTube Shorts Integration:** Restores dislike counts on the YouTube Shorts sidebar action buttons.
* **Zero Configuration:** Works out-of-the-box using the public Return YouTube Dislike API.
* **Lightweight:** Built with vanilla JavaScript and CSS to minimize browser memory footprint.

## 🛠️ Installation (Developer Mode)

To load the extension locally during development:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/anshupriyan/YT-Dislike-Preview.git
   ```
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (toggle in the top-right corner).
4. Click **Load unpacked** (top-left corner).
5. Select the root folder containing the `manifest.json` file.

## ⚙️ How It Works

* **Content Script (`content.js`):** Injects dislike badges into YouTube's user interface.
* **Background Service Worker (`background.js`):** Interacts with the Return YouTube Dislike API and caches votes in-memory to prevent redundant network requests.

## 💬 Support This Project

* **Discord:** [Join the community](https://discord.gg/9DZxKzxuJc)
* **Buy Me a Chai:** [Support the project via Razorpay](https://razorpay.me/@anshupriyan)

## 📊 Attribution & Data Source

This project retrieves vote data using the public API provided by [Return YouTube Dislike](https://returnyoutubedislike.com/). 

## 🛡️ License

Distributed under the MIT License.
