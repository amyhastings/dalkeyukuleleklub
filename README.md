# dalkeyukuleleklub

### Purpose of the website
This website for the Dalkey Ukulele Klub comprises my project for Module 1: Web Design of UCD's 24-03 Full-Stack Software Development Course. The objective of the project is to create a website using only HTML and CSS as follows:


> Design, develop and publish a responsive web site using recommended design practices. Your web site will contain a home page and three content pages. Create an external style sheet (.css file) that configures text, colour and layout. No font tags, embedded CSS or inline CSS is allowed. You must publish your project to the Internet.
>
> Your website must be on one of the following topics:
> ● Sport
> ● Music
> ● Comedy

I chose to prepare a website for a local music club, the Dalkey Ukulele Klub (the DUKs). The primary purpose of the website is to communicate information about the Dalkey Ukulele Klub (the DUKs) to prospective members (e.g. where they meet, what they do, where you can get in contact with them). An ancillary purpose of the website is to provide information about the DUKs to fans and also existing members of the Klub, such as future events and photographs of past events.

### Required features of the website
The text below outlines the principal requirements of the project for the website and how each requirement was satisfied.
- *Appropriate meta tags.* The html for the website includes the following meta tags: charset, viewport, description.
- *One page utilising tables effectively to display tabular information.* The 'Events' page of the website tabulates data relating to the Klub's events.
- *One e-mail hyperlink.* An email hyperlink is included in the footer on each page of the website, as well as on the 'Join' page.
- *One external hyperlink.* An external hyperlink to the Klub's Facebook page is included in the footer on each page of the website, as well as on the 'Join' page. Please note that, as the Klub has only one social media page, a conscious decision was made not to include a link to that page using the Facebook icon as would be typical.
- *Consistent banner logo area.* The banner logo area is consistent from page to page when viewed on a device of a specified size. The banner logo area will change in response to the size of the device viewing the site using media queries.
- *Consistent main navigation.* Main navigation is consistent from page to page when viewed on a device of a specified size. The main navigation area will change in response to the size of the device viewing the site using media queries. For example, the main navigation area uses a collapsible drop-down menu for devices with a screen width of less than 768 pixels. The code for this HTML and CSS only collapsible menu was adapted from https://codeburst.io/how-to-make-a-collapsible-menu-using-only-css-a1cd805b1390
- *Association with external style sheet (.css file).* An external CSS style sheet is used for all styles. However, it is noted that the Deezer iframe code for the widget on the 'Songbook' page includes some inline styling. This was not removed so as to avoid any issues with functionality.
- *One Bonus Feature: YouTube video, CSS image gallery, or CSS Transition.* The Deezer widget is included on the 'Songbook' page. A CSS image gallery is included on the 'Gallery' page. A CSS Transition is included in the main navigation area for screens with a width greater than 768 pixels.
- *Popular browsers (including Chrome, Edge, and Firefox) must render each page correctly.* The site was tested on all popular browsers and found to work correctly. Testing identified a known issue with functionality of the pseudo-class :hover for mobile devices using iOS so this was removed for devices with a screen width of less than 1024 pixels using media queries.

### Licensing
All images on the website are the copyright of the Dalkey Ukulele Klub.