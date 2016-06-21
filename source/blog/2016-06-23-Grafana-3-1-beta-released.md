--
title: Grafana 3.1 Beta Released
author: Torkel Ödegaard
published_on: June 23, 2016
---

Grafana 3.1 beta is now available for download! We are super excited to announce a new way
of sharing dashboards for Grafana. Its now possible to download and upload dashboards to
[Grafana.net](http://grafana.net/dashboards/) which makes it easier to ....

If you built some great dashboards, why not share them with the rest of us?

<div class="text-center">
<a class="button secondary radius" href="/download">Download Grafana 3.1</a>.
<a class="button primary radius" href="http://play.grafana.org" target="_blank">Live Demo</a>.
</div>

## Release Highlights

- **Dashboard Repository** Grafana.net now supports download and uploading dashboards.
- **Dashboard Url** Timerange and template variable is now part of URL.
- **Singlestat** Can now map ranges to text.
- **Internal metrics** Grafana now supports sending metrics about itself.
- [Full changelog](https://github.com/grafana/grafana/blob/master/CHANGELOG.md)

## Breaking changes
- **Logging**: The logging format have been changed to support key, value pairs.

## Dashboard Repository

Sharing dashboards is something that we wanted to do for a very long time and something that aligns very good with our vision.

- Democratize Metrics ()
- Built Better Together

You can browse the dashboard repository at [http://grafana.net/dashboards](http://grafana.net/dashboards).
When you find a dashboard you like, just copy the URL and head back to Grafana and go to Dashboards -> Import.

<img src="/assets/img/blog/v3.0/import_dashboard.png">

Paste the URL pointing to the dashboard page on grafana.net.

<img src="/assets/img/blog/v3.0/import_dashboard_settings.png">

## Dashboard Urls

Saving the timerange and template variable in the url makes it much easier to share dashboards with others within your organisation.

## Internal metrics

Do you want metrics about view metrics? Ofc you do! In this release we added support for sending metrics about Grafana to graphite.

## Thanks
A big thank you to everyone who helped test and report issues with the beta release.

<div class="">
<a class="button secondary radius" href="/download">Download Grafana 3.1</a>.
<a class="button primary radius" href="http://play.grafana.org" target="_blank">Live Demo</a>.
</div>

#### Subscribe to project updates
<section class="newsletter">
  <form action="http://grafana.us8.list-manage.com/subscribe/post?u=2aeb5711db2aececc990be536&amp;id=5585d37ecc" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank">
    <row class="collapse">
      <div class="medium-10 columns">
        <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address">
      </div>
      <div class="medium-2 columns">
        <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button postfix">
      </div>
    </row>
  </form>
</section>