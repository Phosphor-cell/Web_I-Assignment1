# Planning Document (Tentative)

**Jarod**:  
- Update the HTML required for the given layout
- Create and work on normalize.css
- Analyze the website for accessibility issues
  

**Dev**:
- Update the CSS to match the given layout
- Fix any accessibility issues that we come across

---

# Issues identified through manual and automated analysis:

**Perceivability**: An accessibility issue that we discovered was that when adding figure caption for accessibility, the text-colour was black which had a low contrast with the header colour (red), we fixed this by changing the text to white. The webpage is already organized, links are underlined, and all images have titles, alt text and captions with the exception of the logo which does not have a caption.

**Operability**: An accessibility issue that we identified was that there was no keyboard navigation. We fixed this by allowing the user to navigate our website using the 'Tab' key as well as styled our 'focus ring' to make it colour-blind friendly. We did not implement a 'Skip to Main Content' solution as our navigation bar only has three items, however as we continue to add more webpages and our navigation bar increases in size, it would be something we would implement for accessibility users to improve keyboard navigation and bypass repetitive content.
  
**Understandability**: An accessibility issue that we encountered was that the font size was the same for every screen size. This can cause issues because fixed font sizes may appear too large on smaller devices and too small on larger devices. We fixed this issue by adjusting the font size depending on the screen size (Larger devices have a larger font size and smaller devices have a smaller font).

**Robustness**: An accessibility issue that we encountered was that different browsers may have not render the elements consistently. We fixed this by creating a normalize.css file to fix browser inconsistencies and enhance accessibility.