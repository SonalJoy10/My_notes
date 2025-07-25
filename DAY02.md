# 🛡️ Cybersecurity Class – Day 2 Report

📅 **Date:** [Insert Date Here]  
🎯 **Topic:** Installing Kali Linux in Oracle VirtualBox

---

## 🧰 Requirements

To install Kali Linux on a Windows host machine, you need the following:

1. **Kali Linux VirtualBox Image**  
   📥 [Download](https://cdimage.kali.org/kali-2025.2/kali-linux-2025.2-virtualbox-amd64.7z)

2. **Oracle VirtualBox**  
   📥 [Download](https://download.virtualbox.org/virtualbox/7.1.12/VirtualBox-7.1.12-169651-Win.exe)

3. **7-Zip File Extractor**  
   📥 [Download](https://www.7-zip.org/a/7z2500-x64.exe)

> 💾 **Note:** Make sure you have at least **10–15 GB** of free disk space available.

---

## 🧱 Step 1: Install Oracle VirtualBox

1. Run the downloaded VirtualBox installer.
2. Click **Yes** to allow administrator privileges.
3. Click **Next** in the installer dialog box.
4. On the **Custom Setup** page, leave settings unchanged and click **Next**.
5. If a **"Warning! Network Interfaces"** page appears, click **Yes**.
6. If a **"Missing Dependencies"** warning appears, click **Yes**.
7. On the **Ready to Install** page, click **Install**.
8. Once done, click **Finish**.

---

### ⚠️ Troubleshooting Oracle VirtualBox Installation

#### 🔧 Problem 1: Missing Dependency  
**Microsoft Visual C++ 2015–2022 Redistributable (x64) - 14.44.35211**  
📥 [Download](https://aka.ms/vs/17/release/vc_redist.x64.exe)

- Install the package and re-run the VirtualBox installer.

#### 🔧 Problem 2: AMD-V Disabled in BIOS

1. Restart your system and enter the BIOS menu.
2. Enable **Virtualization** (may appear as **SVM Mode** or similar).
3. Common BIOS keys by brand:
   - Dell: `F2` or `F12`
   - Lenovo: `F1`, `F2`, or `Fn + F2`
   - Acer: `F2` or `Del`
   - HP: `Esc` or `F10`

---

## 📦 Step 2: Install 7-Zip

1. Right-click the 7-Zip installer and choose **Run as Administrator**.
2. Click **Install** in the dialog box.
3. Click **Close** after installation.

---

## 🗃️ Step 3: Extract Kali Linux Image

1. Locate the downloaded `.7z` Kali Linux image file.
2. Right-click it → **Show more options** → hover over **7-Zip** → select **Extract Here**.
3. Wait for extraction to complete.

---

## 🖥️ Step 4: Load Kali Linux in VirtualBox

1. (Optional) Create a **separate disk partition** (10–15 GB) to store Kali Linux files.  
   📺 [How-to video](https://www.youtube.com/watch?v=HGqo17dGk0E)

2. Move the **extracted image folder** into the new partition.
3. Inside the folder, locate the `.vbox` file (VirtualBox Machine Definition).
4. Double-click the `.vbox` file to open it with Oracle VirtualBox.
5. Click **Start** in VirtualBox to boot Kali Linux.
6. On first boot, it may take some time to load.
7. When prompted, use:
   - **Username:** `kali`
   - **Password:** `kali`

---

## ✅ Conclusion

You’ve successfully installed Kali Linux in a virtual environment. This setup will be your primary platform for running and testing cybersecurity tools safely in an isolated space.

---
