不知为什么火了，感谢赵老师的指导开源，仅供学习使用，若侵权联系删除
点击fork 点击 create a fork 
然后就能够 在自己的github上拥有一个 一样的仓库

你现在就在 GitHub 的 **创建 Fork** 页面，当前设置基本正确。
# GPT：
### 现在这样操作

1. `Owner` 保持 `PING3753`
2. `Repository name` 保持 `ROS2_Tuition`
3. `Description` 可以保留，也可以不填
4. **Copy the main branch only** 保持勾选
5. 点击右下方绿色按钮 **Create fork**

等待十几秒，GitHub 会创建一份属于你的仓库：

```text
PING3753/ROS2_Tuition
```

原仓库的默认分支确实是 `main`，所以只复制 `main` 没问题。([GitHub][1])

## 创建成功后回到 GitBook

切换回 GitBook 标签页：

1. 在 `Select repository` 中选择：

```text
PING3753/ROS2_Tuition
```

若暂时看不到，关闭 Git Sync 窗口后重新打开，或者刷新 GitBook 页面。

2. `Select branch` 选择：

```text
main
```

3. `Project directory` 先保持：

```text
./
```

4. `Initial sync` 保持：

```text
GitHub → GitBook
```

也就是页面显示的：

```text
Content in GitHub replaces content in GitBook
```

5. 点击右下角 **Sync**。

## 这个仓库有一个重要情况

我查看了这个仓库：根目录主要是 `_book`、`README.md` 和 `_book.rar`，并且仓库内容几乎全部是 HTML。([GitHub][1])

这说明 `_book` 很可能是旧版 GitBook 已经生成好的网页文件，而不是用于编辑的 Markdown 原始文档。因此同步到新版 GitBook 后，可能只出现一个 `README` 页面，原来的完整左侧目录不一定会自动恢复。

所以第一次先使用：

```text
Project directory: ./
```

**不要填写 `./_book`**。`_book` 更像生成后的网页成品，而不是新版 GitBook 的文档源文件。这个判断是根据仓库结构作出的推断。([GitHub][1])

你当前这一步直接点击绿色的 **Create fork** 就可以继续。

[1]: https://github.com/Rechardluxry/ROS2_Tuition "GitHub - Rechardluxry/ROS2_Tuition: ROS2_Tuition赵虚左 · GitHub"

# 
