# HTML_CSS_travel_guide

Usability and Accessibility
The site is optimised for devices with smaller screens by using viewport. To make the size of the font, some margins, borders, and some of the images responsive, viewport units were used. The primary navigation menu and headers are placed further away from the sides of the screen, to make it easier to navigate when someone will be using only one hand on their phone. Each navigation button is distinct, appropriately sized and can be easily pressed on all differently sized devices. 
The site is created according to The Web Content Accessibility Guidelines (WCAG). To check how the site appears to the people who see colours differently or are colour blind the site https://www.toptal.com/designers/colorfilter was used. Green or red colours were avoided so as not to confuse visually impaired users. The site has been made easy to navigate for older, physically impaired people and people with cognitive disabilities as the font is larger than standard size and the layout of the site has been kept simple. Different sections of the pages can be easily distinguished from each other. This was achieved by creating contrast between them, by using colours and borders, for example, for the review section on the ‘Index’ page, and to separate flexboxes from each other on the ‘Places’ and ‘Travel tips’ pages. The negative space was used to distinguish sections of pages from each other too. Flashy and bright colours were avoided as it would create an unpleasant user experience for the people who suffer from light sensitivity problems. To not confuse blind people, empty alt was implemented, so they will know what the images on the site are about.
Breadcrumbs were used, to make it easier for users understand which page is currently open. Also, the links and buttons that will take users to a different page, will perform a task, or will open a section with the information, have been highlighted. This was achieved by giving the relevant buttons a distinct colour, a border, a shadow or by underlining the link and giving it a distinct colour.
The pseudo-classes were used, to show users when they are interacting with the page (hovering over or pressing on the button or the link). Also, on the navigation menu users can always see which page they are currently surfing.
To increase the readability of the site, sufficient spacing between letters, words and the proper line height was set. Furthermore, the padding between the lines of the text was increased.
The design of the site is simple. The font of the headers is bigger, has a distinct colour and is centred, as it is important information. All the other text is aligned to the left except the text in the reviews, as it should draw the attention of users. For this reason, it was bolded too. All the images that have been placed in containers were centred, except the images on the ‘Travel tips’ page, as the direction of flexboxes on that page is a row. 
The colours were chosen by using the Kuler site to create a pleasing aesthetic experience for users and to differentiate areas of the website to make navigation easy. The range of colours used was kept to a minimum and consistently used on every page. Important information was highlighted by using a distinct colour. To control the opacity of some of the colours the RGB option of setting the colour was used. To not create a harsh contrast between the text and the background, a dark(non-black) colour was used for the font of text on the site. The level of the contrast was checked by using the WebAIM site.

Layout techniques
To create the layout of the site, CSS position, flexbox, inline block, floating and CSS box model properties were used. 
Relative CSS position was used to create a background image for the primary navigation menu and header links at the top of the site. On the ‘Transport’ page absolute CSS position was used to place an aside container on the right of the page.
The margin property was used to position the content of the site further from the edges of the screen. Also, margins and borders were used to distinguish sections of the pages from each other. The padding property helped to create a negative space between the border and the content inside the containers and to make spaces larger between the lines of the text. 
The float property was used to float an image with a figcaption on the ‘Index’ page, to make the text wrap around it on the smaller-sized screens.
The inline-block property was used to horizontally display header links, primary navigation, and footer links. 
Flexboxes were used to create containers for reviews and to separate information inside these containers on the ‘Index page’. The same thing was done with the flexboxes on the ‘Travel tips’ page to display the travel tips. On the ‘Places’ page the flexboxes were used to portray each place in a separate container. The direction of flexboxes on that page is a column to display the flexboxes in a one column, or two or three columns, on devices with the smaller screens. The two-column ‘Transport’ page was created by using flexboxes too. On the smaller screens this page becomes a one column page.

HTML Semantic Elements 
To increase the readability and the accessibility for machines and humans, the html semantic tags were used. To make readability easier for humans the HTML and CSS codes were commented.
The <html> tag was used to mark the root of the html document, the <head> tag to mark the metadata, the <link> tag to link external resources, the <title> tag to create the title on the page’s tab, the <body> tag to mark the content, the <main> tag to mark the content excluding headers, footers, and primary navigation menu, the footer was marked with the <footer> tag.
The <section> tag was used to highlight the titled sections of pages, the <article> tag to mark the titled, self-contained content, except the reviews which have no title on the ‘Index’ page. The <div> tag was used where other semantic tags were not appropriate.
The <nav> tag was used to mark the header links, the primary secondary and footer navigations. The <header> tag was used for the headers (<h1>, <h2>, <h3>), the <img> tag for the images, the <figcaption> tag for the text under the images, the <figure> tag to mark the images related to self-contained content. To mark the buttons the <button> tag was used, the <p> tag was used to mark the paragraphs, the <ul> and the <li> tags to mark the lists, the <span> tag to mark a part of the inline text, the <a> tag to define the hyperlinks, the <b> tag to bolden the text, the <br> tag to break the line, the <aside> tag to mark the information that was not directly related to the main content of the page. 
To create the ‘Registration’ and the ‘Sign in’ forms these tags were used: the <form> tag to mark all the ‘Registration’ and the ‘Sign in’ forms related code, the <input> tag to mark the field where users enter the data and the <label> tag to mark the captions.
