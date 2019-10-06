This setting configures the acceleration rate of the print head while the middle layer of the raft is printed. The acceleration during the middle layer of the raft can be configured separately from the base and top layers.

![Where the middle layer is located in the raft](images/raft_dimensions_simplified.svg)

Since the raft generally consists of long line segments, increasing acceleration normally has very little impact on printing time. Increasing the acceleration will save a bit of time when going through corners at the end of the lines though.

Increasing the acceleration rate will cause the printer to vibrate more while printing the middle layer of the raft. This slightly increases the risk of pulling the raft off of the build plate.