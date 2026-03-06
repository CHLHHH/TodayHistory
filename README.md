
 #### 项目名称:  历史上的今天 
 ####   项目描述：一款面向历史爱好者的 Android 应用，用户可通过日期选择查看对应历史事件、黄历宜忌等信息，支持日期切换、历史事件详情浏览等功能，界面简洁美观，交互流畅。
  ####  项目重要技术点：
	1-采用 Kotlin 作为主开发语言，结合 Java 兼容库，熟练掌握 Kotlin 语法特性与 Android 开发流程   
	2-封装 BaseActivity 基类，统一页面生命周期与通用逻辑，提升代码复用性与可维护性   
	3-基于 OkHttp 进行网络请求，结合 Gson 解析 JSON 数据，实现历史事件与黄历信息的获取与展示  
	4-使用 RecyclerView + 自定义 Adapter 实现时间轴样式的历史事件列表，优化列表滚动性能
	5-集成 DatePickerDialog 实现日期选择器，支持切换任意日期并自动更新页面内容
	6-自定义数据类（HistoryBean、LaoHuangLiBean）封装接口返回数据，结合 SimpleDateFormat 处理日期格式化
	7-实现 Activity 间跳转与数据传递，支持从历史事件列表页跳转到详情页查看完整内容
	8-使用 Kotlin Android Extensions 简化视图绑定，提升开发效率
	9-优化图片加载与页面切换动画，提升用户体验与应用流畅度
 #### 效果图展示
 <img width="446" height="828" alt="image" src="https://github.com/user-attachments/assets/46a3e44c-dc7e-4732-8127-cdfa67ce2e58" />
 <img width="1920" height="1020" alt="d0601372ff849adcca5e116285e4c039" src="https://github.com/user-attachments/assets/f7195040-5f67-499c-b573-0d65b868b7f6" />
<img width="437" height="829" alt="88a8f272180cd1e9db988e5b5cc21157" src="https://github.com/user-attachments/assets/f9aacf2e-72e6-485a-a8f3-54de5f32812e" />
<img width="414" height="832" alt="8d5d8ea5d6710c9c62922d2b61adb666" src="https://github.com/user-attachments/assets/9c51e0cc-57be-4018-b788-3e189865b858" />
<img width="400" height="819" alt="488db1e322bcf87fffd81c6bdef3adc6" src="https://github.com/user-attachments/assets/9cb9120f-8750-480e-a180-ffac21a3c9d6" />
