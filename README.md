# T1A2 Project:  Plan & Develop a Portfolio Website

**Author:** Jessica Jakeman

**Date Created:** 7 April, 2024

## Project Source Files

All files pertaining to this project can be found in the following GitHub repo:

- [Portfolio-Website](https://github.com/jeskaj/Portfolio-Website)

## Website Description

### Purpose

The purpose of this website is to showcase my skills, talents, abilities and coding experience, in order to introduce myself to potential employers as a skilled web developer and IT professional.

### Website Structure

My portfolio has a relatively simple structure, consisting of two levels only, as shown in the sitemap below:

1. First level: Home page only
2. Second level pages:
    1. About
    2. Portfolio
    3. Blog
    4. Contact

![Sitemap](docs/sitemap.png)

#### Navigation

Every page contains a navigational component to enable all other pages to be accessed directly.  On the Home page, this takes the form of prominent navigational button-like anchor elements featured in the mid section of the page.  All other pages contain a nav bar, directly under the header component on smaller layouts and as a sidebar in larger layouts.

The nav bars show the link to the current page in a darker colour, to indicate the user's current location.

The About page contains a list of blog posts, which link directly to the relevant articles on the Blog page.

The only other internal document linked to the site is a PDF of my resume, which is linked to the About page.

#### External links

Links to my professional social media profiles ([LinkedIn](https://www.linkedin.com/in/jessica-jakeman/) and [Github](https://github.com/jeskaj) - see screenshots below) are included in the footer of every page, except for the Contact page, which features them more prominently in the main section.

<figure>
    <figcaption>LinkedIn Profile page</figcaption>
    <img src="docs/linkedin-profile.png" alt="LinkedIn Profile">
</figure>

<figure>
    <figcaption>GitHub Profile page</figcaption>
    <img src="docs/github-profile.png" alt="GitHub Profile">
</figure>

Each Project on the Profile page contains a link to the relevant repository within my Github profile.

<figure>
    <figcaption>IMA Zebra project GitHub repository page</figcaption>
    <img src="docs/github-ima-zebra.png" alt="IMA Zebra project GitHub repository">
</figure>

<figure>
    <figcaption>Cute Puppy project GitHub repository page</figcaption>
    <img src="docs/github-effects--animations-challenge.png" alt="Cute Puppy project GitHub repository">
</figure>

<figure>
    <figcaption>Chess Board project GitHub repository page</figcaption>
    <img src="docs/github-chess-board.png" alt="Chess Board project GitHub repository">
</figure>

### Design Aesthetics

I chose the below image of mountains under a sunset view for the header (hero) image, as it reflects my love of being in nature and also projects an atmosphere in calm, which reflects my calm and rational nature.  

![Header mountain image](docs/mountains-header-image.png)

This set the aesthetic for the site and the colour pallet used was based off the tones in this image (especially the background purple and dark pink).

The headshot image used stands out well against the background header image, but does not conflict with it.  However, I do intend to replace it with a more professional headshot, similar to the one on my LinkedIn profile (that photo was taken by my former employer and I only have a version of the file with very low resolution, which is not sufficient when the image is enlarged beyone quite a small size, as you can see from my use of it in the placeholder resume, linked on the About page).

A text colour of light grey or white was used against the purple background and black against the pink background, to produce sufficient contrast for readability.

The font family of League Spartan was chosen for its clean, modern, sans-serif look (with sans-serif as backup font), as being suitable for a professional site.

The nav bar was given a black background for prominence and contrast, with light grey link text and a darker grey used on the link indicating the current page location (on second level pages).

*Vertical nav bar indicating current location is the About page:*  
![Vertical nav bar](docs/nav-bar-vertical.png)

Turning the nav bar into a checkerboard type of effect on the desktop layout of the Home page was done to make better use of the screen real estate, given that the page had no other main content.  It also adds a bit of whimsy to the site ;-)

![Home page desktop layout nav](docs/home-nav-desktop.png)

In the list of blog posts on the About page, the blog articles on the Blog page and the project sections on the portfolio page, the dark pink background was alternated with a light coffee colour to highlight the change from one item to the next and provide visual interest:

![Project cards with alternating backgrounds](docs/project-alt-backgrounds.png)

#### Wireframes

*Home Page layouts for mobile and tablet:*

![Home Page - Mobile Wireframe](docs/home-mobile-tablet-wireframes.png)

*Home Page layout for desktop:*

![Home Page - Desktop Wireframe](docs/home-desktop-wireframe.png)

*About Page layouts for mobile and tablet:*

![About Page - Mobile Wireframe](docs/about-mobile-tablet-wireframes.png)

*About Page layout for desktop:*

![About Page - Desktop Wireframe](docs/about-desktop-wireframe.png)

*Portfolio Page layouts for mobile and tablet:*

![Portfolio Page - Mobile Wireframe](docs/portfolio-mobile-tablet-wireframes.png)

*Portfolio Page layout for desktop:*

![Portfolio Page - Desktop Wireframe](docs/portfolio-desktop-wireframe.png)

*Blog Page layouts for mobile and tablet:*

![Blog Page - Mobile Wireframe](docs/blog-mobile-tablet-wireframes.png)

*Blog Page layout for desktop:*

![Blog Page - Desktop Wireframe](docs/blog-desktop-wireframe.png)

*Contact Page layouts for mobile and tablet:*

![Contact Page - Mobile Wireframe](docs/contact-mobile-tablet-wireframes.png)

*Contact Page layout for desktop:*

![Contact Page - Desktop Wireframe](docs/contact-desktop-wireframe.png)

### Functionality & Features

This structure and content of this site was written in HTML and styled with CSS (including SASS/SCSS).

The site comprises the following **components**:

#### Header (Hero Unit)

Each page contains a Header component / Hero unit at the top.  All headers include:

- Background image - setting the aesthetic of the site
- Headshot image - to introduce me to the audience
- Title of page heading - in large text to make the purpose of the current page clear

*Header of the Home page:*

![Header](docs/header.png)

The semantic tag `<header>` has been used to indicate that this component appears near the top of the page and contains important information about it.

The primary purpose of the Header is to introduce the page to the user and make its purpose clear.

In the case of the Home page, it also communicates my full name and states my current role, via a short line of text under the heading, introducing me as a web development student:

*Web development student at Coder Academy*

The Header also provides visual interest to the page, via the background image and headshot.  On tablet and desktop views, it also provides visual balance to the page, offsetting the footer (which has a background colour chosen from the header image).

#### Navigational Bar (Nav)

The purpose of the Nav is to provide the user with clear and simple navigation throughout the site.

The semantic tag `<nav>` has been used to indicate that this component is a navigational bar containing links to other pages within the site.

On the Home page, the Nav includes links to the four second level pages:

1. About
2. Portfolio
3. Blog
4. Contact

The Home nav features four rectangular button-link links which clearly stand out and has three layout designs for different screen sizes:

The mobile view has the links vertically stacked, to fill the screen space:

![Home Nav - Mobile](docs/home-nav-mobile.png)

The table view is a 2 x 2 grid, to better fill tablet proportions:

![Home Nav - Tablet](docs/home-nav-tablet.png)

The desktop view moves to a 4 x 2 grid with the links appearing in odd numbered spaces, producing checkerboard-type effect, to better fill desktop proportions:

![Home Nav - Desktop](docs/home-nav-desktop.png)

On all second level pages, the Nav includes links to all of the five site pages, including Home:

1. Home
2. About
3. Portfolio
4. Blog
5. Contact

Due to the limited horizontal space available in portrait mobile views, the mobile nav bar is horiztonal, appearing below the header:

![Level 2 Pages - The mobile view](docs/lvl2-nav-mobile.png)

Ihe table and desktop views, the nav becomes a sidebar, to make better use of the increased horiztonal space:

![Level 2 Pages - Tablet](docs/lvl2-nav-tablet.png)

![Level 2 Pages - Desktop](docs/lvl2-nav-desktop.png)

#### Main Section (Second Level Pages)

The purpose of the Main section on the second level pages is to contain the primary information the page has been created to communicate, ie:

- About:  Information about my skills, experience and interests, including a link to my resume
- Portfolio:  Information about my recent projects
- Blog: Blog articles I have written
- Contact:  My contact information

*Main section of the Portfolio page:*

![Main section](docs/main-section.png)

The semantic tag `<main>` has been used to indicate that this component contains the main content the page.

The Home page does not contain a Main section, as, aside from introducing my name and role (which is done by the Header), it's main function is a to be a landing page allowing the user to quickly navigate to other site pages.  Therefore, the Nav occupies the middle section / primary real estate of the Home page.

#### Aside (About Page)

The purpose of the Aside is to be a container displaying a list of the blog posts with links to the full articles on the Blog page.  It appears on the About page, as the blog posts I have written further demonstrate my experience, skills and interests.

The semantic tag `<aside>` has been used to indicate that this component contains additional information, aside from the main page content.

The Aside contains multiple blog post summary elements, each of which is a component in it's own right and contains a summary of a blog post.  Each post listing contains an image for visual interest, in addition to title, date published, a brief summary sentence and a direct link to the full blog post.

Due to limited horizontal space on mobile layouts, the Aside appears underneath the Main section:

![Aside - mobile layout](docs/aside-mobile.png)

On tablet and desktop layouts, to make better use of available horizontal space, it appears on the right hand side of the screen next to the Main section.  In this way, it is more prominent to the user's attention and also provides some visual balance to the Nav bar on the left side of the main section.

*Aside in desktop layout:*
![Aside - mobile layout](docs/aside-desktop.png)

#### Project Sections (Portfolio Page)

Project sections appear within the Main section of the Portfolio page:

![Project Sections](docs/project-section.png)

The purpose of the Project sections is to demonstrate my technical skills by displaying my recent projects for potential employers to review.

The semantic tag `<section>` defined with `class="project"` has been used to indicate that this component is a section within its parent element that contains information on a project.

Each project section comprises:

1. The project name
2. A link to the project's Github repository - to enable viewers to view the full project and review my code
3. A project brief - a short description of the project's purpose
4. A project image - to give some idea of the project's appearence / end result and also to provide visual interest and draw the user's attention

#### Blog Post Articles (Blog Page)

Blog Post Articles appear within the Main section of the Blog page:

![Blog Article](docs/blog-article.png)

My site includes a Blog to further demonstrate my experience, skills and interests.

The purpose of each Blog Post Article is to contain a full blog post. The semantic tag `<article>` has been used for blog posts as each post is a self-contanied article that could be reused elsewhere, independent of other content on the Blog page.

Each Blog Post Article comprises:

1. An image - relevant to the blog topic and to draw user attention
2. Blog post title - to make clear the subject of the post
3. Date published - to give context regarding when the post was written
4. The text of the blog - the full article


#### Footer

The purpose of the footer is to display the site's copyright information on every page and to provide links to my social media profiles (if not otherwise provided in the main section of the page).

The semantic tag `<footer>` has been used to indicate that this component contains the footer content and appears at the bottom of the page.

On the tablet & desktop layouts, where height is restricted to the viewport height, the footer has a lighter background colour (chosen from the header image), distinguishing it from the main section of the page and also providing visual balance, as an offset to the header.

*Footer in mobile layout:*  
![Home Footer - Mobile](docs/home-footer-mobile.png)

*Footer in table layout:*  
![Home Footer - Tablet](docs/home-footer-tablet.png)