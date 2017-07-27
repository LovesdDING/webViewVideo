# webViewVideo
解决Android webView 加载H5页面 播放视频时  没有全屏按钮的情况。 
H5 文件中已对js代码做设置 ，但Android端仍然需要 自己进行设置 需要对js做处理 
设置  setChromeClient  重写onShowCustomView 和onHideCustomView
