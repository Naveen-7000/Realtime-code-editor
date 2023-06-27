# Realtime Code Editor

## Introduction

The Realtime Code Editor is a web-based code editor that allows multiple users to edit the same codebase simultaneously in realtime. It is built with React.js, Node.js, Socket.IO, and Tailwind CSS. You can find the Live Demo  at [https://musical-khapse-5244f7.netlify.app/.](https://shorturl.at/oqyGV)

<img width="887" alt="code-editor-2" src="https://github.com/Naveen-7000/Realtime-code-editor/assets/79650422/0ddc8ec8-d763-435c-9092-65c1dc5306ba">
<img width="881" alt="code-editor-3" src="https://github.com/Naveen-7000/Realtime-code-editor/assets/79650422/ade37016-6a22-46c5-bd23-66767a367984">



## Features

- Collaborative editing: Multiple users can edit the same codebase at the same time and see each other's changes in realtime.
- Syntax highlighting: The editor supports syntax highlighting for multiple programming languages.
- Live preview: Changes to the code are reflected in a live preview window.
-Supports mulitiple languages

## Installation

To install and run the Realtime Code Editor locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Naveen-7000/Realtime-code-editor`
2. Navigate to the project directory: `cd realtime-code-editor`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`

The application will be running at http://localhost:3000.

## Deployment

To deploy the Realtime Code Editor to a production environment, follow these steps:

1. Build the production bundle: `npm run build`
2. Set the `NODE_ENV` environment variable to `production`: `export NODE_ENV=production`
3. Start the production server: `npm run start:prod`

## Configuration

The Realtime Code Editor can be customized by creating a `.env` file in the root directory of the project and setting the following variables:

- `PORT`: The port number on which the server should listen (default: 3000).
- `SESSION_SECRET`: A secret used to encrypt session data.
- `HOST`: The hostname or IP address of the server (default: localhost).

## API Reference


## Contributing

If you would like to submit a bug fix or new feature, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push your branch to your fork and submit a pull request.

## License

The Realtime Code Editor is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
