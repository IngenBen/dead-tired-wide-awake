# Claim References — MED claims — WORKING SCAFFOLD (Step B)

Blind-endnotes sourcing for the 142 **MED** claims in `scratch-pad-claims-ranking.md`.
This is the Step B scaffold: every MED claim expanded to one sentence + the exact book
source sentence(s), then de-duplicated into **distinct facts** and grouped into **topic
clusters**. `/book/` read with the file-reader for context only; unedited.

MED = a general scientific/mechanistic claim (broadly accepted, worth a further-reading
pointer) OR a contested / counterintuitive claim. Scrutiny is concentrated on the
contested/counterintuitive ones and any numbers.

**Reuse key:** `HIGH✓` = same fact already sourced in `claim-references.md` (reuse that
citation, don't re-search). `NEW` = needs a fresh search. `FLAG` = contested / number /
evidence concern to watch.

---

# PART 1 — Per-claim scaffold (by chapter)

## Ch01 — The Weight of It
- **01.5** Knew poor sleep underlies serious disease. — Book: "I knew it sat behind some of the most serious long-term diseases." → **HEALTH1** · HIGH✓ (=Ch03.14, CDC/NINDS).
- **01.8** Falling asleep instantly signalled a huge deficit. — Book: "falling asleep the moment my head hit the pillow… meant I was running such a huge sleep deficit my body would just crash." → **SO1** · NEW (short sleep-onset latency as a marker of sleep debt).

## Ch02 — The Turning Point
- **02.5** Intense biking days gave worse sleep. — Book: "days on the mountain that were the most physically intense of my life… I consistently slept worse." → **O5** · anecdote, maps O1 / HIGH Ch20.6 (late/intense exercise).
- **02.6** Daytime stress causes night-time sleep problems. — Book: "if daytime stress causes a nighttime problem…"; "a stressful day at work led to a bad night's sleep." → **E6** · NEW (daytime stress → impaired sleep).

## Ch03 — The Uncomfortable Truth
- **03.1** CBN is a THC breakdown product, sleep-targeted. — Book: "CBN — a compound formed when THC breaks down, supposedly even more targeted for sleep than CBD." → **CBN1** · NEW (book hedges "supposedly"; evidence thin).
- **03.13** Only a small percentage truly function sleepless. — Book: "only a very small percent of the population can genuinely function that way." → **SS1** · NEW (true short sleepers / DEC2 etc.).
- **03.16** Sleep depends on hormones' rhythmic rise/fall. — Book: "the whole process of sleep depends on hormones… that need to rise and fall in a predictable rhythm throughout 24 hours." → **FW1** · NEW (circadian/homeostatic framework).

## Ch04 — Sleep Incorporated
- **04.5** Adenosine is the sleep-pressure executive. — Book: "Adenosine — your sleep pressure executive." → **A1** · HIGH✓ (adenosine context, NINDS/Reichert).
- **04.6** Melatonin is the sleep-timing executive. — Book: "Melatonin — your sleep timing executive." → **C1** · partial HIGH (SHF/NINDS).
- **04.7** Cortisol is the waking-energy executive. — Book: "Cortisol — your waking-energy executive." → **E1** · HIGH✓ (Ch07 cortisol).
- **04.8** Dopamine is the motivation executive. — Book: "Dopamine — your motivation executive." → **U1** · NEW.
- **04.14** Pills don't fix root misalignment. — Book: "a sleeping pill… never fixes the root problem." → **FW2** · NEW (CBT-i first-line vs hypnotics).
- **04.22** Adenosine technically a neurotransmitter, labelled hormone. — Book (footnote): "Technically, adenosine is a neurotransmitter rather than a hormone." → **A2** · NEW.

## Ch05 — Adenosine
- **05.3** Adenosine builds from waking, a byproduct. — Book: "your brain starts producing adenosine - a natural byproduct of being awake." → **A1** · HIGH✓.
- **05.4** Builds sleep pressure across the day. — Book: "It accumulates through the day, building what is sometimes called sleep pressure." → **A1** · HIGH✓ (merge 05.3).
- **05.6** Morning levels reset near zero. — Book: "By morning… levels are back to near zero." → **A3** · HIGH✓ (=Ch05.5).
- **05.10** Poor clearing means insufficient deep sleep. — Book: "Adenosine not clearing overnight comes down to one thing: not enough deep sleep." → **A3** · HIGH✓ (=Ch05.5).
- **05.13** Stress holds brain in vigilant state. — Book: "Stress holds the brain in a lighter, vigilant state — the opposite of what deep sleep needs." → **E6** · NEW (stress → lighter/fragmented sleep).
- **05.14** Warmth blocks the needed temperature drop. — Book: "deep sleep needs your core temperature to drop, and a warm room makes that harder." → **G2** · HIGH✓ (=Ch12.11/13).
- **05.15** Irregular schedule cuts deep-sleep timing. — Book: "An irregular schedule cuts deep sleep timing. It's front-loaded into the first part of the night." → **Q1** + HIGH✓ Ch05.16 (front-loading).
- **05.17** Screens fragment lighter stages, eat slow-wave. — Book: "The light, notifications, and habit of checking fragment the lighter stages and eat into slow-wave sleep." → **D5** · NEW.
- **05.18** Caffeine is an hours-long activating signal. — Book: "Every cup is activating — a signal that lasts for hours." → **B1** · HIGH✓ (=Ch13.6 half-life).

## Ch06 — Melatonin
- **06.4** Melatonin is a signal, not a pill. — Book: "Melatonin is not a sleeping pill your body makes. It's a signal." → **C1** · partial HIGH.
- **06.5** Released as evening light drops. — Book: "As the day fades and light drops, your brain begins releasing it." → **C2** · HIGH✓ inverse (Ch06.12 light suppresses; NINDS dark→melatonin).
- **06.6** Lowers temperature and alertness; prepares body. — Book: "Core body temperature drops slightly. Alertness falls. The machinery prepares." → **C3** · NEW.
- **06.7** Enables sleep rather than forcing it. — Book: "the signal doesn't force sleep — it enables it." → **C1** · partial HIGH (merge 06.4).
- **06.13** Irregular schedule misplaces the rhythm. — Book: "the system loses its reference point. The rise still happens, but… at the wrong time, or flattens, or arrives too late." → **Q1** · NEW.
- **06.14** Stress and hyperarousal override rising melatonin. — Book: "a nervous system running too hot can override it." → **E8→E4/E6** · merge.
- **06.15** Consistent bedtime plus morning light fixes timing. — Book: "A consistent bedtime and morning light exposure… give the system what it needs to set the rhythm." → **D2** · HIGH✓ (=Ch16.5).
- **06.20** Body responds to the rise, not level. — Book: "the body responds to the rise rather than the level." → **C4** · HIGH✓ (=Ch06.19).

## Ch07 — Cortisol
- **07.5** Anxious and positive thoughts both involve cortisol. — Book: "anxious version or positive version, both involve cortisol." → **E3** · NEW.
- **07.6** Cortisol is a wake executive. — Book: "Cortisol is a Wake Executive… the body's alertness system." → **E1** · HIGH✓.
- **07.9** Baseline curve; demand spikes above it. — Book: "That curve is your baseline. Demand lifts you above it… a temporary spike." → **E2** · partial HIGH (Ch07.8 diurnal curve).
- **07.10** Well-regulated systems return to baseline. — Book: "a well-regulated system brings it back down to the line. Spike and return." → **E2** · partial HIGH.
- **07.11** Cortisol mobilises for anything feeling urgent. — Book: "Cortisol actually mobilises you for anything that feels like it needs immediate action." → **E3** · NEW.
- **07.12** Nervous system can't distinguish threat from productivity. — Book: "The nervous system doesn't distinguish between a threat and productivity. Both can feel urgent." → **E3** · NEW (merge 07.5/07.11).
- **07.14** Cortisol and melatonin work in opposition. — Book: "Cortisol and melatonin should work in opposition — in the evening as cortisol falls, melatonin rises." → **E4** · HIGH✓ (=Ch07.17).
- **07.19** Stimulation costs cortisol, raises the baseline. — Book: "every piece of stimulation is another small bump… Baseline cortisol creeps up." → **E5** · relates HIGH Ch07.18/20.
- **07.22** Podcast: don't do daytime things at night. — Book: "don't do things at night that you'd do during the day. It sends completely the wrong signal." → **SC4** · T6 (podcast attribution) / maps stimulus control.

## Ch08 — Dopamine
- **08.5** Dopamine responds to opportunity, worth pursuing. — Book: "Dopamine responds to opportunity… to say this is worth pursuing." → **U1** · NEW.
- **08.6** Fast cheap signals drown quieter ones. — Book: "Train it on fast, cheap signals… and the quieter signals stop getting through." → **U2** · NEW.
- **08.8** Provocative content triggers stress and cortisol. — Book: "content that triggers a strong reaction — a jolt of stress, cortisol along with it." → **U3** · NEW.
- **08.9** Curiosity content: same mechanism, less cortisol. — Book: "the same dopamine minus the cortisol." → **U3** · NEW.
- **08.10** Brain responds to novelty and unpredictability. — Book: "What it responds to is novelty and unpredictability." → **U2** · NEW (variable reward).
- **08.12** Reward system recalibrates to fast spikes. — Book: "this recalibrates the reward system. Fast, frequent, unpredictable spikes become the baseline." → **U2** · NEW.
- **08.14** Right TV is genuinely passive, different. — Book: "The right show — low-stakes, predictable, easy to follow — is genuinely passive." → **U6** · NEW (weak/extension).
- **08.16** Gaming engineered to deliver dopamine. — Book: "Gaming… is almost perfectly engineered to deliver it. Constant rewards… Unpredictable outcomes." → **U4** · NEW.

## Ch09 — Taking Ownership
- **09.18** Doing it with others aids completion. — Book: "People are far more likely to see the program to the end if they are doing it with other people." → **BC1** · NEW (social support → adherence).

## Ch10 — Your Feedback Loop
- **10.6** Trackers can worsen anxiety for some. — Book: "For some people having a tracker can make them obsessed and more anxious." → **I1** · NEW (orthosomnia).
- **10.7** Trackers aren't perfectly accurate night to night. — Book: "the trackers aren't perfectly accurate night to night." → **I2** · HIGH✓ (=Ch10.19).
- **10.14** Deep sleep does physical repair. — Book: "Deep sleep is where the body does its physical repair work." → **H1** · NEW (NINDS).
- **10.16** HRV reflects nervous-system balance and recovery. — Book: "heart rate variability… reflects how well your nervous system is balancing its two modes… higher variability generally means better recovery." → **HRV1** · NEW.
- **10.17** Trackers get total sleep time right. — Book: "total sleep time. They typically get this right." → **I2** · HIGH✓ (=Ch10.19, Chinoy).
- **10.18** Lying still awake can miscount as sleep. — Book: "If you spend a lot of time lying very still while awake, some devices will count it as sleep." → **I2** · HIGH✓.
- **10.21** Oura has the most published research. — Book: "the Oura Ring has the most published research behind it." → **I3** · NEW (verify).

## Ch11 — Supplements
- **11.3** Form/extract matters more than generic name. — Book: "the form or extract makes a significant difference to how well the body absorbs it." → **J1** · NEW (bioavailability by form).

## Ch12 — Your Sleep Environment
- **12.5** Night light reads as near-morning. — Book: "When light enters the bedroom during the night, your body reads it as a signal — almost morning." → **D1** · NEW.
- **12.6** Low light causes background mild alertness. — Book: "Even low-level light can put your system into a state of mild alertness… reducing the quality of sleep." → **D1** · NEW (relates HIGH Ch15.21 lux).
- **12.9** Temperature most directly connected to quality. — Book: "Temperature is the environmental factor with the most direct connection to sleep quality." → **G1** · NEW.
- **12.12** Body sheds heat through hands and feet. — Book: "Your body needs to shed heat outward through your hands and feet." → **G2** · HIGH✓ (=Ch12.11 distal heat loss).
- **12.17** Sudden noises pull you from deep sleep. — Book: "Sudden sounds in particular can either pull you out of sleep entirely, or pull you out of deep sleep without fully waking you." → **NOI1** · NEW.
- **12.20** Bedroom TV stimulates and builds association. — Book: "introduces stimulation… your brain learns by association. TV teaches it that the bed is also for being awake." → **SC1** · maps HIGH Ch15.16 (stimulus control).
- **12.21** TV's light less the concern than stimulation. — Book: "the light output isn't really the main concern here — it's the stimulation and the association." → **D6/SC1** · HIGH✓ (=Ch21.3 content>light).

## Ch13 — Caffeine
- **13.2** Caffeine the single biggest disruptor for many. — Book: "for a significant number of people it is the single habit most likely to be disrupting their sleep." → **B2** · NEW.
- **13.5** Wearing off creates a worse slump. — Book: "When the caffeine wears off and the adenosine… floods back, that is the afternoon slump… caffeine makes it significantly worse." → **B3** · NEW (extends HIGH Ch13.4).
- **13.7** Halving math: morning coffee still 10pm. — Book: "Every six hours, the amount in your system halves… a single shot espresso at 10pm." → **B1** · HIGH✓ (=Ch13.6, number FLAG: 6h half-life high).
- **13.8** Morning coffee competes with cortisol/adenosine clearance. — Book: "Drinking coffee in this window competes with both." → **B4** · NEW.
- **13.9** Delay first coffee 60–90 minutes. — Book: "delay the first coffee by sixty to ninety minutes." → **B4** · NEW.

## Ch14 — Alcohol
- **14.6** Alcohol does speed falling asleep. — Book: "It does help you fall asleep faster. That much is true." → **F1** · HIGH✓ (Gardiner/Ebrahim).
- **14.7** Alcohol sedates rather than inducing sleep. — Book: "Alcohol sedates rather than induces natural sleep." → **F1** · HIGH✓.
- **14.11** Fragmented deep sleep leaves adenosine uncleared. — Book: "Deep sleep is also when the brain clears adenosine… when alcohol fragments it, that clearing is incomplete." → **F2** · **FLAG** — depends on the contested "alcohol fragments deep sleep" (HIGH Ch05.12/14.8: CONTRADICTED).
- **14.17** Food slows absorption, softens the peak. — Book: "having it with food slows absorption and softens the peak." → **F3** · NEW.

## Ch15 — Can't-sleep routine
- **15.2** When the mind races, get up. — Book: "When you notice your mind racing… get up." → **SC3** · HIGH✓ (=Ch15.16 CBT-i stimulus control).
- **15.8** Couch sleeping acceptable if needed. — Book: "Or just sleep on the couch… sleeping is what matters most." → **SC3** · author practice (minor).
- **15.12** Lying frustrated raises cortisol, blocks sleep. — Book: "the more frustrated you get, the more cortisol rises, the more alert you stay." → **E7** · NEW (frustration loop; relates HIGH Ch07.20).
- **15.13** Brain associates bed with racing mind. — Book: "Bed-equals-racing-mind, instead of bed-equals-sleep." → **SC1** · HIGH✓ (stimulus control).
- **15.14** Bed activities crowd out the sleep association. — Book: "Every activity in bed… teaches the brain that bed is a place where those things happen." → **SC1** · HIGH✓.
- **15.19** Sitcoms/cartoons worked; daytime-worthy shows wouldn't. — Book: "cartoons I wouldn't [watch by day]… If I really liked them, they would have kept me up." → **U6** · author practice (weak).
- **15.20** Routine rewrites the association over weeks. — Book: "over weeks it rewrites the association — bed equals sleep." → **SC2** · relates SC1/HIGH Ch15.16.

## Ch16 — Morning Routine
- **16.3** Wake-and-light time is the key input. — Book: "the single most important input… is the time you wake up and get light into your eyes." → **D2** · HIGH✓ (=Ch16.5).
- **16.4** Shifting wake time shifts everything later. — Book: "When that time shifts… the cortisol awakening response fires later. The countdown to evening melatonin… starts later." → **Q1/D2** · HIGH✓-adjacent.
- **16.6** Light within 30–60 minutes signals daytime. — Book: "Light entering your eyes in the first thirty to sixty minutes after waking tells your brain: it's daytime." → **D2** · HIGH✓.
- **16.9** Five–fifteen minutes of sun usually enough. — Book: "Five to fifteen minutes in direct sunlight is usually enough." → **D3** · HIGH✓-adjacent (=Ch16.8) · number check.
- **16.10** Overcast sky still beats indoor light. — Book: "The sky, even grey, delivers far more light than the inside of a house." → **D3** · HIGH✓ (=Ch16.8).
- **16.11** Movement amplifies the light signal. — Book: "movement alongside it amplifies the signal." → **MOV1** · NEW (weak/extension).
- **16.15** Light-therapy lamp substitutes if stuck inside. — Book: "a bright light therapy lamp at breakfast can be a workable substitute." → **D4** · NEW.
- **16.16** After a late night, wake time holds. — Book: "wake time does not move. Get up." → **Q2** · HIGH✓ (=Ch17.13 regularity).
- **16.17** Short nap okay, twenty minutes max. — Book: "the shortest nap you can manage. Twenty minutes at most. Not before mid-morning and not in the late afternoon." → **Y2** · NEW.
- **16.18** A full sleep-in sends inconsistent signal. — Book: "Rolling over and going back to sleep for a couple of hours sends an inconsistent signal." → **Q2** · HIGH✓-adjacent.

## Ch17 — Evening Routine
- **17.2** By dinner cortisol falls, melatonin rises. — Book: "cortisol… is naturally declining. Melatonin is beginning to rise." → **E4** · HIGH✓ (=Ch07.17).
- **17.4** Bright light/stimulation slides the window later. — Book: "Bright overhead light… stimulating content… the window slides later." → **D6** · HIGH✓ (=Ch06.12/Ch21.3).
- **17.9** The bed is for sleep only. — Book: "The bed is for sleep." → **SC1** · HIGH✓ (stimulus control).
- **17.12** Keep bedtime within 30 consistent minutes. — Book: "keep your bedtime within 30 minutes of the same time, each night." → **Q2** · HIGH✓ (=Ch17.13).

## Ch18 — Meditation
- **18.9** Consistent breathing is nervous-system strength training. — Book: "Breathing — done consistently… is nervous system strength training." → **M6** · NEW (relates HIGH Ch18.21).
- **18.13** Two modes: sympathetic activating, parasympathetic calming. — Book: "a sympathetic dominant state, your activating system… a parasympathetic dominant state, your calming system." → **M1** · NEW (ANS physiology).
- **18.14** Poor sleepers stuck in activated state. — Book: "Most people with persistent sleep problems spend too much time in the activated state." → **E9** · NEW (hyperarousal model of insomnia).
- **18.16** Meditation builds the calming muscle. — Book: "Meditation, done consistently, builds that muscle." → **M6** · NEW (merge 18.9).
- **18.17** Calming runs through the vagus nerve. — Book: "Its primary channel is the vagus nerve." → **M2** · HIGH✓ (=Ch18.18 Russo).
- **18.19** The vagus carries signals both directions. — Book: "the vagus runs both ways… it carries information up from it." → **M3** · NEW (vagal afferents).
- **18.20** Lungs uniquely controllable off autopilot. — Book: "the lungs are unique — the only organ you can take off autopilot." → **M4** · NEW (voluntary breathing → ANS).
- **18.24** Body-based meditation sends body-to-brain signal. — Book: "body-based meditation runs the other way, body to brain." → **M3** · NEW (interoception bottom-up).
- **18.28** Nasal breathing naturally slows the breath. — Book: "Nasal breathing naturally slows the breath down." → **M5** · NEW.
- **18.29 (HIGH)** noted for context (exhale/pause slows HR) — HIGH✓.
- **18.32** 528 Hz became his meditation cue. — Book: "I search for '528 Hz'… I've made it my meditation music… my brain has come to recognise it as a signal for calm." → **CON1** · NEW (classical conditioning; book hedges the 528Hz-frequency claim).

## Ch19 — Napping
- **19.4** Long/late naps spend the sleep resource. — Book: "Especially when they ran long or landed too close to bedtime — I was spending down the very resource." → **Y1** · NEW.
- **19.5** Standard advice: short, not within 7–8h. — Book: "Keep it short — twenty minutes at most. Don't nap within seven to eight hours of your bedtime." → **Y2** · NEW.
- **19.6** Naps clear adenosine sleep pressure. — Book: "Napping clears some of that [adenosine] out." → **Y1** · NEW (relates A1).

## Ch20 — Exercise
- **20.3** Exercise spikes cortisol by design. — Book: "Exercise spikes cortisol. That's not a flaw… that's the point." → **O1** · NEW.
- **20.4** Well-rested bodies clear cortisol within hours. — Book: "cortisol clears within a few hours of the effort ending." → **O1** · NEW.
- **20.8** Sleep-deprived people recover poorly from intensity. — Book: "The calming system is already compromised. Recovery is already slow." → **O1** · NEW.
- **20.10** Intensity and timing both matter. — Book: "intensity and the timing — and nobody told you that those two things matter as much as they do." → **O2** · relates HIGH Ch20.18.
- **20.16** Morning exercise works with the cortisol curve. — Book: "Morning exercise works with your cortisol curve… exercise channels that into effort rather than creating a fresh spike later." → **O3** · HIGH✓ (=Ch20.17).
- **20.19** His safer margin: six hours before bed. — Book: "at least six hours as the safer margin." → **O4** · author self-experiment FLAG (contrast HIGH Ch20.18 = 4h research, itself mixed).
- **20.21** Yoga is somatic, trains the nervous system. — Book: "yoga… actively trains the nervous system while you move… somatic exercise." → **Z1** · NEW.
- **20.22** Somatic movement trains calming in motion. — Book: "somatic movement trains it in motion." → **Z1** · NEW (merge 20.21).
- **20.23** Tai chi and qigong work similarly. — Book: "Tai chi works on the same principle. So does qigong." → **Z2** · NEW.

## Ch21 — Social Media
- **21.4** Can't blue-light-filter your way out. — Book: "you can't blue-light-filter your way out of it." → **D6** · HIGH✓ (=Ch21.3 content>light).
- **21.9** Algorithm serves more of what engages. — Book: "It just serves you more of what you've already responded to." → **U4** · NEW.
- **21.10** We respond most reliably to provocation. — Book: "we respond most reliably to content that makes us feel something – outrage, shock, indignation." → **U5** · NEW (negativity bias).

## Ch22 — Hydration
- **22.3** Mild dehydration registers as stress. — Book: "Even mild dehydration… is enough for the body to register as a low-level stress state." → **V1** · HIGH✓ (=Ch22.4).
- **22.5** Dehydration makes cooling down harder. — Book: "Dehydration also makes it harder for the body to cool down." → **V2** · NEW.
- **22.6** Cooling down helps trigger sleep onset. — Book: "cooling down is part of what triggers sleep onset." → **G3** · HIGH✓ (=Ch12.11).
- **22.7** Elevated cortisol makes the bladder signal loud. — Book: "When cortisol is elevated and sleep is light, the bladder signal… becomes loud enough to wake you." → **NOC1** · NEW (author mechanism).
- **22.8** Night holding relies on low cortisol. — Book: "that system relies on cortisol being low and sleep being deep." → **NOC1** · NEW (nocturia / vasopressin).
- **22.11** Thirst lags; don't rely on it. — Book: "by the time you feel it, you're already behind." → **V3** · NEW.
- **22.12** Two–three litres is reasonable daily. — Book: "between two and three litres is a reasonable daily amount." → **V4** · NEW (number).
- **22.14** Urine colour is the simplest signal. — Book: "urine colour is the simplest one. Pale straw… Dark yellow." → **V5** · NEW.

## Ch23 — Food Timing
- **23.2** Like alcohol: helps onset, hurts quality. — Book: "while it might help us get to sleep, the quality suffers." → **R2** · relates HIGH Ch23.7.
- **23.3** Eating shifts the body into active state. — Book: "When you eat, your body shifts into an active state." → **R1** · NEW.
- **23.4** Digestion raises metabolism and core temperature. — Book: "Metabolism rises, core temperature follows." → **R1** · NEW (diet-induced thermogenesis).
- **23.5** Eating fights the needed cooling down. — Book: "You're asking the body to cool down while it's generating heat." → **R1** · NEW (merge 23.3/23.4).
- **23.6** You drop off but sleep fragments. — Book: "You'll often still drop off… But the sleep you get is lower quality and more fragmented." → **R2** · relates HIGH Ch23.7.
- **23.8** Three-hour gap is his target. — Book: "I use 3 hours as the target." → **R3** · HIGH✓ (=Ch23.7, SHF 2–3h).
- **23.10** Hunger is its own cortisol trigger. — Book: "Hunger is its own cortisol trigger." → **HUN1** · NEW (fasting/hunger → cortisol).

## Ch24 — Sugar & Food Sensitivities
- **24.12** Brain registers glucose drop as emergency. — Book: "The brain, which runs almost exclusively on glucose, registers this as an emergency." → **W1** · NEW (relates HIGH Ch24.11).
- **24.13** Cortisol mobilises energy to correct it. — Book: "Cortisol mobilises stored energy and raises blood glucose back to safe levels." → **W2** · NEW (counter-regulation).
- **24.16** Evening sugar disrupts the cortisol-melatonin handover. — Book: "A significant sugar hit late in the evening… disrupts that handover directly." → **W3** · NEW (extension).
- **24.17** Late sugar can trigger 2–3am waking. — Book: "A late sugar hit… a blood sugar dip provoking a cortisol surge… pulling you out of deep sleep." → **W3** · NEW (extension; relates HIGH Ch24.11).
- **24.20** Food sensitivities cause low-grade immune response. — Book: "food sensitivities that are quietly generating a low-grade immune response." → **X1** · NEW.
- **24.21** Symptoms: congestion, fog, fatigue, bloating. — Book: "disrupted sleep, persistent fatigue, brain fog, bloating… a stuffy nose that never quite goes away." → **X2** · NEW (congestion → fragmented sleep).
- **24.22** Common culprits: gluten, dairy, eggs, soy. — Book: "The most commonly reactive foods are gluten, dairy, eggs, and soy." → **X3** · NEW.
- **24.23** Elimination is the most reliable start. — Book: "an elimination approach is the most reliable place to start." → **X4** · NEW (elimination-reintroduction = gold standard).
- **24.24** Reactivity blood tests contested, not diagnostic. — Book: "the science is contested. Many clinicians consider them unreliable." → **X5** · NEW (IgG tests not validated; book flags contested).

---

# PART 2 — Distinct facts, by cluster

Legend: **[reuse]** already sourced in HIGH file · **[new]** needs search · **[flag]** contested/number.

## A — Adenosine
- **A1** Adenosine accumulates from waking as a metabolic byproduct, building "sleep pressure" across the day. [04.5, 05.3, 05.4] — **[reuse]** NINDS/Reichert.
- **A2** Adenosine is technically a neurotransmitter/neuromodulator, not a hormone. [04.22] — **[new]**.
- **A3** Deep sleep clears adenosine; poor deep sleep = incomplete clearance = morning tiredness; ~zero by morning. [05.6, 05.10] — **[reuse]** =Ch05.5.

## B — Caffeine
- **B1** Caffeine is a long-acting stimulant lasting hours (half-life math). [05.18, 13.7] — **[reuse]** =Ch13.6 **[flag]** 6h high.
- **B2** Caffeine is the single biggest sleep disruptor for a large share of people. [13.2] — **[new]**.
- **B3** Caffeine masks tiredness (blocks adenosine); on wearing off the rebound deepens the afternoon slump. [13.5] — **[new]** (extends Ch13.4).
- **B4** Coffee in the first 60–90 min after waking competes with the cortisol-awakening surge & adenosine clearance; delay first cup 60–90 min. [13.8, 13.9] — **[new]**.

## C — Melatonin
- **C1** Melatonin is a hormonal *timing signal*, not a sedative — it enables rather than forces sleep. [04.6, 06.4, 06.7] — **[reuse/partial]** SHF/NINDS.
- **C2** Melatonin secretion rises as evening light falls (darkness-driven). [06.5] — **[reuse]** inverse of Ch06.12; NINDS.
- **C3** Melatonin lowers core temperature and alertness, preparing the body for sleep. [06.6] — **[new]**.
- **C4** The body responds to the *rate of rise* of melatonin, not the absolute level. [06.20] — **[reuse]** =Ch06.19.

## D — Light & circadian cue
- **D1** Light entering the bedroom at night is read as a wake signal; even low light causes background alertness and lowers sleep quality. [12.5, 12.6] — **[new]** (relates Ch15.21 lux).
- **D2** Morning light within 30–60 min of waking is the dominant circadian-setting cue; wake+light time anchors the clock. [06.15, 16.3, 16.4, 16.6] — **[reuse]** =Ch16.5.
- **D3** Natural daylight (even overcast) is far brighter than indoor light; 5–15 min sun (≈20 overcast) usually enough. [16.9, 16.10] — **[reuse]** =Ch16.8 **[number]** dose.
- **D4** A light-therapy lamp can substitute for morning sun when indoors. [16.15] — **[new]**.
- **D5** Screens (light + notifications + checking) fragment light-sleep stages and eat into slow-wave sleep. [05.17] — **[new]**.
- **D6** Evening bright light/stimulating content delays the sleep window. [17.4, 21.4, 12.21] — **[reuse]** =Ch06.12/Ch21.3.

## E — Cortisol, stress & hyperarousal
- **E1** Cortisol is the daytime alerting/wake hormone. [04.7, 07.6] — **[reuse]** Ch07.
- **E2** Cortisol has a diurnal baseline curve; demands cause reactive spikes that a healthy system returns to baseline. [07.9, 07.10] — **[reuse/partial]** Ch07.8.
- **E3** Cortisol mobilises for anything perceived as urgent; the nervous system doesn't distinguish threat from positive/productive arousal. [07.5, 07.11, 07.12] — **[new]**.
- **E4** Cortisol & melatonin operate in opposition; the evening handover is cortisol-down/melatonin-up. [07.14, 17.2, 06.14] — **[reuse]** =Ch07.17.
- **E5** Chronic stimulation/stress raises baseline cortisol over time, shallowing the evening decline. [07.19] — **[reuse/partial]** Ch07.18/20.
- **E6** Daytime stress causes night-time sleep problems; stress holds the brain in a lighter, vigilant state (less deep sleep). [02.6, 05.13] — **[new]**.
- **E7** Frustration at being awake is itself an acute stressor that raises cortisol/arousal (the frustration loop). [15.12] — **[new]** (relates Ch07.20).
- **E9** Chronic poor sleepers are over-represented in a sympathetic-dominant ("activated") state — the hyperarousal model of insomnia. [18.14] — **[new]**.

## F — Alcohol
- **F1** Alcohol speeds sleep onset but sedates rather than inducing natural sleep. [14.6, 14.7] — **[reuse]** Ch14.8/Gardiner.
- **F2** Alcohol fragments deep sleep, leaving adenosine uncleared. [14.11] — **[flag — CONTRADICTED]** per HIGH Ch05.12/14.8.
- **F3** Eating with alcohol slows absorption and softens the blood-alcohol peak. [14.17] — **[new]**.

## G — Temperature
- **G1** Temperature is the environmental factor most directly tied to sleep quality. [12.9] — **[new]**.
- **G2** Core temperature must drop to initiate/maintain sleep; heat is shed via hands/feet; warmth blocks the drop. [12.12, 05.14] — **[reuse]** =Ch12.11.
- **G3** Cooling down helps trigger sleep onset. [22.6] — **[reuse]** =Ch12.11.

## H — Sleep stages / restorative sleep
- **H1** Deep (slow-wave) sleep is when the body does physical repair/restoration. [10.14] — **[new]** NINDS.

## I — Trackers (incl. HRV)
- **I1** Sleep trackers can worsen anxiety/obsession for some (orthosomnia); not accurate night-to-night. [10.6, 10.7] — **[new]**.
- **I2** Trackers measure total sleep time fairly well but can miscount still wakefulness as sleep. [10.17, 10.18, 10.7] — **[reuse]** =Ch10.19 (Chinoy).
- **I3** The Oura Ring has the most published validation research. [10.21] — **[new — verify]**.
- **HRV1** HRV reflects autonomic (sympathetic/parasympathetic) balance; higher HRV ~ better recovery/resilience. [10.16] — **[new]**.

## J — Supplements
- **J1** A supplement's specific form/salt/extract determines bioavailability & effect (e.g., magnesium forms). [11.3] — **[new]** (relates HIGH Ch11.10).

## U — Dopamine & digital media
- **U1** Dopamine signals reward/opportunity/anticipation ("worth pursuing") and drives motivation. [04.8, 08.5] — **[new]**.
- **U2** Fast, frequent, unpredictable (variable-reward) digital stimuli recalibrate/desensitise the reward system so slower signals stop registering. [08.6, 08.10, 08.12] — **[new]**.
- **U3** Both provocative and curiosity content drive dopamine; provocative content additionally triggers cortisol/stress. [08.8, 08.9] — **[new]**.
- **U4** Games and social-media feeds are engineered to exploit dopamine/variable reward (algorithmic reinforcement). [08.16, 21.9] — **[new]**.
- **U5** People respond most reliably to emotionally provocative content (negativity bias). [21.10] — **[new]**.
- **U6** Passive, predictable TV is genuinely less activating than interactive/novel media. [08.14, 15.19] — **[new — weak/extension]**.

## M — Vagus / breathing / meditation
- **M1** The ANS runs in two modes — sympathetic (activating) vs parasympathetic (calming). [18.13] — **[new]** (textbook physiology).
- **M2** The parasympathetic/calming response runs primarily through the vagus nerve. [18.17] — **[reuse]** =Ch18.18 (Russo).
- **M3** The vagus is bidirectional (mostly afferent); attending to body sensations works it bottom-up. [18.19, 18.24] — **[new]**.
- **M4** Breathing is the one autonomic function under voluntary control, giving deliberate access to the ANS. [18.20] — **[new]**.
- **M5** Nasal breathing naturally slows respiration. [18.28] — **[new]**.
- **M6** Consistent breathing/meditation practice trains/strengthens parasympathetic regulation over time. [18.9, 18.16] — **[new]** (relates HIGH Ch18.21).

## CON — Conditioning
- **CON1** A repeated neutral cue (e.g., specific audio) becomes a conditioned signal for calm (classical conditioning). [18.32] — **[new]** (book hedges 528Hz-specific claim).

## SC — Stimulus control & conditioned association (relates N-CBTi)
- **SC1** The brain conditions bed/bedroom ↔ wakefulness vs sleep; in-bed activity (phone, TV, worry) conditions the bed for wakefulness — basis of stimulus control. [12.20, 15.13, 15.14, 17.9] — **[reuse]** =Ch15.16 (CBT-i).
- **SC2** Re-conditioning the bed↔sleep association takes repeated nights/weeks. [15.20] — **[reuse/partial]** Ch15.16.
- **SC3** Get up when you can't sleep / mind racing (stimulus-control instruction). [15.2, 15.8] — **[reuse]** =Ch15.16.
- **SC4** "Don't do daytime activities at night" (behavioural signal). [07.22] — **[T6]** podcast attribution.

## Q — Schedule regularity
- **Q1** An irregular sleep/wake schedule disrupts circadian timing (melatonin rhythm loses its reference). [05.15, 06.13] — **[new]** (relates Ch17.13).
- **Q2** Consistent wake time is the anchor; keep bedtime within ~30 min; hold wake time after a bad night. [16.16, 16.18, 17.12] — **[reuse]** =Ch17.13 (Faust).

## O — Exercise
- **O1** Exercise acutely spikes cortisol (by design); a recovered body clears it within hours; sleep-deprived bodies recover poorly. [20.3, 20.4, 20.8, 02.5] — **[new]**.
- **O2** Both exercise intensity and timing affect sleep. [20.10] — **[reuse/partial]** Ch20.18.
- **O3** Morning exercise works with the cortisol-awakening curve rather than creating a later spike. [20.16] — **[reuse]** =Ch20.17.
- **O4** (Author self-experiment) finish vigorous exercise ~6 h before bed. [20.19] — **[flag]** author's figure vs research 4h (HIGH Ch20.18, itself mixed).

## Z — Somatic movement
- **Z1** Yoga / somatic movement trains the calming nervous system in motion (vagal/parasympathetic). [20.21, 20.22] — **[new]**.
- **Z2** Tai chi & qigong work on the same principle. [20.23] — **[new]**.

## Y — Napping
- **Y1** Naps reduce adenosine/sleep pressure; long or late naps "spend" the pressure needed for night sleep. [19.4, 19.6] — **[new]**.
- **Y2** Standard nap guidance: short (~20 min), not within 7–8 h of bedtime. [19.5, 16.17] — **[new]**.

## V — Hydration (incl. nocturia)
- **V1** Mild dehydration registers as low-level stress, nudging cortisol up. [22.3] — **[reuse]** =Ch22.4.
- **V2** Dehydration impairs the body's ability to cool down (thermoregulation). [22.5] — **[new]**.
- **V3** Thirst lags hydration status — don't rely on it. [22.11] — **[new]**.
- **V4** ~2–3 L/day total fluid is a reasonable adult target. [22.12] — **[new — number]**.
- **V5** Urine colour (pale straw) is a simple hydration marker. [22.14] — **[new]**.
- **NOC1** Elevated cortisol + light sleep make the bladder signal break through (nocturia); nocturnal holding relies on low cortisol & deep sleep. [22.7, 22.8] — **[new]** (author mechanism; vasopressin/nocturnal polyuria literature).

## NOI — Noise
- **NOI1** Sudden noises cause arousals / pull you out of deep sleep, reducing quality. [12.17] — **[new]**.

## R — Food timing (incl. hunger)
- **R1** Eating shifts the body into an active/metabolic state, raising metabolism & core temperature (diet-induced thermogenesis), opposing the cooling sleep needs. [23.3, 23.4, 23.5] — **[new]**.
- **R2** Eating close to bed may ease onset (food coma) but worsens/fragments sleep quality. [23.2, 23.6] — **[reuse/partial]** Ch23.7.
- **R3** ~3-hour pre-bed gap target. [23.8] — **[reuse]** =Ch23.7 (SHF 2–3h).
- **HUN1** Hunger / going to bed hungry is itself a cortisol trigger. [23.10] — **[new]**.

## W — Sugar / glucose
- **W1** The brain runs almost exclusively on glucose and registers a glucose drop as an emergency. [24.12] — **[new]**.
- **W2** Cortisol is a counter-regulatory hormone — it mobilises stored energy / raises blood glucose. [24.13] — **[new]**.
- **W3** Evening/late sugar → spike then reactive crash → cortisol surge disrupts the cortisol-melatonin handover and can trigger 2–3am waking. [24.16, 24.17] — **[new — extension]** (relates HIGH Ch24.11).

## X — Food sensitivities
- **X1** Non-allergic food sensitivities can generate a low-grade chronic immune/inflammatory response. [24.20] — **[new]**.
- **X2** Symptoms are subtle/delayed — disrupted sleep, fatigue, brain fog, bloating, skin, nasal congestion; congestion fragments sleep. [24.21] — **[new]**.
- **X3** Most commonly reactive foods: gluten, dairy, eggs, soy. [24.22] — **[new]**.
- **X4** Elimination-and-reintroduction is the most reliable way to identify a sensitivity. [24.23] — **[new]**.
- **X5** IgG / immune-reactivity food-sensitivity blood tests are scientifically contested and not diagnostic. [24.24] — **[new]** (book flags contested).

## FW / Misc — framework & standalone facts
- **FW1** Sleep depends on multiple hormones rising/falling in a predictable 24-hour rhythm. [03.16] — **[new]** (circadian framework).
- **FW2** Sleeping pills treat the symptom, not the root hormonal misalignment; behavioural approaches address the cause. [04.14] — **[new]** (CBT-i first-line vs hypnotics).
- **SO1** Falling asleep the instant your head hits the pillow signals a large sleep deficit (very short onset latency = sleep deprivation). [01.8] — **[new]**.
- **SS1** Only a very small % of people are true short sleepers who function well on little sleep. [03.13] — **[new]** (DEC2/short-sleeper genetics).
- **CBN1** CBN is a cannabinoid formed when THC degrades, marketed as sleep-targeted; evidence thin. [03.1] — **[new]** (book hedges).
- **BC1** Doing a behaviour-change program with others improves adherence/completion. [09.18] — **[new]**.
- **MOV1** Movement alongside morning light amplifies the circadian signal. [16.11] — **[new — weak/extension]**.
- **HEALTH1** Poor sleep is linked to serious long-term disease. [01.5] — **[reuse]** =Ch03.14.

---

# Step B summary

- **142 MED claims** expanded and mapped above.
- **De-duplicated to 92 distinct facts.**
- **Grouped into 27 topic clusters** (A, B, C, D, E, F, G, H, I, J, U, M, CON, SC, Q, O, Z, Y, V, NOC, NOI, R, HUN, W, X, FW, + misc standalones SO/SS/CBN/BC/MOV/HEALTH).
- **Reuse vs new:** ~22 facts are already sourced in `claim-references.md` (reuse), ~70 need a fresh search.
- **Split stubs:** Ch22.7/8 (bladder) split into the nocturia fact NOC1; Ch23 thermogenesis facts merged into R1.
- **Early flags (carry to C/D):** F2 (alcohol fragments deep sleep — CONTRADICTED in HIGH); O4 (6h exercise margin = author self-experiment vs 4h research); B1 (6h caffeine half-life — number high); V4 & D3 (number checks); I3 (Oura "most research" — verify); CON1/CBN1/X5 (book already hedges).

---

# Step C — T1/T2 authoritative-body sweep results

Verbatims below were retrieved & read this session. Number checks against the book's figure noted.

## Resolved at T1/T2 (new facts)
- **NOI1** — **T1.** WHO Environmental Noise / Community Noise Guidelines (who.int/europe noise fact sheet; corrob. EHP 2022 update to WHO meta-analysis, DOI 10.1289/EHP10197). Quote: WHO recommends "less than 30 dB(A) in bedrooms during the night for a sleep of good quality"; "even at very low noise levels… physiological reactions like increases in heart rate, body movements and arousals can be reliably measured." Number check: NA (book gives none). Supports.
- **V4** — **T1.** EFSA, *Scientific Opinion on Dietary Reference Values for water* (2010), EFSA Journal 8(3):1459, DOI 10.2903/j.efsa.2010.1459. Quote: "a daily intake of 2.0 litres is considered adequate for women and 2.5 litres for men" (total water, incl. ~20% from food). **Number check: book "2–3 litres" is on the HIGH side** — EFSA total-water AI is 2.0/2.5 L (actual fluids ~1.6/2.0 L). NHS quotes ~1.5–2 L fluids. Partial/supports with note.
- **V3** — **T2.** NHS (NHS inform hydration). Quote: "Thirst is a late sign — do not wait until you feel thirsty." Supports.
- **V5** — **T2.** NHS urine-colour charts (multiple NHS trusts). Quote: "Pale straw-coloured urine indicates good hydration… the lighter your pee is, the more likely you are to be hydrated." Supports (book: pale straw good / dark yellow behind / clear = overdone).
- **X5** — **T1/T2.** EAACI Task Force, Stapel SO et al. (2008), *Allergy* 63:793–796, DOI 10.1111/j.1398-9995.2008.01705.x; + AAAAI statement. Quote: "testing of IgG4 to foods is considered as irrelevant for the laboratory work-up of food allergy or intolerance and should not be performed in case of food-related complaints." **Strongly supports** book's "contested, not diagnostic."
- **FW2** — **T1.** ACP guideline, Qaseem A et al. (2016), *Ann Intern Med* 165:125–133, DOI 10.7326/M15-2175. Quote: "ACP recommends that all adult patients receive cognitive behavioral therapy for insomnia (CBT-I) as the initial treatment for chronic insomnia disorder (Grade: strong recommendation)." Supports "pills don't fix the root; behavioural first." (Pairs with HIGH Ch15.16 AASM.)
- **Y1** — **T2.** Sleep Health Foundation (AU), *Napping*. Quote: "a long nap late in the day can make it difficult for you to sleep at night." Supports.
- **Y2** — **T2 (partial).** SHF *Napping*: "Naps should be short; 15–30 minutes is best." Number check: book "20 min max" sits inside 15–30. **The "not within 7–8 h of bedtime" figure is NOT in SHF** — defer that number to D.
- **F3** — **T2/T3.** NIAAA *Alcohol Metabolism*; + Food-effect PK studies. Quote (consensus): "Having a meal just before drinking alcohol will result in a lower, delayed blood alcohol concentration peak"; studies show "reductions in peak alcohol concentration from 9% to 23%." Supports.
- **B2** — **T2.** SHF *Caffeine and Sleep* + NSF data. Quote: "Caffeine can have a significant impact on falling asleep and staying asleep"; NSF profile data: "~88% of people who regularly consume caffeine in the afternoon have also reported at least one sleep problem." Supports "biggest disruptor for many" (directional).
- **C1** — **T2.** SHF / NINDS — melatonin framed as the body-clock *timing signal*, not a sedative. (NINDS: light/dark controls melatonin release; melatonin signals night.) Supports.
- **I1** — **T2/T3.** Baron KG et al. (2017), "Orthosomnia," *J Clin Sleep Med* (AASM journal) 13:351–354, DOI 10.5664/jcsm.6472; AASM 2023 survey (~1 in 3 US adults track sleep). Quote: orthosomnia = patients whose "preoccupation with their sleep data" worsens sleep/anxiety. Supports.
- **Z1/Z2** — **T2 (partial).** NCCIH *Sleep Disorders & Complementary Approaches*; AASM 2021 behavioural guideline. NCCIH: "yoga may be helpful for people with sleep problems"; "yoga and tai chi may help improve sleep quality." Caveat: NCCIH rates the evidence **limited/low-quality**. Supports direction; full strength → D (meta-analyses).

## Concept-confirmed at T1/T2, number/detail pending → D
- **X4** (elimination = most reliable) — implied by allergy bodies (oral food challenge / elimination-reintroduction is the diagnostic standard); needs a clean authoritative verbatim in D.
- **B3** (caffeine masks tiredness → rebound slump) — adenosine-block confirmed (reuse HIGH Ch13.4 NINDS/SHF); the "worse rebound slump" specific → D.
- **D1 / D5** (light/screens at night reduce quality) — relates HIGH Ch06.12 / Ch21.3 / Ch15.21; concept confirmed, dose/threshold → D.
- **Q1** (irregular schedule disrupts rhythm) — CDC/NINDS state consistent schedule matters; clean verbatim → D.

## Not found at T1/T2 → defer to Step D (expect T3–T6)
A2, B4, C3, D4, E3, E6, E7, E9, F2 (CONTRADICTED), G1, HRV1, I3, J1, M1, M3, M4, M5, M6, CON1, SC4, O1, O4, NOC1, R1, HUN1, W1, W2, W3, U1, U2, U3, U4, U5, U6, CBN1, BC1, MOV1, SO1, SS1 (DEC2 ~1/1000 — strong T3 primary lit, Ying-Hui Fu group; concept strongly supported).

---

# Step D — deeper tiers (T3–T6)

## Pass 1 — clusters E (stress/cortisol), F (alcohol), O (exercise), W (glucose), R/HUN (food/hunger), SS/SO

- **E6** (daytime stress → lighter/fragmented sleep) — **T3.** Kim EJ, Dimsdale JE (2007), *Behav Sleep Med* 5:256–278, DOI 10.1080/15402000701557383 (systematic review, 63 studies; PMC4266573). Quote: "Experimental stress resulted in fairly consistent changes: decreases in slow wave sleep, REM sleep, and sleep efficiency (SE), as well as increases in awakenings." Supports.
- **E9** (poor sleepers stuck in activated/hyperarousal state) — **T3.** Riemann D et al. (2010), *Sleep Med Rev* 14:19–31 (hyperarousal model review); Dressle RJ et al. (2023), *J Sleep Res* 32:e13928. Quote: insomnia "characterised by increased physiological, cognitive and emotional arousal… a dysregulation of the HPA axis leads to elevated sympathetic activity and increased cortical activation." Supports. (Caveat: cortisol findings across studies are mixed — Riemann 2002 found no diff; the *arousal* model is robust, the cortisol-specifically piece less so.)
- **E3** (cortisol mobilises for anything urgent; threat = productivity) — **T4 (extension).** Stress-physiology consensus: the HPA/cortisol response is driven by *perceived* psychological demand, not only physical threat (Kim & Dimsdale; hyperarousal lit). Gap: the specific "doesn't distinguish positive-productive arousal from threat" is the author's reasonable framing, not a measured contrast.
- **E7** (frustration loop raises cortisol/arousal) — **T4 (extension).** Follows from E9 (conditioned/cognitive arousal) + HIGH Ch07.20 (sleep loss = stressor). No direct "lying-awake-frustrated raises cortisol" trial pinned; reasonable extension.
- **F2** (alcohol fragments deep sleep → adenosine uncleared) — **T5 / CONTRADICTED.** Reaffirmed from HIGH Ch05.12/14.8: Gardiner 2024 + Ebrahim 2013 show alcohol does **not** suppress slow-wave/deep sleep (Ebrahim: early-night SWS *increases*). The Ch14.11 "fragments deep sleep, so adenosine doesn't clear" mechanism is unsupported. **Flag — same rewrite as HIGH.**
- **O1** (exercise spikes cortisol by design; clears in hours; sleep-dep recover poorly) — **T3.** Hill EE et al. (2008), *J Endocrinol Invest* 31:587–591, DOI 10.1007/BF03345606, PMID 18787373. Quote: cortisol change +5.7% (40%), +39.9% (60%), +83.1% (80% VO₂max); "moderate to high intensity exercise provokes increases in circulating cortisol… low intensity exercise actually resulted in a reduction." Supports — **with nuance: only *moderate-to-high* intensity spikes cortisol; low-intensity lowers it** (consistent with the book's own intensity argument). "Clears within hours" / "sleep-deprived recover poorly" not directly in Hill — the clearance-time piece sits with HIGH Ch20.6 (Kenny 2017, temperature) and is a reasonable read.
- **O4** (finish vigorous ~6 h before bed — author margin) — **T5 / author self-experiment.** Book labels it self-experiment. Research (HIGH Ch20.18, Stutz 2019) supports ~1 h for healthy sleepers; 6 h is conservative and beyond the evidence. Flag: keep framed as personal caution, not "the research says."
- **R1** (eating raises metabolism & core temperature, opposing cooling) — **T3.** Diet-induced thermogenesis reviews (e.g., *J Endocrinol* 2018 238:R75; Saito BNF 2022). Quote: "Within minutes of consuming a meal containing carbohydrate and/or protein… an increase in energy expenditure and body temperature, typically described as diet-induced or meal thermogenesis." Supports (effect is real but modest/transient — DIT ≈ 5–15% of daily energy expenditure).
- **W1** (brain runs almost exclusively on glucose; drop = emergency) — **T2/T3.** Glucose-counterregulation reviews (*Front Neurosci* 2014 8:38, PMC3935387; *Endocr Rev* 2019). Quote: "the brain normally relies on circulating blood glucose as a primary source of energy and accounts for 60–80% of total body glucose uptake." Supports (book's "almost exclusively on glucose" is right; brain is the dominant glucose consumer).
- **W2** (cortisol mobilises stored energy / raises blood glucose) — **T2/T3.** Same counterregulation lit. Quote: "cortisol activates hepatic gluconeogenesis to increase plasma glucose… reduces insulin-dependent glucose uptake." Supports (cortisol is a named counter-regulatory hormone).
- **W3** (late sugar → reactive crash → cortisol surge → 2–3am waking) — **T4 (extension).** Mechanistically chains W1+W2+HIGH Ch24.11 (reactive hypoglycaemia) + Ch07.17 (2am cortisol). Each link sourced; the *specific nocturnal sugar→waking* chain is the author's reasonable extrapolation, not a demonstrated trial. Flag as extension (matches HIGH Ch24.11 caveat).
- **HUN1** (hunger / going to bed hungry triggers cortisol) — **T3 (with gap).** Fasting–cortisol meta-analysis (Nakamura/Soeters lineage; Stress 2016 meta: "fasting showed a very strong effect in increasing serum cortisol"); Bergendahl 1996 (5-day fast → 1.8× cortisol production). Supports the *direction*. **Gap:** evidence is for sustained fasting; a single skipped-dinner "hunger at bedtime" is a milder extension.
- **SS1** (only a tiny % are true short sleepers) — **T3.** He Y et al. (2009), *Science* 325:866 (DEC2); Shi G et al. (2019), *Neuron* (ADRB1); reviews note natural short sleepers are rare (~1 in 1,000 carry DEC2; familial short sleep is uncommon). Supports "very small percent."
- **SO1** (falling asleep instantly = large sleep deficit) — **T3.** MSLT scoring + sleep-latency literature: mean sleep latency <5–8 min indicates pathological sleepiness/sleep debt; deliberate sleep deprivation drives latency below 1 min. Supports book's "head hits the pillow… huge deficit." (Caveat: very short latency can also flag apnea/narcolepsy — sleep debt is the common cause.)

## Pass 2 — clusters U (dopamine/media), M (vagus/breathing), CON (conditioning), HRV

- **U1** (dopamine = reward/opportunity/anticipation, "worth pursuing") — **T3.** Berridge KC (2007), *Psychopharmacology* 191:391–431 (incentive-salience / "wanting"); Schultz W (reward-prediction). Quote: dopamine codes "incentive salience ('wanting')" and "reward anticipation… dopaminergic activation prior to reward." Supports the book's dopamine-as-anticipation/motivation framing.
- **U5** (we respond most reliably to provocative/negative content) — **T3.** Soroka, Fournier, Nir (2019), *PNAS* 116:18888 (17-country psychophysiology study); Baumeister "bad is stronger than good." Quote: "negative information has a stronger influence on human attention, cognition, and emotion compared to positive information." Supports.
- **U4** (games/feeds engineered to exploit dopamine via variable reward) — **T3 (mechanism) / T4 ("engineered").** Variable-ratio/random-ratio reinforcement maximises dopamine release (behavioural-neuroscience consensus; slot-machine analogy); persuasive-design critique (Tristan Harris). Supports the variable-reward mechanism; "deliberately engineered" is well-argued but partly a design-ethics claim, not a lab finding.
- **U3** (provocative & curiosity content both drive dopamine; provocative adds cortisol) — **T4 (extension/synthesis).** Curiosity → reward/dopamine (U1); provocative/negative → stress/cortisol (U5 + Kim & Dimsdale stress lit). Reasonable synthesis; no single source makes the exact dual claim.
- **U2** (fast/variable digital stimuli desensitise / recalibrate the reward system) — **T5 (contested).** Some support (e.g., reduced striatal dopamine receptor availability in heavy users) but most popular citations are non-peer-reviewed; **no strong systematic review establishes the "screens cause dopamine desensitisation" claim** — actively contested among neuroscientists. **Flag: soften / present as hypothesis.**
- **U6** (passive predictable TV less activating than interactive/novel media) — **T4 (extension).** Follows from U1/U4 (novelty + unpredictability drive dopamine; predictable low-stakes content less so). No direct head-to-head source. Reasonable.
- **M1** (ANS = sympathetic activating vs parasympathetic calming) — **T2.** Textbook physiology (e.g., NCBI Bookshelf / StatPearls, Autonomic Nervous System). Established; sound as a simplification.
- **M3** (vagus is bidirectional, ~80% afferent; body-to-brain) — **T3.** Berthoud HR, Neuhuber WL (2000), *Auton Neurosci* 85:1–17; widely cited "vagus is ~80% afferent." Quote: "the vagus nerve is a mixed nerve composed of 80% afferent and 20% efferent fibers… a two-way communication highway." Supports.
- **M4** (breathing = the one autonomic function under voluntary control → ANS access) — **T3.** Slow-breathing autonomic literature (Russo 2017 — HIGH Ch18.18; HRV-BF). Supports the mechanism; "the *only* organ off autopilot" is a slight overstatement (rhetorical) but breathing is uniquely voluntarily controllable among autonomic outputs.
- **M5** (nasal breathing naturally slows respiration) — **T4.** Basic respiratory physiology (higher nasal airway resistance limits airflow/over-breathing). No single authoritative verbatim pinned this session; physiologically sound, source can be firmed up.
- **M6** (consistent breathing/meditation trains/strengthens parasympathetic regulation) — **T3.** HRV-biofeedback literature; Lehrer & Gevirtz (2014), *Front Psychol* 5:756; Lehrer 2003 (baroreflex neuroplasticity after 3 months of HRV-BF). Quote: slow-paced breathing (~0.1 Hz) "increases the baroreflex activity"; HRV-BF produces "autonomic activity characteristic of relaxation." Supports the "nervous-system strength training" framing (pairs with HIGH Ch18.21).
- **CON1** (a repeated neutral cue becomes a conditioned calm signal) — **T2/T3 for the principle** (classical/Pavlovian conditioning is foundational psychology). **The 528 Hz–specific "frequency aids sleep" claim = T6/NONE** — but **the book already hedges it** ("Some claim the frequency itself aids sleep, but the more important point is… I've made it my meditation music"), so the conditioning point stands and the 528Hz part is appropriately caveated.
- **HRV1** (HRV reflects autonomic balance; higher = better recovery/resilience) — **T3, with caveat.** Shaffer F, Ginsberg JP (2017), *Front Public Health* 5:258 (PMC5624990). Quote: "High HRV indicates high vagal tone, which reflects parasympathetic nervous system activity"; higher resting vagally-mediated HRV linked to better self-regulation. **Caveat (flag):** the simple "balance of two modes" / LF-HF reading is an oversimplification — Shaffer notes "PNS and SNS interactions are complex, non-linear… uncertainty regarding… contributions to the LF/HF ratio." The book's "higher HRV ~ better recovery" is sound; the "balancing its two modes" gloss is a simplification.

## Pass 3 — remaining tail (A2, B3, B4, C3, D1, D4, D5, Q1, G1, I3, J1, NOC1, CBN1, BC1, MOV1, SC4, X4)

- **C3** (melatonin lowers core temperature & alertness) — **T3.** Cagnacci A et al. (1997), *J Biol Rhythms* 12:509; Lok R et al. (2019), *J Pineal Res* 66:e12583. Quote: "melatonin decreases core body temperature" (~0.2–0.4 °C); daytime melatonin "coincided with decreased subjective alertness." Supports.
- **Q1** (irregular schedule disrupts circadian timing) — **T3.** Social-jetlag / sleep-regularity literature (Wittmann/Roenneberg; Sleep 2020 zsaa076). Quote: circadian misalignment from irregular schedules "almost always leads to chronic sleep debt… shorter, lower-quality sleep." Supports.
- **J1** (supplement form/extract changes bioavailability) — **T3.** Magnesium-bioavailability systematic review (*J Funct Foods* 2021); Lindberg 1990 (citrate > oxide). Quote: "Organic forms of magnesium… are more bioavailable than inorganic forms." Supports the book's general "form matters" point.
- **X4** (elimination-and-reintroduction = most reliable for sensitivities) — **T2/T3.** Allergy/clinical consensus (EAACI; clinical guides). Quote: "the elimination diet is recognized as the gold standard in identifying non-IgE, nonanaphylactic food sensitivities and intolerances." Strongly supports.
- **D4** (light-therapy lamp substitutes for morning sun) — **T2/T3.** Bright-light-therapy literature (SAD/circadian; AASM circadian guideline). 10,000-lux lamps "mimic… daylight," used ~20–30 min in the morning to regulate circadian rhythm. Supports.
- **I3** (Oura has the most published validation research) — **T3 / verify (supported).** Oura Gen3 PSG validation (Sleep Med 2024, 96 participants/421,045 epochs); Sensors 2024 (Brigham & Women's) rated Oura most accurate in 4-stage staging (~79% agreement). Supports — **but note many studies are Oura-funded; the book's own hedge ("might mean most accurate, or might just mean it publishes most") is fair.**
- **CBN1** (CBN is a THC-degradation cannabinoid marketed for sleep; evidence thin) — **T3/T6.** Reviews: "Cannabinol (CBN) is a mildly psychoactive cannabinoid formed from the degradation of THC"; "scant objective scientific evidence to support CBN's use as a sedative/hypnotic." **Supports the book's skeptical framing** (book reports the "even more targeted than CBD" line as a forum claim it doubts — evidence does *not* support CBN > CBD for sleep).
- **BC1** (doing the program with others improves adherence/completion) — **T3.** Behaviour-change/adherence literature; group-exercise review (J Behav Med 2011): "group exercise participants were more likely to stick with programs… due to social reinforcement"; supportive-accountability model. Supports.
- **A2** (adenosine is technically a neuromodulator/neurotransmitter, not a hormone) — **T2/T3.** Established neuroscience (adenosine = neuromodulator; Reichert 2022 — HIGH; Fredholm adenosine reviews). Book's footnote is accurate. Supports.
- **B3** (caffeine masks tiredness → worse rebound slump) — **T3 (reuse + extension).** Adenosine-receptor block = reuse HIGH Ch13.4 (NINDS/SHF). The "worse rebound slump when it wears off" follows from accumulated adenosine flooding back + the circadian afternoon dip — reasonable; no single trial pinned for the "worse" magnitude.
- **D1** (light at night = wake signal; even low light lowers quality) — **T3 (reuse-adjacent).** HIGH Ch06.12 (light suppresses melatonin) + Ch15.21 (dim-light melatonin suppression, ED50 ~25–100 lux, big individual range). Supports the direction; "even low light" is person-dependent.
- **D5** (screens fragment sleep — light + notifications + checking) — **T2/T3 (reuse-adjacent).** HIGH Ch21.3 (NSF consensus: pre-bed screen *content* impairs sleep). Supports; the device light is the weaker part (content/arousal dominates).
- **B4** (delay first coffee 60–90 min; it competes with the cortisol-awakening surge & adenosine clearance) — **T4 (weak / popular).** Widely promoted (e.g., Huberman) but **the morning cortisol–caffeine-tolerance evidence is limited/contested**; the book itself concedes "it appears to train the body" and "I can't point to a sign on my tracker yet." Flag: present as a reasonable, low-confidence tip, not established science.
- **NOC1** (elevated cortisol + light sleep make the bladder signal break through; night holding relies on low cortisol & deep sleep) — **T4 (author mechanism).** Nocturnal polyuria/nocturia is real (vasopressin rises overnight; lighter/fragmented sleep → more awareness of bladder). The specific **cortisol→nocturia** link is the author's mechanism, plausible but not directly demonstrated. Flag as extension.
- **MOV1** (morning movement amplifies the light/circadian signal) — **T4 (weak/extension).** Exercise has modest circadian phase-shifting effects, and pairing with morning light is sensible, but "amplifies the light signal" specifically is an extension, not a measured additive effect.
- **G1** (temperature is the environmental factor most directly tied to sleep quality) — **T6 (author framing).** The underlying point — temperature strongly affects sleep quality — is well supported (HIGH Ch12.13, Okamoto-Mizuno). The comparative superlative "*the most* direct" is the author's framing, not a ranked finding. Soft flag.
- **SC4** ("don't do daytime activities at night") — **T6 / reuse.** Podcast attribution in the book; the underlying principle = stimulus control (reuse HIGH Ch15.16, AASM CBT-i). Sound as behavioural advice; weak as a standalone citation.
