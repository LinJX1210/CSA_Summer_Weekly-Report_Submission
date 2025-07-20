# CSA_Summer_Weekly-Report_Submission



HAUST-CSA-Lab Weekly Report Submission Office

## 周报提交指北

### 提交流程：

1. 克隆仓库到本地

   a. **创建ssh key，用于ssh方式克隆github代码。** （如果未配置过）在电脑上合适的位置新建一个文件夹，在文件夹下打开终端使用`ssh-keygen -t rsa -b 4096 -C "你的邮箱"`（把“你的邮箱”替换成）命令，创建ssh key，下面的选项全部直接敲回车即可。 随后使用 `cat ~/.ssh/id_rsa.pub` 命令查看生成的公钥，并完整的复制下来。 在github仓库界面点击自己的头像，选择 settings 。进入到设置页面后，点击左侧的 SSH and GPG keys 选项。点击 New SSH key 选项，并将复制下来的内容粘贴上去，添加该 ssh key 的描述。随后点击 Add SSH key ，并一路点击确认即可

 b. **点击醒目的绿色`code`按钮，选择ssh，复制链接** 并在终端运行命令 `git clone "链接"` 即可。

1. 把周报的文件放到克隆下来的目录中
2. （假如你是第一次使用）运行`git config --global user.email "you@example.com"`和`git config --global user.name "Your Name"`命令。（分别是你创建github账号使用的邮箱和你的github名字）
3. 在仓库的根目录（Weekly_Report-yourname）下运行 `git add .;` `git commit -m "班级+姓名+第x周周报";` `git push`命令，即可完成提交。

### 具体内容：

周报的格式不作要求，清楚说明内容即可。尽量不要出现背书内容（指复制资料/ai助手的大段文字），但也不要过于简洁。

周报可以包含理论知识（如计网，或者某门编程语言等）和技术实践（如漏洞复现，跟做实验或ctf题目wp等），但不限于以上。可以把任何自己觉得恰当的内容放进去。

距开学还有五周时间，组员提交周报的次数应大于等于四篇。同时应对于自己在暑假学习的内容有系统性认知，可以在开学的第一个周末进行概述性分享。同时，开学后原则上每周应有一位组员进行时长约为一节课的技术讲解，具体安排后续会发在群中，大家可以提前做准备。

对于暑期学习不够积极的组员，经和老师的商定后，会做清退处理。以上内容的提交截止到9月2日0：00。

期待大家学有所得。