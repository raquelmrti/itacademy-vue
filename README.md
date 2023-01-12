# Front End Development with Vue.js - IT Academy

My sprints for IT Academy's Vue course. As I work through the exercises, I will document my progress in this page.

---

## **Sprint 1**

The first sprint consists in familiarizing yourself with **flexbox** (and **grid**, optionally) by building a blog-like website layout.

<details>
<summary>Log</summary>

### ⭐ **Level 1** ⭐

**— Exercise 1**

Desktop version. Even though the content of the website is just simulated, I decided to apply [semantic HTML](https://css-tricks.com/how-to-section-your-html/) for practice.

##### ✅ Finished: 28/11/2022

**— Exercise 2**

Add media queries for tablet view.

##### ✅ Finished: 28/11/2022

**— Exercise 3**

Add media queries for mobile view.

##### ✅ Finished: 28/11/2022

· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

### ⭐⭐ **Level 2** ⭐⭐

**— Exercise 4**

Add content and style the header.

##### ✅ Finished: 29/11/2022

**— Exercise 5**

Add content and style the rest of the page.

✏️**Notes:**

- I had to change the media query for the mobile view so it would activate earlier, because the layout was getting too squished before it'd switch to mobile view and it was hard making it look right.
- I also had to change the sidebar's width. At first I didn't give it any width and just made it have `flex-grow: 1` so it'd take up all the remaining space, which was fine while the sidebar had no content, but when I added text it expanded and made the `main` element shrink. So I had to give it a width of 30%.

##### ✅ Finished: 01/12/2022

· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

### ⭐⭐⭐ **Level 3** ⭐⭐⭐

**— Exercise 6**

Add animation to logo and tagline.

##### ✅ Finished: 01/12/2022

**— Exercise 7**

Adapt the layout to grid. I decided to leave the navbar as a flexbox element due to the fact that it's one-dimensional, and I believe there'd be no benefit to using grid.

##### ✅ Finished: 01/12/2022

</details>

---

## **Sprint 2**

This sprint is about building a landing page using **Bootstrap 5**, as well as using **SCSS** (although minimally because you're supposed to use the Bootstrap HTML classes.)

<details>
<summary>Log</summary>

### ⭐ **Level 1** ⭐

**— Exercise 1**

Make the header + start of the main content.

##### ✅ Finished: 23/12/2022

**— Exercise 2**

Make the features section. The truth is I struggled a lot with this part, as I found customizing bootstrap components very troublesome at times. But in the end I think I did a decent job!

Also, I found out this exercise is a challenge from Frontend Mentor, so I took some missing text content from there (the text for the Speedy Searching and Easy Sharing tabs.)

##### ✅ Finished: 28/12/2022

**— Exercise 3**

Make the download section.

##### ✅ Finished: 03/01/2023

**— Exercise 4**

Make the FAQ section.

##### ✅ Finished: 04/01/2023

· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

### ⭐⭐ **Level 2** ⭐⭐

**— Exercise 5**

Make the footer and form with Bootstrap validation.

✏️**Notes:**

- Before starting Level 2, I decided to divide my SCSS into partial files in order to try the module system. It helps organizing your SCSS! I've read that [doing `@import` is outdated and it's been replaced with `@use`](https://stefaniefluin.medium.com/the-new-sass-module-system-out-with-import-in-with-use-e1bd8ba032d0), but I've also read that Bootstrap doesn't support `@use`. I'm unsure whether that has changed yet or not, I have to look into it.

##### ✅ Finished: 11/01/2023

· · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

### ⭐⭐⭐ **Level 3** ⭐⭐⭐

**— Exercise 6**

Modify the hover state of multiple elements across the page, and stylize the invalid feedback message in the email form.

✏️**Notes:**

- Before this exercise, I had been using the Bootstrap classes `text-black` and `text-white` to change the color of some links in the HTML, but I discovered that made me unable to modify the color on hover. So I got rid of those classes and established the text color in the CSS instead.

- I made a mixin for the login button and the contact button because they have the same styling, but are nested under different parents, so if I wanted to target both of them at once it was going to disorganize my code.

- For the social icons in the footer, I swapped the `img` tag to `svg`. This way I was able to modify the `fill` property on hover.

##### ✅ Finished: 12/01/2023

</details>
