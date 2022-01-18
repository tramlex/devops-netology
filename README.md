1) Local .terraform directories

2) .tfstate files

3) Crash log files

4) Exclude all .tfvars files, which are likely to contain sentitive data, such as
   password, private keys, and other secrets. These should not be part of version
   control as they are data points which are potentially sensitive and subject
   to change depending on the environment.

5) Ignore override files as they are usually used to override resources locally and so
   are not checked in

6) Ignore CLI configuration files
