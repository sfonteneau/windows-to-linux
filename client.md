# windows-to-linux — replacements

| usage | solution | note |
|---|---|---|
| Domain join | sssd | https://samba.tranquil.it/doc/fr/samba_config_client-client_join_clients_linux.html |
| BitLocker | lvm + LUKS (backup key in AD `msFVE-RecoveryInformation` via script) | 
| LAPS | automatic password rotation script + write to AD | https://wapt.tranquil.it/store/fr/tis-laps |
| Network drive (non-admin) | smbnetfs | https://doc.ubuntu-fr.org/smbnetfs |
| RDP | xrdp / RustDesk | https://doc.ubuntu-fr.org/xrdp |
| Certificate enrollment | CEP/CES openSUSE (todo: TPM attestation) | https://github.com/openSUSE/cepces |
| SRP / AppLocker | fapolicyd / AppArmor | |
| Smartcard login (PKINIT) | wapt package | https://wapt.tranquil.it/store/fr/tis-sssd-pkinit
| Printer connect (non-admin) | not found |
