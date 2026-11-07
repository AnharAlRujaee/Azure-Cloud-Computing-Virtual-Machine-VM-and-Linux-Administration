# Azure Cloud Computing – Virtual Machine and Linux Administration

**Student:** Anhar Taha Al-Rujaee  
**Platform:** Microsoft Azure  
**Operating system:** Ubuntu Server 24.04 LTS  
**VM:** `AnharAlRujaee-VM`  
**Azure region shown in the VM evidence:** South Africa North

## Project overview
This repository documents a practical assignment deploying and administering an Ubuntu Linux virtual machine in Microsoft Azure. It covers web hosting, database setup, Samba file-sharing configuration, and Azure Files integration.

## Tasks completed
1. **Azure VM:** Created an Ubuntu VM and connected using SSH.
2. **Apache:** Installed and enabled Apache, published a custom HTML welcome page, and added an Azure inbound rule for HTTP (TCP/80).
3. **MySQL:** Installed MySQL Community Server 8.0.46, created `anhar_database`, created a `students` table, inserted a sample row, and verified it with `SELECT`.
4. **Samba:** Installed Samba, created `/srv/samba/shared`, configured a `sambashare` group and Samba user, added the `[AnharShare]` share configuration, validated the configuration, and confirmed `smbd` was running. A separate remote-client connection test was not documented.
5. **Azure File Share:** Created the `nexuscrm` storage account and `anhar-files` share, mounted it at `/media/anhar-files`, and successfully created, read, and deleted a test file.

## Repository contents
- `Report/Azure_VM_Assignment_Report.pdf` – final report.
- `Report/Azure_VM_Assignment_Report.docx` – editable report.
- `Screenshots/` – selected evidence from the practical work. The VM overview screenshot has its public IP and subscription ID redacted.
- `Configuration/samba-share-config.txt` – Samba share configuration example.

## Security
Screenshots and repository files must not contain passwords, storage account keys, private keys, access tokens, or `.env` files. Do not expose Samba TCP/445 to the public internet. The assignment VM and storage resources should be deleted only after submission and any trainer review are complete.

## Author
[Anhar Taha Al-Rujaee – LinkedIn](https://www.linkedin.com/in/anhar-taha-al-rujaee-645668226/)

## Repository
https://github.com/AnharAlRujaee/Azure-Cloud-Computing-Virtual-Machine-VM-and-Linux-Administration
