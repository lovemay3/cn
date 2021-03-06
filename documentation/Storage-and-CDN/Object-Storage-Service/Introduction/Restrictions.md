# 限制说明

京东云对象存储的使用限制如下：

|限制项|说明|
|-|-|
|存储空间|1.同一用户在每个地域可以创建的存储空间总数不能超过20个。<br>2.存储空间一旦创建成功，名称和所处地域不能修改。<br>3.存储空间名称全局唯一。<br>4.删除存储空间之前需要先删除掉该存储空间下的全部文件资源和图片样式。<br>5.存储空间命名长度必须在3-63个字符之间，且名称仅能由小写字母、数字、中划线(-)组成，且仅能以小写字母或数字开头和结尾。<br>6.目前控制台默认不支持bucket绑定自定义域名，如果需要使用此功能需要单独提交工单申请。|
|上传文件|1.通过控制台上传的文件大小不能超过1GB。<br>2.使用普通上传或分片上传，单个文件或者分片大小不能超过5GB。<br>3.要上传大小超过5GB的文件必须使用分片上传方式，最大允许上传48.8TB的文件。<br>4.支持上传同名文件，但会覆盖已有文件。
|删除文件|1.文件删除后无法恢复。<br>2.欠费停服后60天内若未充正欠款，全部文件将被自动删除。<br>3.目前不支持批量删除。
|Access Key管理|1.用户在开通对象存储服务时不会自动创建Access Key。<br>2.需要到个人中心Access Key管理处手动创建，最多支持5个Access Key。
