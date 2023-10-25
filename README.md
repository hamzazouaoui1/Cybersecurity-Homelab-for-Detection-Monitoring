
# Building The Host PC

For this Lab, I will be using my personal desktop which has more than enough to host the intended VMs. The hardware specifications are listed below:

- **CPU**: Intel Core i7-9700K 3.6 GHz 8-Core Processor
- **RAM**: Corsair Vengeance RGB Pro 64GB (4 x 16 GB) DDR4
- **STORAGE**: Samsung 970 Evo Plus 1 TB M.2-2280 PCIe 3.0 X4 NVME
- **GRAPHICS CARD**: EVGA SC2 HYBRID GAMING GTX 1080 Ti 11 GB
- **MOTHERBOARD**: MSI B450 TOMAHAWK MAX ATX AM4
- **HOST OPERATING SYSTEM**: Windows 10 Pro

You have the option to purchase a dedicated server, or alternatively, repurpose an older laptop, as long as it meets the necessary requirements to run all the essential virtual machines. While 8GB of RAM is generally sufficient, I suggest opting for 16GB if possible.

# Downloading & Installing VMware Workstation Pro

To obtain and set up VMware Workstation Pro, I will utilize VMware Workstation 16 Pro as my hypervisor for this lab. Although this software carries a price tag of approximately $120, a student discount is available. I assure you that this investment is highly valuable for your needs.

VirtualBox is also a free and feature-rich alternative Hypervisor from Oracle. If you cannot afford the VMware license, VirtualBox is equally good.

## Step 1: Download VMware Workstation

1. Visit the VMware website [here](https://www.vmware.com/products/workstation-pro.html) and download the latest version of VMware Workstation. You may need to create or log in to a VMware account to access the download.

## Step 2: Install VMware Workstation

### For Windows:

1. Run the installer you downloaded in Step 1.

2. Click "Next" on the initial installation screen.

3. Accept the End User License Agreement (EULA) and click "Next."

4. Choose the installation location or keep the default and click "Next."

5. Select the product updates and check for the latest updates during installation (recommended). Click "Next."

6. Choose whether you want to participate in the Customer Experience Improvement Program and click "Next."

7. Review the installation settings and click "Install" to begin the installation.

8. Wait for the installation to complete. It may take a few minutes.

9. Once the installation is finished, click "Finish" to exit the installer.

### For Linux:

1. Open a terminal.

2. Navigate to the directory where the installer is located.

3. Make the installer executable (if needed) using the following command:

   ```bash
   chmod +x VMware-Workstation-Full-*.bundle
   ```

   Replace "VMware-Workstation-Full-*" with the actual name of the installer file.

4. Run the installer using the following command:

   ```bash
   sudo ./VMware-Workstation-Full-*.bundle
   ```

   Replace "VMware-Workstation-Full-*" with the actual name of the installer file.

5. Follow the on-screen instructions to complete the installation, including accepting the EULA and specifying installation settings.

## Step 3: License Activation (if required)

1. Launch VMware Workstation.

2. If prompted for a license key, enter your license key and follow the activation process. If you don't have a license key, you can choose to use VMware Workstation in trial mode.

## Step 4: Create a Virtual Machine

1. Launch VMware Workstation.

2. Click "File" and then "New Virtual Machine."

3. Follow the New Virtual Machine Wizard to create a virtual machine by specifying the operating system, hardware configuration, and other settings.

4. Install the operating system on the virtual machine using an ISO image or other installation media.

## Step 5: Install VMware Tools (Optional)

After installing the guest operating system on your virtual machine, you can install VMware Tools for enhanced performance and integration.

1. In the VMware Workstation window, go to "VM" > "Install VMware Tools."

2. Follow the on-screen instructions to install VMware Tools within the virtual machine.

That's it! You now have VMware Workstation installed, and you can create and manage virtual machines for various purposes.
