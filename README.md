# kofi-darkmode
A community contributed dark theme for Ko-fi

The Ko-fi dark theme is maintained by members who are willing to contribute to the project (Mainly me)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/flleeppyy)


# Notes
- Follow suggestions in newsfeed have a weird box shadow, especially on hover. Ref: `.kfds-hz-follow-suggestion-box`
- Colors should be organized with variables instead of figuring out what color looks nice
- Some colers may not show properly if the ko-fi user has a customized color theme. There is no way around this unless there is a variable for the user's custom color.

# How do I install this theme
Currently, we haven't exactly worked out the details with Ko-fi on integrating a public beta, so for now, do the following:  

For Google Chrome users:
* Use an extension like [UserCSS](https://chrome.google.com/webstore/detail/user-css/okpjlejfhacmgjkmknjhadmkdbcldfcb), [Styler](https://chrome.google.com/webstore/detail/styler/bogdgcfoocbajfkjjolkmcdcnnellpkb/), [CSS and Javascript Injection](https://chrome.google.com/webstore/detail/css-and-javascript-inject/ckddknfdmcemedlmmebildepcmneakaa), or [CSS JS injector](https://chrome.google.com/webstore/detail/css-js-injector/gamgadbdliolbhjdcfjjpjfjhgfnckbp)  

For Firefox users
* Use [Stylus](https://addons.mozilla.org/firefox/addon/styl-us/), or [CSS Override](https://addons.mozilla.org/en-US/firefox/addon/css-override/?src=search)  

1. Make sure your on [Ko-fi's website](https://ko-fi.com) otherwise you'll be applying the css to a page you didn't intend to.
2. Insert the following code into the CSS text area (Depends on the extension, but it should be easy to figure out)

```css
@import url("https://flleeppyy.github.io/kofi-darkmode/dark.css")
```
3. Then hit run (If there is a button for it; Some extensions may apply instantly)


# How do I contribute?
1. Fork this repository
2. Make your changes in your forked repository
3. Run `yarn css:build`/`npm run css:build` or `css:watch` to build the css live while making changes.
4. Make a pull request,
5. Describe your changes, take screenshots of before and after of what your changes have affected
6. Done!

Please make sure you build before commiting.


# Screenshots

## Home manage page
![Home manage page](https://raw.githubusercontent.com/flleeppyy/kofi-darkmode/master/screenshots/manage_page.png)

## Newsfeed page
![Newsfeed page](https://i.imgur.com/hSnMCur.gif)

## Explore page
![Explore Page](https://raw.githubusercontent.com/flleeppyy/kofi-darkmode/master/screenshots/explore.png)

## User Page
![User page](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/user_page.png?raw=true)

## Recieved and Given
![Recieved and Given](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/Recieved_and_given.png?raw=true)

## Settings - Profile
![Settings - Profile](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/settings_profile.png?raw=true)

## Settings - payment
![Settings - payment](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/settings_payment.png?raw=true)

## Settings - page
![Settings - page](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/settings_page.png?raw=true)

## API page
im just adding this cause i wanna show off the cool code box i added lol
![API page](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/API.png?raw=true)

## Gold Page
Warning: Long screenshot
![Gold Page](https://github.com/flleeppyy/kofi-darkmode/blob/master/screenshots/gold_page.png?raw=true)

