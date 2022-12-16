# مقدمة

*هياكل البيانات وجلب المعلومات في بيثون* عبارة عن مقدمة للخوارزميات وهياكل البيانات باستخدام محركات بحث الويب كمثال محفز.

وهو يعتمد جزئيا علي *[ التفكير بهياكل البيانات Think Data Structures](https://greenteapress.com/wp/think-data-structures/)*، والذي استخدم بلغة جافا.

عناصر محرك البحث هي:

* الزاحف The Crawler، ويقوم بتنزيل صفحات الويب وتتبع الروابط للصفحات الاخري،

* المفهرس The Indexer، يبني خريطة بين كل مصطلح بحث والصفحة التي يظهر فيها،

* المسترد The Retriever، وهو الذي يبحث عن الكلمات ويجد افضل الصفحات المرتبطة بها،

يخزن الفهرس في ردس Redis، وهو مخزن بيانات يوفر هياكل كالمجوعات واللوائح ومخطط التشفير hashmaps. يقدم الكتاب كل هيكل بياني اولا بلغة بيثون، ثم بلغة ردس، وهو ما سيساعد القاريء علي التمييز بين السمات الاساسية وتفاصيل التضمين.


كما فعلت في [*التفكير ببايز Think Bayes*](https://greenteapress.com/wp/think-bayes/)، فقد كتبت كامل هذا الكتاب في دفتر جوبتر، واستخدمت JupyterBook لتحويله الي HTML. يمكن تشغيل الدفاتر في كولاب Colab، وهي خدمة مقدمة من قوقل تشغل الدفتر في المتصفح مباشرة. وهو ما سيساعدك علي قراءة الكتاب وتشغيل الاكواد، والعمل علي التمارين دون تثبيت اي شيء علي حاسبك.

هذه المواد ما زالت تحت التطوير، لذا نرحب باي تعليقات. وافضل طريقة للقيام بذلك هي  [ بالنقر هنا وانشاء مشكلة في جيت هب](https://github.com/AllenDowney/DSIRP/issues).

[شرائح الاستعراض](https://docs.google.com/presentation/d/e/2PACX-1vRFFocqlEH4YAbi8_xgZhfx9cvHFdMkhx_-yQ2aVVqc5quUQlm_mhuu7XoE9UOARsvwDe9X0kcA2DqS/pub)


## الدفاتر notebooks

انقر علي الروابط ادناه لتشغيل الدفاتر علي كولاب.

* الخوارزميات: نشاط اول يوم التحقق من الجناس الناقص anagrams وايجاد مجموعات الجناس الناقص
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/algorithms.ipynb)

* التحليل: مقدمة لتحليل الخوارزميات وتمثيل O الكبيرة Big O notation.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQXYlOUlPPTE9GGR3UBugxYT8n_TcIGR5ttG7Rz_aA8lAFLTCeYUC1HFnQyDQBKPOv6PC7_PQ5Q-xz6/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/analysis.ipynb)

* التوقيت: التحقق من السلوك المقارب asymptotic عن طريق قياس وقت التشغيل.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/timing.ipynb)

* سؤال 01  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz01.ipynb)

* وظائف المولد: فصل التكرار عن منطق البرنامج
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vTOxX01R5LNdEZDqSkiG5YOlJQieAO2bePigUnz6Fx5fiJqTMtpoOzn0ltpaeuWbfLl74vz6YqWUmZK/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/generator.ipynb)

* المجموعة: استخدام مجموعات Python للغش في ألعاب الكلمات.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/set.ipynb)

* العودية Recursion: ممارسة الوظائف العودية.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/recursion.ipynb)

* [سؤال02](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz02.ipynb)

* البحث بالتعمق اولا Depth First Search: اجتياز الشجرة في BeautifulSoup
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vTQzIt8u_vdwhqeFjPIHUNDFlO0_2-GId567gTbSCtyfQM0nRWjlxbklUhWTGl4KDzVI4_JxcfYRfEa/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/dfs.ipynb)

* البحث: البحث الخطي ، والتقطيع bisection، وأشجار البحث الثنائية.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQItNQPqCoUITZggi-ML-OYZtecevxcsPVvbP1JvW55erx2tXaO3cibTrWE5E8myJ4wqRPLt7xby7ei/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/searching.ipynb)

