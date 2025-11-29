- 表单
 - 作用：收集用户信息
 - 使用场景：
   - 登录页面
   - 注册页面
   - 搜索区域
   - 留言区域
   - 评论区域

  - input标签基本使用
    - type属性值：
      - text：文本输入框，用于输入单行文本
      - password：密码输入框
      - radio：单选框
      - checkbox：复选框
      - file：文件上传框
      - button：按钮
      - submit：提交按钮
      - reset：重置按钮--
      - hidden：隐藏域

    - 附加属性值
      - placeholder：input标签占位文本：提示信息

    - 单选框radio
      - 常用属性：
        - 属性名：name 作用：控件名称 特殊说明：控件分组，同组只能选中一个（单选功能）
        - 属性名：checked 作用：默认选中  特殊说明：属性名和属性值相同，简写为一个单词 

    - 上传文件file：默认情况下，文件上传表单控件只能上传一个文件，添加multiple属性可以实现文件多选功能
      <input type="file" multiple>

    - 复选框（多选框）
      - 使用场景：注册账户中是否同意协议、兴趣爱好等
      - 默认选中：checked

    - 下拉菜单：select嵌套option,select是下拉菜单整体，option是下拉菜单选项
      - <select>标签：下拉菜单标签
      - <option>标签：下拉菜单选项标签
      - <optgroup>标签：下拉菜单分组标签
      - <select>标签的属性值：
        - name：下拉菜单名称
        - multiple：多选
        - size：显示的行数
        - selected：默认选中
        - disabled：禁用
        - required：必填
        - autofocus：自动获取焦点
        - form：指定表单
        - label：指定标签的标题
        - value：指定选项的值
        - data-*：自定义属性
        - id：指定选项的id
        - class：指定选项的class
        - style：指定选项的样式
        - title：指定选项的提示信息
        - onclick：指定选项的点击事件
        - onchange：指定选项的change事件
        - onmouseover：指定选项的鼠标移入事件
        - onmouseout：指定选项的鼠标移出事件
        - onmousemove：指定选项的鼠标移动事件
        - onmousedown：指定选项的鼠标按下事件
