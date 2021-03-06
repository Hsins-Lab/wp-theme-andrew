<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/Hsins-Lab/wp-theme-andrew.svg?style=flat-square)](./LICENSE)

</div>

<!-- title, logo and description -->
<div align="center">
  <img src="https://i.imgur.com/lEosH3Q.png" alt="Custom WordPress Theme: Andrew" height="150px">

# Custom WordPress Theme: Andrew

๐งช _A hands-on WordPress Theme from the course - "How to Create a Custom WordPress Theme" by [Andrew Wilson](https://github.com/wilsmex)._

</div>

## File Structure

```
โโโ assets
โ   โโโ css
โ   โ   โโ main.css
โ   โโโ fonts
โ   โ   โโ ...
โ   โโโ images
โ   โ   โโ ...
โ   โโโ js
โ       โโ ...
โโโ classes         // PHP classes used for various functions to override WordPress functionality
โโโ inc             // stands for "includes", any sort of files to be included
โโโ template-parts  // split individual parts of templates
โโโ templates       // main template folder
โโโ 404.php         // served when user get a 404 server error
โโโ archive.php     // delivering an archive page, e.g. index of all blog posts
โโโ comments.php    // displaying and serving comments
โโโ footer.php      // responsible for the footer section
โโโ front-page.php  // display the site front page
โโโ functions.php   // [IMPORTANT] override and initiate different features of the theme
โโโ header.php      // responsible for the header section
โโโ index.php       // [REQUIRED] MUST HAVE. serves as the fallback
โโโ page.php        // displaying static pages (except blog posts and archive pages)
โโโ readme.txt      // file for putting copyright notices
โโโ search.php      // displaying search results
โโโ single.php      // displaying single blog posts
โโโ style.css       // [REQUIRED] MUST HAVE. master stylesheet for website
```

## References

- [How to Create a Custom WordPress Theme | YouTube](https://www.youtube.com/watch?v=-h7gOJbIpmo)