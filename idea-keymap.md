#IDEA快捷键

##Editing

+	`Ctrl + Space`：自动完成名称(任意类名，方法名，变量名)注意系统输入法切换的快捷不要冲突。**(常用)**
+	`Ctrl + Shift + Space`：智能代码完成(所期望类型的变量和方法列表供选择)。**(常用)**
+	`Ctrl + Alt + Space`：类名自动完成，如果没有import会自动import(Project里的任意类名，包括jar包里)。
+	`Ctrl + Shift + Enter`：在末尾自动添加";"完成当前语句，很有用的一个快捷键。**(常用)**
+	`Ctrl + P`：提示当前调用方法的入参信息，当方法为重载方法时很有用。**(常用)**
+	`Ctrl + Q`：快速查看类、方法等的JavaDoc。**(常用)**
+	`Ctrl + mouse over code`：按住Ctrl键，然后鼠标移动到上面会显示信息摘要。**(常用)**
+	`Ctrl + F1`：在错误或者警告标志上显示说明。
+	`Alt + Insert`：代码自动生成(getter，setter，构造方法，hashCode等对象常用方法)。**(常用)**
+	`Ctrl + O`：重写(覆盖)方法。**(常用)**
+	`Ctrl + I`：实现方法。
+	`Ctrl + Alt + T`：调用代码模板。
+	`Ctrl + /`：行注释的启用和取消。
+	`Ctrl + Shift + /`：代码块注释的启用和取消。
+	`Ctrl + W`：递进式选择代码块。**(常用)**
+	`Ctrl + Shift + W`：返回上一次选择的代码块状态。
+	`Alt + Q`：上下文信息，如在类的任意地方按此快捷键查看类的定义。
+	`Alt + Enter`：显示可能的动作和快速修改的方式供选择。**(常用)**
+	`Ctrl + Alt + L`：代码格式化。**(常用)**
+	`Ctrl + Alt + O`：优化import导入，其实就是将每个类中导入的无效import去除。
+	`Ctrl + Alt + I`：自动缩进。
+	`Tab/Shift + Tab`：缩进/取消缩进选择的行。
+	`Ctrl + X or Shift + Delete`：剪切当前行或选定块到剪贴板。
+	`Ctrl + C or Ctrl + Insert`：复制当前行或选定块到剪贴板。
+	`Ctrl + V or Shift + Insert`：从剪贴板粘贴。
+	`Ctrl + Shift + V`：从剪贴板缓存中选择信息粘贴。**(常用)**
+	`Ctrl + D`：复制并粘贴当前行或选定块。
+	`Ctrl + Y`：删除当前行或选定块。
+	`Ctrl + Shift + J`：自动将下一行合并到当前行末尾。
+	`Ctrl + Enter`：智能分隔行。
+	`Shift + Enter`：开始新一行。
+	`Ctrl + Shift + U`：切换当前词或选定块的大小写。**(常用)**
+	`Ctrl + Shift + ]/[`：从当前光标选定到代码块结束/开始。(注：是代码块，不是代码行)
+	`Ctrl + Delete`：删除到当前词结尾。
+	`Ctrl + Backspace`：删除到当前词开头。
+	`Ctrl + NumPad+/-`：展开/折叠代码块。**(常用)**
+	`Ctrl + Shift + NumPad+`：展开所有。**(常用)**
+	`Ctrl + Shift + NumPad-`：折叠所有。**(常用)**
+	`Ctrl + F4`：关闭当前Tab页。**(常用)**
+	`Ctrl + Shift + Alt + F4`：关闭所有Tab页。(自定义)。**(常用)**

##Search/Replace

+	`Ctrl + F`：查找。**(常用)**
+	`F3`：查找下一个。**(常用)**
+	`Shift + F3`：查找上一个。**(常用)**
+	`Ctrl + R`：替换。**(常用)**
+	`Ctrl + Shift + F`：在指定路径查找。
+	`Ctrl + Shift + R`：在指定路径替换。
+	`Ctrl + Shift + S`：搜索结构(旗舰版才支持)，这里的结构可以是方法，代码模板等。
+	`Ctrl + Shift + M`：替换结构(旗舰版才支持)，这里的结构可以是方法，代码模板等。

##Usage Search 使用搜索

+	`Alt + F7 / Ctrl + F7`：搜索最近使用的地方/在文件中搜索使用的地方。
+	`Ctrl + Shift + F7`：高亮显示文件中使用的部分。
+	`Ctrl + Alt + F7`：显示使用的地方(可以显示方法、变量等在哪些地方被使用了)。

##Compile and Run

+	`Ctrl + F9`：项目构建(编译修改和相关)。
+	`Ctrl + Shift + F9`：编译选定的文件、包或模块。
+	`Alt + Shift + F10`：选择配置和运行(弹出窗口，选择要运行的项目，运行)。
+	`Alt + Shift + F9`：选择配置和调试(弹出窗口，选择要调试的项目，调试)。
+	`Shift + F10`：运行。
+	`Shift + F9`：调试。
+	`Ctrl + Shift + F10`：从编译器运行配置的上下文(运行选定的类或当前编译的类)。

