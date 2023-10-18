# knock_every_door
Interactive webpage for the Knock Every Door initiative

Components of Map:
1. On click, display all info about it. And link to update the section. And maybe link to download map for that section (printable). Make sure to give Streams of Light full credit, etc.
2. Ability to filter by year and type of activity (research how to do this)
3. Few options to verify. When update, will just continually be the most recent one.
    1. Tammie manually reviews - probably best
        1. For submission, required to put in a church, so we can call to verify if unfamiliar.
    2. Simple password
    3. MISDA email
4. Sidebar with population/homes reached as part of the total.
5. On hover, shows who did it and when they did it.
6. Ability to color code them either by all one color or no color; maybe need a binary attribute (if completed or not) and a separate source attribute, so we can color them based on those.
7. Have regular maps hidden, but show boundaries when hover 

Website Components:
Website - like type form. 
Bold headline
Sub header with current count of doors, maybe specifics about what we’re seeking to accomplish
Then a video promo with b roll and micheff, Craig, SSPM, and students, pastors, reach, etc.


Then how to get involved - 4 options with links

Then a map of our current progress, would be good to have a menu bar item to access it directly, maybe a one page with menu bar items that move to div.
Links to news reports of our progress and link to sign up.
Link to donate specifically to REACH literature.
At bottom - project of misda.

Map Page:
1. Password protected; simple password; if haven't accessed before, simple form to request access; automatically emails password + instructions to email given.
2. Use Xata and Python program to get all church names and links. Use simple query by ID and a drop-down form to get a page with a simple link to the Google Drive folder with the maps.


Versions:
1. Deploy a super-minimal Next.js app with Vercel so I can prove it works.
2. Fill out the HTML with simple links.  Just header, sub-header, links to get involved, news reports, link to sign up, and link to donate (courtesy of STRIPE).
3. Add Tailwind CSS to make it all pretty and usable as a website.
4. Set up Xata with all details so I have a working database.
5. Build a simple page to search and access it.
6. Password protect it with a Zapier email template, auth, etc.
7. Build out simple pages for Pathfinders (etc.) so they can access all instructions in one place.
8. Start on the GeoJSON section and getting that all built. That doesn't need to be built till April-ish. As long as
9. Maybe if this is taking forever, start with a simple form to email in maps to Tammie until we get April thing set up.




