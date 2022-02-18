The Ansible role to automate the replascement of Self-Signed certtificates by CA signed.

The role exposes HPE iLO API based on redfish.

Role tasks structure:

1. Generate CSR on the target iLO
2. Obtain CSR from the iLO
3. Issue CA signed Certificate based on the CSR
4. Import CA signed Certificate into an iLO