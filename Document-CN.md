# 自建图床！国内延迟最低0.22s！超轻松，草履虫都能学会的教程！
## 先说优点
1. 国内延迟极低
2. 图片高可用，多副本，异地备份
3. 正常使用完全免费
4. 搭建简单，不要域名。不要服务器，只要一个账号
## 缺点
 ~~没有缺点，免费的要什么自行车~~

1. 图片不能上传大于20m的
## 演示站地址
http://clo4pni5g6hclq1elc20.app.memfiredb.com/

## 搭建方法

### 注册账号

点击 [注册链接](https://cloud.memfiredb.com/auth/login?from=fZA8As)
直接短信登录即可 会自动创建账号

### 创建应用

登陆成功后点击我的应用

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/b2043f94fe2847a98226da96330c9a57.png)
*对，你没看错，这家公司主营分布式数据库的，也挺好用，以后我再出个教程*

点击创建应用

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/f47cbf8cf6e64756b4136c1e86045cf2.png)


![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/0811850bb11f4950aa2c1a2fe790e033.png)

名称随便填，数据库账号点创建新账号，会跳转到账号管理

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/87c8aeee70e845a6b16e1a1d60dc4dc7.png)

点击创建账号

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/d6f6f623090742c9bc19c592eac4d34b.png)

创建完之后返回创建应用 选择刚刚创建的账号

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/1b61f53b58a440ddb9cea1b03255e628.png)
创建之后会一直加载 等到应用的左上角出现绿色√，鼠标移到省略号，点击进入应用

![如图](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/dc6d7b741a73408aae36e7421c16a07d.png)

点击设置

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/49ec1800255c45229110975dd6405fd1.png)
点击API

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/590a47f98cee4e819b335ba28247000b.png)
复制以下两个值 **保存备用**
URL：
应用API密钥：公钥

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/b819f073b8e7494fa9ebca7fe260a8bc.png)
然后点击储存-新建储存桶，**储存桶名字保存备用**

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/7285564529024b09b1a67072f18ceeac.png)
切记 一定要选择公开储存桶
然后给桶添加策略：

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/4949628f26c64f7aaba9bd423237d822.png)
策略名称随便输就行 然后选择SELECT和INSERT，点击回看

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/ea50e6b70cce488d9e49699bee6e097d.png)
然后点击保存即可

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/5e6b120e76a2417cbb57d5115a184c15.png)然后下载我的代码
github:
https://github.com/RuiZhang-cn/memfire-img

![github](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/bc0955f4362443589b41d0d3b7049d8a.png)
或者前往gitee:
https://gitee.com/rui2450/memfire-img

![gitee](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/c68b2f456b724bce90535f4b1a56ba82.png)
下载zip文件之后 找到里面的index.html
用文本编辑器打开，修改以下内容：

![修改](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/a04e11868ca141dda9c5a5b4162e055f.png)

然后把html文件压缩成zip 点击上传文件即可。如果之前有文件先点击清空文件

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/a5e436ba49254e7ba3194dd9841644d9.png)
成功后点击上面的访问地址即可

![rt](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/0683d60e38534aad8656df80faa72540.png)
然后就开始使用吧！后面我会编写对接api相关的教程！

![enter description here](https://clo4pni5g6hclq1elc20.baseapi.memfiredb.com/storage/v1/object/public/%E5%9B%BE%E5%BA%8A/fd6207b97df3432b83378f4e264b0547.png)
