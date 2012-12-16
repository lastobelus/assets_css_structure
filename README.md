Sandbox for working out a clean SASS/Sprocekets/Zurb-Foundation/SMACSS setup

## Creating the css_canon gem
* a rails generator
* delete application.css
  * strip it of import lines that match import lines in the application.css.scss template
  * strip import lines matching 
* if application.css.scss exists:
  * strip it of sprockets requires
  * strip it of import lines that match import lines in the application.css.scss template
  * add remainder to to_migrate.css.scss
