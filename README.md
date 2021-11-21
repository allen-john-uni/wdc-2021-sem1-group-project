# WDC Group 97 Project

You can run the web by first doing `cd web` and then `npm install` to install all the packages needed to run the web server.

Afterwards, `npm start` to get the web server starting and open the web server by
1. Click on the `CS50 IDE` on the top left, and
2. Select `Web Server`

## Links
Video submission: https://drive.google.com/file/d/14Fw4gkX4ooshK9MBPugaSJvAdlB-beCz/view?usp=sharing
CS50 IDE: https://ide.cs50.io/84ce275c3da74fc286321e56d78c003b

## Dabatase-related
Database backup is in `web/public/db/tarcedb3.sql`.
Database queries is in `web/public/db/db_query.sql`.
Database schema is in `web/public/db/db_schema.sql`.

## Login details
The following details can log you in to our website (either as a user, admin, or venue manager)
`Email: tansu.yvonne@gmail.com`
`Password: testyt`

### Feature details and security implementation
Afterwards, you can choose to sign-in as a user, admin or venue manager.

If you choose to sign in as a user,
What you can do:
- Profile: To see your details and update it accordingly. You can also update password/set password if you originally register using Google.
- View hotspots
- Check-in using store code or QR code
- View check-in history in the form of list (scrollable list of 20 which you will be able to load more by pressing `Load More` button) or map
- FAQs
- Contact Us

If you choose to sign in as an admin, there additional things on top of what users can do:
- `Manage Users` (edit user details and also view their check-in history) by entering the user's `email` in and press `search`.
- `Manage Venues` (edit venue details and also view their check-in history) by entering the venue's `store code` in and press `search`.
- `Manage Hotspots` (edit user details and also view their check-in history) by entering the venue's `store code` and press `search`.
- `Sign Up Others` (the person you signed up for will automatically be an admin/health official).

If you choose to sign in as a venue manager,
What you can do:
- View venue's current hotspot status
- View check-in history of the venue in terms of scrollable list of 20 which you will be able to load more by pressing `Load More` button.
- Display the venue's store code and also QR Code.
- View Hotspots
- FAQs
- Contact Us

Security implemented:
- Session storage in database
- Sanitize inputs using `sanitize-html`
- Middleware located in the `routes` folder and also the parent functions imported from `auth.js`.# wdc-2021-sem1-group-project
# wdc-2021-sem1-group-project
# wdc-2021-sem1-group-project
# wdc-2021-sem1-group-project
# wdc-2021-sem1-group-project
