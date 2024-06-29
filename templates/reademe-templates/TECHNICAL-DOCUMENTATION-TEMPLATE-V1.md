[![Logo](https://raw.githubusercontent.com/miles-advani/dev-launch-kit/164991da3e5bc7a557e8d0861a52088d8894250a/assets/logos/logo-ma-dev.svg)](https://www.miles-advani.com/)

# Technical Documentation Template

This template provides a structure for documenting technical details about a project.

It can be used to consolidate various technical details, such as architecture descriptions, environment setup instructions, dependency information, and more, alongside the file structure.

## Table of Contents

1. [File Structure](#file-structure)

### File Structure

This file structure is an example based on [My Portfolio](https://github.com/miles-advani/Portfolio).

<details>
<summary>Basic Structure</summary>
<br>

<br>

<pre>
project-root/
├── public/
│   └── icons/
│   └── images/
│   └── favicon.svg
├── src/
│   └── assets/
│   └── components/
│   └── pages/
│   └── store/
│   └── utils/
│   └── App.jsx
│   └── index.cssc
│   └── main.jsx
├── .env
├── index.html
├── LICENSE
├── package.json
└── README.md
</pre>
</details>

### Pages / Components Structure:

- #### [App](https://github.com/MilesAdvani/Portfolio/blob/main/src/App.jsx)

  #### [Portfolio](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/portfolio)

  - [Layout](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/layout)

    - [Header](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/header)
      - [Logo](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/logo)
        - [LogoSVG](https://github.com/miles-advani/Portfolio/blob/main/src/assets/logo.svg)
      - [MainMenu](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/main-menu)
      - [LanguageButton](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/language-button)
    - [Footer](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/footer)

  - [AboutMe](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/about-me)
    - [Profile](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/profile)
      - [ProfileImage](https://github.com/miles-advani/Portfolio/blob/main/src/assets/images/profile-picture.png)
    - [AboutMeSlider](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/about-me-slider)
    - [TechStackSlider](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/tech-stack-slider)
      - [TechStackIconSVGs](https://github.com/miles-advani/Portfolio/tree/main/public/icons)
  - [Projects](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/projects)

    - [ProjectCard](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/project-card)
      - [ProjectImages](https://github.com/miles-advani/Portfolio/tree/main/public/images)
      - [ProjectLinks](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/project-links)

  - [Contact](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/contact)

  #### [BlogPosts](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/blog-posts)

  - [Layout](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/layout)

    - [Header](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/header)
      - [Logo](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/logo)
        - [LogoSVG](https://github.com/miles-advani/Portfolio/blob/main/src/assets/logo.svg)
      - [MainMenu](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/main-menu)
      - [LanguageButton](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/language-button)
    - [Footer](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/footer)

  - [BlogPosts](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/blog-post)

  - [ProjectLinks](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/project-links)

  #### [NotFound](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/not-found)

  - [Layout](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/layout)
    - [Header](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/header)
      - [Logo](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/logo)
        - [LogoSVG](https://github.com/miles-advani/Portfolio/blob/main/src/assets/logo.svg)
      - [MainMenu](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/main-menu)
      - [LanguageButton](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/language-button)
    - [Footer](https://github.com/MilesAdvani/Portfolio/tree/main/src/components/footer)

[Back to Top](#readme-template-v1)

<!-- ============================================================================== -->
<!-- ============================================================================== -->
<!-- !!! DELETE OR COMMENT OUT EVERYTHING BENEATH THIS COMMENT !!!   ↓↓↓↓↓↓↓↓↓↓↓↓↓↓ -->

<details>
<summary>How to create a logo for your GitHub repository:</summary>
<br>

Logos are a great way to brand your GitHub repository. They can be used to showcase your personal brand, company, or project. You can create a logo using a graphic design tool like Adobe Illustrator, Figma, or Sketch. Once you have created your logo, you can export it as an SVG file and add it to your GitHub repository.

- With Figma: Visit [Figma](https://www.figma.com/) and create a new file. Design your logo using shapes, text, and colors. Once you are happy with your design, export it as an SVG file (Select your Logo with the mouse, right-click, and select copy as SVG). You can then add the SVG file to your GitHub repository.

</details>

<details> <summary>How do I dropdown?</summary> <br> This is how you dropdown. <br><br> <pre> &lt;details&gt; &lt;summary&gt;How do I dropdown?&lt;&#47;summary&gt; &lt;br&gt; This is how you dropdown. &lt;&#47;details&gt; </pre>

<br>

<details> <summary>How do I dropdown with a Image?</summary> <br> This is how you dropdown with a Image. <br><br> < img bla bla ... /> </details>

</details>
