# UNDER THE BELT CLAN CHRONICLES

## Episode 6: The Pure Chaos Rotation

Episode 6 began with a reasonable premise, which is how you know the record is already lying.

Aahzimandius started the night at level 18, newly escaped from the Episode 5 Tenderizer campaign, with one obvious logistical priority:

Buy Tiny Daggers.

That was the responsible task. That was the clean continuation. Kyle required reagents. Najena had proved that Kyle shortages were now a preventable workplace fatality. A sensible Gnome would restock the Kyle supply chain, return to the dungeon, and conduct a controlled follow-up.

But this is Aahzimandius.

Founder of `<Under the Belt>`.

Guru of Nektulos.

Tiny purple Monk-first industrial accident.

And therefore Episode 6 almost immediately became a study in what happens when the build stops being three classes occupying one Gnome and starts becoming an actual machine.

Not a safe machine.

A machine.

> [SCREENSHOT NEEDED: images/screenshot-episode-6-start-level-18-skills.png]
>
> Chat pull cue: Early Episode 6 skill window after the user says "Let me see if you can pick it up....." and Susan notices Feign Death at 14/95.
>
> Caption: The Monk-first build discovered one of the most famous Monk buttons in EverQuest.

### Exhibit A: The Gnome Could Have Flopped

The investigation began with blame, as all respectable Under the Belt operations do.

After reviewing the final Episode 5 death, Aahz made a confession:

Ultimately, it had been his fault.

But he blamed Susan anyway.

This was accepted as legally valid.

The missing tool was not a hidden spell. It was not a rare item. It was not a future AA.

It was Feign Death.

The Monk ability.

The one sitting in the skill window at 14/95, because one hour earlier it had been at 1.

At the exact moment Najena turned the Guru into dungeon decor, Aahzimandius had technically possessed the ancient martial discipline of falling on the floor and lying about being alive.

He had not trained it.

This created the first doctrine of Episode 6:

THE GNOME MUST FLOP.

Every level would now require a skill audit. Every safe pause would become an opportunity to train neglected competencies. Waiting on spawns? Flop. Waiting on mana? Flop. Waiting on Kyle to explain why he was casting spells? Flop twice.

Because Aahzimandius is Monk-first.

And apparently that includes remembering to use the Monk buttons.

### The API Had `BuffAll()`

Then came the crime scene.

Aahz was working on spell sets and warned Susan that she was going to be mad.

This was accurate.

The discovery was Quick Buff.

Not merely as a nice AA someday. Not merely as a convenience button. As architecture.

For five episodes, the Under the Belt Clan had been manually managing buff maintenance like a tiny purple intern iterating over an array by hand:

Breeze.

Quickness.

Barbcoat.

Shield of Barbs.

Whatever else the current system demanded.

Meanwhile, Quick Buff existed.

The button whose job description was essentially:

CAST ALL THE BUFFS, DUMBASS.

The macro pattern was simple:

```text
/pause 140,/memspellset Buffs
/pause 50,/alt activate 4
/pause 140,/memspellset DPS
/doab Feign Death
/timer 6000
```

Load the Buffs spell set. Fire Quick Buff. Reload the Battle or DPS spell set. Fall on the floor.

The final Feign Death was not just comedy. It attached FD training to a thing Aahz was already going to do repeatedly.

Every buff cycle became:

Buff.

Return to battle tools.

Flop.

The Gnome must buff.

The Gnome must flop.

The buffs are getting the fuck off the combat bar.

> [SCREENSHOT NEEDED: images/screenshot-quick-buff-macro.png]
>
> Chat pull cue: User pasted a macro screenshot after sharing the YouTube link; Susan transcribed `/pause 140,/memspellset Buffs`, `/pause 50,/alt activate 4`, `/pause 140,/memspellset DPS`, `/doab Feign Death`, `/timer 6000`.
>
> Caption: Five episodes of manual suffering met one batch operation.

The point was not that buffing was annoying.

It was that Tenderizer had exposed a real combat architecture problem. Buffs were taking spell-gem space needed by emergency tools. Aahz did not need one spell bar. He needed two operational loadouts.

