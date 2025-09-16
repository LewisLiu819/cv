# Personal Website - Bridge Builder in Computer Science

A comprehensive portfolio website showcasing educational innovation, AI research, and community building, built with Astro and designed according to modern web standards.

## 🌟 Features

- **Performance-First**: Built with Astro for optimal loading speeds and SEO
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern Architecture**: Component-based structure with TypeScript support
- **Professional Portfolio**: Comprehensive showcase of achievements and projects
- **Blog Platform**: Ready-to-use blog structure for sharing insights

## 📁 Website Structure

- **Homepage**: Hero section with key metrics and featured work
- **About**: Personal narrative as a bridge builder in CS education
- **Research**: AI research portfolio with detailed project descriptions
- **Projects**: Showcase of educational and technical projects
- **Achievements**: Academic excellence and competition results
- **Teaching**: Educational philosophy and curriculum development
- **Blog**: Insights on AI, education, and technology
- **Contact**: Professional contact information and collaboration opportunities

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd cv

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### Development Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## 🛠️ Technology Stack

- **Framework**: Astro 5.x
- **Styling**: Tailwind CSS
- **Content**: MDX support for blog posts
- **Deployment**: Optimized for Vercel, Netlify, or GitHub Pages
- **SEO**: Built-in sitemap generation and meta optimization

## 📦 Key Dependencies

- `astro` - Static site generator
- `@astrojs/tailwind` - Tailwind CSS integration
- `@astrojs/mdx` - MDX support for content
- `@astrojs/sitemap` - Automatic sitemap generation
- `tailwindcss` - Utility-first CSS framework

## 🎨 Customization

### Personal Information
1. Update contact information in `src/layouts/Layout.astro`
2. Replace placeholder images in `public/` directory
3. Add your actual CV file to `public/cv.pdf`

### Content Updates
- **Personal details**: Update name, links, and contact info throughout the pages
- **Project information**: Modify project descriptions in relevant page files
- **Research details**: Update research projects and publications
- **Achievements**: Add your specific accomplishments and metrics

### Styling
- **Colors**: Modify the color scheme in `tailwind.config.mjs`
- **Fonts**: Update font selections in the layout file
- **Components**: Customize components in `src/components/`

## 🌍 Deployment

### Vercel (Recommended)
```bash

```

### Netlify
1. Connect your repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`

### GitHub Pages
```bash
npm run build
# Deploy the `dist` folder to your GitHub Pages repository
```

## 📈 Performance Features

- **Zero JavaScript by default**: Astro's island architecture
- **Optimized images**: Responsive image handling
- **Fast loading**: Minimal CSS and optimized fonts
- **SEO optimized**: Meta tags, structured data, and sitemaps
- **Lighthouse perfect scores**: Optimized for Core Web Vitals

## 🔧 Configuration

### Site Configuration
Update `astro.config.mjs` with your domain:
```javascript
export default defineConfig({
  site: 'https://yourdomain.com',
  // ... other config
});
```

### SEO and Meta
Update meta descriptions and titles in each page's frontmatter.

## 📝 Content Management

### Adding Blog Posts
1. Create new `.md` or `.mdx` files in a `src/content/blog/` directory
2. Follow the established frontmatter structure
3. Images should be placed in `public/blog/` directory

### Updating Projects
Modify the project showcases in `src/pages/projects.astro` with your specific projects, technologies, and achievements.

## 🤝 Contributing

This is a personal portfolio template, but suggestions for improvements are welcome:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎯 Based on Website Plan

This implementation follows the comprehensive website plan for college applications, focusing on:
- **Bridge-builder positioning**: Highlighting connections between technology and education
- **Performance excellence**: Astro framework for optimal speed and SEO
- **Professional presentation**: Clean, modern design suitable for academic applications
- **Content strategy**: Strategic organization of achievements and experiences
- **Technical demonstration**: Modern web technologies showcasing technical competence

## 📞 Support

For questions or customization help, please refer to:
- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [MDX Documentation](https://mdxjs.com/)

---

**Built with ❤️ using Astro, designed for impact and performance.**