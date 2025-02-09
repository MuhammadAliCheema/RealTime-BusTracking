Here's the rephrased text to avoid plagiarism:

# Real-Time Bus Tracker Exercise
M.I.T xPRO Real-Time Bus Tracker Exercise
Real-Time Bus Tracker Exercise: [link](https://github.com/MuhammadAliCheema/RealTime-BusTracking.git)

___

The Real-Time Bus Tracker Exercise is the final project of the ninth week in the MIT xPRO Full Stack Development with MERN course.

## Project Description
The Real-Time Bus Tracker allows you to view the locations of buses on Boston's route one in real-time. This route passes by MIT and Harvard universities. The tracker uses the MBTA API to update bus locations every 15 seconds. Buses traveling north to south are shown in blue, while those heading south to north are in red. This project primarily uses HTML.
___

## How to Run
After cloning the repository, you will find three main files and two images:<br>
- `index.html`
- `styles.css`
- `mapanimation.js`
- `Images/Blue.png`
- `Images/Red.png`

The `index.html` file includes the Google Maps API and sets up the DOM with a map. The `mapanimation.js` file uses the MBTA API to fetch JSON data for the Boston route and adds markers with red or blue icons depending on the bus direction. The `styles.css` file styles the information box using the classes `.headline` and `info-container.wow.fadeInDown.bordered`.
___

## Future Improvements
- Add bus stop locations and include more routes between Harvard and MIT.
- Provide more information about each bus, such as whether it is full or empty.
- Enable users to create custom routes from one stop to another.
- Switch from Google Maps to the Mapbox API.
- Update code to use `let` and `const` instead of `var`.
___
## License information
MIT License

Copyright (c) [2024] [Muhammad Cheema]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
