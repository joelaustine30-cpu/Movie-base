# 🎬 CINEMAX - Movie Discovery Platform

A modern, responsive movie discovery website built with HTML, CSS, and JavaScript. Browse movies, search for your favorites, and discover upcoming releases.

## 🌟 Features

- **Modern UI Design** - Dark theme inspired by popular streaming platforms
- **Movie Grid Layout** - Responsive grid display of featured movies
- **Search Functionality** - Filter movies by title in real-time
- **Movie Details** - Detailed information about selected movies including director, genre, and ratings
- **Star Ratings** - Visual star ratings for each movie
- **Mobile Responsive** - Fully optimized for mobile, tablet, and desktop devices
- **Smooth Scrolling** - Smooth navigation between sections
- **Hover Effects** - Interactive hover animations for better UX

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Responsive design with flexbox and grid
- **JavaScript (Vanilla)** - DOM manipulation and search functionality
- **Placeholder Images** - Via Placeholder.com

## 📁 Project Structure

```
Movie-base/
├── Index.html          # Main HTML file
├── style.css           # External CSS styles
├── README.md           # This file
└── file_*.png          # Repository assets (screenshots/branding)
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/joelaustine30-cpu/Movie-base.git
   cd Movie-base
   ```

2. **Open in browser**
   - Simply open `Index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx http-server
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (or your server's address)

## 🎨 Features Guide

### Navigation
- Fixed sticky navigation bar
- Quick links to Home, Movies, and About sections

### Hero Section
- Eye-catching banner with call-to-action buttons
- Smooth gradient background

### Movie Gallery
- Grid layout with automatic column adjustment
- Movie cards with hover lift effect
- Rating system using stars

### Search
- Real-time movie search by title
- Case-insensitive matching
- "No results" message for empty searches

### Movie Details
- Dedicated section with full movie information
- Director, genre, and release information
- Call-to-action buttons

### About Section
- Platform description
- Feature highlights

## 📱 Responsive Breakpoints

- **Desktop**: Full grid layout with 220px minimum column width
- **Tablet**: Adjusted spacing and font sizes
- **Mobile** (< 700px): 
  - Stacked navigation
  - Larger touch targets
  - Optimized text sizes

## 🔧 Customization

### Change Colors
Edit the color scheme in `Index.html` `<style>` section or `style.css`:
- Primary brand color: `#e50914` (red)
- Background: `#080808` (near black)
- Text: `white` / `#ccc`

### Add Movies
Add new movie cards in the `.movies` section following the existing structure:
```html
<div class="movie">
    <div class="poster">
        <img src="your-image-url.jpg" alt="Movie Title">
    </div>
    <div class="movie-info">
        <h3>Movie Title</h3>
        <div class="rating">★★★★☆</div>
        <p>Genre • Category • Year</p>
        <a href="#" class="button">More Info</a>
    </div>
</div>
```

### Add Images
Replace placeholder images with your own:
1. Host images online or in an `images/` folder
2. Update `src` attributes in `<img>` tags

## ⚠️ Important Notes

- Currently uses placeholder images from Placeholder.com
- To use real images, host them on a web server or use a CDN
- Search functionality works with existing movie titles
- No backend/database - static data only

## 🌐 Deployment

### Deploy on Vercel (Recommended)
```bash
npm install -g vercel
vercel login
vercel
```

### Deploy on GitHub Pages
1. Push to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://username.github.io/Movie-base`

### Deploy on Netlify
1. Connect your GitHub repo to Netlify
2. Set build command: (leave empty for static site)
3. Set publish directory: `/`

## 📞 Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Contact: Joel Austine

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- **Developer**: Joel Austine
- **Design Inspiration**: Popular streaming platforms
- **Placeholder Images**: Placeholder.com

---

**Status**: ✅ Ready for deployment
**Last Updated**: August 2026
