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
    
    - 文本域：多行输入文本的表单控件
      - textarea：双标签

  - label标签：网页中，某个标签的说明文本
    - 作用：为表单控件添加说明
    - 经验：用label标签绑定文字和表单控件的关系，增大表单控件的点击范围

    - 写法1
      - label标签只包裹内容，不包裹表单控件
      - 设置label标签的for属性值和表单控件的id属性值一致
        <input type="radio" id="man">
        <label for="man">男</label>

    - 写法2
      - 使用label标签包裹表单控件，不需要属性
      <label><input type="radio">女</label>

    提示：支持label标签增大点击范围的表单控件：文本框、密码框、上传文件、单选框、多选框、下拉菜单、文本域等等。

  - 按钮 button标签
    <button type="">按钮</button>

    type属性值：
    - button：普通按钮，默认没有功能，一般配合JavaScript使用
    - submit：提交按钮，点击后可以提交数据到后台（默认功能）
    - reset：重置按钮，点击后将表单控件的值重置为初始值

    - 无语义的布局标签
      作用：布局网页（划分网页区域，摆放内容）
      - div：块级布局标签，独占一行
      - span：行内布局标签,不换行

  - 字符实体
    作用：在网页中显示预留字符
    - 符号实体：&nbsp; 空格
      <div>123&nbsp;456</div>
    - 符号实体：&lt; 小于号 显示结果 <
    - 符号实体：&gt; 大于号 显示结果 >