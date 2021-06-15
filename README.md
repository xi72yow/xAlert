# xAlert

JS script for Alerts

![](xAlertDemo.gif)

## Setup

To run this project, include the script like:

    <script src="xAlert.min.js"></script>

or

    <script src="https://xi72yow.github.io/xAlert/xAlert.min.js"></script>

## Demo

[Here](https://xi72yow.github.io/xAlert/demo.html) you can see the result.

## Usage

### Alerts

```javascript
let xAlerts = new xAlert();

let duration = 2000;

//send info
xAlerts.send("info msg", "dark", duration);

//send error
xAlerts.send("error msg", "prime", duration);

//send warning
xAlerts.send("warning msg", "second", duration);
```

### Tooltips

```html
<span data-xTip-l="zorro kappa">tooltip left</span>
<span data-xTip-r="url here!">tooltip right</span>
<span data-xTip-b="zorro kappa">tooltip bottom</span>
<span data-xTip-t="url here!">tooltip top</span>
```

## ToDo

- handle to much alerts
