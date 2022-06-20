# awesome-volto<!-- omit in toc -->

A curated list of things that make Volto awesome. Please feel free to contribute directly or send a PR!
For add-ons for the CMS Plone which is the backend of Volto please see the [awesome-plone list](https://github.com/collective/awesome-plone)


## Contents<!-- omit in toc -->

- [Official websites](#official-websites)
- [Community](#community)
- [Addons](#addons)
  - [Bundles](#bundles)
  - [Rich text editing](#rich-text-editing)
  - [Layout addons](#layout-addons)
  - [Widgets](#widgets)
  - [Themes](#themes)
  - [More](#more)
  - [Plone backend addons for Volto](#plone-backend-addons-for-volto)
- [Training, example code, tutorials](#training-example-code-tutorials)
  - [Awesome React articles, relevant to any Volto developer](#awesome-react-articles-relevant-to-any-volto-developer)
- [Open-source websites built with Volto](#open-source-websites-built-with-volto)
- [Companies](#companies)


## Official websites

- [github.com/plone/volto](https://github.com/plone/volto)
- [Plone 6 - Frontend documentation](https://6.dev-docs.plone.org/volto/)
- [plone.org](https://plone.org)


## Community

- [#volto on Discord](https://discord.com/invite/EtdRAkHu8x )


## Addons

> :warning: While we try to list them all, some of these addons **might be a Work in Progress**, require special branches of Volto or dedicated Plone addons.

Various addons that can't fit in a specific category:

- [volto-cookie-banner](https://github.com/collective/volto-cookie-banner) - Volto cookie banner integration addon. To be used with: `collective.volto.cookieconsent`
- [volto-dropdownmenu](https://github.com/collective/volto-dropdownmenu) - Volto addon for a customizable dropdown menu. Intended to be used with `collective.volto.dropdownmenu`
- [volto-geocoding](https://github.com/collective/volto-geocoding) - A widget for Volto to search addresses and save coordinates.
- [volto-venue](https://github.com/collective/volto-venue) - An addon for Volto as a frontend for `collective.venue`
- [volto-google-analytics](https://github.com/collective/volto-google-analytics) - Google Analytics integration for Volto.
- [volto-social-settings](https://github.com/collective/volto-social-settings) - Add-on for manage a list of social network links on Volto
- [volto-embed](https://github.com/eea/volto-embed) - GDPR compliant external resource embedding Volto Block
- [volto-plotlycharts](https://github.com/eea/volto-plotlycharts) - (EEA) Powerful chart editor based on Plotly
- [volto-block-data-figure](https://github.com/eea/volto-block-data-figure) - (EEA) Volto add-on for Daviz specific SVG charts.
- [volto-datablocks](https://github.com/eea/volto-datablocks) - (EEA) Provides primitives for data connectivity to volto-plotlycharts and other blocks
- [volto-form-builder](https://github.com/kitconcept/volto-form-builder) - A TTW builder of forms
- [volto-corsproxy](https://github.com/eea/volto-corsproxy) - A CORS-proxy integrated with Volto, enables access to third-party API servers.
- [volto-block-toc](https://github.com/eea/volto-block-toc) - An extensible TOC block alternative to Volto's Table of Contents block.
- [volto-matomo](https://github.com/eea/volto-matomo) - Basic Matomo Tracker integration for Volto
- [volto-form-block](https://github.com/collective/volto-form-block) Volto customizable form block
- [volto-subsites](https://github.com/collective/volto-subsites)
- [volto-bookmarks](https://github.com/collective/volto-bookmarks) – Add and manage bookmarks of pages and searchkit queries.
- [volto-slate-glossary](https://github.com/rohberg/volto-slate-glossary) - (WIP) Tooltips for glossary terms
- [volto-plausible](https://github.com/collective/volto-plausible) - Volto integration for Plausible.io privacy-first analytics
- [volto-newsblock](https://github.com/rohberg/volto-newsblock) - Volto block with selected news items
- [volto-authomatic](https://github.com/collective/volto-authomatic) - Social login for Plone ( Using [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic))
- [volto-leaflet-block](https://github.com/adeweb-be/volto-leaflet-block) - A Leaflet map block for Volto
- [volto-fullcalendar-block](https://github.com/mbarde/volto-fullcalendar-block) - A block for adding a [FullCalendar](https://fullcalendar.io/) to display events from an ics/iCal file
- [volto-subfooter](https://github.com/collective/volto-subfooter) Volto addon for a customizable subfooter
- [volto-middleware-static](https://github.com/collective/volto-middleware-static) Volto configurable middleware to serve dynamic static resources
- [volto-taxonomy](https://github.com/eea/volto-taxonomy) - Controlled Vocabulary management in Volto control panel
- [volto-tableau](https://github.com/eea/volto-tableau) - Integration with Tableau
- [volto-openlayers-map](https://github.com/eea/volto-openlayers-map) - Specific implementation of openlayers map
- [volto-sentry-rancher-config](https://github.com/eea/volto-sentry-rancher-config) - Auto-configure Sentry from Rancher metadata
- [volto-banner](https://github.com/eea/volto-banner) - Adds a banner to highlight staging, demo or dev websites
- [volto-listingadvanced-variation](https://github.com/codesyntax/volto-listingadvanced-variation) - Adds a new variation to the listing block with advanced configuration options.
- [volto-staticrender-bots](https://github.com/nzambello/volto-staticrender-bots) - For crawl spiders, serve static rendering of Volto pages
- [volto-arcgis-block](https://github.com/eea/volto-arcgis-block) - ArcGIS Map integration for Volto blocks


### Bundles

- [volto-eea-kitkat](https://github.com/eea/volto-eea-kitkat) - A known good set of Volto add-ons.
- [eea.kitkat](https://github.com/eea/eea.kitkat) - The back-end support for the `volto-eea-kitkat` add-on.

### Rich text editing

Enhance the basic text editing experience

- [volto-slate](https://github.com/eea/volto-slate) - (Almost) drop-in replacement for the Volto richtext editor with multiple enhancements
- [volto-slate-footnote](https://github.com/eea/volto-slate-footnote) - Footnote (and references) plugin for volto-slate.
- [volto-slate-metadata-mentions](https://github.com/eea/volto-slate-metadata-mentions) - Plugin for volto-slate to embed dynamic text that renders Plone metadata fields
- [volto-slate-zotero](https://github.com/eea/volto-slate-zotero) - Plugin for volto-slate to connect footnotes to Zotero and OpenAire references
- [volto-slate-dataentity](https://github.com/eea/volto-slate-dataentity) - Connect text entities in the rich text editor to volto-datablocks connected data
- [volto-workflow-progress](https://github.com/eea/volto-workflow-progress) - Shows workflow steps for content editors.


### Layout addons

Enhancements to the way blocks can be used, to create custom layouts

- [volto-subblocks](https://github.com/collective/volto-subblocks) - A framework to edit and embed blocks into other blocks. (Note: Volto provides a sub-blocks framework that is not compatible with this. Consider looking at volto-columns-block, volto-accordion-block, volto-tabs-block for example if you need to embed block in block).
- [volto-tabs-block](https://github.com/eea/volto-tabs-block) - Split a Volto page into tabs, complete with editing form integration, using just a simple tabs block.
- [volto-metadata-block](https://github.com/eea/volto-metadata-block) - Custom Volto Block to insert Plone metadata fields
- [volto-accordion-block](https://github.com/eea/volto-accordion-block) - Create group based accordions in blocks.
- [volto-columns-block](https://github.com/eea/volto-columns-block) - Enables grouping Volto blocks as columns
- [volto-group-block](https://github.com/eea/volto-group-block) - Group blocks in sections and filter available blocks per content-type per section
- [volto-blocks-grid](https://github.com/kitconcept/volto-blocks-grid) - Unidimensional (x-axis) grids for blocks
- [volto-block-divider](https://github.com/eea/volto-block-divider) - Block to render a section separator
- [volto-pdf-block](https://github.com/eea/volto-pdf-block) - Flexible PDF integration in Volto
- [volto-listing-block](https://github.com/eea/volto-listing-block) - Extension for the Volto listing block adding more templates
- [volto-block-style](https://github.com/eea/volto-block-style) - A generic framework to configure block decorations and CSS styles


### Widgets

Input components, to be reused in the form library

- [volto-object-widget](https://github.com/eea/volto-object-widget) - Widget for generic JS objects
- [volto-widget-geolocation](https://github.com/eea/volto-widget-geolocation) - Geolocation with [GeoNames](https://www.geonames.org/) integration.
- [volto-widget-temporal-coverage](https://github.com/eea/volto-widget-temporal-coverage) - Volto widget: Temporal coverage.
- [volto-widgets-view](https://github.com/eea/volto-widgets-view) - Provides the "view" counterpart for the "edit" widgets in Volto
- [volto-multilingual-widget](https://github.com/collective/volto-multilingual-widget)
- [volto-widget-toggle](https://github.com/eea/volto-widget-toggle/) - Replace checkbox widgets with a visually nicer toggle widget
- [volto-blocks-widget](https://github.com/collective/volto-blocks-widget) - Volto addon to use blocks inside fields
- [volto-vocabulary-icons-widget](https://github.com/collective/volto-vocabulary-icons-widget) -  Widget to edit vocabularies where term key is associated with a Fontawesome icon.
- [volto-react-table-widget](https://github.com/eea/volto-react-table-widget) - Widget to replace Volto's ObjectListWidget to edit data-grid like widgets in a more performant way with a table based on [react-table](https://tanstack.com/table/v8/)
- [volto-image-crop-widget](https://github.com/mbarde/volto-image-crop-widget) - Extends built-in FileWidget to be able to crop images in-place

### Themes

- [volto-sustainability-theme](https://github.com/eea/volto-sustainability-theme) - Volto Theme for "Sustainability transitions, EEA-Eionet platform"
- [volto-ims-theme](https://github.com/eea/volto-ims-theme) - Volto theme for "European Environment Agency's Indicator Management System"
- [volto-forests-theme](https://github.com/eea/volto-forests-theme) - Volto theme for "Forest Information System For Europe"
- [volto-energy-theme](https://github.com/eea/volto-energy-theme) - Volto theme for "Climate and energy in the EU"
- [volto-quanta](https://github.com/plone/volto-quanta) - A new theme for Volto, right now only styles a few form controls

### More

- See all [volto-addon](https://www.npmjs.com/search?q=keywords:volto-addon) tagged packages on NPM.

### Plone backend addons for Volto

- [github.com/plone/plone.volto](https://github.com/plone/plone.volto) - Official Volto integration package for Plone.
- [collective.volto.dropdownmenu](https://github.com/collective/collective.volto.dropdownmenu) - Add-on for manage a `Dropdown Menu` in Volto.
- [collective.volto.subsites](https://github.com/collective/collective.volto.subsites) - This add-on enable a new Subsite content-type and provides some utilities for Volto.
- [collective.volto.formsupport](https://github.com/collective/collective.volto.formsupport) - Add some helper routes and functionalities for Volto sites with form blocks provided by `volto-form-block` Volto plugin.
- [collective.bookmarks](https://github.com/collective/collective.bookmarks) -Bookmarks (aka favorites, wishlists). The Plone pendent is `volto-bookmarks`
- [collective.volto.secondarymenu](https://github.com/collective/collective.volto.secondarymenu) - Add-on for Volto to manage a secondary menu (right column) for `Dropdown Menu`
- [collective.volto.blocksfield](https://github.com/collective/collective.volto.blocksfield) - Custom z3c.form field that allows to use Volto blocks. This field can replace RichText fields in your custom content-types.
- [collective.volto.socialsettings](https://github.com/collective/collective.volto.socialsettings) - Add-on for manage a list of social network links on Volto
- [eea.api.layout](https://github.com/eea/eea.api.layout) - DX fixed blocks layout behavior with auto-sync support
- [eea.schema.slate](https://github.com/eea/eea.schema.slate) - DX TTW Slate JSONField to be used with DX Content-Types metadata and `volto-slate`


## Training, example code, tutorials

- Several online training sessions have been recorded, they are available on youtube by searching [volto training](https://www.youtube.com/results?search_query=volto+training)
- Volto – [Create your own site using Volto.](https://training.plone.org/5/volto/index.html)
- Volto Hands-On – [Practice your skills by recreating the plone.com site using Volto.](https://training.plone.org/5/voltohandson/index.html)
- Volto Add-ons Development – [Build custom Volto add-ons, explore more advanced Volto topics.](https://training.plone.org/5/voltoaddons/index.html)
- Mastering Plone 6 Development – [Learn the best practices of Plone development for frontend and backend using Volto as well as Plone Classic.](https://training.plone.org/5/mastering-plone/index.html)
- [Demo project for Volto addons](https://github.com/collective/volto-example-project-addons)


### Awesome React articles, relevant to any Volto developer

- [Writing resilient react components](https://overreacted.io/writing-resilient-components/)
- [React rendering behavior](https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/)
- [React Algebraic Effects](https://blog.reesew.io/algebraic-effects-for-react-developers?x-host=blog.reesew.io )
- [Code Splitting - deeper understanding](https://medium.com/1mgofficial/code-splitting-ssr-lazy-loading-react-components-a-deeper-understanding-part-1-7d714196706)
- [High Performance React](https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3)
- [A Complete Guide to useEffect (and more)](https://overreacted.io/a-complete-guide-to-useeffect/#why-usereducer-is-the-cheat-mode-of-hooks)
- [On the intricacies on React's onClick event handlers](https://dev.to/dvnrsn/why-isn-t-event-stoppropagation-working-1bnm)
- [React rendering order](https://imkev.dev/react-rendering-order)
- [Using AbortController to deal with race conditions](https://wanago.io/2022/04/11/abort-controller-race-conditions-react/)


## Open-source websites built with Volto

- [Forest Information System for Europe](https://github.com/eea/forests-frontend) - Volto project for https://forest.eea.europa.eu
- [Freshwater Information System for Europe](https://github.com/eea/freshwater-frontend) - Volto project for https://water.europa.eu/freshwater
- [European Industrial Emissions Portal](https://github.com/eea/industry-frontend ) - Volto project for https://industry.eea.europa.eu
- [Biodiversity Information System for Europe](https://github.com/eea/bise-frontend) - Volto project for https://biodiversity.europa.eu
- [Sustainability transitions, EEA-Eionet platform](https://github.com/eea/sustainability-frontend) - Volto project for https://sustainability.eionet.europa.eu
- [EEA Indicator Management System](https://github.com/eea/ims-frontend) - Volto project for https://www.eea.europa.eu/ims
- [Climate and energy in the EU](https://github.com/eea/climate-energy-frontend) - Volto project for https://climate-energy.eea.europa.eu
- [volto-bise](https://github.com/eea/volto-bise) - A Volto project packaged as an addon. It provides theming using a razzle.extend.js provided alias.
- [design-volto-theme](https://github.com/RedTurtle/design-volto-theme)
- [2021.ploneconf.org](https://github.com/plone/ploneconf.org) - Volto project for https://2021.ploneconf.org


## Companies

- [kitconcept](https://kitconcept.com/)
- [Redturtle](https://www.redturtle.it/)
- [Eau de Web](https://www.eaudeweb.ro/)
- [Rohberg](https://www.rohberg.ch/de)
- [Simples Consultoria](https://www.simplesconsultoria.com.br/)
- [CodeSyntax](https://www.codesyntax.com/en?set_language=en)
- [RawMaterial](https://rawmaterial.it/en)
- ... please add yourself here
