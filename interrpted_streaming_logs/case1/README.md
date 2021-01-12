The entire streaming is for a 300 second video so it should last 5 mins. </br>
Client nfd log - 5 mins because streaming stopped midway while downloading the 52nd segment of 1.5Mbps quality. </br>
Router nfd log - log for 11 mins within which client was streaming. </br>
Server repo log - The repo log consists of all logs yesterday. The time on server node is 7 hrs behind client node. So, in the log one should look at 16:11:39 and the next 5 minutes approximately </br>
NOTE: Client & Router VMs are logging in UTC and server on MST, thus 7 hrs behind on their date & time settings so while looking at the logs we should/are looking at the following timestamps: </br>
CLIENT STREAMING: 4 Jan 2021 23:11:39 - 23:16:39 </br>
ROUTER NODE: 4 Jan 2021 23:10:39 - 23:21:39 </br>
SERVER NODE: 4 Jan 2021 16:11:39 - 16:16:39 </br>
