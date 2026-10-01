# GitHub 上传步骤（JAUE26-10 R105）

建议仓库名：

`coccinellid-aphid-forecast-reanalysis`

## 上传

1. 登录 GitHub。
2. 点击 **New repository**。
3. Repository name 填上面的建议名称，或使用你自己的名称。
4. 选择 **Public**。
5. 不需要让 GitHub 自动生成 README，因为本包已经有 `README.md`。
6. 在电脑上先解压本 ZIP。
7. 把解压后的仓库根目录中的文件和文件夹上传到 GitHub；不要只上传 ZIP 后就结束，因为 GitHub 不会自动把 ZIP 展开成可浏览仓库结构。
8. Commit message 可写：`Publish R105 supporting materials for JAUE26-10`。

## 建议再做一个 Release

上传完成后：

1. 打开仓库右侧 **Releases**。
2. 创建新 Release。
3. Tag 建议：`R105`。
4. Release title：`R105 supporting materials`。

GitHub 仓库 URL 本身可以作为公开在线地址。若以后需要 DOI，可再把 GitHub Release 归档到支持 DOI 的长期存储服务。

## 非常重要

当前包中 **没有** 原始 `Analysis_Code_Derived_Outputs_R104.zip`。因此，在补入该文件之前，不要把仓库描述为“完整代码复现包”。

你上传完成后，把 GitHub 仓库链接发回 ChatGPT。我可以把真实仓库 URL 写入：

- 修订主稿；
- 给编辑的逐点回复；
- 重投邮件；
- 仓库 README；

然后生成真正可重新发送给 JAUE 编辑的最终包。
