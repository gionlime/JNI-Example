# JNI Example
JNI 静态注册、动态注册Java端代码都一样，差别主要体现在C/C++端
# JNI 静态注册
Java_com_vivek_wo_jni_JniExample_onJniExecute(JNIEnv *env, jobject thiz)

# JNI 动态注册
JNI动态注册 要使用JNI_OnLoad 映射JAVA和C/C++的方法
