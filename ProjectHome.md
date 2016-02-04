<br><br>　　该项目致力于完善PHP手册的中文翻译，并将该工作持久进行下去；<br>
我们还发布广大PHP爱好者喜闻乐见的<a href='http://code.google.com/p/phpdocs-cn-chm/'>PHP中文手册/英文手册（最新评论整合CHM版，2012年04月09日更新，点击前往下载）</a> 。<br />
参与该计划，无需签署锲约协议，无需长期时间支出，自愿自主自发参与，以帮助他人为乐趣，以奉献自己为追求。<br />
时间少，翻译一页即可，时间多，翻译多页或者章节更好，人多力量大，碎片化翻译，积沙成塔。<br />
当前参与状态，<a href='http://code.google.com/p/phpdoc-zh/wiki/GoinLlist'>猛击查看详细列表</a>、<a href='http://svn.php.net/viewvc/phpdoc/zh/trunk/?view=log'>狂点查看SVN日志</a>；首次提交PHP官方SVN特别纪念，<a href='http://svn.php.net/viewvc?view=revision&revision=302990'>猛击查看当日SVN日志</a>。<br>
<br>
<h1>PHP手册中文翻译补完计划参与方式（草稿）</h1>
<pre><code>　　〇、无障碍参与： https://edit.php.net/ <br>
<br>
    一、初级参与：直接翻译html页面 <br>
        你的工作：认领－翻译－提交 <br>
            1. 访问： http://docs.php.net/manual/zh/ <br>
            2. 在各级导航列表中中，纯英文标题的章节，一般就是尚未翻译的章节 <br>
            3. 查看自己熟悉和感兴趣的章节和页面，考虑是否翻译 <br>
            4. 如果决定翻译，请记录网址，并信件告知 honestqiao@gmail.com[暂定] ，以便统筹安排，避免重复劳动 <br>
                ××××××××信件格式×××××××× <br>
                标题：[PHPDOC-ZH] [认领] 章节或者页面英文名称-章节或者页面中文名称 <br>
                内容：章节或者页面网址，预计翻译的内容列表，预计翻译完成的时间 <br>
            5. 然后开始翻译另存的网页文件，在预计翻译完成的时间之前搞定，越快越好 <br>
            6. 翻译完成，发送邮件给 honestqiao@gmail.com[暂定] <br>
                ××××××××信件格式×××××××× <br>
                标题：[PHPDOC-ZH] [翻译] 章节或者页面英文名称-章节或者页面中文名称 <br>
                内容：章节或者页面网址，实际翻译的内容列表，实际翻译完成的时间，翻译结果附件 <br>
            7. 如精力许可，跟踪对应的英文页面，保持更新 <br>
             <br>
        我们的工作：确认－校对－发布  <br>
            1. 确认认领工作，预防重复劳动或建立对话合作劳动 <br>
            2. 翻译内容校对 <br>
            3. 组织为PHP官方手册所需的xml页面 <br>
            4. 编译生成CHM手册，并再次查看校对，确保所翻译页面正确无误 <br>
            5. 提交给PHP官方手册库，并在提交说明中署上翻译者基本个人信息 <br>
            6. 邮件反馈给翻译者 <br>
 <br>
    二、 中级参与：xml页面 <br>
        你的工作：认领－翻译－提交 <br>
            1. 未翻译xml页面列表： http://doc.php.net/php/zh/revcheck.php?p=missfiles <br>
            2. 使用SVN导出最新的英文和中文手册 <br>
                svn co http://svn.php.net/repository/phpdoc/en/trunk <br>
                svn co http://svn.php.net/repository/phpdoc/zh/trunk <br>
                或者使用SVN在线找到对应的xml文件：（在xml文件最终页" (download)"链接上鼠标右键另存） <br>
                http://svn.php.net/viewvc/phpdoc/en/ <br>
                http://svn.php.net/viewvc/phpdoc/zh/ <br>
            3. 参考“一、初级参与：直接翻译html页面”，查看自己熟悉和感兴趣的章节和页面，考虑是否翻译 <br>
            4. 如果决定翻译，请记录网址，并信件告知 honestqiao@gmail.com[暂定] ，以便统筹安排，避免重复劳动 <br>
                ××××××××信件格式×××××××× <br>
                标题：[PHPDOC-ZH] [认领] 章节或者页面英文名称-章节或者页面中文名称 <br>
                内容：章节或者页面网址，预计翻译的内容列表，预计翻译完成的时间，翻译者个人资料 <br>
            5. 然后开始翻译对应的xml文件，在预计翻译完成的时间之前搞定，越快越好 <br>
            6. 翻译完成，发送邮件给 honestqiao@gmail.com[暂定] <br>
                ××××××××信件格式×××××××× <br>
                标题：[PHPDOC-ZH] [翻译] 章节或者页面英文名称-章节或者页面中文名称 <br>
                内容：章节或者页面网址，实际翻译的内容列表，实际翻译完成的时间，翻译结果附件，翻译者个人资料 <br>
            7. 如精力许可，跟踪对应的英文页面，保持更新 <br>
 <br>
        我们的工作：确认－校对－发布 <br>
            1. 确认认领工作，预防重复劳动或建立对话合作劳动 <br>
            2. 翻译内容校对 <br>
            3. 检查是否为PHP官方手册所需的xml页面 <br>
            4. 编译生成CHM手册，并再次查看校对，确保所翻译页面正确无误 <br>
            5. 提交给PHP官方手册库，并在提交说明中署上翻译者基本个人信息 <br>
            6. 邮件反馈给翻译者 <br>
 <br>
 <br>
    三、高级参与：svn操作 <br>
        你的工作：认领－翻译－提交 <br>
            1. 如需翻译html页面，参考“一、初级参与：直接翻译html页面”；<br>
               如需翻译xml页面，“二、 中级参与：xml页面”，完成认领 <br>
            2. 申请 http://code.google.com/p/phpdoc-zh/ 项目的SVN操作权限，并导出最新翻译成果 <br>
                svn checkout https://phpdoc-zh.googlecode.com/svn/trunk/ phpdoc-zh --username 用户名 <br>
            3. 翻译html页面或者xml页面 <br>
            4. 提交文件到html或者xml，提交时，注意留下翻译说明信息，以及，翻译者个人资料 <br>
                ××××××××说明格式×××××××× <br>
                标题：[PHPDOC-ZH] [翻译] 章节或者页面英文名称-章节或者页面中文名称 <br>
                内容：章节或者页面网址，实际翻译的内容列表，实际翻译完成的时间，翻译者个人资料 <br>
 <br>
        我们的工作：确认－校对－发布  <br>
            1. 确认认领工作，预防重复劳动或建立对话合作劳动 <br>
            2. 翻译内容校对 <br>
            3. 检查是否为PHP官方手册所需的xml页面 <br>
            4. 编译生成CHM手册，并再次查看校对，确保所翻译页面正确无误 <br>
            5. 提交给PHP官方手册库，并在提交说明中署上翻译者基本个人信息 <br>
            6. 邮件反馈给翻译者 <br>
 <br>
    其他说明： <br>
        1. 尚未翻译xml页面列表： http://code.google.com/p/phpdoc-zh/downloads/detail?name=revcheck.html<br>
        2. 认领和翻译，将在： http://code.google.com/p/phpdoc-zh/w/list 列出 <br>
        3. 将根据最新翻译成果，制作为最新CHM手册（带评论）并大力推广 <br>
        4. 翻译人员交流QQ群：50360909，认领页面后可申请加入 <br>
        5. 欲参与翻译，请与 honestqiao@gmail.com[暂定] 或者 QQ/5601680[暂定] 联系。<br>
        6. 本项目的SVN权限，仅用于在本项目中提交翻译后的文件；html页面直接提交到html/下面即可，xml页面需要按照官方svn的en手册目录结构提交。<br>
        7. 翻译时，对于拿捏不准的词汇，可以参考机器翻译结果，但是不得直接采用，更不可为了翻译而翻译！！！<br>
           http://www.jollo.com/可同时提供多个在线翻译站点的翻译结果，进行对比查看。<br>
</code></pre>