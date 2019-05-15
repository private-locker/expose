# Expose (Bash SSH HoneyPot script)
Private-Locker's SSH HoneyPot

This project is to display Fail2Ban Logs of the SSH Port Jail on a HTML page that displays
where they are located (GeoIP) and with a Clickable Whois Lookup link.

## Usage:
./expose

## Dependencies:
- Python
- Webserver (NGINX/Apache/httplightd)

## Recommended Setup:
- Use a seperate user account with no access to any directories but their home folder.
- Set Website to look for new users Home folder and use a directory in there to host the
website.
- Limit your connection rate to the Web Service to prevent DDoS attacks on the displaying 
website.
