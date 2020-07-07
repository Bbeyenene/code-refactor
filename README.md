# Code-Refactor
The Horizon social media web page is refactored on 07/07/2020 to meet web accessibilty standard. The CSS selectors and properties are consolidated, the semantic structure of the HTML elements is well organized, and comments are included before each element or section of the page.

# HTML semantic
The structure of the web page was in a sirios of divs, now the whole `body` is organized into:
 `header` that include `nav`
 `section` that include `main` content and `aside` benefits.
 `footer`. This will help the difernt teqnologies to identify the parts of the web page easily.
Moreover, divs that will be styled the same way to are given the same name.

# CSS 
1. Selectors Used:- once the cleaned up the styling got easer to manuplate mainly the `header`, `section`, `aside` and `footer` followed by styling what ever is inside. Now, the web page is flexible with flexible divs.
2. Sequential Order:- there was too much code writing `i.e 200 lines` and now it is cleaned up to `135 lines`.

# Tip
Media Query is added to the styling to make the wab page fully responsive to different screen size. In divices that have max-widith: 800px; the background image shrink to half of its original size, the section that is the main and aside contents aalign in a column. At max-width: 675; the head topic and the nave align in column and center; and the topic and paragragh of the main align bellow the img.

A reset code(`reset.css`) is added, this clear any existing styling to fit any computer machines follower by the `style.css`.