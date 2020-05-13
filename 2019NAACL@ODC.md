**Title**: Online Distilling from Checkpoints for Neural Machine Translation

**Abstract**:
> Current predominant neural machine translation (NMT) models often have a deep
> strcuture with large amounts of paramters, making these models hard to train and
> easily suffering from over-fitting. A common practice is to utilize a validation
> set to evaluate the training process and select the best checkpoint. Average and
> ensemble techniques on checkpoints can lead to further performance improvement.
> However, as these methods do not affect the training process, the system performance
> is restricted to the checkpoints generated in original training procedure. In contrast,
> we propose an online knowledge distillation method. Our method on-the-fly generates a
> teacher model from checkpoints, guiding the training process to obtain better performance.
> Experiments on several datasets and language pairs show steady improvement over a strong
> self-attention-based baseline system. We also provide analysis on data-limited setting
> against over-fitting. Furthermore, our method leads to an improvement in a machine
> reading experiment as well.

**URL**: https://www.aclweb.org/anthology/N19-1192/

**Wiki**: TODO

**Note**: Feel free to open issues if you have any questions. :)
