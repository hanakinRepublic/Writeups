# Reversing
---
# Web
---
# RECON
## Social
### Description
  記載なし
### Solution
  まず初めに、そもそもジャンルの*RECON*がどのようなジャンルか分からなかったので検索しました。  
  すると、「ネットストーカーをする問題」との記載がありました。    
  ってことは、、、と思いSNSアカウントを隈なく調べてみることにしました。    
  具体的には、FireShellのチーム・メンバーのアカウントを調べて今回のCTFに関係ありそうな投稿やプロフィール欄の文字を調べました。  
  すると、FBの今大会の宣伝ページにQRコードがあることに気づきました。    
  それを読み取ると、怪しげなページが。。。(スクショ撮り忘れ)    
  URLをみると、`%0AF#%7B4re_Y0u_r3c0n?!!_:)%7D`
  の文字が。。。  
  いわゆるURLエンコーディングではないかと思い、Webで検索したツールを使ってデコード。  
  `F#{4re_Y0u_r3c0n?!!_:)}`    
  ビンゴ！
### Reference
  - [CTFのジャンル概要 - http://www.zombie-hunting-club.com/entry/2017/10/29/201108](http://www.zombie-hunting-club.com/entry/2017/10/29/201108)
  - [URLエンコード - https://www.tagindex.com/tool/url.html](https://www.tagindex.com/tool/url.html)
  ---
