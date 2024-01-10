# Netflix GPT - AI Movie Recommendations

Netflix GPT is an innovative movie recommendation application that harnesses the power of Artificial Intelligence (AI) to provide users with personalized and intelligent movie suggestions. This project seamlessly integrates with popular technologies, offering a user-friendly and engaging experience for movie enthusiasts.

## Key Features

**AI-driven Movie Recommendations:** Utilizing advanced AI algorithms, Netflix GPT analyzes user preferences and viewing history to deliver tailored movie recommendations. Enhance your movie-watching experience with suggestions that match your tastes.

**Interactive User Interface:** The application boasts an intuitive and interactive user interface designed for both ease of use and visual appeal. Navigate through various sections effortlessly, from the homepage to the browsing and search functionalities.

**Tailwind CSS Integration:** Netflix GPT is built upon React, with Tailwind CSS providing a responsive and visually appealing design. Tailwind CSS streamlines the styling process, ensuring a polished and professional look for the entire application.

**Authentication System:** Access exclusive features with a secure user authentication system. The home page dynamically adjusts based on user authorization, offering a seamless experience for both guests and registered users.

**Comprehensive Browsing Experience:** Explore an extensive collection of movies through the Browse Page, featuring a curated showcase, trending movies, and personalized suggestions. The Movies GPT section further enhances the browsing experience with dynamic movie lists.

## Tech Stack

- **React:** Frontend framework for building user interfaces.
- **Firebase:** Authentication and hosting platform.
- **OpenAI:** Movie recommendation engine.
- **TMDB:** Movie database for fetching movie details.

## Setup

1. Install the React app using create-react-app (CRA):

    ```bash
    npx create-react-app netflix-gpt
    ```

2. Create a `.env` file and configure it with your application base URL, OpenAI API key, and TMDB API key:

    ```env
    REACT_APP_BASE_URL = YOUR_APPLICATION_BASE_URL; // http://localhost:3000
    REACT_APP_OPENAI_KEY = YOUR_API_KEY_WILL_HERE;
    REACT_APP_TMDB_KEY = YOUR_API_KEY_WILL_HERE;
    ```

3. Install and initialize Tailwind CSS:

    ```bash
    npm install -D tailwindcss
    npx tailwindcss init
    ```

4. Configure Tailwind CSS in your project by updating `tailwind.config.js`:

    ```js
    module.exports = {
      content: ["./src/**/*.{js,jsx,ts,tsx}"],
      theme: {
        extend: {},
      },
      plugins: [],
    };
    ```

5. Add the Tailwind CSS directives to your `./src/index.css` file:

    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

6. Start your local development server:

    ```bash
    npm start
    ```
