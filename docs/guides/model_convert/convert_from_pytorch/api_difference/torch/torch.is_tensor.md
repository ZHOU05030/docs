## [ 仅参数名不一致 ]torch.is_tensor

### [torch.is_tensor](https://pytorch.org/docs/stable/generated/torch.is_tensor.html?highlight=is_tensor#torch.is_tensor)

```python
torch.is_tensor(obj)
```

### [paddle.is_tensor](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/is_tensor_cn.html#is-tensor)

```python
paddle.is_tensor(x)
```

两者功能一致且参数用法一致，仅参数名不一致，具体如下：

### 参数映射

| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| <font color='red'> obj </font> | <font color='red'> x </font> | 输⼊ Tensor ，被判断的 Tensor ，仅参数名不一致。   |