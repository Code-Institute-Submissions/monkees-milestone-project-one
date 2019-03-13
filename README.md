# The Monkees Website - Milestone Project One

This is a website for the band, **_The Monkees_**. My website will be used by existing, new and prospective fans and event planners to find out more about the band and its members. They can also listen to the band's music and sign up to the newsletter to keep up to date on the latest news and new music releases. Each page contains links to the band's social media pages.

Users can use my website to book tickets for the band's upcoming concerts, and they will have the ability to book the band to perform at their upcoming events through the contact form.

## UX

My website is for current and potential fans and event planners, who are looking to follow the band, listen to their music, book tickets and book the band to perform at their events. My website provides a *"one-stop-shop"* for users, to help them to achieve all of these things, along with several links to the band's external social media and wikipedia pages.

I've chosen to style my website in the way that I have, as I felt that it best reflected the brand of the band. The band were at their peak during the late 60s, 70s and 80s, so the fonts and colour scheme that I've chosen best reflect this era and create a feeling of authenticity for users.

### User Stories

- As a potential fan I want to know more about the band and its members so that I can expand my knowledge of the band.
- As the band manager I want fans and event organisers to be able to book the band to perform at events such as weddings and Christmas parties so that the band can connect more with their fans.
- As the band members we want to know when and where event organisers and fans have booked the band to perform so that we can prepare for our performances and tailor them to the type of audience.
- As a lifelong fan I want to listen to the band's songs for entertainment and subscribe to their newsletter so that I'll be kept up to date when they release new material.
- As a wedding planner I want to contact the band so that I can book them to perform at my clients' wedding.
- As a current fan I want to visit the band's website so that I can buy tickets for their concerts.
- As an event organiser I want to know more about the band members and their music so that I can decide whether to book them for an upcoming Christmas party.
- As a current fan I want to sign up to the newsletter so that I can keep up to date with the latest news and tour dates.
- As a potential fan I want to listen to the band's music and visit their social media profiles all from one place so that I can learn more about them and don't have to spend time searching for each of their social media profiles.

### Wireframes

I drew my wireframes using Balsamiq. All wireframes are contained in a single file, and it includes my consideration of how to make my webssite responsive. The link to the file is below:



There are some differences between my wireframes and my final website. This was due to visual preferences and feedback received from other users who tested my website.

## Features

### Existing Features

#### All Pages

- **'Sign Up!' call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to sign up for the band's newsletter.
- **Modal with built in form and submit button** - The modal is triggered by the 'Sign Up!' call to action button, and allows users to complete a form and submit their details to sign up to the band's newsletter. Each of the form's fields are required. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **Hamburger button** - Clicking the hamburger button triggers a full screen overlay menu containing the navigation links to all pages on my website. The user can click the links to navigate to the relevant webpage.
- **Social media links** - Each link opens a new page with the relevant social media page for the band (Facebook, Twitter and YouTube). These links make it easy for users to access the band's social media profiles from one place. The social media profiles load in a new tab, which allows users to then return to the site.
- **Full screen overlay menu** - The full screen overlay menu contains navigation links which redirect the user to the different pages of my website. The social media links are displayed in the top right hand corner of the medium to extra large screens.
- **Navigation links** - Allows users to navigate around my website by clicking each navigation link, which redirects them to the relevant webpage.

#### All Pages (exluding index.html)

- **Return to top link** - This is located at the bottom the webpage, just above the footer. It allows users to return to the top of the page by clicking the link.
- **Footer 'Sign Up!' call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to sign up for the band's newsletter. This is displayed in the centre of the footer, above the social media links on extra small and small screens. It is displayed to the left in the footer on medium to extra large screens.
- **Footer social links** - These have the same function as the social media links in the navigation bar/header. They are displayed in the centre of the footer, below the 'Sign Up!' call to action buttion on extra small and small screens. They are displayed to the right in the footer on medium to extra large screens.

#### band.html

- **Band member cards and links** - Each band member's picture and information is displayed in a card. Each card has a scroll bar, which allows users to scroll through and read all the information contained within the card. Users can then click the 'Find out more...' link, which opens the Wikipedia page for the relevant band member in a new browser tab.
- **Carousel with indicators and controls** - The carousel contains four pictures of the band, which slide automatically. Alternatively, users can use the controls to manually slide forwards or backwards through the images. The indicators allow users to see which image of the series they are viewing.
- **Band history link** - The 'Find out more...' link at the bottom of the *'Band History'* section allows users to find out more about the band. Clicking the link opens the band's Wikipedia page in a new browser tab. 

#### music.html

