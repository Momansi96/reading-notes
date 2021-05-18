# Class13 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS. 

ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. 

Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request. 
 
 * thereby slowing down your web application by needlessly transmitting the same data over and over.
 * thereby sending data unencrypted over the internet.
 * Cookies are limited to about 4 KB of data — enough to slow down your application. 

* What we really want is: 
 
 * a lot of storage space.
 * on the client.
 * that persists beyond a page refresh.
 * and isn’t transmitted to the server. 

#### INTRODUCING HTML5 STORAGE: 

What we will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”, So what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. 

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. 

#### USING HTML5 STORAGE: 

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string, Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. 

#### TRACKING CHANGES TO THE HTML5 STORAGE AREA: 

If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something, The storage event is supported everywhere the localStorage object is supported. 








