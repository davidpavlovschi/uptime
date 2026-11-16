# uptime

Checks outdm.com, seoformy.app and outformat.com every five minutes from outside their servers: home pages, web health, database and worker. On outformat.com the health check fails when paid work has waited over 30 minutes and no runner has polled for 15.

A failed run means a door is down. GitHub emails the repository owner on every failed run. Open the run to read which check failed.

Run it by hand: Actions, uptime, Run workflow.
