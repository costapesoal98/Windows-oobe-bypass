# 🧑‍💻 Force Local Account Creation During Windows OOBE (Shift + F10 Method)

This project documents a simple, manual method to **force the local account creation screen** during the Windows 10 or 11 setup process (OOBE), using a special URI from the Command Prompt.

---

## 🎯 Purpose

During the Windows Out-of-Box Experience (OOBE), especially in **Windows 11 Home and Pro**, users are often required or encouraged to use a Microsoft account. This guide shows how to **bypass that screen** and launch the hidden local account creation UI using the `ms-cxh:localonly` protocol.

✅ Works without modifying installation media  
✅ Requires no internet connection  
✅ 100% Microsoft-native behavior  
✅ Useful for IT pros, field technicians, or offline deployments

---

## 🚀 How It Works

During Windows setup (OOBE), press **Shift + F10** to open a command prompt, then run the following command:

```cmd
start ms-cxh:localonly

```

---

## 🧭 Credit / Source

The `ms-cxh:localonly` URI used in this guide was originally referenced in the open-source project:

🔗 [MSAPatcher by builtbybel](https://github.com/builtbybel/MSAPatcher/blob/main/Program.cs)

Special thanks to the author for sharing this powerful trick with the community!

---

## 📄 License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE) for more information.

---

## 👤 Author

**Maintained by [YourGitHubUsername]**  
Feel free to submit issues or improvements via Pull Request.

---

## ⭐ Star This Repo

If this helped you, please consider giving it a ⭐ on GitHub to help others discover it!
