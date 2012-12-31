The main Crowbar repositories have moved from the dellcloudedge org
to the crowbar org on Github.

The repositories in the dellcloudedge org have been kept behind strictly
for legacy purposes

To use the repos on the Crowbar org, you can use the dev tool to add
a new remote for the crowbar org and set it as the highest-priority remote:

./dev remote add https://github.com/crowbar
./dev remote priority dellcloudedge 15
./dev remote priority crowbar 5



