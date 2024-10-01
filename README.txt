```markdown
# python-tools

`python-tools` 是一个包含多个图片处理命令行工具的 Python 项目。这些工具可以帮助你对图片进行去色、裁剪等操作。

## 功能

- **图片去色工具**：将彩色图片转换为灰度图片。
- **图片裁剪工具**：根据指定的尺寸裁剪图片。

## 安装

你可以通过以下步骤安装和使用这些命令行工具。

1. 克隆此仓库：

    ```bash
    git clone https://github.com/yourusername/python-tools.git
    cd python-tools
    ```

2. 安装依赖：

    ```bash
    pip install .
    ```

## 工具说明

### 1. 图片去色工具

#### 功能
将彩色图片转换为灰度图片。

#### 使用方法

```bash
python-tools grayscale --input <input_image> --output <output_image>
```

#### 示例

```bash
python-tools grayscale --input ./images/input.jpg --output ./images/output.jpg
```

参数说明：
- `--input`: 输入图片路径。
- `--output`: 输出灰度图片路径。

### 2. 图片裁剪工具

#### 功能
根据指定的宽度和高度裁剪图片。

#### 使用方法

```bash
python-tools crop --input <input_image> --output <output_image> --width <width> --height <height>
```

#### 示例

```bash
python-tools crop --input ./images/input.jpg --output ./images/output.jpg --width 200 --height 200
```

参数说明：
- `--input`: 输入图片路径。
- `--output`: 输出裁剪后图片的路径。
- `--width`: 裁剪后的宽度（单位：像素）。
- `--height`: 裁剪后的高度（单位：像素）。

## 贡献

欢迎提交 PR 以改进此项目，或者提出 issue 反馈问题。

## 许可证

此项目采用 MIT 许可证。详情请查看 [LICENSE](./LICENSE) 文件。
```
