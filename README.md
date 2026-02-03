<div align="center">

# EsteOri-OS

[![Download Pack](https://img.shields.io/badge/Download-EsteOri--OS_Pack-blue?style=for-the-badge&logo=windows)](https://mega.nz/folder/KkZEiTAa#I1LJgvmhXKjUFbmNK7cjfw)

</div>

---

## 📥 Installation Guide

Follow these steps to flash **EsteOri-OS** to your USB drive correctly. The download pack includes everything you need.

### **Step 1: Flash with Rufus**
1.  Open the **EsteOri-OS** folder you downloaded.
2.  Launch **`rufus-4.12.exe`** (included in the pack).
3.  Click the **SELECT** button.
4.  Navigate to the folder and select **`EsteOri-OS.iso`**.
5.  Click **START**.
    * *Wait for the progress bar to finish until it says "READY".*

> **Optional Pro Tip:**
> When you click START, Rufus may show a popup called "Windows User Experience."
> * Check the box **"Create a local account with username"**.
> * Type your desired name (e.g., `Ben`).
> * This ensures your user is created automatically without Microsoft account requirements.

---

### **Step 2: Verify Your USB**
Once finished, open your USB drive in File Explorer. It should look **exactly** like this:

```text
📂 boot
📂 efi
📂 sources
📂 support
📄 autorun.inf
📄 bootmgr
📄 bootmgr.efi
⚙️ setup.exe
