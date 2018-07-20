# BigQuery-> CrUX->June 2018 Analysis
Chrome User Experience Report Analysis Report

* The Chrome User Experience Report provides user experience metrics for how real-world Chrome users experience popular destinations on the web.

* The Chrome User Experience Report is powered by real user measurement of key user experience metrics across the public web, aggregated from users who have opted-in to syncing their browsing history, have not set up a Sync passphrase, and have usage statistic reporting enabled. The resulting data is made available via:

    * PageSpeed Insights, which provides URL-level user experience metrics for popular URLs that are known by Google's web crawlers.
    * Public Google BigQuery project, which aggregates user experience metrics by origin, for all origins that are known by Google's web crawlers, and split across multiple dimensions outlined below.

#### Metrics provided by the public Chrome User Experience Report hosted on Google BigQuery are powered by standard web platform APIs exposed by modern browsers and aggregated to origin-resolution.

* First Paint: First Paint reports the time when the browser first rendered after navigation. This excludes the default background paint, but includes non-default background paint. This is the first key moment developers care about in page load – when the browser has started to render the page.

* First Contentful Paint: First Contentful Paint reports the time when the browser first rendered any text, image (including background images), non-white canvas or SVG. This includes text with pending webfonts. This is the first time users could start consuming page content.

* DOMContentLoaded: The DOMContentLoaded reports the time when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.

* onload: The load event is fired when the page and its dependent resources have finished loading.

* First Input Delay: First Input Delay (FID) measures the time from when a user first interacts with your site (i.e. when they click a link, tap on a button, or use a custom, JavaScript-powered control) to the time when the browser is actually able to respond to that interaction.

#### Performance of web content can vary significantly based on device type, properties of the network, and other variables.

* Effective Connection Type: Provides the effective connection type (“slow-2g”, “2g”, “3g”, “4g”, or “offline”) as determined by round-trip and bandwidth values based on real user measurement observations.

* Device Type: Coarse device classification (“phone”, “tablet”, or “desktop”), as communicated via User-Agent.

* Country: Geographic location of users at the country-level, inferred by their IP address. Countries are identified by their respective ISO 3166-1 alpha-2 codes.