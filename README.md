# 🎬 Prime Flix - Movie Discovery App

[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Axios](https://img.shields.io/badge/Axios-1.9.0-5A29E4?style=for-the-badge&logo=axios&logoColor=white)](https://axios-http.com/)
[![React Router](https://img.shields.io/badge/React_Router-7.6.2-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/)
[![TMDB API](https://img.shields.io/badge/TMDB-API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)](https://www.themoviedb.org/)

A modern and responsive movie discovery application built with React 19, featuring real-time movie data from The Movie Database (TMDB) API. Users can explore the latest movies in theaters, save favorites, and watch trailers seamlessly.

## 🚀 Features

### Core Functionality
- **Latest Movies Display**: Shows the top 10 most recent movies currently in theaters
- **Movie Details**: Comprehensive movie information including synopsis, ratings, and high-quality images
- **Favorites System**: Save and manage favorite movies with persistent local storage
- **Trailer Integration**: Direct YouTube links to movie trailers
- **Responsive Design**: Optimized for desktop and mobile devices
- **Error Handling**: Graceful error pages and user feedback with toast notifications

### User Experience
- **Fast Loading**: Efficient API calls with loading states
- **Intuitive Navigation**: Clean header with easy access to favorites
- **Visual Feedback**: Toast notifications for user actions
- **Clean UI**: Modern design with hover effects and smooth transitions

## 🛠️ Technologies Used

### Frontend
- **React 19.1.0** - Latest React with modern hooks and features
- **React Router DOM 7.6.2** - Client-side routing and navigation
- **Axios 1.9.0** - HTTP client for API requests
- **React Toastify 11.0.5** - Toast notifications for user feedback

### Styling
- **Custom CSS** - Responsive design with flexbox layouts
- **Modern UI Components** - Clean and professional interface

### API Integration
- **The Movie Database (TMDB) API** - Real-time movie data
- **Image Optimization** - High-quality movie posters and backdrops

## 📁 Project Structure

```
src/
├── components/
│   └── Header/
│       ├── index.js          # Navigation header component
│       └── header.css        # Header styling
├── pages/
│   ├── Home/
│   │   ├── index.js          # Main page with movie listings
│   │   └── home.css          # Home page styling
│   ├── Filmes/
│   │   ├── index.js          # Movie details page
│   │   └── filme-info.css    # Movie details styling
│   ├── Favoritos/
│   │   ├── index.js          # Favorites management page
│   │   └── favoritos.css     # Favorites page styling
│   └── Erro/
│       ├── index.js          # 404 error page
│       └── erro.css          # Error page styling
├── services/
│   └── api.js                # Axios configuration for TMDB API
├── routes.js                 # Application routing configuration
├── App.js                    # Main application component
├── index.js                  # Application entry point
└── index.css                 # Global styles
```

## 🎯 Key Components

### Home Page (`/`)
- Fetches and displays the latest 10 movies from TMDB
- Shows movie posters, titles, and access links
- Implements loading states for better UX

### Movie Details (`/filme/:id`)
- Detailed movie information with high-quality backdrop images
- Movie synopsis, ratings, and metadata
- Save to favorites functionality
- Direct trailer links to YouTube

### Favorites (`/favoritos`)
- Persistent favorite movies using localStorage
- Add/remove functionality with instant feedback
- Links back to movie details

### Header Component
- Consistent navigation across all pages
- Prime Flix branding
- Quick access to favorites

## 🔧 Installation & Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/movieapp.git
   cd movieapp
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production
```bash
npm run build
```

## 🌐 API Integration

This application integrates with The Movie Database (TMDB) API:

- **Base URL**: `https://api.themoviedb.org/3/`
- **Endpoints Used**:
  - `/movie/now_playing` - Latest movies in theaters
  - `/movie/{id}` - Specific movie details
- **Features**: Automatic Portuguese (Brazil) localization
- **Image CDN**: High-quality movie images via TMDB's image service

## 💾 Data Persistence

- **Local Storage**: Favorite movies are stored locally using `@primeflix` key
- **Data Structure**: JSON array of complete movie objects
- **Persistence**: Favorites survive browser sessions and page refreshes

## 🎨 Design Highlights

- **Color Scheme**: Professional brown and black theme
- **Typography**: Clean sans-serif fonts
- **Layout**: Centered, responsive design with maximum 1000px width
- **Interactive Elements**: Hover effects and smooth transitions
- **Mobile-First**: Responsive design for all screen sizes

## 🚀 Performance Features

- **Optimized Rendering**: Efficient React hooks usage
- **Image Optimization**: Responsive images with proper sizing
- **Code Splitting**: Component-based architecture
- **Lazy Loading**: Efficient API calls only when needed

## 🔮 Future Enhancements

- Movie search functionality
- User authentication and cloud sync
- Movie ratings and reviews
- Advanced filtering options
- Watchlist categories
- Social sharing features

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS/Android)

## 🤝 Contributing

This project is part of my portfolio, but suggestions and feedback are welcome! Feel free to:

1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 About the Developer

**Cristóvão Junior** - Frontend Developer

This project demonstrates proficiency in:
- **Modern React Development** (React 19, Hooks, Router)
- **API Integration** (REST APIs, Axios, Error Handling)
- **State Management** (useState, useEffect, Local Storage)
- **Responsive Web Design** (CSS Flexbox, Mobile-First)
- **User Experience** (Loading States, Notifications, Navigation)

---

**📧 Contact**: cristovao.b.jr@gmail.com | **💼 LinkedIn**: [linkedin.com/in/cristóvão-borges-junior-53880a226](https://linkedin.com/in/cristóvão-borges-junior-53880a226)

> Built with ❤️ by Cristóvão Junior using React 19 and The Movie Database API