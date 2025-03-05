# GameGlance 🎮  
[Live Website](https://gameglance-18dab.firebaseapp.com/) | [Client-Side Repository](https://github.com/Mustazir/GameGlance-Client.git) | [Server-Side Repository](https://github.com/Mustazir/GameGlance-Server.git)  

## Introduction  
**GameGlance** is a user-friendly game review platform where users can explore, share, and manage game reviews. Designed with simplicity and functionality in mind, it offers a "chill" experience for gaming enthusiasts to interact and share their opinions.  

---

## Features  
- **Dynamic Game Reviews**: View, add, and manage game reviews with features like rating, genres, and descriptions.  
- **Protected Routes**: Secure access to private routes such as "My Reviews" and "Add Review" for logged-in users.  
- **User Authentication**: Log in or register using email-password authentication with additional Google login support.  
- **Game Watchlist**: Save your favorite reviews to a personal watchlist for quick access.  
- **Sort and Filter Reviews**: Sort reviews by rating and year, or filter them by genres for a customized experience.  
- **Unique Design**: A modern, responsive UI with a clean design and dark/light theme toggle.  

---

## Pages Overview  
### **Home Page**  
- A visually appealing **banner slider**.  
- **Highest Rated Games** section displaying top games.  
- Two additional meaningful sections.  

### **Reviews Management**  
- **All Reviews**: Explore reviews with sorting and filtering options.  
- **My Reviews**: View, update, or delete your reviews.  
- **Add Review**: Submit new reviews with a detailed form (protected route).  
- **Update Review**: Edit previously submitted reviews.  

### **Game Watchlist**  
- Manage a personal list of games saved to your watchlist.  

### **Authentication**  
- Login and Register pages with email-password and Google login options.  

### **Other Pages**  
- **404 Page**: Friendly design for unavailable routes.  
- **Loading Spinner**: Shown during data loading.  

---

## Technologies Used  
### **Client-Side**  
- **React.js**: Framework for building a responsive and interactive UI.  
- **Firebase**: Hosting and authentication.  
- **CSS/Frameworks**: For styling and responsiveness.  

### **Server-Side**  
- **Node.js & Express.js**: Backend for handling API requests.  
- **MongoDB**: Database to store reviews and user information.  

### **Additional Packages**  
- **Lottie React**: For animations.  
- **React-simple-typewriter**: Adds dynamic text animations.  
- **React Awesome Reveal**: Smooth animations for elements.  

---

## Environment Variables  
To keep your application secure:  
- **Firebase Config Keys**  
- **MongoDB Credentials**  

These are stored securely in `.env` files and not exposed in the repositories.  

---

## Deployment  
- **Client**: Hosted on Firebase.  
- **Server**: Hosted on Vercel.  

---

## Getting Started  
1. Clone the repositories:  
   ```bash  
   git clone https://github.com/Mustazir/GameGlance.git  
   git clone https://github.com/Mustazir/GameGlance-Server.git  
   ```
2.Install dependencies:
   ```bash
   npm install  
   ```
3.Add .env files with your credentials for Firebase and MongoDB.
4.Run the application
   ```bash
   npm run dev
   ```