Hi!

I can't wait for meeting you at tomorrow's Android Things workshop!
I have so many interesting things to demo/present to you and we so little time (only 1.5 ours) for this... So let's get prepared in advance to spend these 90 minutes in the most efficient way (and to not ruin the event's wi-fi :)!

I kindly ask you:
1) Bring your own laptop and charger for it (the coool package with Android Things goodies is on us)

2) Sign up for the free account in Android Things Console https://partner.android.com/things/console/

3) Download setup utility from here: https://partner.android.com/things/console/#/tools

4) Unpack this archive and run the version of utility suitable for your OS. For macOS:
- ./android-things-setup-utility-macos
- Pick "1 - Install Android Things and optionally set up Wi-Fi"
- Pick "2 - NXP Pico i.MX7D"
- Pick "1 - Default image". It will download 300Mb firmware. We are good here for now.

5) Download and install Android Studio https://developer.android.com/studio/
- Go to Preferences -> Appearance & Behaviour -> System Settings -> Android SDK. Check Android 7.1.1 and Android 8.1 SDKs, click "OK"

6) If you are on macOS, please make sure that your /Users/USERNAME/.bash_profile file looks like this:
export ANDROID_HOME=/Users/USERNAME/Library/Android/sdk
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_XXX.jdk/Contents/Home

7) Clone the repos:
https://github.com/androidthings/sample-tensorflow-imageclassifier
and
https://github.com/androidthings/weatherstation
We'll use one of them.

8) Open these projects (select the coresponding folder as a target in "Open" dialog) in your Android Studio. Run Build -> Make project to check that the build went successfully.

9) We are good for now!

Happy evening, good luck with this small homework. And see you soon!

Questions, issues? Send me a DM on Twitter: https://twitter.com/webmaxru

Your trainer,
Maxim Salnikov
salnikov@gmail.com
