<p align="center">
<img src="https://github.com/user-attachments/assets/aab04f32-172d-48ea-95ec-7a5017f4952b" 
</p>


# 📁 Windows Server: Shared Folder Permissions

This lab taught me how to **control who gets access to certain files or folders** on a network. I used Windows Server to create shared folders and gave different levels of access depending on the user's group — like read-only, full access, or no access at all.

---

## 🧰 What Tools Did I Use?
- 🖥️ Windows Server (DC-1)  
- 👤 Active Directory (Users & Groups)  
- 🗂️ File Explorer (Folder Sharing & Permissions)  
- 💻 Windows 10 Client (to test user access)

---

## ✅ What Did I Set Up?

| Folder Name     | Group Assigned        | What They Could Do         |
|------------------|------------------------|------------------------------|
| `read-access`    | Domain Users           | View only                   |
| `write-access`   | Domain Users           | View + Edit                 |
| `no-access`      | Domain Admins Only     | Everyone else = blocked     |
| `accounting`     | ACCOUNTANTS Group      | Access given only after added to group ✅  |

---

## 🔍 What I Learned

🔐 Not everyone should see or change everything on a network  
👥 Permissions can be based on groups, not just individuals  
⚙️ Windows lets you combine *share* permissions with *NTFS* (file-level) settings  
✅ Testing access as different users helps confirm your security setup works

---

## 🖼️   
* visuals showing permission settings, folder sharing, failed access messages, successful access after group assignment, etc. *

---

