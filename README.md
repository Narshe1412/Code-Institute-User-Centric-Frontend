# Monkees Band Website

In this project, I have been tasked to create a frontend-only website using an User Centric Mobile First approach. 

The client is a 1960’s rock band that have around 50 years experience of performing live at numerous events around the world. They want to establish an online pressence that will include a contact form and links for their other social media pressence.

## Customer background and request

The following requirements have been provided after interviews with the client’s representatives:
- Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
- Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

## User Stories

- As an user, I want to be able to read the band's information and discography, so I can learn more about the band.
- As an user, I want to be able to hear sound clips from the band's catalog, so I can check the quality and style of the band's music.
- As an user, I want to be able to watch clips from the band's catalog, so I can check the quality and style of the band's appearance and performance.
- As an user, I want to be able to contact the band for availability, so I can hire them to perform on events.
- As an user, I want to be able to find social media links that will point me to other social media accounts from the band, so I can choose my preferred social media app to interact with the band.


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
- Future Appearances - Allow users to check out the incoming public shows the band will be playing
- Contact Form - Allow users to contact the band, for reservations or further information
- Social Media Icons - Allow users to find other official social media accounts from the band

### Features Left to Implement
- Embedded social media pressence, like Twitter widget with the latest interactions from the band, or latest Instagram posts, etc...
- Official chat room, where fans can interact with each other


## Technologies Used
<a href="http://www.w3.org/html/logo/">
    <img src="https://www.w3.org/html/logo/badge/html5-badge-h-css3-device-multimedia-semantics.png" width="229" height="64" alt="HTML5 Powered with CSS3 / Styling, Device Access, Multimedia, and Semantics" title="HTML5 Powered with CSS3 / Styling, Device Access, Multimedia, and Semantics">
</a>

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to provide semantics to blocks of text that improves readability to screen readers and impaired users of the site.
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses **CSS** to provide custom styling and visualization to the site.
- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to provide a common responsive layout that is familiar with other websites on the Internet. It also makes the website fully responsive, created with a mobile-first approach.


# TODO
## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from [Code Institute](https://github.com/Code-Institute-Org/project-assets)

### Acknowledgements
- I received inspiration for this project from X

---

#### Code Institute Requirements
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
