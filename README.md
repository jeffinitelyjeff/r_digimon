This subreddit stylesheet is predominantly an adaptation of [Naut 3.1](https://github.com/Axel--/Naut-for-reddit).

## Inspiration

- [/r/pokemon](http://www.reddit.com/r/pokemon)

## Main Customizations

- Enables ["Text Strings" Naut addon](https://www.reddit.com/r/naut/wiki/csstext)
- Enables ["Color Customization" Naut addon](https://www.reddit.com/r/naut/wiki/customcolors) (slightly modified to centralize color tweaks of new elements)
- Adds a hover message to upvote button (to match Naut's downvote hover)
- Tweaks the subscriber/online user display to take up two lines, include a spritesheet image, and fit with [RES 4](http://redditenhancementsuite.com/)
- Hides post actions (share, save, etc.) until hover
- Adds post hover indicator
- Adds custom height banner
- Styles top buttons (hot, new, top, etc.) to match Naut's submit button
- Adds large multi-line user flair
- Moves timestamps to float right

## Minification Process

Reddit restricts stylesheet content to 100kB, and Naut 3.1 in raw un-minified form is about 97kB, requiring almost any adaptation of Naut 3.1 (beyond simple color tweaks) to use minification. This is fine if only one mod ever touches the stylesheet, but can get very messy as soon as there are two cooks in the kitchen. There needs to be a centralized version of the unminified stylesheet which both mods know to modify when they come in with a new change.

This repo stands as a record of changes to mirror reddit's internal record of the minified version. When updating the stylesheet, in the "reason for revision" note, I will include a link to the unminified stylesheet which generated that revision of the minified stylesheet. This way a mod coming in to modify the stylesheet can alawys look up the proper unminified version to modify.
