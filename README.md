
# Vanilla-JS-Alert

A simple JS (with html and css) function to show alert modals. If you are looking for some more flexibility with full prompts look at my [Vanilla-JS-prompt](https://github.com/lecoa/Vanilla-JS-Prompt) project.


## Installation

To use this function you only need to follow these four steps:

1. Download the alert.js and modal.css to your project.
2. Link to the alert.js and modal.css in your html file.
3. Add the content of modal.html to the bottom of the body of your html file.
4. Start calling the show_alert(); function. See below for examples.

## Usage
Open the index.html file to see examples in action

The function with parameters
```javascript
show_alert(title, message, btnHide = false, btnLabel = "Close")
```

Example with a custom text lanel for the close button
```javascript
show_alert('Custom close button', 'Close button with custom text label.', false, 'Ok')
```
## Author

- [@lecoa](https://github.com/lecoa)

