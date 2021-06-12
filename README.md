# awesome-volto

A curated list of things that make Volto awesome. Please feel free to contribute directly or send a PR!

## Contents

- [Official websites](#official-websites)
- [Community](#community)
- [Addons](#addons)
- [Open-source websites built with Volto](#open-source-websites-built-with-volto)
- [Companies](#companies)

## Official websites

- [github.com/plone/volto](https://github.com/plone/volto)
- [docs.voltocms.com](https://docs.voltocms.com)
- [plone.org](https://plone.org)

## Community

- [#volto on plone.slack.com](https://plone.slack.com/)
- [#volto on gitter.im](https://gitter.im/plone/volto)

## Addons

> :warning: While we try to list them all, some of these addons **might be a Work in Progress**, require special branches of Volto or dedicated Plone addons.

Various addons that can't fit in a specific category:

- [volto-quanta](https://github.com/plone/volto-quanta) - A new theme for Volto, right now only styles a few form controls
- [volto-cookie-banner](https://github.com/collective/volto-cookie-banner)
- [volto-dropdownmenu](https://github.com/collective/volto-dropdownmenu)
- [volto-geocoding](https://github.com/collective/volto-geocoding)
- [volto-venue](https://github.com/collective/volto-venue)
- [volto-google-analytics](https://github.com/collective/volto-google-analytics)
- [volto-social-settings](https://github.com/collective/volto-social-settings)
- [EEA volto-addons](https://github.com/eea/volto-addons) - (deprecated) Various smaller addons, bunched up in a single package
- [volto-embed](https://github.com/eea/volto-embed) - (WIP) GDPR compliant external resource embedding Volto Block
- [volto-searchkit](https://github.com/eea/volto-searchkit) - (WIP) A full ElasticSearch-powered faceted search integrated as a configurable Volto block
- [volto-plotlycharts](https://github.com/eea/volto-plotlycharts) - (EEA) Powerful chart editor based on Plotly
- [volto-block-dataFigure](https://github.com/eea/volto-block-data-figure) - (EEA) Volto add-on for Daviz specific SVG charts.
- [volto-datablocks](https://github.com/eea/volto-datablocks) - (EEA) Provides primitives for data connectivity to volto-plotlycharts and other blocks
- [volto-form-builder](https://github.com/kitconcept/volto-form-builder) - A TTW builder of forms
- [volto-corsproxy](https://github.com/eea/volto-corsproxy) - A CORS-proxy integrated with Volto, enables access to third-party API servers.
- [volto-block-style](https://github.com/eea/volto-block-style) - A generic framework to configure block decorations and CSS styles.
- [volto-block-toc](https://github.com/eea/volto-block-toc) - An extensible TOC block alternative to Volto's Table of Contents block.
- [volto-matomo](https://github.com/eea/volto-matomo) - (WIP) Basic Matomo Tracker integration for Volto
- https://github.com/collective/volto-form-block
- https://github.com/collective/volto-subsites
- [volto-bookmarks](https://github.com/collective/volto-bookmarks) – Add and manage bookmarks of pages and searchkit queries.
- [volto-slate-glossary](https://github.com/rohberg/volto-slate-glossary) - (WIP) Tooltips for glossary terms

### Rich text editing

Enhance the basic text editing experience

- [volto-slate](https://github.com/eea/volto-slate) - (Almost) drop-in replacement for the Volto richtext editor with multiple enhancements
- [volto-slate-footnote](https://github.com/eea/volto-slate) - Footnote (and references) plugin for volto-slate.
- [volto-slate-metadata-mentions](https://github.com/eea/volto-slate-metadata-mentions) - Plugin for volto-slate to embed dynamic text that renders Plone metadata fields
- [volto-slate-zotero](https://github.com/eea/volto-slate-zotero) - Plugin for volto-slate to connect footnotes to Zotero references
- [volto-ckeditor](https://github.com/eea/volto-ckeditor) - (deprecated) Simple integration with CKEditor
- [volto-slate-dataentity](https://github.com/eea/volto-slate-dataentity) - Connect text entities in the rich text editor to volto-datablocks connected data

### Layout addons

Enhancements to the way blocks can be used, to create custom layouts

- [volto-subblocks](https://github.com/collective/volto-subblocks) - A framework to edit and embed blocks into other blocks
- [volto-tabs-block](https://github.com/eea/volto-tabs-block) - Split a Volto page into tabs, complete with editing form integration, using just a simple tabs block.
- [volto-mosaic](https://github.com/eea/volto-mosaic) - (Deprecated) Flexible grid-based implementation of a mosaic layout, complete with responsive layout versions.
- [volto-tabsview](https://github.com/eea/volto-tabsview) - (Deprecated) Extension of volto-mosaic
- [volto-gridlayout](https://github.com/eea/volto-gridlayout) - (Deprecated) Supersedes volto-mosaic, another go at providing a flexible full page grid-based mosaic layout
- [volto-metadata-block](https://github.com/eea/volto-metadata-block) - Custom Volto Block to insert Plone metadata fields
- [volto-accordion-block](https://github.com/eea/volto-accordion-block) - Create group based accordions in blocks.
- [volto-grid-block](https://github.com/eea/volto-grid-block) - Enables grid layout grouping of Volto blocks. It introduces a "grid block" which can be used, from the Edit form, to group other blocks
- [volto-columns-block](https://github.com/eea/volto-columns-block) - Enables grouping Volto blocks as columns
- [volto-group-block](https://github.com/eea/volto-group-block) - Group blocks in sections and filter available blocks per content-type per section
- [volto-blocks-grid](https://github.com/kitconcept/volto-blocks-grid) - Unidimensional (x-axis) grids for blocks

### Widgets

Input components, to be reused in the form library

- [volto-object-widget](https://github.com/eea/volto-object-widget) - Widget for generic JS objects
- [volto-widget-geolocation](https://github.com/eea/volto-widget-geolocation) - Geolocation with [GeoNames](https://www.geonames.org/) integration.
- [volto-widget-temporal-coverage](https://github.com/eea/volto-widget-temporal-coverage) - (EEA) Volto widget: Temporal coverage.
- [volto-widgets-view](https://github.com/eea/volto-widgets-view) - Provides the "view" counterpart for the "edit" widgets in Volto
- [volto-multilingual-widget](https://github.com/collective/volto-multilingual-widget)
- [volto-widget-toggle](https://github.com/eea/volto-widget-toggle/) - Replace checkbox widgets with a visually nicer toggle widget
- https://github.com/collective/volto-blocks-widget

### Plone addons for Volto

- https://github.com/collective/collective.volto.dropdownmenu
- https://github.com/collective/collective.volto.subsites
- https://github.com/collective/collective.volto.formsupport
- https://github.com/collective/collective.bookmarks
- https://github.com/collective/collective.volto.secondarymenu
- https://github.com/collective/collective.volto.blocksfield
- https://github.com/collective/collective.volto.socialsettings

## Training, example code, tutorials

- [Demo project for Volto addons](https://github.com/collective/volto-example-project-addons)
- https://github.com/collective/volto-hands-on-training

### Awesome React articles, relevant to any Volto developer

- [Writing resilient react components](https://overreacted.io/writing-resilient-components/)
- [React rendering behavior](https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/)
- [React Algebraic Effects](https://reesew.io/posts/react-algebraic-effects)
- [Code Splitting - deeper understanding](https://medium.com/1mgofficial/code-splitting-ssr-lazy-loading-react-components-a-deeper-understanding-part-1-7d714196706)
- [High Performance React](https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3)
- [A Complete Guide to useEffect (and more)](https://overreacted.io/a-complete-guide-to-useeffect/#why-usereducer-is-the-cheat-mode-of-hooks)
- [On the intricacies on React's onClick event handlers](https://dev.to/dvnrsn/why-isn-t-event-stoppropagation-working-1bnm)

## Open-source websites built with Volto

- [forests-frontend](https://github.com/eea/forests-frontend) - Volto project for https://forests.eea.europa.eu
- [eprtr_frontend](https://github.com/eea/eprtr_frontend) - Volto project for EPRTR
- [volto-bise](https://github.com/eea/volto-bise) - A Volto project packaged as an addon. It provides theming using a razzle.extend.js provided alias.
- [design-volto-theme](https://github.com/RedTurtle/design-volto-theme)

## Companies

- [kitconcept](https://kitconcept.com/)
- [Redturtle](https://www.redturtle.it/)
- [Eau de Web](https://www.eaudeweb.ro/)
- [Rohberg](https://www.rohberg.ch/)
- ... please add yourself here
