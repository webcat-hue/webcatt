Ⅰ. Function Introduction
 
This tool is a pure‑client‑side TOTP dynamic verification‑code generator running locally, complying with RFC6238. Its algorithm is compatible with Google Authenticator and Microsoft Authenticator.
All secret keys are stored locally in browser localStorage only. No data will be uploaded to remote servers, and verification codes can be generated without an internet connection.
Features include multi‑account key management, 6‑digit codes refreshed every 30 seconds, countdown indicator and key deletion.
 
Ⅱ. Usage Instructions
 
1. Obtain your Base32 secret key
Head to websites or admin panels supporting two‑factor authentication. Enable two‑step verification, choose the manual key entry option, then copy the provided Base32 string.
2. Add account information
Name your account such as GitHub or Steam for easy identification. Paste your Base32 key and click the add button to save.
3. Check dynamic verification code
Tap any saved‑account entry. The current 6‑digit code appears at the top, with a countdown showing remaining valid time.
4. Delete stored keys
Click the red delete button beside the target account to remove its saved key.
 
Ⅲ. Notes
 
1. Saved keys will be erased after clearing browser cache, switching browsers or closing incognito tabs. Keep backups for important keys.
2. Standard Base32 keys are required. Keys containing digits 0,1,8,9 cannot be decoded properly.
3. Codes refresh every 30 seconds. Expired codes cannot be used for login. Make sure the countdown is still running before use.
 
Ⅳ. Liability
 
You shall bear all losses arising from using this code.
