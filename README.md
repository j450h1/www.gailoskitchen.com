# www.gailoskitchen.com
The new website for gailoskitchen

## Code

* Setup new site - make sure no other files than *.Rproj, this README and other hidden files (directory is "empty")

```blogdown::new_site(theme = "seanlane/gochowdown")```

* To preview the website:

```blogdown::serve_site()```

# Setup

* Under netlify, setup: **Add a custom domain to your site**

* DNS configuration:
Point www CNAME record to elastic-liskov-5c5411.netlify.app

* For Google Domains - there is a message that says it can take 48 hours to update after saving the change.

* Or alternatively just setup Netlify DNS under Options in Domain and then follow instructions

* Update baseURL = "https://www.gailoskitchen.com/" under **config.toml**

## Old website

```	<div class="blurb">
        		<h1>Hi there, I'm Gurmail!</h1>
				<p>I make fresh Samosas (Vegetarian only) for pickup in Vancouver!</p>
                                <p>Contact me for minimum orders of 50 Samosas. <b>604-767-8116</b> </p>
    		<img src="images/Gailos_Kitchen_Business_Card.jpg">
    		
```
