<!-- Logo=============================== -->

<details>
<summary>How to create a logo for your GitHub repository:</summary>
<br>

Logos are a great way to brand your GitHub repository. They can be used to showcase your personal brand, company, or project. You can create a logo using a graphic design tool like Adobe Illustrator, Figma, or Sketch. Once you have created your logo, you can export it as an SVG file and add it to your GitHub repository.

- With Figma: Visit [Figma](https://www.figma.com/) and create a new file. Design your logo using shapes, text, and colors. Once you are happy with your design, export it as an SVG file (Select your Logo with the mouse, right-click, and select copy as SVG). You can then add the SVG file to your GitHub repository.

</details>

[![Logo](https://github.com/miles-advani/cheat-sheets-and-templates/blob/main/assets/logos/ma-dev-logo.svg)](https://www.miles-advani.com/)

# README Template V1

<!-- Badges=============================== -->

<details>
<summary>How to add a badge to your GitHub repository:</summary>
<br>

Badges are a great way to showcase the status of your project. They can be used to display information such as the version, build status, coverage, stars, pull requests, forks, issues, downloads, and license.

- Generate Badge on Shields.io: Visit [Shields.io](https://shields.io/) and find the badge you want to create. Shields.io allows you to customize badges for version, build status, coverage, and more.

- Customize Your Badge: Follow the instructions on Shields.io to customize your badge. This usually involves selecting options from a form or modifying a URL to reflect your specific data (like your GitHub username and repository name).

- Copy the Badge Markdown Code: Once your badge is customized, Shields.io will provide you with Markdown code. Copy this code.

- Paste the Badge in Your README File: Open your README.md file in your GitHub repository and paste the copied Markdown code at the desired location in the file.
</details>

![Version](https://img.shields.io/github/package-json/v/miles-advani/repo-readme-boilerplate)
![Build Status](https://img.shields.io/github/workflow/status/miles-advani/repo-readme-boilerplate/CI)
![Coverage](https://img.shields.io/codecov/c/github/miles-advani/repo-readme-boilerplate)
![Stars](https://img.shields.io/github/stars/miles-advani/repo-readme-boilerplate?style=social)
![Pull Requests](https://img.shields.io/github/issues-pr/miles-advani/repo-readme-boilerplate)
![Forks](https://img.shields.io/github/forks/miles-advani/repo-readme-boilerplate?style=social)
![Issues](https://img.shields.io/github/issues/miles-advani/repo-readme-boilerplate)
![Downloads](https://img.shields.io/github/downloads/miles-advani/repo-readme-boilerplate/total)
![License](https://img.shields.io/github/license/miles-advani/repo-readme-boilerplate)

<!-- Index=============================== -->

## Table of Contents

1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technical Documentation](#technical-documentation)
6. [Contributing](#contributing)
7. [License](#license)
8. [Changelog](#changelog)

## Description

This is a template for creating a README file for a GitHub repository. It provides a structured format with sections that can be customized to suit the needs of the project. Additionally it includes instructions on how to add a logo, badges, and a license to the repository.

<details>
<summary>Preview Image</summary>
<br>
Example Image
<br><br>
<img src="https://github.com/miles-advani/cheat-sheets-and-templates/blob/main/assets/images/example-image.png">
</details>

<br>

<details> <summary>Tech Stack</summary> 
<br> 
<ul>
  <li>Markdown</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>[Add other technologies used]</li>
</ul>
</details>

<br>

<details> <summary>How do I dropdown?</summary> <br> This is how you dropdown. <br><br> <pre> &lt;details&gt; &lt;summary&gt;How do I dropdown?&lt;&#47;summary&gt; &lt;br&gt; This is how you dropdown. &lt;&#47;details&gt; </pre>

<br>

<details> <summary>How do I dropdown with a Image?</summary> <br> This is how you dropdown with a Image. <br><br> < img bla bla ... /> </details>

</details>

## Installation

Instructions on how to clone and set up the project locally. This section is crucial for getting developers started with the project.

- Example:

Before you begin, ensure you have met the following requirements:

- You have installed Node.js and npm
- You have a `<specific OS>` operating system

1. Clone the repository:

```bash
git clone git@github.com:your-account-name/your-repo-name.git
```

2. Navigate to the project directory:

```bash
cd your-repo-name
```

3. Install the dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

## Usage

Explain how to use the project or software, including any commands or scripts for running it. This section can also include examples of the project in action.

<details>
<summary>Preview Image</summary>
<br>
Example Image
<br><br>
<img src="https://github.com/miles-advani/cheat-sheets-and-templates/blob/main/assets/images/example-image.png">
</details>

## Features

Detail the key features and functionalities of the project. This helps developers understand what the project can do.

- Feature 1: Description
- Feature 2: Description
- Feature 3: Description

## Technical Documentation

If the project is complex, include a link to more detailed technical documentation or create a section that dives deeper into the architecture, design decisions, and more intricate details of the project.

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

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

For detailed guidelines, see [CONTRIBUTING.md](path/to/CONTRIBUTING.md).

## License

<details>
<summary>How to add a license to your GitHub repository:</summary>
<br>

- Navigate to Your Repository: Open your GitHub repository where you want to add the license.

- Click on Add file: Click on the Add file dropdown and select Create new file.
<details>
<summary>Preview Image (Add file)</summary>
<br>

<img src="https://github.com/miles-advani/cheat-sheets-and-templates/blob/main/assets/images/add-a-license.png">
</details>

- Name the file: In the text field, type LICENSE.

- Choose a license template: Click on Choose a license template and select the license you want to add.

- Preview the license: Click on Review and submit.
</details><br>

Example:

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/your-account-name/your-repo-name?tab=MIT-1-ov-file)

## Changelog

Keep a record of all the changes made to the project over time. This is useful for developers to track progress and updates.

- **v1.0.0**: Initial release with features A, B, and C.
- **v1.1.0**: Added feature D.
- **v1.1.1**: Fixed bug in feature B.

[Back to Top](#readme-template-v1)
