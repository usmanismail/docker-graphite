Graphite on Docker
===========================

This repository contains the sources to build a Graphite_ Docker
image. collectd is configured to receive metrics from the network and to store
them to Graphite.

If you have Docker installed, you can try it out with::

   docker build -t graphite . # from the root of this repository
   docker run graphite

