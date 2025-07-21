# 🛠️ AnyDesk Reset Tool (Batch Script)

A one-click batch script to **fully reset AnyDesk** to its default state. This tool removes cached configuration files, restarts the service, and relaunches AnyDesk cleanly.

---

## ⚙️ Features

- 🔁 Stops and restarts the AnyDesk service
- 🧼 Deletes `service.conf`, `user.conf`, and thumbnail cache
- 📂 Temporarily backs up essential files (`user.conf`, thumbnails)
- 🔄 Auto-relaunches AnyDesk after cleanup

---

## 🚀 Usage

1. **Right-click** on the `.bat` file and select **Run as administrator**
2. The script will:
   - Stop AnyDesk service
   - Remove all configs
   - Restore essential configs
   - Restart the service and launch AnyDesk

---

## 🧠 Notes

- ✔️ Compatible with both `Program Files` and `Program Files (x86)` installs
- ⚠️ Must be run with administrative privileges
- ⏳ Waits until AnyDesk regenerates `system.conf` before proceeding

---

## 📄 License

Released under the [MIT License](LICENSE)  
Free to use, modify, and distribute — just give proper credit.

---

## 👨‍💻 Author

**The Traveler**  
System automation and Windows scripting enthusiast.
