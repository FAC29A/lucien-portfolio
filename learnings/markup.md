## 1. Structure a site using semantic HTML to aid accessibility

- Semantic HTML: We incorporated semantic elements (such as `<header>`, `<section>`, `<article>`  in our HTML. We particularly mindful the use of `<section>` and `<article>`:  we use `<article>` when the content is self-contained and can stand alone; we use `<section>` for grouping related content within a document, making it easier for both users and automated tools to navigate our website. (see below image). 

   <img width="416" alt="Screenshot 2023-10-29 at 20 53 45" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/eeafb45b-42e9-4fbe-b27c-106dac3e41da">

- `<H1>` `<H2>` elements are use in correct order to ensured that they would be read out by a screen reader.(see below image)

  <img width="408" alt="Screenshot 2023-10-29 at 21 02 56" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/d1dd2892-15be-421f-bc32-5aad45b7a854">


- We used alt-tags on each image (for the empty image we use `alt=""` so the machine understand this is intentionally left blank description) This is important for those with sight access requirements to be able to use screen readers for acquire the description of images


## 2. Ensure a web page is readable for screen readers

We tested the site via various screen readers (Chromes, Safari, Mac screen reader). The important content and section are sucessfully read out on these screen readers


## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

We use the color contrast checker suggest by Lighthouse (https://dequeuniversity.com/rules/axe/4.7/color-contrast) to ensure they pass WCAG Standard AAA.

<img width="464" alt="Screenshot 2023-10-29 at 21 28 42" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/cdd6b6cb-1289-4801-8bfd-fcd9cdb48134">

## 4. Use various tools to check that our website meets accessibility criteria

We use various tools to varify our accessiblity rate 

- https://www.a11yproject.com/checklist/  (see below image)
- https://validator.w3.org/nu/ 
- Lighthouse on Google Chrome: Our site rate 94% on accessiblity score in Lighthouse.(see below image)

<img width="536" alt="Screenshot 2023-10-29 at 21 45 05" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/021e45e0-cee3-4b03-8336-dce1b0324ee2">
<img width="621" alt="Screenshot 2023-10-29 at 21 40 21" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/f2654c78-dcc3-45c1-87e3-a495c5d319be">


## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes

The site has media queries to adjust for small screen (max-screen-width 600px) and medium screen (max-screen-width 900px). 


<img width="622" alt="Screenshot 2023-10-29 at 21 49 05" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/129cf3d6-467a-47c1-861c-c653653992ec">
<img width="498" alt="Screenshot 2023-10-29 at 21 49 00" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/c1142e76-7e6b-4bdc-9204-25f19d66027f">


## 6. Demonstrate a mobile-first approach to building a website
The site is responsive for mobile user(see below image).  However for this project we did not start building using mobile-frist approach. We started to build the site from wide-screen user. This is a note to take for the next project.

<img width="579" alt="Screenshot 2023-10-29 at 21 52 38" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/f1f69fa4-357d-4437-a630-12175c400d23">


## 7. Use CSS variables to apply repeated colours to HTML elements
In CSS we use colour variable to apply all the elements on the site ( see below image)


<img width="345" alt="Screenshot 2023-10-29 at 21 56 49" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/d91bbaf8-b64f-458e-a8fb-90bbd4fb0d19">


## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)
We use Flexbox to style the navbar in a single direction layout

<img width="487" alt="Screenshot 2023-10-29 at 22 00 21" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/ed47ef7d-1771-40b8-8b2f-f51cbaa0466b">

## 9. Use CSS Grid to style children in two-direction layout
We use CSS Grid to style `<article>` with two direction layout
<img width="852" alt="Screenshot 2023-10-29 at 22 01 52" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/5e325893-66e6-45e3-9ccf-00f16c0a1062">


## 10. Ensure our Git commit history tells a coherent story

In our Git commit - we can see in which section was changed / and what was the purpose of the changed. 
<img width="435" alt="Screenshot 2023-10-29 at 22 06 14" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/4ba8f5d8-6bd5-42e9-bbdb-3fb78f3ce02c">

## 11. Use the appropriate input types in HTML forms for gathering different types of information
In our form, we use `<fieldset>` `<input type="radio">` `<input type=email>`...etc. 

<img width="602" alt="Screenshot 2023-10-29 at 22 09 35" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/09e17b6a-0232-4279-b57e-512e4313dd54">

