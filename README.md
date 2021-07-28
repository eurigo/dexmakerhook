# dexmakerhook
提取自[dexmaker release v2.28.1](https://github.com/linkedin/dexmaker),包含ProxyBuilder的hook库

反射调用时发现网络上现有库都不是基于最新的dexmaker版本，导致ProxyBuilder类代码不同，重新从dexmaker v2.28.1版本中提取出，不包含Mockito相关类

+ ## Use
#### Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
#### Step 2. Add the dependency
```
	dependencies {
	        implementation 'com.github.eurigo:dexmakerhook:1.0'
	}
```
