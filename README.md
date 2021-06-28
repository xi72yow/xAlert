# xAlert

## Demo

JS script for Alerts

![](xAlertDemo.gif)

[Here](https://xi72yow.github.io/xAlert/demo.html) you can see the result.

## Setup

To run this project, include the script like:

    <script src="./path/to/xAlert.min.js"></script>

or

    <script src="https://xi72yow.github.io/xAlert/xAlert.min.js"></script>

## Usage

### Hints

You can only Use 20 charakters in msg. 

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

//set slots on rezize
window.addEventListener("resize", xAlerts.setSlots);
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
