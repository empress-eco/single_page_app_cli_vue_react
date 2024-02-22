<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project logo">
    <h1 align="center">Empress Doppio: Single Page App CLI for Vue & React</h1>
    <p align="center">
        A robust command-line tool to set up and manage single page applications on your custom apps.
        <br />
        <a href="https://grow.empress.eco/">Explore the Docs</a>
        ·
        <a href="https://github.com/empress-eco/single_page_app_cli_vue_react/issues">Report Bug</a>
        ·
        <a href="https://github.com/empress-eco/single_page_app_cli_vue_react/issues/new">Request Feature</a>
    </p>
</div>

## About The Project

Empress Doppio is a flexible and efficient command-line tool that simplifies the process of setting up and managing single-page applications (SPAs) using Vue 3 or React. Designed with the developer in mind, it provides a streamlined process for integrating an SPA into your application, while offering the flexibility to create custom desk pages. 

### Key Features

- Simplify the setup of a new single-page application on your custom app.
- Choose between Vue 3 or React for your SPA.
- Opt to use TypeScript or JavaScript.
- Enable Tailwind CSS setup along with the SPA.
- Add a starter project to your custom app.
- Set up React or Vue-powered custom desk pages.
- Build for production and have it placed in the `www` directory of your app.

## Technical Stack and Setup Instructions

Empress Doppio is built with Vue 3, React, and TypeScript. It uses the bench CLI which must be installed in your development environment before using this tool.

### Installation

To install Empress Doppio, clone the repository and navigate to your bench directory:

```bash
git clone https://github.com/empress-eco/single_page_app_cli_vue_react.git
cd single_page_app_cli_vue_react
```

Then run the command:

```bash
bench get-app doppio
```

To set up a new single-page application, run the following command in your bench directory:

```bash
bench add-spa --app <app-name> [--tailwindcss] [--typescript]
```

Alternatively, run `bench add-spa` and follow the prompts.

## Usage

To start using Empress Doppio, navigate to the SPA directory of your app (e.g. `dashboard`) and run:

```bash
yarn dev
```

This starts a development server at port 8080 by default. You can now start developing your SPA!

## Contribution Guidelines

We welcome contributions from the community! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

This project is licensed under the MIT License. Your contributions are also licensed under the same.

We would like to express our gratitude to the Empress Community for their foundational contributions. Their innovation and dedication have been instrumental to the development of this project. We are immensely thankful for their pioneering work and ongoing support.