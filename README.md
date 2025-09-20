# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
<img width="1898" height="955" alt="436824504-f59bf54d-2fe1-4e89-8647-87e4f961686f" src="https://github.com/user-attachments/assets/550b1b99-d002-45e0-a321-c2028ad59b3a" />
<img width="975" height="384" alt="436826032-6903c170-1426-423a-9844-60121b584469" src="https://github.com/user-attachments/assets/dbe0e1d8-c1b7-4639-823c-46954f517076" />
![WhatsApp Image 2025-09-20 at 14 37 15 (1)](https://github.com/user-attachments/assets/be197f18-abc4-4993-9c9c-6e533a16e01a)
![WhatsApp Image 2025-09-20 at 14 37 15 (2)](https://github.com/user-attachments/assets/d0e38efa-a9d5-42a4-a22f-37358d92f773)
![WhatsApp Image 2025-09-20 at 14 37 15](https://github.com/user-attachments/assets/be900904-22ce-4953-a3a9-4d652e631f17)
![WhatsApp Image 2025-09-20 at 14 37 15](https://github.com/user-attachments/assets/404d95d7-18ea-48d5-8559-8f81a7b729d8)

<img width="1670" height="953" alt="435598964-662b99bf-a610-4ca0-b243-284d9642df7c-2" src="https://github.com/user-attachments/assets/849f29db-aa3a-49de-a0f7-316d579c6414" />

<img width="1914" height="930" alt="435599647-3a049473-4ab8-4edf-8568-b711701bbb4c" src="https://github.com/user-attachments/assets/3b498b32-aa08-4899-a5fa-7d645452e09a" />
<img width="1917" height="874" alt="435599822-eba10265-f48c-47cc-861f-24a83bb72b10" src="https://github.com/user-attachments/assets/f39f85e1-12b1-47e9-a947-809b6cb36543" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
