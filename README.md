# S-DES
这是一个S-DES算法实现
## **开发说明**
根据"信息安全导论"课程第5次课讲述的DES算法：

* 实现简单的加解密（二进制加解密和ASCII码字符串加解密）
* 对相同的相同的密文进行交叉测试
* 在已知明密文的条件下暴力破解出密钥
* 对随机的明密文对进行封闭测试

## **运行程序**
```bash
sd_des.html
```
## **功能测试与运行界面**

* **主界面**
![主页面](https://github.com/TeFur0/S-DES/blob/main/png/主页面.png?raw=true)
* **二进制加密界面**
![位加密](https://github.com/TeFur0/S-DES/blob/main/png/位加密.png?raw=true)
* **交叉测试**
![交叉f](https://github.com/TeFur0/S-DES/blob/main/png/交叉f.png?raw=true)
![交叉](https://github.com/TeFur0/S-DES/blob/main/png/交叉.png?raw=true)
* **ASCII码加密界面**
![ASCII加密](https://github.com/TeFur0/S-DES/blob/main/png/ASCII加密.png?raw=true)
* **暴力破解界面**
![暴力破解](https://github.com/TeFur0/S-DES/blob/main/png/暴力破解.png?raw=true)
* **封闭测试**

针对同一个明密文对，可以确实存在多个不同的密钥K[i],k[j],能够加密相同的明文得到相同的密文。

尤其是在低安全强度的加密算法中，明文空间内会出现不同的密钥加密得到相同的密文的情况。
