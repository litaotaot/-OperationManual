#### 匹配半角字符（英文字母，数字，英文特殊符）
    new RegExp("[\x20-\x7E]{"+str.length+"}") 
#### 仅输入：英文、数字、下划线、中划线
    /^[a-zA-Z0-9_\\-]+$/