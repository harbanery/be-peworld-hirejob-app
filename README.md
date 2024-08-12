<div align="center">
  <img src="./public/peworld.png" alt="Logo Peworld" width="200"/>
</div>

# Back-End for Peworld: Hire Job Implementation

<details>
  <summary>Table of Contents</summary>
  <ul>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#documentation">Documentation</a></li>
        <li><a href="#project-related">Project Related</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ul>
</details>

## About The Project

This back-end project for **Peworld** was developed by [muhammadrisano](https://github.com/muhammadrisano) using Express.js. Feel free to explore the source code, which I have forked from the original repository. It includes all the files and documentation needed to develop and run the server side of this application. Thank you for developing this back-end project.

### Built With

- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/en)
- [PostgreSQL](https://www.postgresql.org/)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Ensure you have the following installed on your local machine:

- npm

  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone Repo

   ```sh
   git clone https://github.com/harbanery/be-peworld-hirejob-app.git
   ```

2. Go to folder directory

   ```bash
   cd be-peworld-hirejob-app
   ```

3. Install NPM packages

   ```sh
   npm install
   ```

4. To start the development server:

   ```sh
   npm run dev
   ```

## Usage

To use this project, follow the instructions below for understanding the project structure and how to use the provided API documentation.

### Project Structure

```
be-peworld-hirejob-app/
├── node_modules/
├── public/
│   └── peworld.png
├── src/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── auth/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── experience/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── hire/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── portfolio/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── recruiter/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── skill/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   ├── workers/
│   │   |   ├── index.js
|   |   |   └── request_model.js
│   │   └── upload.js
│   ├── helpers/
│   │   ├── auth.js
│   │   └── common.js
│   ├── middlewares/
│   │   ├── auth.js
│   │   └── upload.js
│   ├── models/
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── users.js
│   │   └── workers.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── index.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── upload.js
│   │   └── workers.js
│   └── utils/
│       └── cloudinary.js
├── .gitignore
├── README.md
├── index.js
├── package-lock.json
├── package.json
├── vercel.json
└── yarn.lock
```

### Documentation

Access the API documentation for the **Peworld** project, also created by [him](https://github.com/muhammadrisano). Use this documentation to test endpoints and understand the structure and functionality of the available APIs in this project.

[![Peworld API Postman Documentation](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/36623326/2sA3s4kqFe)

### Project Related

- [`Front-End Project Repository Link`](https://github.com/harbanery/peworld-hirejob-app)

- [`Front-End Demonstration Link`](https://peworld-hirejob.vercel.app/)

- [`Back-End Demonstration Link`](https://fwm17-be-peword.vercel.app/)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

If you have any questions or inquiries regarding this back-end project, feel free to contact him at [Github](https://github.com/muhammadrisano) or [LinkedIn](https://www.linkedin.com/in/muhammad-risano-80847b152/). Or if you just want to get in touch with me, feel free to contact me at ryusuf05@gmail.com or [LinkedIn](https://www.linkedin.com/in/raihan-yusuf/)

## Acknowledgements

Feel free to check it out:

- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com/)
- [GitHub Pages](https://pages.github.com/)
