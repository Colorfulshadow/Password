# Password
a .py file to create a  strong password
```
import hashlib
str = ''

md5_obj=hashlib.md5("".encode("utf-8"))
md5_obj.update(str.encode("utf-8"))

print('MD5加密前为 ：' + str)
print('MD5加密后为 ：' + md5_obj.hexdigest())
print('MD5加密后前十二位是：'+ md5_obj.hexdigest()[0:12])
print('通过此种方法生成的密码是：Zty'+md5_obj.hexdigest()[0:12]+'!@#')
```
