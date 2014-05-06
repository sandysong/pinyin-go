pinyin-go
=========

获得汉字对应的汉语拼音，拼音数据来自：emptyhua/bash-pinyin-completion

只包含一个函数：GetPinyin(r rune) []string
传入一个Unicode字符，返回对应的拼音（考虑到多音字情况，返回的是string数组）
非中文汉字返回nil
