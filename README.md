# Lead Management Admin Dashboard

This repository contains the source code for an **Admin Dashboard** designed to manage leads effectively. The dashboard provides a clean, responsive interface with essential tools to track and analyze leads.

## Features

- **Responsive Design:** Built with Bootstrap for compatibility across devices.
- **Intuitive Navigation:** Sidebar menu with quick access to Dashboard, Store, Analytics, Messages, Team, and Settings.
- **Interactive Dashboard Widgets:** Key metrics like new leads, visitors, and total leads are displayed.
- **Data Table:** Organized display of lead details including location and timestamps.
- **Search and Notifications:** Easy-to-use search functionality and notification alerts.
- **Dark Mode Toggle:** Switch between light and dark themes effortlessly.
- **Export Feature:** Download data in `.xlsx` format.

## Project Structure

- **`index.html`:** The main HTML file containing the dashboard layout and structure.
  - Sidebar navigation.
  - Main content area with widgets and data table.

- **CSS:**
  - **Bootstrap:** Used for responsive layout.
  - **Custom CSS:** Additional styling via `style.css`.

- **JavaScript:**
  - Dynamic updates and event handling via `script.js`.

## Getting Started

### Prerequisites

- **Web Browser:** A modern browser like Chrome, Firefox, or Edge.
- **Code Editor:** Recommended for customization, e.g., Visual Studio Code.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nasal-thanseer/admin-dashboard.git
   cd admin-dashboard
   ```

2. **Open the project:**
   - Ensure the following files are in place:
     - `index.html` for the dashboard layout.
     - `style.css` for custom styles.
     - `script.js` for dynamic behavior.
   - Open `index.html` in your browser or serve it using a local server.

   Example using Python's built-in server:
   ```bash
   python -m http.server 8080
   ```

3. **View the dashboard:**
   - Navigate to `http://localhost:8080` in your browser.

## Usage

1. **Navigate through the sidebar:** Access different sections like Analytics, Messages, and Team.
2. **View Dashboard Widgets:** Monitor lead metrics such as new leads and visitors.
3. **Interact with Data Table:** Check detailed lead information.
4. **Download Reports:** Export lead data in `.xlsx` format.
5. **Customize Theme:** Toggle between light and dark modes.

## File Details

### HTML
- **`index.html`**: Provides the structure and layout for the admin dashboard.

### CSS
- **`style.css`:**
  - Adds bespoke styles for enhanced visuals.
  - Works alongside Bootstrap for a modern, responsive design.

### JavaScript
- **`script.js`:**
  - Handles interactive elements such as toggles and notifications.
  - Updates data dynamically in the table.

## Future Enhancements

- Integrate with a backend to store and fetch lead data.
- Add authentication for secure access.
- Enhance analytics with graphs and charts.
- Implement APIs for real-time updates.

## Contributing

We welcome contributions! Fork the repository, make changes, and submit a pull request.

