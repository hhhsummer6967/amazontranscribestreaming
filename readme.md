
在aws文件中填入参数，注意正式环境不建议将密钥放在该文件中，此处为最小化功能验证使用
```
export const AWS_REGION = "XXXX";
export const AWS_ACCESS_KEY_ID = "XXXXX";
export const AWS_SECRET_ACCESS_KEY = "XXXX"

```
运行以下命令
```
# 安装插件
npm install

#打包文件
npx webpack --config webpack.config.js
```


参考文档：
https://medium.com/@jannden/create-an-amazon-transcribe-web-app-with-javascript-a56c14b87db2

https://docs.pingcode.com/baike/2484253
