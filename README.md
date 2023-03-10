# HTML_CSS_travel_guide

![1](https://user-images.githubusercontent.com/85522584/212560647-de692b1c-5bf3-4143-9e19-8b294d5e2151.jpg)
![2](https://user-images.githubusercontent.com/85522584/212560681-b9062e0b-1b56-40cc-843d-fe0edf60e041.jpg)
![3](https://user-images.githubusercontent.com/85522584/212560693-f98ebd92-3488-4089-9679-092aa57495eb.jpg)
![4](https://user-images.githubusercontent.com/85522584/212560703-591793fd-48a1-462f-97db-801d67a3af37.jpg)
![5](https://user-images.githubusercontent.com/85522584/212560709-14fdb5fc-2616-42de-b094-673ae46d60a9.jpg)
![6](https://user-images.githubusercontent.com/85522584/212560714-81ea30c1-a72b-4dd9-b92d-ba923a2cadcc.jpg)
![7](https://user-images.githubusercontent.com/85522584/212560724-45988e7f-cbde-4492-96ab-6da884e43bbf.jpg)
![8](https://user-images.githubusercontent.com/85522584/212560730-227fba78-8e88-4a2d-b683-a6209657e215.jpg)
![9](https://user-images.githubusercontent.com/85522584/212560735-9d985b6d-1b77-4f3f-bc4b-9c0a8ba2bcfe.jpg)



Usability and Accessibility

The site is optimised for devices with smaller screens by using viewport. To make the size of the font, some margins, borders, and some of the images responsive, viewport units were used. The primary navigation menu and headers are placed further away from the sides of the screen, to make it easier to navigate when someone will be using only one hand on their phone. Each navigation button is distinct, appropriately sized and can be easily pressed on all differently sized devices. 

The site is created according to The Web Content Accessibility Guidelines (WCAG). To check how the site appears to the people who see colours differently or are colour blind the site https://www.toptal.com/designers/colorfilter was used. Green or red colours were avoided so as not to confuse visually impaired users. The site has been made easy to navigate for older, physically impaired people and people with cognitive disabilities as the font is larger than standard size and the layout of the site has been kept simple. Different sections of the pages can be easily distinguished from each other. This was achieved by creating contrast between them, by using colours and borders, for example, for the review section on the ???Index??? page, and to separate flexboxes from each other on the ???Places??? and ???Travel tips??? pages. The negative space was used to distinguish sections of pages from each other too. Flashy and bright colours were avoided as it would create an unpleasant user experience for the people who suffer from light sensitivity problems. To not confuse blind people, empty alt was implemented, so they will know what the images on the site are about.

Breadcrumbs were used, to make it easier for users understand which page is currently open. Also, the links and buttons that will take users to a different page, will perform a task, or will open a section with the information, have been highlighted. This was achieved by giving the relevant buttons a distinct colour, a border, a shadow or by underlining the link and giving it a distinct colour.

The pseudo-classes were used, to show users when they are interacting with the page (hovering over or pressing on the button or the link). Also, on the navigation menu users can always see which page they are currently surfing.

To increase the readability of the site, sufficient spacing between letters, words and the proper line height was set. Furthermore, the padding between the lines of the text was increased.

The design of the site is simple. The font of the headers is bigger, has a distinct colour and is centred, as it is important information. All the other text is aligned to the left except the text in the reviews, as it should draw the attention of users. For this reason, it was bolded too. All the images that have been placed in containers were centred, except the images on the ???Travel tips??? page, as the direction of flexboxes on that page is a row. 

The colours were chosen by using the Kuler site to create a pleasing aesthetic experience for users and to differentiate areas of the website to make navigation easy. The range of colours used was kept to a minimum and consistently used on every page. Important information was highlighted by using a distinct colour. To control the opacity of some of the colours the RGB option of setting the colour was used. To not create a harsh contrast between the text and the background, a dark(non-black) colour was used for the font of text on the site. The level of the contrast was checked by using the WebAIM site.

Layout techniques

To create the layout of the site, CSS position, flexbox, inline block, floating and CSS box model properties were used. 

Relative CSS position was used to create a background image for the primary navigation menu and header links at the top of the site. On the ???Transport??? page absolute CSS position was used to place an aside container on the right of the page.

The margin property was used to position the content of the site further from the edges of the screen. Also, margins and borders were used to distinguish sections of the pages from each other. The padding property helped to create a negative space between the border and the content inside the containers and to make spaces larger between the lines of the text. 

The float property was used to float an image with a figcaption on the ???Index??? page, to make the text wrap around it on the smaller-sized screens.
The inline-block property was used to horizontally display header links, primary navigation, and footer links. 

Flexboxes were used to create containers for reviews and to separate information inside these containers on the ???Index page???. The same thing was done with the flexboxes on the ???Travel tips??? page to display the travel tips. On the ???Places??? page the flexboxes were used to portray each place in a separate container. The direction of flexboxes on that page is a column to display the flexboxes in a one column, or two or three columns, on devices with the smaller screens. The two-column ???Transport??? page was created by using flexboxes too. On the smaller screens this page becomes a one column page.


