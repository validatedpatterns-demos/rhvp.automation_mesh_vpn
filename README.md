# Ansible Collection - rhvp.automation_mesh_vpn

This collection implements mechanism to install both AAP Automation Mesh and OpenVPN. This is to enable Valdiated
Patterns to run on hardware nodes (in addition to the OpenShift pattern component running in public cloud).

This collection has the following main uses:
1. Install automation mesh nodes on AAP 2.5+.
2. Install an OpenVPN VPN server
3. Install OpenVPN clients.
4. Build a minimalistic PKI for the OpenVPN Server and Clients. It does not support CRL or other long-term
   features that are really needed for practical management of a VPN. The goal of this component is to provide
   the PKI features that OpenShift needs with just openssl.
