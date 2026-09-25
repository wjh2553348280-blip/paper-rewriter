# Paper Rewriter

AI 辅助学术写作与论文改写工具，基于 Python 和 Streamlit 构建。

> 这是该系列项目的主维护仓库。`paper-rewriter-2` 与 `paper-rewriter-3` 为历史实验版本，仅供参考。

## 项目结构

- `app.py`：Streamlit 应用入口
- `ai_rewriter.py`：改写核心逻辑
- `prompts.py`：提示词定义
- `requirements.txt`：Python 依赖

## 本地运行

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
streamlit run app.py
```

请在本地配置凭据，切勿提交 API 密钥或其他敏感信息。