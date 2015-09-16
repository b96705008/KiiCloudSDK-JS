## Overview
This repository is fork from KiiCorp/KiiCloudSDK-JS (https://github.com/KiiCorp/KiiCloudSDK-JS)

## How to use

Require module

```
var kii = require('kii-cloud-sdk');
```

Initialize

```
kii.Kii.initializeWithSite(appid, appkey, kii.KiiSite.US);
```

Kii User example

```
kii.KiiUser.authenticate(loginName, password, {...});
```