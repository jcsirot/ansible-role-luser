<!-- THIS IS A GENERATED FILE, DO NOT EDIT -->

manage authorized user accounts.

## Supported Platforms

  * Debian

## Variables

| Name | Values | Default | Description |
|------|--------|---------|-------------|
| user_authorized_users | (list) |  | list of authorized users among all users |
| luser_locked_root | true, false | False | if yes, this must be the last playbook action if the current user is root |
| luser_all_users | (list) |  | list of all managed users |
| luser_path | (path) |  | local directory containing all <user>.pub and <user>.sudoers files |

*— Generated by © [Arb](http://github.com/fclaerho/arb) on 2015-07-08 16:50:06.384578 —*