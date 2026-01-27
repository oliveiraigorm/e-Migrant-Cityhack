# e-Migrant

You can view the live project at: [https://oliveiraigorm.github.io/cityhack](https://oliveiraigorm.github.io/cityhack)

## About
Project files developed during City Hack 2020 Hackathon

City Hack 2020 was a 24-hour technology marathon hackathon that took place entirely online on May 30-31, 2020, in Portugal. Organized by CityHack Portugal and supported by the Calouste Gulbenkian Foundation's "Hack for Good" initiative, this intensive event brought together 110 participants to develop technological solutions aimed at improving quality of life in cities. 

The hackathon adapted to the COVID-19 pandemic by moving fully online, demonstrating resilience and innovation in challenging times. Participants worked around the clock to create practical solutions for urban challenges, with a focus on education and social impact. The e-Migrant project emerged from this collaborative environment as a response to the pressing need for better integration support for immigrants in Portuguese cities.

e-Migrant is a web platform designed to simplify the lives of immigrants by providing them with essential resources, guidance, and opportunities to integrate into their host society.

## Mission

By linking immigrants directly with the host society, we decrease unequal opportunities. We promote the use of technology to solve social problems, providing the easiest way for immigrants who need guidance, information, job opportunities, education, and community to integrate with the host society.

## Features

The platform provides comprehensive support across multiple key areas:

### 🏢 **Jobs**
- Job opportunities specifically targeted for immigrants
- Career guidance and resources
- Employment support services

### 📚 **Education** 
- Educational opportunities and programs
- Language learning resources
- Skill development courses
- Information about local institutions

### ⚖️ **Legal**
- Legal guidance and resources
- Immigration information
- Document assistance
- Rights and responsibilities

### 🏥 **Health**
- Healthcare information and access
- Medical insurance guidance
- Health support services
- Well-being resources

### 👥 **Community**
- Community connection opportunities
- Social integration support
- Networking resources
- Cultural adaptation guidance

### 📰 **News & Updates**
- Latest immigration news
- Policy updates
- Community announcements
- Relevant events and opportunities

## The Problem

Whether pursuing a career, obtaining better education, volunteering, or seeking asylum, adapting to a new environment is one of the most life-changing experiences. It's often difficult without proper guidance, as most websites provide basic, insufficient information, frequently only in Portuguese. Immigrants lose significant time searching for information across multiple websites in a confused manner.

## Our Solution

We use technology to simplify immigrants' lives through a unified platform that provides:
- Centralized information and resources
- Easy navigation and accessibility
- Comprehensive guidance across all integration aspects
- Community support and connection opportunities
- Multilingual support where needed

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **CSS Framework**: Bootstrap 4.3.1
- **Build Tools**: Gulp.js for automation and build processes
- **Icons**: Font Awesome 5.10.2
- **JavaScript Library**: jQuery 3.5.0
- **CSS Preprocessor**: Sass/SCSS

## Getting Started

### Prerequisites

- Node.js (version 10 or higher)
- npm (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/oliveiraigorm/cityhack.git
   cd cityhack
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

   This will:
   - Compile SCSS files to CSS
   - Minify JavaScript files
   - Start a local development server
   - Open the application in your browser at `http://localhost:3000`
   - Enable live reloading for development

### Available Scripts

- `npm start` - Runs the development server with live reload
- Custom Gulp tasks are available for specific operations:
  - `gulp css` - Compile SCSS to CSS
  - `gulp js` - Minify JavaScript files
  - `gulp build` - Complete build process
  - `gulp watch` - Watch for file changes and rebuild
  - `gulp clean` - Clean vendor directory
  - `gulp vendor` - Copy vendor files

## Project Structure

```
├── css/                    # Compiled CSS files
├── img/                    # Images and assets
├── js/                     # JavaScript files
├── scss/                   # SCSS source files
├── vendor/                 # Third-party dependencies
├── *.html                  # HTML pages
├── gulpfile.js            # Gulp build configuration
├── package.json           # Project dependencies and scripts
└── README.md              # This file
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the package.json file for details.

## Contact

For support, questions, or contributions, please use the contact form on the platform or reach out through the repository's issue tracker.

---

**Note**: This platform is part of a social initiative to leverage technology for solving real-world immigration challenges and promoting inclusive societies.