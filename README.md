## koa-ts-template

该模板是集成了 prisma orm 的版本。

## 使用

- 添加.env 文件 设置 DATABASE_URL 参考[prisma 文档](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/connect-your-database-typescript-postgres).
- 执行下面脚本根据 model 创建对应的数据表 user post

  ```
  npm run db
  ```

- 开启应用

  ```
  npm run start
  ```

## 注意事项

每次手动修改 model 后需要重新生成 prisma client api，即手动执行

```
 npm run db
```

如果执行完后仍然 ts 没有正确的代码提示，关掉项目重新启动即可

## 参考资料

[prisma 官方文档](https://www.prisma.io/)
