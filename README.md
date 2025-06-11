# From Questions to Transformation

**A Practitioner's Guide to Inquiry-Based Educational Reform**

📖 **Read the book online at:** https://www.ensembio.com/book-china-education/

## About

This book presents a comprehensive framework for implementing inquiry-based educational reform through the Three Questions, Three Explorations methodology. Drawing from case studies across China's educational landscape, it provides educational leaders with practical tools for navigating the complex transition from pilot programs to system-wide transformation.

**Author:** Jian Huang  
**Publisher:** Proofbound, Inc  
**Copyright:** 2025

## Project Setup

This book is built using [Quarto](https://quarto.org/), a scientific and technical publishing system.

### Prerequisites

1. **Install Quarto**: Download and install from https://quarto.org/docs/download/
2. **Install R or Python** (optional but recommended for advanced features)
3. **Install LaTeX** (for PDF output): 
   - macOS: `brew install --cask mactex`
   - Windows/Linux: Install TeX Live

### Getting Started

1. **Clone the repository:**
   ```bash
   git clone [repository-url]
   cd book-china-education
   ```

2. **Preview the book:**
   ```bash
   quarto preview
   ```
   This will start a local server and open the book in your browser with live reload.

3. **Build the book:**
   ```bash
   # HTML version
   quarto render
   
   # PDF version
   quarto render --to pdf
   
   # EPUB version  
   quarto render --to epub
   ```

### Project Structure

- `_quarto.yml` - Main configuration file
- `index.qmd` - Book introduction/preface
- `intro.qmd` - Introduction chapter
- `ch1-foundations.qmd` through `ch10-sustainability.qmd` - Main chapters
- `summary.qmd` - Conclusion
- `references.bib` - Bibliography
- `_resources/` - Images, CSS, and other assets
- `docs/` - Rendered output directory

### Development Workflow

1. Edit `.qmd` files using your preferred editor
2. Use `quarto preview` for live development
3. Commit changes to git
4. Build final versions with `quarto render`

### Output Formats

The book is configured to generate:
- **HTML**: Interactive web version with search
- **PDF**: Print-ready version with custom formatting
- **EPUB**: E-reader compatible format

### Publishing

The HTML version is automatically published to GitHub Pages when changes are pushed to the main branch.

## Contributing

This book documents educational reform practices and methodologies. For questions or suggestions, please contact the author or publisher.

## License

Copyright 2025 Proofbound, Inc. All rights reserved.