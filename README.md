# Fully Customizable Subscription Page Template for Marzban & Marzneshin

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Version](https://img.shields.io/badge/version-1.0.0-green.svg) ![Downloads](https://img.shields.io/badge/downloads-1000%2B-orange.svg)

Welcome to the **qoqnoos-template** repository! This project offers a fully customizable subscription page template designed specifically for Marzban and Marzneshin. You can modify it to fit your needs, whether you are looking to create a simple subscription form or a more complex user interface.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Fully Customizable**: Change colors, fonts, and layouts easily.
- **Responsive Design**: Looks great on all devices.
- **User-Friendly**: Simple interface for easy navigation.
- **Easy Integration**: Works well with existing projects.
- **Documentation**: Comprehensive guides to help you set up.

## Installation

To get started with the **qoqnoos-template**, you need to download the latest release. Visit the [Releases](https://github.com/acs-ust-edu-sd/qoqnoos-template/releases) section to download the necessary files. Once downloaded, extract the files and run the index.html file in your web browser.

## Usage

After you have installed the template, open the `index.html` file in your browser. You will see the basic structure of the subscription page. 

### Basic Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subscription Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Subscribe Now!</h1>
    </header>
    <main>
        <form id="subscription-form">
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2023 Marzban and Marzneshin</p>
    </footer>
</body>
</html>
```

## Customization

### Changing Colors

To change the colors of your subscription page, open the `styles.css` file. You can easily modify the color variables to match your branding.

```css
:root {
    --primary-color: #4CAF50; /* Change this to your desired color */
    --secondary-color: #ffffff; /* Change this to your desired color */
}
```

### Modifying Layout

You can adjust the layout by changing the CSS styles. For example, to center the form, add the following styles:

```css
main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
```

## Contributing

We welcome contributions to improve the **qoqnoos-template**. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For more updates and to download the latest version, check the [Releases](https://github.com/acs-ust-edu-sd/qoqnoos-template/releases) section.

Feel free to explore the template and customize it to fit your needs. Enjoy building your subscription page!