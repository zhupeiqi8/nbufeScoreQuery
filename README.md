## nbufeScoreQuery 成绩查询工具

使用 PyInstaller 打包 `nbufeScoreQuery.py` 为可执行文件（`.exe`）。以下是命令和每个参数的详细说明：

```bash
pyinstaller.exe -F ./nbufeScoreQuery.py \
--add-data="C:\\**\\Lib\\site-packages\\onnxruntime\\capi\\onnxruntime_providers_shared.dll;./onnxruntime/capi" \
--add-data="C:\\**\\Lib\\site-packages\\ddddocr\\common.onnx;./ddddocr"  \
--add-data="C:\\**\\Lib\\site-packages\\ddddocr\\common_old.onnx;./ddddocr"
