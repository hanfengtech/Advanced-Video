# Agora Media Source Windows

*其他语言版本： [简体中文](README.zh.md)*

The Agora Media Source Windows Sample App is an open-source demo that will help you get video chat integrated directly into your Windows applications using the Agora Video SDK.

With this sample app, you can:

- Join / leave channel
- Mute / unmute audio
- Enable / disable video
- Change camera
- Send message to channel
- Setup resolution, frame rate and bit rate
- Enable encryption
- Enable / disable black and white filter
- Enable / disable external video & audio stream capturing and audio stream playing

This demo is written in **C++**

A tutorial demo can be found here: [Agora-Windows-Tutorial-1to1](https://github.com/AgoraIO/Basic-Video-Call/tree/master/One-to-One-Video/Agora-Windows-Tutorial-1to1)


##Install Directx SDK

You need to download and install [directx sdk 2010 June](https://www.microsoft.com/en-us/download/confirmation.aspx?id=6812)。

After install dx sdk successfully,you need to reboot your computer.


## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID. define the APP_ID with your App ID.

```
#define APP_ID _T("Your App ID")
```

Next, download the **Agora Video SDK** from [Agora.io SDK](https://docs.agora.io/en/Agora%20Platform/downloads). Unzip the downloaded SDK package and copy the **sdk** to the "AgoraMediaSource" folder in project(the old one may be over written).

Finally, Open AgoraMediaSource.sln, build the solution and run.

Note：
  1. After the program is compiled, if the program "xxx\xxx\xxx\Debug\Language\English.dll" cannot be started when running the program, 
      please select the AgoraMediaSource project in the Solution Explorer and right click. In the pop-up menu bar, select "Set as active project" to solve. Then run the program again.
  
  2. The dll library under the sdk/dll file needs to be placed in the corresponding execution path.
  
  Tips: The relevant dll library has been configured for you in this case tutorial. If you want to use the interface provided by agora for related development, you need to put the dll library into the corresponding execution path as prompted above.

## Developer Environment Requirements
* VC2013 or higher
* WIN7 or higher

## Connect Us

- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can fire bugs about this demo at [issue](https://github.com/AgoraIO/Advanced-Video/issues)

##Note

For master branch

You need IAgoraRtcEngine2.h header file.

## License

The MIT License (MIT).
