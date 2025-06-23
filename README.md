This is a professional INTERPOL identity card generator with a QR code that links to the exact HTML file content. The application allows users to generate official-looking INTERPOL agent credentials with security features.

![INTERPOL Identity Card](screenshot.png)

## Features

- Professional INTERPOL-themed interface
- Form to input agent details
- Real-time ID card generation
- Barcode for agent credentials
- QR code that points to the raw HTML file content
- Responsive design for all device sizes

## Hosting on GitHub Pages

### Step 1: Create a GitHub Repository
1. Create a new repository on GitHub.
2. Name it `interpol-identity-card` (or your preferred name).

### Step 2: Upload Files
1. Create a new file named `index.html` (not `interpol-identity-card.html`).
2. Copy your HTML content into this file.
3. Commit and push the file to your repository.

### Step 3: Enable GitHub Pages
1. Go to your repository settings on GitHub.
2. Navigate to "Pages" in the left sidebar.
3. Under "Source", select "Deploy from a branch".
4. Choose the `main` branch and `/ (root)` folder.
5. Click "Save".

### Step 4: Update QR Code URL
1. After GitHub Pages is enabled, your live site will be:  
   `https://YOUR_USERNAME.github.io/interpol-identity-card/`
2. The raw content URL for your HTML file will be:  
   `https://raw.githubusercontent.com/YOUR_USERNAME/interpol-identity-card/main/index.html`
3. In your `index.html` file, update this line:  
   ```js
   const fileContentUrl = "https://raw.githubusercontent.com/YOUR_USERNAME/interpol-identity-card/main/index.html";
   ```
   Replace `YOUR_USERNAME` with your GitHub username.

---

**Your site will now be live at:**  
`https://YOUR_USERNAME.github.io/interpol-identity-card/`
