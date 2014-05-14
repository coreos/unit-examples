Example Units
=====

A collection of systemd units designed to run on CoreOS/fleet.

Blog posts and other documentation that contain example units are contained in folders within this repository. It's recommended to clone this repository onto the machine that you'll be controlling fleet with. If you're interested in controlling your cluster from your laptop, you can [use fleetctl with a remote address](http://coreos.com/docs/launching-containers/launching/fleet-using-the-client/#from-an-external-host).

## Contributing

Submit a PR for any units/containers you've written that take advantage of the unique features of CoreOS. For example, if you're experimenting with a MySQL cluster that does master election with etcd, submit a fully working group of units.
