# Dialog Box Tutorial

Dialog boxes are used extensvely across many websites. You may use it to ask a user to sign up for a newsletter, or to ask them to login to your website. But custom making dialog boxes can be a time consuming process. You may have to style an array of ```<div>``` tags, style them, and use various JavaScript methods to show and hide the dialog.

Luckily, there's a solution. The HTML ```<dialog>``` tag is used to easily create dialogs and lightboxes. With JavaScript, you can call simple methods to open and close the dialog.

### Setting up a Modal

The basic code for a dialog is as follows.

```javascript

<dialog>
  <p> Hello <p>
</dialog>

```

You may include various HTML structures within the ```<dialog>``` tag. You may add a form, a table, a list, and so much more.

### Opening and Closing a Dialog

```javascript

// Opening the Dialog
const dialog = document.querySelector('.dialog');

window.onload = function() {
  dialog.show();
}

// Closing a Dialog
const dialog = document.querySelector('.dialog');

window.onload = function() {
  dialog.close();
}

```

You may also add eventListeners and conditional loops to initiate the opening and closing of the dialog

### Conclusion

With these code snippets, you will be able to create a simple dialog box to embed in your website. To view some examples, check out some of the files on this repository.

### References

- [] (https://usefulangle.com/post/110/html-dialog-element-to-create-modal-lightbox)
- [] (https://www.geeksforgeeks.org/html5-dialog-tag/)
- [] (https://towardsdev.com/you-can-finally-make-use-of-the-html-dialog-element-f4b7c591b1b6)
