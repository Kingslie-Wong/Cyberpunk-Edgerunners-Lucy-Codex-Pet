# Cyberpunk Edgerunners Lucy Codex Pet

English | [中文](#中文)

An animated Codex pet inspired by Lucy's cyberpunk outfit design.

The package includes a transparent animated spritesheet and `pet.json` metadata for Codex-compatible pet loading.

## Install from Petdex

Lucy is available on Petdex:

[https://petdex.crafter.run/pets/lucy](https://petdex.crafter.run/pets/lucy)

Install it with one command:

```bash
npx petdex install lucy
```

This drops the pet package into `~/.codex/pets/lucy/`. To activate it in Codex, open Settings -> Appearance -> Pets and select Lucy.

## Manual Download

Download the ready-to-use package:

[dist/lucy-codex-pet.zip](dist/lucy-codex-pet.zip)

After downloading, unzip it. The archive contains a `lucy` folder with:

- `pet.json`
- `spritesheet.webp`

Use that unzipped `lucy` folder as the pet package.

## Preview

![Lucy pet contact sheet](docs/contact-sheet.png)

![Idle animation](docs/previews/idle.gif)

## Included Files

- `pets/lucy/pet.json` - pet metadata
- `pets/lucy/spritesheet.webp` - final animated spritesheet
- `docs/contact-sheet.png` - QA contact sheet showing all animation rows
- `docs/previews/idle.gif` - sample animation preview
- `dist/lucy-codex-pet.zip` - direct download package

## Animation Rows

The spritesheet uses a fixed 8 column x 9 row layout:

| Row | State |
|---:|---|
| 0 | idle |
| 1 | running-right |
| 2 | running-left |
| 3 | waving |
| 4 | jumping |
| 5 | failed |
| 6 | waiting |
| 7 | running |
| 8 | review |

## Validation

The final spritesheet was validated at `1536 x 1872` pixels with transparent unused cells and no validation errors.

## Notes

This is fan-made character artwork packaged as a Codex pet. It is intended for personal and portfolio use.

---

## 中文

[English](#cyberpunk-edgerunners-lucy-codex-pet) | 中文

这是一个以 Lucy 赛博朋克服装设计为灵感制作的 Codex 动态 pet。

包内包含透明背景动态 spritesheet，以及可供 Codex pet 加载使用的 `pet.json` 元数据。

## 从 Petdex 安装

Lucy 已发布到 Petdex：

[https://petdex.crafter.run/pets/lucy](https://petdex.crafter.run/pets/lucy)

使用下面这条命令一键安装：

```bash
npx petdex install lucy
```

安装后，pet 包会放入 `~/.codex/pets/lucy/`。在 Codex 中启用时，打开 Settings -> Appearance -> Pets，然后选择 Lucy。

## 手动下载

下载可直接使用的压缩包：

[dist/lucy-codex-pet.zip](dist/lucy-codex-pet.zip)

下载后解压。压缩包中包含一个 `lucy` 文件夹，里面有：

- `pet.json`
- `spritesheet.webp`

使用解压后的 `lucy` 文件夹作为 pet 包即可。

## 预览

![Lucy pet contact sheet](docs/contact-sheet.png)

![Idle animation](docs/previews/idle.gif)

## 文件内容

- `pets/lucy/pet.json` - pet 元数据
- `pets/lucy/spritesheet.webp` - 最终动态 spritesheet
- `docs/contact-sheet.png` - 展示所有动画行的 QA 预览图
- `docs/previews/idle.gif` - 待机动画预览
- `dist/lucy-codex-pet.zip` - 可直接下载的安装包

## 动作行

spritesheet 使用固定的 8 列 x 9 行布局：

| 行 | 状态 |
|---:|---|
| 0 | idle / 待机 |
| 1 | running-right / 向右移动 |
| 2 | running-left / 向左移动 |
| 3 | waving / 打招呼 |
| 4 | jumping / 跳跃 |
| 5 | failed / 失败 |
| 6 | waiting / 等待 |
| 7 | running / 任务处理中 |
| 8 | review / 审查 |

## 验证

最终 spritesheet 已验证为 `1536 x 1872` 像素，未使用格子保持透明，没有验证错误。

## 说明

这是一个粉丝创作的角色 artwork，并被打包为 Codex pet。适合个人和作品集展示用途。
