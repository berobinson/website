FOR ADDITIONS AND BUILDING
- open github desktop. go to WEBSITE repo. (web and hugo_academic are experiments)
- open the 'website' repo in BBEdit.
- modify things in the 'content' folder. this means
  - content/authors when new people show up
  - content/project for new ahem projects
  - content/publication for new articles
  etc...
- After changes, deploy locally for viewing
  - open terminal.
  - type: cd /Users/ber/Documents/GitHub/website
  - type: hugo server
  - site should deploy to http://localhost:1313
- When happy with updates
  - commit changes in Github desktop
  - push to web
  - then Netlify should see changes and deploy to web. if alls good then voila.

- currently content/post and content/event are not used. could be deleted.
- some things in the public folder are not right too. publications search

--------------
* Things in the works:
--------------

1. I created a 'people' folder to move the team off the main site. this works and can still
navigate to this site, BUT:
- the formatting is a little off, mostly spacing after titles which makes it hard to see groups
- I had to pull html code directly from the public/index.html file. Not sure about having to
  keep it updated manually

2. Was also looking for way to get bluesky icon in the socials, but not there right now, so just
using the twitter icon and linking to bsky acct

3. The bootstrap version of hugo academic is no longer supported, so think the site has
   a medium-term lifespan. Will need to port soon. THoughts:
  - hugo academic is getting new life as HUGO BLOX. looks nice and may be easier to maintain
    but doesn't have the functionality yet. my current site is a "bootstrap" site. the new
    ones are "tailwind" sites. (wtf that means i don't know, but code is different).
    CHECK BACK periodically?
  - post from xiaofanliang shows some workarounds https://github.com/HugoBlox/hugo-blox-builder/discussions/2635
    - her github repo: https://github.com/xiaofanliang/starter-hugo-academic
    - her good site: https://www.xiaofanliang.com/
  - Other options that look decent:
    - git + jekyll. jekyll is similar to Hugo and lots of examples out there
    - good overview here on setting up QUARTO site: https://ab604.uk/how
      led me to this nice (but overbuilt for my tastes) site: https://www.jhelvy.com/
      also this site which has useful blog posts https://www.andrewheiss.com/
