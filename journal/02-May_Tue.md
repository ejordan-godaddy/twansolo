!important
gdphotodna
icinga2 break up cpanel into many DCs
- How does ohp do this same task?
- Just requires us to change the variable that's being pulled in modules/monitoring/templates/icinga2/config.yaml.erb

# GOALS

- Stream my work - day 1
- 1 commit /day

## Team interactions & Notes

- Worked with jbj on illumio issues connecting to HPERF outbound on 80 in cpanel.  Issues might be with DNS lookup and added the ip address to test.
- Queried matkinson about how I'm going to setup their puppet hieradata to account for the new cpanel icinga2 stuff

## Jira Notes

- SREH-5378 need to fix my aws creds and sync with MWP to deploy
- SREH-5300 should be a bot that looks for newly retired hosts in the cpanel/mwp api
- Moved status of SREH-5396 but I'll need to make a proper place for documenting that project
