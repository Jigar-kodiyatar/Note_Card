# Profile Card

This is a simple HTML project displaying a profile card with a link to a GitHub profile. The card includes a date, profile name, and a button to open the GitHub profile in a new tab.

## Technologies Used

- HTML
- Tailwind CSS
- Font Awesome

## Description

The project displays a profile card centered on the screen with a background and hover effect. The card includes:
- A header with the date.
- Profile information.
- A button that links to the GitHub profile of Jigar Kodiyatar.

## Features

- Responsive design.
- Hover effect on the card.
- Button to open the GitHub profile.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Open `index.html` in your web browser.

## Code Explanation

### HTML Structure

- **Head Section**:
  - Includes meta tags for character set and viewport settings.
  - Links to Font Awesome for icons.
  - Includes Tailwind CSS for styling.

- **Body Section**:
  - Main container using Tailwind CSS classes for layout and styling.
  - Two divs creating the layered effect with rotation and hover transitions.
  - Profile card with date, profile name, and button.

### JavaScript

- A simple function `openLink()` is defined to change the window location to the specified GitHub profile.

## Tailwind CSS Classes

- `min-h-screen`, `w-full`, `bg-gray-900`: Sets the main container's height, width, and background color.
- `absolute`, `translate-x-1/2`, `translate-y-1/2`, `rotate-6`: Positions and rotates the card for the layered effect.
- `hover:rotate-0`: Removes rotation on hover for the card.
- `rounded-2xl`, `bg-gray-400`, `bg-gray-100`, `p-6`: Sets border radius, background colors, and padding.
- `flex`, `justify-end`, `justify-center`, `items-baseline`, `gap-2`: Uses Flexbox for layout.
- `text-center`, `text-xl`, `font-extrabold`, `text-gray-600`, `text-gray-900`: Sets text alignment, size, weight, and color.
- `bg-[#7f00ff]`, `text-white`, `hover:bg-[#8A2BE2]`: Custom colors for the button.

## Contributing

If you would like to contribute to this project, feel free to create a pull request or open an issue with your suggestions.

![image](https://github.com/user-attachments/assets/3715fd24-21f1-45ca-a1d4-ad5319410584)
