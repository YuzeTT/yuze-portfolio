安装总结

  你的项目 pnpm 配置了 trust-policy=no-downgrade，它会阻止降级信任的包（比如缺少 provenance attestation
  的新版本）。这导致常规安装失败。

  解决方法： 临时覆盖配置

  pnpm install --save-dev @iconify-json/simple-icons --config trust-policy=downgrade

  如果这个不生效，可以用分步命令：

  pnpm config set trust-policy downgrade --location project
  pnpm install --save-dev @iconify-json/simple-icons
  pnpm config set trust-policy no-downgrade --location project  # 装完恢复

  记住的要点：
  - --config trust-policy=downgrade 只对当次命令生效（首选）
  - 如果要长期装多个包，可以临时改 project 级配置，装完改回来
