如果要使用于中文半监督分类，需要增加bert-base-chinese相关，因此需要修改以下文件：

- semilearn/datasets/collactors/nlp_collactor.py
- semilearn/datasets/collactors/__init__.py
- semilearn/nets/bert/bert.py
- semilearn/nets/bert/__init__.py
- semilearn/nets/__init__.py
