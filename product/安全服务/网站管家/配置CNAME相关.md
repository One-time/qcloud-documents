### 如何配置 CNAME?
- CNAME 域名不能直接访问，您需要在域名服务提供商处完成 CNAME 配置，配置生效后，WAF 将对域名进行防护，具体 CNAME 配置步骤，可参见 [配置 CNAME](https://cloud.tencent.com/document/product/228/3121)。
-  若已完成 CNAME 配置，在您的域名接入 WAF 后，系统会为您自动分配一个以`.qcloudxxx.com`(如 `.qlcoudcjpj.com`、`qcloudwzgj.com` 等)为后缀的 CNAME 域名，可在 [WAF 控制台域名列表](https://console.cloud.tencent.com/guanjia/tea-domain) 中，实例信息处进行查看。
![](https://qcloudimg.tencent-cloud.cn/raw/9db3977fbb4d82da9ace5e7fa16dc7f6.png)
