# my2-jeedipally
# Pranathi Reddy Jeedipally
###### Favourite Vacation Spot - Switzerland
**Switzerland** is my favourite vacation spot because it is known for its mountains, lakes, valleys, and specially for chocolates.<br> Swiss beauty changes with the seasons, **Spring in swiss has colourful blooms**. Swiss has the best scenic view and greenery. 
---
# Activites in Switzerland
1. Hiking
2. Stargazing at the mountains
3. Shopping

# Food in Switzerland
* swiss chocolates
* Cakes and Pastries
* croissant

click here [MyStats.md](MyStats.md) to view the Mystats data.
---

### Sports Table

Sports is the best way to maintain the physical fitness and personal growth.
below table describes about 4 different sports and there benifits.

| Name of the Sport | Reason | No. of hours spent in avg per week |
| :---: | :---:| :---:|
| Table Tennis | Table Tennis is a indoor game, improves hand-eye coordination and burns calories| 6-8|
| Badminton | Badminton reduces rissk of life threatening diseases, helps in reducing stress and anxiety | 8-10 |
| Hiking | Hiking is the best way to connecct with the nature, reduces stress and improves the muscles strength | 2 |
| Cycling | Cycling is good for cardiovascular fitness, muscle toning | 6 |

---

### Pithy Quotes
> " Everything is theoretically impossible, until it is done." - *Robert A. Heinlein.*

> "Science and everyday life cannot and should not be separated." - *Rosalind Franklin*

---

### Code Fencing

> Relevant question on stack overflow : [quick-link to the article on Stack overflow](https://stackoverflow.com/questions/35221259/custom-radio-button-using-css)

```
/*
  Hide the original radios and checkboxes
  (but still accessible)

  :not(#foo) > is a rule filter to block browsers
  that don't support that selector from
  applying rules they shouldn't

*/
li:not(#foo) > fieldset > div > span > input[type='radio'],
li:not(#foo) > fieldset > div > span > input[type='checkbox'] {
  /* Hide the input, but have it still be clickable */
  opacity: 0;

  float: left;
  width: 18px;
}


li:not(#foo) > fieldset > div > span > input[type='radio'] + label,
li:not(#foo) > fieldset > div > span > input[type='checkbox'] + label {
  margin: 0;
  clear: none;

  /* Left padding makes room for image */
  padding: 5px 0 4px 24px;

  /* Make look clickable because they are */
  cursor: pointer;

  background: url(off.png) left center no-repeat;
}

/* Change from unchecked to checked graphic */
li:not(#foo) > fieldset > div > span > input[type='radio']:checked + label {
  background-image: url(radio.png);
}
li:not(#foo) > fieldset > div > span > input[type='checkbox']:checked + label {
  background-image: url(check.png);
}
```
snippet from css-tricks using code fencing : [quick-link for the snippet source](https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons/)