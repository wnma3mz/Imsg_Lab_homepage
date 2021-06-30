## Intelligent Multimedia Security Group 实验室主页

主页：<https://imsg.ac.cn/>

### 说明：

1. 为加速静态资源访问，图片最好使用webp格式。开借助相关工具（xnconver）将png、jpg等格式转换为webp
2. [Publication](<https://imsg.ac.cn/publication.html>)中BibTex点击可直接展开信息，方便LaTex写作时导入
3. people目录下是各成员的人员主页
4. research目录各专题的项目主页
5. img目录下按照主页、成员、论文、专题分类存储

### TO-DO

1. [Information](<https://imsg.ac.cn/info.html>)页面增加会议的DDL及期刊主页


### 注

1. [Publication](<https://imsg.ac.cn/publication.html>)页面期刊格式如下：

   IEEE Transactions on Image Processing, 2020, 29(x): 2610-2621.

   顺序：1. 作者; 2. 标题; 3. 期刊/会议 （方便后续复制粘贴）

   修改说明：
   ```html
         <div class="paper">
            <img height="110px" width="210px" src="图片链接">
            <div class="pauthors">作者.</div>
            <div class="ptitle">文章标题.
            </div>
            <div class="pvenue">会议/期刊.</div>
            <div class="plink">
              <a href="pdf本地链接" target="_blank">[PDF]</a>
              <a href="对应的project，若无则删除该行">[Project]</a>
              <a href="论文发表的会议/期刊链接" target="_blank">[DOI]</a>
              <a onclick="display('bib信息的第一行')" style="color: #1c3ed3">[Bib] </a>
              <div style="display: none;" class="BibtexExpand" id="bib信息的第一行">
                <pre class="bibtex">
                  bib信息
                </pre>
              </div>
            </div>
         </div>
   ```

2. 文字注意两端对齐

3. 日期格式yyyy-mm-dd

4. 尽量避免使用中文数字（一、二、三），替换为阿拉伯数字（1、2、3）

5. 轮播图长宽比尽量接近（1425:500）
