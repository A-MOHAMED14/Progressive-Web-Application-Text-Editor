# Progressive Web Application (PWA): Text-Editor

## Description

This is a Progressive Web Application (PWA) text editor that runs in the browser, designed to work both online and offline. The application uses IndexedDB, with the help of the idb package, to store and retrieve data efficiently. It leverages Webpack for bundling JavaScript files and automatically generating the HTML, service worker, and manifest files. The service worker, implemented using Workbox, ensures that static assets are pre-cached for offline use. The app also includes an "Install" button for downloading the web application as a desktop icon.

## 🚀 Installation

1. Clone the Repository:

```sh
git clone https://github.com/A-MOHAMED14/Progressive-Web-Application-Text-Editor.git
```

2. Navigate to the Project Directory:

```sh
cd PWA-Text-Editor
```

3. Install dependencies:

```sh
npm run install
```

## 🏗️ Usage

To start the application, run the following command:

```sh
npm run start:dev
```

### Notes

- Use `npm run start:dev` for development, which runs both client and server concurrently.
- Use `npm run start` for production, which builds the client and starts the server.

## ⚒️ Technologies Used

- **Workbox**: For implementing service workers and caching strategies.
- **IndexedDB**: For storing and retrieving data locally in the browser.
- **Webpack**: For bundling JavaScript files and assets.
- **Babel**: For transpiling modern JavaScript to ensure compatibility.
- **idb**: A library for easier interaction with IndexedDB.
- **Express.js**: For routing and handling server requests.
- **Node.js**: The runtime environment for executing JavaScript on the server.
- **JavaScript**: The programming language used to build the application logic.

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:

```sh
git checkout -b feature/your-feature-name
```

3. Make your changes and commit them with descriptive messages:

```sh
git commit -m "Add new feature: your feature description"
```

4. Push your changes to your forked repository:

```sh
git push origin feature/your-feature-name
```

5. Open a pull request to the main repository, describing your changes in detail.
