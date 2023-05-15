
# JMeter-Performance-Testing-bookingApi

Dear,

I’ve completed performance test on frequently used API for test App https://restful-booker.herokuapp.com
Test executed for the below mentioned scenario in server https://restful-booker.herokuapp.com/

- 500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 98 And Total Concurrent API requested: 7000.
- 900 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 86 And Total Concurrent API requested: 6300.
- 1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 85 And Total Concurrent API requested: 7000


#### While executed 1000 concurrent request, found 109 request got connection timeout and error rate is 1.56%.
## Summary: 
Server can handle almost concurrent 950 API call with almost zero (0) error rate.

#### Test and report information 
![](https://github.com/Nahid-IIT/JMeter-Performance-Testing-bookinApi/blob/master/images/Test%20and%20Report%20info.PNG)

#### Summary Report:
![](https://github.com/Nahid-IIT/JMeter-Performance-Testing-bookinApi/blob/master/images/RequestSummery.PNG)

#### Statistics:
![](https://github.com/Nahid-IIT/JMeter-Performance-Testing-bookinApi/blob/master/images/statistics.PNG)

#### Errors:
![](https://github.com/Nahid-IIT/JMeter-Performance-Testing-bookinApi/blob/master/images/errors.PNG)

#### Total transaction per second
![](https://github.com/Nahid-IIT/JMeter-Performance-Testing-bookinApi/blob/master/images/Total%20Transaction%20persecond.PNG)