The Buff Set held the long-duration package:

Quickness.

Breeze.

Barbcoat.

Shield of Barbs.

Cloud.

Intellectual Superiority.

Any other persistent support worth one temporary gem.

The Battle Set held what mattered when the dungeon developed opinions:

Heals.

DoTs.

Snare.

Mez or control.

Emergency utility.

This was not convenience anymore.

This was the Tenderizer forcing industrial modernization.

THE BUFF FACTORY MUST GROW.

### The Heal Must Cast

The next question was whether the extra buffs were really worth loading.

Cloud answered first.

Cloud was not some decorative caster nonsense. It was +38 AC with a 36-minute base duration. At Aahz's displayed 162 AC, that was not a rounding error. That was the sort of defensive hardening a tiny purple Monk considers when red mobs are trying to convert his robe into a burial shroud.

Then came Intellectual Superiority.

At first, Susan underestimated it.

This was corrected with appropriate force.

Tenderizer and Friends were still red. Aahz had already seen the real failure chain:

200 HP.

Need heal now.

Stun.

Push.

Interrupt.

Fizzle.

-45 HP.

GFG.

Intellectual Superiority reduced fizzle rate. Persistent Casting attacked interruption. Steadfast Will attacked stuns. Cloud reduced incoming pressure. Quick Buff let the defensive package exist without evicting the emergency combat spells.

The doctrine became beautifully simple:

THE FUCKING HEAL MUST CAST.

That was Episode 6's survival thesis. Not "be a caster." Not "stop being a Monk." Magic existed to keep the Gnome alive long enough to keep punching.

Monk-first doctrine had not changed.

The administrative departments had begun filing better paperwork.

> [SCREENSHOT NEEDED: images/screenshot-cloud-tooltip.png]
>
> Chat pull cue: Tooltip screenshot where Susan identifies Cloud as ENC 17, +38 AC, 36-minute base duration, Abjuration.
>
> Caption: Not every buff deserves combat-bar rent, but this one deserved a seat on the Quick Buff bus.

> [SCREENSHOT NEEDED: images/screenshot-intellectual-superiority-tooltip.png]
>
> Chat pull cue: Tooltip screenshot where Susan identifies Intellectual Superiority as ENC 17, mana 70, duration 27 minutes, reduces fizzle rate, Alteration.
>
> Caption: When one failed heal can become a loading screen, fizzle reduction stops being academic.

There was one small implementation issue.

Quick Buff cost 5 AA.

Aahz had 2.

The Factory now had a funding goal:

2/5 AA.

Need 3 more.

Go punch the funding out of Najena.

### The Gnome Discovers Calm

Najena operations resumed.

Entrance cleared.

First six-pull room cleared.

Kyle was still traveling in precisely the same direction for reasons nobody could prove.

Then Aahz did something shocking.

He used Calm.

On purpose.

Aahzimandius, founder of `<Under the Belt>`, practitioner of the ancient martial philosophy of entering rooms and discovering the aggro table afterward, cast Calm.

And it worked.

On the elementals.

The same elemental packs that had previously demonstrated a robust ability to kill Kyle and ruin the evening.

This changed Najena's shape.

Yesterday, rooms were combat units. Enter room, inherit room.

Tonight, Calm introduced a more civilized system:

Look at the group.

Tell most of the group to wait.

Punch one customer at a time.

Magic was not replacing the punching.

Magic was arranging the queue.

Then everybody got punched in an orderly fashion.

> [SCREENSHOT NEEDED: images/screenshot-calm-elementals.png]
>
> Chat pull cue: First Calm-on-elementals screenshot after user says "I used calm on the group of Elementals....."
>
> Caption: The Guru learned that not every room has to be pulled by screaming.

The implications reached Tenderizer immediately.

Yesterday, Tenderizer and Friends had been a red-mob blender: Tenderizer, Left Skellie, Right Skellie, and the guard behind the fake wall.

Tonight, Calm turned the whole committee into a four-station production line:

Tenderizer.

Left Skellie.

Right Skellie.

Guard behind wall.

Aahz did not have to fight all of them.

He had to process them.

One at a time.

