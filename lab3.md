# Lab Report 3

## Researching Commands
### Source: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
For the command ```grep```, here are some alternate command-line options:
- ```-c```
- ```-n```
- ```-v```
- ```-w```

For the first command-line option, ```-c```:
```
[cs15lsp23fv@ieng6-202]:folder:417$ grep -c "they" technical/911report/preface.txt
2
```
```
[cs15lsp23fv@ieng6-202]:folder:418$ grep -c "they" technical/911report/chapter-3.txt
79
```
When using the command ```grep -c``` followed by a string and name of a text file, it prints the number of lines in the specified text file that match the given string. It is useful because it allows us to easily search for how many lines contain the string given.

For the second command-line option, ```-n```:
```
[cs15lsp23fv@ieng6-202]:folder:419$ grep -n "they" technical/911report/preface.txt  
74:                to detail, and readiness to share what they have learned. We have built on the work
93:                the American people and their amazing resilience and courage as they fought back. We
```
```
[cs15lsp23fv@ieng6-202]:folder:420$ grep -n "they" technical/911report/chapter-3.txt
12:                agencies, and how they adapted to a new kind of terrorism.
85:                Pakistan, where they discussed bombing targets in the United States and assembled a
101:                although they continued to pursue such investigations, planning or hoping for later
105:                analyzing facts to see if they could provide clues to terrorist tactics more
147:                to spend much energy on matters over which they had no control and for which they
204:                the Counterterrorist Center, they identified one small fragment as part of a timing
270:                community information they were expected to analyze. The poor state of the FBI's
301:                Watson that they did not have the analysts, linguists, or technically trained
330:                they would not improperly exploit that process for their criminal cases. Whether the
388:            There were other legal limitations. Both prosecutors and FBI agents argued that they
423:                determining how to deal with them when they appeared at ports of entry. By 1998, 97
456:                told us they were not even aware that when they checked the names of incoming
457:                passengers against the automated watchlist, they were checking in part for
458:                terrorists. In general, border inspectors also did not have the information they
484:                they had little to gain from having a full-time representative on a JTTF.
509:                lead role in addressing terrorism because they were asked to do so.
532:                and onboard security-was seriously flawed prior to 9/11. Taken together, they did
550:                reviewed daily intelligence, and what they did see was screened for them. She was
571:                Prescreening System) designed to identify passengers whose profile suggested they
604:                metal detectors. Even when small knives were detected by secondary screening, they
616:                carriers had seen the enlightened hand of self-interest with respect to safety, they
635:                aircraft, "Even if you make a vault out of the door, if they have a noose around my
686:            As they are housed in the Defense Department, these agencies are keenly attentive to
826:                taken most of the blame, saying they had done so in order to preserve the
861:                Apart from their own peers, they looked for approval and guidance to policymakers.
871:                they wrote their estimates, even in brief papers, they could draw on a deep base of
876:                longer felt they could afford such a patient, strategic approach to long-term
923:                officers: that is, they were suited for traditional agent recruitment or for
953:                managers in the intelligence community often responded that they had meager
998:                military could object if they thought the State Department was setting national
1051:                constantly challenged by the problem of terrorism, for they handled visas for travel
1143:                state governors, they provided support to civilian agencies to assess the nature of
1238:                directives, differently labeled by each president. For President Clinton, they were
1268:                they strike at home or abroad." In February, he sent Congress proposals to extend
1325:                all forms of terrorism: to capture terrorists, no matter where they hide; to work
1355:                begun to wage war on us, a declaration that they did not acknowledge publicly. Not
1690:                Americans, Richardson asked the Taliban to expel Bin Ladin. They answered that they
1707:                residence at the time, Tarnak Farms. After the Afghan tribals reported that they had
1716:                sleep. Working with the tribals, they drew up plans for the raid. They ran two
1730:                "Sooner or later," they said, "Bin Ladin will attack U.S. interests, perhaps using
1739:            The CIA planners conducted their third complete rehearsal in March, and they again
1754:                about 40 percent.) Although the tribals thought they could pull off the raid, if the
1757:                [tribals] prove as good (and as lucky) as they think they will be."
1780:                have wanted something on paper to show that they were not acting on their own.
1846:                operatives and agents. And they had reason to worry about failure: millions of
1869:                Gore later added his thanks to those of Tenet, both making clear that they spoke
1939:                believed that they had received a similar verdict independently, though they and
1989:                too aggressive. The Sudanese denied that al Shifa produced nerve gas, and they
1997:                "that they were going to get crap either way, so they should do the right
1998:                    thing." All his aides testified to us that they based
2016:                that they were viewed as alarmists even within the CIA. A National Intelligence
2020:                Ladin, whom they had been trying to capture and bring to trial. Documents at the
2130:                aggressive." The future, they warned, might bring "horrific attacks," in which case
2140:                to the Taliban, and also to Sudan, that they would be held directly responsible for
2141:                any attacks on Americans, wherever they occurred, carried out by the Bin Ladin
2142:                network as long as they continued to provide sanctuary to it.
2241:                advice, President Clinton invited Sharif to Washington, where they talked mostly
2273:                been used as "described on paper" but added that they were used in other ways or in
2512:                    whether they are related to attacks on aircraft. A Bin Ladin associate in Sudan
2518:                        package in Malaysia. One told his colleague in Malaysia that "they" were in
2555:                options. Special Operations Forces were later told that they might be ordered to
2574:                they discussed was the potential collateral damage-the number of innocent bystanders
2591:                hit the Habash mosque and 'offend' Muslims." He commented that they had not shown
2604:                than a roadside ambush because they would have better control, it would be less
2609:                tribals more latitude. The intention was to say that they could use lethal force if
2613:                capture operation. The tribals were to be paid only if they captured Bin Ladin, not
2614:                if they killed him. Officials throughout the government approved this draft. But on
2623:                seemed clear they had reached). The Justice Department lawyer who worked on the
2646:                or his lieutenants if they surrendered. Finally, the tribals would not be paid if
2653:                law and be treated humanely. The CIA officer reported that the tribals said they
2657:                they wanted to prove that their standards of behavior were more civilized than those
2659:                the tribals noted that if they were to adopt Bin Ladin's ethics,"we would have
2660:                finished the job long before," RESPONSES TO AL QAEDA'S INITIAL ASSAULTS 133 but they
2681:                Alliance as had just been given to the tribals: they could kill Bin Ladin if a
2698:                authority for CIA's sources to engage in direct action, they have shown no
2833:                which they thought complicated and risky. Such efforts would have required bases in
2868:                nations and because they believed the public would not support it. Cruise missiles
2956:                them to be good reporters-few believed they would carry out an ambush of Bin Ladin.
3006:                decision came back that they should stand down, not shoot, the officer said,"we all
```
