# SharedPreferences 操作处理类
简化SharedPreferences的使用
API 简单好用、 支持加密保存
### 类名：SPUtils

| name        | void name           | direction  |
| ------------- | ------------- | :-----:|
| 保存数据      | put(Context context, String FILE_NAME, String key, Object object)  | |
| 获取对象 | Object get(Context context, String FILE_NAME, String key, Object defaultObject) |  |
| 移除某个key值已经对应的值 | remove(Context context, String FILE_NAME, String key)  |    |
| 清除所有数据 | clear(Context context, String FILE_NAME) |     |
| 查询某个key是否已经存在 | boolean contains(Context context, String FILE_NAME, String key) |     |
| 返回所有的键值对 | Map<String, ?> getAll(Context context, String FILE_NAME) |     |
| 加密保存 | saveEncode(Context context, String FILE_NAME, String key, String object) |     |
| 解密读取 | String getDecode(Context context, String FILE_NAME, String key)  |


#Contact me

E-mail:wenld2014@163.com

blog: [wenld's blog](http://blog.csdn.net/sinat_15877283)
