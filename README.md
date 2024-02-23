This repo contains the code for the [BioHackathon Europe 2024 website](https://biohackathon-europe.org).

## BioHackathon Europe
BioHackathon Europe brings people together from around the world to work on coding projects within life science. The event offers an intense week of hacking, with over 160 participants who work on diverse and exciting projects. The week starts with a half-day symposium to introduce these projects, and is followed by five days of hacking with one sole aim: coding to address problems in bioinformatics. 

## The 2024 BioHackathon
This year's event will take place 4 - 8 November 2024 at Campus Belloch near Barcelona. 

## Previous BioHackathons
For details of the past BioHackathons and their projects see the [ELIXIR Europe website](https://elixir-europe.org/events/biohackathon-europe).

For any questions please contact [biohackathon-europe@elixir-europe.org](mailto:biohackathon-europe@elixir-europe.org).

## Technical notes about the site
The site was built with [Jekyll]|(https://jekyllrb.com/) with the [Bulma Clean theme](https://www.csrhymes.com/bulma-clean-theme/). This theme uses the [Bulma CSS framework](https://bulma.io/). 

The theme is used as a gem theme on GitHub pages, so inherits most of its template files and CSS from the parent theme. 

### Developing the site
If you want to add new features to the site, then first look to see if the feature already exists:

  1. Look at the [Bulma Clean theme demo site](https://www.csrhymes.com/bulma-clean-theme/) and the [repo](https://github.com/chrisrhymes/bulma-clean-theme) behind it. This will give you an idea of the features available.
  2. If nothing you want is there, look at the [Bulma CSS documentation](https://bulma.io/documentation/) to see how you could most simply create the feature you want.
  3. Bear in mind the theme uses [Alpine.js](https://alpinejs.dev/) so that may be useful for interactive elements.

By default, the theme loads a free version of FontAwesome but this has been removed from `_includes/head.html`, because so far the site doesn't use it. You can always add it back in if it is needed. The latest versons are here: https://cdnjs.com/libraries/font-awesome.

Avoid overriding the theme templates if possible, so updates are easier in future.

All CSS changes are done in `assets/app.scss`. 