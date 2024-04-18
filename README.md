# Foodie Finder for the Masses

Welcome to the project repository for Foodie Finder, the innovative web application designed to enhance the way food enthusiasts discover and interact with food trucks in real-time. This repository contains all the source code and documentation needed to deploy, manage, and contribute to the Foodie Finder application.

## Table of Contents

- [Getting Started](##getting-started)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Getting Started

These instructions provide a guide to getting a copy of the project up and running on your local machine for development and testing purposes. See the deployment section for notes on deploying the project on a live system.

## Features

Foodie Finder offers several exciting features:
- **Real-Time GPS Tracking:** See live updates of food trucks near you.
- **Advanced Search and Filters:** Customize searches by cuisine, price, or dietary preferences.
- **Interactive Map and Directory:** Explore the food truck scene with an interactive map interface.
- **Favorites and Notifications:** Save your favorite trucks and receive updates.

## Project Structure
```
/app
│
├── /public                # Static files like index.html, favicon, etc.
│   └── index.html         # Main HTML file
│
├── /src                   # Source files for the application
│   ├── /assets            # Media files like images, fonts, etc.
│   │
│   ├── /components        # Reusable UI components
│   │   ├── /common        # Common components like buttons, cards, etc.
│   │   └── /layout        # Layout components like headers, footers, etc.
│   │
│   ├── /hooks             # Custom React hooks
│   │
│   ├── /pages             # Components that act as views/pages
│   │   ├── Home.tsx       # Home page component
│   │   ├── About.tsx      # About page component
│   │   └── Contact.tsx    # Contact page component
│   │
│   ├── /styles            # Tailwind entry point and custom styles
│   │   └── main.css       # Main stylesheet file
│   │
│   ├── /types             # TypeScript type definitions and interfaces
│   │
│   ├── /utils             # Utility functions and helpers
│   │
│   └── App.tsx            # Main application component
│   └── index.tsx          # Entry point for React application
│
├── /tests                 # Test files
│   ├── /integration       # Integration tests
│   └── /unit              # Unit tests
│
├── package.json           # NPM package manager file
├── tailwind.config.js     # Tailwind CSS configuration file
├── tsconfig.json          # TypeScript configuration file
└── README.md              # Project overview and setup instructions

/docs
│
├── /technical_specs       # Technical specifications for the application
│   ├── architecture.md    # Detailed architecture of the application
│   ├── api_specifications.md  # API endpoints and their specifications
│   └── database_schema.md # Schema designs for the database
│
├── /developer_guides      # Guides for developers
│   ├── setup_guide.md     # Setup and installation instructions
│   ├── contribution_guide.md  # Guide on how to contribute to the project
│   ├── testing_guide.md   # Instructions and guidelines for testing
│   └── deployment_guide.md    # Deployment processes and guidelines
│
├── /style_guides          # Coding and design style guides
│   ├── code_style.md      # Code formatting and best practices
│   └── design_principles.md  # UI/UX design guidelines and principles
│
├── /user_personas         # Descriptions of typical users of the application
│   └── personas.md        # Detailed user personas to guide feature development
│
└── /miscellaneous         # Other documentation
    ├── faq.md             # Frequently Asked Questions
    ├── troubleshooting.md # Common issues and their resolutions
    └── glossary.md        # Glossary of terms used in the project
```

### Description of Key Application Directories and Files:

- **/public**: Contains static assets like the `index.html` which is the entry point for the HTML structure, and other static resources such as favicon or manifest files.

- **/src**: The core directory where all the source code resides.
  - **/assets**: Houses images, icons, fonts, and other static files used across the application.
  - **/components**: Contains all React components, divided into subdirectories like `/common` for general-use components and `/layout` for structural components.
  - **/hooks**: For custom React hooks that can be reused across components.
  - **/pages**: Components that represent entire pages of the app, allowing for a clear distinction between different views.
  - **/styles**: Includes CSS files, particularly for Tailwind CSS customizations.
  - **/types**: TypeScript interfaces and type declarations to ensure type safety across the app.
  - **/utils**: Utility functions that provide common functionality throughout the application.

- **/tests**: Contains all testing files, with subdirectories for different types of tests (unit, integration).

- **package.json**: Manages project dependencies and scripts.
- **tailwind.config.js**: Configuration for Tailwind CSS to customize the framework to the project's needs.
- **tsconfig.json**: Configures TypeScript compiler options.

To effectively manage the documentation for the Foodie Finder web application, a structured and clear directory layout within the `/docs` directory is essential. This structure not only facilitates ease of access and navigation for team members but also ensures that all aspects of the application's documentation are thoroughly covered and easily maintainable.

### Explanation of Each Documentation Directory:

- **/technical_specs:** Contains all technical details about the application, including architecture diagrams, API specifications, and database schema. This documentation is crucial for new developers and architects to understand the system’s backbone.

- **/developer_guides:** Provides all necessary information for developers, covering how to set up the development environment, contribute to the project, test their code, and deploy the application. This section ensures that developers have a uniform understanding of how to interact with the project.

- **/style_guides:** Maintains standards for code and design across the project. Code style guides help in maintaining readability and uniformity in the codebase. Design principles ensure that the user interface remains consistent and adheres to best practices.

- **/user_personas:** Describes the target users of the application. Understanding user personas helps in tailoring features and the user interface to meet the needs of these users.

- **/miscellaneous:** Houses documents that do not neatly fit into other categories but are still vital for the project, like FAQs, troubleshooting guides, and a glossary of terms.

This documentation structure will help keep the repository organized and make it easier for team members to find and use the information they need. It also ensures that documentation is comprehensive and covers all aspects necessary for a well-rounded understanding of the project.

## Technologies Used

- **Frontend:** TypeScript, Tailwind CSS, Three.js for 3D effects
- **Backend:** Node.js, Next.js
- **Database:** TBD (the database architecture is yet to be defined)
- **Others:** Docker, AWS (for deployment)

## Installation

To set up your local development environment:

```bash
# Clone the repository
git clone https://github.com/macon-code/FoodieFinder.git

# Go into the app directory
cd FoodieFinder/app

# Install dependencies
npm install

# Start the development server
npm start
```

## Usage

After installation, open your web browser and access http://localhost:3000 to view the application.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. Please refer to the CONTRIBUTING.md file for our contribution guidelines.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

For further information or support, please email us at email@email.com or open an issue in this repository.
