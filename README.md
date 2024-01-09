# Netflix GPT - AI Movie Recommendations

Netflix GPT is a movie recommendation application enhanced with AI capabilities. This project provides personalized movie suggestions based on user preferences.

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

## Features

- **Home Page (for unauthorized users)**
  - Signin/Signup Page
    - SignInForm / SignUpForm

- **Browse Page**
  - Navbar
  - Showcase
  - Trendings
  - Movies Suggestions
    - Movies List \* N

- **Netflix GPT**
  - Search
  - Movies Suggestions

