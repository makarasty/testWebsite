# 🌐 Local Test Server - NGINX Dashboard

Welcome to **Local Test Server**, a simple and elegant web interface designed to provide quick insights into your local or remote NGINX server. This project is ideal for developers, system administrators, or anyone who wants a quick summary of their server's operation at a glance.

## ✨ Features

  * **Dynamic Server Information**: Displays protocol, host, port, client IP address, security status, User Agent, connection time, and full URL.
  * **Connection Performance Test**: A visual indicator of connection performance and a function to test server response time.
  * **Multi-language Support**: Switch between English (EN), Ukrainian (УК), and Russian (РУ) languages.
  * **Copy to Clipboard**: Easily copy any displayed information with a single click.
  * **Server Uptime**: Tracks how long the server has been running since the page was loaded.
  * **Responsive Design**: Looks great on any device, from desktops to mobile phones.
  * **Interactive Background**: Engaging particles on the background for an enhanced visual experience.

## 🚀 Getting Started

To run this project locally, follow these simple steps:

### Prerequisites

You should have NGINX or any other web server capable of serving static HTML files installed.

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/makarasty/local-test-server.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd local-test-server
    ```
3.  **Place `index.html`**:
    Move the `index.html` file into your web server's root directory (e.g., `/var/www/html/` for NGINX on Linux, or the appropriate directory for your setup).

### Usage

Once the `index.html` file is placed on your web server, simply open your web browser and navigate to your server's address (e.g., `http://localhost` or your server's IP address).