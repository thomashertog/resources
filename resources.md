#Table of contents

1. [General design](#general_design)
	1. [Interaction design](#interaction_design)
		1. [Information architecture](#information_architecture)
	2. [Personas](#personas)
	3. [Form design](#form_design)
	4. [Copywriting](#copywriting)
	5. [Process](#process)
	6. [Style guides](#style_guides)
	7. [Visual design](#visual_design)
		1. [Typography](#typography)
2. [Research](#research)
3. [HTML](#html)
4. [CSS](#css)
	1. [Flexbox](#flexbox)
	2. [Grid](#grid)
5. [SASS](#sass)
6. [Responsive Web Design](#responsive_web_design)
7. [Progressive enhancement](#progressive_enhancement)
8. [Accessibility](#accessibility)
9. [Performance](#performance)
10. [Web components](#web_components)
	1. [Polymer](#polymer)
11. [Design testing](#design_testing)
12. [Email design](#email_design)
13. [Web Fonts](#web_fonts)


#<a name="general_design"></a>General design

* [Good UI](http://goodui.org/)
	* Try __a one column layout__ instead of multicolumns
	* Try __giving a gift__ instead of closing a sale right away
	* Try __merging similar functions__ instead of fragmenting the UI
	* Try __social proof__ instead of talking about yourself
	* Try __repeating your primary action__ instead of showing it just once
	* Try __distinct clickable/selected styles__ instead of blurring them
	* Try __recommending__ instead of showing equal choices
	* Try __undos__ instead of prompting for confirmation
	* Try __telling who it's for__ instead of targeting everyone
	* Try __being direct__ instead of indecisive
	* Try __more contrast__ instead of similarity
	* Try __personality__ instead of being generic
	* Try __fewer form fields__ instead of asking for too many
	* Try __exposing options__ instead of hiding them
	* Try __suggesting continuity__ instead of false bottoms
	* Try __keeping focus__ instead of drowning with links
	* Try __showing state__ instead of being state agnostic
	* Try __benefit buttons__ instead of just task based ones
	* Try __direct manipulation__ instead of contextless menus
	* Try __exposing fields__ instead of creating extra pages
	* Try __transitions__ instead of showing changes instantly
	* Try __gradual engagement__ instead of a hasty sign up
	* Try __fewer borders__ instead of wasting attention
	* Try __selling benefits__ instead of features
	* Try __designing for zero data__ instead of just data heavy cases
	* Try __opt-out__ instead of opt-in
	* Try __consistency__ instead of making people relearn
	* Try __smart defaults__ instead of asking to do extra work
	* Try __conventions__ instead of reinventing the weel
	* Try __loss aversion__ instead of emphasizing gains
	* Try __visual hierarchy__ instead of dullness
	* Try __grouping related items__ instead of disordering
	* Try __inline validation__ instead of delaying errors
	* Try __forgiving inputs__ instead of being strict with data
	* Try __urgency__ instead of timelessness
	* Try __scarcity__ instead of abundance
	* Try __recognition__ instead of recall
	* Try __bigger click areas__ instead of tiny ones
	* Try __faster load times__ instead of making people wait
	* Try __keyboard shortcuts__ instead of buttons only
	* Try __anchoring__ instead of starting with the price
	* Try __upfront progress__ instead of starting with a blank
	* Try __progressive disclosure__ instead of overwhelming
	* Try __smaller commitments__ instead of one big one
	* Try __softer prompts__ instead of modal windows
	* Try __multifunctional controls__ instead of more parts
	* Try __icon labels__ instead of opening for interpretation
	* Try __natural language__ instead of dry text
	* Try __curiosity__ instead of being reserved
	* Try __reassurances__ instead of assuming all is fine
	* Try __price illusions__ instead of just plain prices
	* Try __thanking__ instead of simply confirming completion
	* Try __useful calculations__ instead of asking to do math
	* Try __reaffirming freedom__ instead of implying it
	* Try __variable rewards__ instead of predictability
	* Try __attention grabs__ instead of neglect
	* Try __friendly comparisons__ instead of confusion
	* Try __set collections__ instead of independent items
	* Try __expectation setting__ instead of being ignorant
	* Try __humor__ instead of being so serious
	* Try __providing feedback__ instead of silence
	* Try __anticipating intent__ instead of shortsightedness
	* Try __extra padding__ instead of overcrowding elements
	* Try __storytelling__ instead of listing just the facts
	* Try __authenticity__ instead of faking it
	* Try __progressive reduction__ instead of being static
	* Try __putting others first__ instead of self-centeredness
	* Try __explainging__ instead of assuming the obvious
	* Try __concise copy__ instead of using unnecessary words
	* Try __responsive layouts__ instead of static ones
	* Try __visual clarity__ instead of ambiguity
	* Try __enabling corrections__ instead of rigidness
	* Try __social commitments__ instead of solitude
	* Try __retries and redos__ instead of single chances
	* Try __less choice__ instead of giving too many options
* [UX: Less isn't always more](http://java.dzone.com/articles/ux-less-isnt-always-more)
	* reset password form
	* microcopy

 ![UX vs UI](http://editorial.designtaxi.com/editorial-images/NEWS-INFUIUX100615/4.jpg)

* [The 10 laws of simplicity](http://lawsofsimplicity.com/)
	1. __Reduce__ The simplest way to achieve simplicity is through thoughtful reduction
	2. __Organize__ Organization makes a system of many appear fewer
	3. __Time__ Savings in time feel like simplicity
	4. __Learn__ Knowledge makes everything simpler
	5. __Differences__ Simplicity and complexity need each other
	6. __Context__ What lies in the periphery of simplicity is definitely not peripheral
	7. __Emotion__ More emotions are better than less
	8. __Trust__ In simplicity we trust
	9. __Failure__ Some things can never be made simple
	10. __The one__ Simplicity is about subtracting the obvious, and adding the meaningful
* The 3 keys of simplicity
	1. __Away__ More appears like less by simply moving it far, far away
	2. __Open__ Openness simplifies complexity
	3. __Power__ Use less, gain more 
* 7 future web design trends (May 6, 2015)
	1. Gestures are the new clicks
	2. The fold really is dead this time
	3. Users are quicker, websites are simplifying
	4. The pixel is dead
	5. Animation is back
	6. Components are the new frameworks
	7. Social saturation and the rise of direct email
* [5 elements of omni-channel user experiences](http://uxmag.com/articles/5-elements-of-omni-channel-user-experiences)
	* Consistency
	* Availability
	* Channel-Neutrality
	* Context-Optimisation
	* Seamlessness
* [Hermeneutics for designers](http://www.uxbooth.com/articles/hermeneutics-for-designers/)
	* The history of hermeneutics
		* Horizon of understanding
		* Prejudices
		* Conversation as a model for understanding
	* Applying hermeneuticsn
		* What does he mean by mature thought
		* How can we reduce time spent in mechanical thought
	* Next steps
* [Improving the user experience can save time and money](https://boagworld.com/usability/nationaltrust/)
* [On the device context continuum](https://medium.com/@grigs/on-the-device-context-continuum-515d95ef8829)
* [15 UX Commandments](http://thehipperelement.com/post/128705195169/15-ux-commandments?ref=heydesigner-weekly37)
	1. Only ask the questions to whith you really need answers.
	2. Demonstrate uncertainty
	3. Reconstruct your own previous errors of thought and elucidate to your colleagues and clients what factors lead to a changed mind
	4. Do not let the terms with which you understand the world get in the way of understanding it ("your view of the world might be wrong")
	5. Give up any desire to be the smartest person in the room
	6. Remember that people -including you- have bodies, and bodies require movement, sustencance, rest, and relief
	7. Leave room for creativity
	8. Preserve and sustain whatever delusions you've found necessarry to behave in good faith
	9. Do not be afraid to state the obvious
	10. A socratic bully is still a bully
	11. Thoroughly prepare, including making preparations to abandon your preparations entirely
	12. Listen with your body
	13. Suspect charisma
	14. Conduct yourself in such a way that your colleagues can eventually forget that you exist
	15. It never hurts to start with the basics  
* [6 Web design mistakes (and how to correct them)](http://thenextweb.com/dd/2015/08/26/6-web-design-mistakes-and-how-to-correct-them/)
	1. Designing without a grid
	2. Using a theme without customization
	3. Moving forward with poor images
	4. Not using a color or typography palette
	5. Overcomplicated navigation
	6. Site is slow to load
* [Usable content is king](http://usabilitygeek.com/usable-content-is-king/)
	* What makes content usable
		* Consider form as well as function
		* Quality means usability
		* Ensure maximum shareability
		* Publish content in style
		* Fostering usable content ought to be a OneTwo punch
* [Video + transcript: Sara Wachter-Boettcher - Everybody hurts - Content for kindness](http://www.sarawb.com/2015/09/10/everybody-hurts-content-for-kindness/)
* [10 common web developer mistakes](http://code.tutsplus.com/articles/10-common-web-developer-mistakes--cms-24791)
	1. Writing old-school HTML
	2. It works in my browser ...
	3. Bad form
	4. Bloated responses
	5. Creating code that _should_ work
	6. Writing forking code
	7. Designing unresponsively
	8. Making meaningless pages
	9. Producing sites that are too refreshing
	10. Working too much
* [10 guidelines for navigation usability](http://usabilitygeek.com/10-guidelines-for-navigation-usability/)
	1. Embrace predictability
	2. Keep it simple
	3. Don't overdo minimalism
	4. Keep it consistent
	5. Clear hierarchical structure
	6. Make it manageable
	7. Link the logo to the homepage
	8. Include a sitemap
	9. Provide more than one navigation menu
	10. Always include a search bar
* [The 8 worst UX mistakes coming from experts](https://medium.com/swlh/the-8-worst-ux-mistakes-coming-from-experts-692884971f80#.bx9b2rbhc)
	1. Expecting the unexpected (Be clear - Make sure that every item in your project has a purpose, and that it communicates its purpose immediately)
	2. You spin me round (Remove image sliders, carousels, and clickbaiting pagination. Be clear and honest, as no one wants to struggle with the dark side of web design)
	3. Immobile pages (Don't force your users to download your mobile app so they can browse your website)
	4. The art of bad performance (Do not forsake performance for the sake of aesthetics)
	5. Everybody hates reading (Content serves the web right now, so it is crucial to make it easy to digest. Give people a nice read)
	6. Your forms are out of form
	7. Sign in? Sign OUT
	8. Simplify
	
##<a name="interaction_design"></a>Interaction Design

* [Designing Settings](https://medium.com/@imran_parvez/designing-settings-b2a96878961b?mc_cid=ec02ba64fc&mc_eid=b38f2f4652)
	> Products should work for the user and not the other way around
	
	> Not everything is a setting
	
 ![What should be a setting](https://d262ilb51hltx0.cloudfront.net/max/720/1*nygSPS923t8c-ZWhPH1rDg.png)

* [Consider the empty states](http://webdesign.tutsplus.com/articles/ux-tip-consider-the-empty-states--cms-23692)
	* First-use
		* clear explanation
		* link to populate that feature
		* provide an on boarding sequence
	* User-cleared
		* something is better than nothing
		* direct and straight to the point
	* Error
		* appropriate for the situation
		* offers more information
* [The 10 principles of interaction design](http://www.creativebloq.com/netmag/10-principles-interaction-design-1143871)
	1. Start with two
	2. Prototype
	3. Use patterns and prediction
	4. Trick people
	5. Tell stories
	6. Use but don't abuse metaphors
	7. Don't be a dick
	8. Make novices experts
	9. Be a humble expert
	10. Seek your failures
* [The perception of control](http://www.uxbooth.com/articles/the-perception-of-control/?utm_medium=feed&utm_source=FeedPress&utm_campaign=Feed%3A+uxbooth+%28UX+Booth%29à)
	> Every day at the street by my house, I press the "walk" button, and I wait. Each time, as soon as the traffic cycle is complete, I get the walk signal. On a whim, one day I din't press the button... but at the end of the traffic cycle, I got the walk signal. The button I press every day has absolutely no impact on when the light will change. Is it still worth having the button?

* [Masking passwords: help or hindrance](http://www.sitepoint.com/masking-passwords-help-or-hindrance/)
	* problems with password masking
		* masking the password also hides it from the user
		* "over the soulder" attacks aren't as common as we may think
		* the password is still vulnerable to keylogging and malware
		* the design of some mobile operating systems eliminates some benefits of masking
	* Balancing security and usability
		* "Show password" toggle: proven results
* [What you need to know about anticipatory design](http://www.smashingmagazine.com/2015/09/anticipatory-design/)
	* It's always been around
	* Why anticipatory design? Why now?
	* Anticipatory design and cognitive load
	* Anticipatory design and empathy
	* Examples of great anticipatory design
		* Facebook: using geolocation to facilitate real-life encounters
		* Saleswise: how to turn collected data into meaningful time savers
		* Pandora: recommendations based on relevance
		* Brita: how to make repeat purchases much simpler
		* Meetup: recommendations based on user interests
		* Expedia: offer ideas beyond purchase
		* Credit karma: how to anticipate cross-selling opportunities
		* Fandango: finding relevant opportunities to add a "little extra" value
		* Microsoft Delve: automatically tailoring the experience to your user's preferences
		* Turbotax: transpartently combine additional forms based on user inputs
	* A checklist to get started with anticipatory design
	* Anticipatory design: the new standard
* [Are users ready for the desktop hamburger icon?](http://www.sitepoint.com/are-users-ready-for-the-desktop-hamburger-icon/)
	* The good
		* The "clean factor"
		* Let your CTA (Call To Action) be the hero
		* The power of popularity
	* The not-so-good
		* Another click, another barrier
		* Out of sight, out of mind
	* Best uses
		* Simple sites with few pages/little content
		* When it's obviously clickable
		* Paired with a CTA
	* Worst uses
		* On a site aimed at older demographics
		* Sites with unexpected content
* [Video: Mobile Design Essentials - Multi-Device Output, input and posture](https://www.youtube.com/watch?v=ZhnN1CdwvTs)
* [UX Design tips for your app](http://sixrevisions.com/user-experience-ux/ux-tips-app/)
	* The UX should adapt to the user
	* Network awareness means good UX in any context
	* Don't assault your users with notifications
	* You need a search interface
	* Create a good user onboarding experience
* [UX Design tips for your app - part 2](http://sixrevisions.com/user-experience-ux/ux-tips-app-part2/)
	* Keep your toch gestures obvious
	* Branding is a part of the UX
	* Customer support is also part of the UX
	* Don't forget landscape mode
	* Multi-Device support improves the UX on all gadgets
* [So. Many. States](https://css-tricks.com/so-many-states/)
* [Musical Interfaces](https://medium.com/@pablostanley/designing-musical-user-interfaces-4f30b41d7a83?ref=webdesignernews.com)
* [When to paginate and when to infinite scroll](http://www.creativebloq.com/ux/paginate-or-infinite-scroll-71515816)
	* infinite scrolling is best suited for websites that boast user-generated content, visual content
	* pagination is a universal option, and best for platforms that intend to satisfy the goal-oriented activities of the visitors
* [Why UX design patterns work and how to use them](http://www.creativebloq.com/web-design/ux-design-patterns-work-91516961)
	* How users interact with design patterns
	* Learned behavior
	* Universal design conventions
		1. Gestalt
		2. Proximity
		3. Colour
		4. Applying empathy to UI design patterns
	* Conclusion
* [Complete beginner's guide to interaction design](http://www.uxbooth.com/articles/complete-beginners-guide-to-interaction-design/)
	* What is interaction design
	* Common methodologies
		* Goal-driven design
			* Design first; program second
			* Separate responsibility for design from responsibility for programming
			* Hold desingers responsible for product quality and user satisfaction
			* Define one specific user for your product
			* Work in teams of two
		* Usability
			* Learnability
			* Flexibility
			* Robustness
			* Efficiency
			* Memorability
			* Errors
			* Satisfaction
			* Understandability
			* Operability
			* Attractiveness
			* Usability compliance
		* The five dimensions
			1. words
			2. visual representations
			3. physical objects of space
			4. time
			5. behavior
		* cognitive psychology
			* mental models
			* interface metaphors
			* affordances
		* human interface guidelines
	* Daily tasks and deliverables
		* Design strategy
		* Wireframes of key interactions
		* Prototypes
		* Stay current
	* Tools of the trade
		* Balsamiq mockups
		* Invision
		* Omnigraffle
		* Patternry
		* Sketch
		* Axure
		* UXPin
* [5 characteristics of interaction design](http://usabilitygeek.com/5-characteristics-of-interaction-design/)
	* What is interaction design
	* Interaction design vs User experience design
	* What makes a good interaction design
		1. Design must be goal driven
			* user personas
			* user scenarios
			* user experience maps (journey maps)
		2. It must be easy to use
		3. The interface must be easily learned
		4. Keep an eye on signifiers & affordances
		5. What's the feedback and response time
	* Conclusion
* [Content display patterns](http://danielmall.com/articles/content-display-patterns/)
	* Identifying and abstracting patterns
	* A real-world example
	* Don't just build the comp
	* Decoupling
* [Putting my patterns through their paces](https://24ways.org/2015/putting-my-patterns-through-their-paces/)
	* Meet the teaser
	* Moving beyond layout
	* Diving into device-agnostic design
* [Design a contact page: 7 pro tips](http://www.creativebloq.com/web-design/design-contact-page-7-pro-tips-121518342)
	1. Ask the right questions
	2. Allow access at all times
	3. Skip the nonessentials
	4. Show your company has a personality
	5. Incorporate team images to instil a sense of trust
	6. Link to additional contact options from the same page
	7. Consider mobile
* [5 common challenges faced by UI designers](http://usabilitygeek.com/5-common-challenges-faced-by-ui-designers/)
	1. The new, 'rad looking' GUI elements
	2. Looking like a link (and not being one)
	3. Mythbusters: navigation 'must-haves'
	4. May the forms be with you
	5. Clash with the clients
* [Why I moved from a square to a circle](https://www.smashingmagazine.com/2016/01/why-i-moved-from-a-square-to-a-circle-calculator-interface-design/)
	* If it ain't broke, why fix it
	* Redesigning the calculator
		* Reinventing the numeric keypad
		* Resectoring the screen real estate logically
		* Substituting gestures for buttons
		* Enabling easy correction of errors at any time
	* The response and the future

###<a name="information_architecture"></a>Information architecture

* [The complete beginners guide to information architecture](http://www.uxbooth.com/articles/complete-beginners-guide-to-information-architecture/)
	* What is information architecture
	* Common methodologies
		* Library science
		* Cognitive psychology
			* Cognitive load
			* Mental models
			* Decision making
		* Architecture
	* Daily tasks
		* User research and analysis
		* Navigation and hierarchy creation
		* Wireframing
		* Labeling
		* Taxonomies and metadata
		* Data modeling
	* People to follow
	* Tools of the trade
	* Conferences and associations
	* IA Books
* 

##<a name="personas"></a>Personas

* [Creating personas](http://www.uxbooth.com/articles/creating-personas/?utm_medium=feed&utm_source=FeedPress&utm_campaign=Feed%3A+uxbooth+%28The+UX+Booth%29)


##<a name="form_design"></a>Form Design

* [The 10 Commandments of Good Form Design on the Web](http://mono.company/journal/design-practice/the-10-commandments-of-good-form-design-on-the-web/)
	1. Thou shalt provide clear, always visible labels for each field
	2. Thou shalt use a big enough font size (+14px)
	3. Thou shalt provide easily tappable areas.
	4. Thou shalt size the in put fields according to their expected input
	5. Thou shalt not customize checkboxes and radio buttons
	6. Thou shalt provide both a general error message and a field specific one
	7. Thou shalt make it clear what is optional and what is not
	8. Thou shalt hide what is not needed until it is needed
	9. Thou shalt minimize user input
	10. Thou shalt be clear what type of input is expected
	11. Thou shalt only validate a field when a user is done with it
* [Why are drop-downs and select boxes bad for forms?](http://www.formisimo.com/blog/why-are-drop-downs-and-select-boxes-bad-for-forms/)
	* Drop-downs cause users to interact multiple times
	* Persistent usability problem
	* Don't assume everyone knows what to do with a drop-down
	* Drop-down menus are not the most appropriate solution
	* Drop-downs are harder to interact with on mobile devices
	* Creates poor accessibility
		* Selecting a list item requires a steady hand --> Make the options large or keyboard accessible
		* Multiple choice options don't make sense out of context --> Associate the label with the list
		* On-focus shouldn't select --> Only select based on user Intent

##<a name="copywriting"></a>Copywriting

* [How to write a great error message](https://medium.com/@thomasfuchs/how-to-write-an-error-message-883718173322)
	* Write an alert message that describes the alert situation clearly and succinctly
	* Write informative text that elaborates on the consequences and suggests a solution or alternative
	* Express everything in the user's vocabulary
	* Don't abuse alerts for upselling or showing superfluous information
	* Don't just assume people know about the context of a message
	* Write actionable error messages that laypeople can understand
* [6 simple tips for designing copy on the web](http://thenextweb.com/dd/2015/05/06/6-simple-tips-for-designing-copy-on-the-web/)
	1. omit needless words
	2. place key words at the beginnng or end
	3. avoid passive voice
	4. phrase positively (if possible)
	5. use similar forms for similar items
	6. be specific
* [Interface writing](http://nicolefenton.com/interface-writing/)
	* Start with questions
		* what is the user trying to do?
		* what might they be feeling
		* how did they get here
		* what happens next
		* what do they need to understand
		* why does this matter to them
	* Be a good tour guide
	tell people what to expect and help them accomplish their goal
	* Turn your chair
	Shift your focus to your readers. Talk *to* them, not *at* them.
	* Show you care
		* Don't assume you're the core audience
		* Avoid jargon and catchphrases
		* Don't assume dichotomies or binaries will do the trick
		* Don't interrupt
		* Don't be a robot
		* Don't waste time
	> The only unit of time that matters is heartbeats. The time you spend is not your own - Paul Ford
	* Write iteratively
* [Why plain language is vital for website usability](http://www.creativebloq.com/web-design/why-plain-language-vital-website-usability-51514999)
	* Ditch the jargon
	* Use active sentences
	* Use headings
	* Harness the power of visual layout
* [Choosing between min and max-width](http://www.the-haystack.com/2015/12/23/choosing-between-min-and-max-width/)
	* Desktop first and max-width
	* Using max-width against your better judgment
	* So, what's the best to use?

##<a name="process"></a>Process

* [Why designers should never skip prototyping](http://www.creativebloq.com/web-design/why-web-designers-should-never-skip-prototyping-91516933)
	* Got a design pattern? Plan it out
	* Think through the process
	* Design patterns remove guesswork
	* User testing: insights you can't ignore
	* Prepare yourself to test prototypes
	* Next steps
* [Reimagine the web design process](http://sixrevisions.com/web_design/reimagine-web-design-process/)
	* Mobile first
	* One brick at a time
	* Think beyond breakpoints
	* Get real
	* A whole new world
* [From pages to patterns: an exercise for everyone](http://alistapart.com/article/from-pages-to-patterns-an-exercise-for-everyone)
	* Thinking in pages (still)
	* From pages to patterns
		1. paper and scissors
		2. naming components
		3. code
	* Repeat, repeat, repeat
	* What happens next
	* Developing components
	* 

##<a name="style_guides"></a>Style guides

* [Living style guide tools](https://medium.com/@operatino/living-style-guide-tools-in-depth-overview-28cfffb92d05)
	* [KSS](http://warpspire.com/kss/): documentation for CSS (via comments)
	* [SC5 - Style guide generator](https://www.npmjs.com/package/sc5-styleguide) works with KSS
* [How to create a web style guide you'll be proud of](http://www.sitepoint.com/creating-web-style-guide/)
	* So, what do you do?
	* What is a style guide
	* Researching your brand
	* Configuring the color palette
	* Defining buttons and icons
	* Font selection
	* Imagery and video specifics
	* Give a voice to the copy
	* Extras
	* The final word
* [Beyond the style guide](https://24ways.org/2015/beyond-the-style-guide/)
	* The auteur's style guide
	* Painting by numbers
	* Anatomy of a button
		* Content
		* Structure
		* Presentation
		* Behaviour
		* Transcending layers
	* Visual design language: documenting the missing piece
	* A visual language in code form
	* Unlocking possibility
* [VIDEO: Brad Frost - Style guide best practices](http://bradfrost.com/blog/post/style-guide-best-practices-at-beyond-tellerrand/)

##<a name="visual_design"></a>Visual design

* [Can you fix a bad design?](http://designshack.net/articles/typography/can-you-fix-a-bad-design-heres-where-to-start/)
	1. Clean up the typography
	2. Add white space
	3. Ditch poor images
	4. Put it on a grid 
	5. Streamline the color palette
	6. Eliminate the tricks
	7. Be honest
* [7 Ways to create attractive user interfaces](http://www.creativebloq.com/web-design/create-attractive-user-interfaces-91516600)
	1. Follow Hick's law (don't clutter interfaces)
	2. Use the right signifiers
		1. explicit
		2. pattern
		3. hidden
		4. metaphorical
		5. negative
	3. Know which colours evoke which moods
	4. Understand and apply the different types of symmetry
	5. Use photos of real people
	6. Maintain consistency
	7. Take advantage of white space
* [How to fill empty space in your designs](http://www.creativebloq.com/web-design/closer-look-empty-states-91517042)
	* First-time use (onboarding)
	* User cleared data
	* No results
* [Signal vs noise: Color as a wayfinding tool](https://viget.com/inspire/wayfinding#When:17:05)
	* Wayfinding guideposts
		* identification
		* action
		* signification
		* notification
	* In summary	
* [Designing with contrast](https://24ways.org/2015/designing-with-contrast/)
	* A thin veneer
	* Minimalist expectations
	* Imitation without representation
	* For want of good design, the message was lost
	* Standards of excellence
		* Put guidelines in place
		* Test your work
		* Push your limits
	* More than just a facade
* [8 optical illusions to improve your mockups](http://www.creativebloq.com/web-design/8-optical-illlusions-improve-your-mockups-111517939)
	* The science of shape
	* Emergence
	* Reificcation
	* Multistability
	* Similarity
	* The figure-ground relationship
	* Grouping
	* Closure
	* Continuation
	* Takeaway

###<a name="typography"></a>Typography

* [10 commandments of web typography](http://www.creativebloq.com/typography/10-commandments-web-typography-91516546)
	1. Read the text. Take notes
	2. Get a sense of the tone and feeling
	3. Look for reoccurring words and numbers
	4. Note sections and subsections in the text. How many levels of headings will you need?
	5. Note other text-based elements you have to set. Are they captions, pullquotes, numerical data, a featured paragraph? Titles in the text you'll need to italicize?
	6. Start considering appropriate fonts - at the size you plan to use them. They'll look different as text and headline.
	7. Discord fonts that don't support the tone of the text, have problems with reoccurring words and numbers, that can't accomplish what you need it to do.
	8. Test the remaining fonts cross browser. Don't build your site only to learn the doesn't work cross browser
	9. Attend to "the hole trinity" of good text: size, line-height, line-length
	10. Use your line length to set the grid if possible. If your site is responsive, consider line length when setting breakpoints.
* [How to make your type look good on any screen](http://www.creativebloq.com/typography/make-type-look-good-any-device-81515938)
	* Scale
	* Size, length and height
	* Font size (recommendation to set base font-size at 100% --> mostly 16px)
	* Ems and rems
	* Line height 
		* affects readability 
		* on average best is 1.4 (small screens slightly less, large screens slightly more)
		* vertical margins should be in proportion
	* Line length (on average 45-75 characters)
	* Adjusting margins

#<a name="research"></a>Research

![So, you want to leverage the web to conduct your user and UX research](http://boxesandarrows.com/wp-content/uploads/2015/05/02_stuff.jpg)

* [How to moderate effectively in usability research](http://www.smashingmagazine.com/2015/07/moderating-effectively-in-usability-research/)
* [12 Design research methods to get inspired by users](https://medium.com/design-research-methods/12-design-research-methods-to-get-inspired-by-users-cae4789a094b)
	1. User interview (1-2 hour interview with a current or future user, ideally at home or in the context of the thing you're designing)
	2. Expert interview (interviewee should have deep experience or knowledge in the relevant area)
	3. Extreme interview ((interviewee should exhibit sharpened traits of your core users)
	4. Group session
	5. Expert panel (expert group session)
	6. Analogous experience
	7. Empathy experience
	8. Desk research
	9. Data mining
	10. Behaviour tracking
	11. Surveys
	12. Guerilla research
* [10 ways to get more from your UX workshop](https://boagworld.com/usability/10-ways-to-get-more-from-your-ux-workshop/)
>Do not allow your UX workshop to devolve into discussing features. Keep it focused on user needs

	1. Focus on users
	2. Define your digital goals
	3. Make it fun
	4. Don't start designing web pages (start with a book jacket --> most important messages will go on the front)
	5. Vary your exercises
	6. Use voting to keep momentum
	7. Set time constraints
	8. Make it interactive, not just discussion based
	9. Spend time looking at barriers
	10. Refine and report back
* [Never ask what they want - 3 better questions to ask in user interviews](https://medium.com/user-research/never-ask-what-they-want-3-better-questions-to-ask-in-user-interviews-aeddd2a2101e#.3u7xlt3d3)
	* What are you trying to get done? Why?
	* Can you show me how you currently do this?
	* Can you show me what's frustrating about your current process?
* [Correlation and organization: user research methods and derived value](http://usabilitygeek.com/correlation-organization-user-research-methods-derived-value/)
	* The focus group
	* The focus of the focus group
	* Correlation and organization: user research methods and derived value
	* What are the other guys doing
* [Remote user research & usability methods](http://uxmag.com/articles/remote-user-research-usability-methods)
	* When remote study works
		* Flexibility
		* Environment
	* When remote study doesn't work
		* Information security
		* Inability to use screen sharing
		* Face and body movements
	* Moderated vs automated research
	* Recruiting for web or mobile study
		* Live recruiting
		* Other channels for recruiting
		* Incentive
	* Tools for remote UX studies
		* Moderated - Screen sharing & recording
		* Automated - Usability study and task elicitation
		* Moderated or automated mobile studies
		* Observers
		* Making notes
		* Combine everyone's insights
		* Remote collaboration
	* Summary

#<a name="html"></a>HTML

* [Form inputs](http://www.smashingmagazine.com/2015/05/05/form-inputs-browser-support-issue/): The browser support issue you didn't know you had
* [25 hottest web design techniques](http://www.creativebloq.com/netmag/25-hottest-web-design-techniques-81516153)
	1. Ask questions
	2. Listen to your code
	3. Protect the web's inherent accessibility
	4. Take advantage of conditional loading
	5. Use [Ceaser](http://matthewlein.com/ceaser/) to write cubic-bezier
	6. Use height-based media queries (improve experiences when the available height is limited)
	7. Keep the big picture in mind
	8. Use namespaceing for your CSS files
	9. Employ easy image fallbacks
	10. Master debugging in JavaScript
	11. Make your background images responsive (background-size: cover)
	12. Use mixins to create complex grid systems
	13. Think about conversations, not pages
	14. Provide keyboard support
	15. Design quickly in the browser
	16. Simplify your code
	17. Convert fixed widths to percentages
	18. Embrace the title field
	19. Configure Git
	20. Use Git commit hooks
	21. Learn from issues and errors
	22. Feel how fast your site is
	23. Avoid long select boxes
	24. Scale icons with background-image:cover
	25. Keep it short and sweet

#<a name="css"></a>CSS

* [Cyclomatic complexity](http://csswizardry.com/2015/04/cyclomatic-complexity-logic-in-css/): logic in CSS
	* Think of your selectors as mini programs
	* Keep your cyclomatic complexity to a minimum
	* If you don't need the checks, don't put them in there
	* Start thinking about your selectors from the right first
	* Brush up on selector intent
* [Quantity queries for CSS](http://alistapart.com/article/quantity-queries-for-css)
	* Dynamic content
	* Counting
		* Counting to one (:only-child | :only-of-type)
		* Quantity N
			* :nth-last-child(n)
			* :nth-last-child(6):first-child --> the first of 6 elements in the set (where the set can only contain 6 elements)
			* li:nth-last-child(6):first-child ~ li --> all 6 elements in the set (where the set can only contain 6 elements)
			* li:nth-last-child(n+6) --> starting with the 6th element
			* li:nth-last-child(n+6) ~ li --> all elements in a set of 6 or more elements
	*  IE9+
	*  Content-independent design
*  [Selectors Level 4](http://www.sitepoint.com/future-generation-css-selectors-level-4/)
	*  :read-only && :read-write
	*  :default
	*  :valid && :invalid
	*  :in-range && :out-of-range
	*  :required && :optional
	*  [href$="pdf" i] --> case-insensitive attribute selector
	*  :blank && :empty
	*  :matches()
	*  :has()
	*  :any-link
	*  :focus-within
	*  :drop && :drop() --> active, valid, invalid
*  [Force up and down arrow for number input](https://web-design-weekly.com/snippets/force-up-and-down-arrow-for-number-input/)
   
> input[type=number]::-webkit-inner-spin-button,
>
> input[type=number]::-webkit-outer-spin-button {
>
> opacity: 1;
>
> }

* [Remove or disable textarea resize image](https://web-design-weekly.com/snippets/remove-disable-textarea-resize-image/)

> textarea{
>
> resize: none;
>
>}  

* [12 little known CSS facts](http://www.sitepoint.com/12-little-known-css-facts/)
	1. The _color_ property isn't just for text
	2. The _visibility_ property can be set to "collapse"
	3. The _background_ shorthand property has new values
	4. The _clip_ property works only on absolutely positioned elements
	5. Vertical percentages are relative to container width, not height
	6. The _border_ property is kind of like inception
	7. The _text-decoration_ property is now a shorthand
	8. The _border-width_ propery accepts keyword values
	9. Nobody uses _border-image_
	10. There's an _empty-cells_ property
	11. The _font-style_ property accepts a value of "oblique"
	12. _word-wrap_ is the same as _overflow-wrap_
* [12 little known CSS facts - the sequel](http://www.sitepoint.com/12-little-known-css-facts-the-sequel/)
	1. The _border-radius_ property can use "slash" syntax
	2. The _font-weight_ property accepts relative keywords
	3. There is an _outline-offset_ property
	4. There is a _table-layout_ property
	5. The _vertical-align_ property works differently on table cells vs other elements
	6. The _::first-letter_ pseudo element is smarter than you think
	7. You can use invalid characters as delimiters in your HTML class lists
	8. Animation iterations can be fractional values
	9. Animation shorthand can break because of the animation's name
	10. You can select ranges of elements
	11. Pseudo-elements can be applied to some void elements
	12. Some attribute values are case insensitive in selectors
* [Working with shapes in web design](https://css-tricks.com/working-with-shapes-in-web-design/)
* [Comprehensive guide: when to use em vs rem](http://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984)
	* Use em for: (sizing that should scale depending on the font-size of an element other than the root)
		* margin, padding, width, height, line-height
	* Don't use em for font-size - rem is more suited for this
	* Use rem units for: (sizing that should scale depending on browser font-size settings)
		* most heights
		* most widths
		* most padding
		* most margin
		* border width
		* font-size
		* shadow
		* media queries (ALWAYS)
	* Don't use rem for multi-column layout widths (use %)
	* Single columns should still generally incorporate rem via max-width
* [Modern CSS Layout, power and responsibility](https://www.rachelandrew.co.uk/archives/2015/07/28/modern-css-layout-power-and-responsibility/)
* [A look at length units in CSS](http://www.sitepoint.com/look-at-length-units-in-css/)
* [Position sticky: scroll-to-top-then-fixed in pure CSS](http://thenewcode.com/1052/position-sticky-scroll-to-top-then-fixed-in-pure-CSS)
* [Dealing with long words in CSS](https://justmarkup.com/log/2015/07/31/dealing-with-long-words-in-css/?mc_cid=ce70bb0280&mc_eid=b38f2f4652)
	* Hyphens (hyphens: auto + vendor prefixes)
		* supported in every major browser (except Blink)
		* language-sensitive --> non english languages are not supported very well
	* Word-break (word-break: break-all or break-word)
		* supported in every browser (except Opera)
	* Overflow-wrap (word-wrap: break-word; overflow-wrap: break-word;)
		* supported in every browser
	* Ellipsis (text-overflow: ellipsis; white-space: nowrap; overflow: hidden;)
		* supported in every major browser
		* truncation is not a job for CSS
* [Less CSS mess](http://thomasbyttebier.be/blog/less-css-mess)
	* Coding guidelines
	* [ITCSS](itcss.io)
	* Namespaced CSS
	* BEM
		* .block
		* .block\_\_element
		* .block--modifier
* [Back to the :roots](http://simurai.com/blog/2015/09/09/back-to-the-roots/)
	1. For every CSS property that you write, try to move it up the tree as far as possible. In other words: Back to the :root.
	2. Style certain properties always as a __combo__
	3. Use "dynamic" values, such as _currentColor_ and _em_s
	4. Override UA styles to _inherit_ from its parents
* [The @font-face dilemma](https://viget.com/extend/the-font-face-dilemma)
	* How we got here
		* @font-face browser defaults
	* Improving font loading performance
		* font loaders
			* typekit/google web font loader, 11kB minified
			* font face observer, 4kB minified
			* LocalFont
		* Embracing FOUT (Flash Of Unstyled Text)
	* Font loading in the future
		* Font loading API
		* CSS Font rendering Draft
	* Wrap up
* [Things to avoid when writing CSS](https://medium.com/@Heydon/things-to-avoid-when-writing-css-1a222c43c28f#.2y32thsoz)
	* Multiple files (you shouldn't organise CSS by splitting it into separate files any more than you should organise a pane of glass by dropping it on a concrete floor)
	* Nesting (with sass) (nesting is not the sass feature you are looking for)
	* Pixel units (embrace relativity and reap the rewards)
	* Device breakpoints (Apple aren't the only people who make handheld devices with browsers on them. No really.)
	* Photography (a picture paints a thousand words. most of those words are just incoherent mumbles and repetitions of the statement "I don't give a shit about your data allowance". SVG for charts, diagrams and icons; typography and CSS for everything else
	* Giving anything a set height ever (nobody fucking cares if those buttons line up exactly or not. Vain, pointless frippery that doesn't make anything any more useful or appealing or your product more successful)
	* Calling it "semantic" (there's more to something having meaning than just sticking a label on it. This applies to the web, language systems and culture in general)
	* Making it just about the code (We should invest in the maintainability of our code, unless it's not worth maintaining)
* [Understanding and using rem units](http://www.sitepoint.com/understanding-and-using-rem-units-in-css/)
	* What are rem units?
	* rem units vs em units
	* font sizing with rem units
	* using rems with media query breakpoints
	* using rem units for scaling documents
	* conclusion
* [Stylish and sane: a guide to better CSS](http://www.infoq.com/articles/guide-to-better-css)
	* Why is this so hard
		* Whoa that's a lot of CSS
		* Writing CSS when you shouldn't have to
		* No re-use
		* Everything is special
		* Side effects
	* It doesn't have to be this way
		* Treat your CSS like code
		* Think about your styles like a consumer
		* Component-based styling
	* Introducig the style guide
	* Creating your own style guide
	* Keeping your CSS DRY
		* The first rule of CSS is don't write any CSS
		* Style each component once
		* Consistent markup (writing more consistent HTML means less CSS)
		* Scope specific styles (only applies to that scenario and nowhere else)
		* Be critical of every line (the less code you leave behind, the less code there is to confuse you the next time around)
		* Talk about keeping things simple
		* Mobile first
	* Less CSS, less hassle
* [Manage large CSS projects with ITCSS](http://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528)
	* Introducing ITCSS - Inverted Triangle CSS
	* Prerequisites
		* No ID selectors
		* Componentised UI architecture
		* Class-based architecture (less markup != clean markup)
	* Key metrics
		* Generic to explicit
		* Low specificity to high specificity
		* Far-reaching to localised
	* Layers
		* Settings (global)
		* Tools (mixins and functions)
		* Generic
		* Elements
		* Objects
		* Components
		* Trumps
	* Partials
	* The result
* [Do we actually need specificity in CSS](http://philipwalton.com/articles/do-we-actually-need-specificity-in-css/)
	* A little background
	* But specificity is good, right?
	* What if specificity didn't exist?
	* Removing specifity from the cascade
		* Handling ID specificity
		* Handling selectors that may already refer to the root element
		* The full rewriting algorithm
		* Potential downsides
	* Final thoughts
* [Building and shipping functional CSS](https://blog.colepeters.com/building-and-shipping-functional-css/)
	* Atomic? Functional? WTF?
		* Performance is critical
		* Clarity trumps cleverness
		* Classes should be as reusable as possible
		* Classes should be composable and free of side-effects
	* Bringing Functional CSS to TrialReach
	* The approach
		* Settings
		* Elements
		* Objects
		* Components
		* Utilities
		* Visuals
	* A few examples in practice
	* The outcome
	* Gripes and gains -- getting comfortable with functional CSS
		* Component-driven design vs. component-driven CSS
		* Make documentation and code reviews a priority
		* Wrap frequently-used markup in partials or custom components
		* Repetitions: some are good, others less so
		* Functional classes in responsive design
	* I never promised you a rose-coloured panacea
* [Blending modes in CSS: Color theory and practical application](http://webdesign.tutsplus.com/tutorials/blending-modes-in-css-color-theory-and-practical-application--cms-25201)
	* The basics of blending
		* What does "blending mode" actually mean?
		* You do the math
	* Types of blending modes available in CSS
	* [interactive example](http://codepen.io/tutsplus/live/wMvoyj)
	* Separable blend modes
		* Screen (the concept of projecting multiple photo exposures at the same time on one screen
		* Darken (selects the darker of the two colors)
		* Lighten (selects the lighter of the two colors)
		* Color dodge (lightens the background color to reflect the source color)
		* Color burn (darkens the background color, increasing the contrast between the source and the background)
		* Hard light (applies "multiply" on lighter colors and "screen" on darker colors)
		* Overlay (applies "screen" on lighter colors and "multiply" on darker colors)
		* Soft light (applies a variant of multiply on dark values and a variant of screen on lighter values)
		* Difference (takes the absolute difference value between the two colors)
		* Exclusion (same basic effect as the "difference" mode, except that similar colors result in a lower contrast middle value)
	* Non-separable blending modes
		* Hue (applies the hue of the source layer to the luminance and saturation of the background color)
		* Saturation (applies the saturation of the foreground to the hue and the luminance of the background)
		* Color (applies the hue and saturation of the foreground to the luminance of the background)
		* Luminosity (applies luminosity of the source layer with the hue and saturation of the background layer)
	* Conclusion
* [Blending modes demystified](http://alistapart.com/article/blending-modes-demystified)
	* Blending modes explained
	* Transparency effect with multiply
		* x = a * b
		* multiplies luminance for each of the RGB channels
		* filters out white background of logo on top of other image
	* Dust and scratches with screen
		* x = 1 - (1 - a) * (1 - b)
		* functional opposite of multiply
		* multiplying the inverse of a times the inverse of b and then inverting it once more
		* white pixels are completely opaque, black pixels are transparent
	* Colorizing with _hue_ and _color_
		* Hue
			* takes the hue component of the overlapping layer and applies it to the colors below, leaving saturation and luminostiy unmodified
		* Color
			* affects both hue and saturation of the source, ignoring luminosity
			* achieve the same effect by reversing order of your layers, blending with _luminosity_
		* Cross-browser blending
			* Not just browsers are inconsistent
			* People are inconsistent (color blindness)
			* Test on real devices (performance issues - scrolling might lag - 60 fps might be affected)
		* Applying blending modes
			* Blending background images
			* Blending HTML elements
				* _mix_blend_mode_ blends between stacked HTML elements
				* applied to an entire element along with all of its children
		* Browser support
* [An introduction to CSS's @supports rule (feature queries)](http://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/)
	* Detecting browser features with the @supports rule
	* Testing for multiple conditions at once
	* The operators in action
	* JavaScript with CSS Feature queries
	* Browser support
	* Conclusion
* [A specificity battle! (and other trickery) - 19 ways to override a background](https://css-tricks.com/a-specificity-battle/)
	1. starting with _div{background:black;}_
	2. Step 1: element selector _(0,0,0,1)_
	3. Step 2: two element selectors _(0,0,0,2)_
	4. Step 3: three element selectors _(0,0,0,3)_
	5. Step 4: class selector _(0,0,1,0)_
	6. Step 5: class + element selector _(0,0,1,1)_
	7. Step 6: element + class + pseudo-class selector _(0,0,2,1)_
	8. Step 7: stacked classes _(0,0,&infin;,0)_
	9. Step 8: id selector _(0,1,0,0)_
	10. Step 9: id + attribute selector _(0,1,1,0)_
	11. Step 10: combining many above... _(0,1,3,3)_
	12. Step 11: inline style _(1,0,0,0)_
	13. Step 12: !important _(kind of like 1,0,0,0 on a per-property basis)_
	14. Step 13: !important on inline style _(kind of like &infin; on a per property basis)_
	15. Step 14: box-shadow trickery _(box-shadow paints on top of background)_
	16. Step 15: invert filter
	17. Step 16: pseudo element overlay
	18. Step 17: !important again
	19. Step 18: @keyframes trickery _(!important isn't animateable, so animation can override it)_
	20. Step 19: coloring the content _(putting a huge block character over everything flips the color again)_
* [CSS specificity is base infinite](https://css-tricks.com/css-specificity-is-base-infinite/)
* [20 essential CSS recipes](http://ipestov.com/22-essential-css-recipes/)
	1. Blend modes
	2. Gradient borders
	3. Transition for z-index
	4. currentColor
	5. Object fit
	6. Checkbox and radio buttons styles
	7. Counters in CSS
	8. Advanced CSS counters
	9. Menu Icon without Images
		1. Shadows
		2. Gradient
		3. UTF-8
	10. @supports
	11. visibility: visible
	12. position:sticky --> [caniuse](http://caniuse.com/#search=sticky)
	13. New dimensions
	14. Text decorations
	15. Block scroll on touch devices
	16. Using hardware acceleration
	17. Unicode classes
	18. Vertical margins in percents
	19. Margins in firefox buttons
	20. Color + border = border-color;

##<a name="flexbox"></a>Flexbox

* [Flexbox cheatsheet](http://jonibologna.com/flexbox-cheatsheet/)
* [A complete guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [A visual guide to CSS3 flexbox properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
* [Ridiculously Easy Layouts with Flexbox](https://www.youtube.com/watch?v=2hak2xElAKI)
	* Multi-axis
		* main & cross
		* start, end and size
		* direction depends on flex-direction
	* Benefits	
		* W3C standard (almost)
		* No more float and clear
		* Vertical positioning
		* override source order
		* equal heights
		* perfect fit for RWD
		* more semantic (in contrast to e.g. Bootstrap)
* [Flexbox in the real world](http://www.planningforaliens.com/blog/2014/03/11/real-world-flexbox/)
* [Useful flexbox technique: Alignment shifting wrapping](https://css-tricks.com/useful-flexbox-technique-alignment-shifting-wrapping/)
	*  title split into two sections, first portion is left aligned, second is right aligned
	*  when there isn't room based on screen size or length issues, left-align wrapping is what we want
	*  [Live demo](http://codepen.io/chriscoyier/pen/doVXLV)
*  [Flexbox adventures](http://chriswrightdesign.com/experiments/flexbox-adventures/)
	*  Flexbox basics
		*  Flex-basis and Flex-grow
		*  Applying grow
		*  Calculating the space
			*  available space = (container size - sum of flex-basis of siblings)
			*  grow unit = (available space / sum grow siblings total)
			*  flex item size = (flex basis + (grow unit * num))
		*  A rounding bug
		*  Flex shrink
			*  total items = multiply each basis by its shrink value and add together
			*  shrink factor / item = divide each item by the total items
			*  mulptiply shrink factor with negative space (overflow)
		*  Relative distributions (set basis to 0)
		*  Source ordering
		*  Reverse it
		*  Vertical center & equal height columns
			*  Vertical center div
			*  Equal height columns
		*  Flexbox transitions
		*  Flexbox feature support
		*  Enhancing to flexbox
		*  Wrapping up
*  [Using flexbox today](http://chriswrightdesign.com/experiments/using-flexbox-today/)
	*  Road to flexbox
		*  Making layouts better
		*  Card layouts
		*  Split screen layouts
		*  Pinned layouts
		*  Newspaper and ad units
		*  Multi-column layouts
		*  Dashboards
		*  Embracing change
		*  Content is flexible
		*  We don't always have control
		*  More design tools
		*  Bend and break
	*  Strategy for Flexbox
		*  Build the way we always did
		*  Minimize code
		*  Make it worthwhile
		*  Cut the mustard: flex-wrap
		*  Enhancing with flexbox
	*  Troubleshooting Flexbox
		*  Axis direction (flex direction)
		*  Flex items horizontal off the page
		*  Inflexible imagery
			*  Workaround
		*  Understanding space-around and space-between
		*  How grow and shrink work
		*  Items become many tiny columns
		*  IE 10/11 only: wrapping too early, items too big
		*  IE 10/11 only: the heights are oddly collapsed
		*  FF: column-reverse and overflow-y
		*  Internet explorer ignores min-height
		*  Well documented cross-browser bugs
		*  Add flexbox to your layouts
* [Flexbox Froggy: A game to understand flexbox](http://flexboxfroggy.com/)
* [Flexbox for interfaces: tracks case study](http://www.smashingmagazine.com/2015/11/flexbox-interfaces-tracks-case-study/)
	* Flexy atomic components
	* Inline patterns
	* Inline form inputs
	* Dropdown menu
	* Media objects
	* Flexy calendar
	* Layout
	* Sticky footers
	* Be careful
	* Conclusion
* [VIDEO: the axis of flexbox](http://www.sitepoint.com/watch-the-axis-of-flexbox/)
* [Designing a product page layout with flexbox](https://css-tricks.com/designing-a-product-page-layout-with-flexbox/)
	* This is based on the "Venture" theme
	* The header layout
	* The products layout
	* Bottom-aligning the product footers
	* Responsive flexboxing
	* Compatibility
	* Conclusion
* ['Flex-grow' is weird. Or is it?](https://css-tricks.com/flex-grow-is-weird/)
	* How flex-grow _doesn't_ work
	* How flex-grow really works
		* First we have to calculate the remaining space
		* Next we have to determine how much one-flex-grow is
		* The sliced up remaining space gets distributed between all elements
	* Allright, but why does the first demo work?
	* Flex-grow and flex-basis
	* Working with the box model
	* Some useful examples
		* No more width: [x]%
		* The "Holy Grail" 3 column liquid layout with pixel-widths
		* Filling remaining space with any element
	* Listening to the specs

##<a name="grid"></a>Grid

* [VIDEO: Start using CSS Grid Layout - Rachel Andrew](https://www.youtube.com/watch?v=Felq4z_rdPQ)
* [Deep dive into grid layout placement](http://blogs.igalia.com/mrego/2016/02/01/deep-dive-into-grid-layout-placement/)
	* Grid lines (numbered startign at 1)
	* Grid placement properties
	* Cell spanning
	* Negative line numbers
	* Named grid lines
	* Grid areas
	* Grid areas & named grid lines
	* Implicit grid
	* Implicit grid & named grid lines
	* Special cases
	* Recap
	* Status

#<a name="sass"></a>SASS

* [Ins and outs of Sass](https://www.youtube.com/watch?v=_4WSOy2gBls)
	* File organization
		* Base (configuration/settings for the project)
		* Components (largest directory / aka modules)
		* Layout (systems level layouts)
		* Patterns (reusable patterns)
		* Plugins 3rd party files
	* _Partials.css (does not create extra HTTP requests)
	* @mixin (way to share reusable pieces of code)
		* does not compile yet
		* needs to be included (@include)
		* accept arguments ($variable) --> should include default values or all includes should provide the variable
		* passing named arguments (useful with more than 1 optional argument)
		* order matters for arguments --> required arguments before optional ones
	* %extends
		* don't take arguments
		* chains selectors instead of duplicating
	* Nesting
		* should not go further than 3 to 4 levels
		* Ideally used for pseudo-selectors
	* Functions
		* @function
	* Lists and maps
* [Extending in Sass without creating a mess](http://www.smashingmagazine.com/2015/05/04/extending-in-sass-without-mess/)
	* __the target "simple selector" is identified__
	* __contraints are formed on the target selector using:__
		* __the selector that's doing the extending__
		* __and the selector that's being extended__
	* Use and extend %placeholder selectors
	* extend a selector as few times as possible
	* extend traits selectively, and consider mixins for short traits
	* use @extend for relationships
	* define relationships via placeholders, not classes
	* represent one selector per placeholder in relationships
	* be wary of descendant and general sibling combinators
	* have separate placeholders for modifiers
	* use @extend inside similar media queries
	* use @extend with :matches() in the future
* [Responsive typography with sass maps](http://www.smashingmagazine.com/2015/06/17/responsive-typography-with-sass-maps/)
	* font-size switching based on breakpoints
		* function to retrieve value from map
		* font-sizes map (breakpoint, font-size)
	* font-size switching based on breakpoints continued
		* function to retrieve font-size based on breakpoint
		* breakpoints map (name, value) + font-sizes map (breakpoint name, font-size)
	* font-size + line-height switching based on breakpoints
		* function to retrieve font-size and/or line-height based on breakpoint
		* breakpoints map (name, value) + font-sizes map (breakpoint name, list combining font-size with line-height)
* [Sass optimization - 5 tips for faster work](http://blog.alexdevero.com/sass-optimization-5-tips-for-faster-work/)
	1. Sass @import directive
	2. Use variables
	3. Use mixins
	4. Nesting the rational way
	5. Use Sass color functions
* [Using Sass's @error, @warn, and @debug Directives](http://www.sitepoint.com/using-sass-error-warn-and-debug-directives/)
	* Stop Everything - The @error directive
	* Don't miss this - The @warn directive
	* If you were curious - The @debug directive
* [How to nest selectors and properties in sass](http://vanseodesign.com/css/how-to-nest-selectors-and-properties-in-sass/)
	* Nesting selectors
	* Referencing parent selectors (&)
	* Trailing parent reference
	* Nesting properties
	* Closing thoughts
* [The pros and cons of nesting your sass code](http://vanseodesign.com/css/the-pros-and-cons-of-nesting-your-sass-code/)
	* The cons of nested sass
		* specificity
		* inception-like
	* The pros of nestingM
		* more readable code
		* more maintainable code
	* Closing thoughts
* [How to use sass variables](http://vanseodesign.com/css/how-to-use-sass-variables/)
	* A simple example using variables
	* Allowed characters in variable names
	* Variable scope (!global)
	* Default values in variables (!default)
	* Variable interpolation (#{variable})
	* Closing thoughts
* [Classy CSS: a programmatic approach to sass stylesheets](http://una.im/classy-css/)
	* Classy CSS, please
	* A classy button
	* Well, what about mixins?
	* In defense of @extend
	* Benefits
* [Mixing color for the web with Sass](http://alistapart.com/article/mixing-color-for-the-web-with-sass)
	* A hex on hex codes
	* Packing up the color picker for Sass
	* Proportional palettes with color scaling
	* Mastering color with mixing
	* Additional considerations for developing your palette
* [The Sass ampersand](https://css-tricks.com/the-sass-ampersand/)
	* Basic nesting
	* Adding another class
	* The "aha" moment!
	* Using the & with pseudo classes
	* Using the & with >, .+, and ~
	* Qualifying based on context
	* Tweaking the definition of the &
		* Wacky but working example #1
		* Wacky but working example #2
	* What the & isn't
	* @at-root to the rescue
	* Doubling up specificity
	* Modifying the ampersand
	* Conclusion
* [Variables: The backbone of CSS architecture](https://www.smashingmagazine.com/2016/01/variables-in-css-architecture/)
	* What is the preprocess poster child?
	* Why should variables be the core reference for a sass project
	* Storing CSS variables
	* When should I create a variable
	* Reduce mixins and extends to the bare essentials
		* Write vanilla css when abstraction causes confusion
		* Use mixins or extends for well-established conventions
		* For global styles, can you swap a mixin with a variable if it doesn't need arguments
		* Don't lock yourself in by using mixins for vendor prefixes
		* Use local variables only when necessary
		* Break your own rules; it's often helpful to have a few handy mixins or placeholders
	* Variables: Pixie-dusting our partials with care
		* Think before making a new variable
		* Think before reusing a variable; would native CSS values suffice?
		* Don't reuse variables inappropriately
	* Variables: Nomenclature
		* Most descriptive, but most restricted
		* Descriptive, but less restrictive
		* Less descriptive, with more weightage
		* Less descriptive, but offers some weightage
	* Common variables for a web application
		* Variables for dimensions
		* Variables for spacing: paddag and margins
		* Variables for colors
		* Variables for z-index
		* Variables for border-radius
		* Variables for typography
		* Variables for font icons
		* Variables for media queries
		* Native variables with pure CSS --> [CanIUse](http://caniuse.com/#search=css%20variables)
	* Resources
* [Sass: @-rules and directives](http://vanseodesign.com/css/sass-at-rules-and-directives/)
	* CSS @-rules
	* The @at-root directive
	* (without: directive-name) and (with: directive-name)
	* The @debug, @warn, and @error directives
	* Closing thoughts

#<a name="responsive_web_design"></a>Responsive Web Design

* [Responsive Logos, Part 1](http://viget.com/inspire/responsive-logos-part-1-tips-for-adapting-logos-for-small-screens): Tips for adapting logos for small screens 
* [Responsive Logos, Part 2](http://viget.com/inspire/responsive-logos-part-2-making-logos-truly-responsive-with-svg): Making logos truly responsive with inline SVG
![Responsive Strategy Illustration](https://pbs.twimg.com/media/CGewrArXEAALg5N.jpg:large)
* [Responsive typography with sass maps](http://www.smashingmagazine.com/2015/06/17/responsive-typography-with-sass-maps/)
	* font-size switching based on breakpoints
		* function to retrieve value from map
		* font-sizes map (breakpoint, font-size)
	* font-size switching based on breakpoints continued
		* function to retrieve font-size based on breakpoint
		* breakpoints map (name, value) + font-sizes map (breakpoint name, font-size)
	* font-size + line-height switching based on breakpoints
		* function to retrieve font-size and/or line-height based on breakpoint
		* breakpoints map (name, value) + font-sizes map (breakpoint name, list combining font-size with line-height)
* [Viewport sized typography](https://css-tricks.com/viewport-sized-typography/)
* [When responsive images get ugly](http://codepen.io/Tigt/blog/when-responsive-images-get-ugly)
	* Some ground floor stuff
		* Why bother.
		* Srcset is preferable
	* Unintuitive behavior & gotchas
		* Media conditions, NOT media queries
		* Troublesome CSS units
			* % only works if you know how big an element's parent are otherwise CSS is required to calculate it
			* rem and em are resolved based on users default font-size
		* sizes _will_ affect how your image displays
	* Media-aware images
		* Printer-friendly
		* E-ink-friendly
		* Night mode & bright sunlight
	* The deepest backwards-compatibility possible
	* Height _and_ width-constrained _srcset_
		* object-fit:cover
		* object-fit:contain
	* Responsive bitmaps inside inline SVG
		* Fixing IE
		* Building the sizes
		* Making things worst with not quite-entire-viewport scaling
			* The browser viewport
			* The <svg> element
			* The viewbox
			* The image
			* Assembling
	* That's all, folks
* [Container Queries: once more unto the breach](http://alistapart.com/article/container-queries-once-more-unto-the-breach)
Why we should rename element queries into container queries
* [13 tips for making responsive web design multi-lingual](http://responsivenews.co.uk/post/123104512468/13-tips-for-making-responsive-web-design)
	1. don't confuse languages, scripts and countries with one another
	2. make each version easily configurable
	3. use a templating language to customize HTML for each service
	4. create translation files for words that will be hard coded into your UI
	5. ensure your web font is compatible with all the languages you support
	6. make your layout language neutral
	7. use sass to create bi-directional layouts
	8. add additional break points for language specific issues
	9. make components adaptable for certain language issues
	10. localize social media buttons
	11. don't worry too much about iconography
	12. localize dates
	13. localizing content for specific services
* [A pros guide to responsive web design](http://www.creativebloq.com/rwd/pros-guide-responsive-web-design-71515692)
	* Responsive images
		* Basic
			* Think about whether you really need to include an image. Is it core content or decorative. One less image will mean a faster load time
			* Optimise the images you do need to include
			* Set expire headers for your images on your server or .htaccess file
			* PictureFill as a polyfill
		* Advanced
			* Lazy load images using jquerys lazy load plugin
			* use sizes and picture for feature detection
	* Performance
	* Conditional and lazy loading
		* Basic
			* Enable gzipping for files and set expire headers for all static content
			* Use Lazy Load jQuery plugin
		* Advanced
			* Set up a CDN
			* Enable SPDY for http2-enabled browsers to take advantage of http2 features like parallel http requests
			* Ajax Include pattern will load content snippets from data-attributes
	* Responsive typography
		* Basic
			* Base your font on 100% body
			* Work in relative em units
			* Set your margins to you line height to maintain vertical rhythm in your design
		* Advanced
			* Improve font loading performance with enhance.js or deferred font loading
			* Use Sass @includes for semantic headings
	* Media queries in JavaScript
		* Forget about JS for different viewports. Provide content and website functions to users in a way they can access it across all viewports. We should never need JavaScript
		* Extend Gustafson's method by using breakup as a predefined list of media queries and automating the creation of the list of font families for getActiveMQ-watcher
	* Progressive enhancement
	* Layout
* [VIDEO: Jason Grigsby talking about the "why" of "responsive images](https://vimeo.com/134952797)
	* resolution switching
	* art direction
	* text on images
	* image breakpoints
	* memory usage on resizing
	* hero images aka a box for marketing
* [The anatomy of responsive images](https://jakearchibald.com/2015/anatomy-of-responsive-images/)
	* Fixed size, varying density --> src + srcset with x-descriptor
	* Varying size and density --> src + srcset with w-descriptor + sizes
	* Varying width, density and art direction --> picture element with nested img element with src + srcset with w-descriptor and sizes
	* Varying on type --> type attribute of picture element
	* Further reading
* [5 responsive design pitfalls and how to avoid them](http://www.sitepoint.com/5-responsive-design-pitfalls-and-how-to-avoid-them/)
	1. Unexpected font-size changes
	2. Unwanted form styles
	3. Emulator errors can mislead
	4. Smooth animation on desktop could be a rough animation on mobile
	5. The coordinates of a touch are stored differently than the coordinates of a click
* [Create responsive forms and tables](http://www.creativebloq.com/rwd/create-responsive-forms-and-tables-101517303#disqus_thread)
	* Tables
		* Things that are not tables
		* Things that appear to tables
		* Things that must be tables
	* Forms
		* Layout
		* Validation
			* Inside the input
			* Outside the input
		* Dates
		* Selects
		* Long selects
		* Complex selects
	* Let's face it, these things are messy
* [9 responsive design mistakes you don't want to make](http://thenextweb.com/dd/2015/10/28/9-responsive-design-mistakes-you-dont-want-to-make/)
	1. Focusing on devices instead of screens
	2. Using only device sizes as breakpoints
	3. Only thinking small
	4. Hiding content
	5. Insisting on consistent navigation
	6. Failing to design for touch
	7. Linking to non-mobile friendly content
	8. Ignoring performance
	9. Forgetting to test your design
* [9 responsive typography tips from the experts](http://www.creativebloq.com/rwd/expert-responsive-typography-tips-101517572)
	1. Size your body text appropriately
	2. Consider the reader
	3. Watch your measure
	4. Adjust line spacing
	5. Use visual variation other than size
	6. Choose fonts wisely
	7. Use a type test rig
	8. Set type in context
	9. Learn from others
* [Being responsive to the small things](https://24ways.org/2015/being-responsive-to-the-small-things/)
	* Enter container queries
	* Our saviour this christmas: JavaScript
	* Christmas is over
* [7 common mistakes made with responsive mockups](http://www.creativebloq.com/web-design/common-mistakes-responsive-mockups-111517922)
	1. Designing for devices, not screens
	2. Relying only on device sizes for breakpoints
	3. Ignoring touch controls
	4. Linking to content that isn't mobile-friendly
	5. Poor planning for bigger screens
	6. Using consistent navigation across screen-sizes
	7. Hiding content
* [http://blog.cloudfour.com/responsive-guide-to-type-sizing/](A responsive guide to type sizing)
	* Using a modular scale for typographic proportions
	* Applying your scale from the ground up
		* Configuring the variables
		* Establishing default sizes
		* Expanding your scale when proportional contrast is needed
		* Broadening the usage of your scale

#<a name="progressive_enhancement"></a>Progressive Enhancement

> Progressive enhancement is more about dealing with technology failing than technology not being supported. - Andy Hume

* [Progressive enhancement with handlers and enhancers](https://hiddedevries.nl/en/blog/2015-04-03-progressive-enhancement-with-handlers-and-enhancers)
* [Everyone has JavaScript, right?](http://kryogenix.org/code/browser/everyonehasjs.html)
* [The true cost of progressive enhancement](https://medium.com/@AaronGustafson/the-true-cost-of-progressive-enhancement-d395b6502979)
* [Advancing JavaScript without breaking the web](https://channel9.msdn.com/Events/WebPlatformSummit/2015/Advancing-JavaScript-without-breaking-the-web)
* [Thriving in unpredictability](http://timkadlec.com/2015/06/thriving-in-unpredictability/)
* [Baseline](https://adactio.com/journal/9206) 
* [Video: Jake Archibald talking about performance, service worker and progressive enhancement](https://vimeo.com/134952424)
* [Video: Aaron Gustafsson - Where do we go from here](https://vimeo.com/134954018)
	* [transcript](http://www.sitepoint.com/responsive-web-design-where-do-we-go-from-here/)
* [Video: Jeremy Keith - enhance!](https://vimeo.com/137117401)
* [Video: Jake Archibald - Modern progressive enhancement](http://www.fivesimplesteps.com/products/modern-progressive-enhancement)
	> Every phase of enhancement needs a real user
	* loading time is important but time to first byte and time to start render is much more important (perception of speed)
	> The only time people hate wasting the most is right now.
* [Video: Jeremy Keith - The Long Web](http://aneventapart.com/news/post/the-long-web-by-jeremy-keith-an-event-apart-video)
* [Understanding progressive enhancement](http://alistapart.com/article/understandingprogressiveenhancement)
	* There's a (subtle difference)
		* The graceful degradation perspective
		* The progressive enhancement perspective
	* So how does it work?
		* The peanut
		* The chocolate coating
		* The hard candy shell
	* Putting it all together
* [Progressive enhancement with CSS](http://alistapart.com/article/progressiveenhancementwithcss)
	* Style sheet organization
		* Use multiple style sheets
		* Working with alternate media types
	* Now for the $10M question: how do we deal with IE6?
	* Other considerations
	* Putting it all together
* [Interaction is an enhancement](http://alistapart.com/article/interaction-is-an-enhancementl)
	* Get familiar with potential issues so you can avoid them
	* Understand your medium
	* Why no JavaScript
* [Reimagining Single-Page Applications with progressive enhancement](https://www.smashingmagazine.com/2015/12/reimagining-single-page-applications-progressive-enhancement/)
	* Writing views
	* Navigation
	* One view at a time
	* The default view
		* It's time
	* The hashchange event
	* Abstraction
		* Notes
	* Completely static views
		* Static views with enhanced functionality
	* Conclusion
* [Getting started with progressive web apps](https://addyosmani.com/blog/getting-started-with-progressive-web-apps/)
	* What is a progressive web app?
	* Principles
		* Web app manifest
		* Add to home screen banner
		* Service worker for offline caching
		* Push notifications for re-engagement
		* Layering in advanced features
		* Framework-friendly
	* Architecture
	* Getting started boilerplates
		* Application shell
		* Polymer starter kit
		* Web starter kit
	* Progressive web apps with and without frameworks
		* Vanilla JS
		* Polymer
		* React
		* Virtual-Dom
		* Angular.js
	* Closing notes
	* Further reading

#<a name="accessibility"></a>Accessibility

* [Everyone is different](https://www.youtube.com/watch?v=6ic8OO4ORI8)
* [Practical ARIA examples](http://heydonworks.com/practical_aria_examples/)
	1. Input tooltips without javascript
	2. Button controlled input with live feedback (e.g. number input)
	3. Progressive collapsibles (e.g. accordeon pattern)
	4. Simple ARIA tab interface
	5. Alert! You're offline
	6. Warning dialog
	7. A simple toolbar widget
	8. Progressive hamburger
	9. Simple dropdowns
* [7 things every designer needs to know about accessibility](https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b?section=suggested)
	1. Accessibility is not a barrier to innovation (We don't want to design for our design peers)
	2. Don't use color as the only visual means of conveying information
	3. Ensure sufficient contrast between text and its background --> [Color safe](http://colorsafe.co/)
	4. Provide visual focus indication for keyboard focus
	5. Be careful with forms
		1. Forms without borders
		2. Forms without labels (also: contrast!)
	6. Avoid component identity crises (e.g. autocomplete with edit and delete features)
	7. Don't make people hover to find things
* [UX accessibility with aria-label](https://dev.opera.com/articles/ux-accessibility-aria-label/)
	> Whenever you communicate anything on the web not using text, you're probably doing so inaccessibly

	* title attribute is urealiable
	* alt attribute is only available on certain elements
	* aria-label and aria-labelledby override other methods
* [Notes on client-rendered accessibility](http://www.smashingmagazine.com/2015/05/06/client-rendered-accessibility/)
	* Semantics
	* Interactivity
	* Focus Management
	* Notifying the user
* [Visually assess accessibility on your website - Development & testing environment](http://khan.github.io/tota11y/)
* [What does it mean to develop accessible websites](http://www.vanseodesign.com/web-design/develop-accessible-websites/)
* [Falling in love with forms](https://channel9.msdn.com/Events/WebPlatformSummit/2015/Falling-in-love-with-forms)
	* label & field
	* label, field & note --> via __aria-describedby__
	* placeholders && HTML5 input types
	* __datalist with select (and aria-labelledby) as fallback__
		* HTML5 available --> datalist only allows <option\> as child element
		* HTML5 not available --> datalist element is ignored --> select is fallback
	* grouping in list --> screenreaders
	* multiple choice --> fieldset && legend
	* aria-labelledby works as space-separated list
	* tap-friendly hit targets by negative margins and positive paddings
	* aria-required
	* tabindex="0" (follows natural tabindex order)
	>Focus on making the form __read__ naturally and easily
	* Custom error message via JS
		* field.setCustomValidity("my custom error message")
		* easy-validation.js (jquery plugin) --> polyfill for HTML5 forms & custom validation message
	* Error summary with links to relevant fields
	* Provide field-level help
		* aria-invalid && aria-describedby
* [WCAG Principles & Guidelines](http://www.vanseodesign.com/web-design/wcag-principles-guidelines/)

	1. **Principle 1: Perceivable** (Information and user interface components must be presentable to users in ways they can perceive)
		* Text alternatives (alt text for images, ...)
		* Time-based media (text version of a podcast --> not a transcription --> edited version)
		* Adaptable (present equivalent content across devices and conditions)
		* Distinguishable (provide enough color contrast + offer controls)

	2. **Principle 2: Operable** (User interface components and navigation must be operable)
		* Keyboard accessible
		* Enough time (allow to set time limits for moving information)
		* Seizures (avoid potential to induce seizures in some people)
		* Navigable (help people find what they want and where they are)

	3. **Principle 3: Understandable** (Information and the operation of user interface must be understandable)
		* Readable (multiple languages and reading level)
		* Predictable (navigation label accurately identifying where it leads)
		* Input assistance (minimize the potential for errors)
	4. **Principle 4: Robust** (Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies)

		* Compatible
			* parsing (markup)
			* name, role, value (ARIA)
* [5 rules for using ARIA roles, states, and properties](http://vanseodesign.com/web-design/five-rules-aria-html/)
	1. If you can use native HTML elements and attributes to communicate the proper semantics and behavior then do so
	2. Don't change semantics, unless you really have to
	3. All interactive ARIA controls must be usable with the keyboard.
	4. Don't use role="presentation" or aria-hidden="true" on a visible focusable element
	5. All interactive elements must have an accessible name
* [Video: What is the business case for accessibility](https://vimeo.com/134825451)
	> We can reframe accessibility in terms of what we provide, not what other people lack
* [Reframing accessibility for the web](http://alistapart.com/article/reframing-accessibility-for-the-web)
	* Who are these "people with disabilities" anyway?
	* Why do we fixate on justifying the existence of people with disabilities?
	* Reframing accessibility as a technology challenge
		* Creating a test matrix for accessibility
			* [list of input devices](https://en.wikipedia.org/wiki/Input_device)
			* [list of output devices](https://en.wikipedia.org/wiki/Output_device)
		* Checking content against the matrix
		* Testing beyond the obvious
	* People over process, unless process enables people
* [An alphabet of accessibility issues](https://the-pastry-box-project.net/anne-gibson/2014-july-31)
* [Video: Aaron Gustafsson - Where do we go from here](https://vimeo.com/134954018)
* [Accessibility - beyond the screen reader](http://www.creativebloq.com/web-design/accessibility-beyond-screen-reader-91516540)
	* Thinking outside the (black) box
	* Word wrapping
	* Proximity
	* Beyond the blind spot
* [Avoiding redundancy with WAI-ARIA in HTML pages](http://www.sitepoint.com/avoiding-redundancy-wai-aria-html-pages/)
	* ARIA basaics and general perceptions
	* Effect of ARIA roles on most elements
	* Does HTML4 need ARIA roles
	* New features in HTML5
	* Redundancy in ARIA
	* Examples of redundancy
		* Default implicit roles to interactive elements
		* ARIA role allong with native HTML counterparts
		* ARIA added to long implemented structural elements
		* ARIA with HTML5 structural elements
			* Browser support
	* Wrapping it up
* [An introduction to WAI-ARIA](http://www.sitepoint.com/introduction-wai-aria/)
	* WAI-WHAT?
		* Functionality via roles
		* States and properties (aria-controls and aria-labelledby)
		* Live regions for dynamic content (aria-live)
		* Enhanced keyboard navigation (e.g. tabindex)
	* ARIA and HTML5
	* Can I use ARIA without risk?
	* Conclusion
* [Labeled with love](https://medium.com/@AaronGustafson/labeled-with-love-bda2592250b#.dar3bbzg8)
	* Connecting the dots (using the `<label>` element - with for attribute)
	* An alternate approach (using the `<input>` element - inside a `<label>` - combined with explicit association via for attribue)
	* Added benefit: interactivity
	* Placeholders aren't labels
* [How our CSS framework helps enforce accessibility](http://www.ebaytechblog.com/2015/11/04/how-our-css-framework-helps-enforce-accessibility/)
	* Semantics
	* Swiss cheese
	* Enforcing rules
	* Implicit roles
	* Enforcing states
	* ARIA
	* Tabs
	* Faux tabs
	* Real tabs
	* Good behavior
	* Summary
* [The web accessibility basics](https://www.marcozehe.de/2015/12/14/the-web-accessibility-basics/)
	* Alternative text for images
		* All img tags require an alt attribute
		* Every alt attribute has to have a value (meaningful text)
		* It is called alt attribute but never alt tag
	* Labeling form fields
		* Every input element (except for the button ones) require a label element to be present
		* The association between such an input and label happens by giving the input a unique ID, given by the id attribute on the input, and the label's for attribute which points to said ID
		* Do not, under any circumstances, use the placeholder attribute as the label for an input element
		* Give button elements inner text
		* A series of radio buttons go inside a fieldset element to group them together
		* Fieldset and legend should also be used if grouping togechter different sections of a bigger form for better readability
		* Label required fields by providing the HTML5 required attribute on the input as well as stating in the label that a form field is required
		* Use appropriate input types for e-mail, URL, phone number etc
		* Make sure keyboard visibility is always guaranteed
	* Document structure
		* Heading structure
		* Landmarks (article, aside, footer, header, nav, main)
		* Lists (ul, ol, dl)
		* Others (p, blockquote, q, hr)
		* Tables
			* Add a caption element to give the table a proper heading or summary
			* Use th elements to denote column and row headings
			* Use other structural table elements to further structure your table
			* If a table gets too complex or has multiple sections that don't necessarily have to be in one table, split them up into several data tables
	* Some more quickies
		* Separation of concepts
		* Color contrast
		* Keep pinch alive
	* OK, but what about advanced widgets?
	* It is all in the semantics
	* In conclusion
* [The accessibility mindset](https://24ways.org/2015/the-accessibility-mindset/)
	* Beyond the bare minimum
		* Button example
	* More information
	* Conclusion
* [Seriously, don't use icon fonts](http://blog.cloudfour.com/seriously-dont-use-icon-fonts/)
	* Screen readers actually read that stuff
	* They're a nightmare if you're dyslexic
	* They encroach on emoji turf
	* They fail poorly and often
	* They never looked right
	* You're probably doing it wrong
	* There's already a better way
		* SVG's can't be combined into sprites (they can)
		* SVGs are larger in file size (not when you optimize, sprite and compress them)
		* The icon markup is too verbose by comparison (just barely)
		* Browser support for SVG is worse (not anymore)
		* The framework we chose already has an icon font
	* Don't be table guy
* [10 reasons we switched from an icon font to svg](http://ianfeather.co.uk/ten-reasons-we-switched-from-an-icon-font-to-svg/)
	1. Separation of concerns
	2. Some devices don't honour the private unicode area
	3. Black squares and crosses on opera mini
	4. Chrome support for font-icons has been terrible recently (false positive)
	5. Crisper icons in Firefox
	6. You don't always have to use generated content
	7. Less fiddly to position
	8. Multi-colour icons
	9. SVGs allow us to use animation within our icons
	10. It's always felt like a hack
	* What about the benefits of font-face?
		* Colour variations
		* Browser support
* [A quick reminder on how and why to use labels in forms to make them more accessible](https://www.christianheilmann.com/2015/12/04/a-quick-reminder-on-how-and-why-to-use-labels-in-forms-to-make-them-more-accessible/)

#<a name="performance"></a>Performance

* [Supercharging page load](https://www.youtube.com/watch?v=d5_6yHixpsQ)
* [When it comes to delivering the best possible user experience, how fast is fast enough?](http://www.soasta.com/blog/website-monitoring-fast-enough-user-experience/)
* [10 ways to optimise images for better performance](http://www.creativebloq.com/netmag/10-ways-optimise-images-better-performance-71515792)
	1. Lossless optimisation with [ImageOptim for OS X](http://imageoptim.com/) or [FileOptimizer for Windows and Linux](http://nikkhokkho.sourceforge.net/static.php?page=FileOptimizer)
	2. Use correct dimensions
	3. Save for web
	4. Audit and remove images
	5. GIFs and PNGs
	6. Downsample PNGs with [ImageAlpha for OS X](http://pngmini.com/) or [PNGyu for windows](http://nukesaq88.github.io/Pngyu/)
	7. The right file format
		* animation --> lossy GIF
		* photograph --> JPEG
		* photograph with transparency --> lossy PNG
		* otherwise --> 8-bit PNG --> fall back to JPEG if unsatisfied with quality
	8. Cache-Control: no-transform
	9. CSS and SVG
	10. Progressive JPEGs
* [Fix scrolling performance with CSS will-change property](https://fourword.fourkitchens.com/article/fix-scrolling-performance-css-will-change-property)
	* background-attachment:fixed causes a paint operation on scroll
	* put background in different element (pseudo)
	* add "will-change:transform;" --> it creates a new paint layer
* [HTTP/2 - The future of the web is already here](http://www.creativebloq.com/web-design/http2-future-already-here-71515657)
	* Multiplexing (allowing requests and responses for multiple objects to overlap on the same connection)
	* Header compression (helping to solve the stateless nature of HTTP/1 where a browser needs to address support for a given file format or language on every request)
	* Dependencies and prioritisation (communicating to the server what objects are dependent on what other objects, and listing the priorities, the server can make certain the critical data is delivered to the browser right away.)
	* Server push (addressing round trip latency of an HTTP request and response by sending the browser an object before it is asked for)
	* And for the everyday user?
		* no one will have to change their website or applications to ensure they continue to work properly
		* if you want to benefit from performance and security features, consider some things
			* encryption (applications running over HTTP/2 are likely to experience improvements in performance over secure connections)
			* Optimising the TCP layer (applications should be designed with a TCP layer implemented to account for the switch from mulltiple TCP connections to a single long-lived one, especially when adjusting the congestion window in response to packet loss
			* undoing HTTP/1.1 best rpactices (domain sharing, image spriting, resource in-lining and concatenation)
			* Deciding what and when to push
* [Video: Jake Archibald talking about performance, service worker and progressive enhancement](https://vimeo.com/134952424)
* [Strategies for Cache-Busting CSS](https://css-tricks.com/strategies-for-cache-busting-css/)
	* Query strings
	* Changing file names
	* Basing Cache Busting "Number" on File updated date
	* ETags
	* Framework does it for us
		* Rails asset pipeline
		* Wordpress
	* Build tools
	* Async CSS
* [Eliminating roundtrips with preconnect](https://www.igvita.com/2015/08/17/eliminating-roundtrips-with-preconnect/)
	* Preconnect for dynamic request URLs
	* Initiating preconnect via Link HTTP Header
	* Preconnect with JavaScript
	* Preconnect often, Preconnect wisely
* [The illusion of time](https://medium.com/swlh/the-illusion-of-time-8f321fa2f191#.c9qb9mrqj)
	* Time in the digital age
	* Keep users engaged
	* Perform actions optimistically
	* Create transitional interfaces
	* Avoid modal spinners
	* Communicating longer waits
		* Progress bars
		* Countdowns/ETA
	* Load Content Progressively
	* Tick. Tock.
* [Saving bandwidth by using images the smart way](http://www.sitepoint.com/saving-bandwidth-by-using-images-the-smart-way/)
	* Choosing the appropriate image format
		* GIF
		* PNG (PNG8 vs PNG24)
		* JPG
	* Let's compare
	* Does 'Save for web' make any _real_ difference?
	* Serving resized images
	* Avoiding images altogether
* [Why performance matters, part 1: The perception of time](http://www.smashingmagazine.com/2015/09/why-performance-matters-the-perception-of-time/)
	* Basic concepts
	* Part 1: objective time
	* Choosing a performance budget
	* The need for performance optimization: the 20% rule
	* Neutralization, or chasing the leader
* [Why performance matters, part 2: Perception management](http://www.smashingmagazine.com/2015/11/why-performance-matters-part-2-perception-management/)
	* Psychological time: perception management
		* Preemptive start
		* Early completion
	* Conclusion... for now
* [HTTP/2: the pros, the cons, and what you need to know](http://www.sitepoint.com/http2-the-pros-the-cons-and-what-you-need-to-know/)
	* How HTTP/1 works
	* How HTTP/2 will work
		* multiplexed streams
		* server push
		* header compression
		* binary instead of textual format
	* What developers will be able to do differently now
		* Things to be aware of
			* most browsers supporting HTTP/2 will require HTTPS encryption
			* the web will transition painlessly for the public
	* Some controversy
	* See the difference
	* Bottom line
* [9 things you can do today to make your site load faster](http://www.creativebloq.com/web-design/make-your-site-load-faster-101517559)
	1. Find the best host possible and consider more power than that
	2. Crack down on your images and optimize them properly
	3. Evacuate your themes, plugins and comments
	4. Go crazy with caching
	5. Maybe minify your code? Yes!
	6. Check on the more necessary plugins that slow the site down
	7. Optimize your database
	8. Crack a CSS sprite
	9. Consider lazyloading your images
* [6 quick things developers can do to improve performance](http://www.creativebloq.com/web-design/6-quick-things-developers-can-do-improve-performance-111517884)
	1. Compress your images and serve them at the correct size
	2. Minify and compress all your HTML, CSS, and JavaScript
	3.  Limit the use of heavy JavaScript. Render as much as you can on the server and use JavaScript to sprinkle on enhancements
	4.  Optimise for the critical path so that your content appears as quickly as possible
	5.  Start familiarising yourself with HTTP/2 because that changes so many things
	6.  If you're going to use something like Bootstrap, be sure you remove all the unused CSS in a build process. There's a ton of unnecessary bloat.
* [Building for HTTP/2](http://rmurphey.com/blog/2015/11/25/building-for-http2)
	* Deploying JavaScript applications (2013)
	* Splitting it up
	* Versioning
	* Push: Because you downloaded scout.js, you might also like...
	* The elephants in the room
	* For consideration: HTTP/2-friendly deployments with HTTP/1.1 support
	* Reality check
* [Intrinsic placeholders with the picture element](http://daverupert.com/2015/12/intrinsic-placeholders-with-picture/)
* [VIDEO: Mat Marquis - Smaller, faster websites](https://bocoup.com/weblog/smaller-faster-websites)
	* Images in responsive web design
	* Critical CSS
	* Web fonts loading
* [VIDEO: Maciej Ceglowski - The website obesity crisis](https://vimeo.com/147806338)
* [Optimising SVGs for web use - part 1](https://medium.com/larsenwork-andreas-larsen/optimising-svgs-for-web-use-part-1-67e8f2d4035)
	* Raison d'être
	* The Path
		* Use fewer nodes
		* Use fewer handles
		* Use integers
		* Don't use a grid that is any bigger than necessary
	* The result
		* Graphics
		* Code
* [Optimising SVGs for Web Use - part 2](https://medium.com/larsenwork-andreas-larsen/optimising-svgs-for-web-use-part-2-6711cc15df46#.du5kkdo5f)
	* Step 1 - get/draw an icon
	* Step 2 - determine the optimal size for the viewbox
	* Step 3 - load the svg into your editor
	* Step 4 - reduce the number of nodes + handles
	* Step 5 - round to int
	* Step 6 - re-add the circle
	* Step 7 - cleanup
	* The result
	* Another example
	* PS
* [Optimising SVGs for web use - part 2 &frac12;](https://medium.com/larsenwork-andreas-larsen/optimising-svgs-for-web-use-part-2-1-598815d74f9c#.punh4l9f8)
	* Get the logo
	* Save the svg
	* (SVGO)
	* We need more
	* Circle
	* Remove the last node
	* Cubic vs quadratic
	* Bytes saved
	* Mpre
* [The future of loading in CSS](https://jakearchibald.com/2016/link-in-body/)
	* The current state of loading CSS
	* The current state-of-the-art of loading CSS
		* It requires a (small) JavaScript library
		* You're restricted to two phases of loading
	* A simpler, better way
	* Changes to chrome
		* Firefixing
	* See it in action
* [Instant loading with Service Workers](https://www.youtube.com/watch?v=jCKZDTtUA2A&index=5&list=PLNYkxOF6rcICcHeQY02XLvoGL34rZFWZn)
* [HTTP/2 101](https://www.youtube.com/watch?v=r5oT_2ndjms&index=19&list=PLNYkxOF6rcICcHeQY02XLvoGL34rZFWZn)
	* [Setting up HTTP/2](https://surma.link/things/h2setup/)

#<a name="web_components"></a>Web Components

##<a name="polymer"></a>Polymer

* [Polymer for the performance obsessed](https://aerotwist.com/blog/polymer-for-the-performance-obsessed/)
	1. Inline styles and region your app
	2. Conditionally (and async) load the polyfill 
	3. Only bundle related elements
	4. Don't inline polymer into your bundles

#<a name="design_testing"></a>Design testing

* [7 best pieces of user testing software](http://www.creativebloq.com/ux/best-user-testing-software-61515337)
	1. [Peek by User testing](http://peek.usertesting.com/)
	2. [Crazy Egg](http://www.crazyegg.com/)
	3. [Inspectlet](http://www.inspectlet.com/)
	4. [Optimizely](https://www.optimizely.com/)
	5. [Usabilla](https://usabilla.com/)
	6. [User Zoom](http://www.userzoom.co.uk/?langchoice=uk)
	7. [Morae](http://www.userzoom.co.uk/?langchoice=uk)
* [Talking to users in a usabillity test](http://www.nngroup.com/articles/talking-to-users/)
	* Echo (repeat the last phrase or word the user said, while using a slight interrogatory tone)
	* Boomerang (generic nonthreatening question - e.g. what do you think, what would you normally do)
	* Columbo (be smart but don't act that way)  
* [How to use the System Usability Scale to evaluate the usability of your website](http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
* * [Ultimate guide to user feedback part 1: Why user feedback matters](http://blog.teamtreehouse.com/ultimate-guide-user-feedback-part-1-user-feedback-matters)
	* Feedback: the best way to improve a project once you know how to build it
	* Why get feedback?
		* It'll help you regain perspective on your project
		* You can't know everything, even when you know more about your project than anyone else
		* It helps prevent small problems from growing into big problems
		* It helps increase your awareness of possible issues (even if you don't make changes right away)
		* You'll learn about problems you had no idea existed
	* But you don't have to get feedback if you don't want to (as long as you know the downsides)
		* Your focus is more on learning about _how_ not on _what_ is built
		* You're just building for yourself, and just for the fun of it
		* The key is to know when you're building for yourself and when you're building for others
	* When to get feedback
* [Ultimate guide to user feedback part 2: 10 ways to get user feedback](http://blog.teamtreehouse.com/ultimate-guide-user-feedback-part-2-10-ways-get-user-feedback)
	1. Existing users via email or an in-app option
	2. Call or talk to your existing users
	3. Talk to people who you think would use your project
	4.  Talk to users of a similar project as yours (or even a competing project)
	5.  On-page (or in-app) chat
	6.  On-page (or in-app) survey tools
	7.  Talk to people you know
	8.  Show your project to strangers (in-person)
	9.  Use a service or remote tool (like UsersThink)
	10.  Use a mix of the approaches above
* [Optimize your design for rapid prototype testing](https://www.smashingmagazine.com/2015/12/optimizing-your-design-for-rapid-prototype-testing/)
	* Design to test specific stimuli, with few variables at a time
	* Make copy consistent when it is not being tested
	* Don't sweat details that don't matter
	* Focus on what you want to learn from users, not stakeholders
	* Create a clear path
	* Capture user behavior, in addition to feedback
	* Keep in mind
		* Do not prototype the entire product
		* Plan for multiple rounds of testing
		* Educate your stakeholders
		* Define up front what a succesful user experience looks like
		* Pay attention to the size of copy
		* Learn as much as possible about how the test will be conducted
		* Create reusable templates
		* Save a set of "unbranded" templates
		* Leverage standard user interface elements
		* Choose images and content that will not potentially bias the outcome of the test
		* Consider recreating the live website in prototype form
	* Cheat sheet
	* Summary
* [7 new ways to test your minimum viable product](http://www.sitepoint.com/7-new-ways-to-test-your-minimum-viable-product/)
	1. Wizard of Oz
	2. Fake door
	3. Audience building
	4. Micro-surveys
	5. Competition analysis
	6. Crowdfunding
	7. Software tests

#<a name="email_design"></a>Email design

* [What you should know about HTML email](http://webdesign.tutsplus.com/tutorials/what-you-should-know-about-html-email--webdesign-12908)
	* Coding HTML Email can be a challenge
		* Email standards don't exist
	* How to approach your work
		* Work structurally first
		* Test often - [Litmus](http://www.litmus.com) or [Email on Acid](http://www.emailonacid.com)
		* Validate often
		* Sending your email
		* Content, Development and SPAM scores
	* Diving into development
		* Tools of the trade
		* Starting with a good base
		* !DOCTYPE	(include content-type + viewport)
		* Email is all about nesting tables (rowspan and colspan not supported)
		* Paragraphs or cells (inconsistent rendering of semantic tags)
		* Inline styles or stylesheets (max 1 class per element, no shorthand properties)
		* Image names and SPAM scores
		* Image size
		* Other gotchas (specify ALL widths, main container in pixels, rest can be done with percentages)

#<a name="web_fonts"></a>Web Fonts

* [Web Font Anti-Patterns](http://bramstein.com/writing/web-font-anti-patterns.html)
	* Overusing web fonts
		* Using web fonts for lettering
	* Inlining fonts
		* Base64 encoding and decoding
		* Font format negotiation
		* Caching
	* Aggressive subsetting
	* Using local fonts
	* Reimplementing caching
	* Not styling fallback fonts