
# Hengrui Zhang's Academic Website

![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fhengruizzzz.github.io)
![GitHub last commit](https://img.shields.io/github/last-commit/HENGRUIZZZZ/HENGRUIZZZZ.github.io)
![GitHub repo size](https://img.shields.io/github/repo-size/HENGRUIZZZZ/HENGRUIZZZZ.github.io)

Welcome to the source code repository for my personal academic website! This site showcases my research, publications, and academic journey as a PhD student at University College London.

🌐 **Live Website**: [https://hengruizzzz.github.io](https://hengruizzzz.github.io)

## 📖 About This Website

This is my personal academic website built with Jekyll and hosted on GitHub Pages. The site includes:

- **About Me**: Research interests and academic background
- **Publications**: List of my research papers and publications
- **CV**: Comprehensive curriculum vitae
- **Blog Posts**: Thoughts and insights on my research and academic life

## 🛠️ Built With

- **Jekyll**: Static site generator
- **Academic Pages Theme**: Based on the Minimal Mistakes theme
- **GitHub Pages**: Free hosting and automatic deployment
- **Markdown**: Content writing and formatting

## 🚀 Quick Start

### Prerequisites
- Git
- Ruby (version 2.7 or higher)
- Bundler gem

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/HENGRUIZZZZ/HENGRUIZZZZ.github.io.git
   cd HENGRUIZZZZ.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install --path vendor/bundle
   ```

3. **Run the site locally**
   ```bash
   bundle exec jekyll serve --host localhost --port 4000
   ```

4. **View the site**
   Open your browser and navigate to `http://localhost:4000`

### Alternative: Using Docker

If you prefer using Docker to avoid Ruby setup issues:

```bash
docker run --rm -it -p 4000:4000 -v $(pwd):/srv/jekyll jekyll/jekyll:latest jekyll serve --host 0.0.0.0
```

## 📁 Repository Structure

```
├── _config.yml          # Site configuration
├── _data/
│   └── navigation.yml   # Navigation menu
├── _includes/           # Reusable HTML components
├── _layouts/            # Page templates
├── _pages/              # Main pages (About, CV, etc.)
├── _posts/              # Blog posts
├── _publications/       # Research publications
├── _sass/               # Styling files
├── assets/              # CSS, JS, and other assets
├── images/              # Image files
└── files/               # PDFs and other downloadable files
```

## 🎨 Customization

### Key Files to Modify

- **`_config.yml`**: Update personal information, social media links, and site settings
- **`_pages/about.md`**: Edit the main about page content
- **`_pages/cv.md`**: Update your curriculum vitae
- **`_data/navigation.yml`**: Customize the navigation menu
- **`images/profile2.png`**: Replace with your profile photo

### Adding Content

- **Publications**: Add `.md` files to `_publications/` directory
- **Blog Posts**: Add `.md` files to `_posts/` directory with date format `YYYY-MM-DD-title.md`
- **Files**: Upload PDFs and other files to `files/` directory

## 🔧 Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `master` branch. The deployment typically takes 2-5 minutes to complete.

### Deployment Status
You can check the deployment status in the "Actions" tab of this repository.

## 📚 Resources

- **Jekyll Documentation**: [https://jekyllrb.com/docs/](https://jekyllrb.com/docs/)
- **Academic Pages Guide**: [https://academicpages.github.io/](https://academicpages.github.io/)
- **GitHub Pages Documentation**: [https://docs.github.com/en/pages](https://docs.github.com/en/pages)
- **Markdown Guide**: [https://www.markdownguide.org/](https://www.markdownguide.org/)

## 📞 Contact

If you have questions about this website or would like to collaborate:

- **Email**: rmhizha@ucl.ac.uk
- **GitHub**: [@HENGRUIZZZZ](https://github.com/HENGRUIZZZZ)
- **Website**: [https://hengruizzzz.github.io](https://hengruizzzz.github.io)

## 📄 License

This project is based on the [Academic Pages template](https://github.com/academicpages/academicpages.github.io), which is derived from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose. 

The original template is released under the MIT License. See [LICENSE](LICENSE) for details.

---

⭐ **If you find this website template useful, please consider giving it a star!**
