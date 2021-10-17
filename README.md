<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/Hsins-Lab/wp-theme-andrew.svg?style=flat-square)](./LICENSE)

</div>

<!-- title, logo and description -->
<div align="center">
  <img src="https://i.imgur.com/lEosH3Q.png" alt="Custom WordPress Theme: Andrew" height="150px">

# Custom WordPress Theme: Andrew

🧪 _A hands-on WordPress Theme from the course - "How to Create a Custom WordPress Theme" by [Andrew Wilson](https://github.com/wilsmex)._

</div>

## File Structure

```
├── assets
│   ├── css
│   │   └─ main.css
│   ├── fonts
│   │   └─ ...
│   ├── images
│   │   └─ ...
│   └── js
│       └─ ...
├── classes         // PHP classes used for various functions to override WordPress functionality
├── inc             // stands for "includes", any sort of files to be included
├── template-parts  // split individual parts of templates
├── templates       // main template folder
├── 404.php         // served when user get a 404 server error
├── archive.php     // delivering an archive page, e.g. index of all blog posts
├── comments.php    // displaying and serving comments
├── footer.php      // responsible for the footer section
├── front-page.php  // display the site front page
├── functions.php   // [IMPORTANT] override and initiate different features of the theme
├── header.php      // responsible for the header section
├── index.php       // [REQUIRED] MUST HAVE. serves as the fallback
├── page.php        // displaying static pages (except blog posts and archive pages)
├── readme.txt      // file for putting copyright notices
├── search.php      // displaying search results
├── single.php      // displaying single blog posts
└── style.css       // [REQUIRED] MUST HAVE. master stylesheet for website
```

## References

- [How to Create a Custom WordPress Theme | YouTube](https://www.youtube.com/watch?v=-h7gOJbIpmo)