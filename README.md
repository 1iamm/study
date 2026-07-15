# AI 课程助手

这份仓库保存两门一对一课程的提示词、课堂书签和课后复习资料：

- `courses/spanish/`：西班牙语课
- `courses/guitar/`：吉他课

## 一次性设置

1. 在 ChatGPT 中分别创建两个 Project：`西班牙语`、`吉他`。
2. 将每个目录中的 `chatgpt-project-instructions.md` 全文复制到对应 Project 的 **Project settings → Instructions**。
3. 上课前，在 macOS ChatGPT App 手动启动 Record，并确认已授予麦克风和系统音频权限。
4. 课中用 `lesson-marker-template.md` 的格式插入短书签；最稳妥的方式是在腾讯会议静音后口头说出书签。
5. 下课后把该课的 `after-class-prompt.md` 发给本次 Record，让它按照书签前后文输出复习资料。把老师给的作业、课件和截图一并上传到相应 Project。

## 工作方式

ChatGPT Record 负责记录整节课；你不写完整笔记，只在个人卡点、老师纠正、作业和阶段切换时插入书签。书签和课程音频在同一份转写中，便于 AI 在课后补全前后文。

这些 Markdown 文件不会自动同步到 ChatGPT；它们是可编辑、可备份的源文件。每次调整提示词后，将变更复制回相应 ChatGPT Project 即可。

录制前请先取得老师同意。
