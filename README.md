# webnow.jnlp
WebNow JNLP

```
<?xml version="1.0" encoding="UTF-8"?>
<jnlp codebase="http://myURL.to/webnow/" spec="1.0+">
        <information>
                <title>WebNow</title>
                <vendor>Perceptive Content</vendor>
                <description>Web Now</description>
        </information>
        <security>
                <all-permissions/>
        </security>
        <resources>
                <java href="http://java.sun.com/products/autodl/j2se" version="1.7+"/>

                <jar href="webnowapplet.jar" main="true"/>
                <jar href="lang.jar"/>
                <jar href="TimingFramework-1.0.jar"/>
                <jar href="jxlayer.jar"/>
                <jar href="l2fprod-common-all.jar"/>
                <jar href="icebrowser.jar"/>
                <jar href="jniwrap-3.8.4.jar"/>
                <jar href="comfyj-2.10.jar"/>
                <jar href="winpack-3.8.4.jar"/>
                <jar href="slf4j-api-1.5.8.jar"/>
                <jar href="slf4j-simple-1.5.8.jar"/>
        </resources>

<applet-desc main-class="com.imagenow.webnow.applet.WebNow"  name="webnow" width="1280" height="800">
        <param name="java_version" value="1.6* 1.7* 1.8*"/>
        <param name="archive" value="webnowapplet.jar,lang.jar,TimingFramework-1.0.jar,jxlayer.jar,l2fprod-common-all.jar,icebrowser.jar,jniwrap-3.8.4.jar,comfyj-2.10.jar,winpack-3.8.4.jar,slf4j-api-1.5.8.jar,slf4j-simple-1.5.8.jar"/>
        <param name="code" value="com.imagenow.webnow.applet.WebNow"/>
        <param name="cache_archive" value="webnowapplet.jar,lang.jar,TimingFramework-1.0.jar,jxlayer.jar,l2fprod-common-all.jar,icebrowser.jar,jniwrap-3.8.4.jar,comfyj-2.10.jar,winpack-3.8.4.jar,slf4j-api-1.5.8.jar,slf4j-simple-1.5.8.jar"/>
        <param name="MAYSCRIPT" value="true"><param name="displayusername" value="null"/>
        <param name="sessionid" value="2C99764B184E220773970B0854649E32"/>
        <param name="safari" value="true"/>
        <param name="centerimage" value="true"/>
        <param name="boxborder" value="false"/>
        <param name="image" value="webnow_startup.jpg"/>
        <param name="native-support" value="true"/>
        <param name="appletSessionId" value="1557258294882"/>
</applet-desc>
</jnlp>
```

## Instructions
Replace myURL.to with correct URL, save as .jnlp file

## Execute Java Web Start
```
javaws <filename.jnlp>
```
