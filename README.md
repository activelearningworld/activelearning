# ActiveLearningWorld – Android App Brand & Legal Website

A professional static website for **ActiveLearningWorld**, featuring:

- Home
- About
- Privacy Policy
- Terms & Conditions
- Disclaimer
- Contact

The entire website is contained in a single file:

```
index.html
```

No frameworks, build tools, or dependencies are required.

---

# Features

✅ Fully Responsive

✅ Mobile Friendly

✅ Fast Loading

✅ SEO Friendly

✅ Privacy Policy Included

✅ Terms & Conditions Included

✅ Disclaimer Included

✅ Contact Section Included

✅ Deploy Anywhere

---

# Project Structure

```
/
├── index.html
└── README.md
```

Optional:

```
/
├── index.html
├── app-ads.txt
└── README.md
```

---

# Running Locally

## Option 1: Open Directly

Simply double-click:

```
index.html
```

and open it in your browser.

---

## Option 2: Python Server (Recommended)

Open terminal in the project folder:

```bash
python -m http.server 8000
```

or

```bash
python3 -m http.server 8000
```

Open:

```
http://localhost:8000
```

---

## Option 3: Node.js

```bash
npx serve .
```

or

```bash
npx http-server .
```

---

## Option 4: VS Code Live Server

1. Install "Live Server" extension.
2. Right-click `index.html`.
3. Click:

```
Open with Live Server
```

---

# Deploy to GitHub Pages

## Step 1

Create a GitHub repository.

Example:

```
activelearningworld
```

---

## Step 2

Upload:

```
index.html
```

to the repository root.

---

## Step 3

Open:

```
Repository Settings
```

→

```
Pages
```

---

## Step 4

Under:

```
Build and deployment
```

Select:

```
Source: Deploy from a branch
```

---

## Step 5

Select:

```
Branch: main
Folder: /(root)
```

---

## Step 6

Click:

```
Save
```

---

## Step 7

Wait 1–2 minutes.

Your website will be available at:

```
https://USERNAME.github.io/REPOSITORY_NAME/
```

Example:

```
https://activelearningworld.github.io/website/
```

---

# Deploy to Netlify

## Method 1: Drag and Drop

1. Visit:

```
https://app.netlify.com
```

2. Login.
3. Click:

```
Add New Site
```

4. Drag your project folder onto the page.
5. Deployment starts automatically.

---

## Method 2: GitHub Repository

1. Connect GitHub.
2. Select repository.
3. Build command:

```
Leave Empty
```

4. Publish directory:

```
.
```

5. Click:

```
Deploy Site
```

Website URL:

```
https://your-site.netlify.app
```

---

# Deploy to Vercel

## Step 1

Visit:

```
https://vercel.com
```

---

## Step 2

Import GitHub repository.

---

## Step 3

Framework preset:

```
Other
```

---

## Step 4

Leave build settings empty.

---

## Step 5

Click:

```
Deploy
```

Website URL:

```
https://your-project.vercel.app
```

---

# Deploy to Cloudflare Pages

## Step 1

Visit:

```
https://pages.cloudflare.com
```

---

## Step 2

Create Project.

---

## Step 3

Connect GitHub repository.

---

## Step 4

Build Command:

```
Leave Empty
```

---

## Step 5

Output Directory:

```
.
```

---

## Step 6

Deploy.

Website URL:

```
https://your-project.pages.dev
```

---

# Setting Up app-ads.txt (AdMob)

Create a file:

```
app-ads.txt
```

Add:

```text
google.com, pub-YOUR_PUBLISHER_ID, DIRECT, f08c47fec0942fa0
```

Example:

```text
google.com, pub-1234567890123456, DIRECT, f08c47fec0942fa0
```

Upload it to the root directory.

Example:

```
/
├── index.html
├── app-ads.txt
└── README.md
```

Verify:

```
https://your-domain.com/app-ads.txt
```

You should see only:

```text
google.com, pub-1234567890123456, DIRECT, f08c47fec0942fa0
```

---

# Google Play Console

Update your website URL:

```
Google Play Console
→ Store Presence
→ Store Listing
→ Contact Details
→ Website
```

Use your deployed website URL.

Example:

```
https://activelearningworld.pages.dev
```

---

# Customization

## Change Email

Search:

```
activelearningworld@gmail.com
```

Replace with your email.

---

## Change Brand Name

Search:

```
ActiveLearningWorld
```

Replace with your brand name.

---

## Change Colors

Edit CSS variables inside:

```css
:root {
}
```

Example:

```css
--primary: #2563eb;
--primary-dark: #1d4ed8;
```

---

# Troubleshooting

## Website Not Updating

Hard refresh:

```
Ctrl + F5
```

---

## app-ads.txt Not Found

Verify:

```
https://your-domain.com/app-ads.txt
```

must open directly.

---

## GitHub Pages Not Working

Wait 5–10 minutes after enabling Pages.

---

# License

MIT License

You may use, modify, and distribute this project.

---

# Support

Email:

```
activelearningworld@gmail.com
```

---

Made with ❤️ for Android App Development.
