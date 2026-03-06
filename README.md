# Ecommerce Android App (APK Releases)

This repo is only for sharing APK builds of my Android ecommerce app. I’m a CSE student (24), and this is one of my personal projects that connects a Flutter app with a WordPress-based store through a small Node/Express middle layer for security. The backend is running on a VPS (cloud), not on this machine.

## What the app does
- Browse products from the main WordPress site
- View product details with images, price, and stock info
- Add to cart and place orders
- Basic account features (login, order history)

## How it works (high level)
- **Frontend**: Flutter Android app
- **Main site**: WordPress (acts as the core ecommerce system)
- **Middleman API**: Node/Express service (located in a `server` folder in the full project, runs with npm)
- **Hosting**: API is deployed on the same VPS as the WordPress site

## Download & install
- Go to the **Releases** section and download the latest APK.
- On your Android phone: Settings → Security → allow “Install unknown apps”.
- Install the APK and open the app.

## Notes
- This repo does **not** contain source code.
- The APKs are for testing/demo purposes.
- If you face a login or checkout issue, it’s likely related to the API or WordPress server status.

## Contact
If you want to discuss the project or need a test account, reach out to me.
