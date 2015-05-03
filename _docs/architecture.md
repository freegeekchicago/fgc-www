# http://freegeekchicago.org

## Main Pages to Sort

```
# Legend
 * Feature should exist on page
 - Sub-page of parent page
```

```
# Pages
- root / Front Page
    * Big (maybe Red) **DONATE** Button on main navbar. Link to embedded PAYPAL donation page.
    * Links to other sections.

- About Us
    * Mission
    * History
    * Contact Us (Link to /contact)
    - Media / Press (Read all about us!)
        * List of news articles
    - Legal

- Contact Us
    * Directions + Map
    * Hours
    * Contact Form

- Calendar
    * Just the calendar

- Shop / Buy / Store
    * Thrift Store
    * Online Store
        Pre-Installed Software
        Min Desktop Package
        Avg Desktop Package
        Min Laptop Package
        Avg Laptop Package
        Warranty and Returns
        Pricelist

- Donate
    * Cash Donations (on main "Donate" page)
    * Non-Cash Donations (on main "Donate" page)
        What we accept
        What we do not accept
        Suggested donations for equipment
        Preparations for Donation
    - Data Destruction Policy
    - Environmental Policy
    - Pickups

- Volunteer
    * Orientation
    * Volunteer Requirements
    * Rewards Program
    - Earn-A-Box / Full Rewards Policy
    - Laptop Refurbishing
    - Hacking Crew
        * Github/freegeekchicago
        * Github/sc3
    - Education

- Community
    * About the Community
    * Our Board of Directors
    * Our Support Staff
    - Code of Conduct
    - Constitution
    - Discussion List (Google Group Embed)
    - News/Web-log
```

## Additional Information Areas to Sort
- Hackpad / Wiki
- Townsquare (Under Community / Volunteer)

- Twitter (Footer)
- Facebook (Footer)    
- Google+ (Footer)

- LinkedIn (Footer)
- Github (Footer)

- Yelp
- Google+ Place



## Temporarily needed pages
- PayPal
    Specifically used to process a thrift store sale.

## Structure

```
.
├── /
|   |
|   ├── Blog Feed
|   ├── Twitter Feed
|   ├── Calendar Feed
|   ├── Photo (Instagram / Flickr) Feed
|   ├── 
|   |
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
|   ├── /about/contact
|   |   ├── * Directions + Map
|   |   ├── * Hours
|   |   └── * Contact Form
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
|   |   └── * News stories (top one displayed on front page)
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
|   |   |   └── * Short snippet with link to /volunteer/testing
|   |   ├── * Education
|   |   |   └── * Short snippet with link to /volunteer/education (or /education/volunteer ?)
|   |   ├── * Store / Customer Service
|   |   |   └── * Short snippet with link to /volunteer/store (or /store/volunteer ?)
|
|
├── /donate
|
├── /shop
|
├── /contact
|   └── Hours and Directions

```
