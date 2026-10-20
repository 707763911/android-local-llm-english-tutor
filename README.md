
### 8. `android-local-llm-english-tutor/README.md`

```markdown
# Android Local LLM English Tutor

安卓本地/半离线 LLM 与语音识别的英语练习应用实现。仓库内对话与模型配置为脱敏合成数据，不包含客户数据。

## 功能
- 场景化英语对话
- ASR 语音输入
- 本地/半离线 LLM 推理入口
- TTS 朗读回复
- 简单纠错与提示
- 对话历史本地保存（可选）

## 技术栈
Kotlin、Android、本地 LLM Runtime（llama.cpp/MLC 等按实际）、ASR/TTS

## 快速开始
1. Android Studio 打开项目
2. 按项目说明放置模型文件或配置服务地址
3. 授予麦克风权限后开始对话

## 安全与合规
- 对话内容为脱敏合成数据
- 模型许可按实际模型确认
- 不采集用户语音与对话上传

## License
MIT（第三方模型与库遵循各自许可）
