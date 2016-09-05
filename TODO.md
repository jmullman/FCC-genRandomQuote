# TODO

**genRandomQuote**

## Steps
1. Conceptual work
2. Wireframing
3. Execution
4. Repeat

## Conceptual work
* The application is modular.
  * Each module of application does one thing, and does it well.
    * quoteGetter.js: Retrieves quote from an URL, returns JSON with quote and author.
    * quotePrinter.js: Testing of quoteGetter, prints the values of the JSON returned from quoteGetter.
    * quoteFormatter.js : Accepts JSON from quoteGetter and returns a string containing a `<blockquote>` containing the value of quote, along with a `<footer>` containing the value of author.
    * genTweet.js: Prepares a string that conforms to Twitter's [web intent API](https://dev.twitter.com/web/tweet-button/web-intent).
    * genRandomQuote.html: The markup responsible for displaying the application.
    * themeA.css, themeB.css, themeC.css: Styles the entire application.
      * themeA: Light theme.
      * themeB: Dark theme.
      * themeC: High-contrast theme.
## Wireframing

Initial application development will revolve around quoteGetter and quotePrinter. It will be cli-based, for quick prototyping and reuse.

Once that is satisfactory, quoteFormatter will be drawn up, with a test of `console.log()`.

genRandomQuote.html will be very simple with no theme, to begin with, just simple text returned by a button that is pressed to generate a random quote. This will be iterated over as theming as added, giving better medium to the content.
