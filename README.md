# zxing
扫描二维码libs，用于使用JitPack发布开源库
## https://jitpack.io/
### 使用方式
第1步：添加JitPack库来构建文件

在你的根的build.gradle添加在库的结尾：

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
第2步：添加的依赖

	dependencies {
	        compile 'com.github.zhao-mingjian:zxing:v1.0.1'
	}
