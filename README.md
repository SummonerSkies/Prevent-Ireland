# PREVENT Ireland

## Overview

![Screenshot of AmIResponsive.com showing an image of the current website across multiple device sizes](/assets/images/amiresponsive1.png)

### Purpose
The goal of PREVENT Ireland is to create an informative webpage that introduces the general public to the Prevent strategy and its education goals regarding radicalization. To facilitate this, the site's content should be well-organised and easy to digest, with a focus on simplicity and clarity. When visiting the site, they should know:
- What is Prevent
- What is radicalization and how to recognise it, and
- How to report it to the appropriate authorities and/or community partners

### Target Audience
This site should be useable by anyone seeking general information on the topic. 

## Design Goals

These were the target goals for the website, starting with the minimal viable product (MVP) and expanding from there.

### Must-Have Design Elements
- As a site owner, I want clear and concise layout so information on Prevent is easily accessible.
- As a user, I want a clear and concise homepage with a simple layout to help me find the information I need.
- As a user I want to be reassured that the site is professional and provides accurate information.

### Should-Have Design Elements
- As a site owner, I want to display basic information on Prevent clearly and easily. 
- As a site owner, I want a responsive page allowing clear reading of information. 
- As a user I want to be able to find the information quickly and easily, regardless of device used to access the site.
- As a user I want a page that can direct me to find more information about Prevent’s initiatives.
- As a user, I want to easily reach out to someone for help.

### Could-Have Design Elements
- As a site owner, I want to redirect any complex queries to the relevant bodies.
- As a user, I want to know how to voice a complaint about Prevent.

## Features Implementation

### Existing Features
	
#### *Responsive Design*
Each page on website has been designed to be responsive to adjustments in browser size, and will adapt to the device being used.

#### *Custom Pages*
- Index Page
- About Page: "What is PREVENT?"
- Information Page: "What is Radicalization?"
- Contact Page: "Reach Out"

#### *Branding (Logo) and Favicon*
The chosen font for the logo and celtic knot heart emblem are distinctive and unique to the site, making it memorable.

#### *Navigation Bar*
The navigation bar will allow the user to easily navigate links that are clearly labeled to each section of the website. The fully responsive design is found on all pages, without having to go back to a previous page via the ‘back’ button on the browser.

#### *Embedded Video*
Two videos covering appropriate topics have been successfully included in the body of the "What is PREVENT?" and "What is Radicalization?" pages, and their size is responsive to the size of the device used to view the page.

#### *Footer*
This clearly shows the linked social media for the PREVENT Ireland website.

## Design Decisions

When designing the site, I wanted to start with the follow: 

- Keep the design simple and clean.
- Make the site's content easy to digest.
- Reference the Irish flag colours.  
- Include an appropriate celtic themed logo.

### Colour Palette

