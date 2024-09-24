
# Networking Group Mixer
Welcome to the **Networking Group Mixer**! This project aims to facilitate networking opportunities by creating groups of professionals and students. It allows users to shuffle and create groups based on a predefined set of members, ensuring a mix of experiences and backgrounds.

## Demo
You can check out the live demo of the Networking Group Mixer application [here](https://halimbahae.github.io/Networking-Group-Mixer/).

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [New Features](#new-features)
- [Contributing](#contributing)

## Features

- **Dynamic Group Creation**: Easily create groups of professionals and students with customizable settings.
- **Configurable Parameters**:
  - Set the total group size.
  - Specify the maximum number of students per group.
  - Define how frequently groups should change (in mm:ss format).
- **User-Friendly Interface**: Simple and intuitive design using Tailwind CSS.
- **Live Countdown Timer**: Displays the time remaining until the next group change.
- **Logging**: Automatically logs group changes, including time, group number, members, and change interval.
- **Shuffle Groups**: Randomly shuffles existing groups with the click of a button.
- **Download Log**: Option to download the group change log as a CSV file.
- **Clear Log**: Clear previous log entries to start fresh.
- **Display Log**: A toggle feature to view the tracker log for quick reference.

## Installation

To get started with the Networking Group Mixer, follow these simple steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/halimbahae/networking-group-mixer.git
   cd networking-group-mixer
   ```

2. **Open the HTML file**:
   - Open `index.html` in your favorite web browser.

3. **Ensure internet connectivity**:
   - The project utilizes Tailwind CSS via a CDN, so an internet connection is required to load the styles.

## Usage

1. **Add Professionals and Students**: Enter names into the respective text areas, with each name on a new line.
2. **Configure Group Settings**:
   - Set the desired group size and maximum students per group.
   - Specify the timer duration for group changes.
3. **Create Groups**: Click the **Create Groups** button to generate and display groups.
4. **Shuffle Groups**: Click the **Shuffle Groups** button to randomize existing groups.
5. **View Log**: Use the **Show The Tracker log** button to toggle the visibility of the log table, which records group changes.

## New Features

- **Enhanced Timer Functionality**: The timer now counts down and automatically creates new groups when time is up.
- **Dynamic Inputs**: Users can specify both the group size and the maximum number of students per group, allowing for more tailored group configurations.
- **Detailed Logging**: Each group creation logs the current time, group number, members, and the timer setting for better tracking of group activities.
- **Clear and Download Log Options**: Users can clear the log or download it as a CSV file, improving usability for record-keeping.

## Contributing

We welcome contributions to the Networking Group Mixer! If you have suggestions for improvements or want to add features, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.


---
**Created with ❤️ by [Bahae Eddine Halim](https://linkedin.com/in/halimbahae)**
