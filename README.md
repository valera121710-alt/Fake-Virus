# 🚨 FolderVirus - Joke "Virus" 🚨

## ⚠️ WARNING - READ BEFORE DOWNLOADING!
**THIS IS A HARMLESS JOKE PROGRAM!** 
- 🎭 **Pranks only** - for fun with friends
- 🔒 **No damage** - doesn't harm your computer
- 📁 **Creates folders only** - no files deleted
- 🛑 **Not real malware** - educational purpose only

## 📁 What It Does
When you run this program, it creates **100 folders** on your desktop with funny names like:
Budem kushat? (1)
Budem kushat? (2)
...
Budem kushat? (100)

text

"Budem kushat?" means "Shall we eat?" in Russian - because why not? 🍕

## 🎯 How to Use (For Pranks)
1. Download `FolderVirus.exe`
2. Send to a friend (tell them it's a "game" or "tool")
3. Watch them get confused by 100 new folders! 😄
4. **Always tell them it's a joke afterwards!**

## 🛡️ Safety Guarantee
- ✅ No system modifications
- ✅ No file deletions  
- ✅ No data theft
- ✅ No network connections
- ✅ No registry changes
- ✅ Completely reversible (just delete the folders)

## 🔧 Technical Details
**Language:** Java  
**Type:** Executable (EXE)  
**Size:** ~45MB (includes Java Runtime)  
**Platform:** Windows 10/11  

## 📥 Download

[![Download Virus](https://img.shields.io/badge/Download-FolderVirus.exe-red?style=for-the-badge&logo=windows)](https://github.com/valera121710-alt/cmd-blocker/releases/download/Fun/FolderVirus-1.0.exe)

**Direct Link:** https://github.com/valera121710-alt/cmd-blocker/releases/download/Fun/FolderVirus-1.0.exe

## 🗑️ How to Remove
Simply delete all "Budem kushat?" folders from your desktop. That's it!

## ⚖️ Legal Notice
Use responsibly! Only for:
- 🎉 Pranks with friends who will laugh about it
- 🧪 Educational purposes
- 😄 Funny demonstrations

**Do not use for malicious purposes!**

## 🐛 Source Code
```java
// Simple folder creation "virus"
import java.io.File;

public class Virus {
    public static void main(String[] args) {
        String desktop = System.getProperty("user.home") + "\\Desktop\\";
        for (int i = 1; i <= 100; i++) {
            new File(desktop + "Budem kushat? (" + i + ")").mkdir();
        }
    }
}
Remember: With great power comes great responsibility! Use this only for good-natured fun! 🦸

PS: If you fell for this prank - don't worry, your computer is safe! 😊
