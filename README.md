# azure-vm-deployment-lab
Hands-on lab to create, connect, and delete a Windows Virtual Machine on Microsoft Azure using the Azure Portal. Ideal for beginners in cloud computing.
# 🚀 Azure Virtual Machine Deployment Lab

This lab demonstrates how to create, connect to, and delete a **Windows Virtual Machine (VM)** on Microsoft Azure using the **Azure Portal**. It's ideal for beginners who are learning how to use cloud computing services in a hands-on way.

---

## 🎯 Objective

- Deploy a Windows Server 2022 Virtual Machine using Azure Portal
- Connect to the VM using Remote Desktop Protocol (RDP)
- Clean up resources to avoid billing charges

---

## 🧰 Tools Used

- Microsoft Azure Portal
- Windows 10 (local machine)
- Remote Desktop (RDP)
- GitHub (to document the lab)

---

## 🪜 Steps Performed

### ✅ Step 1: Log in to Azure Portal
Go to [https://portal.azure.com](https://portal.azure.com) and sign in.

📸 Screenshot: `Step1_AzurePortalDashboard.png`

---

### ✅ Step 2: Create a Virtual Machine
- Click **Create a resource**
- Search for **Virtual Machine**
- Click **Create**

📸 Screenshot: `Step2_CreateVM_Option.png`

---

### ✅ Step 3: Configure VM Basics
- Resource Group: `MyVMLabRG`
- VM Name: `MyWindowsVM`
- Region: `UK South` or nearest
- Image: `Windows Server 2022 Datacenter`
- Size: `Standard B1s`
- Username: `azureuser`
- Password: (choose your own)
- Public inbound ports: Allow **RDP (3389)**

📸 Screenshot: `Step3_VM_Basics.png`

---

### ✅ Step 4: Review and Create
- Click **Review + Create**
- Wait for **Validation passed**
- Click **Create**

📸 Screenshot: `Step4_ValidationPassed.png`  
📸 Screenshot: `Step5_DeploymentInProgress.png`

---

### ✅ Step 5: Connect via RDP
- Go to the **Virtual Machine Overview**
- Click **Connect > RDP**
- Download the `.rdp` file
- Log in using your `azureuser` credentials

📸 Screenshot: `Step6_RDPConnected.png`

---

### ✅ Step 6: Clean Up to Avoid Charges
- Go to **Resource Groups**
- Click `MyVMLabRG`
- Click **Delete resource group**
- Type `MyVMLabRG` to confirm and delete

📸 Screenshot: `Step7_DeleteResourceGroup.png`  
📸 Screenshot: `Step8_ResourceNotFound.png` (confirms deletion)

---

## 📘 What You Learned

- How to deploy a VM using the Azure Portal
- How to connect securely using RDP
- How to clean up cloud resources to prevent unexpected costs

---

## 🏷️ Tags

`Azure` `VirtualMachine` `CloudComputing` `BeginnerLab` `WindowsServer` `RDP` `GitHubPortfolio`

---

## 👤 Author

**Ime Ben**  
📧 imegcu55@gmail.com  
💼 GitHub: [ime-cloud-sec-analyst](https://github.com/ime-cloud-sec-analyst)

---

