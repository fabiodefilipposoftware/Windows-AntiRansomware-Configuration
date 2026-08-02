# Windows-AntiRansomware-Configuration
This is my configuration for hardening Windows against Ransomware.

## ⚠️WARNING⚠️!

<strong>AFTER THIS SETUP, YOU WILL LIKELY NOT BE ABLE TO INSTALL NEW SOFTWARE. INSTALL ALL YOUR SOFTWARE BEFORE APPLYING THESE CHANGES!</strong>

<strong>WHILE I'VE PERSONALLY TESTED THESE SETTINGS SUCCESSFULLY, IT'S POSSIBLE YOUR SYSTEM COULD BECOME UNSTABLE. I TAKE NO RESPONSIBILITY; PERFORM THESE CHANGES AT YOUR OWN RISK! USE THIS IN PRODUCTION OR TEST THIS IN VIRTUAL MACHINE ENVIRONMENT</strong>

## INSTRUCTIONS:

1. Run super-hardening.bat script as Administrator;
  
2. Run regedit;

3. For each single key in list below click with the right button of mouse, click on Permissions", click on "Advanced", on "Permissions" panel select "Users", YOURUSERNAME and "Administrators" (ONLY PRE-EXISTING USERS), "Disable inheritance", then click on "Modify" and disable the "Full control" authorization (LEAVING "READ-ONLY" ENABLED), click on "OK", "Apply" and "OK";

* HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run

* HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\RunOnce

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services

* HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Tracing\RASAPI32

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\SafeBoot

* HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced

* HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\Approved

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Browser Helper Objects

* HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\URLSearchHooks

* HKEY_CURRENT_USER\Environment

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows

* HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\SystemCertificates\ROOT\Certificates

* HKEY_CURRENT_USER\Software\Microsoft\SystemCertificates\ROOT\Certificates

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print\Monitors

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\NetworkProvider\Order

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Active Setup\Installed Components\

* HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies

* HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\AppCertDLLs

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Drivers32

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\Windows Error Reporting\RuntimeExceptionHelperModules

* HKEY_CLASSES_ROOT\http\shell\open\command

* HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Protocols\Handler

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Setup\OOBE

* HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\App Paths

4. Reboot the system;

