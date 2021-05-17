# ClearTerms website implementation

![mid-fi mockup of website screens](https://github.com/sskellner/clearterms/blob/master/Frame%2023%20(2).png)

Documentation: 
- [Google Drive] includes presentation, content docs, documentation, etc.
- [Figma file] contains lo-fi, mid-fi, and hi-fi prototypes; color scheme/branding guide

Please [contact me] if you need access to any of these files!

[Google Drive]: https://drive.google.com/drive/folders/1IhYvlUsq-jI_LArXi94XjbNE5XkqHe84?usp=sharing
[Figma file]: https://www.figma.com/file/VOTyTpqvFv1encyjgw5teS/ClearTerms-pages?node-id=111%3A1
[contact me]: mailto:skellner@andrew.cmu.edu

# Future Developers- Code Refactoring

Notice there are two html files: navBar.html and footer.html. The CSS of each webpage only works when the website is hosted LIVE, not when testing locally. This is done through jquery.

The reason the code is designed this way is so if future developers want to modify either the navBar or the footer (ie: add a new company for the search bar), they would not have to copy and paste those changes onto every webpage.

If you are testing changes internally, you must copy and paste the code inside the head and body tags of both navBar.html and footer.html onto each webpage to view that webpage. In addition, in the webpage, you must comment out the jquery refactor link, the div containing id "nav-placeholder", and the div containing id "footer-placeholder"- as well the script tags associated with those divs.

Attached in the repository is a file: "GHPagesTutorial" which gives instructions on how to host websites on github. When hosted, you can see changes made on the website live rather than locally. You can also bypass the jquery code refactoring issue mentioned above.

Here are some additional sources:

Reuse navigation bars on multiple pages (code refactoring): https://www.mackenziesoftware.com/2020/06/reuse-navigation-bar-on-multiple-pages.html

Building a Javascript search bar: https://www.jamesqquick.com/blog/build-a-javascript-search-bar

Slick slider options and settings:
https://kenwheeler.github.io/slick/
