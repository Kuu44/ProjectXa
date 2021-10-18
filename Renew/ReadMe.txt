1. go to DockerQuickstartTerminal
2. edit 'create.sh' to the required UnityVersion
3. type 'bash create.sh' and run
4. copy contents of 'insidebash.txt' and run
5. Wait for output that looks like this:

LICENSE SYSTEM [2017723 8:6:38] Posting <?xml version="1.0" encoding="UTF-8"?><root><Syste

6. then go to step 5: https://github.com/Unity-CI/unity3d-ci-example
7. After finishing that, create a variable
   UNITY_LICENSE_CONTENT
   in travis-ci.com and paste contents of the downloaded 'Unity_v20xx.x.ulf' into it and save
8. For 2018 and 2019 versions, use the (encrypted) travis ci file
9. Add the ANDROID_KEYSTORE_BASE64 variable as the encrypted
10. For the rest of the variable, check the ss or 
https://discordapp.com/channels/@me/421505420604211201/710533112425349141
