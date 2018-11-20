## Android与JS 通过WebView互相调用方式 ##

### 对于Android调用JS代码的方法
* 通过WebView的loadUrl()
* 通过WebView的evaluateJavascript()
### 对于JS调用Android代码的方法
* 通过WebView的addJavascriptInterface()进行对象映射 
* 通过WebViewClient的ShouldOverriderUrlLoading()方法回调拦截url 
* 通过WebChromeClient的onJsAlert(),onJsConfirm(),onJsPrompt() 方法回调拦截 JS对话框alert(),confirm(),prompt()消息