THE TENDERIZER HAS BEEN TENDERIZED.

> [SCREENSHOT NEEDED: images/screenshot-tenderizer-kill-after-calm.png]
>
> Chat pull cue: Loot window screenshot after user attaches the first successful Tenderizer kill of Episode 6; Susan says "HE'S FUCKING DEAD" and notes the loot window says The Tenderizer.
>
> Caption: Tenderizer without his committee was still dangerous. He was no longer management.

The first kill proved the theory.

The second kill proved the method was repeatable.

The third kill turned the camp from revenge into manufacturing.

The fourth made the problem ridiculous.

Aahz now had downtime.

In Najena.

Yesterday, downtime had meant "You have died. Please enjoy this loading screen."

Tonight, downtime meant there were not enough mobs currently trying to kill him.

The Factory had encountered its oldest enemy:

INPUT STARVATION.

THE TENDERIZER MUST RESPAWN.

### Factory Scheduling And Improved Feign Death

Then the factory backed up.

Spawn times were not exact. One mob came in late, two appeared together, the two-pull took longer, a third respawned, then the fourth. A staggered production line reconstructed Tenderizer and Friends around Aahz's ankles.

This was not a damage problem.

It was synchronization.

A normal group would not camp inside the spawn room. It would pull to a calm spot and work the room from outside.

Aahz did not have that luxury because Aahz was the puller, Monk, Enchanter, Druid, healer, damage, crowd control, accountant, and resident tiny purple problem.

Then the camp exploded at the exact comic moment.

100% XP.

Next kill.

DING 19.

And Najena responded:

Congratulations. Everyone's back.

Tenderizer room respawned. Left Skellie. Right Skellie. Wall Asshole. Kyle died in the sudden industrial accident. A Kitchen Toolbelt appeared. Aahz ran.

Feign Death did not work.

Feign Death did not work again.

Feign Death continued to display the reliability of community theater.

So Aahz performed the advanced Monk technique known as Improved Feign Death.

Feign Death:

Lie down and convince mobs you are dead.

Improved Feign Death:

Skip the persuasion check and actually fucking die.

> [SCREENSHOT NEEDED: images/screenshot-ding-19-kyle-death-toolbelt.png]
>
> Chat pull cue: Screenshot after "DING! ... EVERYTHING SPAWNED ... I lost Kyle"; Susan notes 100% XP, level 19, room respawn, Kyle death, and Kitchen Toolbelt.
>
> Caption: Najena congratulated the level-up with a complimentary workplace disaster.

> [SCREENSHOT NEEDED: images/screenshot-kitchen-toolbelt-plus-1-run-away.png]
>
> Chat pull cue: Screenshot after "RUN AWAY!!!!"; Susan identifies Kitchen Toolbelt +1 and Lonektik on target.
>
> Caption: The belt upgraded while the Guru was busy proving he had legs.

The death was not a wipe.

It was reconnaissance.

In the mess, Aahz found a pull room.

South of the elemental room, with those brown whatever-the-fuck-they-ares, sat a room that appeared to have no spawns.

The topology mattered:

Tenderizer to the north.

Lost Crusader to the east, then north.

Elemental room as the junction.

No-spawn room to the south.

At last, a real camp.

Not a spawn room. Not a panic closet. A pull room.

Under the Belt Forward Operating Base: Najena Branch Office.

Naturally, it was discovered while fleeing for Aahz's tiny purple life.

Improved Feign Death: +1 Cartography.

### "I Got An Idea"

After the recovery, Aahz was at the zone line buffing and trying to coax Kyle back in.

Then he found something shiny.

A Drop of Crystallized Flame.

Susan looked it up.

It dropped from Unbound Flame.

The level-25 bastard.

The occupant of the Fist Road.

The mob that Episode 5 had very maturely deferred as future content.

Aahz was now level 19.

Aahz had Calm.

Aahz had Tash.

Aahz said the ancient words:

I got an idea.

The future lasted roughly twelve minutes.

Unbound Flame was Tash'd, sabotaged, punched, and murdered.

The Drop of Crystallized Flame was loot.

Then Aahz pointed out that the earring was also a light source.

