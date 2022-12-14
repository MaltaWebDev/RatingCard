# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI).

### The challenge

Users can:

- View the optimal layout for the app depending on their device's screen size. ✅
- See hover and focus states for the five rating score buttons. ✅
- View hover state for the main submit button. ✅
- Select and submit a number rating. ✅
- See the "Thank you" card state after submitting a rating. ✅
- See the correct score displayed in the "Thank you" card state. ✅

### Links

- Solution URL: [github.com/maltawebdev/ratingcard](https://github.com/maltawebdev/RatingCard)
- Live Site URL: [maltawebdev.github.io/RatingCard/](https://maltawebdev.github.io/RatingCard/)

### My solution

- Semantic HTML5 form with 5x radio buttons.
- Form fires a GET request and dispalys results.html on submit.
- CSS preprocessed with SASS mixins and variables.
- Flexbox and Grid to center and space elements.
- Small amount of JS on result page to read and display rating from URL.
- Uses .sr-only utility class to ensure buttons are accessably hidden.
- Form will not fire if none of the inputs are selected.

### Screenshots

#### Normal state

![](./ss/rating-state.png)

#### Hover state

![](./ss/hover-state.png)

#### Checked state

![](./ss/checked-state.png)

#### Submit button hover state

![](./ss/submit-hover.png)

#### Form firing, capturing and displaying rating

![](./ss/thank-you.png)
