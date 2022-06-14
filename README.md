# react-learning

## Project init

1. 全局安装create-react-app

   ```shell
   npm install -g create-react-app
   create-react-app ProjectName    // 创建项目
   ```

2. 配置github代码仓

   ```shell
   git config --global user.name 'Shaye/96'	// 配置用户名
   git config --global user.email '1151032202@qq.com'// 配置Email
   ssh-keygen -t rsa -C '1151032202@qq.com'	// 生成id_tsa.pub文件（密钥）
   GitHub - 个人- setting - ssh.... - new SSh - 将文件内容复制进去
   ```

3. 创建本地分支并同步到代码仓

   ```shell
   git checkout -b dev_1
   git push -u origin dev_1
   ```

   