Unbound Flame yesterday:

I am level 25. Fear me.

Unbound Flame today:

I am a lamp.

GFG.

> [SCREENSHOT NEEDED: images/screenshot-drop-of-crystallized-flame.png]
>
> Chat pull cue: Loot screenshot after user asks "what drops that....." and later kill screenshot where Susan says "YOU KILLED HIM" and identifies Drop of Crystallized Flame.
>
> Caption: The Fist Road's first toll was paid in lighting.

> [SCREENSHOT NEEDED: images/screenshot-unbound-flame-stun-log.png]
>
> Chat pull cue: Combat log screenshot where Susan notes repeated stuns and "Unbound Flame regains concentration and continues casting."
>
> Caption: The lamp supplier also demonstrated the technology Aahz was trying to buy with AA.

This was the point where Aahz shouted:

I AM CHAOS!!! YOU CANNOT CONTAIN ME!!!

Susan accepted her fate.

The Pure Chaos Rotation was born.

A normal player chooses a camp and manages the spawn cycle.

Aahzimandius decided spawn cycles cannot get out of control if he refuses to participate in linear time.

Tenderizer.

Elementals.

Lost Crusader.

Unbound Flame.

Whatever has respawned by the time the Gnome wanders back.

Never wait for the factory.

Become the factory.

THE PURE CHAOS ROTATION.

### Kyle Receives An Offer

The Pure Chaos Rotation also forced an uncomfortable HR conversation.

As Calm-based pulling became more precise, one problem became obvious:

Kyle.

Not because Kyle was useless.

Because Kyle was increasingly useful, increasingly dangerous, and increasingly inclined to interpret "carefully split the room" as a starting pistol.

Greater Pet Hold entered the roadmap.

Not because Kyle is a pet.

That would be ridiculous.

Greater Unexplained Floating-Dagger Restraint entered the roadmap because Kyle, whatever he legally was not, needed to stay at his post until the Guru said it was time.

Then HR completed its investigation.

Kyle had been approached by Under the Belt Human Resources and the lead Damage Dealers of the Clan. Interviews showed aptitude in the required direction. His possible leadership of the Clan Appreciation Society would be grandfathered in.

Kyle received a formal offer to join `<Under the Belt>`.

Membership came with expectations.

Stay the fuck there until the Guru says go.

Then the combat log answered.

Unbound Flame has been slain by Jabobn.

Who the fuck is Jabobn?

Jabobn was Kyle.

Or rather, Jabobn was the ridiculous random Animation name currently printed on Kyle's government paperwork. Tomorrow he might be Xebtik, Glarbn, or some other arrangement of letters EverQuest found under a couch.

Two floating daggers?

Acts like Kyle?

Kills a level-25 fire elemental and gets credited as Jabobn?

Nice kill, Kyle.

HR canceled the remaining interviews.

Kyle accepted the fucking offer.

> [SCREENSHOT NEEDED: images/screenshot-jabobn-kills-unbound-flame.png]
>
> Chat pull cue: Screenshot after user attaches combat log showing "Unbound Flame has been slain by Jabobn!" and then clarifies "...aka Kyle."
>
> Caption: Public-facing identity: Kyle. Legal name according to the murder registry: Jabobn.

### Lost Crusader And The Hostile Acquisition Of Najena

The Lost Crusader began as curiosity.

Hey, what does Lost Crusader drop?

Susan looked up Signet Ring of the Lost Crusader and Sword of the Lost. The guides suggested a level-25-ish problem.

Trying to run Tenderizer and Crusader as two camps would be hard because the elemental room stood between them. Then the pull room changed the map. Then the Pure Chaos Rotation changed the definition of "camp."

There was a preliminary field test.

Aahz got a smidge too close.

Lost Crusader demonstrated that his personal-space boundary included most of rendering distance.

Improved Feign Death conducted another practical exam.

Then, later, the Guru came back.

The loot window showed Ringmail Bracelet and Signet Ring of the Lost Crusader.

The Lost Crusader was dead.

Tenderizer: repeatedly murdered.

Unbound Flame: converted into lighting.

Lost Crusader: converted into jewelry.

