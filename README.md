# SambaSetup
For future me, how not to waste half day on Linux -> Windows 10 Samba setup.  

1. Run > Secpol.msc

then I set Local Policies > Security Options > Network Security: LAN Manager authentication level to 'Send NTLMv2 response only. Refuse LM & NTLM

2. smb.conf
