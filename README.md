# hometown-homepage

![Preview image of the final Hometown Homepage](images\project-hometown-homepage.jpg)

## Project Overview 
"Hometown Homepage" is a website for selling a traveler on a visit to my hometown Bothell, Washington. Basic HTML, and CSS are both demonstrated with. Stretch goals were completed and functionality was expanded beyond the original scope. Added functionality includes highlighting things to do on hover, adding multiple pages and adding return navigation that also utilized hover mechanics.


## Features

__Requirements:__ <br/>
- Build it from "scratch" (Figma file provided)
- Make sure you use:
    - Classes
    - Flexbox
    - Background-image
    - The color palette

__Stretch Goals:__ <br/>

- Make it about your own hometown, country, or whatever place you like
- Use a different color palette
- Add a Google Font
- Find a way to use :hover
- Add a whole new section

</br>

**My Implementation:**<br/>

- I started by replacing all of the content on the original site with information 

## Challenges and Learning

### DOM Element Initialization Order

I received an error indicating that the boardClock wasn't initialized before it was access. With clarification from ChatGPT, I learned that this can occur if the JavaScript code runs before the DOM is fully constructed. The solution to address this issue was to set the script tag for the JavaScript just before the closing body tag in the HTML. This ensured that the DOM elements were created before the code was run and resolved the issue.

### Calling SetInterval

I received an error that I had called setInterval incorrectly. With some assistance from ChatGPT, I learned that I should not pass countDown as a function call but as a reference to the function. I made this change by removing the () from the function within the setInterval parameter list. Before doing so, the countDown function would be referenced immediately, rather than as called for by the setInterval function.

### Clearing SetInterval

While reviewing this information, ChatGPT also highlighted the importance of using clearInterval() to ensure that multiple countdown instances did not exist simultaneously.


## Installation
Install the dependencies and run the project

npm install<br/>
npm start<br/>
Head over to https://vitejs.dev/ to learn more about configuring vite

## Contributing
Feel free to fork this project and submit pull requests. You can also open issues for any bugs you find or enhancements you think would be useful.

## Authors
John Okleberry - [Github profile](https://github.com/John-Okleberry)


About Scrimba
At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜 If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉 The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

Our courses
The Frontend Career Path
Become a Scrimba Pro member
Happy Coding!
