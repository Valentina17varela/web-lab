# Stripe Payment App

![](https://img.shields.io/badge/Code-ReactJs-informational?style=flat&logo=react&logoColor=white&color=61DAFB)
![](https://img.shields.io/badge/Build-Android-informational?style=flat&logo=android&logoColor=white&color=green)
![](https://img.shields.io/badge/Code-NodeJS-informational?style=flat&logo=Node.js&logoColor=white&color=43853D)
![](https://img.shields.io/badge/Framework-ExpressJS-informational?style=flat&logo=express&logoColor=white&color=43853D)

This Android mobile app makes it easy to manage unpaid check-ins at rental properties and hotel establishments. With direct integration with Stripe Terminal, it enables fast and secure payments directly at the point of service, optimising the experience for both staff and customers.
> The Frontend is made with react native and is integrated with a node Backend.

🎬 [Here](https://youtu.be/cSkEjiw5qZo) is a demonstration of how the application works.

<p align="center">
  <img width="1525" height="951" alt="Screenshot 2026-10-15 at 2 12 11 PM" src="https://github.com/user-attachments/assets/38ecc257-67b6-4363-8c3f-cc4106d18282" />
</p>


<br>

## 🤑 Features
- Display of check-ins pending payment.
- Integration with Stripe Terminal for in-person payments.
- Real-time notifications and updates on completed payments.

<br>

## ⚙️ Deploy
```
cd MiamiHospitality/
```
```
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$ANDROID_HOME/emulator:$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH
source ~/.zshrc
```

```
npx react-native run-android
```
