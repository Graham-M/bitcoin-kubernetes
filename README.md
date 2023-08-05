Seems to be very few examples of doing this.

I'll do this properly 'soon'.

It relies of a hostPath to store the data.  I don't intend to change that for my purpose.

If you want to use this for your cluster:
- Update the host path for storage.
- Update the node affinity.

To do:
- Add a configMap for the `bitcoind.conf` file.
- Choose a version for the container.
- Parameterise all the things.
