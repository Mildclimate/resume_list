# 📄 个人简历模板合集

> 自用 LaTeX 简历模板，使用 XeLaTeX 编译，支持中英文混排。

## 目录结构

| 文件 | 说明 |
|------|------|
| `myresume.tex` | 通用简历模板（示例：张某人），含教育经历、工作经历等基础结构 |
| `resume_boheng.tex` | **最新个人简历**（谢搏珩），覆盖教育背景、工作经历、项目经历、开源贡献等 |
| `myresume.aux` / `resume_boheng.aux` | LaTeX 辅助文件（编译自动生成） |

## 技术特性

- **编译方式**：XeLaTeX
- **字体配置**：
  - `myresume.tex` — 英文使用 Source Code Pro，中文使用 PingFang SC
  - `resume_boheng.tex` — 统一使用 PingFang SC 字体
- **颜色主题**：深空蓝 + 深海蓝 + 科技蓝，简约专业
- **自定义命令**：`\sectionheader` 章节标题、`\entry` 条目排版

## 使用方法

```bash
xelatex myresume.tex        # 编译通用模板
xelatex resume_boheng.tex   # 编译最新简历
```

## 后续计划

- [ ] 扩充更多简历版本（不同岗位方向）
- [ ] 添加英文简历模板
- [ ] 优化配色与排版样式
- [ ] 补充封面信（Cover Letter）模板
- [ ] 自动化编译脚本

## 许可

仅供个人参考与使用。
