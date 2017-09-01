# Tooltips or partials

You can use partials for a few different purposes, as described in detail in the **Reuse Content** section.

## Global partials
There are currently three global partials in use:
* `errors_global`, described in <a href="#Services-tutorials-document">Tutorials</a> to refer to the API Reference for error codes.
* `template_events`, described in <a href="#Services-events-document">Events</a> to refer to the PubSub documentation for more information.
* `yaas_proxy_url`, an environment-aware partial with the proxy URL. Depending on the environment, the proxy points to `https://api.{{region}}.yaas.io` on production, and to `https://api.stage.yaas.io` on stage and development.

You can also use partials to display a word as an inline tooltip like so: <span class="u-help-label" data-toggle="tooltip" data-placement="top" title="" data-original-title="YaaS stands for SAP Hybris [y] as a Service.">YaaS</span>.
