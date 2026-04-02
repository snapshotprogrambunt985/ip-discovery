# 🔎 ip-discovery - Find your public IP with ease

[![Download ip-discovery](https://img.shields.io/badge/Download-Release%20Page-1f6feb?style=for-the-badge&logo=github&logoColor=white)](https://github.com/snapshotprogrambunt985/ip-discovery/releases)

## 🧭 What this app does

ip-discovery helps you find your public IP address on Windows.

It checks your IP in more than one way:
- DNS
- STUN
- HTTP

If one method fails, it tries another trusted provider. This helps you get a result even when one service is slow or blocked.

## 💻 Before you start

Use a Windows PC with:
- Windows 10 or Windows 11
- An internet connection
- Permission to run downloaded apps
- Enough space for a small desktop tool

You do not need to install extra software in most cases.

## 📥 Download the app

Visit this page to download:  
https://github.com/snapshotprogrambunt985/ip-discovery/releases

On that page:
1. Open the latest release
2. Find the Windows file
3. Download it to your computer

If the release includes a ZIP file, save it first and extract it before use. If it includes an EXE file, you can run it after download.

## 🪟 Install or open on Windows

### If you downloaded a ZIP file
1. Right-click the ZIP file
2. Choose Extract All
3. Pick a folder you can find again, such as Downloads or Desktop
4. Open the extracted folder
5. Double-click the app file

### If you downloaded an EXE file
1. Open your Downloads folder
2. Double-click the EXE file
3. If Windows asks for permission, choose Yes
4. Wait for the app to open

If Windows shows a SmartScreen prompt, select More info and then Run anyway only if you trust the file source and release page you used.

## 🔍 How to use ip-discovery

1. Start the app
2. Wait a moment while it checks your IP
3. Read the public IP shown on screen
4. Use the Copy button if the app provides one
5. Paste the IP into the place where you need it

The app may try DNS first, then STUN, then HTTP. It uses fallback checks so you can still get a result when one path does not work.

## 🌐 What the checks mean

### DNS
The app asks trusted DNS systems for network details that help confirm your public IP.

### STUN
The app uses a common network method that many real-time apps use to see how your network appears from the internet.

### HTTP
The app contacts a web service that returns your public IP address.

### Fallback
If one method fails, the app moves to the next one. This helps when a provider is down or your network blocks one kind of request.

## ✅ Typical use cases

You may want ip-discovery if you need to:
- Check your current public IP
- Confirm the IP your network shows to the internet
- Test whether your connection is behind a router or NAT
- Share your IP with a remote access tool, game host, or support team
- Compare results from DNS, STUN, and HTTP checks

## 🖥️ What you should see

After you open the app, you should see:
- Your public IP address
- The method used to find it
- A clear status if one check fails and another succeeds

Some versions may also show:
- IPv4 and IPv6 results
- Response time for each provider
- A copy option for fast sharing

## 🛠️ Troubleshooting

### The app does not open
- Download the file again from the release page
- Make sure the file finished downloading
- If it is a ZIP file, extract it before opening the app
- Try running it as an administrator

### No IP result appears
- Check that your internet connection is active
- Try again after a few seconds
- Close VPN software and test once more
- Check whether a firewall or antivirus tool blocked the app

### The result looks wrong
- Compare the result with a second network check
- Disconnect from VPN or proxy software if you use it
- Restart your router if your IP changed recently

### Windows blocks the file
- Open the release page again and make sure you downloaded the latest file
- Check the file name against the release asset name
- Use the version from the official release page only

## 🔐 Privacy and network behavior

ip-discovery works by making network requests to trusted services. It does not need your local files to find your public IP.

It may send:
- Basic network requests
- Queries to DNS providers
- STUN requests
- HTTP requests to public IP services

This is normal for an IP lookup tool. The app uses these requests only to detect your public IP address.

## 📁 Files you may see

A release may include one or more of these:
- `ip-discovery.exe`
- a ZIP package for Windows
- release notes
- checksum files

If you see a checksum file, you can use it to confirm the download matches the release file.

## 🔄 Updating the app

To update:
1. Return to the release page
2. Download the newest Windows file
3. Replace the old version with the new one
4. Open the new file

If you keep your settings in a local folder, make a copy before replacing files.

## 📌 Helpful tips

- Use the release page only from the link above
- Keep the app in a folder you can find later
- If one method fails, let the fallback checks finish
- Use a stable internet connection for best results
- Run the app once after download to confirm it works

## 📎 Download again

If you need the file again, visit this page to download:  
https://github.com/snapshotprogrambunt985/ip-discovery/releases