# Parent Project

The parent project combines a Laravel backend and a React frontend into a single project using Docker Compose. This
allows you to run both projects together seamlessly.

## Installation

Please follow the steps below to set up and run the project:

1. Clone the repository:

   ```bash
   git clone https://github.com/ameerdhi7/news-app-aggergator

2. Navigate to the project directory:
    ```shell
    cd parent-project
    ```

3. Build and run the Docker containers using Docker Compose:
   ```shell
    cd parent
   ```
   This will start the containers for the Laravel backend, React frontend, and PostgreSQL database.
4. Access the Laravel backend at http://localhost:9000 and the React frontend at http://localhost.

# Laravel Backend

The Laravel backend project resides in the laravel subfolder. It is built using PHP and provides the server-side logic
and API endpoints for the application.

# React Frontend

The React frontend project resides in the react subfolder. It is built using Node.js and provides the user interface and
client-side interactions for the application.

## Project Idea

News Application The project aims to develop a News Application that provides users with up-to-date news articles from
various sources. The application will offer a user-friendly interface where users can browse through different news
categories, read articles, and stay informed about the latest events and topics of interest. The key features of the
News Application include:

1. **News Categories**: The application will categorize news articles into different sections, such as World News,
   Business, Technology, Sports, Entertainment, and more. Users can easily navigate through these categories to find
   articles that align with their interests.
2. **Article Listings**: The application will display a list of news articles based on the selected category. Each
   article listing will include the article's title, a brief description, the source, the author, and an accompanying
   image.
3. **Search Functionality**: The application will offer a search feature that allows users to search for specific news
   articles by entering relevant keywords. This functionality will enable users to find articles on specific topics or
   events of their interest quickly
4. **User Authentication**: The News Application will incorporate user authentication to provide personalized
   experiences. Registered users can save preferences.
5. **Responsive Design**: The application will be designed to be responsive, ensuring a
   seamless user experience across different devices.