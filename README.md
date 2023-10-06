# Blitz 2
 
## Scenario:
 A QA engineer sent 14,000 requests to our server using jmeter in order to stress test the URL shortener application.

 # Preparation: 
 Two CloudWatch alarms were set prior to the stress test, one for > 60% CPU usage and the other for > 40% MEM usage. These percentage points were used based on intended usage expectancy and will be adjusted as necessary after test results are received and resource optimization options are implemented. 

 ## Results:

 ### CPU Usage hovered below 1% prior to `stress -ng` testing at 23:10 UTC. The initial 10 minutes of stress testing there was an increase of CPU usage to 100%.

![Screen Shot 2023-10-04 at 9 03 36 PM](https://github.com/z0sun/Blitz2/assets/135557197/04854921-124d-4a1a-9f3f-7c39669f6d5f)
