# A Simple Server Boilerplate

This is starter setup for an ExpressJS server implemented in Coffeescript. It uses the Nunjucks templating engine, and relies on Twitter's Bootstrap as well.

Bootstrap is included as the source LESS files, rather than a compiled CSS, to allow for dynamic adjustments to the Bootstrap variables. You should modify the `variables.less` and `mixins.less` files found directly in `stylesheets`, not under the `bootstrap` folder. This will allow easy upgrades of Bootstrap, and a clear view of deviations from the standard theme.