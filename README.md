# Remote_Test

在嘗試遠端連接 -> git clone .. 的時候會出現被deny的情況：
後還是看到，我沒有自己的SSH的key，所以會被denied，
就自己用RSA生成一組pulic/private key，
把pulic key新增到git-hub的SSH key那邊，就可以了!
Key's Location：( C:\Users\USER\.ssh )
