# Claude Development Guide

This document provides Claude with context and instructions for working on the "From Questions to Transformation" Quarto book project.

## Project Overview

- **Type**: Quarto book project
- **Author**: Jian Huang
- **Topic**: Inquiry-based educational reform methodology
- **Online**: https://www.ensembio.com/book-china-education/

## Technical Stack

- **Build System**: Quarto
- **Formats**: HTML, PDF, EPUB
- **Styling**: Minty theme with custom CSS
- **Deployment**: GitHub Pages (docs/ directory)

## Development Commands

### Preview and Development
```bash
# Start live preview server
quarto preview

# Check project structure
quarto check
```

### Building
```bash
# Render all formats
quarto render

# Render specific format
quarto render --to html
quarto render --to pdf
quarto render --to epub
```

### Quality Checks
```bash
# Validate Quarto project
quarto check

# Preview before publishing
quarto preview
```

## File Structure

- `_quarto.yml` - Main configuration (book metadata, chapters, formats)
- `*.qmd` - Quarto markdown chapters and content
- `references.bib` - Bibliography entries
- `_resources/` - Images, CSS, assets
- `docs/` - Built output (do not edit directly)

## Content Guidelines

1. **Chapter Files**: All content is in `.qmd` files using Quarto markdown
2. **References**: Use `references.bib` for citations
3. **Images**: Store in `_resources/images/` 
4. **Cross-references**: Use Quarto's built-in cross-referencing

## Common Tasks

### Adding New Chapter
1. Create new `.qmd` file
2. Add to `chapters` list in `_quarto.yml`
3. Use consistent heading structure

### Updating Bibliography
1. Edit `references.bib` file
2. Reference using `[@key]` syntax in `.qmd` files

### Modifying Styling
1. Edit `_resources/book/css/normalize.css`
2. Modify theme settings in `_quarto.yml`

## Publishing Workflow

1. Edit content in `.qmd` files
2. Preview with `quarto preview`
3. Build with `quarto render`
4. Commit changes (docs/ directory is built output)
5. Push to repository (auto-deploys via GitHub Pages)

## Notes for Claude

- Always run `quarto preview` to test changes
- Check `_quarto.yml` for project configuration
- Use existing chapter structure as template for new content
- Preserve Chinese font support in PDF configuration
- Maintain consistent academic tone throughout book