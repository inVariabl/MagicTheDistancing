# MagicTheDistancing
Find Zoom Meetings for Magic the Gathering Games

Enter in the time you can play, your deck level, your email and zoom id and this program will match you will 3 other people and send you a zoom meeting link.

## Prospectus
### Frontend
The Frontend will be a website hosted with [Github Pages](https://pages.github.com/) that will serve as a:
1. A form to sign up with your Name, Email, and Deck Level
2. A display of those who are online, rooms currently available, and when others have signed up
3. Send the encrypted JSON "forms" to the server

##### Resources
+ [MaterializeCSS](https://materializecss.com/) form

---

### Backend
The Backend will be a [Node.JS](https://nodejs.org/en/about/) server running on [Heroku](heroku.com) that will:
1. Parse the JSON
2. Group together 4 people first by time, then by skill. [Time Matcher](https://doodle.com)?
4. Create Zoom meeting - [API](https://marketplace.zoom.us/docs/guides/tools-resources/zoom-apis)
5. Send Email?
