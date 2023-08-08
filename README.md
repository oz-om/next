# NextJs on your Android 🚀
### running nextjs server in your phone with an eruda console 😀
![](https://hackmd.io/_uploads/Syz5CtJhn.jpg)


***requirements:***
1. the first thing you should have is [termux](https://play.google.com/store/apps/details?id=com.termux)
2. the second thing is a [code editor](https://play.google.com/store/apps/details?id=com.foxdebug.acode) (recommend Acode).

***installation:***
* update and upgrade termux env
```
apt upgrade -y
apt update -y
```
* install nodeJs
we can install nodejs by running:
```
pkg install nodejs-lts
pkg install nodejs
```

* running Nextjs
open termux app then clone this repo `git clone repURL`.
before running this reop you should be installing this package *@next/swc-android-arm-eabi* by running this command:
```
npm i -g @next/swc-android-arm-eabi
```
after that move to root dir `cd next`
and run `npm install && npm run dev`
and congratulations 🎉 the nextJs server `http://localhost:3000` now running on your termux
![](https://hackmd.io/_uploads/By1u0Fy22.jpg)

