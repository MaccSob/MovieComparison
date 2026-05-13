# 🎬 MovieComparison

> A dynamic web application that allows users to search for two movies simultaneously and compares their key statistics, such as Box Office, release year, budget etc.

## 📌 About The Project
MovieComparison is an interactive web tool built to solve the ultimate dilemma of deciding what to watch. By utilizing the OMDb API, the app retrieves complex movie data on-the-fly and applies comparative logic to highlight which film ranks higher in specific categories. This project showcases proficiency in DOM manipulation, asynchronous programming, and data rendering without external framework overhead.

## 🛠️ Tech Stack
*   **Frontend:** HTML5, CSS3, JavaScript (ES6+)
*   **API Integration:** Axios / Fetch API (Interacting with the external OMDb API)
*   **Styling:** Modern CSS (Flexbox, CSS Grid, Responsive Web Design)

## 🌟 Key Features
*   🔍 **Dual Search Engine:** Independent autocomplete search inputs for two different movies.
*   📊 **Side-by-Side Comparison:** Direct data mapping for parameters like Box Office earnings, Metascore, IMDb Rating, Awards, and Votes.
*   🎨 **Visual Hierarchy & Indicators:** Smart UI highlights (e.g., changing background color or icons) that immediately reveal which movie won in a specific statistical category.
*   📱 **Responsive Layout:** Clean, readable presentation of data comparisons on mobile devices as well as desktop screens.
*   🛡️ **Debounced Input Handling:** Implemented a custom debounce function to optimize API request frequency while the user is typing.
*   
## 📈 Key Learnings & Engineering Challenges
*   **Data Parsing and Normalization:** Overcame the challenge of comparing raw text statistics (e.g., converting `$200,000,000` string into an integer) to execute accurate greater-than/less-than logic.
*   **Debouncing Requests:** Learned how to implement a debouncer mechanism to limit the amount of network requests, protecting the application from hitting free API tier rate limits.
*   **Complex DOM Manipulation:** Managed dynamic element rendering where the component structure changes heavily based on the user's search state and API payload availability.
