median
====================

A <a href="http://nodered.org" target="_new">Node-RED</a> node that provides
a moving average function by selecting the median value from the set of the
last (n) values.

Install
-------

Run the following command in your Node-RED user directory - typically `~/.node-red`

    npm install node-red-contrib-median


Usage
-----

TODO -- documentation goes here

If `msg.reset` is received (with any value), all the counters and intermediate values are reset to an initial state.

**Note:** This node only operates on **numbers**. Anything else will try to be
made into a number and rejected if that fails.