* مخطط التشفير Hashmap: كيف تعمل أعظم هياكل البيانات.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQXOQd5jpi4eHfIg9iqPCOSLVFEnaAvAiFhBAGZECl0wZ2XKJdbMSnGZsym8CvVq-IsxvvKu1tB7e2L/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/hashmap.ipynb)

* [سؤال03](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz03.ipynb)

* الكومة Heap: هل هي مصفوفة ، هل هي شجرة ، ام صف باولوية PriorityQueue!
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQTHKlq7pvrOCgqgPhLodGUtrcA3sFGco4r8O041WvmKLi-JFDfUPpb4X6txEn1qe2RR_xBfvXlXtSD/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/heap.ipynb)

* كود هوفمان: استخدم الهياكل التي تعلمناها لإنشاء كود مبدئي مثالي.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQjk8Ko3u59qdandz-R_KfmQiHc2oIBk5RcJlWMXubdIMDxYuZpVHqn26jLylm0_eMf_ZJ-rOgnBjpi/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/huffman.ipynb)

* الوصول إلى الفلسفة: اتبع روابط ويكيبيديا حتى تصل إلى الفلسفة.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQKVxHQKnp4LoiDipCvMh6GFRhgdiNFG_fqJ6vOfFb-ai9S1jLLbFvR1Qp4ocaAMNGL2FSaUd3-3H62/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/philosophy.ipynb)

* [سؤال04](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz04.ipynb)

* ردس Redis: مقدمة مخزن البيانات ردس.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/redis.ipynb)

* اللوائح المترابطة Linked List: ايهما اول الشجرة أم اللائحة؟ غريب لكن صحيح.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vRSKmupEcVRXzH4jj31Zk5To6PrmIej58HviUrbN0a7wKTKBZwdoVHcGSFKvWac-L1w3Js9R6eD33fn/pub)
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/linked_list.ipynb)

* المفهرس Indexer: انشاء مخطط الانترنت لتسريع البحث.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/indexer.ipynb)

* [سؤال05](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz05.ipynb)

* الصفيف Deque: مثل القائمة المترابطة ، ولكن أكثر من ذلك.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/deque.ipynb)

* المخطط Graphs: تمثيل المخططات باستخدام NetworkX.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/graph.ipynb)

* بحث بترتيب المستوى: استخدم الوحدة النمطية `os` لاجتياز نظام الملفات.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQT31xIq3pY-JF9J2RezS-i3528RM-NSpa67PN3wjfNF_6T0uUw_pV253lFKCB7pc_zXsnglXKOU2Pw/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/level_order.ipynb)

* البحث بالتوسع اولا Breadth-First Search: اساسيات الخوارزميات الرسومية graph algorithms.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vRXakv4ZkGq648UwqRCXUkmqUFwGx4kJ4OskY6F9_busCH2aXPjZKKsQhGP4ESdJJNDq8bJowB9zLJb/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/bfs.ipynb)

* [سؤال06](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz06.ipynb)

* الزاحف Crawler: تتبع الروابط وبحث الانترنت بالتوسع اولا.
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/crawler.ipynb)

* ترتيب الدمج Mergesort: فرق تسد، والدمج في الزمن الخطي.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vQbgVZohGR3tSm7LtnYVravKt_za_70Egy4hQwpGeLsjvhfmG16QfBjhph991EsIWsrfyABsRMmMAMk/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/mergesort.ipynb)

* تحويل فورييه السريع: يشبه فرز الدمج ، لكن بأرقام مركبة.
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vRuShFoETvJiCPAiM1xbxDBIM6MaXh2kMpjYB3FvRB4xzYsfi3vgZYgoQbxtGq8ODLjC8qhwn17f2_V/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/fft.ipynb)

* [سؤال07](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/quiz07.ipynb)

* رتب الصفحات PageRank: مسارات عشوائية Random walks ومصفوفات متجاورة adjacency matrices ومتجهات ذاتية eigenvectors! 
[الشرائح](https://docs.google.com/presentation/d/e/2PACX-1vTXdmLq-KdIVsm9dQVPUi5skj-hLDlYHuxMLmDimtvBF_qs1ZyRA6gy5SgsdINLf1baWppl6SsFL6OD/pub)  
[الدفتر](https://colab.research.google.com/github/AllenDowney/DSIRP/blob/main/notebooks/pagerank.ipynb)




الحقوق محفوظة 2021 Allen B. Downey

الرخصة: [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
