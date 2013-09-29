bootstrap-legacy-ie
===================

    <!--[if lt IE 8 ]>
    <script src="bootstrap-legacy-ie.js" data-bootstrap-legacy-ie data-target="#main"></script>
    <![endif]-->


## Options

* `data-target` (Required)  
    Default: null  
    Accepts a jQuery selector string. This option indicates where the message box should be shown.

* `data-method` (Optional)  
    Default: `append`  
    How does the message block should be added to the target element. You can use any [jQuery manipulation method](http://api.jquery.com/category/manipulation/) to replace the default method.

* `data-html` (Optional)  
    Default: a message html  
    If you like, you can specify your custom message in html format via `data-html` option. Here is the default message:

        <div class="alert alert-info clearfix">
            <i class="icon-exclamation-sign pull-left"></i>
            <div class="pull-left margin-left-half">
                您所使用的 IE 瀏覽器版本已過時，我們建議您升級您的瀏覽器以達到最佳瀏覽效果。<br />
                我們建議您將 <a class="text-error" href="http://windows.microsoft.com/zh-tw/internet-explorer/download-ie" target="upgrade-browser">瀏覽器升級至IE9</a> 以上或改用瀏覽效果更佳的 <a class="text-error" href="http://www.google.com/intl/zh-TW/chrome/browser/" target="upgrade-browser">Google Chrome</a> 瀏覽器<br />
                若您是 <strong>Windows XP</strong> 使用者，請將 <a class="text-error" href="http://windows.microsoft.com/zh-TW/internet-explorer/downloads/ie-8">瀏覽器升級至IE8</a> 或改用瀏覽效果更佳的 <a class="text-error" href="http://www.google.com/intl/zh-TW/chrome/browser/" target="upgrade-browser">Google Chrome</a> 瀏覽器
            </div>
        </div>