- **Discography timeline links** - Each album name is a link. These links allow users to find out more about the albums by opening the Wikipedia page for the relevant album in a new browser tab.
- **Spinning music discs** - This is purely visual and gives users a sense that music is playing. These discs constantly spin though, which is due to a limitation as I haven't yet learned JavaScript to make them start and stop spinning when certain actions are completed.
- **iframes** - The iframe embeds contains two of the band's albums on Spotify. Users can click each of the songs and listen to a 30 second preview of them. They are then redirected to the Spotify album page to either log in or sign up.
- **Spotify 'Follow' widget** - Allows users to click the 'Follow' button to follow the band on Spotify. If the user isn't signed in to Spotify, clicking the button opens a new window that allows users to login to their Spotify profile to then follow the band.
- **Audio tracks with controls** - Allows users to listen to the relevant track using the controls. Users can also download an mp3 copy of the track to their local drive by using the controls.
- **Video with controls** - Allows users to watch the video using the controls. Users can watch the video on full-screen, and they can also download a copy of the video to their local drive by using the controls.

#### tickets.html

- **'Book Now' button call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to receive instructions on how to finalise their ticket booking.
- **Modal with built in form and submit button** - The modal is triggered by the 'Book Now' call to action button, and allows users to complete a form and submit their details to receive instructions on how to finalise their ticket booking. Each of the form's fields are required. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **'Limited availability' alert** - This is a banner above the 'Book Now' button that alerts the user to the fact that there is limited ticket availability for that particular concert.
- **'Sold Out' disabled button** - This button allows the user to see that the particular concert is sold out. The button is disabled and is for information purposes only.

#### contact.html

- **Form with submit button** - Allows users to book the band to perform at their events by completing the form and submitting their details. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **Form dropdowns** - Some of the forms input fields have dropdowns, which allows users to select the relevant option from a list of options.
- **Form date selector** - Allows users to choose the desired date that they want to book the band by clicking the date selector icon, which displays a calendar. 
- **Form number input field with min and max range** - Allows users to input the number of attendants to the event by either typing the number directly into the input field, or by using the higher or lower selectors. This field has a minimum value of 20 and a maximum value of 999999999.

### Features Left to Implement

Once I've learnt JavaScript and back-end web development, I will add further functionality to the existing features on my website.

- **'Sign Up!' modal action** - I will add further functionality to the 'Submit' button so that it displays an on-screen 'Thank you' message. I will also add functionality for an email to be sent to users to confirm that they have successfully signed up for the band's newsletter.
- **Hamburger button** - I will add functionality for the burger button to change to a close icon once the full screen overlay menu is triggered and displayed.
- **Full screen overlay menu** - I will improve the display and functionality of the full screen overlay menu, which will in turn reduce the amount of CSS code that I've had to use instead.
- **Spinning music discs** - I will add functionality to these discs so that they are triggered to spin when the user plays the music within the relevant iframe, and they will stop spinning when the music is stopped.
- **Audio and video controls** - I will add personal styles to the existing audio and video controls so that they also reflect the brand of the band and the theme of the website, and so that they appear the same in all browsers.
- **'Book Now' modal action** - I will add further functionality to the 'Submit' button so that it displays an on-screen 'Thank you' message. I will also add functionality for an email to be sent to users with further instructions to complete the ticket booking process.
- **'Limited availability' alert** - I will add functionality to the 'Limited availability' alert so that it is only displayed when there is a limited availability of tickets for that particular concert.
- **'Sold Out' disabled button** - I will add functionality to the 'Sold Out' button so that it is only displayed when there the particular concert is sold out. This will require the 'Book Now' button to change to a 'Sold Out' button in this event.
- **Form with submit button on contact.html page** - I will add functionality to the 'Submit'button so that it displays an on-screen 'Thanks for booking us!' message. I will also add functionality for an email to be sent to users to confirm that they have booked the band for their event.
- **Form date selector** - I will add functionality to the date selector icon to change it to a calendar icon. I will also add my custom styles to the calendar and improve the fuctionality so that it greys out any dates that have already been booked, or when the band is unavailable.

## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - The project uses **HTML5** to create the basic elements and content of my website.
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses **CSS3** to add custom styles to the elements and content of my website.
- [Bootstrap v4.3](https://getbootstrap.com/)
    - The project uses **Bootstrap v4.3** to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.
- [jQuery](https://jquery.com)
    - The project uses **jQuery** to simplify DOM manipulation. This is the standard jQuery that is built with Bootstrap components.
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google Fonts** to style the text and suit the style of the band.
- [Font Awesome](https://fontawesome.com/)
    - The project uses **Font Awesome** for the social media links and the hamburger button on my website.

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
"Take files, put them on the local drive and then run the site"

## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X