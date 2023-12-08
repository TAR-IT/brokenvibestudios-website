# BROKEN VIBE STUDIOS - official website
Official portfolio website for **BROKEN VIBE STUDIOS** - an independent artist from germany.

## Table of Contents
1. [Technologies Used](#technologies-used)
2. [User Experience](#user-experience)
    - [User Stories](#user-stories)
    - [Design Decisions](#design-decisions)
    - [Accessibility](#accessibility)
3. [Getting Started](#getting-started)
    - [Installing](#installing)
    - [Testing](#testing)
    - [Contributing](#contributing)
6. [License](#license)

## Technologies Used
- [HTML](https://www.w3.org/)
    - The project uses **HTML** to create the page.
- [Bootstrap](https://getbootstrap.com/)
	- The project uses the **Bootstrap 4.5.2** framework for styles mainly.
- [CSS](https://www.w3.org/)
    - The project uses custom **CSS** in addition to Bootstrap.
- [JavaScript](https://developer.mozilla.org/bm/docs/Web/JavaScript)
    - The project uses **JavaScript** to manipulate the DOM.
- [GitHub Pages](https://pages.github.com/)
    - **GitHub Pages** is used as the hosting platform via a fork of this repository.

## User Experience

### User Stories
- As a user, i should be able to switch between languages (en/de) if I want, since there are local people looking for music lessons and international people looking for e.g. a producer.
- As a user, I should be able to find information about the studio and the music lessons seperately depending on what I am looking for on the website.
- As a user, I should be able to find contact information about the owner of the website via a "Contact" page. This page should contain links to social media-accounts and provide an email address.
- As a user, I should not be forced to accept cookies. The portfolio website should keep data transfer as low as possible.

### Design Decisions
To keep the project simple and maintainable for the client himself, no plugins are used. The website contains a "/de" directory for german pages and a "/en" directory for english pages.<br>
The english versions of "index.html" and "404.html" are placed in the root directory to be used as defaults. This provides users the choice to be redirected to a german alternative of the page without having to get information about the language from their browser in the first place, thus preventing cookies to be cached - keeping the Privacy Policy simple.<br>
The visuals of the website are kept simple using Bootstrap 4.5.2 and some custom css. The colors/fonts are analogous to the theme of Broken Vibe Studios.

### Accessibility
To provide accessibility for english and german native speakers, a "language switch button" is implemented into each site. English is the default language.

## Getting Started

### Installation
1. Clone/fork or download the repository.
2. Open index.html in your web browser of choice.

### Testing
No tests have been applied yet.

### Contributing
Contributing on this project is not intended for public.

## License
No licensing is done on this project yet