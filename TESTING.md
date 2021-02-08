# Testing

### W3C HTML Validator

All html written for the site was checked using the HTML Validator on [W3C](https://validator.w3.org/).

- #### index.html

<img src="./markdown-images/w3c-index-validated.png" alt="index.html">

- #### about.html

<img src="./markdown-images/w3c-about-validated.png" alt="about.html">

- #### contact.html

<img src="./markdown-images/w3c-contact-validated.png" alt="contact.html">

### W3C CSS Jigsaw Validator

The Custom CSS `style.css` was validated using [Jigsaw](https://jigsaw.w3.org/css-validator/validator):

<img src="./markdown-images/w3c-css-validated.png" alt="css validated">

### PageSpeed Insights

I ran the deployed site through Google's page speed insights. It recommended that up to 4.8 seconds could be saved by compressing all the images into a modern web format.

To remedy this, I compressed all .jpg files into .webp. This reduced the image size by ~40% and thus helped increase page speed.

For example, I compressed the hero image from `.jpg` to `.webp` and was able to see a 44% decrease in image storage size. This was done for all `.jpg` images to enable faster loading times as recommended.

<img src="./assets/images/readme/comparison.png" alt="comparison">

### Google Lighthouse

Google Lighthouse was used to test many factors of the website, mainly - Performance, Accessibility, Best Practices and Search Engine Optimisation.

<img src="./assets/images/readme/lighthouse.png" alt="performance"/><br />

The test scored very well in all tested factors. Best practices scored an ~80 due to some render-blocking resources. However, upon diving into these resources, I determined they were critical - bootstrap and font-awesome. They needed to stay in the `<head>` tag so the bootstrap grid and icons were available on page-load.

<img src="./assets/images/readme/improvement.png" alt="improvement"/><br />

### Responsiveness Testing

Before every `git push` to the remote branch, the website was checked for responsiveness to ensure no changes made were breaking.

The following breakpoints were tested (w x h):

- **Desktop** - 1920px x 1080px
- **Tablet** - 768px x 1024px
- **Mobile** - 360px x 720px

### User Inputs

The only place a user can input their own data is the contact form. As the scope of this project is front-end, we can only implement client-side input validation. To accomplish this every input `type` was set correctly and given the attribute `required`. So if it was an email type, it would require a valid email.

This covered the following scenarios:

- If the user submits an empty form, an appropriate error message tells them to fill in the appropriate (missing) fields.
- If the email address is invalid, the browser will tell the user to adhere to a certain format.

### Known Bugs

- The Contact Page does not have enough content to enable a scrollbar, when navigating to and from the contact page, the page grows wider / smaller with the absence of a scrollbar. This leads to less than smooth navigation.

- When the device width reaches < 300px, the content starts to get less responsive and stretched.
