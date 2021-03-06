## Chapter 12、Takeaways: Setting up development and test sets

**小结：建立开发集和测试集**

- 从分布中选择开发集和测试集，该分布反映你期望在未来获得什么样的数据，并希望在上面做得很好。这可能和你训练数据的分布不一样。
- 如果可能的话，选择来自同一分布的开发集和测试集。
- 为你的团队选择单一数字的评估指标进行优化。如果你关心多个目标，考虑把它们合并到一个公式中（例如平均多个错误指标），或设定满足指标和优化指标。
- 机器学习是一个高度迭代的过程：在发现你满意的方法之前你可能需要尝试很多的idea。
- 开发/测试集和单一数字评估指标可以帮助你快速评估算法，从而迭代的更快。
- 当开始一个全新的应用时，尝试快速建立开发/测试集和评估指标，最好在一周之内。当然，在成熟应用上花费更长的时间是ok的。
- 当你拥有大量数据时，依据70%：30%的比例划分训练/测试集这一经验性的方法不太适用；开发/测试集可以占远小于30%的数据量。
- 你的开发集应该足够大，以检测出算法准确性有意义的改变，但没必要更大。你的测试集应该足够大，大到能对你的系统整体性能有一个确信的评估。
- 如果你的开发集和评估指标不再使你的团队在正确方向上前进，快速改变它们：（i）如果你过拟合了开发集，去获得更多的开发集数据。（ii）如果你所关心的实际分布和开发/测试集的分布不同，那么去获得新的开发/测试集数据。（iii）如果你的评估指标不再能衡量对你来说最重要的东西，改变评估指标。