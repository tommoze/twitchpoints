# Get +50 twitch points by automising click process in Chromium based browsers

Open Developer Tools by ```right mouse click => Inspect```

```Javascript
setInterval(() => {
  var btn = document.querySelector(
    ".tw-button.tw-button--success.tw-interactive"
  );
  btn && btn.click();
}, 5000);
```
