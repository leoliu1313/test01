# test01

http://en.wikipedia.org/wiki/Responsive_web_design
Responsive web design (RWD)
Mobile first, unobtrusive JavaScript, and progressive enhancement based on browser-, device-, or feature-detection

http://en.wikipedia.org/wiki/Unobtrusive_JavaScript
Unobtrusive JavaScript
1. [Separation] [Usability] To separate JavaScript from HTML markup, as well as keeping modules of JavaScript independent of other modules.
2. [Graceful degradation] Unobtrusive JavaScript should degrade gracefully - all content should be available without all or any of the JavaScript running successfully.
3. [Accessibility] Unobtrusive JavaScript should not degrade the accessibility of the HTML, and ideally should improve it, whether the user has personal disabilities or are using an unusual, or unusually configured, browser.
from
<input type="text" name="date" onchange="validateDate()" />
to
<input type="text" name="date" id="date" />
window.onload = function() {
    document.getElementById('date').onchange = validateDate;
};

http://leoliu1313.github.io/test01/
