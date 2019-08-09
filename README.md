# ansible-role-postfix

Not Ready to use!

Ansible Role for Postfix version 3

The following Postfix Typs  are tested

- [] Internet Site
  - [] hash access test
  - [] hash canonical test
  - [] hash generic
  - [] hash transport
- [] Internet with Smarthost
  - [] hash access test
  - [] hash canonical test
  - [] hash generic
  - [] hash transport
- [x] Satellite System (just the base . Not sasl)
  - [] SASL Auth
  - [] hash access test
  - [] hash canonical test
  - [] hash generic
  - [] hash transport
- [] Advanced Backends
- [] Internet Site
  - [] Postgresql
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
  - [] LDAP
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
  - [] mysql
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
  - [] Postgresql
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
- [] Internet with Smarthost
  - [] LDAP
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
  - [] mysql
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
- [] Satellite System
  - [] LDAP
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
  - [] mysql
    - [] virtual alias maps
    - [] virtual domain maps
    - [] virtual groups
    - [] virtual users
    - [] virtual mailbox maps
    - [] virtual relocated
    - [] virtual mailbox limits
    - [] virtual recipients
- [] local only
- [] Manage /etc/aliases
- [] Include external Roles
  - [] Role for IMAP Dovecot
  - [] Role for IMAP cyrus
  - [] Antispam AMaViS
  - [] Antispam Spamassasin
  - [] Antispam Razor
  - [] Antispam Pyzor
  - [] Security DKIM
  - [] Security Clamav

Next ToDo

- [] Use external role for explezit Services
- [] Add SASL because just working currently as a local open Satellite System

## User Beckend und tabels

- alias = local email alias and mailman alias information.
- relocated = relocated user email address maps
- transport = default mail transport information for all domains you are hosting
- users = all user account information
- virtual = virtual domain email alias maps
