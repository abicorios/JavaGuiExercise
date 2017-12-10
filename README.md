# JavaGuiExercise
It is an example of the using of the GUI by the Java.
# Dependence
Use JDK for compile and run.
# Compile and run
In the command line input:
```
javac javagui.java
java javagui
```
# Android
1. The Android device which can run Termux;
2. The Hacker's Keyboard https://play.google.com/store/apps/details?id=org.pocketworkstation.pckeyboard have the additional keys  (Ctr, Alt, Esc, etc) like on the keyboard for the desktop. But you must set it from 3 to 5 rows. You can want to stop some console programm by the Ctrl+C, so install this full keyboard before using Ping, for example.
3. The Termux from the GooglePlay https://play.google.com/store/apps/details?id=com.termux is the powerfull command line;
4. The TermuxArch https://wiki.termux.com/wiki/Arch is the full extensible operation system with the package manager and now (end of 2017 year) it is one working Linux distributive which can be installed without big errors by PRoot in Termux. Also TermuxArch produce less errors than pure Termux along using like on the usual Linux. And it is better for your to confirm the adding of the startarch script in your path at the end of the installing of the TermuxArch;
5. For install JDK9 and Git, in TermuxArch run
```
pacman -S jdk9-openjdk git
```
6. Install and run https://play.google.com/store/apps/details?id=x.org.server 
7. In the TermuxArch input:
```
export DISPLAY=:0 PULSE_SERVER=tcp:127.0.0.1:4712
```
Now you can compile and run Java code with Gui. But on the Android you do not have the exit key on the Swing window by default. So you need code exit key, or use Ctrl+C in the console.
