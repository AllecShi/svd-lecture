# SVD 交互讲义

数据科学通识导论（12004100-03）

奇异值分解（SVD）的中文交互讲义：定义与结构、几何意义、2×3 手算、图像低秩近似、句向量语义分类、小结与自测，共六节、五个可动手的实验。

**在线阅读：** https://allecshi.github.io/svd-lecture/

- 单文件页面：`SVD交互讲义.html`，下载后双击即可离线阅读（数学字体已内嵌；中文字体首次需联网）。
- 实验 01–04 在浏览器中实时计算。
- 实验 05 用 bge-m3 句向量 + SVD 投影给请假理由分类：语料为脚本合成的 2772 条句子，SVD 与类中心用 NumPy 离线计算后内嵌在页面里，41 条样例句随处可点；输入新句子需要本机运行编码服务（`127.0.0.1:8787`，转发到 Ollama 的 bge-m3）。

## 第三方素材与授权

- 公式排版：[KaTeX](https://katex.org/) 0.16.11，MIT 许可，脚本与字体已内联。
- 句向量模型：[BAAI/bge-m3](https://huggingface.co/BAAI/bge-m3)，MIT 许可。
- “黄昏教学楼”：[Art Building Dusk](https://commons.wikimedia.org/wiki/File:Art_Building_Dusk-_(17289797303).jpg)，Texas A&M University-Commerce Marketing Communications Photography，[CC BY 2.0](https://creativecommons.org/licenses/by/2.0)。已裁切、缩放并灰度化。
- “红砖立面”：[Goldstein Alumni and Faculty Center at Syracuse University 01](https://commons.wikimedia.org/wiki/File:Goldstein_Alumni_and_Faculty_Center_at_Syracuse_University_01.jpg)，Kiran891，[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)。已裁切、缩放并灰度化，修改后的图像同样按 CC BY-SA 4.0 提供。
