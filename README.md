# Monkees Band Website

The client is a 1960’s rock band that have around 50 years experience of performing live at numerous events around the world. They want to establish an online pressence that will include a contact form and links for their other social media pressence.

## Customer background and request

The following requirements have been provided after interviews with the client’s representatives:
- Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
- Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

## User Stories

- As a user, I want to be able to read the band's information and discography, so I can learn more about the band.
- As a user, I want to be able to hear sound clips from the band's catalog, so I can check the quality and style of the band's music.
- As a user, I want to be able to watch clips from the band's catalog, so I can check the quality and style of the band's appearance and performance.
- As a user, I want to be able to contact the band for availability, so I can hire them to perform on events.
- As a user, I want to be able to find social media links that will point me to other social media accounts from the band, so I can choose my preferred social media app to interact with the band.

## UX
Users of the site would be fans or soon-to-be-fans. Therefore the website should provide easy access to the information that new users would expect from the band profile, but also give some extra to those who are already fans by providing easy to access links to songs and videos.

In order to alleviate the web load, videos would be hosted externally. Music will also load on demand.

The design is mobile-first, as we expect users to be able to listen to the music or watch the videos while commuting, without the need to go to external sites to do this, increasing revenue via embedded ads and/or referral links.

Social media links are also provided and cross-references in each respective social media pressence.

Below some of the initial mockups for the site:
- Mobile design: [Profile](/assets/docs/profile_mobile.png) - [Media](/assets/docs/media_mobile.png) - [Contact](/assets/docs/contact_mobile.png)
- Desktop design: [Profile](/assets/docs/profile_desktop.png) - [Media](/assets/docs/media_desktop.png) - [Contact](/assets/docs/contact_desktop.png)

## Features
### Existing Features
- Band Profile - Allow users to get more information about the band
- Video Carousel - Allow users to check out different featured videos of the band
- Media Showcase - Allow users to listen to different audio tracks from the band
- Future Appearances - Allow users to check out the incoming public shows the band will be playing. This was not included as specific requirement, but it will help the customer to have an overview of scheduled live events to gauge expectations on band's availability.
- Contact Form - Allow users to contact the band, for reservations or further information
- Social Media Icons - Allow users to find other official social media accounts from the band

### Features Left to Implement
- Embedded social media pressence: Twitter widget with the latest interactions from the band, or latest Instagram posts, etc...
- Official chat room, where fans can interact with each other
- Ability for the client to update the content of the website without relying in a developer.

## Technologies Used

### Website
<a href="http://www.w3.org/html/logo/">
    <img src="https://www.w3.org/html/logo/badge/html5-badge-h-css3-device-multimedia-semantics.png" width="229" height="64" alt="HTML5 Powered with CSS3 / Styling, Device Access, Multimedia, and Semantics" title="HTML5 Powered with CSS3 / Styling, Device Access, Multimedia, and Semantics">
</a>

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to provide semantics to blocks of text that improves readability to screen readers and impaired users of the site.
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses **CSS** to provide custom styling and visualization to the site.
- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to provide a common responsive layout that is familiar with other websites on the Internet. It also makes the website fully responsive, created with a mobile-first approach.

