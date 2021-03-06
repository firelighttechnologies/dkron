---
date: 2018-11-26
title: "dkron"
slug: dkron
url: /cli/dkron/
---
## dkron

Open source distributed job scheduling system

### Synopsis

Dkron is a system service that runs scheduled jobs at given intervals or times,
just like the cron unix service but distributed in several machines in a cluster.
If a machine fails (the leader), a follower will take over and keep running the scheduled jobs without human intervention.

### Options

```
      --config string   config file path
  -h, --help            help for dkron
```

### SEE ALSO

* [dkron agent](/cli/dkron_agent/)	 - Start a dkron agent
* [dkron doc](/cli/dkron_doc/)	 - Generate Markdown documentation for the Dkron CLI.
* [dkron keygen](/cli/dkron_keygen/)	 - Generates a new encryption key
* [dkron version](/cli/dkron_version/)	 - Show version

###### Auto generated by spf13/cobra on 26-Nov-2018
