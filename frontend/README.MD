# Frontend Development Guidelines

## React-based Structure
As per the challenge requirements, use React for the frontend. You can set up your project using Create React App or any other React boilerplate of your choice.

## Key Components to Implement

1. **User Authentication**
   - Implement registration and login forms

2. **GPU Listings**
   - Create a page to display all available GPU listings
   - Implement a form for users to create new listings
   - Allow users to edit or delete their own listings

3. **Bidding System**
   - Create a component for placing bids on listings
   - Implement a basic dashboard for users to manage their bids and listings and see latest prices

4. **State Management**
   - Choose a state management solution (e.g., Redux, Context API, MobX)
   - Manage application state, including user authentication and data fetching

5. **API Integration**
   - Create services to interact with your backend API
   - Handle API requests and responses

6. **Routing**
   - Implement client-side routing using React Router

7. **UI/UX**
   - Create a responsive design
   - Implement basic styling (you can use CSS, SASS, or a UI library like Material-UI)

## Folder Structure
Organize your code logically. A common structure might include:
- `components/`: Reusable React components
- `pages/`: Components that represent entire pages
- `services/`: API call functions
- `styles/`: CSS or styling files
- `utils/`: Utility functions
- `context/`: If using React Context for state management

## Best Practices
- Use functional components and hooks
- Implement proper error handling and loading states
- Write clean, modular, and reusable code
- Consider implementing basic accessibility features

Remember, the goal is to create a functional and user-friendly interface for the GPU marketplace. Focus on implementing the core features effectively within the given time frame.