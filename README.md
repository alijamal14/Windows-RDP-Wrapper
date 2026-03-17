# Windows RDP Wrapper

## Public Internet Setup

1. Install `RDPWInst-v1.6.2.msi`.
2. Download and extract `RDPWrap-v1.6.2.zip`.
3. Run Notepad as an Administrator.
4. Open the file located at `C:\Program Files\RDP Wrapper\rdpwrap.ini`.
5. Obtain the latest `rdpwrap.ini` file from GitHub:
   - https://github.com/sebaxakerhtc/rdpwrap.ini/blob/master/rdpwrap.ini
   - https://github.com/BobbyCephy/rdpwrap.ini/blob/master/rdpwrap.ini
6. Replace the content of the local `rdpwrap.ini` file with the content from the GitHub file.
7. Run the `install.bat` file extracted in step 2.
8. Run `RDPConf.exe`, check if it shows **fully supported**, then click **Apply** and **OK**.
9. Go to Windows Services and restart the **Remote Desktop Service**.
10. Test multiple user logins.
