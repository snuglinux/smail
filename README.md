smail - BASH script to send emails via SMTP SSL.

addmail - script to generate the configuration file. For more details, run the command: addmail -v

smail - a script to send emails from the console. For more details, run the command: smail -v

Warning: The user from whom the message will be sent must be in the "mail" group.

You can verify script execution from another user by running the command in the console:
su - bareos -c "smail -f=test@ukr.net -t=test@ukr.net -s=Test"

The project site: https://snuglinux.pp.ua
