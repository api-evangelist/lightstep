---
title: "How can I debug why 99.99% of my spans are being dropped"
url: "https://www.servicenow.com/community/cloud-observability-forum/how-can-i-debug-why-99-99-of-my-spans-are-being-dropped/m-p/3175024#M11"
date: "Tue, 11 Feb 2025 22:39:02 GMT"
author: "MarkR7232213139"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/Category?category.id=cloud-observability&interaction.style=forum"
---
<p>My service, IMS, is getting a ton of errors trying to push to traces to Lightstep.</p><p>&nbsp;</p><p>Here's what I know</p><p>* Some pushes work, so I have a few but not many, traces in LS</p><p>* I have a consistently high `rate(lightstep_error_event_total)` metric on all my pods, so traces are being continously dropped</p><p>* I have a lot of `<span>flush failed, could not send report to Collector` errors</span></p><p><span>* I am getting a lot of `status code (400) is not ok` in my logs for the trace.</span></p><p>&nbsp;</p><p><span>Is there a way to change the lightstep micro-satellite to log the requests that produce these 400 errors? For the LS go client library, can I turn up the debugging level to get more details on why this is failing?</span></p>
