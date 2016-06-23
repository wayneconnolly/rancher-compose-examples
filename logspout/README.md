# Logspout Usage

This compose file will
 - Pull all containers again  (io.rancher.container.pull_image: always)
 - Deploy container to all hosts (io.rancher.scheduler.global: true)
 
# Configuration
 - Replace the X's with the appropriate details (syslog://logsX.papertrailapp.com:XXXXX)
 - Make sure that all containers do not start with "tty: true" from docker-compose and "-t" from docker run commands.
 
# Sign up for free papertrailapp.com account
 - www.papertrailapp.com
