# The Irish Golf Society

![The Irish Golf Society](readme-files/am-i-responsive.JPG)

## UX

### Who are we?

The Irish Golf Society is a fictional Golf society, organising premium Golf days, in a long running societal format. The main ethos for the society is to encourage golfers of any ability/background to enjoy great experiences in friendly and inclusive environment. 

Founded by two brothers, John and James Herron who felt as though there was a niche in the market for golfers who wanted the opportunity to play premium courses for much better value than was being offered in the open market.

To provide context, they have devised the following networking business model:

1. Collaborate with the most forward-thinking premium Golf Clubs around to purchase blocks of tee-times for discounted prices (by economies of scale) in advance. 
2. Collaborate with key players in the Golf market to provide great prizes through sponsorship. 
3. Aggressively market the society and it's benefits/ethos through postering in clubs and a website. 
4. Gain traction for community growth through word of mouth/social media from participants regarding enjoyment/value/fulfillment of events attended/prizes won/free stuff accrued.
5. Greater number of community players involved = greater purchasing econmies of scale/greater value for sponsors.

The future vision for the society is the evolve into a "Club" type of organisation. Where members pay a yearly fee, and can not only play organised events but can play premium courses on a significant discount from the open market. 

The website can be viewed [here](https://cldwlkn13.github.io/irish-golf-society/).

### Why do the IGS need a website?

1. As a marketing tool to new potential players.
2. An interface to register for an event of the user's choosing through the registration form.
3. Source of society news.
4. Results/Leaderboard information for existing participants. 
5. Sponsorship affiliation.

### User Stories 

- As the society director, I want to be able to attract new players to register for an event. 
- As the society director, I want to ensure that my sponsors are well represented where possible and their homepages can be easily navigated to. 
- As the society director, I want the user to be able to find the information they require quickly through well designed naviagtion.
- As the society director, I want the user to be able to access our social media links easily from each page. 
- As a potential customer, I want to see the benefits of why I should register for an event.
- As a potential customer, I want to see what other people have been saying about their experiences with the IGS. 
- As a potential customer, I want to be able to see what events are upcoming. 
- As a potential customer, I want to be able to see where I can contact the IGS to ask a question. 
- As an existing customer, I want to be able to see my results and position on the leaderboard. 
- As an existing customer, I want to be able to get directions to the course where I will be playing. 
- As a sponsor, I want to see that my brand is being promoted on the site. 
- As a Golf Club owner, I want to see the event scheduled is being promoted. 


### Wireframes

Wireframes were designed using Microsoft Powerpoint and images of the slides can be viewed in the following table:

|    Desktop   |    Tablet    |    Mobile    |
|    :----:    |     :----:   |    :----:    |
|[Home Page](wireframes/desktop/homepage-desktop.JPG)|[Home Page](wireframes/tablet/homepage-tablet.JPG)|[Home Page](wireframes/mobile/homepage-mobile.JPG)|
|[Calendar](wireframes/desktop/calendar-desktop.JPG)|[Calendar](wireframes/tablet/calendar-tablet.JPG)|[Calendar](wireframes/mobile/calendar-mobile.JPG)|
|[Standings](wireframes/desktop/standings-desktop.JPG)|[Standings](wireframes/tablet/standings-tablet.JPG)|[Standings](wireframes/mobile/standings-mobile.JPG)|

---

## Features 

**Header** contains
- **Society Name/Logo** Easily identifiable branding
- **Responsive Navigation Bar** Facilititates site navigation in a common intuitive way.
*The header is fixed at the top of each page, always visible. 


**Footer** contains
- **Key Sponsor Links** Branded links to the IGS key sponsors, allowing users to navigate to their homepages in new tabs. 
- **Social Media Links** Links to the societies social media accounts (actual accounts for the IGS do not exist).
- **Contact details** Address, email (with mailto link) & phone number to contact the IGS. 
*The footer is available at the bottom of each page


**Home Page** contains
 - **About Us** to provide a little bit of background about the society
 - **Latest News** so users can easily log on and see any developments
 - **Marketing/Testimonials** so potential customers can be attracted to register for an event
 - **Next Event - Call to Action** so all users can easily see what the next upcoming event is and register for it. 


**Calendar** contains
  - **List of Upcoming Events** each containing
    - **Directions** so users can physically navigate to the course via Google Maps
    - **Call to Action** so users can register for an event
    - **Prize Informstion** so that users can see the exciting prizes on offer if they register


**Standings** contains
  - **Men's Leaderboard table** so Men can see their position on the leaderboard
  - **Ladies' Leaderboard table** so Ladies can see their position on the leaderboard


**Register Form**
  - **HTML5 form** so a user can input all the relevant information to register for an event. 
  
### Feature Roadmap

**Standings**
 - Leaderboards compile from database of score information, rather than displayed from typed HTML. 

**Register Form**
 - Form should select the correct event in the event dropdown depending on the source of the click. 
 - Form should persist information to a database upon submit. 
 - User should be notified of action success/fail.
  
 ## Technologies

**Development:**
- [GitHub](https://github.com/) - site host.
- [Gitpod](https://gitpod.io/) - dev IDE.

**Key content and styling:**
- [HTML5](https://en.wikipedia.org/wiki/HTML5) site content
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) site styling
- [Bootstrap](https://getbootstrap.com/) - project layout & additional styling

**Supplementary technologies**
- [Google Fonts](https://fonts.google.com/) - source of fonts for the site.
- [Font Awesome](https://fontawesome.com/) - various Icons for abstract marketing as well as social media branding
- [Am I Responsive?](http://ami.responsivedesign.is/) - responsiveness visualisation.
- [Microsoft Powerpoint](https://en.wikipedia.org/wiki/Microsoft_PowerPoint) - wireframe designs.

## Testing

**HTML Validation**
- **[Home Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcldwlkn13.github.io%2Firish-golf-society%2F)** : 3 errors

 ![Home Page Html Validation](readme-files/homepage-html-errors.JPG)
 *The errors listed above were ignored as the headings for this page were handled in a different manner.
 
- **[Calendar](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcldwlkn13.github.io%2Firish-golf-society%2Fcalendar)** : 0 errors

 ![Calendar Html Validation](readme-files/calendar-html-errors.JPG)
 
- **[Standings](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcldwlkn13.github.io%2Firish-golf-society%2Fstandings)** : 0 errors

 ![Standings Html Validation](readme-files/standings-html-errors.JPG)
 
- **[Register](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcldwlkn13.github.io%2Firish-golf-society%2Fregister)** : 0 errors

 ![Register Html Validation](readme-files/register-html-errors.JPG)
 
 **CSS Validation**

 ![CSS Validation](readme-files/css-errors.JPG)
 
 **Responsiveness Quality Testing**
 
 *Testing conducted on [Responsive Design Checker](https://responsivedesignchecker.com/)
 
 - **Mobile**
 
  ![Mobile Testing](readme-files/mobile-testing.JPG)
 
 - **Tablet**
 
  ![Tablet Testing](readme-files/tablet-testing.JPG)
  
 - **Desktop**
 
  ![Desktop Testing](readme-files/tablet-testing.JPG)
 
**Browser Compatibility** 

 - **Google Chrome** No issues identified. 
 
 - **Microsoft Internet Explorer**
    - [Ticker Issue](readme-files/ie-ticker-bug.JPG) The animation on the ticker can be intermittently faulty.
    - The background of the Register form does not show correctly.
    - The Glow effect on the navbar does not work as expected.  
  
 - **Microsoft Edge** No issues identified. 
   
 - **Mozilla Firefox** No issues identified. 
    
 - **Opera** No issues identified. 
 
 
**User Story Testing**

- As the **society director**, I want to be able to attract new players to register for an event. 
  - User can see attractive site design, with lots of relevant information on the homepage. Can also identify the next upcoming event and information pertaining to it. 

- As the **society director**, I want to ensure that my sponsors are well represented where possible and their homepages can be easily navigated to. 
  - Key sponsor links are available in the footer on each page. 
  - Sponsors are referenced in other news articles where relevant.
  - Sponsor links correctly open in a new browser tab when clicked. 

- As the **society director**, I want the user to be able to find the information they require quickly through well designed naviagtion.
  - Navigation bar is avaiable fixed to the top of each page. At smaller screen sizes the menu collapses to an attractive dropdown. 

- As the **society director**, I want the user to be able to access our social media links easily from each page. 
  - Social media links are available in the footer of each page. 
  - They open in a new browser tab when clicked. 
 
- As a **potential customer**, I want to see the benefits of why I should register for an event.
  - The four key reasons why to register are neatly presented on the homepage.
  - Some background information about the society is presented at the top of the homepage.
  - Testimonial quotes are presented on the homepage.
 
- As a **potential customer**, I want to see what other people have been saying about their experiences with the IGS.  
  - Testimonial quotes are presented on the homepage.

- As a **potential customer**, I want to be able to see what events are upcoming.
  -  Next Upcoming Event presented in its own section on the homepage. 
  -  Calendar page displays the full list of upcoming events.

- As a **potential customer**, I want to be able to see where I can contact the IGS to ask a question.
  - Contact information, including mailto email link available in the footer of each page. 
 
- As an **existing customer**, I want to be able to see my results and position on the leaderboard.
  - Standings page has two tables with the current leaderboard standings for Men and Women. 

- As an **existing customer**, I want to be able to get directions to the course where I will be playing. 
  - Directions to the course, in the form of a link to Google Maps is available in each section of the calendar page. 
 
- As a **sponsor**, I want to see that my brand is being promoted on the site. 
  - Key sponsor links are available in the footer on each page. 
  - Sponsors are referenced in other news articles where relevant.
 
- As a **Golf Club owner**, I want to see the event scheduled is being promoted. 
  - Calendar page shows all the upcoming events with attractive images and links to the Club's homepage. 

**Bugs**
 - The scaling of HTML table on the standings page was quite poor without some alterations to the font size and paddings in the media queries. 
 - The timeline "Latest News" feature did not perform well at lower screen sizes. The circles and the lines became detached. So at the smaller sizes a design decision was made to remove the line. 
 - The duration of the ticker animation was poor when implemented and would not show the full information before commencing the next loop. This was fixed by amending the 'animation-duration' property to 40 seconds. 
 - Trying to click the links in the ticker was troublesome as the ticker did not pause and the user could physically miss the link. So a pause on hover action was implemented. 
 

## Deployment

**To deploy**

The Irish Golf Society is hosted on **GitHub Pages**

1. In the GitHub repository select **Settings**.
2. The **Pages** section is 75% down the page, scroll here. 
3. In the **Source** dropdown menu select **master**.
4. The website is now deployed.

**To clone from Github**

1. In the Github repository click the green **Code** button.
2. Select clone protocol of your choice (SSL/HTTP/CLI)
3. Go to your IDE.
3. Open **Git Bash**.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type **git clone**, and then paste the URL copied from GitHub.
6. Press **enter** and the local clone will be created.

*for more information on cloning in git hub, please see [github cloning documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

## Credits
As this project is ficticious, the majority of the content was imagined and devised by myself. 
 
[svgbackgrounds](https://www.svgbackgrounds.com/) for the background theme on each page. 

[lewismcarey](https://codepen.io/lewismcarey/pen/GJZVoG) for providing the source code idea for the ticker. 

[W3Schools](https://www.w3schools.com/) for providing various tips and tricks throughout the development process, in particular the "Latest News" timeline feature.

The pictures of the Golf courses mentioned in this site were sourced from the following locations:
https://www.top100golfcourses.com/
https://www.scotsman.com/
https://www.golfdigest.com/
https://images.squarespace-cdn.com/
https://www.druidsglenresort.com/
https://irishgolfer.ie/
https://www.oldgroundhotelennis.com/
https://www.golfholidays.com/


## Acknowledgments

[Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/?originalSubdomain=ng) for all his support and guidance.

I would also like to thank Susan for their feedback and support through this process!
