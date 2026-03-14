═══════════════════════════════════════════════════
  TECH SUPPORT DASHBOARD — HOSTING SETUP GUIDE
═══════════════════════════════════════════════════

PACKAGE CONTENTS:
  index.html   → Your main website
  .htaccess    → SSL force + security (Apache)
  robots.txt   → SEO file
  README.txt   → This guide

───────────────────────────────────────────────────
STEP 1 — BUY DOMAIN + HOSTING
───────────────────────────────────────────────────
Recommended providers (cheap & reliable):
  • Hostinger.com  (cheapest, ~₹99/mo)
  • Namecheap.com
  • GoDaddy.com

Buy:
  ✔ A domain name (e.g. yourbrand.com)
  ✔ A shared hosting plan (any basic plan works)

───────────────────────────────────────────────────
STEP 2 — POINT DOMAIN TO HOSTING
───────────────────────────────────────────────────
1. In your Domain registrar → DNS Settings
2. Set Nameservers to your hosting provider's NS
   (e.g. ns1.hostinger.com, ns2.hostinger.com)
3. Wait 10–30 minutes for propagation

───────────────────────────────────────────────────
STEP 3 — UPLOAD FILES via cPanel File Manager
───────────────────────────────────────────────────
1. Login to your hosting cPanel
2. Open "File Manager"
3. Navigate to: public_html/
4. DELETE the default index.html if it exists
5. Upload ALL these files:
   → index.html
   → .htaccess   ⚠ (make sure hidden files are visible)
   → robots.txt
6. Done! Visit your domain — site is live.

───────────────────────────────────────────────────
STEP 4 — ENABLE FREE SSL CERTIFICATE
───────────────────────────────────────────────────
In cPanel:
1. Go to "SSL/TLS" or "Let's Encrypt SSL"
2. Click "Install" for your domain
3. SSL is FREE with most hosts via Let's Encrypt
4. .htaccess already forces HTTP → HTTPS auto

───────────────────────────────────────────────────
STEP 5 — ADD YOUR WHATSAPP NUMBER
───────────────────────────────────────────────────
1. Open index.html in Notepad or any text editor
2. Find this line (near bottom of file):
   const WHATSAPP_NUMBER = "1234567890";
3. Replace 1234567890 with your number:
   Include country code, NO + or spaces
   Example India: "919876543210"
   Example UK:    "447911123456"
4. Save and re-upload index.html

───────────────────────────────────────────────────
DONE! Your site is now LIVE with SSL 🚀
═══════════════════════════════════════════════════
