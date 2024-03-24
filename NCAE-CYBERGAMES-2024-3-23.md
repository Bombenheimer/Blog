# NCAE Cybergames CTF:
Today, I participated in a CTF competition and finished in 2nd place with my other 7 teammates (See below). It was high stress indeed, and probably the most interesting part was when we accidentaly leaked our password list my making our google document public so that the red team also saw it. We did get locked out of our servers a few times but we got them back by sending a 45 second video of some of our team members dancing to give us our passwords back. Another interesting thing was when the red team decided to change some of our servers language and keboard locales to German and we had to change it back. But, it was a great experience and one of my teammates gave me a monitor to use so I will be able to finally make a homelab as soon as I get an AC cable to power the monitor.

The competion involves protecting your systems as well as completing capture the flags for points. The harder capture the flags will be more worth points while the servers that are harder to keep online will also be worth more points as well. Because we were able to complete a lot of CTFs, we won by a mere 13 points to win 2nd place past Westchester. We are competing against other blue teams like us to keep our servers online while the red team (who are more expereinced) must poke hole in our systems and put them back online when they take them off. The black team are there to give us guidence, but ironically the red team were actually more helpful.

With that being said, we definitely got cooked indeed even though we came in second place. But I did take away some VERY important things about cybersecurity from this competition:

<br>

<br>

- ***"The most secure servers are ones that make it persistently difficult for attackers to penetrate"***

I really did walk into the competietion thinking that because of the knowledge we've gained from the NCAE training videos and simulations that our team have done and with the scripts that we've made, I really expected that we would crush the competition and make it even difficult for the red team to breach our servers and turn off our services, but that didn't happen. So I think one factor that contributed to us actually making it to the top 3 was our persistence in keeping our services online for as long as we could to where red team caught on to this and started poking more holes at us. Security is not about making systems impenetrable (which is practically impossible), but rather about raising the bar high enough to deter attackers and make their efforts as difficult and time-consuming as possible. No attacker wants to expend all of their resources as even an attacker's resources are limited as well (unless the attacker in question is a state-sponsored attacker who stops at nothing to attack one server). This would make their efforts futile to where it would be more profitable to go for the "low hanging fruit" of systems, as most cybercrime is driven by the intention to make money

<br>

- ***"A sys admin has to be correct every time, but an attacker has to be right only once"***

The bitter truth that security experts must face is that, in the grand scheme of things, we will have to assume that an attacker ALWAYS has the possibility or means to create a successful attack. Systems are complex, intergrated, and interconnected with one another in such a way that there are constant threats evolving to poke at these systems and we constantly have to be on alert to them as systems become more and more advanced. This means that we have to analayze various attack vectors which can be extensive, while the attacker can find a vulnerablility for at least one of these vectors to become successful

<br>

- ***"The one time they are correct will determine the longevity of your server or business"***

This ringed true for us the entire competition as much as the second point throughout the entire competition. Some teams like us had to send dancing videos to the red team to regain control of their servers again, but that does make me wonder about businesses and organizations that aren't so lucky to be able to do that. Even when the red team took over my shell server, I had created a backup user that had root permissions. If I had been able to change my root password fast enougth and kill all processes then I would have been able to regain control. So in that case it was very nice to have a backup A single successful breach can have significant consequences for an organization, ranging from financial losses and reputational damage to legal and regulatory repercussions. Therefore, having proper incident response plans, secure backups, and business continuity measures is crucial for minimizing the impact of security incidents and ensuring the resilience of the business.

<br>

<br>

So yeah, the competition was a nice expereince and I actually want to participate in more of them. Maybe I will when I become a Junior and actually have more time to dedicate myself to the team.

### UP NEXT: Creating my first Homelab with a mini pc!

<details>
<summary> Team Members </summary>
  <ul>
    <li>Edgar Quinones, Team Captain</li>
    <li>Alex Ramudo, Network Security Administrator</li>
    <li>Geo Archbold, Web Security Specialist</li>
    <li>Bruce Smith (me), Systems Security Engineer</li>
    <li>Jacob Lee, CTF Coordinator / Security Analyst</li>
    <li>Froylan Tellez, Backup and Recovery Specialist</li>
    <li>Delali Simpson, DNS Security Specialist</li>
    <li>Chastity Bythwood, Researcher / Documentation Specialist</li>
  </ul>
</details>
