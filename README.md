# no-iprefresh
NO-IP Client to update IP

1o. Create a file called settings.py with the following content

USERNAME = "username"
PASSWORD = "password"
HOSTNAMES = ["hostname.ddns.net"]


CRONTAB every 3 hours

0 */3 * * * /home/pi/.local/bin/pipenv run python /home/pi/Workspace/no-iprefresh/noiprefresh.py
