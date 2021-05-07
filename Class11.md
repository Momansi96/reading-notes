# Class11 

[Return to home page](https://momansi96.github.io/reading-notes/). 


## images: 

#### Controlling sizes of images in CSS: 

You can control the size of an image using the width and height properties in CSS, just like you can for any other box. Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download. You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across many of their pages.

* AligNing images Using CSS: Rather than using the "<img>" element's align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved:

1. The float property is added to the class that was created to represent the size of the image. 

2. New classes are created with names such as align-left or align-right to align the images to the left or right of the page. 

* Centering images Using CSS: By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

1. On the containing element, you can use the text-align property with a value of center.

2. On the image itself, you can use the use the margin property and set the values of the left and right margins to auto. 

* Background Images (background-image): The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.

* Repeating Images (background-repeat, background-attachment): The background-repeat property can have four values:

1. repeat: The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).

2. repeat-x: The image is repeated horizontally only (as shown in the first example on the left).

3. repeat-y: The image is repeated vertically only.

4. no-repeat: The image is only shown once. The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:

 * fixed: The background image stays in the same position on the page.
 * scroll: The background image movesup and down as the user scrollsup and down the page.

* Background Position (background-position): When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed. This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.

* shorthand (background): The background property acts like a shorthand for all of the other background properties you have just seen, and also the background-color property. The properties must be specified in the following order, but you can miss any value if you do not want to specify it.

1. background-color.
2. background-image.
3. background-repeat.
4. background-attachment.
5. background-position.

* Contrast of background images: If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

1. High Contrast. 
2. Low Contrast.  
3. Screen. 

## Practical Information: 

#### Search Engine Optimization (SEO): 

SEO is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines. 

1. The Basics: Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

2. On-Page Techniques: On-page techniques are the methods you can use on your web pages to improve their rating in search engines. 

3. Off-Page Techniques: Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.

* On-Page SEO: In every page of your website there are seven key places where keywords can appear in order to improve its findability. 

1. Page Title: The page title appears at the top of the browser window or on the tab of a browser. It is specified in the "<title>" element which lives inside the "<head>" element.

2. URL / Web Address: The name of the file is part of the URL. Where possible, use keywords in the file name.

3. Headings: If the keywords are in a heading "<hn>" element then a search engine will know that this page is all about that subject and give it greater weight than other text.

4. Text: Where possible, it helps to repeat the keywords in the main body of the text at least 2-3 times. Do not, however, over-use these terms, because the text must be easy for a human to read.

5. Link Text: Use keywords in the text that create links between pages (rather than using generic expressions such as "click here").

6. Image Alt Text: Search engines rely on you providing accurate descriptions of images in the alt text. This will also help your images show up in the results of image-based searches.

7. Page Descriptions: The description also lives inside the "<head>" element and is specified using a "<meta>" tag. It should be a sentence that describes the content of the page. 

* How to Identify Keywords and Phrases: Determining which keywords to use on your site can be one of the hardest tasks when you start to think about SEO. Here are six steps that will help you identify the right keywords and phrases for your site.

1. Brainstorm: List down the words that someone might type into Google to find your site. Be sure to include the various topics, products or services your site is about.

2. Organize: Group the keywords into separate lists for the different sections or categories of your website.

3. Research: There are several tools that let you enter your keywords and then they will suggest additional keywords you might like to consider. 

4. Compare: It is very unlikely that your site will appear at the top of the search results for every keyword. This is especially true for topics where there is a lot of competition. The more sites out there that have already been optimized for a given keyword, the harder it will be for you to rise up the search results when people search on that term.

5. Refine: Now you need to pick which keywords you will focus on. These should always be the ones that are most relevant to each section of your site. 

6. Map: Now that you have a refined list of keywords, you know which have the most competition, and which ones are most relevant, it is time to start picking which keywords you will use for each page. 

#### Analytics: Learning about your Visitors. 

* As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.

1. Signing Up: The Google Analytics service relies on you signing up for an account. 

2. How it Works: Every time someone loads a page of your site, the tracking code sends data to the Google servers where it is stored.  

3. The Tracking Code: A tracking code is provided by Google Analytics for each website you are tracking. 

* What Are Your Visitors Looking At?: The content link on the left-hand side allows you to learn more about what the visitors are looking at when they come to your site. 

1. Pages: This tells you which pages your visitors are looking at the most and also which pages they are spending the most time on.

2. Landing Pages: These are the pages that people arrive on when first visiting your site. This can be particularly helpful because you may find people are not always coming into your site via the homepage.

3. Top Exit Pages: This shows which pages people most commonly leave from. If a lot of people are leaving from the same page then you might consider changing that page or improving it. 

4. Bounce Rate: This shows the number of people who left on the same page that they arrived on. A high bounce rate suggests that the content is not what they were looking for or that the page did not sufficiently encourage them to look around the rest of the site. 

* Where Are Your Visitors Coming From?: The traffic sources link on the left hand side allows you to learn where your visitors are coming from. 

1. Referrers: This shows the sites that have linked to you and the number of people who have come via those sites. 

2. Direct: This shows which page a user arrived on if they did not come via a link on another site. 

3. Search Terms: This shows the terms users entered into a search engine to find your site. 

4. Advanced Features: We have only scratched the surface of what you can find out about your visitors from Google Analytics. 

#### Domain Names & Hosting: 

In order to put your site on the web you will need a domain name and web hosting: 

1. DOMAIN NAMES: Your domain name is your web address (e.g. google.com or bbc. co.uk). There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name. 

2. WEB HOSTING: So that other people can see your site, you will need to upload it to a web server. Web servers are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when they are requested. 

3. Hosted Services: There are a number of online services that allow you to point your domain name to their servers. 



