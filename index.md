#### [Fringe Notes](/fringe-notes.md)
#### [Markdown Cheat Sheet](/markdown-cheat-sheet.md)
#### [Franchise Notes](/franchise-notes.md)

# CTG Notes

## Confetti Bits Notifications Stuff

- Notifications registered as a component in its component class in bp-notifications/classes/class-bp-notifications-component.php
- The notifications component class extends the standard BP_Component class
- "The ```extends``` keyword is used to derive a class from another class. This is called inheritance. A derived class has all of the public and protected properties of the class that it is derived from."
- Component class is defined in bp-core/classes/class-bp-component.php
- A new component needs: str $id, str $name, str $path, and array $params set up in the construct function
- The way buddyboss builds the path is by trail slashing the plugin_dir_path to the plugin file and then the bp_source_subdirectory, which is just an empty string I guess? We could probably just do a trailing slashed stylesheet directory for this.
- How do they increment their action ids and stuff in the database? That's wild
- Maybe check some of their other component notifications files
- There might be an incrementer in those functions somewhere


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
- [x] Chadlynn
- [x] David
- [x] Jacqueline
- [x] Jen
- [x] Jody
- [x] Luis
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


## Sales & Marketing Stuff 3.28.22

- ~~Spirit animals???~~
- I just said my fav animal is an elephant
- Koopid/Gail stuff
- Chat bot net sheets go to Rob & Robin now
- Gail marketing stuff goes out April 11th

### To-Do Stuff

- [ ] Confetti Bits Notifications
- [ ] Confetti Bits Transfer Panel
- [ ] Any CTG-Houston edits
- [ ] Send Ali training vid repository
- [ ] Coffee Bag stuff
- [x] Spanish CTG Rack Card

### 4.4.22

Wins this week:
---
- I've made a lot of progress on Confetti Bits Notifications
- CTG Links is fully live
- Our SEO is outstanding

Here's the to do list of stuff I started the week with, and their statuses
---
*Done:*
- Made progress on Confetti Bits notifications
- Franchise page tweaks
- Create the rest of the SP pages
*Not done:*
- Make progress on Confetti Bits transfer

Here's a list of stuff that got added on over the week (this is the "unseen" and/or last-minute stuff I'm always talking about):
---
*Done:*
- Fielded a lot of TeamCTG bug reports
- Verified several more locations on Google
- Continue filtering through bug reports
*Not done:*
- I need to upload a few Celebrate U classes that are sitting in my inbox

Must do:
---
- Confetti bits notifications update

5 goals:
---
- Not lose sanity
- Start getting some functionality from Confetti Bits Notifications
- Set schedule for CTG site updates; get Anika to compile them into a list for EOM changes
- Refer people to bug report system and/or make form submission for bug reports
- Send ins-and-outs of including a franchise location on GatherUp to Laurel

Challenges:
---
- Loads of bug reports and dev requests, seriously so many random emails about things either not working properly or updates people want to (insert website here).com

Misc updates/notes:
---
- Edited a lot of super cool pics for Fringe show!

Candy Bag items
---
- Text notifications for events
- Email notifications for events

Any classes/courses/education you took this week and what you got out of it!
---
I've been reading through tons and tons and tons of code, and I've narrowed down some more key things that help build some components for TeamCTG
Learning a million and one things about object-oriented programming. I've also built the object for a Confetti Bits notifications component, so now I need to add some functionality and extra methods, and we should be good to go!


#### Gail marketing stuff goes out April 11th


Wins this week:
---
- We had a shoot on Thursday that I think we got a lot of good footage from

Here's the to do list of stuff I **started the week with**, and their statuses
---

**Done:**
- Made progress on Confetti Bits notifications

**Not done:**
- Make progress on Confetti Bits transfer panel

Here's a list of **stuff that got added on** over the week (this is the "unseen" and/or last-minute stuff I'm always talking about):
---

**Done:**
- Learned how to balance the gimbal on Wednesday
- Helped shoot on Thursday
- Got a decent number of videos onto Houton SharePoint

**Not done:**
- I need to upload a few Celebrate U classes that are sitting in my inbox
- I need to send Ali instructions for Google verification

Must do:
---
- [ ] Confetti bits notifications update
- [x] Send Ali instructions for Google verification

5 goals:
---
- Not lose sanity
- Start getting more functionality from Confetti Bits Notifications
- Set schedule for CTG site updates; get Anika to compile them into a list for EOM changes
- Refer people to bug report system and/or make form submission for bug reports
- Get Houston on Google

Challenges:
---
- Object-oriented programming is a travesty of a programming paradigm, and it should burn in hell
- I lost a couple days this week helping out with some other stuff, but should be back on track now

Misc updates/notes:
---
- I changed my brakes! I am also entirely out of money. But the main thing is that I have new brakes now.
- I'm learning a lot about object-oriented programming, which is a grueling but ultimately very useful skill.

Candy Bag items
---
- The big QR code campaign

Any classes/courses/education you took this week and what you got out of it!
---
- I've almost completely hooked Confetti Bits into the TeamCTG platform
- I learned how to create and implement action and filter hooks
- I learned a better way to autoload classes to make them publicly accessible throughout the program
- I learned a million new functions and how to hook into them to build onto TeamCTG even more



### "Focusing on Urgency"
- Focus on what's important
- Ask questions like "What is the absolute dead date you need this by?"
- We have a lot of things open but no absolute deadlines
- Generally with projects and when we're asked, we determine deadlines according to us, and don't typically ask when their deadline is
- We usually have to create things when people ask us for something


#### Pending
- Boxes are back
- 




