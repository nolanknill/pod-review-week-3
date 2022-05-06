## Instructions
- Follow the mockups to make index.html
- The following color codes will be useful:
  header background: #fff
  body background: #dcc6bf
  footer background: #132D34


# Planning

- What is our breakpoint? 
  - 768px

- Header font-size:
  - Desktop: 1.5rem
  - Mobile: 1.25rem

- Vertical padding is different
  - Desktop: 2rem
  - Mobile: 1rem

- Horizontal-padding:
  - Same for desktop and mobile: 2rem 

- Desktop has 3 links
- Mobile has hamburger menu


- Structure:

<header>
  <nav class="nav">
    <a class="nav__site-name" href="/">Header</a>
    <a class="nav__hamburger hamburger" href="#hamburger">
      <div class="hamburger__bar"></div>
      <div class="hamburger__bar"></div>
      <div class="hamburger__bar"></div>
    </a>
    <ul class="nav__list">
      <li class="nav__item">
        <a class="nav__link" href="#">Link 1</a>
      </li>
      <li class="nav__item">
        <a class="nav__link" href="#">Link 2</a>
      </li>
      <li class="nav__item">
        <a  class="nav__link" href="#">Link 3</a>
      </li>
  </nav>
</header>

- styles:
  - justify-content: space-between

- html structure  will have to have both list of links and the hamburger menu
  - in css: 
    - in mobile (default): 
        - hamburger menu will be displayed (display: block)
        - links list will not be displayed (display:none) 
    - at the desktop:
      - hamburger menu will be hidden (display: none)
      - links list will be displayed (display: flex)