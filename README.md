<p style="text-align: center">
<img src="./assets/images/logo.png" height="150">
<img src="./assets/images/readme/readme-logo.png" height="80">
<p>

---

Crate O' Wine is a monthly wine subscription that allows customers to receive a new assortment of wines every month to their doorstep.

It was designed and built with a mobile-first development strategy. This was possible by leveraging Bootstrap.

Website deployed using GitHub Pages - [See Live](https://kenwilde1.github.io/crate-o-wine/).

## Table of Contents

- [Project Purpose](https://github.com/kenwilde1/crate-o-wine#crate-o-wine)
- [User Experience (UX)](https://github.com/kenwilde1/crate-o-wine#user-experience-ux)
  - [Objective](https://github.com/kenwilde1/crate-o-wine#objective)
  - [User Goals and Stories](https://github.com/kenwilde1/crate-o-wine#user-goals-and-stories)
  - [Wireframes](https://github.com/kenwilde1/crate-o-wine#wireframes)
- [Site Components](https://github.com/kenwilde1/crate-o-wine#site-components)
  - [Existing Site Components](https://github.com/kenwilde1/crate-o-wine#existing-site-components)
  - [Components to Implement](https://github.com/kenwilde1/crate-o-wine#components-to-implement)
- [Design](https://github.com/kenwilde1/crate-o-wine#design)
  - [Design Considerations](https://github.com/kenwilde1/crate-o-wine#design-considerations)
  - [Design Choices](https://github.com/kenwilde1/crate-o-wine#design-choices)
- [Technologies Used](https://github.com/kenwilde1/crate-o-wine#technologies-used)
- [Testing](https://github.com/kenwilde1/crate-o-wine#testing)
  - [PageSpeed Insights](https://github.com/kenwilde1/crate-o-wine#pagespeed-insights)
  - [Google Lighthouse](https://github.com/kenwilde1/crate-o-wine#google-lighthouse)
  - [Resonsiveness Testing](https://github.com/kenwilde1/crate-o-wine#responsiveness-testing)
  - [User Inputs](https://github.com/kenwilde1/crate-o-wine#user-inputs)
  - [Known Bugs](https://github.com/kenwilde1/crate-o-wine#known-bugs)
- [Deployment](https://github.com/kenwilde1/crate-o-wine#deployment)
- [Media](https://github.com/kenwilde1/crate-o-wine#media)

## User Experience (UX)

### Objective

The Objective of the UX process was to provide end-user (potential customers) with a clear and succinct way to interact and retrieve information from within the website. Through this, we avoid overwhelming the end-user with too much information and give them the freedom to navigate the website as they please.

A Secondary Objective served to provide a short path to drive users towards purchasing the product. It was important to do this in as few clicks as possible in order to hold onto the end-user's attention.

### User Goals and Stories

As an End-User, the goal is to learn about the product so you can make an educated purchasing decision. As the Site Owner, in order to help the end-user achieve this goal, the website was designed to provide freedom of navigation with clear and succinct data points. As the end-user becomes overwhelmed with buttons, paragraphs and other components, the chance of leaving the page increases.

Every component of the website was built with a User Story in mind. This included NavBar, Carousels, Information Containers, Footers etc. No component was built without providing a User Story as a form of justification.

You can view the User Stories [here]('./assets/docs/User-Stories.pdf'). For every user story, a visual card was created. It had a 'title' which served as the reason to build out a selected feature. Below that, you can see that _why_ the user would want this.

### Wireframes

Wireframes were created pre-emptively in order to provide a schematic for how the website would look on every page and device. The Wireframes covered Desktop, Tablet and Mobile for responsive design. They are an original mock-up and some components may vary on the live preview of the website.

You can view the Wireframes [here]('./assets/docs/Wireframes-Desktop-Tablet-Mobile.pdf').

Here is a preview of the Home page on Desktop, Tablet and Mobile:

- ##### Desktop

  <img height="600" src="./assets/images/readme/desktop-preview.png">

- ##### Tablet

  <img height="600" src="./assets/images/readme/tablet-preview.png">

- ##### Mobile
  <img  height="600" src="./assets/images/readme/mobile-preview.png">

## Site Components

### Existing Site Components

- #### Navbar

  The Navbar serves as a source of navigation and design. On the left side of the navbar, it contains the logo and title 'Crate O' Wine'. This is clickable and brings the user back to the homepage. On the right side of the navbar are our nav links - Home, About and Contact, respectively.

- #### Hero Image

  The Hero Image component will be the first thing the user sees and is implemented to grab attention. It contains a text box in the center that containts two links - read more and start now. Read More will bring the user to the About page where they can be informed about the product. Start Now will bring the user to the Contact page where they can subsequently get in touch to start the subscription.

- #### Promise Container

  The Promise component informs the user of a fairtrade guarantee, it contains a button that brings them to the About page to learn more about this.

- #### User Feedback Carousel

  The User Feedback Carousel is a text and image slide of people who have subscribed to the product and left feedback. It's goal is to gain trust with the user.

- #### Information Container

  The Information container, located on the About page, will educate the User on exactly what they need to know about the product - the How, What, Where.

- #### Subscription Plans

  This section gives the user a list of available subscription plans - standard and premium. They are presented in the form of panes, they provide a basic overview of each plan - description and price. Both plans have a button that brings up a Modal.

- #### Subscription Modals

  As mentioned previously, clicking on the button in the subscription plans brings up a modal. This provides in-depth details of what exactly each plan offers.

- #### Fairtrade Container

  As mentioned before with the promise container, it's button brings the user here. This is a container to explain why each wine on offer is fairtrade guaranteed. Put simply, it educates the user on why this is a core value of the product.

- #### Contact Form
  Within the scope of this project, the contact form is the place that the User declares their interest in starting a monthly subscription. It provides input fields and validation. In addition, there is a google maps embed along with the physical address.

### Components to Implement

- #### Checkout

  In the future, the user should be able to select a plan and perform a checkout for the plan they selected. This would include a cart-like system and a purchasing container.

- #### Gallery
  An Image Gallery showing visual aspects of these crates can also capture a user's interest in the product. As the company is fictitious, this was not possible to implement during development.

## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

  - The project uses **HTML5** to structure the components of the pages, this includes the Nav, Main Content and Footer.

- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)

  - The project uses **CSS3** to add styling to certain components of the page.

- [Bootstrap 4](https://developer.mozilla.org/en-US/docs/Web/CSS)

  - The project uses **Bootstrap 4** to tell the browser how the page layout should look using containers, rows and columns. Each component on the page uses Bootstrap and/or Flexbox to provide layout.

- [Git](https://git-scm.com/)
  - At every significant change, the changes were committed using Git and Github. This was done to keep track of changes, have a remote repository for protection against redundancy.

## Design

### Design Considerations

- Clear & Succinct
- Consistent
- Accessible
- Appealing

Throughout the development, these four factors were at the forefront in terms of design. When the user visits the website, the goal is not to overwhelm them with all the information they need. It was important to give them the freedom to seek that information if they so chose, while giving them a **clear** landing page that provided some level of detail about the product.

Every page had to be **consistent** to convery professionalism as if every component of the website was created together rather than in isolation.

The website being **accessible** was also very important as you cannot expect that all users will be using the same browser, device and viewport. Making it accessible for all devices and compatible with all browsers was a key driver duing development.

Lastly, while the content is clear, consistent and accessible, grabbing the user's attention with **appealing** colours, themes and layouts that enabled increased interaction is perhaps one of the most important factors of web design.

### Design Choices

- #### Colours
  I used Custom CSS rules in tandem withb Bootstrap. This was because Bootstrap tends to have uniform and non-configurable styles. To accomplish this and ensure consistency throughout, I used CSS variables to declare the colours for the website:

<img src="./assets/images/readme/palette.png" alt="palette">

Additionally, the following Boostrap colours were used to style the background and buttons, respectively:

- `bg-light` - styled the backgrounds of all components e.g carousel, subscription plans etc.
- `btn-danger` - this colour worked well for my buttons and provided a hover effect which saved me some time.

## Testing

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

## Deployment

Github pages were used to deploy the project. You can visit it [here](https://kenwilde1.github.io/crate-o-wine). Github pages looks at the `main` respository for an index.html and that has references to the rest of the website. Every time a `push` is made, a new build is deployed to github pages.

To run it locally you can:

```
> git clone https://github.com/kenwilde1/crate-o-wine.git
> cd crate-o-wine/
> open ./index.html
```

### Media

- All Images were taken from [Pixabay](https://pixabay.com/). They offer a variety of copyright free images.
- The faces of the people in the carousel were AI-generated using [Generated](https://generated.photos/faces).