##Debugging
+	`F8`：单步。
+	`F7`：步入。
+	`Shift + F7`：智能步入。
+	`Shift + F8`：跳出。
+	`Alt + F9`：运行到光标处。
+	`Alt + F8`：计算表达式。
+	`F9`：恢复程序运行。(到下一个断点)
+	`Ctrl + F8`：切换断点。
+	`Ctrl + Shift + F8`：查看断点。

##Navigation 导航

+	`Ctrl + N`：打开指定类。**(常用)**
+	`Ctrl + Shift + N`：打开指定文件。**(常用)**
+	`Ctrl + Alt + Shift +N`：前往指定的变量、方法。**(常用)**
+	`Alt + Right/Left`：转到下一个/上一个编辑器标签。**(常用)**
+	`F12`：回到前一个工具窗口。
+	`Esc`：进入编辑器(从工具窗口)。
+	`Shift + Esc`：隐藏当前或最后一个激活的工具窗口。**(常用)**
+	`Ctrl + Shift + F4`：关闭当前运行/消息/查找/...标签。
+	`Ctrl + G`：跳到指定行。
+	`Ctrl + E`：弹出最近查看过的文件。**(常用)**
+	`Ctrl + Alt + Left/Right`：跳到(前进/后退)光标编辑过的地方。**(常用)**
+	`Ctrl + Shift + Bachspace`：跳到最近一次编辑的位置。
+	`Alt + F1`：在任意视图弹出选择当前文件或者功能窗口。
+	`Ctrl + B or Ctrl + Click`：跳到类、方法、变量等的声明处。**(常用)**
+	`Ctrl + Alt + B`：跳到具体的实现方法，查找抽象方法的具体实现很好用。**(常用)**
+	`Ctrl + Shift + I`：快速查找定义。
+	`Ctrl + Shift + B`：前往类型声明。
+	`Ctrl + U`：前往父类方法/父类。
+	`Alt + Up/Down`：上一个/下一个方法。**(常用)**
+	`Ctrl + ]/[`：移动到代码块结束/开始。
+	`Ctrl + F12`：弹出文件结构，支持迅速查找当前类的变量、方法，可以使用模糊查询。**(常用)**
+	`Ctrl + H`：类层次结构。**(常用)**
+	`Ctrl + Shift + H`：方法层次结构。**(常用)**
+	`Ctrl + Alt + H`：调用层次。**(常用)**
+	`F2 / Shift + F2`：下一个/上一个高亮突出的错误。
+	`F4 / Ctrl + Enter`：编译源/查看源。
+	`Alt + Home`：显示导航栏。**(常用)**
+	`F11`：设定/取消书签。**(常用)**
+	`Ctrl + F11`：使用助记符设定/取消书签。**(常用)**
+	`Ctrl + Shift + 数字`：使用数字设定/取消书签。**(常用)**
+	`Ctrl + #[0-9]`：转到指定标号的书签。**(常用)**
+	`Shift + F11`：查看书签。**(常用)**

##Refactoring 重构

+	`F5`：文件复制。
+	`F6`：文件移动。
+	`Alt + Delete`：安全删除。
+	`Shift + F6`：改名。**(常用)**
+	`Ctrl + F6`：更改签名。
+	`Ctrl + Alt + N`：内联。
+	`Ctrl + Alt + M`：提取方法。**(常用)**
+	`Ctrl + Alt + V`：提取作为局部变量。
+	`Ctrl + Alt + F`：提取作为实例变量。
+	`Ctrl + Alt + C`：提取作为常量。
+	`Ctrl + Alt + P`：提取作为方法入参。

##VCS/Local History

+	`Ctrl + K`：提交项目。
+	`Ctrl + T`：更新项目。
+	`Alt + Shift + C`：查看最近的更改。

##Live Templates

+	`Ctrl + Alt + J`：弹出模板选择窗口，将选定的代码放入动态模板中。
+	`Ctrl + J`：插入动态模板。**(常用)**
+	`iter`：选择SDK1.5方式的迭代循环模板。
+	`inst`：instanceof模板。
+	`itco`：集合的循环迭代模板。
+	`itit`：迭代器的循环模板。
+	`itli`：list的循环模板。
+	`psf`：静态常量模板。
+	`thr`：抛出新异常模板(throw new)。
+	`psvm`：生成main方法。**(常用)**
+	`sout`：生成System.out.println()。**(常用)**

##General

+	`Alt + #[0-9]`：打开相应工具窗口。**(常用)**
+	`Ctrl + S`：全部保存。
+	`Ctrl + Alt + Y`：同步、刷新。
+	`Alt + F12`：切换全屏模式。(自定义)**(常用)**
+	`Ctrl + Shift + F12`：编辑器最大化。**(常用)**
+	`Alt + Shift + F`：添加到收藏夹。**(常用)**
+	`Alt + Shift + I`：查看项目当前文件。
+	`Ctrl + Alt + S`：打开IDE系统设置。**(常用)**
+	`Ctrl + Alt + Shift + S`：打开项目结构设置。**(常用)**
+	`Ctrl + Shift + A`：查找操作。**(常用)有点变态**
+	`Ctrl + Tab`：标签和工具窗口快速切换。**(常用)**
