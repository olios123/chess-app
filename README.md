![Logo](https://raw.githubusercontent.com/olios123/chess-app/refs/heads/main/Screenshot-1.png)

# Chess App
Chess App is a simple chess application that uses other libraries and combines everything into one whole. The website is based on a socket-based client-server system.

## Screenshots

![Screenshot](https://github.com/olios123/chess-app/blob/main/Screenshot-2.png)

## Requirements
- NodeJS v20.12.1
- jQuery 3.7.0

## Instalation

The project already has a ready-made **Node.JS** package
Run this command in the console to install the modules necessary for the application to run.

    npm i

## Usage

The `server/config.js` file contains the application configuration.
```javascript
module.exports = {
    port: 3750,
    database: {
        host: 'HOST',
        port: 3306,
        user: 'USER',
        password: 'PASSWORD',
        database: 'DATABASE'
    }
}
```
The standard application port is **3750**, you can change it to one that is not currently occupied.

> [!WARNING]
> Do not use ports like: **80, 21, 587, 3306**, etc...

---
To run the application, enter this command in the console.
You should then see `Server listening on port {PORT}`. This means that the server is working properly.
    
    npm run server


# Development plans
- Adding English language
- Chessboard, pieces and page customization
---
> [!NOTE]
> The project uses other libraries such as [chess.js](https://github.com/jhlywa/chess.js) and [chessboardjs](https://github.com/oakmac/chessboardjs/)
