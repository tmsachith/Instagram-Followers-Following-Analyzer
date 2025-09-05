# Instagram Follower Analyzer

A web-based tool to analyze your Instagram followers and following data to identify accounts that don't follow you back.

## Features

- 📊 **Follower Analysis**: View all your followers with timestamps
- 👥 **Following Analysis**: View all accounts you follow with timestamps  
- 🔍 **Not Following Back**: Identify accounts you follow that don't follow you back
- 🌙 **Dark Mode**: Toggle between light and dark themes
- 🔎 **Search Functionality**: Search through your lists easily
- 📱 **Responsive Design**: Works on desktop and mobile devices

## How to Use

1. **Download Your Instagram Data**:
   - Go to Instagram → Settings → Privacy and Security → Data Download
   - OR use Instagram's "Download Your Information" feature in Account Center
   - Request a download of your account information
   - Wait for Instagram to prepare your data (this can take a few hours to days)

2. **Extract the Files**:
   - Download the zip file Instagram sends you
   - Extract the contents
   - Look for HTML files named `followers_1.html`, `following.html`, or similar

3. **Use the Analyzer**:
   - Open `index.html` in your web browser
   - Upload your followers HTML file
   - Upload your following HTML file  
   - Click "Analyze" to see the results

## File Structure

- `index.html` - Main application file
- `README.md` - This file

## Technical Details

The application uses pure HTML, CSS, and JavaScript with:
- Bootstrap 5 for styling
- Font Awesome for icons
- Native File API for reading HTML files
- DOM parsing to extract username and timestamp data

## Supported Format

This tool works with the latest Instagram data export format (2024-2025) which includes:
- HTML files with space-separated CSS classes
- Username links pointing to Instagram profiles
- Timestamp information for follow/unfollow dates

## Privacy

- ✅ All processing happens locally in your browser
- ✅ No data is sent to any servers
- ✅ Your Instagram data remains private
- ✅ No login or authentication required

## Browser Compatibility

Works with all modern browsers including:
- Chrome/Edge 80+
- Firefox 75+
- Safari 13+