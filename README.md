# Forwarning 
There are inherent dangers in the use of any software available for download on the Internet, and we caution you to make sure that you completely understand the potential risks before downloading any of the software.

The Software and code samples available here are provided "as is" without warranty of any kind, either express or implied. Use at your own risk.

The use of the software and scripts downloaded on this site is done at your own discretion and risk and with agreement that you will be solely responsible for any damage to your computer system or loss of data that results from such activities. You are solely responsible for adequate protection and backup of the data and equipment used in connection with any of the software, and we will not be liable for any damages that you may suffer in connection with using, modifying or distributing any of this software. No advice or information, whether oral or written, obtained by you from me or from here shall create any warranty for the software.

I make makes no warranty that

* the software will meet your requirements
* the software will be uninterrupted, timely, secure or error-free
* the results that may be obtained from the use of the software will be effective, accurate or reliable
* the quality of the software will meet your expectations
* any errors in the software obtained from me will be corrected.

The software, code sample and their documentation made available here could include technical or other mistakes, inaccuracies or typographical errors. We may make changes to the software or documentation made available on its web site at any time without prior-notice.may be out of date, and we make no commitment to update such materials.

I assume no responsibility for errors or omissions in the software or documentation available from its web site.

In no event shall I be liable to you or any third parties for any special, punitive, incidental, indirect or consequential damages of any kind, or any damages whatsoever, including, without limitation, those resulting from loss of use, data or profits, and on any theory of liability, arising out of or in connection with the use of this software.

Henry Wong

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
