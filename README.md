# PTT 自動登入 (Shell)
git
## 使用方法

將 `setting.config.example` 重新命名爲 `setting.config`
並將內容修改為自己的 PTT ID 以及 Password

```
set BBS_ID "YourUserName"
set BBS_PW "YourPassword"
```

# PTT 自動登入發文 (Python)

## 使用方法

將 `setting.ini.example` 重新命名爲 `setting.ini`
並將內容修改為自己的 PTT ID 以及 Password

```
[default]
username = YourUserName
password = YourPassword
```

## 執行範例

```
python PttAuto.py
```

預設為在 PTT Test板 發文
標題 : testtitle
內文 : testcontent

``` python
ptt.post('test', 'testtitle', 'testcontent')
```

## License

MIT license
