# BlinkNews - Real-Time News Application

BlinkNews is a modern, responsive web application designed to keep you updated with the latest news from around the world. Built using React and powered by NewsAPI, this app fetches real-time headlines across various categories like Technology, Business, Health, Sports, and Entertainment. The application is simple, intuitive, and efficient, offering an easy-to-navigate interface with the latest news at your fingertips.

## **Key Features**

- **Real-Time News Fetching**: The app pulls the latest news headlines from various trusted news sources using the **NewsAPI**.
- **Category-Based News**: Allows users to explore news based on specific categories such as Technology, Business, Health, Sports, and Entertainment.
- **Fully Responsive**: The app is responsive, ensuring a smooth experience across all devices.
- **Modern UI**: The application has a clean and modern interface, powered by **Bootstrap** for easy navigation and user interaction.
- **Fast Development**: The app is developed using **Vite**, ensuring fast build times and a streamlined development process.

## **Screenshots**

<img width="947" alt="image" src="https://github.com/user-attachments/assets/6aedf0b7-a1a2-4b89-8779-9891e04d94ca" />
<img width="937" alt="image" src="https://github.com/user-attachments/assets/4a244600-8879-45a0-b734-6bb701db70a4" />
<img width="945" alt="image" src="https://github.com/user-attachments/assets/4090518c-03a8-4608-9a1a-a17b344910a5" />

## **How to Run the Application Locally**

### **1. Clone the Repository**

Start by cloning the project to your local machine:

```bash
git clone https://github.com/Nischal0904/BlinkNews-News-app.git


2. Navigate to the Project Directory
cd BlinkNews-News-app

3. Install Dependencies

Install the necessary dependencies by running:
npm install

4. Configure Environment Variables

Create a .env file in the root of your project and add your NewsAPI key:
VITE_API_KEY=your_news_api_key_here

You can obtain your NewsAPI key by signing up at NewsAPI.

Note: Make sure that the .env file is added to .gitignore to keep your API key secure and prevent it from being pushed to version control.

5. Run the Development Server
To start the app in development mode, run:
npm run dev

By default, the app will be available at http://localhost:5173/.

Tech Stack
Frontend: React.js, Vite, Bootstrap

API: NewsAPI

Deployment: Vercel

Version Control: Git, GitHub

Environment Variables
Ensure that you set the following environment variable in your Vercel dashboard or .env file:

VITE_API_KEY: Your personal API key from NewsAPI.

How It Works
News Fetching: The app fetches top headlines from a specified category (e.g., Technology, Health) using the NewsAPI.

Dynamic Content: As you switch categories through the navigation bar, the displayed news updates in real-time, showcasing the latest articles from that category.

Modular Design: The UI is built in a modular way, using reusable components like Navbar, NewsBoard, and NewsItem.

Contributing
We welcome contributions to improve BlinkNews! If you’d like to contribute:

Fork the repository

Create a new branch for your feature or bugfix

Make your changes and ensure everything works correctly

Submit a pull request with a clear description of your changes

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
NewsAPI: For providing a comprehensive and easy-to-use news data API.

React: For the powerful and flexible UI framework.

Vite: For providing a fast and efficient development environment.

Bootstrap: For the responsive, mobile-first design components.

Conclusion
BlinkNews is designed to be a straightforward, yet powerful news application that can serve as a foundation for more advanced features. Whether you're interested in adding new categories, implementing advanced filtering, or enhancing the user interface, this project is built to scale and evolve.

