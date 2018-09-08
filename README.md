[test-one](https://github.com/Hongyu-Pang/test/blob/master/test-one.ipynb)
### 任务：
将image文件夹下所有的图片名'-‘后面的数字写到一个1.txt文件夹下，一个图片名出来的数字写在一行，读取1.txt文件，打印出里面每一行的内容
### 难点：
os.listdir：返回指定的文件夹包含的文件或文件夹的名字的列表
enumerate():用于将一个可遍历的数据对象(如列表、元组或字符串)组合为一个索引序列,同时列出数据和数据下标
with open(filename, mode) as f:读取文件
str.split()：单一分割指定字符串，不支持正则及多个切割符号
str.strip()：移除字符串头尾指定的字符(默认为空格或换行符)或字符序列
