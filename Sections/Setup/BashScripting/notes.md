- automate day to day job
- host name change in vm by - vi /etc/hosts
  - Example: 127.0.1.1 scriptbox scriptbox

## scripting

- `#!/bin/bash` - it tells open interpreter run the following commands
- `echo` - prints
- `yum` dependency mirror issue fixed by https://serverfault.com/questions/904304/could-not-resolve-host-mirrorlist-centos-org-centos-7
- #!/bin/bash - put this at initial line
- to enable numer line: press : then `se:nu`
- goto first line - gg
- copy and past - `yy then p`

## variables:

- `SKILL = "Devops"
    echo $SKILL
`

* Things that changes you can declare var and reuse it.
* Command line arg `filename.sh Linux AWS`
  - $0 = filename
  - $1 = Linux
  - $2 = AWS
  - note: we can go upto 9
  - system variables - check later

## Quotes

    * single quotes remove special meaning
    * put \ to print the value as it is example `\$9` will print $9

## command substitution

    * VarName=`some operation`

## Exporting Variables

    * /etc/profile - for everyone
    * ./bashrc or./profile - for specific user
    * export NAME=MATHAN
    * $NAME

## If Condition

    * if [$? -eq 0]

## Script for Monitoring

    * echo $?
    * crontab -e
        * for schduling the task to run at particular time

## loops

    * `for value in list
        do
        #code
        done`

## Remote execution

    * inside vm trying to access other vm
    * using the username and password set for the other VM machine
    * other way ssh
