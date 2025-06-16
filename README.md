# ripeatlas-geoloc-misfits
An attempt to crowdsource problems with RIPE Atlas probes

This repo contains the file ripeatlas-suspicious-geoloc.yaml that contains info on RIPE Atlas probes with suspected geolocation problems
The yaml file has multiple documents like this:

```
--- # The first one is still optional
probe_id: <probe id>
reported_by: <github account of reporter>
reported_date: <date in iso format, ie. YYYY-MM-DD
country_hint: <optional, if the reporter suspects they know the country>
city_hint: <optional, if reporter suspects they know the city>
---
probe_id: 50525
reported_by: emileaben
etc.
```
