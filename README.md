To get it to compile:

1. Remove the tilde from line 5 of @momentum-ui/core/scss/momentum-ui.scss

2. Remove the tilde from line 3483 of @momentum-ui/core/scss/settings/settings.scss. (If you run `npm start` now it will throw a different error)

3. Use the @use version instead in styles.scss. Ie. uncomment line 6, 10, 15 and comment out the lines above each of them.
