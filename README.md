# REDCap-Survey-Apache-Proxy

Apache configuration script to set up a reverse proxy server handling Survey requests only.

Apache needs at least these modules enabled:
 - rewrite_module
 - proxy_module
 - proxy_http_module
 - ssl_module

All custom configurations are made at the top of the config file.
Surveys will be accessible at https://your.public.survey.address/surveys/.

Feedback/contributions are welcome!
