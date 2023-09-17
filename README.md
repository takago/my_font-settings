# my_font-settings

Linux Mintのフォント設定（自分用）

```
sudo apt-get install fonts-inconsolata fonts-ipafont fonts-noto fonts-dejavu
# Ryumin, GothicBBB, sans-serif, serif, monospace の設定（鷹合の好みに）
# ハングルなど，個人的には全く必要ないフォントを無効化する（LibreOfficeのフォント選択が軽くなる）．

wget https://raw.githubusercontent.com/takago/my_font-settings/main/78-Reject.conf -P /etc/fonts/conf.d/
wget https://raw.githubusercontent.com/takago/my_font-settings/main/local.conf -P /etc/fonts
```
