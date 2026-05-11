# Amazon Associate Startup Roadmap

This guide covers the technical setup for your Amazon Associate website, focusing on Google Search traffic.

## Step 1: Getting Your Links (Amazon SiteStripe)
You don't need to generate complex code. Use **SiteStripe**.
1.  Log in to your [Amazon Associate Central](https://affiliate-program.amazon.com/).
2.  Go to the regular Amazon.com website.
3.  You will see a grey bar at the top (SiteStripe).
4.  Navigate to any product page.
5.  Click **"Text"** in the SiteStripe bar to get your unique affiliate link.
6.  **Crucial:** Always use the "Full Link" if you want to be safe, though "Short Link" is usually fine.

## Step 2: Domain & Hosting Setup
Since you already have a domain and host, here is how to connect them:
1.  **Nameservers:** Log in to your domain registrar (e.g., GoDaddy, Namecheap) and point the Nameservers to your host (e.g., Bluehost, SiteGround).
2.  **SSL Certificate:** Ensure your site has HTTPS. Most hosts provide a free "Let's Encrypt" SSL. Google penalizes sites without it.
3.  **CMS (WordPress Recommended):** Most affiliate sites use WordPress for ease of SEO. Use your host's "1-Click Install" for WordPress.

## Step 3: Connecting to Google (SEO Setup)
To show up on Google, you must tell Google you exist.
1.  **Google Search Console (GSC):**
    - Go to [Google Search Console](https://search.google.com/search-console/).
    - Add your "Domain" or "URL Prefix".
    - Verify ownership by adding a TXT record to your DNS (on your host/registrar) or uploading an HTML file to your site's root directory.
2.  **Sitemap:**
    - If using WordPress, install an SEO plugin (like RankMath or Yoast).
    - It will generate a `sitemap.xml`.
    - Submit this URL in the "Sitemaps" section of GSC.
3.  **Google Analytics 4 (GA4):**
    - Set up a property to track where your visitors come from.

## Step 4: Content Strategy
1.  **Write "The Best..." Articles:** Review 5-10 products in a niche.
2.  **Comparison Tables:** Use a table at the start of every post so users can click and buy immediately.
3.  **Disclaimer:** You MUST include an affiliate disclaimer at the top of every page (e.g., "As an Amazon Associate, I earn from qualifying purchases.").
