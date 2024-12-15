# React Redux Router App

This project is a React application that uses **React Router** for navigation and **Redux** for state management. It fetches data from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/posts) and displays a list of posts. The app includes a home page where users can view the list of posts and a detail page for each post that displays more information.

## Features

- **Home Page**: Displays a list of posts fetched from the API. Each post is clickable and leads to the post's detail page.
- **Detail Page**: Displays detailed information for each post, including the post's title, body, and the ID of the user who created the post.
- **Responsive Design**: The application is designed to be responsive and works well on both desktop and mobile devices.
- **Loading State Management**: A loading indicator is shown while data is being fetched from the API.

## Technologies Used

- **React**: For building the user interface.
- **React Router**: For handling routing and navigation within the app.
- **Redux**: For state management.
- **Redux Thunk**: For asynchronous data fetching.
- **CSS**: For styling the app and making it responsive.

## Installation

Follow these steps to get the project up and running on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/React-SM.git

## Features and Functionality
## Step 1: Set Up React Router
- Home Page Route (/): Displays a list of items fetched from the API.
- Detail Page Route (/item/:id): Displays information about a single item based on the provided ID.
## Step 2: Set Up Redux
- Redux Store: A Redux store is set up to manage the state of the app.
- Redux Slice: A slice is created to handle the fetched data.
- API Data Fetching: The app fetches data from the JSONPlaceholder API using Redux Thunk.
## Step 3: Create Components
- Home Page Component: Displays a list of post titles with a limited description. Each item is clickable and links to the detail page.
- Detail Page Component: Fetches and displays details of a single post, including the title, body, and the ID of the user who created the post.
## Step 4: Add Styling
- The app is styled based on a provided Figma design.
- It is made responsive, ensuring a smooth user experience across different devices.
## Step 5: Manage Loading State
- Redux is used to manage the loading state while the data is being fetched.
- A loading indicator is shown until the posts are successfully retrieved.
## API Data
- The app fetches data from the JSONPlaceholder API with the following properties for each post:

- userId: The ID of the user who created the post.
- id: The ID of the post.
- title: The title of the post.
- body: The body (content) of the post.

For each post, an image is also fetched from https://picsum.photos/200?random=${post.id}, where ${post.id} corresponds to the ID of the post
