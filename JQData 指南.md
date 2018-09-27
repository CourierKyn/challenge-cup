**安装 JQData**：打开本地 cmd 终端（确保可以使用 conda、pip 等命令，否则使用 anaconda prompt），输入如下语句 ，安装 JQData 数据包：

```
pip install git+https://github.com/JoinQuant/jqdatasdk.git -i https://mirrors.aliyun.com/pypi/simple/
```

**使用 JQData**：安装成功后，打开 python、ipython、jupyter 或其他 IDE 等，输入如下语句，导入 JQData 数据包，并认证用户身份。认证完毕显示“auth success”后即可使用：

```
from jqdatasdk import *
auth('**********','**********')
```

**调用数据**：详见JQData数据调用方法：https://www.joinquant.com/help/api/help?name=JQData#%E6%95%B0%E6%8D%AE%E8%B0%83%E7%94%A8%E6%96%B9%E6%B3%95
