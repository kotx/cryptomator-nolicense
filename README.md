Follow the steps in https://github.com/cryptomator/android#building after applying the patch:
```
git apply license.patch
```

Remember to set the attached environment variables in your shell for the actual build.

If you're building release (`assembleApkStore`), you might want to use this tool for signing: https://github.com/patrickfav/uber-apk-signer