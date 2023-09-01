# Random-User-API-Performance-Test

#About Project Summary :

Through Load and Stress testing find out performance level using Jmeter



Tools & Technology used:


.Jmeter

.VS code




Based on following scenario, completed Load Testing and stress Testing





Find out the actual TPS for if 120000 users can give load for 12 hours
Perform load test on this URL: https://random-data-api.com/api/v2/users

1.You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement. Breakdown the expected TPS in excel sheet and find out the actual TPS

2.Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)





1.Load Test :





Here,Expected tps was,120000/43200=2.77777777777777/s After fining the value , check how system can behave under an expected load.Through gradually increasing time , got a actual tps which is 2.77777777777777/s with 0.1% error.

![image](https://github.com/Sabiya-Sultana/Random-User-API-Performance-Test/assets/134813316/dea0c7a4-1723-4cc5-b76c-f9012bf56d08)





Load Test Html Report :





![screencapture-file-E-apache-jmeter-5-6-2-apache-jmeter-5-6-2-bin-Reportsload-index-html-2023-09-02-02_00_33](https://github.com/Sabiya-Sultana/Random-User-API-Performance-Test/assets/134813316/7ad9263f-f8af-4331-8add-50730a7fd62b)






2.Stress Test :





Here, while gradually increase the load then find out bottleneck point/stress test tps 3.33097627995662/s with 0.78% error.

![Screenshot 2023-09-02 020339](https://github.com/Sabiya-Sultana/Random-User-API-Performance-Test/assets/134813316/2b1e7b6a-b4f2-450f-b4a7-3c707ed80d3d)





Stress Test Html Report:





![screencapture-file-E-apache-jmeter-5-6-2-apache-jmeter-5-6-2-bin-Reportsstress-index-html-2023-09-02-02_05_05](https://github.com/Sabiya-Sultana/Random-User-API-Performance-Test/assets/134813316/9bbd6b32-2c99-4e69-afba-d10f04c217b2)




