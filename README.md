# 轻记 Android WebView 项目

当前版本：`1.4.1-qingji-schemeB-brand`

本版基于 **方案 B：时间轴 · 沉浸式**，并完成轻记品牌信息统一。

## 本版修正

- 应用名称统一为「轻记」
- applicationId / namespace 统一为 `com.qingji.memo`
- Java 包名从旧模板包名迁移为 `com.qingji.memo`
- GitHub Actions artifact 名称改为 `QingjiMemo_v1_4_1_schemeB_apk`
- Launcher 图标替换为轻记时间轴 Logo
- 首页顶部增加轻记 Logo 标识
- 通知渠道、SharedPreferences、悬浮窗 Action 等内部命名改为轻记相关命名
- 保留方案 B 时间轴 UI 与新增、搜索、编辑、提醒、导出、Checklist 等功能

## 构建

```bash
./gradlew assembleDebug
```

或使用 `.github/workflows/build-apk.yml` 自动构建。
