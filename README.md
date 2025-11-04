# awesome-volto<!-- omit in toc -->

A curated list of things that make Volto awesome. Please feel free to contribute directly or send a PR!
For add-ons for the CMS Plone which is the backend of Volto please see the [awesome-plone list](https://github.com/collective/awesome-plone)


## Contents<!-- omit in toc -->

- [Official websites](#official-websites)
- [Community](#community)
- [Add-ons](#add-ons)
  - [Bundles](#bundles)
  - [Rich text editing](#rich-text-editing)
  - [Layout add-ons](#layout-add-ons)
  - [Widgets](#widgets)
  - [Themes](#themes)
  - [More](#more)
  - [Plone backend add-ons for Volto](#plone-backend-add-ons-for-volto)
- [Training, example code, tutorials](#training-example-code-tutorials)
  - [Awesome React articles, relevant to any Volto developer](#awesome-react-articles-relevant-to-any-volto-developer)
- [Open-source websites built with Volto](#open-source-websites-built-with-volto)
- [Companies](#companies)


## Official websites

- [github.com/plone/volto](https://github.com/plone/volto)
- [Plone 6 - Frontend documentation](https://6.docs.plone.org/volto/)
- [plone.org](https://plone.org)


## Community

- [#volto on Discord](https://discord.com/invite/EtdRAkHu8x )


## Add-ons

> :warning: While we try to list them all, some of these add-ons **might be a Work in Progress**, require special branches of Volto or dedicated Plone add-ons.

Various add-ons that can't fit in a specific category, in mostly random order:

- [volto-site-settings](https://github.com/collective/volto-site-settings) - Makes available the site settings to any Volto block / component.
- [volto-outdooractive](https://github.com/collective/volto-outdooractive) - Integration with OutdoorActive, an external service
- [volto-middleware-helmet](https://github.com/collective/volto-middleware-helmet) - Middleware to add security to Volto's HTTP headers
- [volto-customer-satisfaction](https://github.com/collective/volto-customer-satisfaction) - Gather feedback from site users
- [volto-tito-block](https://github.com/collective/volto-tito-block) - Volto block to integrate with Tito, a platform to sell tickets online
- [volto-block-banner](https://github.com/collective/volto-block-banner) - Volto block for a customizable visual banner
- [volto-cookie-banner](https://github.com/collective/volto-cookie-banner) - Volto cookie banner integration add-on. To be used with: `collective.volto.cookieconsent`
- [volto-dropdownmenu](https://github.com/collective/volto-dropdownmenu) - Volto add-on for a customizable dropdown menu. Intended to be used with `collective.volto.dropdownmenu`
- [volto-navigation-dropdown](https://github.com/kenmanheimer/volto-navigation-dropdown) - Volto add-on for Plone website navigation dropdown menus.
- [volto-menu-customization](https://github.com/codesyntax/volto-menu-customization) - Volto add-on provides a customization of Volto's default menu that adds a dropdown menu to display subcontent.
- [volto-geocoding](https://github.com/collective/volto-geocoding) - A widget for Volto to search addresses and save coordinates.
- [volto-venue](https://github.com/collective/volto-venue) - An add-on for Volto as a frontend for `collective.venue`
- [volto-google-analytics](https://github.com/collective/volto-google-analytics) - Google Analytics integration for Volto.
- [volto-social-settings](https://github.com/collective/volto-social-settings) - Add-on for manage a list of social network links on Volto
- [volto-controlpanel](https://github.com/eea/volto-controlpanel) - Enhance Version Overview information in Control Panel. Requires `eea.api.controlpanel` Plone backend add-on.
- [volto-embed](https://github.com/eea/volto-embed) - GDPR compliant external resource embedding Volto Block
- [volto-plotlycharts](https://github.com/eea/volto-plotlycharts) - (EEA) Powerful chart editor based on Plotly
- [volto-flourish](https://github.com/eea/volto-flourish) - (EEA) Embed Flourish visualizations.
- [volto-block-data-figure](https://github.com/eea/volto-block-data-figure) - (EEA) Volto add-on for Daviz specific SVG charts.
- [volto-datablocks](https://github.com/eea/volto-datablocks) - (EEA) Provides primitives for data connectivity to volto-plotlycharts and other blocks
- [volto-corsproxy](https://github.com/eea/volto-corsproxy) - A CORS-proxy integrated with Volto, enables access to third-party API servers.
- [volto-block-toc](https://github.com/eea/volto-block-toc) - An extensible TOC block alternative to Volto's Table of Contents block.
- [volto-matomo](https://github.com/eea/volto-matomo) - Basic Matomo Tracker integration for Volto
- [volto-form-block](https://github.com/collective/volto-form-block) Volto customizable form block
- [volto-subsites](https://github.com/collective/volto-subsites)
- [volto-bookmarks](https://github.com/collective/volto-bookmarks) – Add and manage bookmarks of pages and searchkit queries.
- [volto-slate-glossary](https://github.com/rohberg/volto-slate-glossary) - Tooltips for glossary terms
- [volto-plausible](https://github.com/collective/volto-plausible) - Volto integration for Plausible.io privacy-first analytics
- [volto-newsblock](https://github.com/rohberg/volto-newsblock) - Volto block with selected news items
- [@plone-collective/volto-authomatic](https://github.com/collective/volto-authomatic) - Social (OpenID) login for Plone ( Using [pas.plugins.authomatic](https://github.com/collective/pas.plugins.authomatic))
- [volto-leaflet-block](https://github.com/adeweb-be/volto-leaflet-block) - A Leaflet map for Volto block
- [volto-fullcalendar-block](https://github.com/mbarde/volto-fullcalendar-block) - A block for adding a [FullCalendar](https://fullcalendar.io/) to display events from an ics/iCal file
- [volto-subfooter](https://github.com/collective/volto-subfooter) Volto add-on for a customizable subfooter
- [volto-footer](https://github.com/collective/volto-footer) - Volto add-on for a customizable block-based footer. Allows adding any type of block to create rich, dynamic footer content, with automatic inheritance from the closest footer configuration. Requires [collective.volto.footer](https://github.com/collective/collective.volto.footer) backend add-on.
- [volto-middleware-static](https://github.com/collective/volto-middleware-static) Volto configurable middleware to serve dynamic static resources
- [volto-taxonomy](https://github.com/eea/volto-taxonomy) - Controlled Vocabulary management in Volto control panel
- [volto-tableau](https://github.com/eea/volto-tableau) - Integration with Tableau
- [volto-openlayers-map](https://github.com/eea/volto-openlayers-map) - Specific implementation of OpenLayers map
- [volto-sentry-rancher-config](https://github.com/eea/volto-sentry-rancher-config) - Auto-configure Sentry from Rancher metadata
- [volto-banner](https://github.com/eea/volto-banner) - Adds a banner to highlight staging, demo or dev websites
- [volto-listingadvanced-variation](https://github.com/codesyntax/volto-listingadvanced-variation) - Adds a new variation to the listing block with advanced configuration options.
- [volto-staticrender-bots](https://github.com/nzambello/volto-staticrender-bots) - For crawl spiders, serve static rendering of Volto pages
- [volto-arcgis-block](https://github.com/eea/volto-arcgis-block) - ArcGIS Map integration for Volto blocks
- [volto-carousel-block](https://github.com/kitconcept/volto-carousel-block) - A carousel block, with slick integration
- [volto-separator-block](https://github.com/kitconcept/volto-separator-block) - A divider visual indicator type of block
- [volto-slider-block](https://github.com/kitconcept/volto-slider-block) - A slider with react-slick
- [volto-blocks](https://github.com/kitconcept/volto-blocks) - Miscellaneous blocks
- [volto-dsgvo-banner](https://github.com/kitconcept/volto-dsgvo-banner) - A privacy protection / GDPR banner (mandatory in Europe)
- [volto-button-block](https://github.com/kitconcept/volto-button-block) - A button (call to action) block
- [volto-heading-block](https://github.com/kitconcept/volto-heading-block) - A heading block. Can select the heading level
- [volto-text-with-background-color-block](https://github.com/kitconcept/volto-text-with-background-color-block) A Volto Text With Background Color Block allows editors to add text with a background color to a Volto page
- [volto-social-blocks](https://github.com/kitconcept/volto-social-blocks) - A Social Blocks support for Volto block
- [volto-code-block](https://github.com/plonegovbr/volto-code-block) - Insert code blocks, with syntax highlight, into Volto.
- [volto-twitter-block](https://github.com/plonegovbr/volto-twitter-block) - Embed Tweets into Volto pages.
- [volto-social-sharing](https://github.com/codesyntax/volto-social-sharing) - Show "share in social networks" links in pages.
- [volto-network-block](https://github.com/plonegovbr/volto-network-block) - Volto Social Networks blocks and components.
- [volto-educal-hero-block](https://github.com/collective/volto-educal-hero-block) - Volto block for a customizable visual hero
- [volto-cookiebot](https://github.com/codesyntax/volto-cookiebot) - [CookieBot](https://www.cookiebot.com/) integration package for Volto. CookieBot is a comercial service to comply with the so-called "cookie-law", asking user content before loading any third-party cookie.
- [volto-countdown-block](https://github.com/rnunez80/volto-countdown-block) - A Volto block to count down to any date specified, with optional display of hours, minutes and seconds.
- [volto-advanced-variations](https://github.com/rnunez80/volto-advanced-variations) - Based on codesyntax/volto-listingadvanced-variation this add-on adds events options including dates, times and location, displaying the listing or search as a carousel/slider or background image.
- [volto-existing-block](https://github.com/rnunez80/volto-existing-block) - A Volto block that show content from another page based on the id selected.
- [volto-modal-block](https://github.com/rnunez80/volto-modal-block) - A Volto add-on block that has a button with image when clicked it open the text in an overlay.
- [@codesyntax/volto-maplibre-block](https://github.com/codesyntax/volto-maplibre-block) - A Volto block and component to render maps based on [maplibre-gl-js](https://maplibre.org/maplibre-gl-js/docs/)
- [@codesyntax/volto-countup-block](https://github.com/codesyntax/volto-countup-block) - A Volto block to show a going-up counter
- [volto-videohero-block](https://github.com/rnunez80/volto-videohero-block) - a hero section with a video background, and optional preheader, title, description, call-to-actions and more.
- [volto-chatbot](https://github.com/eea/volto-chatbot) - Volto Chatbot allows the integration of an AI-powered chatbot into your Volto project with [Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx) AI Assistant connected to your company's docs, apps, and people.
- [volto-page-displayer](https://github.com/Kreablo/volto-page-displayer) - A Volto block used for displaying other Volto pages. Features loop detection and a Listing variation.



### Bundles

- [volto-eea-kitkat](https://github.com/eea/volto-eea-kitkat) - A "known good set" of Volto add-ons, mostly specific to EEA websites.
- [eea.kitkat](https://github.com/eea/eea.kitkat) - The back-end support for the `volto-eea-kitkat` add-on.

### Rich text editing

Enhance the basic text editing experience

- [volto-slate-footnote](https://github.com/eea/volto-slate-footnote) - Footnote (and references) plugin for the rich text editor.
- [volto-slate-metadata-mentions](https://github.com/eea/volto-slate-metadata-mentions) - Plugin for the rich text editor to embed dynamic text that renders Plone metadata fields
- [volto-slate-zotero](https://github.com/eea/volto-slate-zotero) - Plugin for the rich text editor to connect footnotes to Zotero and OpenAire references
- [volto-slate-dataentity](https://github.com/eea/volto-slate-dataentity) - Connect text entities in the rich text editor to volto-datablocks connected data
- [volto-workflow-progress](https://github.com/eea/volto-workflow-progress) - Shows workflow steps for content editors.

### Layout add-ons

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
- [volto-anchors](https://github.com/eea/volto-anchors) - Slug based anchor links for volto blocks
- [volto-statistic-block](https://github.com/eea/volto-statistic-block) - A Statistic Text for Volto blocks
- [volto-featured-block](https://github.com/codesyntax/volto-featured-block): Volto block to create pages with arbitrary content based on a simple schema (title + text + image), with variation support, and  not based on existing content of the site (in contraposition to teaser blocks being based on existing content of the site)

### Widgets

Input components, to be reused in the form library

- [volto-vocabulary-icons-widget](https://github.com/collective/volto-vocabulary-icons-widget) - Widget to edit vocabularies where term key is associated with a Fontawesome icon. Volto add-on for vocabularies with icons
- [volto-object-widget](https://github.com/eea/volto-object-widget) - Widget for generic JS objects
- [volto-widget-geolocation](https://github.com/eea/volto-widget-geolocation) - Geolocation with [GeoNames](https://www.geonames.org/) integration.
- [volto-widget-temporal-coverage](https://github.com/eea/volto-widget-temporal-coverage) - Volto widget: Temporal coverage.
- [volto-widgets-view](https://github.com/eea/volto-widgets-view) - Provides the "view" counterpart for the "edit" widgets in Volto
- [volto-multilingual-widget](https://github.com/collective/volto-multilingual-widget) - Enabled multi-language editing of data, used internally by the cookie consent add-on
- [volto-widget-toggle](https://github.com/eea/volto-widget-toggle/) - Replace checkbox widgets with a visually nicer toggle widget
- [volto-blocks-widget](https://github.com/collective/volto-blocks-widget) - Volto add-on to use blocks inside fields
- [volto-react-table-widget](https://github.com/eea/volto-react-table-widget) - Widget to replace Volto's ObjectListWidget to edit data-grid like widgets in a more performant way with a table based on [react-table](https://tanstack.com/table/v8/)
- [volto-image-crop-widget](https://github.com/mbarde/volto-image-crop-widget) - Extends built-in FileWidget to be able to crop images in-place
- [volto-data-grid-widget](https://github.com/collective/volto-data-grid-widget) - A field to edit lists of data in a data-grid like fashion. Please note that Volto ships already with a widget for "lists of data", the ObjectListWidget, which uses an accordion for the list.
- [volto-icon-selector-widget](https://github.com/affinitic/volto-icon-selector-widget) - A widget to search and select an icon from a list, by default it use awesome font icon implementation in semantic ui, but it can be customized.
- [volto-widget-theme-picker](https://github.com/eea/volto-widget-theme-picker) - A theme color picker for themes in Volto blocks
- [volto-doublerange-facet](https://github.com/eea/volto-doublerange-facet) - Adds a double range facet filter to the Volto Search block

### Themes

- [volto-eea-website-theme](https://github.com/eea/volto-eea-website-theme) - Volto Theme for [European Environment Agency web sites](https://www.eea.europa.eu/en)
- [volto-forests-theme](https://github.com/eea/volto-forests-theme) - Volto theme for "Forest Information System For Europe"
- [volto-energy-theme](https://github.com/eea/volto-energy-theme) - Volto theme for "Climate and energy in the EU"
- [volto-quanta](https://github.com/plone/volto-quanta) - A new theme for Volto, right now only styles a few form controls
- [volto-theme-plone-regional](https://github.com/kitconcept/volto-theme-plone-regional) - Volto Theme for Plone regional sites (i.e. plone.de, plone.org.br)
- [volto-educal-theme](https://github.com/collective/volto-educal-theme) - Volto theme for Educational websites
- [volto-museumhilversum-theme](https://github.com/intk/volto-museumhilversum-theme) - Volto theme for [Museum Hilversum](https://www.museumhilversum.nl/en)
- [volto-intkwebsite-theme](https://github.com/intk/volto-intkwebsite-theme) - Volto theme for [INTK](https://www.intk.com/en)
- [volto-theme-twenty-twenty-one](https://github.com/kitconcept/volto-theme-twenty-twenty-one) - Volto "Twenty Twenty One" theme
- [volto-brasil-theme](https://github.com/plonegovbr/volto-brasil-theme) - Volto visual theme for "PortalBrasil" / Tema visual para o PortalBrasil
- [volto-dsgov-theme](https://github.com/f4biosa/volto-dsgov-theme) - Volto visual theme for "DSGov" / Tema visual para Volto baseado no DSGov
- [volto-pimaker-theme](https://github.com/Fosten/volto-pimaker-theme) - Plone 6 Volto Theme for "Pi Maker"
- [volto-happy-theme](https://github.com/Fosten/volto-happy-theme) - Plone 6 Volto Theme for "Happy Baseball"
- [volto-light-theme](https://github.com/kitconcept/volto-light-theme) - Plone 6 Volto Light Theme (by kitconcept)
- [volto-mountain-theme](https://github.com/Fosten/volto-mountain-theme) - Plone 6 Volto Theme for "Mountain"
- [volto-itxbb-theme](https://github.com/Fosten/volto-itxbb-theme) - Plone 6 Volto Theme for "In The Stix Broadband"
- [zeeuwsmuseum-jaarverslag](https://github.com/cihanandac/zeeuwsmuseum-jaarverslag) - Plone 6 Volto Theme for "ANNUAL REPORTS" of Centraal Museum & Rietveld.


### More

- See all [volto-add-on](https://www.npmjs.com/search?q=keywords:volto-add-on) and [volto-addon](https://www.npmjs.com/search?q=keywords:volto-addon) tagged packages on NPM.

### Plone backend add-ons for Volto

- [plone.volto](https://github.com/plone/plone.volto) - Official Volto integration package for Plone.
- [collective.volto.dropdownmenu](https://github.com/collective/collective.volto.dropdownmenu) - Add-on for manage a `Dropdown Menu` in Volto.
- [collective.volto.footer](https://github.com/collective/collective.volto.footer) - Backend add-on for `volto-footer` to manage a customizable footer in Volto.
- [collective.volto.subsites](https://github.com/collective/collective.volto.subsites) - This add-on enable a new Subsite content-type and provides some utilities for Volto.
- [collective.volto.formsupport](https://github.com/collective/collective.volto.formsupport) - Add some helper routes and functionalities for Volto sites with form blocks provided by `volto-form-block` Volto plugin.
- [collective.bookmarks](https://github.com/collective/collective.bookmarks) -Bookmarks (aka favorites, wishlists). The Plone pendent is `volto-bookmarks`
- [collective.volto.secondarymenu](https://github.com/collective/collective.volto.secondarymenu) - Add-on for Volto to manage a secondary menu (right column) for `Dropdown Menu`
- [collective.volto.blocksfield](https://github.com/collective/collective.volto.blocksfield) - Custom z3c.form field that allows to use Volto blocks. This field can replace RichText fields in your custom content-types.
- [collective.volto.socialsettings](https://github.com/collective/collective.volto.socialsettings) - Add-on for manage a list of social network links on Volto
- [eea.api.controlpanel](https://github.com/eea/eea.api.controlpanel) - Backend add-on to be used with `volto-controlpanel`
- [eea.api.layout](https://github.com/eea/eea.api.layout) - DX fixed blocks layout behavior with auto-sync support
- [eea.schema.slate](https://github.com/eea/eea.schema.slate) - DX TTW Slate JSONField to be used with DX Content-Types metadata and `volto-slate`
- [volto-plone-reloader](https://github.com/instification/volto-plone-reloader) (volto add-on) - Use [plone.reload](https://github.com/plone/plone.reload)'s `/@@reload` feature through a volto frontend


## Training, example code, tutorials

- Several online training sessions have been recorded, they are available on Youtube by searching [volto training](https://www.youtube.com/results?search_query=volto+training)
- [Volto Hands-On](https://2024.training.plone.org/voltohandson/index.html) – Practice your skills by recreating the plone.com site using Volto.
- [Volto Add-ons Development](https://2024.training.plone.org/voltoaddons/index.html) – Build custom Volto add-ons, explore more advanced Volto topics.
- [Mastering Plone 6 Development](https://training.plone.org/mastering-plone/index.html) – Learn the best practices of Plone development for frontend and backend using Volto as well as Plone Classic.
- [Volto Customization for JavaScript Beginners](https://training.plone.org/volto-customization/index.html) - Master Volto customization from the ground up.
- [Effective Volto](https://2024.training.plone.org/effective-volto/index.html) - Learn advanced topics, good practices, and build upon your basic experience with Volto.
- [Demo project for Volto add-ons](https://github.com/collective/volto-example-project-addons)


### Awesome React articles, relevant to any Volto developer

- [Writing resilient react components](https://overreacted.io/writing-resilient-components/)
- [React rendering behavior](https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/)
- [React Algebraic Effects](https://web.archive.org/web/20240910104622/https://blog.reesew.io/algebraic-effects-for-react-developers)
- [Code Splitting - deeper understanding](https://medium.com/1mgofficial/code-splitting-ssr-lazy-loading-react-components-a-deeper-understanding-part-1-7d714196706)
- [High Performance React](https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3)
- [A Complete Guide to useEffect (and more)](https://overreacted.io/a-complete-guide-to-useeffect/#why-usereducer-is-the-cheat-mode-of-hooks)
- [On the intricacies on React's onClick event handlers](https://dev.to/dvnrsn/why-isn-t-event-stoppropagation-working-1bnm)
- [React rendering order](https://imkev.dev/react-rendering-order)
- [Using AbortController to deal with race conditions](https://wanago.io/2022/04/11/abort-controller-race-conditions-react/)
- [Exploring Render Props Vs. React Hooks In 2020](https://hackernoon.com/exploring-render-props-vs-react-hooks-in-2020-xg1b3uko)


## Websites built with Volto

The Plone Marketing Team copy-pastes the content of this section on a quarterly basis into [They use Plone 6](https://plone.org/why-plone/they-use-plone/they-use-plone-6).

To ensure your website gets the greatest exposure, add it both to Awesome Volto and the [Volto `README.md` under "Volto in production"](https://github.com/plone/volto/tree/main?tab=readme-ov-file#volto-in-production).

- [ASP Area Nord](https://www.aspareanord.it/) (Website of the Public company of personal services of the Modena municipalities in the north area. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Baccanale Imola](https://www.baccanaleimola.it) (Baccanale is a food fair that happens every year in Imola, Italy. Developed by [RedTurtle](https://www.redturtle.it), 2020)
- [Biblioteche Pianura Est](https://bibest.it/it) (Website of the Associated libraries of eastern plain. Developed by [RedTurtle](https://www.redturtle.it/), 2021)
- [BISE](https://biodiversity.europa.eu) (Biodiversity Information System for Europe, developed by [Eau de Web](https://eaudeweb.ro/), 2019)
- [Camera di Commercio dell'Umbria](https://www.umbria.camcom.it) (Website Chamber of Commerce of Umbria. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Camera di Commercio di Reggio Emilia](https://www.emilia.camcom.it) (Website Chamber of Commerce of Reggio Emilia. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Camposanto](https://www.comune.camposanto.mo.it/) (Website of the Municipality of Camposanto. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Cantagallo](https://www.comune.cantagallo.po.it/) (Website of the Municipality of Cantagallo. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Medolla](https://www.comune.medolla.mo.it/) (Website of the Municipality of Medolla. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Mirandola](https://www.comune.mirandola.mo.it/) (Website of the Municipality of Mirandola. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Modena](https://www.comune.modena.it/) (Website of the Municipality of Modena. Developed by [RedTurtle](https://www.redturtle.it), 2020)
- [Comune di San Possidonio](https://www.comune.sanpossidonio.mo.it/) (Website of the Municipality of San Possidonio. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Vaiano](https://www.comune.vaiano.po.it/) (Website of the Municipality of Vaiano. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Comune di Vernio](https://www.comune.vernio.po.it/) (Website of the Municipality of Vernio. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [Copernicus In-Situ](https://insitu.copernicus.eu) (Copernicus In-Situ compiles and provides high-quality ground, sea and airborne observation and geospatial reference data to support the Copernicus services. Developed by [Eau de web](https://eaudeweb.ro) for the European Environmental Agency, 2025)
- [Copernicus Land Monitoring Service](https://land.copernicus.eu) (The Copernicus Land Monitoring Service (CLMS) delivers high-quality geospatial information on land cover, land use changes, vegetation state, the water cycle and Earth's surface energy variables. Developed by [CodeSyntax](https://www.codesyntax.com/en) and [Eau de web](https://eaudeweb.ro) for the European Environmental Agency, 2023)
- [Debabarreneko mankomunitatea](https://debabarrena.eus/eu) (Website of the Commonwealth of Debabarrena, community of municipalities to centralize waste handling services, developed by [CodeSyntax](https://www.codesyntax.com/en), 2022)
- [Debako Udala / Ayuntamiento de Deba](https://www.deba.eus/eu) (Website of the municipality of Deba, developed by [CodeSyntax](https://www.codesyntax.com/en), 2022)
- [European Environment Agency](https://www.eea.europa.eu/en) (Website of the European Environment Agency. Developed by [Eau de Web](https://eaudeweb.ro), 2023)
- Excellence at Humboldt-Universität zu Berlin (Website for the excellence initiative of the [Humboldt University Berlin](https://www.hu-berlin.de/de), developed by [kitconcept GmbH](https://kitconcept.com/en), 2019)
- [Film Basque Country](https://www.filmbasquecountry.eus/en) (Website to attract, guide, and support international productions, making it easier for them to film in the Basque Country, developed by [CodeSyntax](https://www.codesyntax.com/en), 2025)
- [Forest Information System for Europe](https://forest.eea.europa.eu) (Thematic website focusing on European forests, developed by [Eau de Web](https://eaudeweb.ro/), 2019)
- [Forschungszentrum Jülich](https://www.fz-juelich.de/de) (Website for Forschungzentrum Jülich, which is one of the largest research institutions in Europe, developed by [kitconcept GmbH](https://kitconcept.com/en), 2022)
- [Geosphere Austria](https://www.geosphere.at/de) (Website of the Austrian Federal Institute, national geological, geophysical, climatological and meteorological service, 2023)
- [German Aerospace Center (DLR)](https://www.dlr.de/de) (The German Aerospace Center (DLR) is the Federal Republic of Germany's research center for aeronautics. With more than 10.000 employees and a yearly budget of more than 1 billion euros, it is one of the largest research institutions in Germany, developed by [kitconcept GmbH](https://kitconcept.com/en), 2023)
- [Helmholtz-Institut Erlangen-Nürnberg für Erneuerbare Energien (HI-ERN)](https://www.hi-ern.de/de) (Website for HI ERN, a research institution for renewable energies, developed by [kitconcept GmbH](https://kitconcept.com/en), 2022)
- [Humboldt Labor](https://www.humboldtforum.org/de/programm/dauerangebot/ausstellung/nach-der-natur-14144/) (The Humboldt Lab is a website where the Humboldt University Berlin presents its latest research projects and findings. Developed by [WLDX](https://wldx.de/) and [kitconcept GmbH](https://kitconcept.com/en), 2020)
- [ILPO](https://ilpo.jyu.fi/) (the registration portal of continuous learning at the University of Jyväskylä. Developed by University of Jyväskylä, 2022)
- [Industrial Emissions portal for Europe](https://industry.eea.europa.eu) (Thematic website focusing on European industrial emissions, developed by [Eau de Web](https://eaudeweb.ro/), 2020)
- [Interpretare.ro](https://www.interpretare.ro) (Romanian medical imaging interpretation service allowing patients to submit MRI, CT, and other diagnostic imaging for professional evaluation by medical specialists, 2022)
- [iTlent - Basque Institute of Talent in VET](https://www.itlent.eus/en) (developed by [CodeSyntax](https://www.codesyntax.com/en), 2024)
- [Jobfamilie MEDICE](https://jobfamilie.medice.de/de) (Carrer website for MEDICE Arzneimittel Pütter GmbH & Co. KG), developed by [Werkbank GmbH](https://werkbank.de/), 2020)
- [Lanku](https://www.lanku.eus) (Website for Lanku Kultur Zerbitzuak, a company offering cultural services and improvised Basque verse singing sessions across the Basque Country, developed by [CodeSyntax](https://www.codesyntax.com/en), 2023)
- [Leibniz Institute for Science and Mathematics Education (IPN)](https://www.leibniz-ipn.de/de) (Website of the IPN, a research institute dedicated to issues related to learning and teaching of science, mathematics and computer science in and outside of schools, developed by [Starzel](https://www.starzel.de), 2023)
- [Nuova Voce Ecologista](https://nuovavoceecologista.it) (Website of Nuova Voce Ecologista, an Italian green Party, 2020)
- [Osaka University](https://www.osaka-u.ac.jp/en) (Osaka University is considered one of the most prestigious universities in Japan. Developed by [CMScom](https://www.cmscom.jp), 2021)
- [Portknox.net](https://portknox.net/de) (Portknox.net is a specialized Nextcloud hosting provider from Germany, developed by [Starzel](https://www.starzel.de/), 2025)
- [ResOU](https://resou.osaka-u.ac.jp/ja) (ResOU is introducing official researched releases by the University of Osaka, Japan. Developed by [CMScom](https://www.cmscom.jp), 2020)
- [Stradanove](https://www.stradanove.it/) (Website of the Department of Youth Policies of the Municipality of Modena, developed by [RedTurtle](https://www.redturtle.it), 2020)
- [Study guide at University of Jyväskylä](https://studyguide.jyu.fi/2020/en/) (Static website where [Volto is used as a headless CMS for authoring additional content](https://tech.blog.jyu.fi/2020/06/plone-volto-hasura-gatsbyjs-mashup/), 2020)
- [Study in Denmark](https://studyindenmark.dk) (Study in Denmark is a Plone 6 website promoting higher education opportunities in Denmark. Developed by [Eau de web](https://eaudeweb.ro) for the Danish Ministry of Higher Education and Science, 2025)
- [Talke Carrer Website](https://karriere.talke.com/) (Carrer website for [Talke](https://www.talke.com), one of the leading a chemical and petrochemical logistics companies in Germany, developed by [kitconcept GmbH](https://kitconcept.com/en), 2020)
- [UEU](https://www.ueu.eus) (Website for Udako Euskal Unibertsitatea, a non-profit University offering all its service only in Basque: courses, publications, ... developed by [CodeSyntax](https://www.codesyntax.com/en), 2023)
- [Unione dei Comuni della Val Bisenzio](https://www.bisenzio.it/) (Website of the Municipality union of Val Bisenzio. Developed by [RedTurtle](https://www.redturtle.it), 2021)
- [VHS Ehrenamtsportal](https://vhs-ehrenamtsportal.de) (Website to help volunteers that help refugees for the [German Adult Education Association](https://www.volkshochschule.de/), developed by [kitconcept GmbH](https://kitconcept.com/en), 2018)
- [VisitModena](https://www.visitmodena.it/it) (Tourist website of the Municipality of Modena, developed by [RedTurtle](https://www.redturtle.it), 2020)
- [WISE-Freshwater](https://water.europa.eu/freshwater) (WISE-Freshwater, the Freshwater Information System for Europe. Developed by [Eau de web](https://eaudeweb.ro) for the European Environmental Agency, 2021)
- [WISE-Marine](https://water.europa.eu/marine) (WISE-Marine, the Marine Information System for Europe. Developed by [Eau de web](https://eaudeweb.ro) for the European Environmental Agency, 2023)
- [Zeelandia](https://www.zeelandia.de/) (Corporate website for one of the leading bakery ingredients manufacturers in Germany, developed by [kitconcept GmbH](https://kitconcept.com/en), 2019)

### Open-source websites built with Volto

The following websites have been built with Volto. You can find their complete source code by following their links. Please note that complex websites are built on top of Volto add-ons, and most of the time they're just an empty shell for the add-ons. You should check the dependencies in their `package.json` for more details.

The Plone Marketing Team copy-pastes the content of this section on a quarterly basis into [They use Plone 6](https://plone.org/why-plone/they-use-plone/they-use-plone-6).

To ensure your website gets the greatest exposure, add it both to Awesome Volto and the [Volto `README.md` under "Open-source websites built with Volto"](https://github.com/plone/volto/blob/main/README.md#open-source-websites-built-with-volto).

- [2022.ploneconf.org](https://github.com/plone/ploneconf.org/tree/2022) - Volto project for [Plone Conference 2022 site](https://2022.ploneconf.org)
- [2023.ploneconf.org](https://github.com/plone/ploneconf.org/tree/2023) - Volto project for [Plone Conference 2023 site](https://2023.ploneconf.org)
- [2024.ploneconf.org](https://github.com/plone/ploneconf.org/tree/2024) - Volto project for [Plone Conference 2024 site](https://2024.ploneconf.org)
- [2025.ploneconf.org](https://github.com/plone/ploneconf.org/tree/2025) - Volto project for [Plone Conference 2025 site](https://2025.ploneconf.org)
- [Biodiversity Information System for Europe](https://github.com/eea/bise-frontend) - Volto project for [Biodiversity Information System for Europe website](https://biodiversity.europa.eu)
- [design-volto-theme](https://github.com/RedTurtle/design-volto-theme) Volto theme for Italian Public Administration
- [EEA Main Website frontend](https://github.com/eea/eea-website-frontend) - Plone 6 Volto frontend for [European Environment Agency](https://www.eea.europa.eu/en)
- [European Industrial Emissions Portal](https://github.com/eea/industry-frontend ) - Volto project for [European Industrial Emissions Portal website](https://industry.eea.europa.eu)
- [Forest Information System for Europe](https://github.com/eea/fise-frontend) - Volto project for [Forest Information System for Europe website](https://forest.eea.europa.eu)
- [Freshwater Information System for Europe](https://github.com/eea/freshwater-frontend) - Volto project for [Freshwater Information System for Europe website](https://water.europa.eu/freshwater)
- [nsw-design-system-plone6-kit](https://github.com/pretagov/nsw-design-system-plone6-kit) - NSW Design System Plone 6 Kit Volto project for [NSW.gov.au sites](https://digitalnsw.pretagov.com.au/)
- [plone.org.br](https://github.com/plonegovbr/plone.org.br) - Volto project for the [Brazilian Plone Community](https://plone.org.br)
- [volto-bise](https://github.com/eea/volto-bise) - A Volto project packaged as an add-on. It provides Theming using a razzle.extend.js provided alias.
- [volto-eea-design-system](https://github.com/eea/volto-eea-design-system) - EEA Design System Plone 6 Kit Volto project for [European Environment Agency web sites](https://eea.github.io/volto-eea-design-system/)
- [volto-eea-kitkat](https://github.com/eea/volto-eea-kitkat) - A known good set of Volto add-ons to be used within all EEA projects and beyond, made for [European Environment Agency](https://www.eea.europa.eu/en)
- [volto-zeeuwsmuseum-theme](https://github.com/intk/volto-zeeuwsmuseum-theme) - Volto project for the [Zeeuws Museum](https://www.zeeuwsmuseum.nl/en) made for [INTK](https://www.intk.com/en).

## Companies

- [kitconcept](https://kitconcept.com/en/)
- [Redturtle](https://www.redturtle.it/)
- [Eau de Web](https://eaudeweb.ro/)
- [Rohberg](https://www.rohberg.ch/de)
- [Simples Consultoria](https://www.simplesconsultoria.com.br/)
- [CodeSyntax](https://www.codesyntax.com/en?set_language=en)
- [Nicola Zambello](https://nzambello.dev)
- [PretaGov AU/UK](https://www.pretagov.com.au)
- [FrescoMedia](https://frescomedia.ro)
- [Starzel](https://www.starzel.de)
- ... please add yourself here
