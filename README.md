# GitHub ID Finder

A web-based application to fetch and display GitHub user profiles using the GitHub API.

## Features
- **Search by GitHub Username**: Enter a GitHub username to retrieve user profile details.
- **Dark and Light Mode**: Toggle between dark and light themes for a better user experience.
- **Display User Information**:
  - Avatar
  - Full Name
  - Username (with link to GitHub profile)
  - Account creation date
  - Bio
  - Public repositories count
  - Followers and following count
  - Location (if available)
  - Personal website (if available)
  - Twitter handle (if available)
  - Company (if available)

## How It Works
1. User inputs a GitHub username in the search bar.
2. The application fetches data from the GitHub API.
3. If the user exists, the profile details are displayed.
4. If the user does not exist, an error message is shown.

## Technologies Used
- **HTML5**: Markup for the web interface.
- **CSS3**: Styling for the web interface.
- **JavaScript**: Logic to fetch and display GitHub user data.
- **GitHub API**: Data source for user information.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pranavkb007/github-id-finder.git
   ```
2. Navigate to the project directory:
   ```bash
   cd github-id-finder
   ```
3. Open `index.html` in a web browser.

## Usage
- Enter a GitHub username in the search bar and press the **Search** button or hit **Enter**.
- Toggle between dark and light modes using the theme switcher.

## File Structure
- `index.html`: Main HTML file containing the structure of the web page.
- `style.css`: CSS file for styling the web page.
- `script.js`: JavaScript file containing the logic for fetching and displaying data, and for handling theme switching.
- `Images/`: Folder containing icons and images used in the application.
