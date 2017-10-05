# BTS-Theme

Rather than having to compile a web wallet on ubuntu, the plan is to compile the sass into css then apply the newly generated css within the web browser.

By reducing the difficulty of theming, anyone will be able to create a BTS theme.

## Tools used:

* Sublime text w/ packages:
  * [Sass](https://packagecontrol.io/packages/Sass)
  * [Sass Build](https://packagecontrol.io/packages/SASS%20Build) - compile sass into css.
  * [LiveStyle](https://packagecontrol.io/packages/LiveStyle) - for loading the compiled css into the web browser.

## Note:

* The Bitshares UI components within this repo are likely to change, so forking the [bitshares-ui](https://github.com/bitshares/bitshares-ui/) repo and [grabbing the latest SASS files](https://github.com/bitshares/bitshares-ui/tree/staging/app/assets/stylesheets) is advised.
* You don't need to use sublime text, as long as you've got some method of building the app.css from the sass components and a method of viewing the changes within the browser you're fine.