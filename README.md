# Refactor-Homework

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://www.w3schools.com/html/html_elements.asp](https://www.w3schools.com/html/html_elements.asp) | 
| CSS     | [https://www.w3schools.com/cssref/css3_pr_flex-wrap.php](https://www.w3schools.com/cssref/css3_pr_flex-wrap.php)      |   

## Description 

[Visit the Deployed Site](https://408broncos.github.io/Refactor-Homework/)

In this project I was able to look at a premade website and see what I can find, within the code, that needs to be added without changing the code itself. I think a challenge I ran into was locating things that needed to be changed but after really looking at the HTML and CSS code I was able to find some elements and little corrections that I could make without changing the code. 

Through this project I was able to really challenge my research skills to discover ways to add to the CSS and HTML code. I was also able to gain new knowledge through this research that I will show in the code refactor section of this README.

## Code Refactor Example

Some steps I took to refactor a code was first looking at the elements within the index.HTML. After carefully looking through it I discovered that the images had a source but no "alt" attribute. After seeing this I was able to quickly look at the images and add the "alt" attributes to it in case the source did not function properly. 

Here is the change I made:


```html
<img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="laptop, magnify glass, pens, notebook with SEO and coffee" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="laptop with a title named reputation" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" alt="table of people with different social media tags" />
            <h2>Social Media Marketing</h2>
```

I was also able to add a flex wrap to the header in CSS so that the texts within the header stays in a comfortable placement when resizing the window into a smaller screen.

Here is the example:

```css
.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
    display: flex;
    flex-wrap: wrap;
}

```

## Usage 

As I previously stated in my "Code Refactor Example" section above I was able to add a "alt" attributes to all of the images since I noticed that none of them had an alt source. 

For the CSS example I was able to research how to flex wrap a section and use the knowledge I gained from it to then apply to the header. I did run into a wall with the contents, but I believe with more practice I will be able to understand it a lot better. 


## Learning Points 


Through this project I was able to learn so many new ways to enhance code without even changing it as well as looking thoroughly through every line to see if change was needed. Through these new skills it has already made me a little more confident with my knowledge and comfortability with this course so far and I am so excited to see how much I grow.


## Author Info

```md
### Jordan Cardenas 
* [LinkedIn](https://www.linkedin.com/in/jordan-cardenas-87a58520b/)
* [Github](https://github.com/408broncos)
```---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
