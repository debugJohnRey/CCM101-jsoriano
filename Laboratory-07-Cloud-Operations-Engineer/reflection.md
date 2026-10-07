# Checkpoint 7 - Mission Reflection

You must check the host server resources. Containers need physical hardware so it can work. Even if your app is perfect, a host that run out of memory or disk space will crash all containers running inside it. Monitor the foundation first. This make sure the server can handles the workloads before you add more traffic.

The `docker logs` command help you to find the exact error when user cannot log into web app. You don't need to guess anymore. You just read logs to see if user put the wrong password or if server crash completely. It make fixing problem much faster for the team.

Logs and metrics is doing different jobs. Logs are record of specific events that happens in the system. For example, log show when user visit a page or when app throw a 404 error. Metrics measures system health over time, like how much CPU or memory the system use. Metrics show when the server is struggle, but logs tells you exactly why it break.

Big companies does not check thousands of containers by hand. They using central tools to monitor everything at once. They use tool called Prometheus for collect data from all servers. Then they use Grafana to build dashboard and send alert when resources gets too high.

My troubleshooting skill in Linux get better. Before this mission, I only deploying apps. Now, I checking their health too. I know how find the hardware baseline using command like `top` and `df -h`. I feeling confident to use Docker tools to find error and resource spike, so I do not have to guess anymore when something break.