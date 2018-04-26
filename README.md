# WebsiteChecklist
These are the items we need to complete at each phase of the development process.

1. [Information Gathering](#information-gathering)
2. [Development Testing](#development-testing)
3. [Speed Checklist](#speed-checklist)
4. [Accessiblity Testing](#accessiblity-testing)
5. [SEO](#seo)
6. [Social](#social)
7. [Security](#security)
8. [Go Live](#go-live)


## Information Gathering

* Current website hosting credentials 
* Current website domain registrar credentials
* Current CMS credentials
* Current Google Analytics/Google Tag Manager credentials
* Set up Route 53/AWS Acccount/S3 buckets
* Set up Typekit account
* Preferred contact form email
* Preferred credit card
* Set up SSL cerficates
* Set up webmaster@domain.tld account
* IAM user
* Current Payment Gateway credentials
* Social Media Account links
* SEO Keywords List

## Development Testing

* Test ALL Forms (functionality and make they have a logical layout) 
* Check form validation
* Check Navigation links
* Check Drop Downs (loading behind images or videos?)
* Check Links on Pages (download links, etc)
* Check in IE 11
* Check in FireFox (windows AND mac)
* Check in Safari
* Check in Chrome
* Check in Edge
* iPad - check to make sure site views correctly.
* Check on Android and Apple device phones.
* Use backend to add content (multiple posts, lots of text, little text, different image sizes)
* Use WYSIWYG features (insert image, align left, align right, h space, v space, make text a link, h1, h2, h3, bold)
* Make sure no "Hello World"/Lorem Ispum pages or posts exist.
* Check 404 page
* Check search page

## Speed Checklist

* set Cache Control Headers on S3 on file upload/edit
* JavaScript/CSS/HTML is minified and combined (as much as possible)
* Images have been optimised
* Enable gzip compression on JSON files
* If using *TypeKit*: go to *Kit Settings* and check the *Optimize Performance* checkbox (caches for one week)
* Test website speed on [Pingdom](https://tools.pingdom.com/) and [Pagespeed Insights](https://developers.google.com/speed/pagespeed/insights/)

## Accessiblity Testing

* Check content for spelling errors, Typos, and grammar mistakes
* Turn off images, and check whether appropriate alternative text is available. 
* Turn off the sound, and make sure audio content is still available through text equivalents.
* Use browser controls to vary font-size: verify that the font size changes on the screen accordingly; and that the page is still usable at larger font sizes.
* Change the display color to gray scale (or print out page in gray scale or black and white) and observe whether the color contrast is adequate.
  controls, and that the links clearly indicate what they lead to.
* Also examine page with scripts, style sheets, applets, and other embedded objects not loaded.
  through the GUI browser? Is the information presented in a meaningful order if read serially?
* Validate HTML

## SEO

* Page titles are descriptive and SEO friendly
* All page titles are unique
* Meta data included and appropriate
* H1s used for page titles and only one H1 per page
* XML sitemap has been generated and added to root of website
* robots.txt is generated and added to root of website
* Website can be accessed by search engines (remove noindex, nofollow for pages)
* Google Analytics and relevant analytics/tracking tools installed

## Social

* Open Graph tags included across website and appropriate? (including images where possible)
* All social network links included, linking to correct URLs and use API for integrations (if needed)

## Security

* Secure areas are locked down and not accessible by search engines
* Default CMS login URL is changed
* Default CMS username & password is changed

## Go Live 

* **All departments have signed off approving the deployment of the site**
* 301 redirects for existing website are prepared and in place
* Ensure site is visible to search engines
* SSL certificates successfully installed
* Images, media and links reference live URL
* Webfonts integrated and working correctly on live site
* Webfonts set to production (as required)
* 301 redirects are in place and working correctly
* Website URL has been submitted to Google
* Generate a new sitemap.xml and upload to root
* Site added to Google Webmaster tools and sitemap submitted
* Analytics has been setup and integrated into website
