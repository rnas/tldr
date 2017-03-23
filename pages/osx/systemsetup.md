# systemsetup

<<<<<<< HEAD
> Configure System Preferences machine settings

- Enable remote login (SSH)

`systemsetup -setremotelogin on`

- Specify TimeZone, NTP Server and enable network time

`systemsetup -settimezone {{US/Pacific}}`
`systemsetup -setnetworktimeserver {{us.pool.ntp.org}}`
`systemsetup -setusingnetworktime on`

- Make the machine never sleep; restart on freeze & power failure

`systemsetup -setsleep off`
`systemsetup -setrestartpowerfailure on`
`systemsetup -setrestartfreeze on`

- List valid startup disks, specify a new startup disk

`systemsetup -liststartupdisks`
=======
> Configure System Preferences machine settings.

- Enable remote login (SSH):

`systemsetup -setremotelogin on`

- Specify TimeZone, NTP Server and enable network time:

`systemsetup -settimezone {{US/Pacific}} -setnetworktimeserver {{us.pool.ntp.org}} -setusingnetworktime on`

- Make the machine never sleep and automatically restart on power failure or kernel panic:

`systemsetup -setsleep off -setrestartpowerfailure on -setrestartfreeze on`

- List valid startup disks:

`systemsetup -liststartupdisks`

- Specify a new startup disk:

>>>>>>> upstream/master
`systemsetup -setstartupdisk {{path}}`
