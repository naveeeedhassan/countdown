# Countdown Timer

A countdown timer designed with HTML, CSS, and JavaScript. This timer is styled with a gradient background and displays the remaining time in days, hours, minutes, and seconds until a specified date and time.

## Features

- Beautiful gradient background (Purple to Blue)
- Displays time in days, hours, minutes, and seconds
- Countdown to a specific date and time
- Customizable target date and time

## Preview

<https://naveeeedhassan.github.io/countdown/>

## Getting Started

### Prerequisites

You need a modern web browser (Chrome, Firefox, Safari, etc.) to run this countdown timer.

### Installation

1. Clone or download the repository.

   - `git clone https://github.com/yourusername/countdown-timer.git`

2. Open `index.html` in your web browser.

   Simply double-click the `index.html` file to open it in your default web browser and view the countdown timer.

3. Alternatively, you can upload the files to a server if you want to use the timer on a website.

### Customizing the Countdown Date

To change the target date and time for the countdown timer, update the following line in the `script` section of `index.html`:

- startCountdown(new Date("2025-02-01T12:00:00Z").getTime());

Replace `"2025-02-01T12:00:00Z"` with your desired target date and time in ISO 8601 format (e.g., `YYYY-MM-DDTHH:MM:SSZ`).

### Customizing the Look and Feel

The timer container has a gradient background (from purple to blue) by default. To change the color scheme, modify the following CSS in `styles`:

- #countdown-container {
    background: linear-gradient(135deg, #6a1b9a, #1976d2); /* Purple to Blue Gradient */
}

You can change the colors or adjust the gradient direction according to your preferences.

### Responsive Design

The countdown timer is fully responsive and will adjust for smaller screen sizes like mobile phones and tablets.

### Example Target Date

To set the timer for a different target, for example, December 31, 2025, at midnight UTC, modify the `startCountdown` function like this:

- startCountdown(new Date("2025-12-31T00:00:00Z").getTime());

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
