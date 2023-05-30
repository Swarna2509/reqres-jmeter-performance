# reqres-jmeter-performance
Dear,

I’ve completed performance test on frequently used API for test site https://reqres.in.
Test executed for the below mentioned scenario in server https://reqres.in.

10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 1.333 And Total Concurrent API requested: 80.

50 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 6.67 And Total Concurrent API requested: 400.

100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 13.3 And Total Concurrent API requested: 800.

150 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 20 And Total Concurrent API requested: 1200.

- While executed 100 concurrent request, found  1 request got connection timeout and error rate is 0.08%.


Summary: Server can handle almost concurrent 800 API call with almost zero (0) error rate. 

Report :

![Screenshot (337)](https://github.com/Swarna2509/reqres-jmeter-performance/assets/72212832/dcf4a815-42b7-46f0-9774-c962a2f7155e)
![Screenshot (338)](https://github.com/Swarna2509/reqres-jmeter-performance/assets/72212832/4a5d5f17-8e42-4f23-abaa-e5bee7defd0b)
![Screenshot (339)](https://github.com/Swarna2509/reqres-jmeter-performance/assets/72212832/fcce9dcf-8118-4570-963e-f6d0d03e9279)
