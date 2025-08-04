
# 🍽️ Food Recipes App

A full-stack web application that allows users to explore, search, and save food recipes. Built using the **MERN stack** (MongoDB, Express.js, React, and Node.js), the app delivers a responsive, dynamic, and user-friendly cooking experience.

---

## 🔧 Features

* 🔍 **Search Recipes** by name, ingredients, or category
* 📋 **View Detailed Recipes** with ingredients, steps, and images
* ❤️ **User Authentication** (Sign up/Login) to save favorite recipes
* 🛒 **Add to Shopping List** from selected recipes
* 🧑‍🍳 **Submit Your Own Recipes**
* 🌐 **Responsive UI** using React and CSS
* 🗃️ **RESTful API** built with Express and Node.js
* 🧾 **MongoDB Database** for storing user data and recipes

---

## 🛠️ Tech Stack

| Frontend | Backend          | Database | Authentication |
| -------- | ---------------- | -------- | -------------- |
| React.js | Node.js, Express | MongoDB  | JWT, bcrypt    |

---

## 📦 Installation

### Prerequisites

* Node.js and npm installed
* MongoDB (local or cloud via Atlas)

### Clone the Repository

```bash
git clone https://github.com/your-username/food-recipes-app.git
cd food-recipes-app
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory and add:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend server:

```bash
npm run dev
```

### Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

The frontend will run on `http://localhost:3000` and connect to the backend on `http://localhost:5000`.

---

## 📁 Project Structure

```
food-recipes-app/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── public/
│
└── README.md
```

---

## 🚀 Future Improvements

* Add comments & ratings for recipes
* Filter by dietary restrictions (e.g., vegan, gluten-free)
* Upload recipe images
* Social login (Google, Facebook)
* Mobile app version (React Native)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and open a pull request.

1. Fork it
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

For any questions or feedback, please contact:
Name  : pranabeshsengupta441@gmail.com
GitHub: https://github.com/PranabeshSengupta

---

