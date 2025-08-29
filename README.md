# 🎬 React Movie Filter App

A simple React application that displays a list of movies in a table and allows users to filter them by **genre** using filter buttons.  

This project demonstrates **React props**, **component composition**, and **array mapping** with a clean UI inspired by the given design reference.  

---

## 🚀 Features

- Displays movies in a responsive table with **Title, Genre, and Year** columns.  
- Filter movies by clicking on genre buttons.  
- Logs the selected genre to the console on button click.  
- Uses **array mapping** to dynamically render movies and genres.  
- Clean and consistent UI with smooth transitions.  

---

## 🛠️ Tech Stack

- **React** (CRA or Vite)  
- **CSS / TailwindCSS** for styling (optional depending on your implementation) 

---

## 📜 Code Overview

### 1. Movies Array
javascript
const movies = [
  { title: 'The Shawshank Redemption', genre: 'Drama', year: 1994 },
  { title: 'The Godfather', genre: 'Crime', year: 1972 },
  { title: 'The Dark Knight', genre: 'Action', year: 2008 },
  { title: '12 Angry Men', genre: 'Drama', year: 1957 },
  { title: "Schindler's List", genre: 'Drama', year: 1993 },
  { title: 'The Lord of the Rings: The Return of the King', genre: 'Fantasy', year: 2003 },
  { title: 'The Good, the Bad and the Ugly', genre: 'Western', year: 1966 },
  { title: 'Forrest Gump', genre: 'Drama', year: 1994 },
  { title: 'Inception', genre: 'Science Fiction', year: 2010 },
  { title: 'The Matrix', genre: 'Science Fiction', year: 1999 },
  { title: 'The Silence of the Lambs', genre: 'Thriller', year: 1991 },
  { title: 'Saving Private Ryan', genre: 'War', year: 1998 },
  { title: 'Jurassic Park', genre: 'Science Fiction', year: 1993 },
  { title: 'Terminator 2: Judgment Day', genre: 'Science Fiction', year: 1991 },
  { title: 'The Lion King', genre: 'Animation', year: 1994 }
];

###2. Genres Array
const genres = [
  "Drama",
  "Crime",
  "Action",
  "Fantasy",
  "Western",
  "Science Fiction",
  "Thriller",
  "War",
  "Animation"
];

3. Passing Props

App.js → Passes movies to MovieList and genres to GenreFilter.

MovieList.js → Maps movies into table rows.

GenreFilter.js → Maps genres into filter buttons.

✅ Evaluation 

MovieList Component: Displays a table with correct mapping.

GenreFilter Component: Displays buttons and logs selected genre.

Passing Arrays as Props: Correctly implemented.

UI Consistency: Matches design reference with animations.

Deployment: Successfully hosted on Netlify/Vercel/GitHub Pages.


👨‍💻 Author

Saurabh Khedkar 
Full Stack Web Developer | Pune, MH, India 
📧 saurabhrkhedkar1707@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/saurabh-khedkar)  
🐙 [GitHub](https://github.com/khedkar2001)  
