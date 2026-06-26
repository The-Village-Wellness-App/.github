# Welcome to...

<!-- Inline HTML that changes the banner image based on the chosen theme on GitHub -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./images/banner-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="images/banner-light.png">
  <img alt="Honey Banner" src="./images/banner-light.png">
</picture>

## Organisation Navigation

> * [Our Front-End Repository](https://github.com/The-Village-Wellness-App/village-frontend)
> * [Our Back-End Repository](https://github.com/The-Village-Wellness-App/village-backend)
> * [Our Project Documentation:](https://github.com/The-Village-Wellness-App/village-documentation/blob/main/README.md) [Organisation README,](https://github.com/The-Village-Wellness-App/.github/blob/main/profile/README.md) [Frontend README,](https://github.com/The-Village-Wellness-App/village-backend/blob/main/README.md) [and Backend README!](https://github.com/The-Village-Wellness-App/village-frontend/blob/main/README.md)
> * [Our JavaScript Style Guide](https://github.com/The-Village-Wellness-App/village-documentation/blob/main/javascript-style-guide.md)

## The Village Organisation

This project was created as part of an academic Web Development assessment using MongoDB, Express.js, React and Node.js (MERN Stack). The Village organisation is made up of a documentation repository, a backend application repository, and a frontend application respository.

Project work is seperated into two kanban project boards - one was used for [project planning](https://github.com/orgs/The-Village-Wellness-App/projects/2) in the initial stages of the project, and one for [build planning (currently private).](https://github.com/orgs/The-Village-Wellness-App/projects/1)

## Repository Navigation

* [Purpose of The Village Wellness App](#the-village-wellness-app)
* [Tech Stack](#tech-stack)
* [Intended Audience](#example-user-personas)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)

## The Village Wellness App

The Village Wellness App is a web-based health and wellbeing tracking application designed to help users monitor changes in their mood and physical pain over time. The application allows users to record structured entries using rating scales select predefined labels that describe their emotional or physical state, and optionally add contextual notes.
These entries are then visualised through time-based graphs, enabling users to identify patterns or trends in their wellbeing.

The application also allows users to add event markers to their timeline, such as starting a new medication, beginning therapy, or experiencing a significant life event. These markers provide additional context that may help users understand potential factors influencing their mood or pain levels. By combining structured tracking with visualisation tools, The Village Wellness App aims to support self-reflection and provide users with useful insights that may assist discussions with healthcare professionals.

## Tech Stack

* MongoDB Atlas
* Express.js
* React
* Node.js
* Mongoose

## Intended Audience

The Village Wellness App is intended for all persons, who may be wanting to track:

* Mood - Mental health & wellbeing
* Pain - Chronic, episodic, or acute pain
* Life Events - Specifically events that coincide with mood changes or pain level changes

### Example User Personas

![Persona: Priya](./images/persona1.png)

![Persona: Marc](./images/persona2.png)

![Persona: Destiny](./images/persona3.png)

![Persona: Selwyn](./images/persona4.png)

## Contributing

Thank you for your interest in contributing to this project.

### Getting Started

Repository options:

* village-frontend
* village-backend
* village-documentation

#### Example: Backend

```js
git clone https://github.com/The-Village-Wellness-App/village-backend.git
npm install
npm run dev
```

### Development Workflow

Create a new branch from the main branch.

```js
git checkout -b feature/your-feature-name
```

Make your changes. Commit using clear and descriptive commit messages.

```js
git commit -m "Add user profile validation"
```

Push your branch and create a pull request.

### Code Standards

* Follow existing project conventions
* Write clear and maintainable code
* Test changes before submitting
* Keep pull requests focused on a single feature or fix

### Issues

Before creating a new issue:

* Check whether a similar issue already exists
* Provide clear reproduction steps
* Include relevant screenshots or logs when appropriate

### Pull Requests

When submitting a pull request:

* Describe the purpose of the change
* Reference any related issues
* Ensure the application builds successfully
* Confirm that existing functionality has not been broken

### Code of Conduct

Contributors are expected to communicate respectfully and collaborate professionally throughout the project.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.txt) file for details.

This project uses third-party technologies including MongoDB, which is licensed under the Server Side Public License (SSPL).

## Authors

Created by [WhiteHotThrash](https://github.com/tim-maastricht) & [✨BeeGeeEss✨](https://github.com/BeeGeeEss)