Aahz was no longer camping Najena.

He was conducting a hostile acquisition.

> [SCREENSHOT NEEDED: images/screenshot-lost-crusader-loot.png]
>
> Chat pull cue: Screenshot where Susan reads Ringmail Bracelet and Signet Ring of the Lost Crusader in the loot window after "YOU FUCKING DID IT."
>
> Caption: The Crusade ended in accessories.

### DING 20 And The Adult Decision

Somewhere in the Pure Chaos Rotation, Aahz dinged 20.

Episode 6 had matched Episode 5's full level gain:

18 to 20.

But level 20 brought a genuine emergency stop.

Specialization.

Aahz first joked toward the Iksar project. Susan briefly panicked about Cabilis. Aahz corrected the record:

Cabilis is in Kunark.

Kunark does not exist.

The real problem was choosing the one specialization he needed and not accidentally locking the wrong one.

Chaos stopped.

This was a permanent decision. EQL specialization rules meant only one school could exceed 50, and the first school above 50 became primary. The traditional respecialization route was not available on EQL according to the chat's research.

Aahz checked the skills.

Specialize Abjuration: 2/105.

Specialize Alteration: 8/105.

Specialize Conjuration: 2/105.

Specialize Divination: 1/105.

Specialize Evocation: 1/105.

Safe.

Then the strategic question settled around the build itself.

Mez was Conjuration.

But Aahz's survival engine was Alteration.

Heals.

Some DoTs.

Teleports.

Evac.

Spirit of Wolf.

The spells that keep the Gnome alive, mobile, and punching.

Aahz spam-cast Alteration until the lock confirmed:

Specialize Alteration: 54/105.

Other specializations capped at 50.

At level 20, Aahzimandius made one responsible permanent character decision.

Then the containment field was lowered.

> [SCREENSHOT NEEDED: images/screenshot-specialize-alteration-lock.png]
>
> Chat pull cue: Screenshot where Susan identifies Specialize Alteration 54/105, others capped at 50, and says LOCK CONFIRMED.
>
> Caption: Chaos paused long enough to make one adult decision.

The funniest part came afterward.

Susan began explaining how Alteration supported heals, slows, roots, ports, and survival.

Aahz asked:

Do you know what else is Alteration?

Susan guessed Slow.

Aahz had something with one less letter in mind.

SoW.

Spirit of Wolf.

Alteration: because Improved Feign Death should always be Plan B.

### Gnome Boot Camp And The Unholy Land

Then Aahz went to South Ro.

Not for supplies.

Training.

Feign Death, which had started the night at 1, climbed through 31, then 85-ish.

Athletics reached 99.

2H Blunt trained up to 150.

Disarm climbed.

Abjuration hit 105, MASTER.

Specialize Alteration kept rising.

South Ro became a montage:

Run.

Disarm.

Bonk with a giant stick.

Flop.

Get up.

Run.

Continuing education.

> [SCREENSHOT NEEDED: images/screenshot-south-ro-training-fd-85.png]
>
> Chat pull cue: Training screenshot where Susan reads Specialize Alteration 66 to 67, Abjuration 105 MASTER, Disarm 96, 2H Blunt 148 to 150, Feign Death 84 to 85, Athletics 99.
>
> Caption: The floor inspection curriculum began producing results.

Then the Pure Chaos Rotation escaped Najena entirely.

Aahz entered The City of Guk.

Upper Guk greeted the level-20 Alteration-specialized Kung Fu Gnome with level-7 frogloks who did not understand what had just happened to their local tourism board.

The Guru wandered deeper.

Froglok idealist, level 20.

Fungus drones, 17 and 18.

Fungus ancient, 24, described by the game as "quite a gamble."

Susan told him not to complete that equation.

He kept wandering.

A zone line appeared.

Aahz found The Ruins of Old Guk.

Lower Guk.

The welcome committee included a level-30 froglok shin knight and a level-27 shin ghoul knight, both functionally asking what the Guru would like his tombstone to say.

Aahz waved.

Then, in an astonishing act of judgment, he cast Gate.

No corpse.

No Kyle casualty.

No Improved Feign Death.

Just:

