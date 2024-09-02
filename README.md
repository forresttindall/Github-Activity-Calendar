# GitHub Activity Calendar

<img width="1086" alt="Screenshot 2024-09-02 at 3 19 56 PM" src="https://github.com/user-attachments/assets/7928c2f8-faf1-4278-87bf-c39ff696b3ae">



## Overview

The GitHub Activity Calendar is a JavaScript library that generates a visual representation of a user's GitHub activity calendar. This library allows you to embed a calendar view of GitHub contributions directly into your website or application. It visualizes pull requests, issues opened, and commits made by a user, providing both graphical and statistical insights.

## Features

- Displays GitHub contribution calendar as seen on user profiles.
- Shows global statistics like longest streak and current streak of contributions.
- Provides tooltips with detailed daily contribution counts.
- Supports responsive design to fit different screen sizes.

## Installation

To use this library, you need to include the JavaScript file in your project. You can either clone the repository or download the file directly.

### Clone the Repository

```sh
git clone https://github.com/your-username/github-activity-calendar.git
```


## Download the File

1. Go to the [releases](link) page.
2. Download the latest release and include it in your project.

## Usage

### Include the Script

Add the JavaScript file to your project.

### Add HTML Element

Add a container element in your HTML where the calendar will be rendered.

```html
<div id="github-calendar"></div>

<script src="path/to/github-activity-calendar.js"></script>
<script>
  GitHubCalendar("#github-calendar", "your-username", {
    tooltips: true,
    summary_text: 'Summary of contributions by @your-username',
    cache: 86400
  });
</script>

```
## Usage

Replace `your-username` with the GitHub username whose calendar you want to display.

## Configuration Options

- `tooltips`: Set to `true` to enable tooltips on hover.
- `summary_text`: Customize the summary text displayed below the calendar.
- `cache`: Time in seconds for caching the calendar data.

## Contributing

We welcome contributions to improve the library. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of the changes.

## License

This project is licensed under the MIT License - see the [LICENSE](link) file for details.

## Contact

If you have any questions or need support, please open an issue in the repository or contact us at [your-email@example.com](mailto:Forrest@forresttindall.com).





