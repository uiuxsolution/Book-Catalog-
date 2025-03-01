# Book Catalog

A modern, responsive web application for browsing and exploring books. Built with React and Vite, featuring a clean and intuitive user interface.

## Features

- **Book Grid Display**: Browse books in a responsive grid layout
- **Detailed Book Views**: View comprehensive information about each book
- **Search Functionality**: Search through the book catalog
- **Amazon Integration**: Direct links to purchase books on Amazon
- **Responsive Design**: Optimized for both desktop and mobile devices

## Technology Stack

- React 18
- React Router DOM 7
- Vite
- CSS3 with modern features (Grid, Flexbox, Gradients)
- Faker.js for demo data

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run start
   ```
4. Open http://localhost:5173 in your browser

## Project Structure

```
/src
  /components
    - BookDetail.jsx    # Individual book view component
    - BookGrid.jsx      # Grid display of books
    - SearchBar.jsx     # Search functionality
  - App.jsx            # Main application component
  - main.jsx          # Application entry point
```

## Features in Detail

### Book Grid
- Responsive grid layout
- Book cover images with fallback
- Quick view of title, author, and price
- Smooth hover animations

### Book Details
- High-resolution book cover display
- Comprehensive book information
- Author biography
- Direct Amazon purchase links
- Responsive layout for all devices

## Development

- `npm run start` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## License

This project is licensed under the MIT License.