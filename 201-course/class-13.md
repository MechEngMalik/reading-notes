# “The Past, Present, and Future of Local Storage for Web Applications”

HTML5 is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and last major HTML version that is a World Wide Web Consortium recommendation. The current specification is known as the HTML Living Standard.
You probably have heard of local storage or session storage terms but never got a chance to explore it. This article will clear all your concepts about it.
Local and Session storage comes under the category of HTML5 Web Storage.
It’s not the same as session storage that you might be familiar with if you came from a Java background where the session is stored on the server-side.
We will use the term Web Storage when we talk about Session and Local Storage together.
Web Storage is used for storing data on the client-side. So the data will be available even when the page is refreshed.
Previously before Web Storage came into play, the only way of storing the data on the client-side was using cookies.
Cookies are still used but there are some disadvantages of using cookies

1. Cookies are stored on the client-side and are transferred to the server on every request sent to the server. This makes cookies less secure
2. Cookies have a storage limit. We can’t store more data into cookies after a certain limit
3. Cookies can be disabled by using some browser extension tools
4. Storing data in cookies required some extra code
So Let’s explore Web Storage Now

## Session Storage

Session Storage is for per browser tab. So data stored in one browser tab will not be accessible in another tab
Each browser tab has separate session storage data
Session Storage data gets cleared when we close the tab
It also gets cleared when we close the browser

### Local Storage

Local Storage is used for storing data across the entire application
Data stored in local storage will be accessible across all the tabs or pages only for that domain ( like www.google.com, www.medium.com, etc)
Local Storage data stored for a particular domain will be accessible even you open another browser window (Control + n or Command + n (Mac)) on the same browser
Local Storage data stored on normal browsing sessions will not be available when you open a browser in private browsing or in Incognito mode.
Local Storage data will not get cleared even if you close the browser. Because it’s stored on your browser cache in your machine.
Local Storage data will only be cleared when you clear the browser cache using Control + Shift + Delete or Command + Shift + Delete (Mac)
We can also clear the local storage data programmatically.

## USING HTML5 STORAGE

With web storage, web applications can store data locally within the user's browser. Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

## HTML5 WEB STORAGE

Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not. ... From your JavaScript code, you'll access HTML5 Storage through the localStorage object on the global window object.

![image](https://coursework.vschool.io/content/images/2018/01/html5_sectioning_high_level.jpg)
