![icon](https://raw.githubusercontent.com/dyazincahya/ptl-js/main/plt-icon.png)
# ptl.js
PTL is an acronym from Pages Transition Loader. ptl.js is made with `Vanilla JS` or what we usually call `Pure Javascript`

### How to use it?
 1. Load the vanilla-js-pages-transition-loader.min.js script in your document.
 ```html
<script src="plt.min.js"></script>
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
