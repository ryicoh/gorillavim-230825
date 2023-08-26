
# 囲いを編集する(vim-surround,vim-sandwich)

## ( で囲いたい場合

1. cw(<C-r>-) (１行のみ、複数行は、cw(<C-r><C-o>")

hello を (hello) に変えたい

... hello ...


2. cw()<ESC>P


... hello ...


## ( で囲われてるのを { に変えたい場合

di(vhr{p する


## " で囲われてるのを ’ に変えたい場合は

di"vhr'p する


## " で囲われてるのを消したい場合

yi"va"p する

