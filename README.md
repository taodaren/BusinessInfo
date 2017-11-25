### 商家信息应用

---

![应用展示](https://github.com/taodaren/BusinessInfo/blob/master/img/business_info.png?raw=true)

### 知识点

---

#### Drawing to App
- step 1 Select the Views
`TextView` `ImageView` ...
- step 2 Style the Views
`color` `size` `text` ...
- step 3 Position the Views
`ViewGroup` `LinearLayout` `RelativeLayout` `Padding` `Margin` ...

### 扩展

---

`@+id/some_value` 与 `@id/some_value` 的区别：
- 对于 `@+id/some_value`：如果 R.java 中 没有 some_value 这个值，则在 R.java 中生成一个 some_value 值；如果有则直接使用已经存在的值
- 对于 `@id/some_value`：如果 R.java 中 没有 some_value 这个值，则使用此值；否则会造成编译错误

因此，`@+id` 与 `@id` 的区别就是：
- `@+id` 引用的值存在则使用，不存在则创建
- `@id` 只能引用 R.java 中已经存在的值，如果应用的值不存在则编译出错

[ConstraintLayout（约束布局）](https://developer.android.com/reference/android/support/constraint/ConstraintLayout.html)
[.ignore 插件](http://blog.csdn.net/qq_34590097/article/details/56284935)