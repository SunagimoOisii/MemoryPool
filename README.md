# MemoryPool

## 目次
- [概要](#概要)
- [使用技術](#使用技術)

## 概要
Vulkanでの**動的メモリ割り当ての最適化**を目的としたメモリプールです。<br>
メモリの確保,解放を高速化し、頻繁な `new`,`delete`呼び出しコストを削減することができます。<br><br>
システムの詳細や工夫点は以下からもご確認いただけます。<br>
[🔗 MemoryPool 詳細（Notionページ）](https://picturesque-kayak-ac4.notion.site/19b281634a16809aa663f12e753d2f4a?pvs=4)

## 使用技術
- Vulkan
- C++