I started with the official colour shades of the Irish Flag, with the intent of styling the primary layout and universal look of the site. Using [Coolors.co](https://coolors.co/) I then generated additional colours, and settled for a blue shade and a charcoal shade.

![Image of five colours with their hexcode taken from coolors.co](/assets/images/colour-palette-version1.png)

The final version of the site, I opted not to use the blue and charcoal colours, as these did not compliment the design as I had hoped. Instead, I opted to use a darker shade of green (#004e22) for the footer to offset the flag-green shade of the header, and a offwhite/cream colour (#fafafa) for the navigation menu and footer icons.

![Image of the two replacement colours with their hexcode taken from coolors.co](/assets/images/colour-palette-version2.png)


### Logo

The Celtic knot is uniquely Irish, and I wanted to find a design that would incorporate this imagery in the shape of a heart. The heart represents community, and the knotwork represents how everyone is connected together.

After a brief search, I found a free vector design I liked by Brian Goff on [Vecteezy](https://www.vecteezy.com/). This was used for both the logo and favicon.

<img src="https://raw.githubusercontent.com/SummonerSkies/Prevent-Ireland/refs/heads/main/assets/images/heart_015.jpg" width=30% height=30% alt="Image of a green celtic knot shaped into a heart.">


### Wireframes

Starting with a clear front page with a hero image, I wanted to make sure the layout was clear and easy to follow.

![index_html](https://github.com/user-attachments/assets/4de9f220-96d8-466e-bef8-e2dace9543cf)

I then made additional wireframes for other potential pages, with the selected page responsively highlighted on each nav bar.

![about_html](https://github.com/user-attachments/assets/535792c9-69c2-4cb1-884d-dca10cedaa54)
![risks_html](https://github.com/user-attachments/assets/6f2b7429-3c93-43c6-82c4-9cc5b0dea8a3)
![community_html](https://github.com/user-attachments/assets/c3d7c6e1-7593-457e-8f65-c28ade2de6c5)
![contact_html](https://github.com/user-attachments/assets/5c9aea5d-068a-47de-b247-2c0ed3fe0880)

When breaking down the above wireframes, I realised I had gone out of scope - I was making too many pages and making the project too complicated for myself. 

I took a step back, and changed the buttons, and made a new design that merged together the 'What is Radicalization' and 'Community Resources' pages, and designed a new one that could include a layout for both.

![whatis_html](https://github.com/user-attachments/assets/a25df8bc-f482-4584-9ac2-add552101377)

This final design was not used, but is worth considering for a future iteration of the website.

### Accessibility Considerations
I planned for, but did not have time to update the HTML with appropriate accessibilty alt tags for the images and iframes. 

## Testing and Validation

### Testing Results
I tested my website in Firefox, Chrome and Edge on PC, and Safari on IOS 17.6.1 on iPhone 13. The site successfully loaded on all platforms.

During this testing, I encountered the following:
- Identify colour and position padding issues with the menu, which I then corrected. 
- See that the embedded YouTube iframes were not responsive on the About and WhatIs pages. After adding appropriate CSS, this issue was corrected.   

### Validation

Due to time constraints with the project, I failed to allocate enough time to test the site using WC3's HTML and CSS checkers.

## Deployment

The site was deployed to GitHub pages. 

The deployment page can be found here: https://summonerskies.github.io/Prevent-Ireland/

## Reflection on Development Process

### Successes
- I successfully created a website with a clean, simple appearance, and laid out the initial goals of the site clear.
- I successfully created responsive pages that changed appropriately when viewed on different devices.
- I created clear wireframe designs that could be used for current and future reference.

### Challenges
- I overscoped myself, and could have kept things much more simple. 
- I did not achieve all the goals of providing information.
- I did not leave myself enough time to do aappropriate WGAC check.
- I did not budget my time well, and spent too long on wireframing and looking for information.
- The site logo/title header could have been more responsive when the page size adjusted between medium sized screens.
- Did not include a Call to Action button for contacting Prevent Ireland as originally planned in the wireframes.

### Final Thoughts
For my first ever website, I am quite pleased with my progress after the first four weeks of coding bootcamp. 

I learned a lot about timekeeping and prioritization from this project. It can be very easy to get caught up in the minor details, and it is important not to forget/ignore the important goals (MVP) required for the site you are building.

My lack of experience with flexboxes shows on several pages, and I had issues aligning some elements. 

Including Bootstrap in future may help with addressing some design decisions.

Finally I should reach out and ask for help more often from both my coding cohort, coding partner, and my instructors as and when I need it. 

## Credits and Attribution

### Code
-   

### Collaborators 
- Coding partner: Brian Murphy.
- PREVENT study partner: William Waldron-Hayden.
- Instructors: David Calikes, John Rearden, and Kevin Loughrey at <a href="https://www.codeinstitute.net" target="_blank" alt="Link to Code Insititute's website that opens in a new window">Code Institute</a>.

### Content
- ACT Early - <a href="https://actearly.uk/spot-the-signs-of-radicalisation/what-to-look-for/" alt="Link to ACT Early's Radicalization page that opens in a new window" target="_blank">Radicalization</a>

### Images
- Logo and Favicon: <a href="https://www.vecteezy.com/vector-art/552197-celtic-knot-heart-vector-illustration" target="_blank" lt="Link to Brian Goff's vector page on Vecteezy that opens in a new window">Celtic Knot Heart vector</a> by Brian Goff<br> (<a href="https://www.vecteezy.com/free-vector/tied" alt="Link to Vecteezy.com that opens in a new window" target="_blank">Tied Vectors by Vecteezy</a>)
- Favicon Converter: <a href="https://favicon.io/" target="_blank" alt="Link to the Favicon website that opens in a new window">Favicon.io</a>
- <a href="https://www.pexels.com" target="_blank" alt="Link to the Pexels website that opens in a new window">Pexels</a> - Hero and insert images
- <a href="https://www.fontawesome.com" target="_blank" alt="Link to the FontAwesome website that opens in a new window">Font Awesome</a> - media icons

## Future Improvements

### Call to Action
- A bold button encouraging the user to Contact Us should be included on the main landing page linked to the contact.html "Reach Out" page, and just above/included as part of the footer on all pages except the Contact Us page. 
- Potentially using Bootstrap to enable deployment of the above as appropriate.

### More Information
- Expand the About.html and WhatIs.html pages to provide greater detail on PREVENT's policies and signs of radicalization respectively, with a responsive layout to ensure ease of reading across multiple devices.

### Expanded Contact Page
- Include options to send feedback and complaints regarding PREVENT Ireland / Prevent strategy.
- Expand the contact page to list options for a user in distress vs contact by concerned family member/friend.
- Contact form option for callback from appropriate team / department / partner service.


[def]: /assets/images/amiresponsive1.png