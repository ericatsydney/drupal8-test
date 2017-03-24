# Drupal 8
> Testing on Drupal 8's admin UI operation and custom module building.

## Time spent on the task

- Three and half hours for Task 1, 2, 3, 4 and 5.1  
- Half an hour for task 5.2
- Twenty mins for task 5.3

## Linting Tools

Using `phpcs` for php linting.

These are the [configuration files](https://gist.github.com/ericatsydney/b5e62ef00b4eb80c2b0bd3d80d9b1932) I am using in the NeoVim.

## Drupal.org account

This is the [account link](https://www.drupal.org/u/ericgxtan). Mainly I use this account to search and check the issues and posts.

## Recent project

- [3dcraft](https://github.com/ericatsydney/3dcraft-drupal): Use Drupal7 + threejs for my 3D printing stuff.
- [My Baby Journal](https://github.com/ericatsydney/mybabyjournal): Use Laravel + Reactjs to make a photo albumn web app.
- [Personal Blog](http://ericatsydney.github.io/geek/2016/05/24/drupal-hook.html): Writing blog and technical notes for myself reference.

## Some side notes

- Use Drupal 8.2.7 in this testing. 
- Local environment is Acquia Dev Desktop for Mac. 
- Run testing on Chrome and Firefox.
- Here's [the link](/modules/custom/xvt_drupal8_test) to the module xvt_drupal8_test (fixed a typo in instruction)
- For task 4.2, we need to `Import Changes` in feature to make title field shown on the system form, as the new field change the original field sequence.
- For task 5.3, I was planning to write a custom template with the message variable inside and use preprocessor to pass in the message value dynamically, because I thought the `drupal_set_message` cannot be shown to anonymous user. But I found out the Drupal message is working for anonymous user as well, so save a lot of time.
- Use Drupal 7 flavour - `hook` API in the custom module building.
- As it's my first time to use Drupal 8 for development, supprised with `drush cc` and `dpm` is depricated, but good to know `drush cache-rebuild` and `kint()` are the replacement.

