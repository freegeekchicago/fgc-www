# http://freegeekchicago.org

## Structure

```
.
├── /   (Front Page)
|   |
|   ├── * Big (maybe Red) **DONATE** or **GIVE** Button on main navbar. Link to /give
|   ├── * Blog Feed
|   ├── * Twitter Feed
|   ├── * Calendar Feed
|   ├── * Photo (Instagram / Flickr) Feed
|   ├── * Lots o' links
|   |
|
|
|── /about
|   ├── * Mission
|   ├── * History
|   ├── * More
|   |   ├── Link to /about/press
|   |   ├── Link to /about/legal
|   |   ├── Link to /about/contact
|   |
|   ├── /about/press OR /about/media
|   |   └── * List of news articles
|   |
|   ├── /about/legal
|   |   ├── * Incorporated Name: FREEGEEK/CHICAGO, NFP
|   |   ├── * Federal Tax Identification Number (TIN, EIN)(Link): 26-1852070
|   |   └── * Illinois, Secretary of State File Number (Link): 65933357
|   |
|   ├── /about/contact (Make this page a redirect from /contact
|   |   ├── * Directions + Map
|   |   ├── * Hours
|   |   └── * Contact Form. Embedded Google form.
|
|
├── /community
|   ├── * About the Community
|   ├── * Our Board of Directors
|   ├── * Our Support Staff
|   ├── * Link to our Policies (github.com/freegeekchicago/fgc-docs)
|   |
|   ├── /community/discuss
|   |   └── * Embedded Google Groups
|   |
|   ├── /community/blog
|   |   └── * News stories (top one displayed on / front page)
|   |
|   ├── /community/thisweek
|   |   └── * ThisWeek @ FreeGeek (top one displayed on /community
|   |
|   ├── /community/calendar
|   |   └── * Embedded Google Calendar
|   |
|   ├── /community/conduct
|   |   └── * Code of Conduct (Embedded from github? or keep synced with github?)
|   |
|   ├── /community/constitution
|   |   └── * Constitution (Embedded from github? or keep synced with github?)
|
|
├── /volunteer
|   ├── * Get Started! / Orientation
|   |   ├── * Service / Learning - OR Why our volunteer programs are awesome!
|   |   |   └── * Brief description of Rewards Program and link to /volunteer/rewards
|   |   ├── * Volunteer Qualifications
|   |   └── * Orientation Dates and Times
|   ├── * Service Areas
|   |   ├── * Build (Build Your Knowledge while You Build a Box. Includes Desktop QA)
|   |   |   └── * Short snippet with link to /volunteer/build-desktops
|   |   ├── * Build for Laptops (Includes Laptop QA)
|   |   |   └── * Short snippet with link to /volunteer/build-laptops
|   |   ├── * Intake and Testing
|   |   |   └── * Short snippet with link to /volunteer/intake
|   |   ├── * Education
|   |   |   └── * Short snippet with link to /volunteer/education (or /education/volunteer ?)
|   |   ├── * Store / Customer Service
|   |   |   └── * Short snippet with link to /volunteer/store (or /store/volunteer ?)
|   |
|   ├── /volunteer/rewards
|   |   └── * Earn-A-Box / Full Rewards Policy
|   |
|   ├── /volunteer/build-desktops
|   |   ├── * What do we do?
|   |   ├── * Service Area Requirements
|   |   ├── * When do we meet?
|   |   └── * Learn More (Link to Hackpad)
|   |
|   ├── /volunteer/build-laptops
|   |   ├── * What do we do?
|   |   ├── * Service Area Requirements
|   |   ├── * When do we meet?
|   |   └── * Learn More (Link to Hackpad)
|   |
|   ├── /volunteer/intake
|   |   ├── * What do we do?
|   |   ├── * Service Area Requirements
|   |   ├── * When do we meet?
|   |   └── * Learn More (Link to Hackpad)
|   |
|   ├── /volunteer/education (or /education/volunteer ?)
|   |   └── * Education Coordinator needs to advise what content is needed
|   |
|   ├── /volunteer/store (or /store/volunteer ?)
|   |   ├── * What do we do?
|   |   ├── * Service Area Requirements
|   |   ├── * When do we meet?
|   |   └── * Learn More (Link to Hackpad)
|
|
├── /give (Cash Donations)
|   ├── * Quote from volunteer about our program
|   ├── * Embedded giving form (PayPal? or Swipe?). Include recurring donation option.
|   ├── * Table of giving amounts and what they might pay for.
|   ├── * Mission statement
|   ├── * Give by check or in person.
|   └── * Link to /donate for equipment and supplies donations
|
|
├── /donate (Non-Cash Donations)
|   ├── * Quote from volunteer about our program
|   ├── * Link to /give (Want to make a monetary donation?)
|   ├── * Table of accepted items.
|   |   ├── * What we accept
|   |   ├── * what we do not accept
|   ├── * Pickups
|   |   ├── * "Need a pickup? Review our minimums for pickup and fill out our pickup request form."
|   |   ├── * Link to /donate/pickups or /pickups
|   ├── * What happens to your donation.
|   |   ├── * Volunteer Build Program. Short description and link to /volunteer or /volunteer/build-desktops
|   |   ├── * Data Destruction Policy. Short description and link to /donate/data
|   |   ├── * Environmental Policy. Short description and link to /donate/environment
|   ├── * Suggested giving amounts for equipment that we end up recycling
|   ├── * Prepare Your Donation
|   |
|   ├── /donate/data
|   |   └── * Data destruction policy
|   |
|   ├── /donate/environment (or /environment or /recycling ?)
|   |   └── * Recycling policy
|   |
|   ├── /donate/pickups (or /pickups ?)
|   |   └── * Pickup request form. Embedded Google form.
|
|
├── /shop or /buy or /store
|   ├── * Ways to shop
|   |   ├── * Link to /shop/logan-square
|   |   ├── * Link to /shop/online
|   ├── * Why buy from FreeGeek?
|   |   ├── * Support our volunteer programming. Link to /volunteer
|   |   ├── * Support our mission of reuse and recycling. Link to /recycling
|   |   ├── * Warranty and quality assurance
|   ├── * Our Hardware
|   |   ├── * Min Desktop Package
|   |   ├── * Avg Desktop Package
|   |   ├── * Min Laptop Package
|   |   ├── * Avg Laptop Package
|   |   ├── * Link to /shop/pricelist for small items
|   ├── * Our Software
|   |   ├── * Short description of available software
|   ├── * Warranty and Returns
|   |   ├── * Link to /shop/warranty or maybe embed fgc-docs/policy-warranty-returns?
|   |
|   ├──/shop/logan-square
|   |   ├── * Include /contact?
|   |   ├── * Embed calendar with only Store hours
|   |
|   ├──/shop/online
|   |   ├── * Description of what we sell online
|   |   ├── * Link to ebay page
|   |   ├── * Link to any additional online sales portals
|   |
|   ├──/shop/pricelist
|   |   ├── * Pricelist for small items. (Mice, keyboards, cables, etc)
|   |   ├── * Maybe make an embedded table from hackpad or Google Sheets?
|
|        
├── /paypal
|   └── Specifically used to process a thrift store sale. Hopefully temporary.

```


## Additional Information Areas to Sort
- Hacking Crew (Sort under /volunteer/labs ?)
    * Github/freegeekchicago
    * Github/sc3

- Our Outreach / Our giving
- Education?

- Hackpad / Wiki
- Townsquare (Under Community / Volunteer)

- Twitter (Footer)
- Facebook (Footer)    
- Google+ (Footer)

- LinkedIn (Footer)
- Github (Footer)

- Yelp (Only on store page?)
- Google+ Place (Only on Store Page?)
