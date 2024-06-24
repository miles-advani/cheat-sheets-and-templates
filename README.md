# README Boilerplate

## Table of Contents

1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Basic Structure](#basic-structure)
5. [Data Fetching](#data-fetching)
6. [Changelog](#changelog)
7. [Contributing](#contributing)
8. [License](#license)

## Description

This is a boilerplate for creating a README file for a GitHub repository. It provides a structured format with sections that can be customized to suit the needs of the project.

<details>
<summary>Preview Image</summary>
<br>
Example Image
<br><br>
<img src="https://github.com/miles-advani/repo-readme-boilerplate/blob/main/images/example-image.png">
</details>

1. **About Me**: This section provides a brief introduction and background information about the developer.

<details>
<summary>Projects</summary>
<br>
Preview
<br><br>
<img src="https://raw.githubusercontent.com/MilesAdvani/Portfolio/main/public/images/portfolio-projects-image.png" alt="About Me Image">
</details>

2. **Projects**: This section displays a collection of web development projects. Each project is accompanied by an individual blog post that delves into the details of the project.

<details>
<summary>Contact</summary>
<br>
Preview
<br><br>
<img src="https://raw.githubusercontent.com/MilesAdvani/Portfolio/main/public/images/portfolio-contact-image.png" alt="About Me Image">
</details>

3. **Contact**: This section provides a means for visitors to get in touch.

The portfolio is multilingual, supporting both English and German, with the ability to switch languages via a button in the header. It also saves the user's language preference in local storage for future visits.

Data for the portfolio is fetched from local JSON files using the Context API, ensuring efficient data management within the React application.

Designed with a responsive layout, the portfolio provides an optimal viewing experience across a wide range of devices - from desktop web browsers to mobile phones.

Additionally, it includes a Dark Mode feature that adjusts the color scheme of the portfolio based on the user's local system settings, providing a comfortable viewing experience in different lighting conditions.

## Installation

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

- Change all data related to the Layout (Header/MainMenu & Footer) and the Headers of the Projects section inside of the JSON files in the `src/assets/data/layoutDataEnglish.json` / `src/assets/data/layoutDataGerman.json` file to your own data.

- Change all data related to the About section inside of the JSON files in the `src/assets/data/profileDataEnglish.json` / `src/assets/data/profileDataGerman.json` file to your own data.
- Profile Image should be placed in the `src/assets/images` folder, and the file name should be `profile-picture.png`.

- Change all data related to the Projects section inside of the JSON files in the `src/assets/data/projectDataEnglish.json` / `src/assets/data/projectDataGerman.json` file to your own data.
- Project Images should be placed in the `src/public/images/` folder, and the file name should match the `image` key in the JSON file.

- Change all data related to the Project Collaborations section inside of the JSON files in the `src/assets/data/projectCollaborationsDataEnglish.json` / `src/assets/data/projectCollaborationsDataGerman.json` file to your own data.

- Change all data related to the Blog Posts section inside of the JSON files in the `src/assets/data/blogPostsDataEnglish.json` / `src/assets/data/blogPostsDataGerman.json` file to your own data.

- Change all data related to the Contact section inside of the JSON files in the `src/assets/data/contactDataEnglish.json` / `src/assets/data/contactDataGerman.json` file to your own data.

## Basic Structure

### [App](https://github.com/MilesAdvani/Portfolio/blob/main/src/App.jsx) / React Router:

- **[Portfolio](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/portfolio) Page**: The root URL `"/"` directs to the `Portfolio` component. This is the main landing page of the
- **[BlogPosts](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/blog-posts) Page**: The URL parameter `"/blog/:projectId"` is used by the `BlogPosts` component. This allows for dynamic routing based on the project ID, which is accessed through the `useParams` Hook. Each individual project has its own unique URL under the `/blog` route.

- **[NotFound](https://github.com/MilesAdvani/Portfolio/tree/main/src/pages/not-found) Page**: A catch-all route `"*"` is delegated to the `NotFound` component. This component is displayed when a user navigates to a route that does not exist in the application, providing a user-friendly error message.

### [LanguageContext](https://github.com/miles-advani/Portfolio/blob/main/src/store/language-context/LanguageContext.jsx) / Context API:

- Avoid Prop Drilling
- Fetches local [JSON files](https://github.com/MilesAdvani/Portfolio/tree/main/src/assets/data) (in 2 languages)
- Is responsible for the language-switching functionality

### [FontAwesome](https://github.com/miles-advani/Portfolio/blob/main/src/utils/font-awesome/FontAwesome.jsx):

- Provides a library of icons for use in the application
- Uses the FontAwesome key through the .env file.
- [.env-example](https://github.com/miles-advani/Portfolio/blob/main/.env-example)

### [FavIcon SVG](https://github.com/miles-advani/Portfolio/blob/main/public/favicon.svg)

### Pages / Components Structure:

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

## Data Fetching

### `JSON Files` →→→

### →→→ `LanguageContext` →→→

- `LanguageProvider`
  - Uses `useState` to initialize `profileData`, `projectData`, `projectCollaborationsData`, and `contactData` state variables with either English or German data based on the `initialLanguage` value.
  - The `initialLanguage` is retrieved from `localStorage`. If no language is stored in `localStorage`, it defaults to `"eng"`.
  - The `switchToEnglish` and `switchToGerman` functions update the application's language by setting state variables with English or German data and storing the chosen language in `localStorage`.

→ ( `LanguageButton` ) →

- Utilizes **useState** to establish a local state variable, **activeLanguage**, which is initially set to "eng
- The **useEffect** hook checks `localStorage` for a language and, if found, updates **activeLanguage** accordingly.
- **handleEnglishClick** and **handleGermanClick** functions call the switchToEnglish and switchToGerman functions from the LanguageContext and update the activeLanguage state.
- Returns two buttons. The className of each button is conditionally set to "active" based on the value of activeLanguage.
- The **onClick handlers** of the buttons are set to the **handleEnglishClick** and **handleGermanClick**.

### → `MainMenu`

JSON files: `LayoutDataEnglish` / `LayoutDataGerman`

- Utilizes the **Context Hook** to fetch `layoutData`.
- Extracts the **menuLinks data object** from `layoutData`.


### → `AboutMe` →

→ `Profile`

→ `AboutMeSlider`

→ `TechStackSlider`

JSON files: `ProfileDataEnglish` / `ProfileDataGerman`

- Utilizes a **helper function** to retrieve data from **Context** using an **Id**.
- Propagates data to child components using the **spread operator** as **props**. (This could be considered bad practice if not all props are necessary for the child components.)

### → `Projects` →

→ `ProjectCard` → `ProjectLinks` ( Prop Drilling / Passing the ID )

JSON files: `ProjectDataEnglish` / `ProjectDataGerman` + `ProjectCollaborationsDataEnglish` / `ProjectCollaborationsDataGerman`
`LayoutDataEnglish` / `LayoutDataGerman`

- Utilizes the **Context Hook** to fetch data.
- **Maps** over the **keys** of these data **objects**.
- Passes each **key** and its corresponding data object to `ProjectCard`.
- `ProjectCard`s are rendered based on the number of data objects.
- Therefore, the order of the `ProjectCard`s is determined by the order in the JSON file.

### → `Contact`

JSON files: `ContactDataEnglish` / `ContactDataGerman`

- Utilizes the **Context Hook** to fetch data.
- **Maps** over the `socialLinks` **array** in `contactData` and **conditionally** creates a **link** for each item.
- Additionally, an **email link** is **conditionally rendered** if it exists in `contactData`.

### → `Footer`

JSON files: `LayoutDataEnglish` / `LayoutDataGerman`

- Utilizes the **Context Hook** to fetch `layoutData`.
- Extracts the **copyright data object** from `layoutData`.
- Extracts the **portfolioCode** link and the **backToTop** link from `layoutData`.

### → `ProjectLinks`

JSON files: `ProjectDataEnglish` / `ProjectDataGerman` + `ProjectCollaborationsDataEnglish` / `ProjectCollaborationsDataGerman`

- Utilizes the **Context Hook** to fetch data based on the **ID** provided by the parent component (either `BlogPosts` or `ProjectCard` - the ID is always the same).
- If **data is not found**, both `codeLink` and `previewLink` default to an **empty string**.
- **Conditionally renders** "Code" and "Preview" links if `codeLink` and `previewLink` are not **empty strings**.

### → `BlogPosts` →

→ `BlogPost`
→ `ProjectLinks` ( Passing the ID)

JSON files: `ProjectDataEnglish` / `ProjectDataGerman` + `ProjectCollaborationsDataEnglish` / `ProjectCollaborationsDataGerman`

- Utilizes the **useParams Hook** to extract the **ID** (`projectId`) from the **URL** (URL is received from `ProjectCard` via the "Read More" link).
- The **ID** is used to fetch data from **LanguageContext** by matching it with an **Object Key**.

- Uses **useEffect** to execute `window.scrollTo(0, 0);` which scrolls the window to the top.

## Media Queries

- tablet 1366px
- tablet 1024px
- mobile 768px
- mobile 510px
- mobile 320px

## Changelog

- Added a new feature...
- Fixed a bug...

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/your-account-name/your-repo-name?tab=MIT-1-ov-file)

[Back to Top](#readme-boilerplate)
