# Scipy_intro

> 斯坦福 Scipy 快速入门[教程](https://cs231n.github.io/python-numpy-tutorial/#numpy) | [官方教程](https://docs.scipy.org/doc/scipy/reference/index.html)

## 0.说明

参考官方文档：[misc](https://docs.scipy.org/doc/scipy/reference/misc.html)

`scipy.misc`：在 scipy=1.10.0 版本被抛弃，在 version=2.0.0 版本会完全移除。

### 0.1 imageio

替代方法之一：使用 `imageio` 包 | [官网地址](https://imageio.readthedocs.io/en/stable/)

安装：`pip install imageio`

```python
import imageio.v3 as iio
dir(imageio) #可以看出 imageio 包内容较少，主要有 imread,imwrite,imsave
```

## 1.操作 matlabfiles

借助  `scipy.io.loadmat` and `scipy.io.savemat` 完成，具体操作见：[matlabfiles](https://docs.scipy.org/doc/scipy/reference/io.html)