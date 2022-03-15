# Unity-CloudBuild-Push-AppStore
bash script to auto-deploy your iOS CloudBuild directly to App Store

# Usage:
- Update your project version + build number to a valid App Store version (have to be a new version to be uploaded)
- Add this bashscript in your Unity project.
- Setup your Unity iOS Cloud-build. (iOS platform, Signing credentials, provisionning profile etc)
- Under Advanced Options, configure the script relative path as Post-Build Script, see example:
![image](https://user-images.githubusercontent.com/21199374/158421195-0436220f-7c30-4c83-973e-697e139d1bc2.png)
- Add your App Store Connect credentials as Environment variable + TARGET_NAME: iOS for me, see example:
![image](https://user-images.githubusercontent.com/21199374/158421542-ecab05a0-ba4f-4497-8dff-937fa178ff5d.png)

Enjoy auto-deploy!
