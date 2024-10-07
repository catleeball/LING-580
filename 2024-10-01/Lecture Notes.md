Dr. Wright's second fav class: Experimental Phonetics

Seminars have no prereqs, note if things get too much

Not a lecture class like it is today or next week

Normally everyone goes does readings, discuss (ideally)

This class: first half logistics, second half into crash course on perception & bias

CLMS students who need this for elective credit: take the 4 credit version , otherwise you can do 2cr

May be that you don't have to present a paper

## Final project overview

If taking 4cr, you have a project at the end of the quarter; open to what it is, could be a software tool, could be a review paper where you summary and crit papers, other is develop idea for project and defend and discuss it. can also be an experiment hypothesis (e.g. some stimuli for testing) but probably too big for 10 week; can be clms thesis, but probably will need a lot of extra work

teams are okay for final project as long as they're equitable work; 2 or 3 probably fine; solo also totally fine

Due: Thursday of finals week (pls no extensions, maybe aim for tuesday as your due date)

Want ling PhDs to write about perception and not LLMs, but fine for CLMS students

## Logistics

Note grading proportions diff for 2cr vs 4cr (see syllabus)
- 2cr: 100% participation
- 4cr: 50% participation / 50% final project

Canvas > Syllabus
- schedule
	- click each schedule event to see what to read if there's something there
	- papers can be found in Canvas > Files
- TBD students can bring up / present papers they might want to read & discuss
	- suggest them at least 1 week in advance

papers aside

- babel on perception better if speaker is perceived as beautiful 
- shanon's entropy
- sumby pollack paper on how visual info is import

Canvas > Discussions
- Topic discussions
	- talk about papers especially if you prefer text-based comms
- Logistics discussions
- Readings
	- Can add new readings & attach their file
	- Say what paper is, summary, citation, attach paper, attach any visuals


- prior bias in speech stream
- listeners perceive things based on probability of next token
- Even when chunks missing people percieve they have full info
	- surprisal
		- inverse log of probability
		- shanon's entropy
- form of context from the speech stream
	- can also come from things like location
	- you might say "formant" louder at a football field since people are less expecting it. you might not enunciate "formant" so much when discussing in a phonetics lab
		- the horrors of lang models using your location to predict text
- bias - changes the probability
	- visual bias: watch (some) of the articulators move
		- not critical to process given disparities 
		- not uniform amount of bias 
		- mcgirk effect is not very reliable / very reliable for some people
- visual bias
	- hair style (according to johnson and strand) largest determiner of gender
		- seeing static picture and audio 
		- (someone Minnesota) perceived gayness and bias
	- conflicting signals (e.g. multilingual dubbed movies like old kung fu movies dubbed)
	- perceived bias of non-native speaker
		- perceived non-native speaker tend to be graded harder
		- (not about auditory perception, but *is* about bias)
	- dialect bias 
	- ties into sexism / racism / homophobia
	- Q: paper on video of police officers treating people of perceived race differently
		- that might be production bias rather than perception
	- Q: sentiment analysis machine is just a bias machine?
		- yes
		- but depends on what you mean by bias
		- machine determines bounds of sentiment 
	- pragmatics (a piece of sentiment) impacts surprisal
- surprisal
	- basically probability of next word in a string of words given lots of priors
	- usually train on one corpus and test on another to avoid overfitting

By next week:
- everyone has grabbed a date
- paper can be tbd still but grab a date
- find to grab a not-tbd paper (e.g. pre-assigned paper)
- 4cr students get precedent 
- it's fine to come to class with questions / confusion about paper to discuss

Probably by end of next week you'll have an idea after doing a few readings
- if you're worried about taking a TBD slot, don't take a TBD slot

LING 575 currently occurring about data infrastructure creating biases in LLMs
- taught by Amanda Lynn
- still has openings for class
- perceptual (and/or financial, and/or structural) bias in LLMs


---

## Slides notes

### The ear

