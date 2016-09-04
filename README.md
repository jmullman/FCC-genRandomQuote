# FCC-genRandomQuote
Random Quote Generation Machine, per Free Code Camp [challenge] (https://www.freecodecamp.com/challenges/build-a-random-quote-machine).

## Objective
 Build a CodePen.io app that is functionally similar to [this] (https://codepen.io/FreeCodeCamp/full/ONjoLe/).
 
## Rules
1. Don't look at the example project's code. Figure it out for yourself.
2. Fulfill the below user stories. Use whichever libraries or APIs you need. Give it your own personal style.

## User Stories
1. I can click a button to show me a new random quote.
2. I can press a button to tweet out a quote.
  * Pulled this from rolling over the twitter link on the example page:
  ```
  https://twitter.com/intent/tweet?hashtags=quotes&related=freecodecamp&text=%22I%20feel%20the%20need%20-%20the%20need%20for%20speed!%22%20Top%20Gun
  ```
  * Based on the above, I can assume that I need the following:
    1. A base URL: `https://twitter.com/intent/tweet`
    2. Followed by a hashtag: `?hashtags=quotes`
    3. Followed by a 'related' tag: `&related=freecodecamp`
    4. Then the quote: `text=%22I%20feel%20the%20need%20-%20the%20need%20for%20speed!%22%20Top%20Gun`
  * The actual documentation for tweeting from a webpage is [here] (https://dev.twitter.com/web/tweet-button)
