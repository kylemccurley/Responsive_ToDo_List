# Todo List

## Notes
- The Media Queries seem to respond to window resizing, but do not respond when the phone screens are used in the inspector tools. I tried to include the extra parameter `screen` to see if it would fix the problem, but it did not. Mobile display is shown when the browser is resized to <= 768px in width.
- This may be unconventional, so I will make note. I used a large box shadow as the overlay for the modal.
- I used the given dimensions from the design file height (818px).
- The modal can be closed by toggling the Item 1 icon.

## Correction Log:

- Moved the <form> for the modal and the checkbox to the beginning of the <main> section; outside of the <td> tag.
- Increased the modal by 20% of the previous values (w: 690px, h: 420px).
- Added a label for the description textarea.
- All text in <label>'s are bold-faced. I initially entered `bold` for the font-family value, but the weight seemed to intense. So, I brought the value down to 400.
- Increased the top padding for text area to 10px, kept the padding value of 5px for the area of the textbox.
- Increased font-size to 1.1rem for the `Save` and `Mark as Completed` buttons.
- 
