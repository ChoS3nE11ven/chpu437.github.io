# 样式目录文件结构
- `css/main.scss`
  - Jekyll 在编译时实际读取的文件
  - **不要直接修改**

- `_sass/bootstrap/`和`_sass/_bootstrap.scss`
  - 基础的样式，相当于“毛坯房”
  - **不要直接修改**

- `_sass/seu-custom/`
  - 自定义样式目录
  - **请在这里添加或修改样式**

- `_sass/seu-custom/_netsi-inherited.scss`
  - 引入继承自 Netsi 的样式
  - **请不要修改此文件**

- `_sass/seu-custom/_variables.scss`
  - 自定义变量目录
  - **请在这里添加或修改变量**

- `_sass/_seu-custom.scss`
  - 引入自定义样式和变量，具体请参考文件内的注释
  - 当你在 `_sass/seu-custom/` 中添加或修改样式时，请确保在这里引入