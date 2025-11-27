# Social Links Profile (Vanilla Web)

A clean, responsive Social Links Profile component built using vanilla HTML and CSS.

![Profile Preview](./images/active-states.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS for a lightweight component.
- **Responsive Design:** Adapts to different screen sizes for good viewing on mobile and desktop.
- **Easy to Integrate:** Drop the `index.html` and `style.css` into any project—no build step or dependencies.
- **Customizable:** Simple class structure and CSS variables (in `style.css`) let you quickly change colors, spacing, and typography.

## Prerequisites & Dependencies

- A web browser (Chrome, Firefox, Safari) to view the component.
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).

## Installation & Setup Instructions

1. **Clone or download the repository** (or copy the project folder locally):

```bash
git clone https://github.com/syntaxSangoma/social-links-profile-vanilla-03
cd social-links-profile-03
```

2. **Open the project** in your editor and open `index.html` in the browser:

- Double-click `index.html` or open it from your editor.
- Or serve the folder using a simple local server (recommended for consistent image loading)

## Usage Examples

The component is static and intended as a visual profile with social links. To modify content, edit `index.html`:

- Change the avatar image at `./images/avatar-jessica.jpeg` to your own image.
- Update the displayed name, location, and bio in the `index.html` markup.
- Edit the anchor tags in the `.profile-card__links` section to point to your real social URLs.

Example: Replace the avatar image file and update the `alt` text and `figcaption`.

## Configuration Options

Most visual changes live in `style.css`. Typical customizations:

- **Colors & Palette:** Update CSS variables at the top of `style.css` (if present) or replace color tokens directly.
- **Typography:** Change the font-family or import a Google Font inside `style.css`.
- **Card Size & Spacing:** Tweak `.profile-card` width, padding and avatar dimensions to fit your design.
- **Link Styles:** Modify `.profile-card__link` styles to change hover, active and focus states.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/add-dark-mode`).
3. Make changes with focused commits.
4. Push to your fork and open a pull request describing your changes.

## License

License not specified

## Acknowledgments

- Google Fonts for the ``Inter`` font used in this project.
