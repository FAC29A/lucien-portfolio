## 1. Structure a site using semantic HTML to aid accessibility




This screenshot shows that we incorporated semantic elements in our HTML, including demarcating each section so that it can be tabbed through by the user, as well as H1 and H2 headings in correct order, which ensured that they would be read out by a screen reader (see below). In addition, we used alt-tags on each image. Being able to tab through the site is especially important for those with sight access requirements, and relates to the below. Unfortunately, we missed using ARIA-labels, which was a glaring omission.
The choice of HTML elements can significantly impact how your content is perceived by both humans and machines. 
---

For example semantic HTML elements, like \<section\> and \<article\>, By using them correctly, you make your content more machine-readable, aiding search engines in understanding your website's structure.

for example   <section> and <article>, use <article> when your content is self-contained and can stand alone, such as a blog post. On the other hand, \<section\> is ideal for grouping related content within a document, making it easier for both users and automated tools to navigate your website. By using semantic HTML, you enhance accessibility, user experience, and SEO, making your website more effective and user-friendly.


## 2. Ensure a web page is readable for screen readers

After incorporating the semantic elements in point 1, I then tested the site via screen readers such as Windows Narrator, Speechify, and NVDA. The site worked well with the first two, but came up against issues with NVDA, which appeared to not be able to read the semantic HTML well.
---

Using semantic HTML also enhances accessibility for screen readers. These tools rely on markup semantics to determine the nature of web page content, making it crucial for developers to use semantic elements that convey the correct information.

## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

The screen shot above in Item #3 above confims that we built the site with the express purposes of it being accessible for users whether colour blind or not.

---
Adequate color contrast is essential because it allows text and elements to stand out clearly against the background, making content more readable and understandable.

This is particularly important for individuals with various forms of color blindness, low vision, or other visual impairments.

Colour contrast checker:   
To assess color contrast, utilise the 'Lighthouse' tool within Chrome's developer tools. After analszing accessibility, it will determine if the site maintains sufficient color contrast.



<img width="568" alt="Screenshot 2023-10-09 at 20 54 41" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/e84ef7f2-3657-4112-8c0e-3b657690353f">


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
