---
title: PB项目V7和V6版本部署
date: 2025-10-20T13:06:20.252Z
---

由于V7版本和V6版本的环境所需不同，因此需要部署不同的虚拟环境，我使用conda分别命名为:
![image.png](https://raw.githubusercontent.com/BrandonWenn/tinymind-blog/main/assets/images/2025-10-20/1760965090888.png)

今天尝试了V7版本的backteset和optimizing，找了一个doeg和sol一起的config，但长期（2021-2025.10）下来效果不佳。

下面是使用tg一个大叔的config，短期（2025.1-2025.7）效果都不错，长期如图书所示：
![image.png](https://raw.githubusercontent.com/BrandonWenn/tinymind-blog/main/assets/images/2025-10-20/1760965270189.png)

在discord上看到一种说法，避免使用单币种来优化，可能会过拟合。我的目前的看法是，我只打算跑一种币的话，我认为优化单币种是有价值、有意义的。但我考虑这种说法，可能考虑多币种，就是考虑市场趋势，也可能规避风险。