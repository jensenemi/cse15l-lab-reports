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
[cs15lsp23fv@ieng6-202]:folder:418$ grep -c "they" technical/911report/chapter-2.txt
20
```
When using the command ```grep -c``` followed by a string and name of a text file, it prints the number of lines in the specified text file that match the given string. It is useful because it allows us to easily search for how many lines contain the string given.

For the second command-line option, ```-n```:
```
[cs15lsp23fv@ieng6-202]:folder:419$ grep -n "they" technical/911report/preface.txt  
74:                to detail, and readiness to share what they have learned. We have built on the work
93:                the American people and their amazing resilience and courage as they fought back. We
```
```
[cs15lsp23fv@ieng6-202]:folder:423$ grep -n "they" technical/911report/chapter-2.txt
8:                newspaper in London to publish what they termed a fatwa issued in the name of a
12:                declared war against God and his messenger, they called for the murder of any
25:                military or civilian. As far as we are concerned, they are all targets." Note:
28:                the last word in the names by which they are known: Nawaf al Hazmi as Hazmi, for
71:                cyclonic change as they confront modernity and globalization. His rhetoric
157:                Americans have wondered, "Why do 'they' hate us?" Some also ask, "What can we do to
159:            Bin Ladin and al Qaeda have given answers to both these questions. To the first, they
274:                they disagree. Beyond the theology lies the simple human fact that most Muslims,
342:                they received little or no assistance from the United States.
348:                allowed to dissolve. They established what they called a base or foundation (al
384:                Ladin's deputy some years later, when they merged their organizations.
589:                2001, with Bin Ladin's help they re-formed into an organization called Ansar al
623:                Islamic army that he could no longer protect them and that they had to leave the
694:                officers hoped for what they called "strategic depth."
729:                best bet as an ally. When he arrived in Afghanistan, they controlled much of the
825:                and would take assignments for him, but they did not swear bayat and maintained, or
828:                they constituted a potential resource for al Qaeda.
863:                they began to form a plan. Al Qaeda had begun developing the tactical expertise for
915:                civilians; they are all targets in this fatwa."
919:                bombs, and acquired the delivery vehicles. On August 4, they made one last casing
```
When using the command ```grep -n``` followed by a string and name of a text file, it prints the line number as well as the content of the line in the specified text file that matches the given string. It is useful because it gives us information on where to find the string and the content of the line the string is in. 

For the third command-line option, ```-v```:
```
[cs15lsp23fv@ieng6-202]:folder:426$ grep -v "they" technical/911report/preface.txt  

            PREFACE
            We present the narrative of this report and the recommendations that flow from it to
                the President of the United States, the United States Congress, and the American
                people for their consideration. Ten Commissioners-five Republicans and five
                Democrats chosen by elected leaders from our nation's capital at a time of great
                partisan division-have come together to present this report without dissent.
            We have come together with a unity of purpose because our nation demands it.
                September 11, 2001, was a day of unprecedented shock and suffering in the history of
                the United States. The nation was unprepared. How did this happen, and how can we
                avoid such tragedy again?
            To answer these questions, the Congress and the President created the National
                Commission on Terrorist Attacks Upon the United States (Public Law 107-306, November
                27, 2002).
            Our mandate was sweeping. The law directed us to investigate "facts and circumstances
                relating to the terrorist attacks of September 11, 2001," including those relating
                to intelligence agencies, law enforcement agencies, diplomacy, immigration issues
                and border control, the flow of assets to terrorist organizations, commercial
                aviation, the role of congressional oversight and resource allocation, and other
                areas determined relevant by the Commission. In pursuing our mandate, we have
                reviewed more than 2.5 million pages of documents and interviewed more than 1,200
                individuals in ten countries. This included nearly every senior official from the
                current and previous administrations who had responsibility for topics covered in
                our mandate. We have sought to be independent, impartial, thorough, and nonpartisan.
                From the outset, we have been committed to share as much of our investigation as we
                can with the American people. To that end, we held 19 days of hearings and took
                public testimony from 160 witnesses.
            Our aim has not been to assign individual blame. Our aim has been to provide the
                fullest possible account of the events surrounding 9/11 and to identify lessons
                learned.
            We learned about an enemy who is sophisticated, patient, disciplined, and lethal. The
                enemy rallies broad support in the Arab and Muslim world by demanding redress of
                political grievances, but its hostility toward us and our values is limitless. Its
                purpose is to rid the world of religious and political pluralism, the plebiscite,
                and equal rights for women. It makes no distinction between military and civilian
                targets. Collateral damage is not in its lexicon.
            We learned that the institutions charged with protecting our borders, civil aviation,
                and national security did not understand how grave this threat could be, and did not
                adjust their policies, plans, and practices to deter or defeat it. We learned of
                fault lines within our government-between foreign and domestic intelligence, and
                between and within agencies. We learned of the pervasive problems of managing and
                sharing information across a large and unwieldy government that had been built in a
                different era to confront different dangers.
            At the outset of our work, we said we were looking backward in order to look forward.
                We hope that the terrible losses chronicled in this report can create something
                positive-an America that is safer, stronger, and wiser. That September day, we came
                together as a nation. The test before us is to sustain that unity of purpose and
                meet the challenges now confronting us. We need to design a balanced strategy for
                the long haul, to attack terrorists and prevent their ranks from swelling while at
                the same time protecting our country against future attacks. We have been forced to
                think about the way our government is organized. The massive departments and
                agencies that prevailed in the great struggles of the twentieth century must work
                together in new ways, so that all the instruments of national power can be combined.
                Congress needs dramatic change as well to strengthen oversight and focus
                accountability.
            As we complete our final report, we want to begin by thanking our fellow
                Commissioners, whose dedication to this task has been profound. We have reasoned
                together over every page, and the report has benefited from this remarkable
                dialogue. We want to express our considerable respect for the intellect and judgment
                of our colleagues, as well as our great affection for them.
            We want to thank the Commission staff. The dedicated professional staff, headed by
                Philip Zelikow, has contributed innumerable hours to the completion of this report,
                setting aside other important endeavors to take on this all-consuming assignment.
                They have conducted the exacting investigative work upon which the Commission has
                built. They have given good advice, and faithfully carried out our guidance. They
                have been superb. We thank the Congress and the President. Executive branch agencies
                have searched records and produced a multitude of documents for us. We thank
                officials, past and present, who were generous with their time and provided us with
                insight. The PENTTBOM team at the FBI, the Director's Review Group at the CIA, and
                Inspectors General at the Department of Justice and the CIA provided great
                assistance. We owe a huge debt to their investigative labors, painstaking attention
                of several previous Commissions, and we thank the Congressional Joint Inquiry, whose
                fine work helped us get started. We thank the City of New York for assistance with
                documents and witnesses, and the Government Printing Office and W.W. Norton
                & Company for helping to get this report to the broad public.
            We conclude this list of thanks by coming full circle: We thank the families of 9/11,
                whose persistence and dedication helped create the Commission. They have been with
                us each step of the way, as partners and witnesses. They know better than any of us
                the importance of the work we have undertaken.
            We want to note what we have done, and not done. We have endeavored to provide the
                most complete account we can of the events of September 11, what happened and why.
                This final report is only a summary of what we have done, citing only a fraction of
                the sources we have consulted. But in an event of this scale, touching so many
                issues and organizations, we are conscious of our limits. We have not interviewed
                every knowledgeable person or found every relevant piece of paper. New information
                inevitably will come to light. We present this report as a foundation for a better
                understanding of a landmark in the history of our nation.
            We have listened to scores of overwhelming personal tragedies and astounding acts of
                heroism and bravery. We have examined the staggering impact of the events of 9/11 on
                have admired their determination to do their best to prevent another tragedy while
                preparing to respond if it becomes necessary. We emerge from this investigation with
                enormous sympathy for the victims and their loved ones, and with enhanced respect
                for the American people. We recognize the formidable challenges that lie ahead.
            We also approach the task of recommendations with humility. We have made a limited
                number of them. We decided consciously to focus on recommendations we believe to be
                most important, whose implementation can make the greatest difference. We came into
                this process with strong opinions about what would work. All of us have had to
                pause, reflect, and sometimes change our minds as we studied these problems and
                considered the views of others. We hope our report will encourage our fellow
                citizens to study, reflect-and act.
            Thomas H. Kean, chair
            Lee H. Hamilton, vice chair
```
```
[cs15lsp23fv@ieng6-202]:folder:429$ grep -v "they" technical/911report/chapter-2.txt

            THE FOUNDATION OF THE NEW TERRORISM
            A DECLARATION OF WAR
            In February 1998, the 40-year-old Saudi exile Usama Bin Ladin and a fugitive Egyptian
                physician, Ayman al Zawahiri, arranged from their Afghan headquarters for an Arabic
                "World Islamic Front." A fatwa is normally an interpretation of Islamic law by a
                respected Islamic authority, but neither Bin Ladin, Zawahiri, nor the three others
                who signed this statement were scholars of Islamic law. Claiming that America had
                American, anywhere on earth, as the "individual duty for every Muslim who can do it
                in any country in which it is possible to do it."
            
            Three months later, when interviewed in Afghanistan by ABC-TV, Bin Ladin enlarged on
                these themes.
            
            He claimed it was more important for Muslims to kill Americans than to kill other
                infidels." It is far better for anyone to kill a single American soldier than to
                squander his efforts on other activities," he said. Asked whether he approved of
                terrorism and of attacks on civilians, he replied:"We believe that the worst thieves
                in the world today and the worst terrorists are the Americans. Nothing could stop
                you except perhaps retaliation in kind. We do not have to differentiate between
                Islamic names often do not follow the Western practice of the consistent use of
                surnames. Given the variety of names we mention, we chose to refer to individuals by
                instance, omitting the article "al" that would be part of their name in their own
                societies. We generally make an exception for the more familiar English usage of
                "Bin" as part of a last name, as in Bin Ladin. Further, there is no universally
                accepted way to transliterate Arabic words and names into English. We have relied on
                a mix of common sense, the sound of the name in Arabic, and common usage in source
                materials, the press, or government documents. When we quote from a source document,
                we use its transliteration, e.g.,"al Qida" instead of al Qaeda.
            Though novel for its open endorsement of indiscriminate killing, Bin Ladin's 1998
                declaration was only the latest in the long series of his public and private calls
                since 1992 that singled out the United States for attack. In August 1996, Bin Ladin
                had issued his own self-styled fatwa calling on Muslims to drive American soldiers
                out of Saudi Arabia. The long, disjointed document condemned the Saudi monarchy for
                allowing the presence of an army of infidels in a land with the sites most sacred to
                Islam, and celebrated recent suicide bombings of American military facilities in the
                Kingdom. It praised the 1983 suicide bombing in Beirut that killed 241 U.S. Marines,
                the 1992 bombing in Aden, and especially the 1993 firefight in Somalia after which
                the United States "left the area carrying disappointment, humiliation, defeat and
                your dead with you."
            
            Bin Ladin said in his ABC interview that he and his followers had been preparing in
                Somalia for another long struggle, like that against the Soviets in Afghanistan, but
                "the United States rushed out of Somalia in shame and disgrace." Citing the Soviet
                army's withdrawal from Afghanistan as proof that a ragged army of dedicated Muslims
                could overcome a superpower, he told the interviewer: "We are certain that we
                shall-with the grace of Allah-prevail over the Americans." He went on to warn that
                "If the present injustice continues . . . , it will inevitably move the battle to
                American soil."
            
            Plans to attack the United States were developed with unwavering singlemindedness
                throughout the 1990s. Bin Ladin saw himself as called "to follow in the footsteps of
                the Messenger and to communicate his message to all nations," and to serve as the rallying point and organizer of a new kind of war to
                destroy America and bring the world to Islam.
            BIN LADIN'S APPEAL IN THE ISLAMIC WORLD 
            It is the story of eccentric and violent ideas sprouting in the fertile ground of
                political and social turmoil. It is the story of an organization poised to seize its
                historical moment. How did Bin Ladin-with his call for the indiscriminate killing of
                Americans-win thousands of followers and some degree of approval from millions more?
            The history, culture, and body of beliefs from which Bin Ladin has shaped and spread
                his message are largely unknown to many Americans. Seizing on symbols of Islam's
                past greatness, he promises to restore pride to people who consider themselves the
                victims of successive foreign masters. He uses cultural and religious allusions to
                the holy Qur'an and some of its interpreters. He appeals to people disoriented by
                selectively draws from multiple sources-Islam, history, and the region's political
                and economic malaise. He also stresses grievances against the United States widely
                shared in the Muslim world. He inveighed against the presence of U.S. troops in
                Saudi Arabia, the home of Islam's holiest sites. He spoke of the suffering of the
                Iraqi people as a result of sanctions imposed after the Gulf War, and he protested
                U.S. support of Israel.
            Islam Islam (a word that literally means "surrender to the will of God") arose in
                Arabia with what Muslims believe are a series of revelations to the Prophet Mohammed
                from the one and only God, the God of Abraham and of Jesus. These revelations,
                conveyed by the angel Gabriel, are recorded in the Qur'an. Muslims believe that
                these revelations, given to the greatest and last of a chain of prophets stretching
                from Abraham through Jesus, complete God's message to humanity. The Hadith, which
                recount Mohammed's sayings and deeds as recorded by his contemporaries, are another
                fundamental source. A third key element is the Sharia, the code of law derived from
                the Qur'an and the Hadith. Islam is divided into two main branches, Sunni and Shia.
                Soon after the Prophet's death, the question of choosing a new leader, or caliph,
                for the Muslim community, or Ummah, arose. Initially, his successors could be drawn
                from the Prophet's contemporaries, but with time, this was no longer possible. Those
                who became the Shia held that any leader of the Ummah must be a direct descendant of
                the Prophet; those who became the Sunni argued that lineal descent was not required
                if the candidate met other standards of faith and knowledge. After bloody struggles,
                the Sunni became (and remain) the majority sect. (The Shia are dominant in Iran.)
                The Caliphate-the institutionalized leadership of the Ummah-thus was a Sunni
                institution that continued until 1924, first under Arab and eventually under Ottoman
                Turkish control. Many Muslims look back at the century after the revelations to the
                Prophet Mohammed as a golden age. Its memory is strongest among the Arabs. What
                happened then-the spread of Islam from the Arabian Peninsula throughout the Middle
                East, North Africa, and even into Europe within less than a century- seemed, and
                seems, miraculous.
            
            Nostalgia for Islam's past glory remains a powerful force.
            Islam is both a faith and a code of conduct for all aspects of life. For many
                Muslims, a good government would be one guided by the moral principles of their
                faith. This does not necessarily translate into a desire for clerical rule and the
                abolition of a secular state. It does mean that some Muslims tend to be
                uncomfortable with distinctions between religion and state, though Muslim rulers
                throughout history have readily separated the two.
            To extremists, however, such divisions, as well as the existence of parliaments and
                legislation, only prove these rulers to be false Muslims usurping God's authority
                over all aspects of life. Periodically, the Islamic world has seen surges of what,
                for want of a better term, is often labeled "fundamentalism."
            
            Denouncing waywardness among the faithful, some clerics have appealed for a return to
                observance of the literal teachings of the Qur'an and Hadith. One scholar from the
                fourteenth century from whom Bin Ladin selectively quotes, Ibn Taimiyyah, condemned
                both corrupt rulers and the clerics who failed to criticize them. He urged Muslims
                to read the Qur'an and the Hadith for themselves, not to depend solely on learned
                interpreters like himself but to hold one another to account for the quality of
                their observance.
            
            The extreme Islamist version of history blames the decline from Islam's golden age on
                the rulers and people who turned away from the true path of their religion, thereby
                leaving Islam vulnerable to encroaching foreign powers eager to steal their land,
                wealth, and even their souls.
            Bin Ladin's Worldview Despite his claims to universal leadership, Bin Ladin offers an
                extreme view of Islamic history designed to appeal mainly to Arabs and Sunnis. He
                draws on fundamentalists who blame the eventual destruction of the Caliphate on
                leaders who abandoned the pure path of religious devotion.
            
            He repeatedly calls on his followers to embrace martyrdom since "the walls of
                oppression and humiliation cannot be demolished except in a rain of bullets." For those yearning for a lost sense of order in an older,
                more tranquil world, he offers his "Caliphate" as an imagined alternative to today's
                uncertainty. For others, he offers simplistic conspiracies to explain their world.
            Bin Ladin also relies heavily on the Egyptian writer Sayyid Qutb. A member of the
                Muslim Brotherhood executed in 1966 on charges of
                attempting to overthrow the government, Qutb mixed Islamic scholarship with a very
                superficial acquaintance with Western history and thought. Sent by the Egyptian
                government to study in the United States in the late 1940s, Qutb returned with an
                enormous loathing of Western society and history. He dismissed Western achievements
                as entirely material, arguing that Western society possesses "nothing that will
                satisfy its own conscience and justify its existence."
            
            Three basic themes emerge from Qutb's writings. First, he claimed that the world was
                beset with barbarism, licentiousness, and unbelief (a condition he called jahiliyya,
                the religious term for the period of ignorance prior to the revelations given to the
                Prophet Mohammed). Qutb argued that humans can choose only between Islam and
                jahiliyya. Second, he warned that more people, including Muslims, were attracted to
                jahiliyya and its material comforts than to his view of Islam; jahiliyya could
                therefore triumph over Islam. Third, no middle ground exists in what Qutb conceived
                as a struggle between God and Satan. All Muslims-as he defined them-therefore must
                take up arms in this fight. Any Muslim who rejects his ideas is just one more
                nonbeliever worthy of destruction.
            
            Bin Ladin shares Qutb's stark view, permitting him and his followers to rationalize
                even unprovoked mass murder as righteous defense of an embattled faith. Many
                stop these attacks?"
                say that America had attacked Islam; America is responsible for all conflicts
                involving Muslims. Thus Americans are blamed when Israelis fight with Palestinians,
                when Russians fight with Chechens, when Indians fight with Kashmiri Muslims, and
                when the Philippine government fights ethnic Muslims in its southern islands.
                America is also held responsible for the governments of Muslim countries, derided by
                al Qaeda as "your agents." Bin Ladin has stated flatly,"Our fight against these
                governments is not separate from our fight against you."
                These charges found a ready audience among millions of Arabs and Muslims angry at
                the United States because of issues ranging from Iraq to Palestine to America's
                support for their countries' repressive rulers.
            Bin Ladin's grievance with the United States may have started in reaction to specific
                U.S. policies but it quickly became far deeper. To the second question, what America
                could do, al Qaeda's answer was that America should abandon the Middle East, convert
                to Islam, and end the immorality and godlessness of its society and culture:"It is
                saddening to tell you that you are the worst civilization witnessed by the history
                of mankind." If the United States did not comply, it would be at war with the
                Islamic nation, a nation that al Qaeda's leaders said "desires death more than you
                desire life."
            
            History and Political Context Few fundamentalist movements in the Islamic world
                gained lasting political power. In the nineteenth and twentieth centuries,
                fundamentalists helped articulate anticolonial grievances but played little role in
                the overwhelmingly secular struggles for independence after World War I.
                Western-educated lawyers, soldiers, and officials led most independence movements,
                and clerical influence and traditional culture were seen as obstacles to national
                progress. After gaining independence from Western powers following World War II, the
                Arab Middle East followed an arc from initial pride and optimism to today's mix of
                indifference, cynicism, and despair. In several countries, a dynastic state already
                existed or was quickly established under a paramount tribal family. Monarchies in
                countries such as Saudi Arabia, Morocco, and Jordan still survive today. Those in
                Egypt, Libya, Iraq, and Yemen were eventually overthrown by secular nationalist
                revolutionaries.
            The secular regimes promised a glowing future, often tied to sweeping ideologies
                (such as those promoted by Egyptian President Gamal Abdel Nasser's Arab Socialism or
                the Ba'ath Party of Syria and Iraq) that called for a single, secular Arab state.
                However, what emerged were almost invariably autocratic regimes that were usually
                unwilling to tolerate any opposition-even in countries, such as Egypt, that had a
                parliamentary tradition. Over time, their policies- repression, rewards, emigration,
                and the displacement of popular anger onto scapegoats (generally foreign)-were
                shaped by the desire to cling to power.
            The bankruptcy of secular, autocratic nationalism was evident across the Muslim world
                by the late 1970s. At the same time, these regimes had closed off nearly all paths
                for peaceful opposition, forcing their critics to choose silence, exile, or violent
                opposition. Iran's 1979 revolution swept a Shia theocracy into power. Its success
                encouraged Sunni fundamentalists elsewhere. In the 1980s, awash in sudden oil
                wealth, Saudi Arabia competed with Shia Iran to promote its Sunni fundamentalist
                interpretation of Islam, Wahhabism. The Saudi government, always conscious of its
                duties as the custodian of Islam's holiest places, joined with wealthy Arabs from
                the Kingdom and other states bordering the Persian Gulf in donating money to build
                mosques and religious schools that could preach and teach their interpretation of
                Islamic doctrine. In this competition for legitimacy, secular regimes had no
                alternative to offer. Instead, in a number of cases their rulers sought to buy off
                local Islamist movements by ceding control of many social and educational issues.
                Emboldened rather than satisfied, the Islamists continued to push for power-a trend
                especially clear in Egypt. Confronted with a violent Islamist movement that killed
                President Anwar Sadat in 1981, the Egyptian government combined harsh repression of
                Islamic militants with harassment of moderate Islamic scholars and authors, driving
                many into exile. In Pakistan, a military regime sought to justify its seizure of
                power by a pious public stance and an embrace of unprecedented Islamist influence on
                education and society.
            These experiments in political Islam faltered during the 1990s: the Iranian
                revolution lost momentum, prestige, and public support, and Pakistan's rulers found
                that most of its population had little enthusiasm for fundamentalist Islam. Islamist
                revival movements gained followers across the Muslim world, but failed to secure
                political power except in Iran and Sudan. In Algeria, where in 1991 Islamists seemed
                almost certain to win power through the ballot box, the military preempted their
                victory, triggering a brutal civil war that continues today. Opponents of today's
                rulers have few, if any, ways to participate in the existing political system. They
                are thus a ready audience for calls to Muslims to purify their society, reject
                unwelcome modernization, and adhere strictly to the Sharia. Social and Economic
                Malaise In the 1970s and early 1980s, an unprecedented flood of wealth led the then
                largely unmodernized oil states to attempt to shortcut decades of development. They
                funded huge infrastructure projects, vastly expanded education, and created
                subsidized social welfare programs. These programs established a widespread feeling
                of entitlement without a corresponding sense of social obligations. By the late
                1980s, diminishing oil revenues, the economic drain from many unprofitable
                development projects, and population growth made these entitlement programs
                unsustainable. The resulting cutbacks created enormous resentment among recipients
                who had come to see government largesse as their right. This resentment was further
                stoked by public understanding of how much oil income had gone straight into the
                pockets of the rulers, their friends, and their helpers.
            Unlike the oil states (or Afghanistan, where real economic development has barely
                begun), the other Arab nations and Pakistan once had seemed headed toward balanced
                modernization. The established commercial, financial, and industrial sectors in
                these states, supported by an entrepreneurial spirit and widespread understanding of
                free enterprise, augured well. But unprofitable heavy industry, state monopolies,
                and opaque bureaucracies slowly stifled growth. More importantly, these
                state-centered regimes placed their highest priority on preserving the elite's grip
                on national wealth. Unwilling to foster dynamic economies that could create jobs
                attractive to educated young men, the countries became economically stagnant and
                reliant on the safety valve of worker emigration either to the Arab oil states or to
                the West. Furthermore, the repression and isolation of women in many Muslim
                countries have not only seriously limited individual opportunity but also crippled
                overall economic productivity.
            
            By the 1990s, high birthrates and declining rates of infant mortality had produced a
                common problem throughout the Muslim world: a large, steadily increasing population
                of young men without any reasonable expectation of suitable or steady employment-a
                sure prescription for social turbulence. Many of these young men, such as the
                enormous number trained only in religious schools, lacked the skills needed by their
                societies. Far more acquired valuable skills but lived in stagnant economies that
                could not generate satisfying jobs. Millions, pursuing secular as well as religious
                studies, were products of educational systems that generally devoted little if any
                attention to the rest of the world's thought, history, and culture. The secular
                education reflected a strong cultural preference for technical fields over the
                humanities and social sciences. Many of these young men, even if able to study
                abroad, lacked the perspective and skills needed to understand a different culture.
            Frustrated in their search for a decent living, unable to benefit from an education
                often obtained at the cost of great family sacrifice, and blocked from starting
                families of their own, some of these young men were easy targets for radicalization.
            Bin Ladin's Historical Opportunity Most Muslims prefer a peaceful and inclusive
                vision of their faith, not the violent sectarianism of Bin Ladin. Among Arabs, Bin
                Ladin's followers are commonly nicknamed takfiri, or "those who define other Muslims
                as unbelievers," because of their readiness to demonize and murder those with whom
                like most other human beings, are repelled by mass murder and barbarism whatever
                their justification.
            "All Americans must recognize that the face of terror is not the true face of Islam,"
                President Bush observed." Islam is a faith that brings comfort to a billion people
                around the world. It's a faith that has made brothers and sisters of every race.
                It's a faith based upon love, not hate." Yet as
                political, social, and economic problems created flammable societies, Bin Ladin used
                Islam's most extreme, fundamentalist traditions as his match. All these
                elements-including religion-combined in an explosive compound.
            Other extremists had, and have, followings of their own. But in appealing to
                societies full of discontent, Bin Ladin remained credible as other leaders and
                symbols faded. He could stand as a symbol of resistance-above all, resistance to the
                West and to America. He could present himself and his allies as victorious warriors
                in the one great successful experience for Islamic militancy in the 1980s: the
                Afghan jihad against the Soviet occupation.
            By 1998, Bin Ladin had a distinctive appeal, as he focused on attacking America. He
                argued that other extremists, who aimed at local rulers or Israel, did not go far
                enough. They had not taken on what he called "the head of the snake."
            
            Finally, Bin Ladin had another advantage: a substantial, worldwide organization. By
                the time he issued his February 1998 declaration of war, Bin Ladin had nurtured that
                organization for nearly ten years. He could attract, train, and use recruits for
                ever more ambitious attacks, rallying new adherents with each demonstration that his
                was the movement of the future.
            THE RISE OF BIN LADIN AND AL QAEDA (1988-1992)
            A decade of conflict in Afghanistan, from 1979 to 1989, gave Islamist extremists a
                rallying point and training field. A Communist government in Afghanistan gained
                power in 1978 but was unable to establish enduring control. At the end of 1979, the
                Soviet government sent in military units to ensure that the country would remain
                securely under Moscow's influence. The response was an Afghan national resistance
                movement that defeated Soviet forces.
            
            Young Muslims from around the world flocked to Afghanistan to join as volunteers in
                what was seen as a "holy war"-jihad-against an invader. The largest numbers came
                from the Middle East. Some were Saudis, and among them was Usama Bin Ladin.
            Twenty-three when he arrived in Afghanistan in 1980, Bin Ladin was the seventeenth of
                57 children of a Saudi construction magnate. Six feet five and thin, Bin Ladin
                appeared to be ungainly but was in fact quite athletic, skilled as a horseman,
                runner, climber, and soccer player. He had attended Abdul Aziz University in Saudi
                Arabia. By some accounts, he had been interested there in religious studies,
                inspired by tape recordings of fiery sermons by Abdullah Azzam, a Palestinian and a
                disciple of Qutb. Bin Ladin was conspicuous among the volunteers not because he
                showed evidence of religious learning but because he had access to some of his
                family's huge fortune. Though he took part in at least one actual battle, he became
                known chiefly as a person who generously helped fund the anti-Soviet jihad.
            
            Bin Ladin understood better than most of the volunteers the extent to which the
                continuation and eventual success of the jihad in Afghanistan depended on an
                increasingly complex, almost worldwide organization. This organization included a
                financial support network that came to be known as the "Golden Chain," put together
                mainly by financiers in Saudi Arabia and the Persian Gulf states. Donations flowed
                through charities or other nongovernmental organizations (NGOs). Bin Ladin and the
                "Afghan Arabs" drew largely on funds raised by this network, whose agents roamed
                world markets to buy arms and supplies for the mujahideen, or "holy warriors."
            
            Mosques, schools, and boardinghouses served as recruiting stations in many parts of
                the world, including the United States. Some were set up by Islamic extremists or
                their financial backers. Bin Ladin had an important part in this activity. He and
                the cleric Azzam had joined in creating a "Bureau of Services" (Mektab al Khidmat,
                or MAK), which channeled recruits into Afghanistan.
            
            The international environment for Bin Ladin's efforts was ideal. Saudi Arabia and the
                United States supplied billions of dollars worth of secret assistance to rebel
                groups in Afghanistan fighting the Soviet occupation. This assistance was funneled
                through Pakistan: the Pakistani military intelligence service (Inter- Services
                Intelligence Directorate, or ISID), helped train the rebels and distribute the arms.
                But Bin Ladin and his comrades had their own sources of support and training, and
            
            April 1988 brought victory for the Afghan jihad. Moscow declared it would pull its
                military forces out of Afghanistan within the next nine months. As the Soviets began
                their withdrawal, the jihad's leaders debated what to do next. Bin Ladin and Azzam
                agreed that the organization successfully created for Afghanistan should not be
                Qaeda) as a potential general headquarters for future jihad.
            
            Though Azzam had been considered number one in the MAK, by August 1988 Bin Ladin was
                clearly the leader (emir) of al Qaeda. This organization's structure included as its
                operating arms an intelligence component, a military committee, a financial
                committee, a political committee, and a committee in charge of media affairs and
                propaganda. It also had an Advisory Council (Shura) made up of Bin Ladin's inner
                    circle.
            
            Bin Ladin's assumption of the helm of al Qaeda was evidence of his growing
                self-confidence and ambition. He soon made clear his desire for unchallenged control
                and for preparing the mujahideen to fight anywhere in the world. Azzam, by contrast,
                favored continuing to fight in Afghanistan until it had a true Islamist government.
                And, as a Palestinian, he saw Israel as the top priority for the next stage.
            
            Whether the dispute was about power, personal differences, or strategy, it ended on
                November 24, 1989, when a remotely controlled car bomb killed Azzam and both of his
                sons. The killers were assumed to be rival Egyptians. The outcome left Bin Ladin
                indisputably in charge of what remained of the MAK and al Qaeda.
            
            Through writers like Qutb, and the presence of Egyptian Islamist teachers in the
                Saudi educational system, Islamists already had a strong intellectual influence on
                Bin Ladin and his al Qaeda colleagues. By the late 1980s, the Egyptian Islamist
                movement-badly battered in the government crackdown following President Sadat's
                assassination-was centered in two major organizations: the Islamic Group and the
                Egyptian Islamic Jihad. A spiritual guide for both, but especially the Islamic
                Group, was the so-called Blind Sheikh, Omar Abdel Rahman. His preaching had inspired
                the assassination of Sadat. After being in and out of Egyptian prisons during the
                1980s, Abdel Rahman found refuge in the United States. From his headquarters in
                Jersey City, he distributed messages calling for the murder of unbelievers.
            
            The most important Egyptian in Bin Ladin's circle was a surgeon, Ayman al Zawahiri,
                who led a strong faction of the Egyptian Islamic Jihad. Many of his followers became
                important members in the new organization, and his own close ties with Bin Ladin led
                many to think of him as the deputy head of al Qaeda. He would in fact become Bin
            
            Bin Ladin Moves to Sudan By the fall of 1989, Bin Ladin had sufficient stature among
                Islamic extremists that a Sudanese political leader, Hassan al Turabi, urged him to
                transplant his whole organization to Sudan. Turabi headed the National Islamic Front
                in a coalition that had recently seized power in Khartoum.
            
            Bin Ladin agreed to help Turabi in an ongoing war against African Christian
                separatists in southern Sudan and also to do some road building. Turabi in return
                would let Bin Ladin use Sudan as a base for worldwide business operations and for
                preparations for jihad.
            
            While agents of Bin Ladin began to buy property in Sudan in 1990, Bin Ladin himself moved from Afghanistan back to Saudi Arabia. In
                August 1990, Iraq invaded Kuwait. Bin Ladin, whose efforts in Afghanistan had earned
                him celebrity and respect, proposed to the Saudi monarchy that he summon mujahideen
                for a jihad to retake Kuwait. He was rebuffed, and the Saudis joined the U.S.-led
                coalition. After the Saudis agreed to allow U.S. armed forces to be based in the
                Kingdom, Bin Ladin and a number of Islamic clerics began to publicly denounce the
                arrangement. The Saudi government exiled the clerics and undertook to silence Bin
                Ladin by, among other things, taking away his passport. With help from a dissident
                member of the royal family, he managed to get out of the country under the pretext
                of attending an Islamic gathering in Pakistan in April 1991.33 By 1994, the Saudi
                government would freeze his financial assets and revoke his citizenship.
            
            He no longer had a country he could call his own.
            Bin Ladin moved to Sudan in 1991 and set up a large and complex set of intertwined
                business and terrorist enterprises. In time, the former would encompass numerous
                companies and a global network of bank accounts and nongovernmental institutions.
                Fulfilling his bargain with Turabi, Bin Ladin used his construction company to build
                a new highway from Khartoum to Port Sudan on the Red Sea coast. Meanwhile, al Qaeda
                finance officers and top operatives used their positions in Bin Ladin's businesses
                to acquire weapons, explosives, and technical equipment for terrorist purposes. One
                founding member, Abu Hajer al Iraqi, used his position as head of a Bin Ladin
                investment company to carry out procurement trips from western Europe to the Far
                East. Two others, Wadi al Hage and Mubarak Douri, who had become acquainted in
                Tucson, Arizona, in the late 1980s, went as far afield as China, Malaysia, the
                Philippines, and the former Soviet states of Ukraine and Belarus.
            
            Bin Ladin's impressive array of offices covertly provided financial and other support
                for terrorist activities. The network included a major business enterprise in
                Cyprus; a "services" branch in Zagreb; an office of the Benevolence International
                Foundation in Sarajevo, which supported the Bosnian Muslims in their conflict with
                Serbia and Croatia; and an NGO in Baku, Azerbaijan, that was employed as well by
                Egyptian Islamic Jihad both as a source and conduit for finances and as a support
                center for the Muslim rebels in Chechnya. He also made use of the
                already-established Third World Relief Agency (TWRA) headquartered in Vienna, whose
                branch office locations included Zagreb and Budapest. (Bin Ladin later set up an NGO
                in Nairobi as a cover for operatives there.)
            
            Bin Ladin now had a vision of himself as head of an international jihad
                confederation. In Sudan, he established an "Islamic Army Shura" that was to serve as
                the coordinating body for the consortium of terrorist groups with which he was
                forging alliances. It was composed of his own al Qaeda Shura together with leaders
                or representatives of terrorist organizations that were still independent. In
                building this Islamic army, he enlisted groups from Saudi Arabia, Egypt, Jordan,
                Lebanon, Iraq, Oman, Algeria, Libya, Tunisia, Morocco, Somalia, and Eritrea. Al
                Qaeda also established cooperative but less formal relationships with other
                extremist groups from these same countries; from the African states of Chad, Mali,
                Niger, Nigeria, and Uganda; and from the Southeast Asian states of Burma, Thailand,
                Malaysia, and Indonesia. Bin Ladin maintained connections in the Bosnian conflict as
                    well.
            
            The groundwork for a true global terrorist network was being laid.
            Bin Ladin also provided equipment and training assistance to the Moro Islamic
                Liberation Front in the Philippines and also to a newly forming Philippine group
                that called itself the Abu Sayyaf Brigade, after one of the major Afghan jihadist
                    commanders.
            
            Al Qaeda helped Jemaah Islamiya (JI), a nascent organization headed by Indonesian
                Islamists with cells scattered across Malaysia, Singapore, Indonesia, and the
                Philippines. It also aided a Pakistani group engaged in insurrectionist attacks in
                Kashmir. In mid-1991, Bin Ladin dispatched a band of supporters to the northern
                Afghanistan border to assist the Tajikistan Islamists in the ethnic conflicts that
                had been boiling there even before the Central Asian departments of the Soviet Union
                became independent states.
            
            This pattern of expansion through building alliances extended to the United States. A
                Muslim organization called al Khifa had numerous branch offices, the largest of
                which was in the Farouq mosque in Brooklyn. In the mid- 1980s, it had been set up as
                one of the first outposts of Azzam and Bin Ladin's MAK.
            
            Other cities with branches of al Khifa included Atlanta, Boston, Chicago, Pittsburgh,
                and Tucson.
            
            Al Khifa recruited American Muslims to fight in Afghanistan; some of them would
                participate in terrorist actions in the United States in the early 1990s and in al
                Qaeda operations elsewhere, including the 1998 attacks on U.S. embassies in East
                Africa.
            BUILDING AN ORGANIZATION, DECLARING WAR ON THE UNITED STATES
                (1992-1996)
            Bin Ladin began delivering diatribes against the United States before he left Saudi
                Arabia. He continued to do so after he arrived in Sudan. In early 1992, the al Qaeda
                leadership issued a fatwa calling for jihad against the Western "occupation" of
                Islamic lands. Specifically singling out U.S. forces for attack, the language
                resembled that which would appear in Bin Ladin's public fatwa in August 1996. In
                ensuing weeks, Bin Ladin delivered an often-repeated lecture on the need to cut off
                "the head of the snake."
            
            By this time, Bin Ladin was well-known and a senior figure among Islamist extremists,
                especially those in Egypt, the Arabian Peninsula, and the Afghanistan-Pakistan
                border region. Still, he was just one among many diverse terrorist barons. Some of
                Bin Ladin's close comrades were more peers than subordinates. For example, Usama
                Asmurai, also known as Wali Khan, worked with Bin Ladin in the early 1980s and
                helped him in the Philippines and in Tajikistan. The Egyptian spiritual guide based
                in New Jersey, the Blind Sheikh, whom Bin Ladin admired, was also in the network.
                Among sympathetic peers in Afghanistan were a few of the warlords still fighting for
                power and Abu Zubaydah, who helped operate a popular terrorist training camp near
                the border with Pakistan. There were also rootless but experienced operatives, such
                as Ramzi Yousef and Khalid Sheikh Mohammed, who-though not necessarily formal
                members of someone else's organization-were traveling around the world and joining
                in projects that were supported by or linked to Bin Ladin, the Blind Sheikh, or
                their associates.
            
            In now analyzing the terrorist programs carried out by members of this network, it
                would be misleading to apply the label "al Qaeda operations" too often in these
                early years. Yet it would also be misleading to ignore the significance of these
                connections. And in this network, Bin Ladin's agenda stood out. While his allied
                Islamist groups were focused on local battles, such as those in Egypt, Algeria,
                Bosnia, or Chechnya, Bin Ladin concentrated on attacking the "far enemy"-the United
                States.
            Attacks Known and Suspected
            After U.S. troops deployed to Somalia in late 1992, al Qaeda leaders formulated a
                fatwa demanding their eviction. In December, bombs exploded at two hotels in Aden
                where U.S. troops routinely stopped en route to Somalia, killing two, but no
                Americans. The perpetrators are reported to have belonged to a group from southern
                Yemen headed by a Yemeni member of Bin Ladin's Islamic Army Shura; some in the group
                had trained at an al Qaeda camp in Sudan.
            
            Al Qaeda leaders set up a Nairobi cell and used it to send weapons and trainers to
                the Somali warlords battling U.S. forces, an operation directly supervised by al
                Qaeda's military leader.
            
            Scores of trainers flowed to Somalia over the ensuing months, including most of the
                senior members and weapons training experts of al Qaeda's military committee. These
                trainers were later heard boasting that their assistance led to the October 1993
                shootdown of two U.S. Black Hawk helicopters by members of a Somali militia group
                and to the subsequent withdrawal of U.S. forces in early 1994.
            
            In November 1995, a car bomb exploded outside a Saudi-U.S. joint facility in Riyadh
                for training the Saudi National Guard. Five Americans and two officials from India
                were killed. The Saudi government arrested four perpetrators, who admitted being
                inspired by Bin Ladin. They were promptly executed. Though nothing proves that Bin
                Ladin ordered this attack, U.S. intelligence subsequently learned that al Qaeda
                leaders had decided a year earlier to attack a U.S. target in Saudi Arabia, and had
                shipped explosives to the peninsula for this purpose. Some of Bin Ladin's associates
                later took credit.
            
            In June 1996, an enormous truck bomb detonated in the Khobar Towers residential
                complex in Dhahran, Saudi Arabia, that housed U.S. Air Force personnel. Nineteen
                Americans were killed, and 372 were wounded. The operation was carried out
                principally, perhaps exclusively, by Saudi Hezbollah, an organization that had
                received support from the government of Iran. While the evidence of Iranian
                involvement is strong, there are also signs that al Qaeda played some role, as yet
                    unknown.
            
            In this period, other prominent attacks in which Bin Ladin's involvement is at best
                cloudy are the 1993 bombing of the World Trade Center, a plot that same year to
                destroy landmarks in New York, and the 1995 Manila air plot to blow up a dozen U.S.
                airliners over the Pacific. Details on these plots appear in chapter 3.
            Another scheme revealed that Bin Ladin sought the capability to kill on a mass scale.
                His business aides received word that a Sudanese military officer who had been a
                member of the previous government cabinet was offering to sell weapons-grade
                uranium. After a number of contacts were made through intermediaries, the officer
                set the price at $1.5 million, which did not deter Bin Ladin. Al Qaeda
                representatives asked to inspect the uranium and were shown a cylinder about 3 feet
                long, and one thought he could pronounce it genuine. Al Qaeda apparently purchased
                the cylinder, then discovered it to be bogus.
            
            But while the effort failed, it shows what Bin Ladin and his associates hoped to do.
                One of the al Qaeda representatives explained his mission: "it's easy to kill more
                people with uranium."
            
            Bin Ladin seemed willing to include in the confederation terrorists from almost every
                corner of the Muslim world. His vision mirrored that of Sudan's Islamist leader,
                Turabi, who convened a series of meetings under the label Popular Arab and Islamic
                Conference around the time of Bin Ladin's arrival in that country. Delegations of
                violent Islamist extremists came from all the groups represented in Bin Ladin's
                Islamic Army Shura. Representatives also came from organizations such as the
                Palestine Liberation Organization, Hamas, and Hezbollah.
            
            Turabi sought to persuade Shiites and Sunnis to put aside their divisions and join
                against the common enemy. In late 1991 or 1992, discussions in Sudan between al
                Qaeda and Iranian operatives led to an informal agreement to cooperate in providing
                support-even if only training-for actions carried out primarily against Israel and
                the United States. Not long afterward, senior al Qaeda operatives and trainers
                traveled to Iran to receive training in explosives. In the fall of 1993, another
                such delegation went to the Bekaa Valley in Lebanon for further training in
                explosives as well as in intelligence and security. Bin Ladin reportedly showed
                particular interest in learning how to use truck bombs such as the one that had
                killed 241 U.S. Marines in Lebanon in 1983. The relationship between al Qaeda and
                Iran demonstrated that Sunni-Shia divisions did not necessarily pose an
                insurmountable barrier to cooperation in terrorist operations. As will be described
                in chapter 7, al Qaeda contacts with Iran continued in ensuing years.
            
            Bin Ladin was also willing to explore possibilities for cooperation with Iraq, even
                though Iraq's dictator, Saddam Hussein, had never had an Islamist agenda-save for
                his opportunistic pose as a defender of the faithful against "Crusaders" during the
                Gulf War of 1991. Moreover, Bin Ladin had in fact been sponsoring anti-Saddam
                Islamists in Iraqi Kurdistan, and sought to attract them into his Islamic army.
            
            To protect his own ties with Iraq, Turabi reportedly brokered an agreement that Bin
                Ladin would stop supporting activities against Saddam. Bin Ladin apparently honored
                this pledge, at least for a time, although he continued to aid a group of Islamist
                extremists operating in part of Iraq (Kurdistan) outside of Baghdad's control. In
                the late 1990s, these extremist groups suffered major defeats by Kurdish forces. In
                Islam. There are indications that by then the Iraqi regime tolerated and may even
                have helped Ansar al Islam against the common Kurdish enemy.
            
            With the Sudanese regime acting as intermediary, Bin Ladin himself met with a senior
                Iraqi intelligence officer in Khartoum in late 1994 or early 1995. Bin Ladin is said
                to have asked for space to establish training camps, as well as assistance in
                procuring weapons, but there is no evidence that Iraq responded to this
                    request.
            
            As described below, the ensuing years saw additional efforts to establish
                connections.
            Sudan Becomes a Doubtful Haven
            Not until 1998 did al Qaeda undertake a major terrorist operation of its own, in
                large part because Bin Ladin lost his base in Sudan. Ever since the Islamist regime
                came to power in Khartoum, the United States and other Western governments had
                pressed it to stop providing a haven for terrorist organizations. Other governments
                in the region, such as those of Egypt, Syria, Jordan, and even Libya, which were
                targets of some of these groups, added their own pressure. At the same time, the
                Sudanese regime began to change. Though Turabi had been its inspirational leader,
                General Omar al Bashir, president since 1989, had never been entirely under his
                thumb. Thus as outside pressures mounted, Bashir's supporters began to displace
                those of Turabi.
            The attempted assassination in Ethiopia of Egyptian President Hosni Mubarak in June
                1995 appears to have been a tipping point. The would-be killers, who came from the
                Egyptian Islamic Group, had been sheltered in Sudan and helped by Bin Ladin.
            
            When the Sudanese refused to hand over three individuals identified as involved in
                the assassination plot, the UN Security Council passed a resolution criticizing
                their inaction and eventually sanctioned Khartoum in April 1996.
            
            A clear signal to Bin Ladin that his days in Sudan were numbered came when the
                government advised him that it intended to yield to Libya's demands to stop giving
                sanctuary to its enemies. Bin Ladin had to tell the Libyans who had been part of his
                country. Outraged, several Libyan members of al Qaeda and the Islamic Army Shura
                renounced all connections with him.
            
            Bin Ladin also began to have serious money problems. International pressure on Sudan,
                together with strains in the world economy, hurt Sudan's currency. Some of Bin
                Ladin's companies ran short of funds. As Sudanese authorities became less obliging,
                normal costs of doing business increased. Saudi pressures on the Bin Ladin family
                also probably took some toll. In any case, Bin Ladin found it necessary both to cut
                back his spending and to control his outlays more closely. He appointed a new
                financial manager, whom his followers saw as miserly.
            
            Money problems proved costly to Bin Ladin in other ways. Jamal Ahmed al Fadl, a
                Sudanese-born Arab, had spent time in the United States and had been recruited for
                the Afghan war through the Farouq mosque in Brooklyn. He had joined al Qaeda and
                taken the oath of fealty to Bin Ladin, serving as one of his business agents. Then
                Bin Ladin discovered that Fadl had skimmed about $110,000, and he asked for
                restitution. Fadl resented receiving a salary of only $500 a month while some of the
                Egyptians in al Qaeda were given $1,200 a month. He defected and became a star
                informant for the United States. Also testifying about al Qaeda in a U.S. court was
                L'Houssaine Kherchtou, who told of breaking with Bin Ladin because of Bin Ladin's
                professed inability to provide him with money when his wife needed a caesarian
                    section.
            
            In February 1996, Sudanese officials began approaching officials from the United
                States and other governments, asking what actions of theirs might ease foreign
                pressure. In secret meetings with Saudi officials, Sudan offered to expel Bin Ladin
                to Saudi Arabia and asked the Saudis to pardon him. U.S. officials became aware of
                these secret discussions, certainly by March. Saudi officials apparently wanted Bin
                Ladin expelled from Sudan. They had already revoked his citizenship, however, and
                would not tolerate his presence in their country. And Bin Ladin may have no longer
                felt safe in Sudan, where he had already escaped at least one assassination attempt
                that he believed to have been the work of the Egyptian or Saudi regimes, or both. In
                any case, on May 19, 1996, Bin Ladin left Sudan-significantly weakened, despite his
                ambitions and organizational skills. He returned to Afghanistan.
            
            AL QAEDA'S RENEWAL IN AFGHANISTAN (1996-1998)
            Bin Ladin flew on a leased aircraft from Khartoum to Jalalabad, with a refueling
                stopover in the United Arab Emirates.
            
            He was accompanied by family members and bodyguards, as well as by al Qaeda members
                who had been close associates since his organization's 1988 founding in Afghanistan.
                Dozens of additional militants arrived on later flights.
            
            Though Bin Ladin's destination was Afghanistan, Pakistan was the nation that held the
                key to his ability to use Afghanistan as a base from which to revive his ambitious
                enterprise for war against the United States.
            For the first quarter century of its existence as a nation, Pakistan's identity had
                derived from Islam, but its politics had been decidedly secular. The army was-and
                remains-the country's strongest and most respected institution, and the army had
                been and continues to be preoccupied with its rivalry with India, especially over
                the disputed territory of Kashmir.
            From the 1970s onward, religion had become an increasingly powerful force in
                Pakistani politics. After a coup in 1977, military leaders turned to Islamist groups
                for support, and fundamentalists became more prominent. South Asia had an indigenous
                form of Islamic fundamentalism, which had developed in the nineteenth century at a
                school in the Indian village of Deoband.
            
            The influence of the Wahhabi school of Islam had also grown, nurtured by Saudifunded
                institutions. Moreover, the fighting in Afghanistan made Pakistan home to an
                enormous-and generally unwelcome-population of Afghan refugees; and since the badly
                strained Pakistani education system could not accommodate the refugees, the
                government increasingly let privately funded religious schools serve as a cost-free
                alternative. Over time, these schools produced large numbers of half-educated young
                men with no marketable skills but with deeply held Islamic views.
            
            Pakistan's rulers found these multitudes of ardent young Afghans a source of
                potential trouble at home but potentially useful abroad. Those who joined the
                Taliban movement, espousing a ruthless version of Islamic law, perhaps could bring
                order in chaotic Afghanistan and make it a cooperative ally. They thus might give
                Pakistan greater security on one of the several borders where Pakistani military
            
            It is unlikely that Bin Ladin could have returned to Afghanistan had Pakistan
                disapproved. The Pakistani military intelligence service probably had advance
                knowledge of his coming, and its officers may have facilitated his travel. During
                his entire time in Sudan, he had maintained guesthouses and training camps in
                Pakistan and Afghanistan. These were part of a larger network used by diverse
                organizations for recruiting and training fighters for Islamic insurgencies in such
                places as Tajikistan, Kashmir, and Chechnya. Pakistani intelligence officers
                reportedly introduced Bin Ladin to Taliban leaders in Kandahar, their main base of
                power, to aid his reassertion of control over camps near
            Khowst, out of an apparent hope that he would now expand the camps and make them
                available for training Kashmiri militants.
            
            Yet Bin Ladin was in his weakest position since his early days in the war against the
                Soviet Union. The Sudanese government had canceled the registration of the main
                business enterprises he had set up there and then put some of them up for public
                sale. According to a senior al Qaeda detainee, the government of Sudan seized
                everything Bin Ladin had possessed there.
            
            He also lost the head of his military committee, Abu Ubaidah al Banshiri, one of the
                most capable and popular leaders of al Qaeda. While most of the group's key figures
                had accompanied Bin Ladin to Afghanistan, Banshiri had remained in Kenya to oversee
                the training and weapons shipments of the cell set up some four years earlier. He
                died in a ferryboat accident on Lake Victoria just a few days after Bin Ladin
                arrived in Jalalabad, leaving Bin Ladin with a need to replace him not only in the
                Shura but also as supervisor of the cells and prospective operations in East
                    Africa.
            
            He had to make other adjustments as well, for some al Qaeda members viewed Bin
                Ladin's return to Afghanistan as occasion to go off in their own directions. Some
                maintained collaborative relationships with al Qaeda, but many disengaged
                    entirely.
            
            For a time, it may not have been clear to Bin Ladin that the Taliban would be his
                country, but key centers, including Kabul, were still held by rival warlords. Bin
                Ladin went initially to Jalalabad, probably because it was in an area controlled by
                a provincial council of Islamic leaders who were not major contenders for national
                power. He found lodgings with Younis Khalis, the head of one of the main mujahideen
                factions. Bin Ladin apparently kept his options open, maintaining contacts with
                Gulbuddin Hekmatyar, who, though an Islamic extremist, was also one of the Taliban's
                most militant opponents. But after September 1996, when first Jalalabad and then
                Kabul fell to the Taliban, Bin Ladin cemented his ties with them.
            
            That process did not always go smoothly. Bin Ladin, no longer constrained by the
                Sudanese, clearly thought that he had new freedom to publish his appeals for jihad.
                At about the time when the Taliban were making their final drive toward Jalalabad
                and Kabul, Bin Ladin issued his August 1996 fatwa, saying that "We . . . have been
                prevented from addressing the Muslims," but expressing relief that "by the grace of
                Allah, a safe base here is now available in the high Hindu Kush mountains in
                Khurasan." But theTaliban, like the Sudanese, would eventually hear warnings,
                including from the Saudi monarchy.
            
            Though Bin Ladin had promised Taliban leaders that he would be circumspect, he broke
                this promise almost immediately, giving an inflammatory interview to CNN in March
                1997. The Taliban leader Mullah Omar promptly "invited" Bin Ladin to move to
                Kandahar, ostensibly in the interests of Bin Ladin's own security but more likely to
                situate him where he might be easier to control.
            
            There is also evidence that around this time Bin Ladin sent out a number of feelers
                to the Iraqi regime, offering some cooperation. None are reported to have received a
                significant response. According to one report, Saddam Hussein's efforts at this time
                to rebuild relations with the Saudis and other Middle Eastern regimes led him to
                stay clear of Bin Ladin.
            
            In mid-1998, the situation reversed; it was Iraq that reportedly took the initiative.
                In March 1998, after Bin Ladin's public fatwa against the United States, two al
                Qaeda members reportedly went to Iraq to meet with Iraqi intelligence. In July, an
                Iraqi delegation traveled to Afghanistan to meet first with the Taliban and then
                with Bin Ladin. Sources reported that one, or perhaps both, of these meetings was
                apparently arranged through Bin Ladin's Egyptian deputy, Zawahiri, who had ties of
                his own to the Iraqis. In 1998, Iraq was under intensifying U.S. pressure, which
                culminated in a series of large air attacks in December.
            
            Similar meetings between Iraqi officials and Bin Ladin or his aides may have occurred
                in 1999 during a period of some reported strains with the Taliban. According to the
                reporting, Iraqi officials offered Bin Ladin a safe haven in Iraq. Bin Ladin
                declined, apparently judging that his circumstances in Afghanistan remained more
                favorable than the Iraqi alternative. The reports describe friendly contacts and
                indicate some common themes in both sides' hatred of the United States. But to date
                we have seen no evidence that these or the earlier contacts ever developed into a
                collaborative operational relationship. Nor have we seen evidence indicating that
                Iraq cooperated with al Qaeda in developing or carrying out any attacks against the
                United States.
            
            Bin Ladin eventually enjoyed a strong financial position in Afghanistan, thanks to
                Saudi and other financiers associated with the Golden Chain. Through his
                relationship with Mullah Omar-and the monetary and other benefits that it brought
                the Taliban-Bin Ladin was able to circumvent restrictions; Mullah Omar would stand
                by him even when otherTaliban leaders raised objections. Bin Ladin appeared to have
                in Afghanistan a freedom of movement that he had lacked in Sudan. Al Qaeda members
                could travel freely within the country, enter and exit it without visas or any
                immigration procedures, purchase and import vehicles and weapons, and enjoy the use
                of official Afghan Ministry of Defense license plates. Al Qaeda also used the Afghan
                state-owned Ariana Airlines to courier money into the country.
            
            The Taliban seemed to open the doors to all who wanted to come to Afghanistan to
                train in the camps. The alliance with theTaliban provided al Qaeda a sanctuary in
                which to train and indoctrinate fighters and terrorists, import weapons, forge ties
                with other jihad groups and leaders, and plot and staff terrorist schemes. While Bin
                Ladin maintained his own al Qaeda guesthouses and camps for vetting and training
                recruits, he also provided support to and benefited from the broad infrastructure of
                such facilities in Afghanistan made available to the global network of Islamist
                movements. U.S. intelligence estimates put the total number of fighters who
                underwent instruction in Bin Ladin-supported camps in Afghanistan from 1996 through
                9/11 at 10,000 to 20,000.
            
            In addition to training fighters and special operators, this larger network of
                guesthouses and camps provided a mechanism by which al Qaeda could screen and vet
                candidates for induction into its own organization. Thousands flowed through the
                camps, but no more than a few hundred seem to have become al Qaeda members. From the
                time of its founding, al Qaeda had employed training and indoctrination to identify
                "worthy" candidates.
            
            Al Qaeda continued meanwhile to collaborate closely with the many Middle Eastern
                groups-in Egypt, Algeria, Yemen, Lebanon, Morocco, Tunisia, Somalia, and
                elsewhere-with which it had been linked when Bin Ladin was in Sudan. It also
                reinforced its London base and its other offices around Europe, the Balkans, and the
                Caucasus. Bin Ladin bolstered his links to extremists in South and Southeast Asia,
                including the Malaysian-Indonesian JI and several Pakistani groups engaged in the
                Kashmir conflict.
            
            The February 1998 fatwa thus seems to have been a kind of public launch of a renewed
                and stronger al Qaeda, after a year and a half of work. Having rebuilt his
                fund-raising network, Bin Ladin had again become the rich man of the jihad movement.
                He had maintained or restored many of his links with terrorists elsewhere in the
                world. And he had strengthened the internal ties in his own organization.
            The inner core of al Qaeda continued to be a hierarchical top-down group with defined
                positions, tasks, and salaries. Most but not all in this core swore fealty (or
                bayat) to Bin Ladin. Other operatives were committed to Bin Ladin or to his goals
                tried to maintain, some autonomy. A looser circle of adherents might give money to
                al Qaeda or train in its camps but remained essentially independent. Nevertheless,
            
            Now effectively merged with Zawahiri's Egyptian Islamic Jihad, al Qaeda promised to become the general headquarters for international
                terrorism, without the need for the Islamic Army Shura. Bin Ladin was prepared to
                pick up where he had left off in Sudan. He was ready to strike at "the head of the
                snake." Al Qaeda's role in organizing terrorist operations had also changed. Before
                the move to Afghanistan, it had concentrated on providing funds, training, and
                weapons for actions carried out by members of allied groups. The attacks on the U.S.
                embassies in East Africa in the summer of 1998 would take a different form-planned,
                directed, and executed by al Qaeda, under the direct supervision of Bin Ladin and
                his chief aides.
            The Embassy Bombings As early as December 1993, a team of al Qaeda operatives had
                begun casing targets in Nairobi for future attacks. It was led by Ali Mohamed, a
                former Egyptian army officer who had moved to the United States in the mid-1980s,
                enlisted in the U.S. Army, and became an instructor at Fort Bragg. He had provided
                guidance and training to extremists at the Farouq mosque in Brooklyn, including some
                who were subsequently convicted in the February 1993 attack on the World Trade
                Center. The casing team also included a computer expert whose write-ups were
                reviewed by al Qaeda leaders.
            
            The team set up a makeshift laboratory for developing their surveillance photographs
                in an apartment in Nairobi where the various al Qaeda operatives and leaders based
                in or traveling to the Kenya cell sometimes met. Banshiri, al Qaeda's military
                committee chief, continued to be the operational commander of the cell; but because
                he was constantly on the move, Bin Ladin had dispatched another operative, Khaled al
                Fawwaz, to serve as the on-site manager. The technical surveillance and
                communications equipment employed for these casing missions included
                state-of-the-art video cameras obtained from China and from dealers in Germany. The
                casing team also reconnoitered targets in Djibouti.
            
            As early as January 1994, Bin Ladin received the surveillance reports, complete with
                diagrams prepared by the team's computer specialist. He, his top military committee
                members-Banshiri and his deputy, Abu Hafs al Masri (also known as Mohammed Atef)-and
                a number of other al Qaeda leaders reviewed the reports. Agreeing that the U.S.
                embassy in Nairobi was an easy target because a car bomb could be parked close by,
                such attacks months earlier, when some of its operatives-top military committee
                members and several operatives who were involved with the Kenya cell among them-were
                sent to Hezbollah training camps in Lebanon.
            
            The cell in Kenya experienced a series of disruptions that may in part account for
                the relatively long delay before the attack was actually carried out. The
                difficulties Bin Ladin began to encounter in Sudan in 1995, his move to Afghanistan
                in 1996, and the months spent establishing ties with the Taliban may also have
                played a role, as did Banshiri's accidental drowning. In August 1997, the Kenya cell
                panicked. The London Daily Telegraph reported that Madani al Tayyib, formerly head
                of al Qaeda's finance committee, had turned himself over to the Saudi government.
                The article said (incorrectly) that the Saudis were sharing Tayyib's information
                with the U.S. and British authorities.
            
            At almost the same time, cell members learned that U.S. and Kenyan agents had
                searched the Kenya residence of Wadi al Hage, who had become the new on-site manager
                in Nairobi, and that Hage's telephone was being tapped. Hage was a U.S.citizen who
                had worked with Bin Ladin in Afghanistan in the 1980s, and in 1992 he went to Sudan
                to become one of al Qaeda's major financial operatives. When Hage returned to the
                United States to appear before a grand jury investigating Bin Ladin, the job of cell
                manager was taken over by Harun Fazul, a Kenyan citizen who had been in Bin Ladin's
                advance team to Sudan back in 1990. Harun faxed a report on the "security situation"
                to several sites, warning that "the crew members in East Africa is [sic] in grave
                danger" in part because "America knows . . . that the followers of [Bin Ladin] . . .
                carried out the operations to hit Americans in Somalia." The report provided
                instructions for avoiding further exposure.
            
            On February 23, 1998, Bin Ladin issued his public fatwa. The language had been in
                negotiation for some time, as part of the merger under way between Bin Ladin's
                organization and Zawahiri's Egyptian Islamic Jihad. Less than a month after the
                publication of the fatwa, the teams that were to carry out the embassy attacks were
                being pulled together in Nairobi and Dar es Salaam. The timing and content of their
                instructions indicate that the decision to launch the attacks had been made by the
                time the fatwa was issued.
            
            The next four months were spent setting up the teams in Nairobi and Dar es Salaam.
                Members of the cells rented residences, and purchased bomb-making materials and
                transport vehicles. At least one additional explosives expert was brought in to
                assist in putting the weapons together. In Nairobi, a hotel room was rented to put
                up some of the operatives. The suicide trucks were purchased shortly before the
                attack date.
            
            While this was taking place, Bin Ladin continued to push his public message. On May
                7, the deputy head of al Qaeda's military committee, Mohammed Atef, faxed to Bin
                Ladin's London office a new fatwa issued by a group of sheikhs located in
                Afghanistan. A week later, it appeared in Al Quds al Arabi, the same Arabic-language
                newspaper in London that had first published Bin Ladin's February fatwa, and it
                conveyed the same message-the duty of Muslims to carry out holy war against the
                enemies of Islam and to expel the Americans from the Gulf region. Two weeks after
                that, Bin Ladin gave a videotaped interview to ABC News with the same slogans,
                adding that "we do not differentiate between those dressed in military uniforms and
            
            By August 1, members of the cells not directly involved in the attacks had mostly
                departed from East Africa. The remaining operatives prepared and assembled the
                run at the embassy in Nairobi. By the evening of August 6, all but the delivery
                teams and one or two persons assigned to remove the evidence trail had left East
                Africa. Back in Afghanistan, Bin Ladin and the al Qaeda leadership had left Kandahar
                for the countryside, expecting U.S. retaliation. Declarations taking credit for the
                attacks had already been faxed to the joint al Qaeda-Egyptian Islamic Jihad office
                in Baku, with instructions to stand by for orders to "instantly" transmit them to Al
                Quds al Arabi. One proclaimed "the formation of the Islamic Army for the Liberation
                of the Holy Places," and two others-one for each embassy-announced that the attack
                had been carried out by a "company" of a "battalion" of this "Islamic Army."
            
            On the morning of August 7, the bomb-laden trucks drove into the embassies roughly
                five minutes apart-about 10:35 A.M. in Nairobi and 10:39 A.M. in Dar es Salaam.
                Shortly afterward, a phone call was placed from Baku to London. The previously
                prepared messages were then faxed to London.
            
            The attack on the U.S. embassy in Nairobi destroyed the embassy and killed 12
                Americans and 201 others, almost all Kenyans. About 5,000 people were injured. The
                attack on the U.S. embassy in Dar es Salaam killed 11 more people, none of them
                Americans. Interviewed later about the deaths of the Africans, Bin Ladin answered
                that "when it becomes apparent that it would be impossible to repel these Americans
                without assaulting them, even if this involved the killing of Muslims, this is
                permissible under Islam." Asked if he had indeed masterminded these bombings, Bin
                Ladin said that the World Islamic Front for jihad against "Jews and Crusaders" had
                issued a "crystal clear" fatwa. If the instigation for jihad against the Jews and
                the Americans to liberate the holy places "is considered a crime,"he said,"let
                history be a witness that I am a criminal."
```
While using the command ```grep -v``` followed by a string and name of a text file, it prints the lines that don't have the specified string in them. It is useful because it gives us the content of the text file that doesn't match the pattern/string. 

For the last command-line option, ```-w```:
```
[cs15lsp23fv@ieng6-202]:folder:430$ grep -w "they" technical/911report/preface.txt
                to detail, and readiness to share what they have learned. We have built on the work
                the American people and their amazing resilience and courage as they fought back. We
```
```
[cs15lsp23fv@ieng6-202]:folder:431$ grep -w "they" technical/911report/chapter-2.txt
                newspaper in London to publish what they termed a fatwa issued in the name of a
                declared war against God and his messenger, they called for the murder of any
                military or civilian. As far as we are concerned, they are all targets." Note:
                the last word in the names by which they are known: Nawaf al Hazmi as Hazmi, for
                cyclonic change as they confront modernity and globalization. His rhetoric
                Americans have wondered, "Why do 'they' hate us?" Some also ask, "What can we do to
            Bin Ladin and al Qaeda have given answers to both these questions. To the first, they
                they disagree. Beyond the theology lies the simple human fact that most Muslims,
                they received little or no assistance from the United States.
                allowed to dissolve. They established what they called a base or foundation (al
                Ladin's deputy some years later, when they merged their organizations.
                2001, with Bin Ladin's help they re-formed into an organization called Ansar al
                Islamic army that he could no longer protect them and that they had to leave the
                officers hoped for what they called "strategic depth."
                best bet as an ally. When he arrived in Afghanistan, they controlled much of the
                and would take assignments for him, but they did not swear bayat and maintained, or
                they constituted a potential resource for al Qaeda.
                they began to form a plan. Al Qaeda had begun developing the tactical expertise for
                civilians; they are all targets in this fatwa."
                bombs, and acquired the delivery vehicles. On August 4, they made one last casing
```

When using the command ```grep -w``` followed by a string and name of a text file, it prints out the lines that contain only the string and not the lines where the string may be part of another word. For example, the string following the command is "they," which means ```grep -w``` will not include lines that have "they're," but only "they." This is useful for when a person wants to search for lines containing a certain word that may be likely to be a part of other words that they don't care about. 
