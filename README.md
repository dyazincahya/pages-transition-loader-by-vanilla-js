![icon](https://raw.githubusercontent.com/dyazincahya/ptl-js/main/icon.png)
# ptl.js
PTL is an acronym from Pages Transition Loader. ptl.js is made with `Vanilla JS` or what we usually call `Pure Javascript`

### Demo 
[See Here](https://dyazincahya.github.io/ptl-js/example/)

![demo-image](https://raw.githubusercontent.com/dyazincahya/ptl-js/main/screenshot.png)

### How to use it?
 1. Load the vanilla-js-pages-transition-loader.min.js script in your document.

**Load via Local File**
 ```html
<script src="plt.min.js"></script>
```

**Load via CDN**
 ```html
<script src="https://cdn.jsdelivr.net/gh/dyazincahya/ptl-js@main/ptl.min.js"></script>
```

2. Customize the loading indicator.
```javascript
let settings = { 
  opacity: 0.9, 
  backgroundColor: "#FFFFFF", 
  color: "#333333", 
  strokeWidth: 10, 
  timeOnScreen: 100, 
  loadingAnimationSpeed: "1s", 
  loadingAnimationTimingFunction: "linear", 
  loadingAnimationIterationCount: "infinite", 
  loadingText: "Loading...", 
  loadingTextSize: "32px",
}
```

Detail information about the settings
| Option | Default | Documentation |
|---|---|---|
| opacity | 0.9 | [see more](https://www.w3schools.com/css/css_image_transparency.asp) |
| backgroundColor | #FFFFFF | [see more](https://www.w3schools.com/cssref/pr_background-color.php) |
| color | #333333 | [see more](https://www.w3schools.com/cssref/css_colors.php) |
| strokeWidth | 10 | [see more](https://www.w3schools.com/graphics/svg_stroking.asp) |
| timeOnScreen | 100 `(milisecond)` | [see more](https://www.w3schools.com/jsref/met_win_settimeout.asp) |
| loadingAnimationSpeed | 1s `(second)` | [see more](https://www.w3schools.com/cssref/css3_pr_animation-duration.php) |
| loadingAnimationTimingFunction | linear | [see more](https://www.w3schools.com/cssref/css3_pr_animation-timing-function.php) |
| loadingAnimationIterationCount | infinite | [see more](https://www.w3schools.com/cssref/css3_pr_animation-iteration-count.php) |
| loadingText | Loading... | just plain text |
| loadingTextSize | 32px | [see more](https://www.w3schools.com/css/css_font_size.asp) |



### Credit : 
> This repo is a fork from [https://www.cssscript.com/pages-transition-loader/](https://www.cssscript.com/pages-transition-loader/)

### License
[MIT License](https://github.com/dyazincahya/ptl-js/blob/main/LICENSE)
