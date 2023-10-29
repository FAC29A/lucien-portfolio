## 1. Structure a site using semantic HTML to aid accessibility





- Semantic HTML: We incorporated semantic elements (such as `<header>`, `<section>`, `<article>`  in our HTML. We particularly mindful the use of `<section>` and `<article>`:  we use `<article>` when the content is self-contained and can stand alone; we use `<section>` for grouping related content within a document, making it easier for both users and automated tools to navigate our website. (see below image). 
  <img width="416" alt="Screenshot 2023-10-29 at 20 53 45" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/eeafb45b-42e9-4fbe-b27c-106dac3e41da">

- `<H1>` `<H2>` elements are use in correct order to ensured that they would be read out by a screen reader.(see below image)
  <img width="408" alt="Screenshot 2023-10-29 at 21 02 56" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/d1dd2892-15be-421f-bc32-5aad45b7a854">


- We used alt-tags on each image (for the empty image we use `alt=""` so the machine understand this is intentionally left blank description) This is important for those with sight access requirements to be able to use screen readers for acquire the description of images


## 2. Ensure a web page is readable for screen readers

We tested the site via various screen readers (Chromes, Safari, Mac screen reader). The important content and section are sucessfully read out on these screen readers


## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

We use the color contrast checker suggest by Lighthouse (https://dequeuniversity.com/rules/axe/4.7/color-contrast) to ensure they pass WCAG Standard AAA

<img width="464" alt="Screenshot 2023-10-29 at 21 28 42" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/cdd6b6cb-1289-4801-8bfd-fcd9cdb48134">




## 4. Use various tools to check that our website meets accessibility criteria

We ran the HTML through https://validator.w3.org, which is a practice that I used regularly while studying the Advanced Web Authoring module of Birkbeck (indeed, a condition of gaining a high mark there was for the HTML to validate correctly). However, we came up against a number of problems when doing this. The validator flags up trailing slashes on void elements as bad for validation, yet Visual Studio Code (unless I am mistaken) appears to add these trailing slashes automatically.

In addition, when running the site directly from LiveServer, the Lighthouse function in Chrome confusingly claimed that there were no alt-tags for the images, even though there were, and gave us 91% for Accessibility accordingly.

## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes
We not consider that we needed CSS media queries for this project, as it already scaled well. However, if we add employed CSS media queries in this project, it would've looked something like this:

## 6. Demonstrate a mobile-first approach to building a website
Our commits show our mobile-first approach. This is in acknowledgement of the fact that many users increasingly access websites via mobile phone and tablets.

## 7. Use CSS variables to apply repeated colours to HTML elements

We used colour sparingly on the site. There is a black navigation bar, with links in white font colour; then the main section of the site has black font colour against a background of a sombre white/gray (#eee8e8). Meanwhile, for the biography section, we used a blend of blue, pink, and green to to lift the rider biography cards from the page.

## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)

## 9. Use CSS Grid to style children in two-direction layout

## 10. Ensure our Git commit history tells a coherent story

## 11. Use the appropriate input types in HTML forms for gathering different types of information
