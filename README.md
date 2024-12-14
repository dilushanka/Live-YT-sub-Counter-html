# Youtube Live Subscribe Counter
Demo Here -- https://www.helalk.com/p/about.html

## Overview
**Youtube Live Subscribe Counter** is a web application that allows users to display the real-time subscriber count of a Youtube channel in a web page. This application uses HTML, CSS, JavaScript, and Google Youtube API to fetch the subscriber count data and display it on the web page.

## Features
* Displays real-time subscriber count of a Youtube channel.
* Updates the subscriber count automatically without the need to refresh the web page.
* Customizable styles and display options.
* Can be easily integrated into any web page using a simple JavaScript code snippet.

## Usage
To use the Youtube Live Subscribe Counter in your web page, follow these steps:

1. Open **script.js** file in your Code editor.
2. Replace the *UCm1_-vkonHv3nQuvux5xtDw*  following code to the Your YT channel ID:
```js
const channelIdCarry = 'UCm1_-vkonHv3nQuvux5xtDw'
```
3. Replace **ApiKey** with your Google console YT API key.
```js
const urlCarry = `https://www.googleapis.com/youtube/v3/channels?part=statistics&id=${channelIdCarry}&key=ApiKey`;
```
## Credits
The Youtube Live Subscribe Counter was created by [Dilushanka](https://github.com/dilushanka/).

## License
The Youtube Live Subscribe Counter is released under the [MIT License.](https://opensource.org/licenses/MIT)
