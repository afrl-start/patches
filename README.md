# patches
A repository of plausible patches for the various scenarios

### Observations

* The attack for `AIS-Scenario7` will fail to trigger if any speedup factor
  greater than one is used, independent of the number of simultaneous
  executions. The time taken to travel between WP2 and WP3
  appears to be insufficient for the attack to be reliably triggered. This
  limitation _substantially_ hampers the efficiency of the search.
