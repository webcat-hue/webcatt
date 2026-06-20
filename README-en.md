![界面预览](https://github.com/webcat-hue/webcatt/blob/f2cf1684d10150679f3f154b69d764a94db018a0/image/2.JPG)
## 1. Function Introduction
This locally‑running front‑end tool generates TOTP dynamic verification codes following the RFC6238 standard. It works the same as Google Authenticator and Microsoft Authenticator.

All keys are saved in browser localStorage locally. No data will be uploaded to servers. Codes can be generated without network access.
It supports managing multiple accounts, 30‑second 6‑digit code refresh, countdown display and key deletion.

Please select your language

[中文](https://github.com/webcat-hue/webcatt/blob/main/README.md) [English](https://github.com/webcat-hue/webcatt/blob/main/README-en.md)


## 2. Usage
1. Get your Base32 key
Enable two‑factor authentication on your service, select manual key entry and copy the Base32 string.

2. Add your account
Fill in the account name such as GitHub or Steam. Paste your Base32 key and save.

3. View verification code
Tap an account entry to view the current code and its remaining valid time.

4. Delete key
Tap the delete button next to the account to remove its key.

## 3. Notes
1. Saved keys will disappear after clearing cache, switching browsers or closing incognito tabs. Back up important keys.
2. Only standard Base32 keys are supported. Keys containing 0,1,8,9 cannot be decoded.
3. Codes refresh every thirty seconds. Expired codes cannot be used for login.

## 4. Disclaimer
Users take full responsibility for any losses caused by using this code.
4. Delete key
Tap the delete button next to the account to remove its key.

## 3. Notes
1. Saved keys will disappear after clearing cache, switching browsers or closing incognito tabs. Back up important keys.
2. Only standard Base32 keys are supported. Keys containing 0,1,8,9 cannot be decoded.
3. Codes refresh every thirty seconds. Expired codes cannot be used for login.

## 4. Disclaimer
Users take full responsibility for any losses caused by using this code.
