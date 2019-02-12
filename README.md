# Android_HandWrite
手写签名

## 步骤1.将JitPack存储库添加到构建文件中 ##

将其添加到存储库末尾的根build.gradle中：

    	allprojects {
			repositories {
				...
				maven { url 'https://jitpack.io' }
			}
		}

## 步骤2.添加依赖项 ##

    	dependencies {
		        implementation 'com.github.nangongyibin7219:Android_HandWrite:1.0.0'
		}


## 效果图：##

![](https://github.com/nangongyibin7219/Android_HandWrite/blob/master/1.gif?raw=true)