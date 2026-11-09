# Zing Arcade

Zing is a web portal for playing games, watching TV, and connecting with the community. It includes a responsive layout for phones and computers.

> **Status:** Zing is under active development. Features and availability may change.

## Features

- **Games and TV:** Browse built-in games and TV content from one lobby.
- **Community games:** Signed-in users can publish games using a URL or HTML code.
- **Social features:** Like, comment on, and share games, or join the global chat.
- **User profiles:** Sign in with Google and customize your display name and profile picture.
- **Zing AI (beta):** Generate images, create code, and get help improving code.
- **Display modes:** Choose a layout for mobile or desktop.

## Getting started

The app is currently a standalone HTML page named [`Code`](./Code) in the repository root. Serve it with a web server and open it in a browser; opening it directly with a `file://` URL may not work.

Sign-in and real-time data require Firebase configuration. Zing AI uses a separate `/ai` endpoint, which must be configured and deployed for those features to work.

## Security note

Firebase web configuration is visible in the browser. Protect your data with appropriate Firebase Security Rules rather than relying on client-side checks. The AI endpoint should validate requests and keep any secret credentials on the server.

## Contact

Created by [Zain](https://www.linkedin.com/in/zain-dev-6b450244a/).
