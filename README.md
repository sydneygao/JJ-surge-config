# JJ-surge-config
## Config files for the iOS Surge app.

### ⚙️ Import the configuration in the Surge app by selecting "Import from URL" and entering one of the following links:

**主链路（gh-proxy.org｜缓存，≤60 秒更新）：**
```text
https://gh-proxy.org/https://raw.githubusercontent.com/sydneygao/JJ-surge-config/main/JJ-config.conf
```

**备用链路1（gh.idayer.com｜动态回源，实时更新）：**
```text
https://gh.idayer.com/https://raw.githubusercontent.com/sydneygao/JJ-surge-config/main/JJ-config.conf
```

**备用链路2（git.yylx.win｜动态回源，实时更新）：**
```text
https://git.yylx.win/https://raw.githubusercontent.com/sydneygao/JJ-surge-config/main/JJ-config.conf
```

**备用链路3（cdn.jsdelivr.net｜稳定，更新延迟12小时）：**
```text
https://cdn.jsdelivr.net/gh/sydneygao/JJ-surge-config@main/JJ-config.conf
```

### ✈️ Add your airport subscription
**Tap the configuration file JJ-surge-config, and select "Edit in Text Mode".**
**Find the code below and fill in the required information.**

 Airport subscription
 1. Fill in the complete airport address below after `policy-path=https://`
 2. To disable subscription updates, set `update-interval=-1`
```text
手动选择 = select, policy-path=https://, update-interval=-1, icon-url=B1::User Interface::Choose
```
