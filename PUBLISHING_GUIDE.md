# How to Publish Your Amazon Affiliate Site

Now that you have your niche ideas and a template, here is how to get it live on your host.

## Option A: Using WordPress (The Easiest Way)
If you followed the ROADMAP.md and installed WordPress:
1.  Log in to your WordPress Dashboard (`yourdomain.com/wp-admin`).
2.  Go to **Posts > Add New**.
3.  Copy the content from `template/index.html` (the text and structure, not the HTML tags if using the Visual Editor).
4.  **Formatting:** Use the "Table" block to create your comparison table.
5.  **Links:** Highlight your "Buy on Amazon" buttons and paste your SiteStripe link.
6.  **Featured Image:** Upload a high-quality image of the product.
7.  Click **Publish**.

## Option B: Using Direct HTML (If you have a static host)
If you want to use the `template/index.html` file directly:
1.  **Edit the File:** Open `template/index.html` in a text editor. Replace all `YOUR_AMAZON_LINK_HERE` with your actual affiliate links from SiteStripe.
2.  **Upload via FTP:**
    - Download an FTP client like **FileZilla**.
    - Connect to your host using the credentials provided in your hosting welcome email (Host, Username, Password).
    - Navigate to the `public_html` folder (or the root folder of your domain).
    - Drag and drop your `index.html` file into that folder.
3.  **Upload via cPanel:**
    - Log in to your host's cPanel.
    - Go to **File Manager**.
    - Navigate to `public_html`.
    - Click **Upload** and select your `index.html` file.

## After Publishing: The Checklist
- [ ] Check if the links work (they should take you to Amazon).
- [ ] Ensure the "Disclaimer" is visible.
- [ ] Go to Google Search Console and "Request Indexing" for your new URL.
- [ ] Check how it looks on mobile.
