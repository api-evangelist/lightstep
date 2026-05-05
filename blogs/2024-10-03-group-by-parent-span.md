---
title: "Group By Parent Span"
url: "https://www.servicenow.com/community/cloud-observability-forum/group-by-parent-span/m-p/3064194#M7"
date: "Thu, 03 Oct 2024 23:53:15 GMT"
author: "barryam3-asana"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/Category?category.id=cloud-observability&interaction.style=forum"
---
<p>In Lightstep Cloud Observability when looking at operations in aggregate, how can I group by the parent operation span name?<br /><br />My use case is I have two operations, let's call them parent_1 and parent_2. Both of them always have a child operation span within them. The parent operations have side effects that can impact the latency of the child operation. I want to see the average P50 for the child operations, grouped by the parent operation.<br /><br />Lightstep seemingly already understands parent-child relationships, which I can view in the Dependency Map. But it doesn't show me aggregated latencies there.<br /><br />I can add metadata to the child spans, but this feels wasteful in terms of data costs and requiring additional code.</p>
