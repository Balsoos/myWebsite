# Interactive Portfolio Website

A modern, responsive portfolio website that you can edit directly on the website itself without touching any code!

## Features

- **Interactive Admin Panel**: Edit all content directly from the website
- **Real-time Updates**: Changes are saved automatically and appear immediately
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful, professional design with smooth animations
- **Local Storage**: Your changes are saved locally in your browser
- **No Backend Required**: Everything runs in your browser

## How to Use

### Getting Started

1. **Open the Website**: Simply open `index.html` in your web browser
2. **Click the Edit Button**: Look for the "Edit" button in the navigation bar
3. **Make Your Changes**: Use the admin panel to update your information
4. **Save Changes**: Click "Save Changes" to apply your updates

### What You Can Edit

#### Personal Information
- **Name**: Your full name
- **Title**: Your professional title (e.g., "Full Stack Developer")
- **Email**: Your contact email address
- **Location**: Your city and country
- **About Me**: A detailed description about yourself

#### Social Links
- **LinkedIn**: Your LinkedIn profile URL
- **GitHub**: Your GitHub profile URL
- **Twitter**: Your Twitter profile URL

#### Skills
- **Add Skills**: Type a skill name and click "Add"
- **Remove Skills**: Click the "Remove" button next to any skill
- **Reorder**: Skills will appear in the order you add them

#### Projects
- **Add Projects**: Click "Add New Project" to create a new project entry
- **Edit Projects**: Update title, description, live URL, and GitHub URL
- **Remove Projects**: Click "Remove Project" to delete a project

### Admin Panel Features

- **Real-time Preview**: See your changes as you type
- **Auto-save**: Changes are automatically saved to your browser
- **Reset Option**: Reset to default values if needed
- **Mobile Friendly**: Admin panel works on all devices

## File Structure

```
myWebsite/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Adding Your Own Profile Picture

To add your own profile picture:

1. Replace the placeholder icon in the hero section
2. Add an `<img>` tag instead of the `<i>` tag in the profile-placeholder div
3. Update the CSS to style your image appropriately

### Changing Colors

The website uses a modern color scheme that you can customize by editing the CSS variables in `styles.css`:

- Primary color: `#3b82f6` (blue)
- Secondary color: `#64748b` (gray)
- Background colors: `#f8fafc` (light gray) and `#ffffff` (white)

### Adding New Sections

To add new sections:

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add JavaScript functionality in `script.js` if needed

## Browser Compatibility

This portfolio works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Data Storage

Your portfolio data is stored locally in your browser's localStorage. This means:
- Your changes persist between browser sessions
- Data is stored only on your device
- No server or database required
- You can export/import your data if needed

## Tips for a Great Portfolio

1. **Keep it Concise**: Focus on your best work and most relevant skills
2. **Use Clear Descriptions**: Explain what each project does and what technologies you used
3. **Include Links**: Always provide links to live demos and source code
4. **Professional Photos**: Use high-quality images for your projects
5. **Regular Updates**: Keep your portfolio current with your latest work

## Troubleshooting

### Changes Not Saving
- Make sure you click "Save Changes" in the admin panel
- Check that your browser supports localStorage
- Try refreshing the page

### Admin Panel Not Opening
- Check that JavaScript is enabled in your browser
- Try refreshing the page
- Check the browser console for any error messages

### Mobile Issues
- The admin panel is fully responsive
- If you have issues, try rotating your device or using landscape mode

## Future Enhancements

Potential features that could be added:
- Image upload for profile picture and project screenshots
- Multiple themes and color schemes
- Export/import functionality for backup
- Contact form integration
- Blog section
- Resume download functionality

## Support

If you encounter any issues or have questions about customizing your portfolio, feel free to:
- Check the browser console for error messages
- Ensure all files are in the same directory
- Try opening the website in a different browser

## License

This project is open source and available under the MIT License. Feel free to modify and use it for your own portfolio! 