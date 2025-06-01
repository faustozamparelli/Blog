# Fausto Zamparelli's Blog

[![Hugo](https://img.shields.io/badge/Hugo-0.128+-blue?logo=hugo)](https://gohugo.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **"WAKE UP, NEO... YOU ARE NO MORE ON GITHUB"**

Welcome to my personal blog - a digital sanctuary where thoughts flow freely without filters. This Hugo-powered site serves as my platform for expressing ideas, sharing perspectives, and stimulating thoughtful discussions.

🌐 **Live Site**: [faustozamparelliblog.vercel.app](https://faustozamparelliblog.vercel.app) | [faustozamparelli.com/blog](https://faustozamparelli.com/blog)

## 🎯 About This Blog

This blog represents my commitment to digital ownership and creative freedom. Inspired by the early days of the Internet when it was full of creators rather than users, this platform is:

- **Unfiltered**: Raw thoughts and honest perspectives
- **Apolitical**: Focus on ideas, not indoctrination
- **Open**: Built with open-source tools and transparency
- **Personal**: A space that truly feels like mine

## 🛠 Built With

- **[Hugo](https://gohugo.io/)** - Fast static site generator
- **[GitHub-Style Theme](https://github.com/MeiK2333/github-style)** - Clean, familiar interface
- **[Vercel](https://vercel.com/)** - Deployment and hosting
- **[Google Analytics](https://analytics.google.com/)** - Insights and analytics

## 🏗 Project Structure

```
Blog/
├── content/
│   ├── readme.md          # About page content
│   └── post/              # Blog posts
│       ├── Welcome.md     # Introduction post
│       ├── Quotes.md      # Collection of meaningful quotes
│       ├── Wokeism.md     # Thoughts on modern culture
│       └── ...
├── themes/
│   └── github-style/      # Hugo theme (git submodule)
├── public/                # Generated static files
├── layouts/               # Custom layout overrides
├── archetypes/            # Content templates
└── hugo.toml             # Hugo configuration
```

## 🚀 Quick Start

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.128.0 or later)
- [Git](https://git-scm.com/)

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/faustozamparelli/Blog.git
   cd Blog
   ```

2. **Initialize submodules**

   ```bash
   git submodule update --init --recursive
   ```

3. **Start the development server**

   ```bash
   hugo server -D
   ```

4. **Open your browser**
   Visit `http://localhost:1313` to see the blog

### Creating New Posts

```bash
hugo new post/your-post-title.md
```

This creates a new post with the proper front matter in `content/post/`.

## ✍️ Content Guidelines

### Post Structure

Each post includes:

- **Front matter** with title, date, and summary
- **Optional Spotify embed** for the writing soundtrack
- **Personal reflections** with sources and reasoning
- **Open-minded discourse** encouraging thoughtful discussion

### Writing Philosophy

- **Authenticity over perfection** - Raw thoughts matter more than polished prose
- **Sources and reasoning** - Transparent thinking process
- **Growth mindset** - Perspectives can evolve
- **Respectful dialogue** - Open to feedback and opposing views

## 🚢 Deployment

The blog is automatically deployed to Vercel on every push to the main branch.

### Manual Deployment

1. **Build the site**

   ```bash
   hugo --minify
   ```

2. **Deploy the `public/` directory** to your hosting platform

### Environment Variables

For deployment, ensure these are configured:

- `HUGO_VERSION`: 0.128.0 (or your preferred version)
- `NODE_VERSION`: 18 (for build process)

## 🎨 Customization

### Theme Modifications

The GitHub-style theme can be customized by:

- Modifying files in `layouts/` to override theme defaults
- Updating styles in theme files
- Adjusting configuration in `hugo.toml`

### Key Configuration

```toml
baseURL = "https://faustozamparelliblog.vercel.app"
title = 'faustozamparelli'
theme = 'github-style'

[params]
  author = 'fast'
  github = 'faustozamparelli'
  location = 'Rome'
  description = 'WAKE UP, NEO... YOU ARE NO MORE ON GITHUB'
  email = 'fausto.zamparelli@gmail.com'
```

## 📊 Analytics

The blog uses Google Analytics (G-MZ2X3WCL72) to understand reader engagement and improve content.

## 🤝 Contributing

While this is a personal blog, feedback is always welcome:

- **Issues**: Report bugs or suggest improvements
- **Discussions**: Share thoughts on posts
- **Email**: Direct feedback to [fausto.zamparelli@gmail.com](mailto:fausto.zamparelli@gmail.com)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 About the Author

**Fausto Zamparelli** - Full-stack developer and AI enthusiast from Rome, Italy

- 🎓 Studying Applied Computer Science and AI at Sapienza University
- 💼 Focus on web development and artificial intelligence
- 🏠 Based in Rome, Italy
- 📧 Email: [fausto.zamparelli@gmail.com](mailto:fausto.zamparelli@gmail.com)

### Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fausto-zamparelli-183387245/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white)](https://x.com/faustozampa)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/faustozamparelli/)
[![Spotify](https://img.shields.io/badge/Spotify-1ED760?logo=spotify&logoColor=white)](https://open.spotify.com/user/fausto.zamparelli-it)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/faustozamparelli)

---

> _"Love what you do, Do what you love"_ - Personal motto

Take the red pill and dive into the rabbit hole of thoughts and ideas. Welcome to the blog! 🐰💊
