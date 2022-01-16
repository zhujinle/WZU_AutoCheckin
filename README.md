# WZU_AutoSign

自行魔改适配了最新的提交格式，已包含于Json之中
## 如何使用
1. 配置好main里的头部信息和邮箱等(如果是本地运行，邮箱可以不需要)
> 请注意，此处的Header和cookie以及Json内容为了保护个人隐私我均已删除，请自行抓包
2. 在wzu_payload里覆盖粘贴抓包到的提交的json
<details>
<summary>不会抓包的我提供一个思路：</summary>
<pre><code>
    下载 FireFox 浏览器，打开温大网站，按下 F12 然后选择网络选项卡，开始检测。</br>
    提交一次问卷后找到写着POST的那一条，点击右侧的请求，复制整个 Json 信息即可</br>
    关于程序里需要的cookie和头信息，也可以在这里查到</br>
</code></pre>
</details>
如需交流请发issues

---

## 真的不会填写的我在Json里面留了我的默认格式，各位可以照着我的填起来然后在我的温大里面看看是否正确


### 感谢学长大佬提供思路和源代码，仓库链接:[TAOTAO5/wzu_sign](https://github.com/TAOTAO5/wzu_sign)和[wkz2003/WZU_AutoSign](https://github.com/wkz2003/WZU_AutoSign)
