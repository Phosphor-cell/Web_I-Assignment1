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

**Perceivability**:  

**Operability**: An accessibility issue that we identified was that there was no keyboard navigation. We fixed this by allowing the user to navigate our website using the 'Tab' key as well as styled our 'focus ring' to make it colour-blind friendly. We did not implement a 'Skip to Main Content' solution as our navigation bar only has three items, however as we continue to add more webpages and our navigation bar increases in size, it would be something we would implement for accessibility users to improve keyboard navigation and bypass repetitive content.
  
**Understandability**: An accessibility issue that we encountered for understandability was that the font size was the same for every screen size. We fixed this issue by adjusting the font size (larger screens require larger text size).

**Robustness**: An accessibility issue that we encountered was that different browsers may have not render the elements consistently. We fixed this by creating a normalize.css file to fix browser inconsistencies and enhance accessibility.