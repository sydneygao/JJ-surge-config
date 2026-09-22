# JJ-surge-config
## Config files for the iOS Surge app.

### ⚙️ Import the configuration in the Surge app by selecting "Import from URL" and entering one of the following links:

**主链路（gh-proxy.org｜最快，≤60 秒更新）：**
```text
https://gh-proxy.org/https://raw.githubusercontent.com/sydneygao/JJ-surge-config/main/JJ-config.conf
```

**备链路（gh.idayer.com｜不同链路，实时）：**
```text
https://gh.idayer.com/https://raw.githubusercontent.com/sydneygao/JJ-surge-config/main/JJ-config.conf
```

**兜底链路（cdn.jsdelivr.net｜最稳，接受最长约 12 小时延迟）：**
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
