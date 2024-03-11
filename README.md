# online softmax
[online_softmax.py](online_softmax.py) softmax的naive实现和online版本实现，作为flash attention的基础。包含标准softmax，online softmax和tiling softmax 3种版本的 实现。其中online softmax可看做tiling n_split=1的特殊情况

# flash attention
[flash_attn.py](flash_attn.py) flash attention的pytorch实习。原出处已经找不到了
