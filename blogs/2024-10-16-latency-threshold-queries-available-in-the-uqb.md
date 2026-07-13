---
title: "Latency threshold queries available in the UQB"
url: "https://docs.lightstep.com/changelog/latency-filter"
date: "2024-10-16"
feed_url: "https://docs.lightstep.com/feed.xml"
---
You can now use the Unified Query Builder (UQB) to query on a latency duration . For example, say you want to see latency on the iOS service that’s over 5 seconds and grouped by customer. You would enter the following: Spans with : latency >= 5 second Filter by (and) : service == iOS Group by : customer The rest of the fields work in the same way as for standard span queries.
