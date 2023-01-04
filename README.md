# bash-twl
script file ရေးသားပြီး ခေါ်သုံးခြင်း
1. $HOME/bin အောက်မှာ script file တစ်ခု တည်ဆောက်ပါ။
2. exe လုပ်လို့ရအောင် chmod +x filename လုပ်ပါ
3. $HOME/bin ကို bash က exe လုပ်တာမို့
4. source .profile လုပ်ပါ။
5. ပြီးရင် file name ဖြင့် ခေါ် run နိုင်ပြီ
---
`
toe@toe$ mkdir bin
$ cd bin/
/bin$ touch helloscript
===============
#!/bin/bash
script logic code is here..!
===============
/bin$ chmod +x helloscript
/bin$ bash helloscript
$ source .profile
$ helloscript
`