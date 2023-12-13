# Description

- Numpy的核心優勢：運算快。
    
    Numpy 利用電腦內存中連續的一塊物理地址存儲數據，因為都是連號的嘛，找到前後的號，不用跑很遠， 非常迅速。 
    
    Python 的 List 並不是連續儲存的，它的資料是分散在不同的實體空間，在批次運算的時候，連號的肯定比不連號的算起來更快。 因為找他們的時間更少了。
    
    Numpy Array 儲存的資料格式也有限制，盡量都是同一種資料格式，這樣也有利於大量的資料運算。 所以只要是處理大規模資料的批次計算，Numpy 肯定會比 Python 的原生 List 要快。

  [Compare the speed of numpy array and python list](https://github.com/eclairsameal/PythonDataProcessing/blob/main/Nnmpy/Basic/compare_speed_array_list.ipynb)

- Dimension - 維度
  
  Numpy 可以處理多維數據， 而且 Numpy 底層的 C 讓它在多維數據上計算也非常快。
