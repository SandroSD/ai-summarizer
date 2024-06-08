# URL Summarizer

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

![React](https://img.shields.io/badge/react-v18.0.2-blue.svg)
![Redux](https://img.shields.io/badge/redux-v9.1.2-blue.svg)
![Tailwind](https://img.shields.io/badge/tailwindcss-v3.4.3-blue.svg)
![Vite](https://img.shields.io/badge/vite-v5.2.0-blue.svg)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Project Overview

**URL Summarizer** is a web application built with React.js and Redux that allows users to input a URL and receive a summarized version of the webpage content. This project leverages an API to fetch and summarize the webpage.

## Features

- **URL Input**: Enter a URL to summarize.
- **Summarization**: Get a concise summary of the webpage content.
- **Responsive Design**: Works on various devices and screen sizes.
- **State Management**: Uses Redux for managing application state.

## Demo

Check out the live demo [here](#).

> Not available the demo yet.

![URL Summarizer Screenshot](example.png)

## Technologies Used

- **Frontend**: React.js, Redux
- **Styling**: TailwindCSS
- **Build Tools**: Vite
- **API**: URL Summarization API

## Installation

First, duplicate `.env.sample`and rename it as `.env`.

It will have the following variable:

```shell
VITE_RAPID_API_ARTICLE_KEY
```

Go to [RapidApi](https://rapidapi.com/restyler/api/article-extractor-and-summarizer) and click `/summarize` endpoint. Then copy the value of the following key `X-RapidAPI-Key` and paste in the `.env` variable.

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/SandroSD/web-summarizer
   ```

2. **Navigate to the project directory**:

   ```sh
   cd web-summarizer
   ```

3. **Install dependencies**:

   ```sh
   pnpm install
   ```

4. **Start the development server**:
   ```sh
   pnpm run dev
   ```

The application will be available at `http://localhost:5173`.

## Usage

1. Open the application in your browser.
2. Enter the URL of the webpage you want to summarize in the input field.
3. Click the "Summarize" button.
4. View the summary displayed on the screen.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## Acknowledgements

- Thanks to the developers of React and Redux for their amazing tools.
- Special thanks to the API provider for their summarization service.
- Shoutout to the open-source community for their continuous support and contributions.

## Contact

If you have any questions, suggestions, or feedback, feel free to contact me:

- **Email**: sdezerio@gmail.com
- **GitHub**: [SandroSD](https://github.com/SandroSD)
- **LinkedIn**: [Sandro Dezerio](https://www.linkedin.com/in/sandro-dezerio/)
