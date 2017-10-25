# Cloudera-CDH-Kerberos

```
ldapsearch -H ldap://<LDAP_url> -b DC=<sub>,DC=<sub>,DC=COM -D <user>@<domain> -W "samaccountname=<WindowsLogin?>"

export KRB5_TRACE=/dev/stdout

kinit -V
```
