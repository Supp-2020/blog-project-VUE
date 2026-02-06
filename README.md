# SwiftPost ✍️  
*A Real-Time Blogging Platform*

SwiftPost allows users to create blog posts with a **title, description, rich-text body**, auto-generated cover images, tags, and sections. Once published, blogs instantly appear on the landing page and are neatly organized based on their assigned sections.

Each blog has a **dedicated details page** for full reading, while a powerful **dashboard** enables complete blog management with pagination, filters, edit, and delete capabilities.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```
---

## ✨ Key Features

### 📝 Real-Time Blog Creation
- Create blogs with:
  - Title
  - Short description
  - Rich Text Editor body
- Content is rendered **exactly as written**, preserving formatting, styles, and structure—just like writing blogs in real time.

### 🖼️ Dynamic Cover Images
- Each blog automatically gets a **random high-quality image from Picsum**.
- No manual image uploads required.
- Keeps every blog visually engaging.

### 🏷️ Tags & Sections
- Assign **multiple tags** for better categorisation.
- Select a **section** (e.g., Tech, Lifestyle, Travel).
- Blogs are automatically pushed and displayed under their respective section areas on the landing page.

### 🏠 Landing Page
- Displays all published blogs in a clean, structured layout.
- Section-based grouping for easy discovery.
- Clicking a blog redirects to its **details page**.

### 📄 Blog Details Page
- Dedicated page for each blog post.
- Displays:
  - Full rich-text content
  - Cover image
  - Tags and related metadata
- Optimized for readability across devices.

### 📊 Admin Dashboard
- Centralized dashboard to manage all blogs.
- Includes:
  - Paginated blog listing
  - Multiple filters (by section, tags, etc.)
  - Edit existing blogs
  - Update content seamlessly
  - Delete blogs when required
