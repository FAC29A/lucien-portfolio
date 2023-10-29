<img width="562" alt="Screenshot 2023-10-29 at 23 30 30" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/2fbdaad1-ae39-44fc-98b7-177a7cd670fd">## 1. Write code that executes asynchronously
we use various asynchronous JavaScript `.then & catch` `async function` ` so the programs can start long-running tasks(such as waiting for the API server's response), and continue running other tasks in paralel. 
<img width="700" alt="Screenshot 2023-10-29 at 22 31 22" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/3369a0ea-f96d-4c17-8bd6-35d312e2d495">


## 2. Use callbacks to access values that aren’t available synchronously
Most of the information aren't avaialble before we receive the response from API server. We use callbacks to display the information when it is available. The frequent application of callback in our code is to use template literal that await data to be received. 


<img width="554" alt="Screenshot 2023-10-29 at 23 00 43" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/cee70538-b359-4101-91d8-e44042af731f">


## 3. Use promises to access values that aren’t available synchronously

We use `.then .catch` to access the values that aren't available synchronously 

<img width="590" alt="Screenshot 2023-10-29 at 22 59 21" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/01f0d7e6-fa70-46a3-88da-7d4fa984bdd7">



## 4. Use the fetch method to make HTTP requests and receive responses

We make HTTP request by using fetch method to New York Time API and Open Libary API 

<img width="690" alt="Screenshot 2023-10-29 at 22 59 05" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/e954ae3e-b95a-4393-a959-39f3ed6e7b72">



## 5. Configure the options argument of the fetch method to make GET and POST requests
Due to the New York Time API and Open Library restriction restriction, only GET requests are accept therefore we entirely make GET request


## 6. Use the map array method to create a new array containing new values

We use map array method to manipulate to data we received 
<img width="472" alt="Screenshot 2023-10-29 at 23 07 23" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/f3258b62-72bb-4a07-bca1-ed80d8582633">


## 7. Use the filter array method to create a new array with certain values removed
We use filter array method to only keep the data items that has rating property

<img width="785" alt="Screenshot 2023-10-29 at 23 07 44" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/1132cd13-fc24-45be-b3e2-ca4826f4e0f3">

## 8. Access DOM nodes using a variety of selectors
Various of selectors are use including `querySelector` `getElementById` 

<img width="472" alt="Screenshot 2023-10-29 at 23 07 23" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/75b80cac-cfc2-4edd-8474-eada3c8f3930">


## 9. Add and remove DOM nodes to change the content on the page
In case of 429 error message, the site title will be changed by add and remove DOM nodes

<img width="483" alt="Screenshot 2023-10-29 at 23 18 43" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/152e5d6b-633d-4e9d-be59-2286d018d0a3">

## 10. Toggle the classes applied to DOM nodes to change their CSS properties
In the carousel section, when user click the arrow button it will trigger the eventListener, and then a classList will be removed from current slide and add to target slide. This will be linking to CSS so create dynamic position of target slide that always be in the center. 
<img width="578" alt="Screenshot 2023-10-29 at 23 32 03" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/61b14ece-7b3e-4ba0-854e-542f81dfa467">

<img width="562" alt="Screenshot 2023-10-29 at 23 30 30" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/9f38f4c2-4991-43a2-802d-43ea301d0d1e">


## 11. Use consistent layout and spacing

Variables of spacing are set up in CSS that are used across the site.
<img width="301" alt="Screenshot 2023-10-29 at 23 38 35" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/8d2fc717-ec59-45af-a64c-3c476bc8d6f1">



## 12. Follow a spacing guideline to give our app a consistent feel
based our spacing variable above, we also repeatly reuse same element and across different page, as well as applying the same margin go give the map a consistent feel 

<img width="1053" alt="Screenshot 2023-10-29 at 23 46 29" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/78382fd6-b653-4db7-a34d-e9744b669e3b">

## 13. Debug client side JS in our web browser
In order to debug, we prodomainately use 
- Google Chrome Debugger:  especially testing the code by pausing it with breakpoints:
<img width="1238" alt="Screenshot 2023-10-29 at 23 51 52" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/b7a7d0d4-8d26-4e9a-b351-b57d5ac6f665">

- Set-up multiple console.log in the code that display deisgnate message for us to identify the issue source.


## 14. Use console.log() to help us debug our code
One of the example that We use console.error to trace at which line of code the error message is fire.  We have the error message set up as "1st fire" and "2nd fire" so we can identitfy the error message that we recieved is from which part of the code

<img width="317" alt="Screenshot 2023-10-29 at 23 56 06" src="https://github.com/FAC29A/lucien-portfolio/assets/128807685/58672185-acab-4696-8246-1aeff97d10e5">

