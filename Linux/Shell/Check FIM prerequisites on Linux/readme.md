Use this script to check for the following prerequisites:

'auditd' is present and in running state
'never,task' rule does not exist in the audit subsystem
'auditd' is in non-immutable state
Following packages and commands are present in case SELinux is enabled in enforcing or permissive mode
SELinux packages
  policycoreutils-python
  policycoreutils
  libselinux-utils
Commands
  checkmodule
  semodule_package
  semodule
  sestatus
  getenforce
