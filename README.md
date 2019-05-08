vim 使用方法技巧
-----------------
* SecureCRT右键粘贴异常（出现VISUAL BLOCK)

解决办法：
1. 在当前用户home目录新建文件：`.vimrc`(若有则无需创建)<br>
2. 在vimrc中添加：`set mouse=nv`<br>

-----------------------------------------------------------
Reference:https://www.itbulu.com/err-wget-not-trusted.html

解决办法：
--no-check-certificate
我们可以直接在wget后面加上脚本即可。
或者我们可以：
```
apt-get install ca-certificates -y #Debian/Ubuntu
yum install ca-certificates -y  #CentOS
```
安装完毕之后应该是可以不用上面脚本直接可以wget。
