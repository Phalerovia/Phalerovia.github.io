# CiberNetics



![](/CiberNetics.png)

CiberNetics is a competition designed to introduce beginners to Red VS Blue Team competitions.

In this competition team of two people will compete with each other with the goal of gathering 
all the flags in the other team's server, while protecting their own flag. 

## Ciber Netics

Will start from May 29 and will last for as long as I can make it last.
2 Teams with 2 player in each team will compete with each other for one hour a day.
Those teams that can make it will compete other can be a spectator, or do their own thing
The teams will be rotate until everyone has a chance to work one a new person at least two times
Once they have worked with someone at least once, each player will have their own score count
If everything goes well, then high scoring player will be paired with low scoring player, and second high scoring player will be paired with second low scoring player and final bracket will be announced.

## Points

If you have more flags then you win
If you get a one hidden super flag then even if the other teams has more flags, the team with the hidden super flag wins
The super secret flag will be known to the teams, and they need to do their best to protect it. Other flag location, and how to get them will not be disclosed.

## Notes

If the teams are stuck and don't know what they are doing I will poke into their server and exploit stuffs, to keep the competition fun.

# Q and A 

* **Do you know what we are doing yet because I have no clue?**

You will be given a SSH key, two server IP's one where you ssh into
and another that you are supposed to attack
You will need to protect your server while also attacking the other IP
Other team will get your server IP, and they will be attacking your server while trying to protect their server

* **I have basic Linux knowledge but never done one of these before, is that a problem?**

It's okay if you are beginner, we are here to learn
If you guys are stuck i will come by and aid both teams 

* **I take it defending is just setting up permissions correctly?**

and attacking is trying to exploit bad permissions
Yup, and see if there are any vulnerable services running, and patching it

* **What if you delete all services?**

There will a script in place to check your service, your points will be deducted based on the amount of time the service is down

* **What if I accidentally delete the service?**

You will need to re-configure the service and get it to how it was before.
So make sure you don't delete any services that's necessary

* **How will I know those services?**

You will be given the list of services that needs to be up.

* **How do I even attack the server?**

If you have no idea how to attack the server, I will have a quick video of how to get into a server.

* **How long will it last for?**

One hour or until one of the server is completely hacked.

* **How will the server be completely hacked?**

If the other person get's the biggest flag assigned to you.

* **What are the flags?**

There will be important informations in your server that you need to protect, and one of them will be of the highest value. 

* **What if I remove the flag in my server so that other can't get it?**

If the flag is removed is the same thing as other team getting it.
I can ssh into the server after it's over and see if the flag are still there.
Ways to claim other teams flag is by removing them, or copying it and sending it to me and telling me where you found it.

* **How would I know if it's a flag?**

It will be in a unique format, and you will know once you see it.
I will tell you the flag that has the highest value.

* **Will there be malware on the system?**

Yes, maybe, probably, who knows 

* **How will we protect the malware from pivoting to our system?**

There will only be beacons on the server, which doesn't really have any power to pivot to your system. 

* **How do we hack? Will be HTB style? CTF style?**

There's no limitation or restriction on how you will attack, you can use tools like metaspolit to see if you can find any old vuln services already running on the system.
You can craft your own script.
First thing I would recommend everyone doing is doing a quick nmap scan.
There will probably be vulnerable services or vulnerable webservers
That you can exploit and get reverse shells
There might even be some binary exploitation that you can leverage for your attack


