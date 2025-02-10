# Restaurants app

## **Objective**

Develop a **Restaurant application** using React Native that allows users to view, add, edit, and delete restaurants. 

To save time; the app should interact with a simple backend API that we provide to you to manage restaurant data:

API Base Endpoint:
https://technical-review-api-tailor.netlify.app/

Repository (reference):
https://github.com/TailorHub-Mad/technical_review_api

## Design

Use this Figma link to get the design of the app:
https://www.figma.com/design/LuwjRZZb3ms0MeAmu7gZch/Tailor-Prueba-t%C3%A9cnica-Junior?node-id=1235-1831&t=QBe1sh3ejkqnEot3-1

## **Requirements**

1. **Restaurant List**
    - Display a list of all restaurants fetched from your API.
    - Each list item should show basic information like the restaurant's name and cuisine type.
2. **Restaurant Details**
    - When a restaurant is selected from the list, navigate to a detail view displaying more information about the restaurant, such as its address, contact details, and a brief description.
3. **CRUD Operation**
    - Implement functionality to add a new restaurant.
    - Allow editing of existing restaurant details.
    - Enable deletion of a restaurant.
4. **User Authentication**
    - Implement user authentication in the app.
    - Allow users to log in and manage their favorite restaurants.
    - Save the session token in the  `AsyncStorage` so the user is not prompted to be logged in every time
5. **Favorites Feature**
    - Enable users to add or remove restaurants from their favorites list.
    - Provide a separate view to display the user's favorite restaurants.
6. **Loading State**
    - Display a loading indicator while fetching data from the API.
7. **Error Handling**
    - Show appropriate error messages for network issues or failed API requests.
8. **Design**
    - Ensure the app is responsive, visually appealing and user-friendly for both iOS and Android users.
9. **Navigation**
    - Use react-navigation for navigation between tabs and screens.
    - Use a Drawer with different tabs
    - Use two different navigation stacks:
    - Auth (Login / Register)
    - Rest of screens
        - Map & Restaurant list
        - Restaurant detail page
        - Create restaurant

# Bonus Points

- **Testing**
    - Write realistic unit tests for the frontend components.
    - Write end-to-end tests with Detox
- **Improvements**
    - You can leave a suggestion of improvements you would implement to this app if it was an ongoing project with more development time allowed
- **Deployments / Distribution**
    - If you've deployed and built the app, specifically for Android since iOS will require a paid Apple Developer account, provide the links in the `README.md`.

# **Submission Guidelines**

- Push your code to a public GitHub repository.
- Include a `README.md` file with instructions on how to run the app.
- If you've deployed the app, provide the deployment links in the `README.md`.