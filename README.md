# Azure Backup & Restore – VM

## 📘 Objective:
Enable backup for an Azure VM and restore it from a backup point.

---

## 🛠️ Steps Performed:

1. Selected existing Azure VM from the portal.
2. Enabled Backup under **Operations > Backup**.
3. Created a Recovery Services Vault and linked to VM.
4. Took an **On-Demand Backup** with 30 days retention.
5. Later performed a **VM Restore** using restore point.
6. Created a new VM from backup named `restored-vm-test`.

---

## 📌 Notes:
- Backup stored in Recovery Services Vault.
- Useful for disaster recovery and system failures.
- Restoration creates a clean copy of the VM.
