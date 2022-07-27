# Canary in a coal mine: Building infrastructure resiliency with canary data reloads

Velocity Conference
San Jose, CA
June 22, 2017

Remember the old practice of the canary in the coal mine, where miners used fragile feathered friends as a failure detector for toxic gasses? In software, a canary run is a trial executed on one machine before the rest of the cluster runs. This presentation explains how Indeed created a canary service leveraging Consul’s key value store to improve the resilience of data reloads in any infrastructure, covering the original implementation of the canary reloader, corner cases encountered, how the canary framework was extended to a general library, and lessons learned along the way.

https://www.oreilly.com/library/view/velocity-conference-2017/9781491976265/video311368.html
