<p align="center">
  🌐 <a href="README.md">Português</a> · <a href="README.en.md">English</a> · <a href="README.es.md">Español</a> · <b>中文</b> · <a href="README.hi.md">हिन्दी</a> · <a href="README.ar.md">العربية</a> · <a href="README.fr.md">Français</a> · <a href="README.bn.md">বাংলা</a> · <a href="README.ru.md">Русский</a> · <a href="README.ur.md">اردو</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a>
</p>

<p align="center">
  <img src="docs/social-preview.png" alt="CedPrinter" width="900">
</p>

<h3 align="center">设计并打印 Zebra 标签，没有广告。</h3>

<p align="center">
  可视化设计器 · 批量打印 · Pix 二维码 · 255 个图标 · 现成模板 · 支持 Windows 和 Android
</p>

<p align="center">
  <a href="https://github.com/arthurbrito-pjt/CedPrinter-releases/releases/latest"><img alt="下载最新版本" src="https://img.shields.io/github/v/release/arthurbrito-pjt/CedPrinter-releases?label=%C3%BAltima%20vers%C3%A3o&style=for-the-badge&color=DB2F01"></a>
  <img alt="下载量" src="https://img.shields.io/github/downloads/arthurbrito-pjt/CedPrinter-releases/total?style=for-the-badge&color=00113B&label=downloads">
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%2F%2011-00113B?style=for-the-badge&logo=windows&logoColor=white">
  <img alt="Android" src="https://img.shields.io/badge/Android-8.0%2B-00113B?style=for-the-badge&logo=android&logoColor=white">
  <img alt="语言" src="https://img.shields.io/badge/idioma-portugu%C3%AAs%20(BR)-DB2F01?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/arthurbrito-pjt/CedPrinter-releases/releases/latest"><b>⬇️ 下载 CedPrinter</b></a>
</p>

<p align="center">
  <img src="docs/screenshots/02-designer-envio.png" alt="CedPrinter 设计器" width="900">
</p>

---

## 简介

**CedPrinter** 是一款用于**设计并打印 Zebra（ZPL）标签**的应用，专为 **Cedisa Central de Aço** 打造，同时向所有人开放。它完全免费、**没有广告**。源代码为私有；这里提供安装程序和已发布的各个版本。

它会按照**您所用标签纸的精确尺寸**生成标签并直接发送到打印机，因此标签的大小和位置始终准确无误。

## 效果展示

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/01-inicio.png" alt="主页"><br><sub><b>主页：</b>快捷入口、现成模板和最近打印记录。</sub></td>
    <td width="50%"><img src="docs/screenshots/04-modelos.png" alt="现成模板"><br><sub><b>现成模板：</b>发货、货量、有效期、价格、Pix 等。</sub></td>
  </tr>
  <tr>
    <td><img src="docs/screenshots/03-icones.png" alt="图标"><br><sub><b>255 个图标</b>，支持搜索。</sub></td>
    <td><img src="docs/screenshots/05-qr-pix.png" alt="Pix 二维码"><br><sub><b>二维码向导：</b>Pix、Wi-Fi、链接、WhatsApp 和联系人。</sub></td>
  </tr>
  <tr>
    <td><img src="docs/screenshots/06-previa-1bit.png" alt="1 位预览"><br><sub><b>1 位预览：</b>提前看到 Zebra 的实际打印效果。</sub></td>
    <td><img src="docs/screenshots/07-escuro.png" alt="深色主题"><br><sub><b>浅色和深色主题</b>，以及强调色。</sub></td>
  </tr>
</table>

## 功能亮点

- **可视化设计器：**文本、条形码（Code 128、Code 39、EAN-13/8、UPC-A、ITF）、二维码、Data Matrix、PDF417、图片、图标、形状和线条。
- **真正的编辑体验：**多选、对齐与分布、参考线、图层、复制/粘贴、撤销/重做。
- **批量打印：**导入表格（Excel/CSV），每行打印一张标签，并支持序列号。
- **日期自动计算：**用 `{_data+30}` 计算有效期，支持多种格式。
- **二维码向导：**Pix、Wi-Fi、链接、联系人、WhatsApp、电子邮件、短信和地图。打印前还会**校验**条码。
- **PDF 和图片：**按实际尺寸打印，或导入设计器进行编辑。
- **现成模板**和自己的模板库、历史记录以及快速标签。
- **直接打印（ZPL）：**通过网络（IP）、USB/Windows、Wi-Fi、蓝牙和 USB（Android）。
- **自动更新**，并显示更新内容。

## 下载

**➡️ [打开最新版本](https://github.com/arthurbrito-pjt/CedPrinter-releases/releases/latest)**，然后从 **Assets** 列表中下载文件：

| 文件 | 用途 |
|---|---|
| `CedPrinter-Setup-X.exe` | **Windows 安装程序**（推荐）。可自动更新。 |
| `CedPrinter-PC-X.zip` | Windows 便携版，无需安装。不会自动更新。 |
| `CedPrinter-X.apk` | **Android 应用**（手机和手持终端）。 |

> `latest.yml` 是内部更新文件：无需下载。

## 安装

### 🖥️ Windows

1. 下载 `CedPrinter-Setup-X.exe` 并打开。
2. 如果 Windows 提示"Windows 已保护你的电脑"，请点击**更多信息 → 仍要运行**（安装程序目前尚无代码签名）。
3. 按照向导操作，然后点击**安装**。
4. 首次使用时，点击屏幕顶部的打印机按钮，选择您的 Zebra 打印机。

### 📱 Android

1. 在设备上下载 `CedPrinter-X.apk` 并打开该文件。
2. 如果 Android 提示，请允许所用浏览器或文件管理器**安装未知应用**。
3. 打开 CedPrinter，进入**打印机**，选择您的 Zebra（Wi-Fi、蓝牙或 USB）。

## 常见问题

**支持哪些打印机？** 支持**使用 ZPL 的 Zebra 打印机**（参考机型：ZD230，203 dpi），可通过网络、USB 或蓝牙连接。不兼容其他品牌。

**需要联网吗？** 仅在下载应用和更新时需要。打印和设计标签可以离线完成。

**应用会收集我的数据吗？** 不会。您的模板、历史记录和设置都保存在您自己的电脑上。应用只会访问 GitHub 来检查是否有新版本。

**免费吗？** 是的，个人和商业用途均可。请查看[使用条款](LICENSE)（葡萄牙语）。

**我发现了问题，或者有好点子。** 请提交一个 [issue](https://github.com/arthurbrito-pjt/CedPrinter-releases/issues/new/choose)，并注明版本号，如果可以的话，也请注明打印机型号。

## 版本历史

每个版本的更新内容请查看 [Releases](https://github.com/arthurbrito-pjt/CedPrinter-releases/releases)。

---

<p align="center">
  由 <b>Arthur Brito - Projetos</b> 开发 · 为 Cedisa Central de Aço 打造<br>
  <a href="https://github.com/arthurbrito-pjt">github.com/arthurbrito-pjt</a>
</p>