### Development
- [GitKraken GloBoards](https://www.gitkraken.com/glo)
    - Boards were used to organize and keep track of issues and feedback while developing the website
- [Cloud9](http://https://c9.io/)
    - Cloud9 was used as IDE for the project.
- [Browserling](https://www.browserling.com/)
    - Browserling was used for testing browser cross-compatibility


## Testing
This website is does not include any programming automation, therefore all Test Cases need to be performed manually as described:

### Test Cases
1. As a user, I want to be able to read the band's information and discography, so I can learn more about the band.
    1. Click "Who we are" menu item to learn more about the band members
    2. Click "How we rock" menu item, followed with "Discography" to learn more about the published albums

2. As a user, I want to be able to hear sound clips from the band's catalog, so I can check the quality and style of the band's music.
    1. Click "How we rock" menu item, followed with "Songs" option
    2. Press Play in any of the songs: The playback should start

3. As a user, I want to be able to watch clips from the band's catalog, so I can check the quality and style of the band's appearance and performance.
    1. Click "How we rock" menu item, followed with "Videos" option
    2. Press Play in the video: The video shall reproduce
    3. Click on the left and right navigation icons: You should be able to scroll through the current list of videos (3)
    4. Click on the bottom navigation buttons: You should be able to visit a specific video from current list inside the carrousel (3)

4. As a user, I want to be able to contact the band for availability, so I can hire them to perform on events.
    1. Click "Hire Us" menu item
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.
        
5. As a user, I want to be able to find social media links that will point me to other social media accounts from the band, so I can choose my preferred social media app to interact with the band.
    1. Navigate to the top of the page
    2. Click on any of the social media icons to navigate to the respective social media account

### Responsiveness
- Small devices:
    The website is collapsed for smaller devices, to make easier the navigation and access to the content. Top menu is collapsed and can be brought up using the "hamburger" icon on the top. Content that displays in several columns for bigger screens is stacked in a single column for small devices. Most margins are reduced or non existant.
- Larger devices:
    The websive uses a full range of columns to make it visually pleasant the exploration and navigation in larger devices. Menu is completely visible and allows easy navigation.

### Other tests performed
- All external links include `target=_blank` so the user never closes the site by navigating to a external resource.
- Submitting the form does not add any of the form contents to the user's URL (via `POST method`)

#### Browsers
Tested in the following browsers:

| Vendor | Version | Compatibility status |
| --- | --- | --- |
| Google Chrome | 69.0.3497.100 | Full |
| Mozilla Firefox | 62.0 | Full |
| Microsoft Edge | 42.17134.1.0 | Full |
| Opera | 52.0 | Full |
| Internet Explorer | 11 | 95% Compatible: Site won't display exactly due to IE bug with Flexbox. |

## Deployment

This website consist in a static project structure. It can be deployed to any hosting website as long as it keeps the same structure and filenames are not altered in regards of case (upper-lower case).

    .
    ├── assets              # Static media files
    │   ├── audio           # Audio library (MP3 files)
    │   ├── css             # Stylesheets
    │   ├── docs            # Support files for README.md
    │   ├── images          # Picture library (JPG, PNG, SVG files)
    │   └── video           # Video library (MP4 files)
    ├── index.html
    └── README.md

## Credits

### Content
- The text for section Who We Are was copied from the respective Wikipedia articles for each band member: [Micky Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz), [Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith), [Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork), [Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician))
- The dates for the live appearances was copied from the [Monkees official website](https://www.monkees.net/)

### Media
- The photos and MP3 used in this site were obtained from [Code Institute](https://github.com/Code-Institute-Org/project-assets)
- The videos used in this site were linked directly from the official Monkees Youtube channel.

### Acknowledgements
- The colour palette was inspired on this [post](https://dribbble.com/shots/4753006-Groovy-colors) by [Kalina Ivanova](https://dribbble.com/KalinaIvanova)
- Kudos to Code Institute slack users _Jo Wings_ and _abonello_ and Code Institute mentor _Moosa Hassan_ for their feedback on the project

---

## Code Institute Requirements
In this project, I have been tasked to create a frontend-only website using a user Centric Mobile First approach. 

- Create a website of around 4-5 pages, or (if using a single scrolling page) these should be separate page areas.
- Incorporate main navigation and grid layout (you might want to use Flexbox or Bootstrap to accomplish this).
- Whenever possible, strive to use semantic HTML5 elements to structure your HTML code better.
- Make sure your site is as responsive as possible. You can test this by checking the website on different screen sizes and browsers.
- We advise that you write down user stories and create wireframes/mockups before embarking on full-blown development.
- The site can also make use of CSS frameworks such as Bootstrap, just make sure you maintain a clear separation between the library code and your code.
- You should conduct and document tests to ensure that all of your website’s functionality works well.
- Write a README.md file for your project that explains what the project does and the need that it fulfills. It should also describe the functionality of the project, as well as the technologies used. Detail how the project was deployed and tested and if some of the work was based on other code, explain what was kept and how it was changed to fit your need. A project submitted without a README.md file will FAIL.
- Use Git & GitHub for version control. Each new piece of functionality should be in a separate commit.
- Deploy the final version of your code to a hosting platform such as GitHub Pages.
