# LogUtils
Easy way to display log 
============
```
LogUtils logUtils;

@Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        logUtils = new LogUtils(this.getClass());
        logUtils.LOGE("Enter Your String Value Here");
        }
```
