# HTML5 resume template

This project is indeed yet another curriculum vitae template. On the bright side, it uses HTML5 and some fancy CSS to render the page in a rather neat fashion for both print and web display. Still need a pdf to hand in your résumé? It's rendering pretty well when using [wkhtmltopdf](https://code.google.com/p/wkhtmltopdf/) too! 

## Example

Take a look at [the template](http://yholkamp.github.io/html5_resume_template/template.html) or [the resulting pdf](http://yholkamp.github.io/html5_resume_template/template.pdf).

## Usage

* Edit `template.html` and possibly `style.css` and `print.css` to your liking.
* Download [wkhtmltopdf](https://code.google.com/p/wkhtmltopdf/)
* Run `wkhtmltopdf template.html cv.pdf -s A4`
* (Optional) If the output is somehow cut off at the bottom of a page, apply the class `pagebreak` to the last `section` element before the pagebreak. There is a known bug that causes issues with pagebreaks, see [the wkhtmltopdf bugtracker](https://code.google.com/p/wkhtmltopdf/issues/detail?id=9).
* Enjoy the output!
