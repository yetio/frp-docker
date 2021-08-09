# frp

[![frp](http://dockeri.co/image/yetio/frps)](https://hub.docker.com/r/yetio/frps)
[![frp](http://dockeri.co/image/yetio/frpc)](https://hub.docker.com/r/yetio/frpc)

Docker Image packaging for Frp.

(amd64, arm32v6, arm32v7, arm64v8, i386)


## Usage

start frps

```bash
docker run --restart=always --network host -d -v /etc/frp/frps.ini:/etc/frp/frps.ini --name frps yetio/frps
```

start frpc

```bash
docker run --restart=always --network host -d -v /etc/frp/frpc.ini:/etc/frp/frpc.ini --name frpc yetio/frpc
```

## Quick reference

* Maintainer:
yetio(yetio@126.com)

* Folked from:

snowdream <sn0wdr1am@icloud.com>

* Supported architectures: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))

frpc:

[amd64](https://cloud.docker.com/u/yetioamd64/repository/docker/yetioamd64/frpc), [arm32v6](https://cloud.docker.com/u/yetioarm32v6/repository/docker/yetioarm32v6/frpc), [arm32v7](https://cloud.docker.com/u/yetioarm32v7/repository/docker/yetioarm32v7/frpc), [arm64v8](https://cloud.docker.com/u/yetioarm64v8/repository/docker/yetioarm64v8/frpc), [i386](https://cloud.docker.com/u/yetioi386/repository/docker/yetioi386/frpc)

frps:

[amd64](https://cloud.docker.com/u/yetioamd64/repository/docker/yetioamd64/frps), [arm32v6](https://cloud.docker.com/u/yetioarm32v6/repository/docker/yetioarm32v6/frps), [arm32v7](https://cloud.docker.com/u/yetioarm32v7/repository/docker/yetioarm32v7/frps), [arm64v8](https://cloud.docker.com/u/yetioarm64v8/repository/docker/yetioarm64v8/frps), [i386](https://cloud.docker.com/u/yetioi386/repository/docker/yetioi386/frps)

* Supported Tags:

[Frps](https://cloud.docker.com/u/yetio/repository/docker/yetio/frps/tags)

[Frpc](https://cloud.docker.com/u/yetio/repository/docker/yetio/frpc/tags)

## Sponsors

[![tencent cloud](https://upload-dianshi-1255598498.file.myqcloud.com/%E5%8D%81%E5%B9%B4%E6%B7%B1%E8%89%B2_345%20200-9da3bd26b593519373f731a7e00a7e0d10e5fb04.jpg)](https://cloud.tencent.com/act/cps/redirect?redirect=1067&cps_key=7ad172f808f30965a01c05887137e4d8&from=console)

[![aliyun](https://img.alicdn.com/tfs/TB1EYNWOEH1gK0jSZSyXXXtlpXa-440-240.png)](https://www.aliyun.com/daily-act/ecs/activity_selection?userCode=dbgo15cy)

## Contact (备注：frp)

* Email: 3217680847#qq.com
* QQ: 3217680847
* QQ群: 82695646
* WeChat: sn0wdr1am86

## Website

1. [fatedier/frp](https://github.com/fatedier/frp)
1. [Snowdream Tech](http://www.snowdream.tech/)
1. [ITCoder](https://www.itcoder.tech/)

## License

Apache 2.0
