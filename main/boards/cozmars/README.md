# 使用说明 


**编译**

```bash
python ./scripts/build.py cozmars --name cozmars
```

如需手动编译，打开 menuconfig 并配置 `Xiaozhi Assistant` → `Board Type` → 选择 `Cozmars robot`, 然后参考 `config.json` 修改 menuconfig 对应选项。

**烧录**

```bash
idf.py flash
```
