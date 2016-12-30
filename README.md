# MMBConfigData \t
shenmin统一中心化配置:
common文件夹下包含公共参数，所有模块继承其参数配置，
eureka-server文件夹下配置注册发现参数，
eureka-zuul文件夹下配置公共入口网关参数，
其他业务模块所有参数都创建单一文件夹，在内部分片设参。
