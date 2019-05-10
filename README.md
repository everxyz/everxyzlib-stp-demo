
# everxyzlib-stp-demo
This demo shows you how to use everxyzlib to render step file in your website.

此demo适用于Everxyz的EverAPI产品，运行此demo前，请先阅读[EverAPI开发文档](https://www.everxyz.com/api)的stp格式部分。

## 使用说明

只需在 `localhost:9090` 下开启 web 服务即可

开启服务后, 在浏览器中打开 `http://localhost:9090`

可以参考如下方法中的一种

### 1. node 环境

  如果你已安装了 node 和 npm:

  ```bash
  $ npm install
  $ npm run start # 或 npx http-server -p 9090
  ```
  注：
  
  1.npm rum start的默认端口为5757
  
  2.服务开启的域名端口，需与申请clientid的域名一致，如clientid是使用localhost：9090申请的，则此处服务器端口也需为9090
  
### 2. python3

  ```bash
  $ python3 -m http.server 9090
  ```

## 3. python2

  ```bash
  $ python2 -m SimpleHTTPServer 9090
  ```

