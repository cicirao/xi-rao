# Document Design Portfolio

It's a web edition portfolio of my Document Design course. (Surely there is a paper edition. : ) )

And also a practice of HAML, SASS, and Typekit.

To output the HTML from Haml, run

      $ haml -q index.haml index.html

To output the CSS from SCSS, run

      $ sass assets/css/screen.scss assets/css/screen.css

To have SCSS constantly regenerate the CSS as you work, run

      $ cd assets/css/
      $ sass --watch screen.scss:screen.css
