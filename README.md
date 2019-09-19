# DC/OS Grafana Dashboards

This repository is the home of the official DC/OS Grafana dashboards.

## Contributing Dashboards

To contribute dashboards to this repository, you should export the dashboard json from Grafana via the `Share` dialog, which offers the option to export the dashboard as a json file.
The `Export for sharing externally` option should be checked.

Dashboard titles should follow a standardized `<Component>: <Description>` format.

## Release Branches

We keep track of a branch for each DC/OS release series (e.g., 1.12.x, 1.13.x, ...).
This allows us to have different sets of dashboards for different DC/OS releases.
Currently, we maintain the following branches:

- 1.12.x (DC/OS 1.12)
- 1.13.x (DC/OS 1.13)
- 2.0.x (DC/OS 2.0)
- master (DC/OS 2.1-dev)


Please make changes to the master branch first, and then backport changes to the corresponding branches if needed.

## Related Projects

- https://github.com/mesosphere/dcos-monitoring
- https://github.com/dcos/telegraf

