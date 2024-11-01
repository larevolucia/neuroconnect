# NeuroConnect

Neurodivergent individuals (such as those with autism, ADHD, dyslexia, etc.) often face unique challenges in daily life. For expats, these challenges are exacerbated by unfamiliarity with the healthcare system, lack of government support, language barriers, and isolation from social networks.

Despite growing international awareness and a significant increase in diagnoses, support for expats remains limited, making it difficult to find professional guidance and community resources.

This site aims to create a community hub for autistic expats and their families in Amsterdam, the Netherlands. With an inclusive approach, it seeks to provide support to individuals from diverse social and economic backgrounds, offering a range of services, from professional assistance by certified coaches to volunteer-led community support and social events.

Live Link to access site [here](https://larevolucia.github.io/neuroconnect/)

<img width="783" alt="image" src="https://github.com/user-attachments/assets/25618673-f2e1-4bfb-8148-1851badb638a">

## Site Goals

- To provide the user with information about the services provided by NeuroConnect.
- To foster a sense a community by sharing with the user information about the events organized by NeuroConnect's community.
- To present the user with a website that is easy to navigate and fully responsive, taking into consideration target audience's sensory and cognitive sensitivities.
- To enable user to contact the service for more information on provided services.
- To allow user to confirm their presence in events organized by the community.

 For additional information check [Project Scope Definition](https://github.com/larevolucia/neuroconnect/issues/1#issue-2568780667)

## User Stories

### First Time Visitor
- [As a first time visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.](https://github.com/larevolucia/neuroconnect/issues/4#issue-2572432780)
- [As a first time visitor, I want to see all essential information without navigating to additional pages, so I can easily understand it's purpose without cognitive overload.](https://github.com/larevolucia/neuroconnect/issues/5#issue-2572442456)
- [As a first time visitor, I want to know how can I get in touch for basic questions, so I can clear any doubts I might have.](https://github.com/larevolucia/neuroconnect/issues/10#issue-2572618599)

### Potential Member

- [As a potential member, I want to be able to easily understand which services are provided, so I can decide which service is the best for my individual needs.](https://github.com/larevolucia/neuroconnect/issues/6#issue-2572505207)
- [As a potential member, I want to know how to get in contact with them, so I can request additional information or request their services.](https://github.com/larevolucia/neuroconnect/issues/8#issue-2572575084)

### Community Member 

- [As community member, I would like to learn about events in the autistic community so I can find a safe space and create a social network that understands me.](https://github.com/larevolucia/neuroconnect/issues/7#issue-2572530226)
- [As a community member, I want to know how can I participate on activities, so I can build a social network and feel part of a community.](https://github.com/larevolucia/neuroconnect/issues/9#issue-2572587684)


### Backlog 

- [FAQ page](https://github.com/larevolucia/neuroconnect/issues/15#issue-2575964343)
- [About the team](https://github.com/larevolucia/neuroconnect/issues/11#issue-2572631278)
- [Newsletter sign-up](https://github.com/larevolucia/neuroconnect/issues/12#issue-2572647336)
- [Volunteer form](https://github.com/larevolucia/neuroconnect/issues/14#issue-2572676949)
- [Testimonials](https://github.com/larevolucia/neuroconnect/issues/13#issue-2572653776)

## Design

Design choices took in consideration insights from web design research done with autistic individuals. There's a minimal page structure variation and use of imagery to reduce cognitive load.

## Images

Research with target audience on preference of information in text vs in image is not conclusive. With that in mind, it was chosen to use images withou excess to convey additional information for individuals that process through images, while keeping a suscint text for those who process through written communication. 

While chosing images there was an attempt to chose images with not too many colors or elements with the intent to making them easy to digest.

### Colors

The colors selected for the site were chosen based on research done with autistic users, where it was pointed out that blues and green where calming colors. The palette was generated by Coolors platfomr and tweaked to achieve contrast values required by WCAG guidelines.

<details>
  <summary>Color Palette</summary>
<img width="783" alt="image" src="https://github.com/user-attachments/assets/34c8d774-5cb1-4708-a237-c90b31f3326c">
</details>


### Fonts

Lexend font was selected for the body font, due to it's readability characteristics. Considering that there is an overlap between autism and dyslexia, having a dyslexic-friendly font was deemed as a must. 
Roboto Slab was selected as a heading font to help differentiating levels of importance of content. 
Both fonts are imported via [Google Fonts](https://fonts.google.com/)

For additional information check [Design Research](https://github.com/larevolucia/neuroconnect/issues/3#issue-2571162628)

### Buttons States

<details>
  <summary>Primary Button States</summary>
<img width="489" alt="image" src="https://github.com/user-attachments/assets/cc6cfacb-e7ff-4193-9751-919f92b84a05">
</details>


### Anchor States

<details>
  <summary>Primary Anchor States</summary>
<img width="283" alt="image" src="https://github.com/user-attachments/assets/70dbfe17-9c03-4c28-94d7-754f6b7c3062">
</details>

<details>
  <summary>Secondary Anchor States</summary>
<img width="257" alt="image" src="https://github.com/user-attachments/assets/1ca1af53-8644-47e7-9ea8-f657490224ea">
</details>

## Wireframes

<details>
  <summary>Home</summary>
<img width="783" alt="image" src="https://github.com/user-attachments/assets/6f67b120-dfc1-44f1-ad89-fe88870f80a5">

</details>
<details>
  <summary>Services</summary>
<img width="783" alt="image" src="https://github.com/user-attachments/assets/51aea832-bd1e-446b-8bcf-c1756aa25d73">

</details>
<details>
  <summary>Events</summary>
<img width="783" alt="image" src="https://github.com/user-attachments/assets/1bbc0616-cecc-4411-8591-6ad47bce59a2">

</details>

## Features

### Navigation

- Fully responsive navigation bar with design optimitization is achieve by the use of media queries. 
- Small screens use a left side logo and a right side menu icon to optimize space. 
- Click behavior on menu icon on smaller screen are achieve by using a checkbox input that is set to hidden. The icon is set as checkbox label. 
- Larger screens display site's name along with logo and display site's section horizontally. Menu icon is hidden using media queries.
- Distinctive color is used to indicate active page. Softer color is used to indicate cursor hover.
- Fixed navigation was achieven using position:sticky together with left and top attributes to set its position on screen.
- It was decided not to nest ```<nav>``` element in the ```<header>```, due to [accessibility recommendations](https://dev.to/masakudamatsu/don-t-nest-nav-inside-header-do-nest-the-hamburger-menu-button-inside-nav-6cp).

![navigation](https://github.com/user-attachments/assets/c1be2633-87ef-4696-81ed-0084fd3d43da)

Inspiration: [Love Running](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/3.6-making-the-header-responsive)


### Skip to Main Content

- A link to skip to the main content was included to facilitate navigation using keyboard. 
- Link has fixed position with negative top value, making it hidden for users. Link becomes visible if user press tab on page first load due to change on fixed position using :focus pseudo class.

  ![accessibility-skip-content](https://github.com/user-attachments/assets/bc66199c-8c93-4226-a250-a24725435fd4)


Inspiration: [BBC](https://www.bbc.com/) / [a11y-collective](https://www.a11y-collective.com/blog/skip-to-main-content/)

### Header 

- All pages follow the same ```<header>``` structure for design consistency necessary to reduce cognitive load when navigating in a new site.
- Hero banner uses ```background-image``` property to populate the HTML with it's content using distinctive ids.
- Overlay text is positioned near the bottom right corner of the image using ```position: absolute```. A semi-transparent ```background-color``` is applied to the text container to ensure readability.

<img width="1255" alt="image" src="https://github.com/user-attachments/assets/60a8c0aa-46d1-4f4d-acde-478e209a90bb">

<details>
  <summary>Service Page Header</summary>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/7c425d03-f555-4a54-a661-c69d13800ba7">
</details>

<details>
  <summary>Events Page Header</summary>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/5bedb7a9-89bd-4e40-8b18-48a708b90d9e">
</details>

Inspiration: [Love Running](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/3.6-making-the-header-responsive)

### Page Summary

- All pages have a summary positioned as the first ```<section>``` in the ```<main>``` element.
- ```<h2>``` titles were added as hidden to comply with SEO best practices. They were made visible to reduce noise on pages.

<img width="1198" alt="image" src="https://github.com/user-attachments/assets/bf5bcbff-9e2e-494b-9556-bcf6f6a58e73">

<details>
  <summary>Service Page Summary</summary>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/8f898a26-5dbe-417d-802b-cc4431a49424">
</details>

<details>
  <summary>Events Page Summary</summary>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/0c60b3d4-6a65-428a-a304-723de070b811">
</details>

### Summary of Services and Events

- To ensure that user would get all the essential information in the home, it was included an area with a summary of Services and Events pages.
- Responsive design was achieved using ```display: flex``` applied to content cards. 
- For performance optmization, images on content cards are inside of ```picture``` element, with a ```source``` for bigger screens, another for smaller screens and a ```<img>``` as fallback.
- Anchor links styled as buttons redirect user to the specific pages within the website.

<img width="734" alt="image" src="https://github.com/user-attachments/assets/aae59c5c-f5d2-4101-8b8c-df4cf8b6641d">


### Services 

- More in-depth information about the services is provided in ```<main>``` element of the Services pages.
- Responsive design was achieved using ```display: flex``` applied to ```<main>```. 
- As the page is more text heavy, it was decided to use [Fontawesome](https://fontawesome.com/) icons as visual conterparts to reduce visual stimuli on page.
- Feedback of initial design was still deemed text-heavy, so a new design with a collapsible element was implemented on commit [5d11e3a](https://github.com/larevolucia/neuroconnect/commit/5d11e3a1214a45294f81af5cc2b01f3dee0ec9ef). More on [issue #25](https://github.com/larevolucia/neuroconnect/issues/25#issue-2619050363)

![collapsible-items-](https://github.com/user-attachments/assets/79fbf5d1-dfb9-4706-baf7-8cc50a312f30)

Inspiration: [SVB.nl](https://www.svb.nl/nl/algemeen/over-onze-website) / [Digitalocean](https://www.digitalocean.com/community/tutorials/css-collapsible) / [Stackoverflow](https://stackoverflow.com/questions/14736496/use-font-awesome-icons-in-css) 

### Get in Touch Form

- Form with responsive design was included as an interactive element which enables user to request one of the listed services.
- Responsive design was achieve using ```display:grid``` on form's container.
- Form fields includes: 
  - Full Name ```<input type="text">```
  - Phone Number ```<input type="tel">```
  - Service options ```<input type="radio">```
  - Message ```<textarea>```
  - Method of contact ```<input type="radio">```
- All fields, except the message is marked as ```required```.
- Pattern was included in phone number field using regular expression to allow only digits. ```title``` was included to the ```input``` element, to show feedback to user about the required pattern.
- Style for field ```:focus``` was modified using a ```border-color``` and ```box-shadow.
- An attempt to provide the feedback on the same page was made using javascript on commit [3839167](https://github.com/larevolucia/neuroconnect/commit/383916767a50d356ed5d5551eb1499fc06b8d206). Attempt is document in [issue #9](https://github.com/larevolucia/neuroconnect/issues/9#issue-2572587684). Experience was simplified and when submitted, form leads user to a success page with message and anchor link styled as button to redirect user back to main page.

  
<img src="https://github.com/user-attachments/assets/5f70036e-5d37-4028-8121-87744748b556" width="680">


Inspiration: [Bootstrap Content Cards](https://getbootstrap.com/docs/5.3/components/card/) / [Bootstrap Forms](https://getbootstrap.com/docs/5.3/forms/form-control/)

### Events 

- Summary of the events is displayed as content cards on Events page. 
- Responsive design is achieve by using ```display: flex```
- Content card contains:
  - One landscape image to visually communicate the event's activity
  - Overlay box using ```position: absolute``` and semi-transparent ```background-color``` providing events' date and location 
  - Event title
  - Short summary of the event
  - Button to sign-up for event (small/medium screens only)
- Content cards suffered redesign through out the development process due to negative feedback received by target audience. Process is documented in [issue #19](https://github.com/larevolucia/neuroconnect/issues/19#issue-2608656036)
- For performance optmization, images on content cards are inside of ```picture``` element, with a ```source``` for bigger screens, another for smaller screens and a ```<img>``` as fallback.
  
<img src="https://github.com/user-attachments/assets/3bb2295d-8a58-43a4-ab61-db045ff777d3" width="680">


### Join Event Form

- Form responsive design was achieve using ```display:grid```
- Focus style used for **Get in Touch Form** were also used in this form
- Form fields includes: 
  - Full Name ```<input type="text">```
  - Phone Number ```<input type="tel">```
  - Events options ```<input type="radio">```
  - Spots to reserve ```<input type="number">```
- All field are marked as ```required```.
- Field destinated for the amount of spots to reserve had additional ```min``` and ```max``` values to ensure that user reserves for at least 1 spot and not more than 10.
- One of the events radio buttons is marked as ```disabled``` to indicate that is already fully booked.
- Form submission leads to a success page with message and anchor link styled as button to redirect user back to main page. 

<img src="https://github.com/user-attachments/assets/1746cedb-2d57-4f77-b6d8-71bddf9086b0" height="680">


Inspiration: [Boardwalk Games](https://github.com/Code-Institute-Solutions/boardwalk-games-v1-sourcecode/tree/main)

### Footer

- Footer includes address, contact e-mail, site map and social media links.
- Responsive design of ```<footer>``` is achieve by using ```display: grid```
- Contact e-mail link uses ```mailto:``` to open e-mail server with empty draft

<img width="1206" alt="image" src="https://github.com/user-attachments/assets/962192fa-39f6-4e4e-9dda-81c6929b7dd6">

## Testing

### Manual Testing 
[issue #18](https://github.com/larevolucia/neuroconnect/issues/18#issue-2575994140)

- Tested all internal links lead to a valid page
- Tested that all external links open in a new window
- Checked for aria-labels in buttons
- Checked for aria-labels in anchors
- Tested form for required fields
- Tested for submission leads to success page
- Tested responsive design using Chrome DevTools, Firefox DevTools and Responsinator.
- Tested multiple browsers: Chrome, Edge, Safari, Firefox
- Tested multiple devices: iPhone, Android Galaxy22, Windows Desktop

### Automated Testing  
[issue #17](https://github.com/larevolucia/neuroconnect/issues/17#issue-2575988664)

- [HTML Validator](https://validator.w3.org/nu/#textarea)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Accessibility Checker](https://www.accessibilitychecker.org/): Avg score 85%. No Critical issues. 
- Lighthouse Scores:

    <details>
      <summary>Home Mobile</summary>
      <img width="459" alt="image" src="https://github.com/user-attachments/assets/a2f0a205-777d-4789-ad8a-e40f1d45d191">
    </details>
    <details>
      <summary>Home Desktop</summary>
      <img width="473" alt="home_desktop_lh" src="https://github.com/user-attachments/assets/d6eafeaa-e7c8-4c62-82a7-3f8553b90f11">
    </details>  
    <details>
      <summary>Services Mobile</summary>
      <img width="473" alt="services_mobile_lh" src="https://github.com/user-attachments/assets/583b7a68-e0b3-49aa-b32c-daf98ea2b4f4">
    </details>
    <details>
      <summary>Services Desktop</summary>
      <img width="428" alt="services_desktop_lh" src="https://github.com/user-attachments/assets/e9ff6c09-b969-40bb-bca6-a2055ab58ece">
    </details>
    
    <details>
      <summary>Events Mobile</summary>
      <img width="461" alt="events_mobile_lh" src="https://github.com/user-attachments/assets/a45abf62-98b8-4a12-91a6-b21617fabb40">
    </details>
    
    <details>
      <summary>Events Desktop</summary>
      <img width="457" alt="events_desktop_lh" src="https://github.com/user-attachments/assets/4babb2b7-378e-4454-aac0-42f88dd76e06">
     </details>
    
    <details>
      <summary>Success Page (Services) Mobile</summary>
      <img width="473" alt="sucess-services_mobile_lh" src="https://github.com/user-attachments/assets/da06be16-ad34-4fd6-9051-d598de9947a9">
    </details>
    <details>
      <summary>Success Page (Services) Desktop</summary>
       <img width="431" alt="sucess-services_desktop_lh" src="https://github.com/user-attachments/assets/987a0e36-addb-445d-b79d-3f761d35689c">
    </details>
    <details>
      <summary>Success Page (Events) Mobile</summary>
      <img width="466" alt="success-events_mobile_lh" src="https://github.com/user-attachments/assets/89be02e2-bd2f-42a4-8417-9e646a46091a">
    </details>
    <details>
      <summary>Success Page (Events) Desktop</summary>
       <img width="454" alt="success-events_desktop_lh" src="https://github.com/user-attachments/assets/29224b54-5ae1-4949-a471-c88742c9e30f">
    </details>



### Accessibility Testing  
[issue #16](https://github.com/larevolucia/neuroconnect/issues/16#issue-2575978267)

- Checked if buttons, links and labels used ```aria-labels```.
- Check if all images had ```alt-text```.
- Used [Contrast Checker](https://webaim.org/resources/contrastchecker/) to validate text visibility.
- Checked the usage of Semantic elements.
- Checked visual order follows DOM order using [WAVE](https://wave.webaim.org/) 
- Validated [Design for Target Group #3](https://github.com/larevolucia/neuroconnect/issues/3#issue-2571162628) with autistic friends
- Checked for errors and alerts on [WAVE](https://wave.webaim.org/) 

### Peer Review and User Feedback

The code was submitted for peer review in the Code Institute community and also received feedback from friends and acquaintances that match the target audience (autistic community).

- Lack of user feedback on required format for phone number. Removed phone pattern checked on [351398a](https://github.com/larevolucia/neuroconnect/commit/351398a) and reintroduce with added user feedback on [48a1d4f](https://github.com/larevolucia/neuroconnect/commit/48a1d4f9acb4d91f04431e66e8f9219ff2f36841)
- Puzzle pieces might be considered offensive. Fixed on [ccd7a82](https://github.com/larevolucia/neuroconnect/commit/ccd7a82).
- Overwhelming design on Events page. Fixed on [ec50ab1](https://github.com/larevolucia/neuroconnect/commit/ec50ab1). More on [isue #19](https://github.com/larevolucia/neuroconnect/issues/19#issue-2608656036)
- Text heavy design on Services page. Fixed on [5d11e3a](https://github.com/larevolucia/neuroconnect/commit/5d11e3a). More on [issue #25](https://github.com/larevolucia/neuroconnect/issues/25#issue-2619050363)

### Bugs & Issues

All issues are documented in this [Project View](https://github.com/users/larevolucia/projects/3/views/4)

- Jigsaw CSS validator error: unkown pseudo-class :user-valid. Although documentation on it can be found online at [W3 School](https://www.w3schools.com/cssref/sel_user-valid.php) and and [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/:user-valid), I chose to remove it and simplify the form validation experience. Documented on [issue #20](https://github.com/larevolucia/neuroconnect/issues/20#issue-2611899383)
- Click on label was not selecting corresponding radio button option on forms. Using the W3 check I found that it was due to duplication of ids on content cards and radio buttons. I renamed the content cards id's to be able to fix it. Documented on [issue #21](https://github.com/larevolucia/neuroconnect/issues/21#issue-2612109157)
- Code clean-up lead to home button misalignment on large screens. To fix it I added a ```min-heigh``` to the ```.card-text``` class on media query for large screens. Documented on [issue #22](https://github.com/larevolucia/neuroconnect/issues/22#issue-2614516551)
- Initial mobile score for performance was around 75. To improve the score I converted images to webp format, set ```loading="lazy"``` and added difference sources depending on screen size using ```<picture>``` + ```<source>```. Documented on [issue #24](https://github.com/larevolucia/neuroconnect/issues/24#issue-2618947783)
- [WAVE](https://wave.webaim.org/) flagged label used for burger menu as an error. To fix it, I added a span to add the text "Menu". To hide it from users, I added a class with ```display: none```. Docummented on [issue #26](https://github.com/larevolucia/neuroconnect/issues/26#issue-2626933126)
- [WAVE](https://wave.webaim.org/) flagged ```alt-text``` from a image on home with an alert. To fix it, I changed the text to remove redundancy of "Image of" and made more concise. Docummented on [issue #26](https://github.com/larevolucia/neuroconnect/issues/26#issue-2626933126)
- After changing image cards to use ```<picture>``` with specific ```source``` for screen distinct screen sizes, the image on home for the events was broken on mobiles. That was due to a broken url, which was fixed on [61c780d](https://github.com/larevolucia/neuroconnect/commit/61c780df34f5e0a4931dca4c1acae4fae431ad9f). Documented on [issue #27](https://github.com/larevolucia/neuroconnect/issues/27)

## Deployment

This project was deployed using GitHub pages. Steps to deploy are as follow:

1. Go to your repository on GitHub.com
2. Select 'Settings' on the repository top menu.
3. Select 'Pages' on the left side menu.
4. Under 'Build and deployment', go to 'Branch' dropdown and select 'main'.
5. Ensure that the selected folder is /root
6. Once done, click on 'Save'.
7. You should receive a deployment confirmation, followed by the web address.

## Technologies Used

### Languages

- HTML5
- CSS

## Resources Used

- [Mozilla](https://developer.mozilla.org/en-US/)
- [w3.org](https://www.w3.org/)
- [Dev.to](https://dev.to/)
- [StackOverflow](stackoverflow.com)
- [a11y-collective](https://www.a11y-collective.com/)
- [Coolors](https://coolors.co/)
- [Google Fonts](https://fonts.google.com/)
- [Freepik](https://www.freepik.com/)
- [favicon.io](https://favicon.io/)
- [FontAwesome](https://fontawesome.com/)
- [Pexels](https://www.pexels.com/)
- [Tinypng](https://tinypng.com/) to optmize the images
- [Responsinator](http://www.responsinator.com/) to test responsiveness
- ChatGPT to assist with creation of content

## Credits

### Content
Content of the page is fictional and created by me. ChatGPT was used on creation of content for consistency of language and character count. 

### Icons
- Favicon design by [Freepik](https://www.freepik.com/icon/infinite_8438654) and converted using [favicon.io](https://favicon.io/)
- Social media icons, burger menu and icons used on Service Page are from [FontAwesome](https://fontawesome.com/)

### Photos
All photos on site are from [Pexels](https://www.pexels.com/)

**Home**
- Banner:[Leeloo The First](https://www.pexels.com/photo/a-woman-holding-cardboard-pieces-with-drawings-7304974/)
- Services: [Alex Green](https://www.pexels.com/photo/ethnic-female-psychotherapist-listening-to-black-clients-explanation-5699479/)
- Events: [Rachel Claire](https://www.pexels.com/photo/people-using-kayak-ok-a-lake-7263736/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)

**Services**
- Banner: [Jorge Urosa](https://www.pexels.com/photo/a-text-on-a-letter-board-9129566/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)

**Events**
- Banner: [RDNE Stock project](https://www.pexels.com/photo/group-of-people-wearing-blue-and-red-shirts-7551752/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)
- Book Club: [Yaroslav Shuraev](https://www.pexels.com/photo/women-covering-their-faces-with-books-9490665/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)
- Game Night:[RDNE Stock project](https://www.pexels.com/photo/man-and-women-playing-cards-at-meeting-in-christmas-6517901/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)
- Hiking Trip:[RDNE Stock project](https://www.pexels.com/photo/people-walking-on-a-pathway-7348737/)
- City Trip: [Sergey Guk](https://www.pexels.com/photo/ferris-wheel-at-sunset-on-the-hague-beach-pier-28688790/?utm_campaign=feedback_request_on_downloads&utm_content=How%20did%20you%20use%20these%20downloads%3F&utm_medium=email&utm_source=pexels)

## Acknowledgments

My mentor Antonio, for his support and guidance.

Code Institute community for the feedback and helpful advices.
