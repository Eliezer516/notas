---
title: "ocultar el navbar al hacer scroll"
---

```javascript
let prevScrollPos = window.pageYOffset; // Store the current scroll position

window.onscroll = function() {
  const currentScrollPos = window.pageYOffset; // Get the new scroll position

  if (prevScrollPos > currentScrollPos) {
    // Scrolling up: show the navbar
    document.getElementById("navbar").style.top = "0";
  } else {
    // Scrolling down: hide the navbar
    document.getElementById("navbar").style.top = "-80px"; // Adjust this value to match your navbar's height
  }
  prevScrollPos = currentScrollPos; // Update the previous scroll position
}
```