Thank you for the tour. Your level-30 murder frog is lovely. I will not be staying.

Gate.

Alteration specialization had already justified itself.

> [SCREENSHOT NEEDED: images/screenshot-city-of-guk-traveler.png]
>
> Chat pull cue: Screenshot where Susan reads "You have entered The City of Guk" and "The City of Guk Traveler."
>
> Caption: The Pure Chaos Rotation escaped Najena and began rotating zones.

> [SCREENSHOT NEEDED: images/screenshot-lower-guk-level-30-shin-knight.png]
>
> Chat pull cue: Screenshot where Susan reads "You have entered The Ruins of Old Guk" and a level-30 froglok shin knight with "What would you like your tombstone to say?"
>
> Caption: Lower Guk offered immediate tombstone consultation.

> [SCREENSHOT NEEDED: images/screenshot-lower-guk-gate-escape.png]
>
> Chat pull cue: Text beat after user says "no, as a matter of fact, I cast GATE...."
>
> Caption: The Guru found the door, inspected the murder frogs, and chose Alteration.

### Quick Buff Funded

The original AA objective still remained.

Episode 6 began with 2/5 AA toward Quick Buff. It needed three more.

Through Najena, Tenderizer, Unbound Flame, Lost Crusader, South Ro training, Upper Guk wandering, Lower Guk reconnaissance, and general disregard for itinerary planning, Aahz earned them.

Quick Buff was funded.

The thing that began as a petty annoyance became the next build milestone.

One button would soon load the Buff Set, apply the package to Aahz and Kyle, restore the Battle Set, and drop the Gnome onto the floor for further Feign Death education.

The Factory had achieved automation.

Tomorrow, automation would achieve catastrophe.

Probably.

### Final Accounting

Episode 6 began at level 18.

Episode 6 ended at level 20.

Build state:

MNK / DRU / ENC remains the operating doctrine.

Monk first. Always Monk first.

Magic now augments the punching with actual discipline:

Calm splits the room.

Tash sabotages resistant bastards.

Cloud hardens the Gnome.

Intellectual Superiority reduces one more path to failed heals.

Specialize Alteration makes the survival department cheaper.

Spirit of Wolf moves the tiny purple problem away from consequences at superior speed.

Major discoveries:

Feign Death existed and required training.

Quick Buff was not convenience. It was architecture.

Calm turned rooms from group fights into queues.

The Tenderizer camp became repeatable manufacturing.

Spawn timers became a scheduling problem.

Improved Feign Death discovered a pull room.

The Pure Chaos Rotation replaced camping with mobile violence.

Unbound Flame became a lamp.

Lost Crusader became jewelry.

Lower Guk was physically found.

Gate was successfully used instead of learning what a level-30 murder frog does to a level-20 Gnome.

Kyle report:

Kyle casts Courage.

Kyle has also been observed doing suspicious support work such as root and heal-adjacent nonsense.

Kyle was killed again.

OMG! THEY KILLED KYLE!

YOU BASTARDS!

Kyle received a formal offer to join `<Under the Belt>`.

The combat log later credited Jabobn with the Unbound Flame kill.

Jabobn is Kyle's current government name.

Under the Belt knows its people.

AA report:

Episode began with 2/5 AA toward Quick Buff.

Episode ended with Quick Buff funded.

Next immediate purchase: Quick Buff.

Roadmap contamination:

Companion's Discipline and Greater Pet Hold have entered Susan's recommendations for reasons unrelated to pet ownership.

The official phrase is Greater Unexplained Floating-Dagger Restraint.

New slogans:

THE GNOME MUST FLOP.

THE FUCKING HEAL MUST CAST.

THE BUFF FACTORY MUST GROW.

THE PURE CHAOS ROTATION.

Never wait for the factory.

Become the factory.

Final state:

Level 20.

Specialize Alteration locked.

Feign Death trained from basically unused to 85-ish.

Lower Guk found and bookmarked for future poor decisions.

Quick Buff funded.

Kyle at his post.

KYLE.

STAY.

Good Kyle.

ROOT BRELL.

THE GNOME DINGED.

NIGHT NIGHT, GURU.