outer ear - concha and ear canal
- single tube resonator (2n-1c/4L)
- ear canal is kinda a schwa
	- short canal that amplifies higher frequencies
	- orientation impacts attenuation 
	- amplifies >= 3kHz
- bigger ears we could hear better

middle ear - ossicles (bones)
- hammer, anvil, stirrup
- connects to tympanic membrane 
- lever system to overcome air/fluid impedence
	- contracts/expends

inner ear
- cochlea
	- slide 10 has saggital view, snail shell shape
	- slide 11 side view
- peaks in pressure wave excite different parts of cochlear membrane 
- as vibration travels up, membranes vibrate against cilia
	- builds up nerve signals which fire when they become sufficiently excited
		- in this way, firing of nerve fibers digitize signal at a certain frequence
	- tonotopic distribution of fibers across the membrane
		- deflect sound, stimulate cilia, excites nerves at certain frequencies 
- nerve fibers not evenly distributed along cochlia 
	- more sensative to higher freq
	- structured simultaneous firing of nerves for periodic sounds
		- helps hear vowel sounds better with lots of background noise
	- (q: how does this tie into brain audio processing)
	- slide 12: nerves, cilia 
- right ear goes to left hemisphere more than left; vice versa
	- each ear fires to both sides, but bias
	- studies about lang understanding differing between ears maybe due to brain half 
- sounds that are loud get broken up as the go up the pathway
	- sounds with suddent changes get amplified as the go up the pathway
		- diverges from spectrograms that doesn't take as much perception into account
		- nowdays:
			- MELS MFCC
			- BARQ wave modeling 
		- end of sounds codas get less amplified
		- beginning of sounds onsets get more amplified
	- brain stem imaging
		- far field recording electrography
		- see formants in stem and as they distrort
		- not great for speech generally though limit of freq detected
- filled with fluid, has cillia
- go underwater, can't hear, because water denser medium and surface of water refracts sound off


brain (slide 12)
- STG
- SPT
- Brochas area
- IFG
- MTG
- dorsal (sub-lexical)
- ventral: sound-lexical (sound meaning processed)

phonetic to gestural mapping a lot in IFG and STG

infants develop mappings of auditory patterns and gestural patterns even before their articulatory anatomy (like tongue tip for D and T sounds) has developed enough to create those sounds

Q: does this happen in music (auditory motor mapping)
A: not sure; tone language learners differ in processing area
- starts in (some area) then (some other area) (missed a bunch here, still on slide 12 for recording)
- motor cast simpler for playing something like violin, speech processing more complex, but we (generally) automatically learn this


Hickok & Poeppel: model of cortican network
- weak connection from motor mapping to sound to auditory-motor interface 
	- not important to answering question, brain filters out this extra signals
- gestural info might or might not be useful depending on task
- hit a button when you hear (sound ba/da/ga) biased against ventral interface since no lexical mapping
- word recognition will need more ventral 
- before this, people would assume this region would always be implicatied, bias in experiment design

be careful of experiments- testing with specific stimuli gives specific results; there's a lot going on in speech perception, be careful when generalizing results

lateralization depends on a lot; left-right-ambidextrous, gender, etc
- changes in this happens at puberty
- Q: second puberty?

(someone) wrote about musicians being better at speech perception
- tones have shape, not tested against tonal language speakers who also have this
- "mandarin is more about shape than tone (but is still a tonal language)"
- different than pitch accent
- tone langs have register tones and shape tones
	- first tone in mandarin (first for historical reasons) is high tone
	- rising tone
	- dipping tone
	- sharp fall tone
- tone shape makes mandarin easier to distinct mandarin tones
- (something about zero tone / neutral tone, missed it)
	- unspecified to use this 
- "musicians must be listening to tones" no (some more words)
- tests to freq sensitivity / combined freqs
	- musicians tend to be better listening

Two sides talk to each other
- dorsal up to parietal
- or
- ventral (do these sounds use same articulators?)

note color areas are averages of many many participants; individual listeners are more all over the place

