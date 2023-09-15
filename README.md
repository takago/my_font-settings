# my_font-settings

Linux Mintのフォント設定（自分用）

```
# 設定ファイルのダウンロード
git clone https://github.com/takago/my_font-settings
cd  my_font-settings/

# Ryumin, GothicBBB, sans-serif, serif, monospace の設定（鷹合の好みに）
sudo apt-get install fonts-inconsolata fonts-ipafont fonts-noto fonts-dejavu
sudo cp local.cof /etc/fonts/

# ハングルなど，個人的には全く必要ないフォントを無効化する（LibreOfficeのフォント選択が軽くなる）．
sudo cp 78-Reject.conf /etc/fonts/conf.d/     
```
