## 文本识别

文本识别技术采用了*google*的*firebase_ml_vision*。目前只有*firebase_ml_vision*支持本地文字识别，但也只限于英文和数字。由于其他语言的识别需要上传到*google*服务器，ENotes出于安全性考虑，暂时不支持。后续也许会增加新的入口，通过上传服务器获取识别结果，支持其他语言的识别。

### 使用说明
打开"文本识别"后，出现有红框包围文本出现时说明已经有文本被识别。目前设置会把5秒内识别的最长文本返回，用户也可以手动返回。
