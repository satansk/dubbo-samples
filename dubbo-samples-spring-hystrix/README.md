## dubbo spring hystrix sample

### Start Provider

Run `com.alibaba.dubbo.samples.annotation.AnnotationProvider`


### Start Consumer

Run `com.alibaba.dubbo.samples.annotation.AnnotationConsumer`

### Result

0. Start provider
0. Start consumer
0. The provider print `java.lang.RuntimeException: Exception to show hystrix enabled`. The exception stack conatins hystrix command info.
0. The consumer print `result :hystrix fallback value`, which means hystrix fallback configuration is effect.
