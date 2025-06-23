# This file contains documentation for the INTERPOL identity card generator project.

This is a professional INTERPOL identity card generator with a QR code that links to the exact HTML file content. The application allows users to generate official-looking INTERPOL agent credentials with security features.

![INTERPOL Identity Card](screenshot.png)

## Features

- Professional INTERPOL-themed interface
- Form to input agent details
- Real-time ID card generation
- Barcode for agent credentials
- QR code that points to the raw HTML file content
- Responsive design for all device sizes

## Hosting on GitHub

### Step 1: Create a GitHub Repository
1. Create a new repository on GitHub
2. Name it `interpol-identity-card` (or your preferred name)

### Step 2: Upload Files
1. Create a new file named `interpol-identity-card.html`
2. Copy the HTML content from above into this file
3. Commit the file to your repository

### Step 3: Enable GitHub Pages
1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Update QR Code URL
1. After GitHub Pages is enabled, note your page URL:  
   `https://YOUR_USERNAME.github.io/interpol-identity-card/interpol-identity-card.html`
2. Get the raw content URL:  
   `https://raw.githubusercontent.com/YOUR_USERNAME/interpol-identity-card/main/interpol-identity-card.html`
3. In the HTML file, find this line:
   ```js
   const fileContentUrl = "https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/interpol-identity-card.html";
```