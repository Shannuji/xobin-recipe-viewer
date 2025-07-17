# 🍛 Recipe Viewer – Xobin Mini Project

A full-stack Indian recipe viewer built using Next.js, MongoDB, and TheMealDB API.  
Users can view Indian dishes, click ❤️ to add to favorites, and manage them in a separate tab.

## 🚀 Features

* 🧾 Fetch recipes from TheMealDB API  
* 🔍 View detailed recipe info  
* ❤️ Save recipes to MongoDB as favorites  
* 🗑 Remove from favorites  
* 🌙 Dark theme UI with elegant fonts  
* 🔄 Clean responsive layout  

## 📦 Tech Stack

* Frontend: Next.js, Tailwind CSS  
* Backend: API Routes with Mongoose + MongoDB Atlas  
* Database: MongoDB Atlas  
* Deployment: Vercel  

## 📁 Folder Structure

/pages
/api/favorites → API routes for saving, deleting, fetching favorites
/favlist → Favorites page
index.js → Homepage with recipe list

/models
Favorite.js → Mongoose schema

/utils
dbConnect.js → MongoDB connection done.
