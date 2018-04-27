# idai-cookie-notice

Simple JS library for creating a notice that cookies are used on the website.

The library handles displaying the message and saving the fact in a cookie that the user
gave her consent by clicking the dismiss-button. The message is shown again after 30 days.

## Installation

    npm i idai-cookie-notice --save

## Usage

Include `idai-cooke-notice.js` in your HTML and call

    IDaiCookieNotice.init();

on your main page. The URL to the privacy policy may be given as an argument to `init()`.

## Styling

Styling uses bootstrap classes but can be customised using CSS with the id `#idai-cookie-notice`.
