# ansible-ftb
Ansible resources for setting up Feed The Beast modpack servers

# usage
Either use one of the server playbooks directly with the given
playbooks, or copy one of them and adapt it to your needs.

Currently there are two playbooks

  - infinity - for FTB Infinity pack
  - regrowth - for the Regrowth pack

To make use of the gentoo-java role, you'll need to download
the oracle 1.7 jre manually and put the tar.gz file in the
roles/gentoo-java/files/ directory.
