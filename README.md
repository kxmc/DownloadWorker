使用方式
```
  RxDownloadUtil.builder()
                .setFragmentManager(getSupportFragmentManager())
                .setUri("http://zx.xkzdai.com/data/wx_app.apk")
                .setBtnType(BTN_TYPE_CANCEL_AND_ENSURE)
                .setFileName("")
                .setMessage("新版本发布了，欢迎下载，快试试新功能吧")
                .setTitle("下载标题")
                .build();
```