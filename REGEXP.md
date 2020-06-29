#### 匹配半角字符（英文字母，数字，英文特殊符）
    new RegExp("[\x20-\x7E]{"+str.length+"}") 