# PGGCrypto
  鹏哥哥加密算法<br>   
  超全的加密算法锦集<br>
  每个算法都进行了封装 都可以通过类方法直接进行创建使用 而且各个类方法中都有详细的说明 使用时请仔细查看<br>
  如果对您有所帮助 请点进下面GitHub链接 送一颗宝贵的星星给我<br>
  GitHub地址  https://github.com/penghero/PGGCrypto.git
# 演示GIF
![image](https://github.com/penghero/PGGCrypto/blob/master/gif/Untitle1.gif)
# 部分讲解
1、AES加密（对称加密算法）<br>
优点：简单、可并行计算、误差不传递<br>
缺点：不能隐藏明文模式（比如图像加密轮廓仍在）、主动攻击（改明文，后续内容不影响，只要误差不传递该缺点就存在）<br>
用途：需要并行加密的应用<br>
 AES加密算法是密码学中的高级加密标准，该加密算法采用对称分组密码体制，密钥长度的最少支持为128、192、256，分组长度128位，算法应易于各种硬件和软件实现。这种加密算法是美国联邦政府采用的区块加密标准，这个标准用来替代原先的DES，已经被多方分析且广为全世界所使用。设计为支持128／192／256位（/32=nb)数据块大小（即分组长度）；支持128／192／256位（/32=nk)密码长度，，在10进制里，对应34×1038、62×1057、1.1×1077个密钥
2、DES加密（对称加密解密）<br>

3、RSA加密  （非对称加密）<br>
包括.der和.p12文件加密解密，和公钥私钥字符串加密解密<br>
特点<br>
RSA加密算法是目前最有影响力的公钥加密算法，并且被普遍认为是目前最优秀的公钥方案之一。RSA是第一个能同时用于加密和数宇签名的算法，它能够抵抗到目前为止已知的所有密码攻击，已被ISO推荐为公钥数据加密标准。RSA加密算法基于一个十分简单的数论事实：将两个大素数相乘十分容易，但想要对其乘积进行因式分解却极其困难，因此可以将乘积公开作为加密密钥。<br>

4、MD5加密<br>
 MD5的作用是让大容量信息在用数字签名软件签署私人密钥前被"压缩"成一种保密的格式（就是把一个任意长度的字节串变换成一定长的十六进制数字串）。<br>
 全写： Message Digest Algorithm MD5（中文名为消息摘要算法第五版）<br>
 输出： 128bit<br>
 特点：<br>
 1、压缩性：任意长度的数据，算出的MD5值长度都是固定的。<br>
 2、容易计算：从原数据计算出MD5值很容易。<br>
 3、抗修改性：对原数据进行任何改动，哪怕只修改1个字节，所得到的MD5值都有很大区别。<br>
 4、弱抗碰撞：已知原数据和其MD5值，想找到一个具有相同MD5值的数据（即伪造数据）是非常困难的。<br>
 5、强抗碰撞：想找到两个不同的数据，使它们具有相同的MD5值，是非常困难的。<br>
 缺陷：Md5一度被认为十分靠谱。2004年8月17日的美国加州圣巴巴拉的国际密码学会议（Crypto’2004）上，来自中国山东大学的王小云教授做了破译MD5、HAVAL-128、 MD4和RIPEMD算法的报告，公布了MD系列算法的破解结果。2009年，冯登国、谢涛二人利用差分攻击，将MD5的碰撞算法复杂度从王小云的2^42进一步降低到2^21，极端情况下甚至可以降低至2^10。仅仅2^21的复杂度意味着即便是在2008年的计算机上，也只要几秒便可以找到一对碰撞。Md5已老， 在安全性要求较高的场合，不建议使用。<br>
 
 5、sha1加密（安全[哈希算法]）只是叫做一种算法，用于检验数据完整性<br>
 全名： 安全哈希算法（Secure Hash Algorithm）输出： 160bit<br>
 与Md5比较<br>
 相同点：<br>
 因为二者均由MD4导出，SHA-1和MD5彼此很相似。相应的，他们的强度和其他特性也是相似。<br>
 不同点：<br>
 1. 对强行攻击的安全性：最显著和最重要的区别是SHA-1摘要比MD5摘要长32 位。使用强行技术，产生任何一个报文使其摘要等于给定报摘要的难度对MD5是2^128数量级的操作，而对SHA-1则是2^160数量级的操作。这样，SHA-1对强行攻击有更大的强度。<br>
 2. 对密码分析的安全性：由于MD5的设计，易受密码分析的攻击，SHA-1显得不易受这样的攻击。<br>
 3. 速度：在相同的硬件上，SHA-1的运行速度比MD5慢。<br>
 
 6、 HMAC加密消息摘要算法<br>
  我们通常在遇到的时候会看到“HMAC”字眼，mac（Message Authentication Code，消息认证码算法）是含有密钥散列函数算法，兼容了MD和SHA算法的特性，并在此基础上加上了密钥。因此MAC算法也经常被称作HMAC算法。<br>
  
 7、HMACMD5加密<br>
  
  
