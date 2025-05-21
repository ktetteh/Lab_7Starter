1. I would choose #1, within a GitHub action that runs whenever code is pushed, because it helps in building a seamless workflow and supporting CI/CD
2. I would not use it to check if a function is returning the correct output, because checking to see if a function is returning the correct output is more suited for unit testing, not E2E in this instance, which focuses on testing user movements.
3. The difference between navigation and shapshot mode is that navigation only analyzes a single page load while snapshot mode analyzes the page in a certain state its in, with naviation mode giving us insights into how the JS is affecting the site and how it can be improved upon, while snapshot mode tests the most on accessibiliy features (20 compared to 4 or 5 in the other categories).
4. One thing that can be improved upon in the CSE 110 shop site based on the Lighthouse results is to properly add a <meta name="viewport"> tag with width or initial-scale, as that not only optimizes the site for mobile device screen but also prevents a 300 ms delay to user input, which if allowed lets our app feel sluggish to our mobile users (likely a huge population). We can also add "preconnect" or "dns-prefetch" resource hints to establish earlier connections to third-party origins, and properly size the images to the scale they are viewed at to improve the load time and save cellular data.





