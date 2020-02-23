# mabi-bflogin

這份專案的登入部分是改寫自 [BeanfunLogin](https://github.com/BeanfunLogin/BeanfunLogin) 詳細的邏輯可以回去看看他的專案的部分  

為了方便快速開啟分身所以寫了這份專案，由於登入BF會有擋掉的機制，所以每個帳號有間隔10秒的時間。

## 使用說明
[accountsInfo.json](https://github.com/NNSound/mabi-bflogin/blob/master/accountsInfo.json)
帳號與密碼請由下面的格式填寫，請記得最後一組帳密的後面請不要加上**逗號**，避免json 格式錯誤。
```
[
    {
        "user": "帳號",
        "pass": "密碼"
    },
    {
        "user": "帳號",
        "pass": "密碼"
    },
    {
        "user": "帳號",
        "pass": "密碼"
    },
]
```
將兩份檔案都放入遊戲資料夾後，啟動opt.exe 就可以了。
