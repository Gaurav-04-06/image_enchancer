# React Image Enhancer using PicWish API

A React frontend-only app that enhances images using the PicWish API.  
Upload an image and get an improved/enhanced version without any backend setup.

---

## Features

- Upload images from your device
- Enhance images via PicWish API calls
- View enhanced images instantly
- Simple and clean user interface built with React

---

## Screenshots

![Upload Image](./public/screenShots/image.png)

---

## Live Demo

[Add your live demo URL here after deployment]

---

## Getting Started

### Prerequisites

- Node.js and npm installed
- PicWish API key (sign up at [PicWish](https://picwish.com) and get your API key)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Gaurav-04-06/image_enchancer.git
   cd image_enchancer
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Add your PicWish API key:

   If you use environment variables, create a `.env` file in the root:

   ```ini
   VITE_APP_PICWISH_API_KEY=your_api_key_here
   ```

   Or replace the placeholder in the code directly (not recommended for security reasons).

### Running the App Locally

```bash
npm start
```

Open http://localhost:5173 to view it in the browser.

---

## How to Use

- Click the file input to upload an image.
- Click the Enhance Image button.
- Wait for the image to be processed.
- See the enhanced image.

## Notes

- Your PicWish API key is exposed in frontend apps — use with caution.
- For production apps, consider proxying API requests via a backend for better security.
- Check PicWish API docs for request limits and pricing.
