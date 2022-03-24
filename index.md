#### [Fringe Notes](/fringe-notes.md)
#### [Markdown Cheat Sheet](/markdown-cheat-sheet.md)

# CTG Notes

## Confetti Bits Notifications Stuff

- Notifications registered as a component in its component class in bp-notifications/classes/class-bp-notifications-component.php
- The notifications component class extends the standard BP_Component class
- "The ```extends``` keyword is used to derive a class from another class. This is called inheritance. A derived class has all of the public and protected properties of the class that it is derived from."
- Component class is defined in bp-core/classes/class-bp-component.php
- A new component needs: str $id, str $name, str $path, and array $params set up in the construct function
- The way buddyboss builds the path is by trail slashing the plugin_dir_path to the plugin file and then the bp_source_subdirectory, which is just an empty string I guess? We could probably just do a trailing slashed stylesheet directory for this.
- How do they increment their action ids and stuff in the database? That's wild


## To Do 3.24.22
- [ ] Confetti Bits Transfer Panel
- [ ] Bobby's Bandits Events Calendar
- [ ] Success Partner Link Page Setup
- [ ] Processor Koopid Training
- [ ] Crypto Closings Class
- [ ] Value Vault Class

### Sales Folks
- [x] Bailey
- [x] Bea
- [ ] Chadlynn
- [ ] David
- [ ] Jacqueline
- [ ] Jen
- [ ] Luis
- [x] Rob
- [x] Robin

### Coffee Notes
- Need info for where the beans are sourced
- We're doing a valve, neato
- I would like a flavor profile as well
- Go to lineageroasting.com
- Coffee 431 on their website for flavor profile and 
- As long as we have the 
- FDA requires either an address or a website address that displays the supplier
- Other than that, it looks pretty rad
- We'll have a couple canisters next to the neat coffee machine thing
- Set up a separate account for each location
- Roastar for bags, we're ordering probably like 500
- 5 lbs. bag for mass production
- We'll have bags in the office and online for agents mainly and in-office purchase
- We'll lower the quantity to probably about 500 total per quearter or until we run out
- One 5 lbs. bag makes about 100 cups of coffee
- When ordering, just say the quantity and where it's going. We'll get one invoice
- Get pics of the coffee machine
- 676 Cherry St. Unit 2, Winter Park, FL 32789



### Passport
- [ ] Head to Aloma, Winter Park Courthouse


### CTGLinks

**Checking for astra_archive_header()**
- [x] require_once ASTRA_THEME_DIR . 'inc/markup-extras.php';
- [x] require_once ASTRA_THEME_DIR . 'inc/extras.php';
- [x] require_once ASTRA_THEME_DIR . 'inc/blog/blog-config.php';
- [x] require_once ASTRA_THEME_DIR . 'inc/blog/blog.php';
- [x] require_once ASTRA_THEME_DIR . 'inc/blog/single-blog.php';


**Markup Files**
- [x] require_once ASTRA_THEME_DIR . 'inc/template-parts.php';
- [ ] require_once ASTRA_THEME_DIR . 'inc/class-astra-loop.php';
- [ ] require_once ASTRA_THEME_DIR . 'inc/class-astra-mobile-header.php';

**Template Parts**
- [x] content-blog.php
- [ ] blog/blog-layout.php
- [ ] content-search.php
- [x] inc/core/markup/class-astra-markup.php

### **FOUND IT**
INC/CORE/COMMON-FUNCTIONS.PHP LINE 923 starts a function that hooks into ASTRA_ARCHIVE_HEADER()

**Functions and definitions.**

require_once ASTRA_THEME_DIR . 'inc/class-astra-after-setup-theme.php';




