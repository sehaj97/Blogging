# ResearchHub

Welcome to **ResearchHub**, your ultimate blog platform for sharing and exploring knowledge across diverse topics such as yoga, mindset, self-help, leadership and more. This repository contains a dynamic, responsive, and modern blog application built with **Jekyll** and enhanced with **Bootstrap** and **JavaScript** for client-side filtering and interactivity.

---

## 🚀 Features

- **Dynamic Blog Posts**: Easily add blog posts using Markdown files in the `_posts` directory.
- **Responsive Design**: Fully responsive layout using **Bootstrap 5**, optimized for all devices.
- **Category Filtering**: Filter posts dynamically by categories with interactive buttons.
- **Client-Side Pagination**: Paginate posts without relying on plugins using **JavaScript**.
- **Modern UI**: Clean, gradient-based card designs with hover effects and dynamic styling.
- **Easy Deployment**: Deploy seamlessly to **GitHub Pages**.

---

## 📂 Folder Structure

```
.
├── _layouts/               # Layout templates for your site
│   ├── default.html        # Default layout template
│   ├── home.html           # Home page layout template
├── _posts/                 # Markdown files for blog posts
│   ├── 2025-01-01-example.md  # Example post
├── _config.yml             # Jekyll configuration file
├── index.md                # Home page content
├── README.md               # Documentation (this file)
```

---

## 🛠️ Installation

Follow these steps to run ResearchHub locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sehaj97/researchhub.git
   cd researchhub
   ```

2. **Install Jekyll**:
   Ensure you have Ruby and Bundler installed. Then, install Jekyll:
   ```bash
   gem install bundler jekyll
   ```

3. **Install Dependencies**:
   Install all required dependencies with Bundler:
   ```bash
   bundle install
   ```

4. **Run the Development Server**:
   Start the Jekyll server locally:
   ```bash
   bundle exec jekyll serve
   ```

5. **Access the Blog**:
   Open your browser and go to: `http://localhost:4000`

---

## ✨ How to Add a Blog Post

1. Navigate to the `_posts` directory.
2. Create a new file with the naming convention: `YYYY-MM-DD-title.md`.
3. Add the following front matter to the file:

   ```yaml
   ---
   layout: post
   title: "Your Blog Post Title"
   date: 2025-01-01
   categories: [yoga, mindset]
   ---
   ```

4. Write your content in Markdown below the front matter.

---

## 🎨 Customization

### **1. Adding Categories and Colors**
To add new categories with custom colors:
- Update the `category_color_map` in `_config.yml`:

  ```yaml
  category_color_map:
    yoga: "#28a745"
    leadership: "#007bff"
    mindset: "#ffc107"
    self-help: "#fd7e14"
    default: "#6c757d"
  ```


## 🌐 Deployment

### Deploying to GitHub Pages:
1. Push your changes to the `main` branch (or your preferred branch).
2. Go to **Settings** → **Pages** in your repository.
3. Set the source branch to `main` and the folder to `/ (root)`.
4. Your blog will be live at `https://<your-username>.github.io/researchhub`.

---



## 🤝 Contributing

We welcome contributions to improve ResearchHub! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- UI powered by [Bootstrap 5](https://getbootstrap.com/)
- Dynamic interactivity using vanilla JavaScript

---
