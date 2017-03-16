## Carbon Black Enterprise Protection (Bit9) Content Pack with Pipeline Rules

This is a fork of dubsout's original [Carbon Black Enterprise Protection (Bit9) Content Pack](https://github.com/dubsout/graylog-carbonblack-enterpriseprotection).

It includes additional Pipeline Rules for detecting ransomware and various threats, which were based on ion-storm's [Graylog_Sysmon](https://github.com/ion-storm/Graylog_Sysmon/tree/master/Pipelines) project.

Loading the content pack will spawn inputs on UDP port 11005, correctly parse incoming  Carbon Black Enterprise Protection messages, and create a handy dashboard for viewing info at a glance.
