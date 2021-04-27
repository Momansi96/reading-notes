# Class04 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Links: 

#### Writing Links: 

Links are created using the "<a>" element. Users can click on anything between the opening "<a>" tag and the closing "</a>" tag. You specify which page you want to link to using the href attribute.

#### Linking to Other Sites: 

Links are created using the "<a>" element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link. Users can click on anything that appears between the opening "<a>" tag and the closing "</a>" tag and will be taken to the page specified in the href attribute. When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL. 

#### Linking to Other Pages on the Same Site: 

When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL. If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page. 

#### Directory Structure: 

On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

* Structure: The top-level folder is known as the root folder. The root folder contains all of the other files and folders for a website. Each section of the site is placed in a separate folder; this helps organize the files.

* Relationships: The relationship between files and folders on a website is described using the same terminology as a family tree.

* Homepages: The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called "index.html". Web servers are usually set up to return the index.html file if no file name is specified.

#### Relative URLs: 

Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

When you are linking to a page on your own website, you do not need to specify the domain name. You can use relative URLs which are a shorthand way to tell the browser where a page is in relation to the current page. This is especially helpful when creating a new website or learning about HTML because you can create links between pages when they are only on your personal computer (before you have got a domain name and uploaded them to the web).

#### Email Links: 

mailto: To create a link that starts up the user's email program and addresses an email to a specified email address, you use the "<a>" element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to. On the right you can see that an email link looks just like any other link but, when it is clicked on, the user's email program will open a new email message and address it to the person specified in the link. 

#### Opening Links in a New Window: 

If you want a link to open in a new window, you can use the target attribute on the opening "<a>" tag. The value of this attribute should be _blank. One of the most common reasons a web page author might want a link to be opened in a new window is if it points to another website. In such cases, they hope the user will return to the window containing their site after finishing looking at the other one.

#### Linking to a Specific Part of the Same Page: 

At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top.

Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). 

The value of the id attribute should start with a letter or an underscore (not a number or any other character) and, on a single page, no two id attributes should have the same value.

To link to an element that uses an id attribute you use the "<a>" element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to.

#### Linking to a Specific Part of Another Page: .

If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique. As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page. Therefore, the href attribute will contain the address for the page, followed by the "# symbol, followed by the value" of the id attribute that is used on the element you are linking to.

## Layout: 



