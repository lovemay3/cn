
常见的错误如下表所示，具体的原因以message中的提示为准。

错误code|错误status|错误原因
:---|:---|:---
400|INVALID_ARGUMENT|参数错误
400|FAILED_PRECONDITION|此操作需要的预置条件不满足
400|OUT_OF_RANGE|参数超出范围
401|UNAUTHENTICATED|验证失败
403|HTTP_FORBIDDEN|没有权限
404|NOT_FOUND|找不到对象
409|ABORTED|操作终止
409|ALREADY_EXISTS|对象已存在
429|QUOTA_EXCEEDED|配额不足
429|RATE_LIMIT|请求过频繁
499|CANCELLED|取消操作
500|UNKNOWN|未知错误
500|INTERNAL|内部错误
501|NOT_IMPLEMENTED|操作未实现
502|SOURCE_UNAVAILABLE|源站不可用
503|UNAVAILABLE|服务不可用