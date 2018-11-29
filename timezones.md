# Configure Timezones

## List times zones
`sudo timedatectl list-timezones`

## Set timezones
`sudo timedatectl set-timezone region/timezone`
Example: `sudo timedatectl set-timezone America/New_York`

## Recheck
`sudo timedatectl`

# NTP

## Download NTP
`sudo yum install ntp`

## Start and enable NTP
- `sudo systemctl start ntpd`
- `sudo systemctl enable ntpd`
