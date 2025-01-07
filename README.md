@https://t.me/CF_NAT/38840

Usage of cfnat:

-addr string
本地监听的 IP 和端口 (default "0.0.0.0:1234")

-code int
HTTP/HTTPS 响应状态码 (default 200)

-colo string
筛选数据中心例如 HKG,SJC,LAX (多个数据中心用逗号隔开,留空则忽略匹配)

-delay int
有效延迟（毫秒），超过此延迟将断开连接 (default 300)

-domain string
响应状态码检查的域名地址 (default "cloudflaremirrors.com/debian")

-ipnum int
提取的有效IP数量 (default 20)

-ips string
指定生成IPv4还是IPv6地址 (4或6) (default "4")

-num int
目标负载 IP 数量 (default 10)

-port int
转发的目标端口 (default 443)

-random
是否随机生成IP，如果为false，则从CIDR中拆分出所有IP (default true)

-task int
并发请求最大协程数 (default 100)

-tls
是否为 TLS 端口 (default true)
