# Live TV Website

This website embeds your YouTube live stream with custom headlines and branding.

## Setup Instructions

### 1. Add Your Logo
- Replace `logo.png` with your actual logo file
- Recommended size: 200x60 pixels (or similar aspect ratio)
- Supported formats: PNG, JPG, SVG

### 2. Customize Headlines
Edit the following sections in `index.html`:

- **Main Headline**: Change "Your Custom Headline Here"
- **Breaking News**: Update the breaking news text
- **News Ticker**: Modify the scrolling news items
- **News Stories**: Replace the placeholder news content

### 3. Update Branding
- Change "Your News Network" in the footer
- Modify colors in `style.css` (currently using red theme)
- Update the page title in the `<title>` tag

### 4. YouTube Stream
The stream is already configured with your provided link:
`https://www.youtube.com/live/45ciC1qVVsQ?si=9mw9g_jMJXxLKIBI`

If you need to change the stream, update the `src` attribute in the iframe.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Fixed Logo**: Your logo stays in the top-right corner
- **Animated Headlines**: Smooth animations for better visual appeal
- **News Ticker**: Scrolling news updates
- **Professional Styling**: Dark theme with red accents

## File Structure

```
tvlive/
├── index.html          # Main HTML file
├── style.css          # CSS styling
├── logo.png           # Your logo (add this file)
└── README.md          # This file
```

## How to Use

1. Add your logo file as `logo.png`
2. Edit the headlines and news content in `index.html`
3. Open `index.html` in a web browser
4. Upload to your web server for live deployment

## Customization Tips

- To change the color scheme, modify the CSS variables for colors
- Adjust the video size by changing the `padding-bottom` percentage in `.video-container`
- Modify animation speeds in the CSS `@keyframes` sections
- Add more news sections by copying the `.news-item` structure

Your website is ready to use! Just add your logo and customize the content.