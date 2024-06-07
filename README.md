# TrustingEyesEars

## SECURITY notice
### This is a study project, use at your own risk.
A Font Awesome kit, present in this userscript as a source tag, keeps a record of its ‘Pageviews’, 
which is a list of all the domains from which the kit was loaded by a source tag. 
This means that we, as the particular Font Awesome's account owners, can view all the domains that someone running our userscript visits. 

---

To run:

<code>cd server</code>

<code>node index.js </code>

---

To compile styles from Tailwind classes:

<code>npx tailwindcss -i ./public/input.css -o ./public/output.css --watch</code>

---

To connect to database:

Create .env file in /server and write this in it (replacing {} for actual password)

<code>DB_PASSWORD={}</code>

###### Note: 
This did not come through much in our reports, and it's a minor detail, 
but it should be known our userscript **ignores images below a size of 112 by 112 pixels** (an experimentally derived value).

