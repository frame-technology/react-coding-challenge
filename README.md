# Frame.ai Coding Challenge

> Welcome to the Frame Coding Challenge!


## Overview

To complete this challenge, you will need to write a simple [React](https://facebook.github.io/react/) web app, and provide us the source files to be built.

The purpose of this challenge is to assess your **skills and approach to composing a simple web app** given a set of screens and an API feed.  We will also assess the **generated HTML, CSS, and JS** output.

This challenge is expected to take about 1-3 hours.


## The Challenge

It's a pretty simple [subreddit](https://en.oxforddictionaries.com/definition/subreddit) viewer. You will allow a user to enter a subreddit name, and then you will render the top entries of that subreddit stream.

For example, if I entered `cats` into your app I would see your novel display of the [cats subreddit feed](https://www.reddit.com/r/cats/). Using the provided screens as inspiration, you'll need to build a set of React components to render the app.  You'll also need to request a JSON feed, filter that data, and use the relevant fields.



Although this is a basic exercise, we'll be looking for **simple, well-designed and tested code** in the submission.

Please include a `README` with setup instructions, and any tests or other documentation you created as part of your solution.

Also, add the following info to your `README`:

* How did you decide which technologies to use as part of your solution?
* Are there any improvements you could make to your submission?
* What would you do differently if you were allocated more time?

## Details

The deployable solution should be built in a folder named **`dist`** with an entry point file of **`index.html`**.

Please create components for each part of the page (eg. header, content, footer, etc).
Assets are provided in the `assets` folder.

The pages should also be usable (but not polished) on mobile devices.

You can assume that you do not have to support legacy browsers without features such as `fetch` or `flexbox`.

**Note**: all subreddits can be read by appending `.json` to the end of the url. So the Cats subreddit at: `https://www.reddit.com/r/cats/` can't be consumed as a json blob at `https://www.reddit.com/r/cats.json`

### "Main" Page

Refer to the [screens/1-home.jpg](./screens/1-home.jpg) screen.

This will be your `index.html` screen.

You will need to display a tile to capture what subreddit the user would like to view, and a set of tiles that render the results. The results should be concise and visually engaging.

You will also need to handle the loading and error states, of fetching the JSON feed:

* "Loading" state [screens/1.1-loading.jpg](./screens/1.1-loading.jpg)
* "Error" state [screens/1.2-error.jpg](./screens/1.2-error.jpg)


## FAQ

### What language, framework, build tool... should I use?

You may use whatever you like as long as the solution is built using [React](https://facebook.github.io/react/).


## Useful Links

* [Bitbucket](https://bitbucket.org/) - Source code hosting, with free private repositories for small teams.
* [Google Fonts - Raleway](https://fonts.google.com/?selection.family=Raleway)
* [React](https://facebook.github.io/react/)
