# Virtual Hard Disk (VHD) in Azure

## What is VHD?

In Azure, **VHD** stands for **Virtual Hard Disk**. It is a file format used to store the disk data of Azure Virtual Machines (VMs). A VHD file represents a virtual disk and can contain the OS, data, applications, and more.

---

## Key Points

### 1. Storage Format
- VHDs are stored as **page blobs** in Azure Blob Storage.

### 2. Types of VHDs
- **Managed Disks**: Automatically managed by Azure, offering high availability and scalability.
- **Unmanaged Disks**: Stored directly in Azure Storage Accounts, giving more control but requiring manual management.

### 3. VHD File Types
- **OS Disk**: Contains the operating system and is used to boot the VM.
- **Data Disk**: Additional storage attached to a VM for storing data, apps, or databases.
- **Temporary Disk**: Provides short-term storage and is not persisted when the VM is stopped or deallocated.

### 4. Disk Formats
- **Fixed Size VHD**: Pre-allocates space for the entire disk size, providing consistent performance.
- **Dynamic VHD**: Grows as data is written, saving space initially.

### 5. Uses
- Storing VM images and snapshots.
- Creating custom VM images.
- Migrating on-premises VMs to Azure.
- Backing up or restoring VM data.

### 6. Supported Formats
- Azure supports **VHD** (not VHDX) files for creating virtual machine disks.

---

## Conclusion

VHDs are an essential part of Azure Virtual Machines, used to store and manage the OS, application data, and system states efficiently. Managed disks simplify storage management, while unmanaged disks provide flexibility and control.
