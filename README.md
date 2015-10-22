# Drupal Performance Resources

A list of Drupal performance resources. Pull requests welcome!

---

## Drupal.org (Start Here)

[Optimizing Drupal to load faster (Server, MySQL, caching, theming, HTML)](https://www.drupal.org/node/1722250)

[Managing site performance](https://www.drupal.org/node/627252)

[Caching: Modules that make Drupal scale](https://groups.drupal.org/node/21897)

---

## Checklists

[Colan Schwartz's Drupal 7 Performance Optimization Options and Checklist](http://colans.net/blog/drupal-7-performance-optimization-options-and-checklist)

[Neerav Mehta's Drupal Performance Optimization Checklist](http://redcrackle.com/blog/performance/drupal-performance-optimization-checklist)

---

## Advanced

[O'Reilly's "High Performance Drupal: Fast and Scalable Designs"](http://shop.oreilly.com/product/0636920012269.do)

[O'Reilly's "High Performance Drupal: Fast and Scalable Designs" - free preview of 1st chapter](http://chimera.labs.oreilly.com/books/1230000000845/ch01.html)

[Drupal 7 performance related patches & replacements for core functionally](https://groups.drupal.org/node/210683)

[Use Grunt and AdvAgg to inline critical CSS on a Drupal 7 theme](http://fourword.fourkitchens.com/article/use-grunt-and-advagg-inline-critical-css-drupal-7-theme)

[APCu and OpCache optimization for a large Drupal site](http://dropbucket.org/node/6791)

---

## drupal.stackexchange.com

[How do you improve Drupal performance?](http://drupal.stackexchange.com/questions/24180/how-do-you-improve-drupal-performance)

[Real world experience in scaling and tuning performance](http://drupal.stackexchange.com/questions/183/real-world-experience-in-scaling-and-tuning-performance)

[Do non-enabled Drupal modules affect performance?](http://drupal.stackexchange.com/questions/22/do-non-enabled-drupal-modules-affect-performance)

[Given that db_select is much slower than db_query, why would I want to use it?](http://drupal.stackexchange.com/questions/1200/given-that-db-select-is-much-slower-than-db-query-why-would-i-want-to-use-it)

[Nginx vs Apache - Are there any actual usage comparisons and statistcs out there?](http://drupal.stackexchange.com/questions/71610/nginx-vs-apache-are-there-any-actual-usage-comparisons-and-statistcs-out-there)

---

## General Performance Tools

### FOSS

* [Apache JMeter](http://jmeter.apache.org/)
* [Xdebug](http://xdebug.org/)
* [XHProf](https://github.com/phacility/xhprof)
* [Nagios](https://www.nagios.org/)
* [Sitespeed](https://www.sitespeed.io/)

### Continuous Profiling Services

* [AppDynamics](https://www.appdynamics.com/)
* [New Relic](https://newrelic.com/)
* [BlazeMeter](https://blazemeter.com/)
* [Blitz](https://www.blitz.io/)

### Discussions & Comparisons

[Benchmarking and profiling Drupal](https://www.drupal.org/profiling)

[Which are the load testing tools that can be easy to use for a developer?](http://drupal.stackexchange.com/questions/31383/which-are-the-load-testing-tools-that-can-be-easy-to-use-for-a-developer)

---

## General Performance Theory

[14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/rules.php)

[The Vanilla Web Diet](http://www.smashingmagazine.com/2012/11/the-vanilla-web-diet/)

[Fixing Performance in the Web Stack](http://ponyfoo.com/articles/fixing-web-performance)

[Think Quarterly: The Speed Issue](https://www.thinkwithgoogle.com/collections/the-speed-issue.html)

[Introducing RAIL: A User-Centric Model For Performance](http://www.smashingmagazine.com/2015/10/rail-user-centric-model-performance/)

---

## Presentations

[4x High Performance for Drupal - Step by Step](https://events.drupal.org/losangeles2015/sessions/4x-high-performance-drupal-step-step)

[DIY Drupal 7 Performance
](https://docs.google.com/presentation/d/1AgnurTWsWdMAFjfFmSU7mk2zfJu8jG_KmVdZ7-o6Pok/edit?usp=sharing)

[Auditing Drupal sites for performance, content and optimal configuration](http://2014.pnwdrupalsummit.org/2014/sessions/auditing-drupal-sites-performance-content-and-optimal-configuration)

[Creating a Culture of Performance](https://events.drupal.org/losangeles2015/sessions/creating-culture-performance)

[Solving Drupal Performance and Scalability Issues](https://events.drupal.org/barcelona2015/sessions/solving-drupal-performance-and-scalability-issues)

[Better performance with Apache/Nginx](https://events.drupal.org/losangeles2015/sessions/better-performance-apachenginx)

[Making Drupal fly - The fastest Drupal ever is near!](https://events.drupal.org/losangeles2015/sessions/making-drupal-fly-fastest-drupal-ever-near)

---

## Feeds

[Drupal.org, high performance group](https://groups.drupal.org/high-performance)

[Drupal.org, performance taxonomy page](https://www.drupal.org/taxonomy/term/32238)

[Acquia, Drupal Website Performance series](https://www.acquia.com/blog/drupal-website-performance)

[Drupal Answers, performance tag](http://drupal.stackexchange.com/questions/tagged/performance)

[Reddit, r/drupal, performance posts](https://www.reddit.com/r/drupal/search?q=performance&restrict_sr=on)

[Dropbucket, performance/scalability snippets](http://dropbucket.org/snippets/performance-and-scalability)

[Drupal Planet, performance tag (via drupalsun.com)](http://drupalsun.com/find?f[0]=field_rss_tags%3A79&page=1&infinite=1)

---

## Distributions

* [Pressflow](http://www.pressflow.org/) - https://github.com/pressflow/7

---

## Modules

### CDN integration

* [CDN](https://www.drupal.org/project/cdn) - [README (7.x-2.x)](http://cgit.drupalcode.org/cdn/tree/README.txt)
* [Akamai](https://www.drupal.org/project/akamai) - [README (7.x-2.x)](http://cgit.drupalcode.org/akamai/tree/README)
* [Fastly](https://www.drupal.org/project/fastly) - [README (7.x-2.x)](http://cgit.drupalcode.org/fastly/tree/README.txt?h=7.x-2.x)

### Key-value stores

* [Redis](https://www.drupal.org/project/redis) - [README (7.x-3.x)](http://cgit.drupalcode.org/redis/tree/README.txt)
* [Memcache API and Integration](https://www.drupal.org/project/memcache) - [README (7.x-1.x)](http://cgit.drupalcode.org/memcache/tree/README.txt)
* [APC - Alternative PHP Cache](https://www.drupal.org/project/apc) - [README (7.x-1.x)](http://cgit.drupalcode.org/apc/tree/README.txt?h=7.x-1.x)

### Front end caching

* [Varnish](https://drupal.org/project/varnish) - [README (7.x-1.x)](http://cgit.drupalcode.org/varnish/tree/README.txt)
* [Advanced CSS/JS Aggregation](https://www.drupal.org/project/advagg) - [README (7.x-2.x)](http://cgit.drupalcode.org/advagg/tree/README.txt)

### Back end caching

* [Boost](https://drupal.org/project/boost) - [README (7.x-1.x)](http://cgit.drupalcode.org/boost/tree/README.txt)
* [Book Cache](https://www.drupal.org/project/book_cache) - [README (7.x-1.x)](http://cgit.drupalcode.org/book_cache/tree/README.txt)
* [Asynchronous Prefetch Database Query Cache](https://www.drupal.org/project/apdqc) - [README (7.x-1.x)](http://cgit.drupalcode.org/apdqc/tree/README.txt)

### Auditing

* [Drupal Site Audit](https://www.drupal.org/project/site_audit) - [README (7.x-1.x)](http://cgit.drupalcode.org/site_audit/tree/README.md)

### Other optimizations

* [HTTP Parallel Request & Threading Library](https://www.drupal.org/project/httprl) - [README (7.x-1.x)](http://cgit.drupalcode.org/httprl/tree/README.txt?h=7.x-1.x)
* [Minify HTML](https://www.drupal.org/project/minihtml)
