# My Weather App

A weather application built with Next.js that provides the current weather and a 5-day weather forecast for any location. The app fetches data from the OpenWeatherMap API and displays it in a user-friendly interface.

## Features

- Current weather conditions
- 5-day weather forecast
- Responsive design
- Dynamic location search

## Demo

You can check out the live demo of the app [https://my-weather-app-two-dun.vercel.app/](https://my-weather-app-two-dun.vercel.app/).

## Screenshots

Screenshot-1
![Screenshot (387)](https://github.com/himansu-1/my-weather-app/assets/118210276/18017c6d-03ef-4c57-807c-d26b1ed1a796)

Screenshot-2
![Screenshot (388)](https://github.com/himansu-1/my-weather-app/assets/118210276/27d3a5c6-1a4a-41d9-a476-d396facdab76)

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env.local` file in the root directory and add your OpenWeatherMap API key:

    ```env
    NEXT_PUBLIC_WEATHER_KEY=your_openweathermap_api_key
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

- Enter the name of a city in the search bar to get the current weather and a 5-day forecast.
- The app will display weather information including temperature, humidity, wind speed, and weather conditions.

## Technologies/Dependencies Used

- Next.js
- React
- Tailwind CSS
- Axios
- OpenWeatherMap API
- react-icons
- react-query
- tailwind-merge
- jotai
- date-fns
- clsx

## Project Structure
.eslintrc.json
.gitattributes
.gitignore
README.md
next.config.js
package-lock.json
package.json
postcss.config.js
tailwind.config.ts
tsconfig.json

weather-app/
├── public/
│ ├── next.svg
| ├── verce.svg
├── src/
│ ├── app/
│ │ ├── atom.ts
│ │ └── favicon.ico
│ │ └── globals.css
│ │ └── layout.tsx
│ │ └── page.tsx
│ ├── components/
│ │ ├── Container.tsx
│ │ └── ForecastWeatherDetail.tsx
│ │ └── Navbar.tsx
│ │ └── SearchBox.tsx
│ │ └── WeatherDetails.tsx
│ │ └── WeatherIcon.tsx
│ ├── utils/
│ │ ├── cn.ts
│ │ └── convertKelvinToCelsius.ts
│ │ └── convertWindSpeed.tsx
│ │ └── getDayOrNightIcon.ts
│ │ └── metersToKilometers.ts
├── .env.local
├── .eslintrc.json
├── .gitattributes
├── .gitignore
├── README.md
├── next.config.js
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.json