a lot of stuff in experimental percpetion should be take w grain of salt; many may be specific to task


Canvas > Loudness something something these from 553

## Sensation of loudness

- loudness non-linear
	- different kinds: slide 2
- specific to mammals
	- studies on chincillas,
- odo-acoustic emissions
	- ear makes tiny sounds when hearing
	- can be used to measure hearing loss kinda

Q: does this look same in ocean mammals?

- no, those different
- but zebra fish and zebra finch can regrow their hair cells in their ears
	- finches that sing so loud they deafen themselves but they regrow hairs
- humans evolved their hearing from fish, nerves down from ears along jaws

Q: echolocation study on bats, put them on swings something something
A: chemicals do this too, lost a lot of my hearing when working peace corps fed us (something toxic) and also got cerebral malaria 

Tiny animals with tiny heads have same shape, but their tiny chochleas are tuned for high freqs. elephants hear subsonic sounds

slide 3: sensitivity
- amplitude to freq "equal loudness scale" stevens 1936
- adjusting volume for different tones to hear
- speech signals mainly 100 -10k hz
	- mostly below 3k hz

since our hearing hasn't changed much in evolution, but our vocal tracts have, it's thought our vocal tracts have evolved in response to our hearing
- apes can't move velar can't make velar sounds, only nasal
- taught apes to hold nose and release to make speech bursts 
- to make oral stop, velum needs to be up
- speech ready posture, even if nasal, we start by moving our posture
- posture and tongue change position and CO2 sensor off when readying for speech production
- when you have a cold, de-nasalize sounds, nose too stuffy for air move and P becomes B
- human language tended to evolve toward loudness sweet spot

(fun fact decibels are from alexander grahm bell and deci- since we needed to adapt from original scale)

Sones are more accurate for hearing system loudness & perception (kinda logrithmic but not quite)

Freq response is non-linear
- linear: hz
- equal freq: ...
- ... bark
- missed it see slide (6 or 7)
have an auditory demo for this not for this 

spectrograms are linear freq, not pay attention to shaping of sound in our perception


saturation and masking
- slide 9
- simultaneous masking
	- 
- upward spread of masking
	- low freq good at masking high freq sounds
	- has to do with choclear structure and how auditory nerves fire
- saturation happens when we get systematic phase locking and the nerves are looking for a certain tone
	- gets fatigue at 20ms, gets progressively less sensitive 
	- gets worse at locking on over time
	- hearing more sensitive to beginning of sound
	- amplitude or freq sound at end of syllable is harder to percieve than beginning 
	- only first 20ms is faithfully encoded, then gets rougher
	- hence almost all languages have onsets
		- codas less, and usually loud sounds

q: missed it
a: missed start of it

- if i hold hand in front of space, make a sound that's not a word, it's hard to tell onsets without lexical recovery
	- fujimori study in japanese listeners; jp listeners worse at codas then en listeners
	- reverse these phonmes and fine
	- (go back over this part I missed a bunch of this so these notes suck)
	- even when no lexical context, sound diffs still observed but not necessarily connected

forward masking slide 11
- onset gets exaggerated
- formant transition is 40ish ms
- you usually get the beginning and direction of format, but get noisier audio transitions at end 
- place of articulation --- missed
- nasals are more poorly perceived than stops

Distribution of info
- Cues
	- slide 11
	- place, manner, voicing, vowel quality
	slide 13- place cues illustration 
	coda sounds tend to get lost as langs change and onsets kept
	fricatives are reliable cue
	onsets are good cues without masking
	theta needs more info, look at place of articulation and lexical info and context
	french guy studies theta: remove S from an S-starting word and you get a theta
	nasals, cues aren't well encoded

- manner cues slide 14
	- tongue moves more gradually out of fricatives and have gradual transitions
	- amplitude envelope tells a lot about mannar

- voicing cues are most complex
	- most stops don't have periodicity
	- vot strong cute but composite cue
		- less reliable if something like release burst is lost
