FIRST LIGHT PARENTING — Website Files
======================================
firstlightparenting.co.uk

FILES
-----
index.html      — Homepage (English)
about.html      — About Camille
blog.html       — Tips & guides index
blog-sleep.html — Article: 18-month sleep regression
fr.html         — Homepage (French)
es.html         — Homepage (Spanish)
README.txt      — This file

HOW TO DEPLOY (GitHub + Cloudflare Pages)
------------------------------------------
1. Create a GitHub repository (public or private)
2. Push all these files to the repo root
3. Go to dash.cloudflare.com → Pages → Create a project
4. Connect to GitHub → select your repo
5. Build settings: leave everything blank (pure static HTML)
6. Click Deploy — site is live at a .pages.dev URL

CONNECT YOUR DOMAIN
--------------------
1. In Cloudflare Pages: Settings → Custom domains → Add domain
2. Type: firstlightparenting.co.uk
3. In Namecheap: change nameservers to Cloudflare's
   (Cloudflare gives you the exact nameserver names)
4. Wait up to 24 hours — usually under 1 hour

ACTIVATE CALENDLY BOOKING
--------------------------
1. Sign up at calendly.com
2. Create event: "Free 20-Minute Intro Call" (20 min, one-on-one)
3. Connect your Google or Outlook calendar
4. Copy your link e.g. calendly.com/camille-firstlight/intro
5. Open index.html, find YOUR_CALENDLY_LINK (there is 1 instance)
6. Uncomment the Calendly widget block (instructions are in the HTML)

SET UP EMAIL
------------
1. Go to zoho.com/mail → sign up free
2. Add domain: firstlightparenting.co.uk
3. Create: hello@firstlightparenting.co.uk
4. Add the DNS records Zoho gives you in Namecheap/Cloudflare

FORMS (web3forms)
-----------------
Forms are already configured with your web3forms access key.
They will work automatically once the site is live.
Submissions arrive at: hello@firstlightparenting.co.uk
Test by submitting the contact form after going live.

CONNECT INSTAGRAM
-----------------
Search index.html for href="#" next to "Instagram"
Replace with: href="https://instagram.com/YOUR_HANDLE"
Do the same in about.html, blog.html

AFTER GOING LIVE — PRIORITY LIST
----------------------------------
1. Test all forms (submit each one, check inbox)
2. Add Calendly link to the booking section
3. Set up Zoho email
4. Create Instagram @firstlightparenting
5. Set up Google Analytics + Search Console (both free)
6. Set up Mailchimp for the lead magnet PDF delivery
7. Write 2 more blog articles targeting search terms:
   - "toddler won't sleep in own bed"
   - "how to handle toddler tantrums"
8. Buy firstlightparenting.com (~£10/yr) as a redirect

SUPPORT
-------
hello@firstlightparenting.co.uk
