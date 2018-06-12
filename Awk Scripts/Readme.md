## How to run AWK files :
<br/>
The awk files are named as :
<br/><br/>
PDR.awk - Packet Delivery Ratio
<br/>
t-put.awk - Throughput
<br/>
e2edelay.awk - End to End Delay
<br/><br/>
To run awk file, first run the tcl file,(eg; ns AODV_20.tcl) and then enter the command
<br/>
awk -f PDR.awk blackhole.tr
<br/><br/>
Similarly do for other awk files.
