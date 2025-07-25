## Hi there 👋

A Kubernetes operator that automatically scales down Deployments and StatefulSets during specific time windows (e.g., at night or on weekends) to save resources and costs.

## Features

- 🕒 **Cron-based Scheduling**: Uses standard cron expressions with second precision
- 🌍 **Timezone Support**: Configure schedules in any timezone
- 📈 **Flexible Scaling**: Scale down and up on different schedules
- 🎯 **Multiple Resource Types**: Supports Deployments and StatefulSets for scaling
- 🧹 **Resource Cleanup**: Automatically delete test resources based on annotations
- 🏷️ **Cleanup-Only Mode**: Pure cleanup functionality without scaling any target resources
- 📊 **Status Tracking**: Monitor last execution times and current replica counts
- 🌐 **Web UI Dashboard**: Built-in web interface to monitor all cron jobs and their status
- ⚡ **Efficient**: Only reconciles when needed, with smart requeue timing
- 🛡️ **Safe Testing**: Dry-run mode for cleanup operations
- 🔧 **Graceful Error Handling**: Continues operation even when target resources are missing

Read the docs [cronschedules.elbazi.co](https://cronschedules.elbazi.co/)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
