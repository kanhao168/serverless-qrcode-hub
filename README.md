登录 Cloudflare 并创建 D1 SQL 数据库
复制 D1 SQL 数据库 ID
回到 GitHub 并 Fork 仓库
在 GitHub 打开你 Fork 的仓库的 wrangler.toml 文件，点击图中的按钮编辑
将 d1_databases 下的 database_id 内容替换为你自己拷贝的 D1 SQL 数据库 ID
回到 Cloudflare 并创建 Worker
选择你 Fork 的 Github 仓库，然后直接点击右下角的 保存并部署
等待部署成功，自动跳转到了这个页面，此时默认分配的 *.workers.dev 域名在国内访问较慢，建议绑定自己的域名
绑定自定义域名
设置一个你在 Cloudflare 托管的域名的子域名
 设置访问密码，注意密码格式为英文字母和数字，尽量长尽量复杂，推荐使用两段随机生成的uuid字符串作为密码
 部署成功，此时已经可以面板上通过默认分配的 *.workers.dev 或者你自定义的域名访问了！
