# Darren Small Portfolio #
Link to the website: [Darren Small Portfolio](https://brilliant-panda-dc61f6.netlify.app/)

Link to the GitHub repository: [T1A2_Portfolio](https://github.com/smallDazza/T1A2_Portfolio)

# **Purpose Of The 'Darren Small Portfolio' Website**
The purpose of my portfolio website is to provide information about my personality, amibitions, skills and experience to prospective employers looking to employ a full stack web developer.
Its layout, structure and design is to present my knowledge and skills in a direct environment of what they can expect I can deliver, should they decide to offer me employment.
Also to give prospective employers the confidence of the professionalism I would be bringing to their companies.

## An Overview Of The Darren Small Portfolio Website. ##
My Portfolio website consists of a total of 5 pages. These are: a 'home' page, 'my story' page, 'experience' page, 'interests' page and a 'contact me' page.
The features of each and a image of Mobile view are:
- **Home Page** 
    - Main landing page with the title of this website and a picture of myself.
    - ![Mobile Home Page](./docs/Home%20Page%20Mobile.png)
- **My Story Page**
    - This page explains who I am , my personality and professonal attributes I have.
    - Has a section describing my future ambitions both personally and career focused to be involved in the progamming / development industry.
    - Examples of blog pages I have followed to help in my education in the industry and help in solving issues I have encountered.
    - Also can view an example of a blog page I have created combining both my love of programming and travelling:
        - Small Travellers Blog.
    - ![Mobile My Story Page](./docs/My%20Story%20Page%20Mobile.png)
- **Experience Page**
    - This page is designed to display my work experience over the last 15 years and how I have grown and achieved the current position I am currently employed in.
    - Employers can download my resume from this page.
    - ![Mobile Experience Page](./docs/Experience%20Page%20Mobile.png)
- **Interests Page**
    - This is a page to explain my career and other interests in life away from work and how it reflects on my personality.
    - ![Mobile Interests Page](./docs/Interests%20Page%20Mobile.png)
- **Contact Me Page**
    - This has all my contact details, links to social media for contacting me.
    - ![Mobile Contact Me Page](./docs/Contact%20Me%20Page%20Mobile.png)

## Navigation Of The Darren Small Portfolio Website. ##
The first main landing page is the home page. On this page and every other page is a navigation bar which has links to the 4 pages of home, my story, experience and interests. Users can select the link of the desired page they want to view, which will open it in a new web browser tab.
The 5th page contact me is opened via a link at the bottom of all the other 4 pages which when selected will open in a new web browser tab.

The 2nd page, 'my story' has links to blog pages I follow and a link to a blog page I have created.

The 3rd page, 'experience' has a link to download my resume in a pdf format.

The 5th page, 'contact me' has links to view my social media and github accounts.

When the screen view is a Mobile phone (<768px wide), i have added a scroll bar function for overflow. This way users know there is more content to scroll down to & can see the footer (contact me) link all the time to select when desired.

## The Design: Site Map ##
Please see this image for the website site map: 

![darren small portfolio site map](./docs/Portfolio%20site%20map.png)

## The Design: Colour Palette ##

In all pages I have used this colour palette 'ice cream' for background, text, object colour, available from this color hex website: [ice cream color palette](https://www.color-hex.com/color-palette/660). 

![Ice Cream Color Palette](./docs/colour%20palette%20-%20ice%20cream.png)

The reason I have chosen this colour palette is because with Chocalate used as text on all other colours = Pass all 4 contrast ratio tests:

![Contrast ratio test](./docs/Ice%20Cream%20Colours%20Pass.png)

## The Design: Website Pages Wire Frame Layouts ##
Based on this website; [Bulma Responsiveness Breakpoints](https://bulma.io/documentation/start/responsiveness/) , I have added the 3 screen size breakpoints.

For the mobile screen layouts of the web pages:
The layout of images, objects and text for mobile screens was taking into account the smaller width <=767px, so all these items would need to appear in a portrait type of structure. 

![mobile screen wire frames](./docs/Mobile%20screen%20wireframes.png)

For the tablet screen layouts of the web pages:
The layout of images, objects and text for tablet screens was taking into account the width between 768px & 1023px, so all these items would need to appear in a combination of portrait and landscape type structures.

![tablet screen wire frames](./docs/Tablet%20screen%20wireframes.png)

For the desktop scrteen layouts of the web pages:
The layout of images, objects and text for desktop screens was taking into account the larger width >=1024px, so all these items would need to appear in a landscape type of structure.

![desktop screen wire frames](./docs/Desktop%20screen%20wireframes.png)

## Components & Properties Used In Website ##
The structure and design of the website has used both HTML 5 and CSS properties.
This is a list of components and properties used over all 5 pages to display some features to enhance the engagement of employers in understanding Darren Small as a person and as a valuable developer employee:
- **Re Used Text Components**
    - a header = to display the top of the page with a title of the page the user has gone to. Used on 4 pages
    - navigation bar = a section with links to navigate to other pages listed above. Using flexbox to adjust and the use of the pseudo-class 'hover' to highlight the link the user has hovered the cursor over.Used on all 5 pages
    - footer = to display the bottom of the page with a link to the contact me page.Used on all 5 pages.
- **Text Components**  
    - 4 pages are using either section or article tags for text components to display content for the relative page. Text components styled with css.
    - 3 pages are also using the unordered list element to display text components relative to the subject or to list external links.
- **Graphical Components**
    - all 5 pages (+ the blog website) have graphical components (or mixed with text) to enhance the page content. Graphical components are styled with css.
**CSS styling properties applied**
- Colour Custom Properties: the colours from the colour palette have been saved as universal selectors using the '*' in each css file.
- Text Font: on all pages the Arial font has been chosen as the first choice in the body element.
- Background Color: this is used on all sections and components to make the content stand out.
- Background Image: this is used on 4 pages to give tha main element area a style to match the page subject.
- Flex Box: On all web pages (+ the blog website) Flex has been used for wrapping &/or centering of the header display, navigation bar, and the main content area for the text and graphical component sections.
- Animation: the home page has a animation function applied to a graphical component called 'ease-in-out'. This will transform the component on the page to different sizes giving the appearance of shrinking & expanding, on a infinite loop. **This only applies to larger screens - as looked a little strange on smaller screens**

## Tech Stack ##
- HTML5: a main index.html + 4 other html files (1 or each page) located in the pages folder.
- CSS: 5 css files (1 for each html file) located in the CSS folder.
- All images + Resume used are located in the images folder.
- Images for this README file located in the docs folder.
- Saved in my GutHub repository called 'T1A2_Portfolio'.
- Deployed as a live site using netlify. 
