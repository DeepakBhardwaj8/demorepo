# demorepo
This repo contains the keywords which needed to be filtered out from the LineDump Qapp output. So, the we will have usable data to analyze.

The keywords will be on the basis of EXCEL default string regex capabilities.

Special Characters are: # @ * -

To skip the special character, you need to use escape character i.e square bracket. So, if you want to match # , you should use [#]. Same is the case for other special characters.

To have partial match you can use below example:-

"interface GigabitEthernet1/0/1" >>>>> this will be matched by "interface *"

"ip prefix-list Cisco" >>>>> this will be matched by "* prefix-list *"
