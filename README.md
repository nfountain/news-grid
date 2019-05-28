# NewsGrid

This is a mock-up of a news site. It was created using CSS grid and media queries to make this multi-page website responsive.

## Adding Pages

A boilerplate page with the Navigation and Footer sections was created to make adding new pages simple and quick. The content section of all pages, other than the main page, now has the class of page-content. This allows all base styles to be applied, responsively, to each new page. This reduces the number of edits to the HTML/CSS that would be needed to add any new pages.

Individual ID's for the content section on each of these pages was left in the HTML documents in case individualized styling is neeeded in the future. Any specific styling for the content section's ID would need to be added to the CSS stylesheets for [base/large screen styles](css/styles.css), and [mobile styles](css/mobile.css).

## Credits

The original project was presented in a watch and code format as part of a [Udemy](https://www.udemy.com) course by [Brad Traversy](https://www.udemy.com/course/modern-html-css-from-the-beginning/). The course was taught large screen first, so the styles will remain in this format for this iteration of the project. I took some liberty with the process, especially in regard to creating classes for different sections (reducing chained selectors) and adjusting the styles for smaller screen sizes.

The image assets were provided along with the course content, and at least some of the images appear to be from [Unsplash](https://www.unsplash.com).

## Contributing

Contributions are welcome, especially those that streamline the HTML and CSS files.