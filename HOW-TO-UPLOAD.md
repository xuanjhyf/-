# 把这个求职仓库传到 GitHub（约 10 分钟）

不用命令行工具，用 GitHub Desktop 图形界面最稳。

## 一、注册 GitHub

1. 打开 https://github.com 注册。
2. 用户名建议用 `he-yufei` / `yufei-ai` 这类（会写进简历）。

## 二、新建仓库

1. 右上角「+」→「New repository」。
2. Repository name：`kejian-expert`（或 `ai-kejian-expert`）。
3. Description（可直接抄）：
   ```
   AI 中学语文备课 Agent（可部署交付版 v1.16.0）：认课文→扫素材→出课件→教案 + 评测体系 + 15 项整改实录
   ```
4. 选 Public（必须，HR 才能看到）。
5. 不勾 README（我们用自己的）。
6. Create。

## 三、用 GitHub Desktop 上传

1. 下载安装 https://desktop.github.com。
2. 登录账号。
3. File → Add Local Repository → 选本地 `github-kejian-expert` 文件夹。
   - 提示 not a git repo → 点 Create repository，路径选它，其他默认。
4. 左侧显示文件变更 → Summary 填：`feat: 课件专家交付档案 + 评测体系`。
5. Commit to main。
6. Publish repository → 取消勾选 private → Publish。

## 四、确认

打开 `https://github.com/你的用户名/kejian-expert`，确认：

- README 正常渲染
- docs / eval_sets / data / reports 有内容
- 文件名没有乱码

## 注意

- 一定要 Public。
- 真实教材数据不要上传（已在 .gitignore 里）。
- 手机号可以保留，也可以改成邮箱。
- 核心源码/脚本可脱敏后公开，也可不公开。求职版放的是复盘、评测、架构和简历案例，不放全部私有数据。

## FAQ

Q：没有代码基础，放一个没代码的仓库会不会显得假？
A：这份仓库的重点是讲清楚"我做过、我怎么修、我怎么验证"，对 AI 产品经理岗本来就比对代码量更看重。真有需要可以再补源码。

Q：要不要放真实源码？
A：可选。求职版的核心是把"我做了什么、怎么修、怎么验证"讲明白，不要求全量代码。