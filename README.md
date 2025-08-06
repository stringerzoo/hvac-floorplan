# HVAC Building Floorplan

Interactive web-based floor plan reference tool for Immanuel Building's HVAC control areas, designed to complement the Trane Tracer SC system.

## 🔗 Live Site
**[https://stringerzoo.github.io/hvac-floorplan/](https://stringerzoo.github.io/hvac-floorplan/)**

## ✨ Features

- **Multi-floor navigation** - Switch between Lower Level, First Floor, Second Floor, and Third Floor
- **HVAC area overlay** - Toggle colored control areas on/off to see scheduling zones
- **Zoom & pan** - Zoom in for details, drag to navigate around zoomed images
- **Quick search** - Find rooms and areas by name to jump to relevant floors
- **Mobile responsive** - Works on tablets and phones for field reference
- **Keyboard shortcuts** - Fast navigation using hotkeys
- **Professional interface** - Clean, modern design optimized for HVAC technicians

## 🎯 Purpose

This tool serves as a **visual reference companion** to the Trane Tracer SC control system, helping technicians quickly:
- Locate HVAC control areas across building floors
- Understand scheduling area boundaries 
- Navigate between different building levels
- Reference room and area relationships

## 🏗️ File Structure

```
hvac-floorplan/
├── index.html              # Main application file
└── images/
    ├── lower-level-base.png     # Base architectural drawing
    ├── lower-level-overlay.png  # With HVAC areas highlighted
    ├── first-floor-base.png
    ├── first-floor-overlay.png
    ├── second-floor-base.png
    ├── second-floor-overlay.png
    ├── third-floor-base.png
    ├── third-floor-overlay.png
    └── 2021-5-20_logomark_gold.png  # Site favicon
```

## 🚀 Usage

### Navigation
- Click floor buttons to switch between levels
- Use "Hide/Show HVAC Areas" to toggle overlay information
- Search for room names or areas to quickly navigate

### Zoom & Pan
- Use +/− buttons or mouse wheel to zoom
- Click and drag when zoomed in to pan around
- Home button (⌂) resets to full view

### Keyboard Shortcuts
- `L` - Lower Level
- `1` - First Floor  
- `2` - Second Floor
- `3` - Third Floor
- `Space` - Toggle HVAC overlay
- `=` / `-` - Zoom in/out
- `0` - Reset zoom
- `?` - Show help dialog

## 💡 Tips

- **Yellow areas** represent office scheduling areas (consistent across all floors)
- **Other colors** vary by floor - refer to overlay text for specific area details
- Tool works offline once initially loaded
- Optimized for use alongside Trane Tracer SC system interface

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no external dependencies
- Hosted via GitHub Pages for reliability and speed
- Responsive design works across desktop, tablet, and mobile devices
- Images optimized for fast loading while maintaining technical drawing quality

---

*Built for Immanuel Building facility management team*
