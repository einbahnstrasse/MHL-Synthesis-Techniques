---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: archive
layout: single   
title: Schedule   
lang: en   
ref: sched   
permalink: /schedule/   
# sidebar:
#   nav: "schedule-toc"   
toc: true  
toc_label: "Schedule" # default: Content
toc_icon: "bell"  # corr esponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc 
read_time: true  
date: 2024-03-20   
last_modified_at: 2024-03-20   

---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/lipis/flag-icons@6.11.0/css/flag-icons.min.css"/>

<div class="lang-sidebar">
  {% assign pages=site.pages | where:"ref", page.ref | sort: 'lang' %}
  {% for page in pages %}
    <li class="zoom"><a href="{{ page.url }}" class="{{ page.lang }}"><span class="fi fi-{{ page.lang }}"></span></a></li>
  {% endfor %}
</div>

<div class="top-h1-icon">
  <i class="fas fa-bell fa-2x"></i>
</div>

<!-- <img src="/Goldford-MTEC1003/assets/organized.gif" alt="organized" width="400" align="right"> -->

<!-- # Schedule -->
_This page will be updated frequently with examples, video tutorials, links to new resources, and occasional updates to ASSIGNMENTS. Our schedule follows the [Current MHL Academic Calendar]({{ site.MHL-calendar }}){:target="_blank"}. The following topics and their precise order may change. Check here for updates!_  

* * *

## Week 1: {{ site.week-01 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-01-topic }}</span>    

#### Start-of-Semester Business  

* Review [Syllabus + course policies.](/MHL-Synthesis-Techniques/index.html){:target="_blank"}  
* Review [Software Installation.](/MHL-Synthesis-Techniques/resources/){:target="_blank"}   
* Join our Digitale Kreation Discord Server _(see link on Syllabus page)_  
<!-- * Review [Detailed Breakdown of Grading.](/MHL-Synthesis-Techniques/grading/){:target="_blank"}   -->

#### Tutorials   
* [Introduction to MaxMSP Slides 1—18: What is MaxMSP?](https://einbahnstrasse.github.io/MHL-intro-to-MaxMSP/){:target="_blank"}   
* [Introduction to MaxMSP (video, 33 minutes)](https://youtu.be/DpKIQzjOh_U?si=ozCElT5NQmD-m9D0){:target="_blank"}        

{% include video id="DpKIQzjOh_U?si=ozCElT5NQmD-m9D0" provider="youtube" %}    

_Choose auto-generated German translations of subtitles if it would help:_  

<img src="/MHL-Synthesis-Techniques/assets/images/auto-generated-subtitles.png" alt="auto-generated subtitles" width="200">  

#### Listening   
* [Max Mathews, _Bicycle Built for Two_ (1961)](https://youtu.be/ZFUVR-clo8g?si=xdj3dzQyMBw-g1Ui){:target="_blank"}     

{% include video id="ZFUVR-clo8g?si=xdj3dzQyMBw-g1Ui" provider="youtube" %}    

#### Downloads    
* [Media Folder of Test Sounds](https://github.com/einbahnstrasse/synth-tech-media){:target="_blank"}     
  
#### Assignments      
_(Unless otherwise noted, assignments are always due before the next class!)_    
* **Install** + **Authorize** MaxMSP   
* Join our Digitale Kreation Discord Server _(see link on Syllabus page)_  
* **Finish these patches** we made in class:   
  - `_scaffold.v01.maxpat`  
  - `lg.sound.in.v01.maxpat`  
  - `lg.sound.out.v01.maxpat`  
  - `00.getting.started.maxpat`  
  - `working.patch.v01.maxpat`  
* **Watch** the [Introduction to MaxMSP (video, 33 minutes)](https://youtu.be/DpKIQzjOh_U?si=ozCElT5NQmD-m9D0){:target="_blank"} video (above), and **make the simple patch** in the video.    

#### Terms, Concepts, Objects, Shortcuts   
_You don't have to memorize these. Use this list as a ***reference*** to remember when we discussed these concepts. Leave ***comments in your patches*** to remind yourself what these are and how they work!_   
- realtime vs. offline electronics   
- computer music   
- patch   
- subpatch `<p>`  
- abstraction   
- object box `command + n`  
- patch cable (or patch cord)   
- lock/unlock patch `command + e`  
- message box `<m>`   
- comment box `<c>`  
- control rate (Max)  
- signal rate (MSP)  
- resize boxes `command + j`   
- duplicate an object `command + D` on any object (or group of objects)  
- open help file: `option + click` on any object   

* * *

## Week 2: {{ site.week-02 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-02-topic }}</span>    

#### Tutorials   
* [MaxMSP Keyboard Shortcuts (MacOS and Windows)](https://docs.cycling74.com/max8/vignettes/shortcuts){:target="_blank"}   
* [Learn About Waveforms (The Pudding)](https://pudding.cool/2018/02/waveforms/){:target="_blank"}   
* [Introduction to MaxMSP Slides 19—35: History through New Terms](https://einbahnstrasse.github.io/MHL-intro-to-MaxMSP/#/19){:target="_blank"}   
* [MaxMSP Beginner's Cheatsheet _(includes Data Classes)_](https://cycling74-web-uploads.s3.amazonaws.com/5462c2a9bdbb99652da7a00a/2017-05-11T08:53:04Z/cheatsheet.pdf){:target="_blank"}     
* [Introduction to GIT (video, 28 minutes)](https://youtu.be/Lw2OgM6tQd8?si=jaZH3IwjPTfGPy4f){:target="_blank"}      

{% include video id="Lw2OgM6tQd8?si=jaZH3IwjPTfGPy4f" provider="youtube" %}    
  
#### Downloads   
  
* [**Week 2** Boiler Patches](https://github.com/einbahnstrasse/MHL-synth-tech-week-2-boilers){:target="_blank"}  
   
#### Listening   
* [Bernard Parmegiani, excerpt from _Ondes Croisées_ from _De Natura Sonorum_ (1978)](https://youtu.be/-GMedIlNmmw?si=mbQDQw2tpbr2NZh8){:target="_blank"}       
   
{% include video id="-GMedIlNmmw?si=mbQDQw2tpbr2NZh8" provider="youtube" %}    
_Consider this attempt to **codify** and to **notate** these abstract electronic sounds._   
   
#### When You See Triangular Brackets   

`<>` denotes a MaxMSP **object**   

When you see **triangular brackets** on this website or in the comments of our pedagogical patches, these help you identify **what to type in an _object box_** or in some cases, what **single letter to type without an object box**, to make the objects that turn into **GUIs (graphical user intefaces)**.   

_Don't type the brackets, only what is inside them._ For example:   

<img src="/MHL-Synthesis-Techniques/assets/images/max.brackets.png" width="85%" alt="triangle brackets example">   

#### Assignments   
* **Install the bach package** using the Max Package Manager _(see the Software and Resources page for details about using the package manager)_.    
* **Finish these patches** we made in class:   
  - `lg.midi.in.v01.maxpat`  
  - `01.basic.waveforms.maxpat`  
  - `02.ADSR.maxpat`  

* **Watch** the [Introduction to GIT (28 minutes, link is above)](https://youtu.be/Lw2OgM6tQd8?si=jaZH3IwjPTfGPy4f){:target="_blank"} video (above), and **set up your repository** for class.    
   
#### Terms, Concepts, Objects, Shortcuts   
- oscillator   
- sine wave oscillator `<cycle~>` 
- sawtooth wave oscillator `<phasor~>` 
- triangle wave oscillator `<tri~>` 
- square wave oscillator `<rect~>`   
- ADSR (attack, decay, sustain, release)  
- envelope   
- duty cycle   
- monosynth   
- **accessing help files**: If you have any questions about how an object works or what it does, remember that you can `option + click` on any MaxMSP object to bring up its help file.   

* * *

## Week 3: {{ site.week-03 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-03-topic }}</span>    

#### Downloads   

* [**Additive Synthesis** Boiler Patches](https://github.com/einbahnstrasse/additive.synthesis.boiler.v01/){:target="_blank"}  
   
#### Tutorials   
* [Introduction to MaxMSP Slides 36-47: Listening Repertoire through Pedagogical Patches](https://einbahnstrasse.github.io/MHL-intro-to-MaxMSP/#/36){:target="_blank"}   
* [Sampling Theorem and the Nyquist Frequency (Digital Audio Fundamentals)](https://youtu.be/vrXGaFV1AmE?si=mNTkZROJiiBjsFEQ){:target="_blank"}  

{% include video id="vrXGaFV1AmE" provider="youtube" %}  

* [Example of **Timbral Fusion** by the Addition of Sine Waves](https://youtu.be/5T4kH1qk3VE?si=p66rjMtRLkGB-9-x){:target="_blank"}  

{% include video id="5T4kH1qk3VE?si=p66rjMtRLkGB-9-x" provider="youtube" %}  
Source: Fitz, Kelly. “Sound Modeling and Morphing.”    
   
#### Listening   
* [Karlheinz Stockhausen, _Studie II_ (1954)](https://youtu.be/_qi4hgT_d0o?si=QK4OQxQV8tt8Gq5s){:target="_blank"}       

{% include video id="_qi4hgT_d0o?si=QK4OQxQV8tt8Gq5s" provider="youtube" %}    
  
* [Jean-Claude Risset, _Mutations_ (1977)](https://youtu.be/B54k8UFuihs?si=x9Z87UvwSSihjFGE){:target="_blank"}     

{% include video id="B54k8UFuihs?si=x9Z87UvwSSihjFGE" provider="youtube" %}    

#### Assignments   
* **Assign** the [Microphone Cable Coiling](https://einbahnstrasse.github.io/MHL-Synthesis-Techniques/xlr-cable-coiling/){:target="_blank"} Assignment (due in Week 6).  
* **Finish these patches** we made in class:   
  - `additive.07.synth.maxpat`  
  - `additive.08.sine.bank.maxpat` _(postponed until further notice)_    
  - `additive.09.power.law.maxpat` _(postponed until further notice)_    
  
* Also, for next week (optional): For our modulation synthesis week, we'll be taking a trip **back to the 80s**. For reasons that will become clear soon, it's pretty much gonna be an 80s party. I can't promise that I _won't_ be wearing some 80s stuff, so feel free to join in if you like that vibe!   
   
<img src="/MHL-Synthesis-Techniques/assets/images/80s.stuff.jpg" alt="80s.stuff.jpg">  

#### Terms, Concepts, Objects, Shortcuts   
- frequency  
- amplitude   
- phase   
- additive synthesis   
- oscillator bank   
- fusion   
- fundamental   
- partial   
- harmonic    
- overtone   
- timbre   
- `<cycle~>`  
- `<kslider>`  
- `<line>`  
- `<function>`  
- `<spectroscope~>`  
- `<scale>`  
- `<multislider>`  
- `<ioscbank~>`   

* * *  

## Week 4: {{ site.week-04 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-04-topic }}</span>    

#### Tutorials   
* [John Chowning, and the origin of the DX7 & FM Synthesis _(see chapter markers below)_](https://youtu.be/sXt_NXjc7oY?si=Jwf3VD3vfh598h0M&t=249){:target="_blank"}       
  - _**click** on the links below to watch the following chapters:_   
    - [Chapter 3 - FM Discovery](https://youtu.be/sXt_NXjc7oY?si=4L1CmlXKvZfbDJMl&t=249){:target="_blank"}       
    - [Chapter 4 - FM License - Stanford & Yamaha](https://youtu.be/sXt_NXjc7oY?si=-ODhlMgB2Y_wlPhB&t=367){:target="_blank"}       

_Or, you can simply select each chapter in the video player's timeline below (visible after you click to begin playback...):_   

{% include video id="sXt_NXjc7oY?si=Jwf3VD3vfh598h0M&t=249" provider="youtube" %}   

* [Yamaha DX7 - Famous Sounds Demo](https://youtu.be/BCwn26FePAo?si=EpZ-nuB-QooIkU_m){:target="_blank"}       
   
{% include video id="BCwn26FePAo?si=EpZ-nuB-QooIkU_m" provider="youtube" %}   

#### Listening   
* [John Chowning, _Stria_ (1977)](https://youtu.be/988jPjs1gao?si=1RMp19Z9PhJIP6PN){:target="_blank"}       
   
{% include video id="988jPjs1gao?si=1RMp19Z9PhJIP6PN" provider="youtube" %}    
    
* [Tristan Murail, _Atlantys_ (1984)](https://youtu.be/rnwoUFhxQLo?si=1mDzM7-voHq_brv_){:target="_blank"}       
   
{% include video id="rnwoUFhxQLo?si=1mDzM7-voHq_brv_" provider="youtube" %}    
     
#### Assignments   
* **Complete our patches** using the [video tutorial](https://youtu.be/BGf7V3CZpwI){:target="_blank"} below, **this weekend if possible, or by Week 6** at the latest:   
   
{% include video id="BGf7V3CZpwI" provider="youtube" %}    

<!-- * Respond to the [Week 4 Discord Reaction Post](https://einbahnstrasse.github.io/MHL-Synthesis-Techniques/week-04-discord-reaction/){:target="_blank"}   assignment before class next week!   -->
* **Finish these patches** we made in class:   
  - `random.notes.maxpat` _(in Week 1 folder and in _scaffold.v01.maxpat)_       
  - `01.RM.AM.FM.on.Waveforms.maxpat`  
  - `02.RM.AM.on.Sounds.maxpat`      

#### Terms, Concepts, Objects, Shortcuts   
- modulation   
- ring modulation (RM)  
- sin-to-sin   
- sin-to-square   
- amplitude modulation (AM)   
- frequency modulation (FM)   
- tremolo   
- vibrato   
- audio rate threshold     
- carrier frequency (ƒc)   
- modulator frequency (ƒm)  
- modulation depth  
- low frequency oscillator (LFO)   
- `<matrix~>`  
- `<crosspatch>`  

* * *  

## Week 5: {{ site.week-05 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-05-topic }}</span>    

#### Tutorials    
* [Aliasing (Digital Audio Fundamentals)](https://youtu.be/91PKZllbgds?si=4sgl-6mLGVlhrnUm){:target="_blank"}     

{% include video id="91PKZllbgds" provider="youtube" %}    

* [Wagon Wheel Effect Example Due to Undersampling](https://youtu.be/ByTsISFXUoY?si=eqtXaZ1cI9kbZd9p){:target="_blank"}     

{% include video id="ByTsISFXUoY?si=eqtXaZ1cI9kbZd9p" provider="youtube" %}    

* MSP Audio Input Chain (Including Anti-Aliasing Filters):     

<img src="/MHL-Synthesis-Techniques/assets/images/msp.audio.input.chain.png" alt="MSP Audio Input Chain" width="100%">  

_In many modern digital audio programs and soundcards, the use of **anti-aliasing filters** can be used to remove frequencies above the Nyquist rate, and therefore **avoid aliasing artefacts**. Above is an example of how this is accomplished in MaxMSP._   

#### Downloads   

* [**Live Processing** Boiler Patches](https://github.com/einbahnstrasse/live.processing.boiler){:target="_blank"}  

#### Listening   
* [Sam Pluta and Peter Evans, _Third Piece_, Live at Roulette (2014)](https://vimeo.com/114201582){:target="_blank"}      
  
{% include video id="114201582" provider="vimeo" %}      
        
#### Assignments   
* Reminder: Next week's class is on Zoom! _(see link below)_    
* **Finish these patches** we made in class:   
  - `live.processing.v01.delay.line.maxpat`      
  - `live.processing.v02.flanging.maxpat`    
  - `live.processing.v03.harmonizer.maxpat`    
  - `live.processing.v04.envelope.follower.maxpat`   
  - `live.processing.v05.transient.detection.maxpat`   

#### Terms, Concepts, Objects, Shortcuts   
- real-time synthesis   
- live input signal  
- delay line    
- flanger   
- harmonizer   
- envelope follower   
- `<tapin~>`  
- `<tapout~>`  
- `<pitchshift~>`  
- `<peakamp~>`  

* * *   

## Week 6: {{ site.week-06 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-06-topic }}</span>    
  
#### Zoom Link   
* [https://columbiauniversity.zoom.us/j/99641354486?pwd=Mk1BNW9PdkI4anRXVE5wR1dkR3dqZz09](https://columbiauniversity.zoom.us/j/99641354486?pwd=Mk1BNW9PdkI4anRXVE5wR1dkR3dqZz09){:target="_blank"}     
     
#### Tutorials  
* [Subtractive Synthesis Boiler Patches](https://github.com/einbahnstrasse/subtractive.boiler){:target="_blank"}     

#### Listening   
* [Jean-Baptiste Barriere, _Chreode I_ (1983)](https://youtu.be/5AEFhybYrPg?si=Iwu6LrsWm1dxx_Zj){:target="_blank"}       
   
{% include video id="5AEFhybYrPg?si=Iwu6LrsWm1dxx_Zj" provider="youtube" %}    
  
* [Fausto Romitelli, _EnTrance_ (1995)](https://youtu.be/NBteiaa31iI?si=rUsWraS6wQWfv0ee){:target="_blank"}       
   
{% include video id="NBteiaa31iI?si=rUsWraS6wQWfv0ee" provider="youtube" %}    

#### Assignments  
* <span style="color: red;"><em>Deadline to send + receive XLR Cable Coiling videos.</em></span>  
* **Finish these patches** we made in class:   
  - `05.one.zero.filter.maxpat`  
  - `05a.one.zero.test.maxpat`  
  - `06b.comb.object.maxpat`  
  - `07.moog.style.synth.maxpat`  

#### Terms, Concepts, Objects, Shortcuts   
- subtractive synthesis   
- constructive interference   
- destructive interference   
- filter sweep   
- white noise   
- pink noise   
- `<noise~>`  
- `<pink~>`  
- `<lores~>`  
- `<reson~>`  
- `<comb~>`  
- `<biquad~>`  

* * *

## Week 7: {{ site.week-07 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-07-topic }}</span>    

#### Tutorials    
* [Waveshapers: A Guide to Destructive Sound Processing and Waveform Design](https://www.perfectcircuit.com/signal/learning-synthesis-waveshapers){:target="_blank"}     

#### Downloads    
* [Wavetable Boiler Patches](https://github.com/einbahnstrasse/wavetable.boiler){:target="_blank"}     
   
#### Listening   
* [Iannis Xenakis, _Gendy3_ (1991)](https://youtu.be/5qS5lqbx9H0?si=NRvTH341rsl8bsOh){:target="_blank"}       
   
{% include video id="5qS5lqbx9H0?si=NRvTH341rsl8bsOh" provider="youtube" %}    
  
#### Assignments   
* Watch the first 23 minutes of [_RiP: A Remix Manifesto_](https://youtu.be/quO_Dzm4rnk?si=f6zYDUvr2Rwum5bZ){:target="_blank"} (Video player posted under Week 8 below). Watch more if you're interested.   
* **Finish these patches** we made in class:   
  - `03.wavetable.synth.maxpat`  
  - `04.waveshaping.maxpat`  
  - `05.waveshaping.bands.maxpat`  
  - `06.wavefolder.maxpat`  

#### Terms, Concepts, Objects, Shortcuts   
- lookup table    
- waveform cycle   
- periodicity   
- control signal   
- interpolation     
- waveshaping  
- distortion   
- transfer function   
- `<cycle~>`   
- `<phasor~>`   
- `<cos~>` 
- `<buffer~>`   
- `<waveform~>`   
- `<wave~>`   
- `<function>`  
- `<peen~>`  
- `<lookup~>`  
- `<pong~>`  

* * *

## Week 8: {{ site.week-08 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-08-topic }}</span>    

#### Tutorials  
* [_RiP: A Remix Manifesto_ (2008, 86 minutes)](https://youtu.be/quO_Dzm4rnk?si=f6zYDUvr2Rwum5bZ){:target="_blank"}       
_This is a documentary film directed by Brett Gaylor._   
_**Watch the first 23 minutes**, or more if you're interested_.   
   
{% include video id="quO_Dzm4rnk?si=f6zYDUvr2Rwum5bZ" provider="youtube" %}    

#### Listening   
* [Pierre Schaeffer, _Etude aux chemins de fer_ ("Railroad Study") (1948)](https://youtu.be/N9pOq8u6-bA?si=FDYDOKGlUPaRfke7){:target="_blank"}       
   
{% include video id="N9pOq8u6-bA?si=FDYDOKGlUPaRfke7" provider="youtube" %}    
   
* [Karlheinz Stockhausen, _Gesang der Jünglinge_ (1956)](https://youtu.be/-RMGGVlMuwo?si=iuZ8Nheg3npgGB9g){:target="_blank"}       
   
{% include video id="-RMGGVlMuwo?si=iuZ8Nheg3npgGB9g" provider="youtube" %}    

* [Horacio Vaggione, _SCHALL_ (1994)](https://youtu.be/K-FjnKiDWQc?si=oj3whzvwrBqZP0P-){:target="_blank"}       
   
{% include video id="K-FjnKiDWQc?si=oj3whzvwrBqZP0P-" provider="youtube" %}    
   
#### Assignments    
* Introduce + assign the Final Project, due in Week 15 _(A small project to be shared in class, a working patch, a small design, nothing big. Details coming soon.)_    
* **Finish these patches** we made in class:   
  - `01.tape.transformation.maxpat`  
  - `02.sampler.instrument.maxpat`  

<!-- <iframe src="https://player.vimeo.com/video/371859612?h=bb2544d760&title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>   -->

<!-- sampling -->
#### Terms, Concepts, Objects, Shortcuts   
- sample value  
- audio sample   
- appropriation   
- key mapping   
- micromontage   
- treatments   
- `<buffer~>`   
- `<groove~>`  

* * *

## Week 9: {{ site.week-09 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-09-topic }}</span>    

#### Tutorials    
* [MyMagnumOpus Boiler Patch](https://github.com/einbahnstrasse/MHL-CAO-spat-boiler){:target="_blank"}   

#### Listening   

#### Assignments   
* Start assembling your project using today's concert patch boiler!  
* **Finish these patches** we made in class:   
  - `_MAIN.PATCH.template.maxpat`  
  - `lg.ping.v02.maxpat`   
* prepare for our guest Stylianos Dimou next week _(stand by for materials to examine, which will be posted here later)_   

<!-- event mgmt -->  
#### Terms, Concepts, Objects, Shortcuts   
- event   
- main patch ("parent" patch)   
- subpatcher `<p>` 
- abstraction    
- initialization ("init")   
- rewind to event    
- `<preset>`  
- `<counter>`   

* * *

## Week 10: {{ site.week-10 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-10-topic }}</span>    

#### Tutorials  

#### Listening   

#### Assignments   
* **Finish these patches** we made in class:   
  - _Patch list coming soon!_   

<!-- interface design -->
#### Terms, Concepts, Objects, Shortcuts   
- GUI (graphical user interface)   
- performer interface    
- presentation mode     
- UI objects: buttons, toggles, dials, sliders, meters, etc.    
- `<mira.frame>`  
- `<mira.multitouch>`  
- `<mira.motion>`  
- network IP address  

* * *

## Week 11: {{ site.week-11 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-11-topic }}</span>    

#### Tutorials 
* [Interacting With `<bach.roll>` boiler patches](https://github.com/einbahnstrasse/interacting-with-bach-roll){:target="_blank"}     

#### Listening   
* [Brian Ferneyhough, _String Trio_ (1995)](https://youtu.be/zwW6hLjPiWM?si=v5WfEC3stoRJqMdp){:target="_blank"}       
   
{% include video id="zwW6hLjPiWM?si=v5WfEC3stoRJqMdp" provider="youtube" %}    

* [Jean-Claude Risset, _Huit esquisses en duo pour un pianiste_ (“Eight Duet Sketches for One Pianist”) (1989)](https://youtu.be/Tz5qqMyAg88?si=cGuLhjL0gpj-VHQf){:target="_blank"}       
   
{% include video id="Tz5qqMyAg88?si=cGuLhjL0gpj-VHQf" provider="youtube" %}    

#### Assignments   
<!-- * [Concert Patch Checkpoint](https://einbahnstrasse.github.io/MHL-Synthesis-Techniques/final-mixed-piece/#21-checkpoints){:target="_blank"}     -->
* **Finish these patches** we made in class:   
  - _Patch list coming soon!_   

<!-- cao -->
#### Terms, Concepts, Objects, Shortcuts   
- computer-assisted composition (cao)   
- generative algorithm   
- proportional notation   
- chord  
- onset  
- duration   
- velocity   
- midicents (mcents)   
- `<bach.roll>`  
- `<bach.unpack>`  
- `<bach.mc2f>`  

* * *

## Week 12: {{ site.week-12 }}   
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-12-topic }}</span>    

#### Tutorials  

#### Listening   
* [Iannis Xenakis, _Concret PH_ (1958)](https://youtu.be/S9zMaIhuMgo?si=LfMMqKln_F8cVX2j){:target="_blank"}       
   
{% include video id="S9zMaIhuMgo?si=LfMMqKln_F8cVX2j" provider="youtube" %}    

* [Barry Truax, _Riverrun_ (1986)](https://youtu.be/u81IGEFt7dM?si=PVJM0z1q6qchxsAM){:target="_blank"}       
   
{% include video id="u81IGEFt7dM?si=PVJM0z1q6qchxsAM" provider="youtube" %}    
  
#### Assignments  
* **Finish these patches** we made in class:   
  - `01.granular.sampler.instrument.maxpat`  
  - `02.munger.maxpat`  

<!-- granular -->
#### Terms, Concepts, Objects, Shortcuts   
- grain  
- microsound   
- granular synthesis   
- concatenation   
- density  
- window function  
- `<trapezoid~>`  
- `<buffer~>`  
- `<info~>`  
- `<groove~>`  
- `<munger~>`  

* * *

## Week 13: {{ site.week-13 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-13-topic }}</span>    

#### Tutorials  
* [Introduction to `<pfft~>` Boiler Patches](https://github.com/einbahnstrasse/pfft.boiler){:target="_blank"}     

#### Listening   
 
#### Assignments   
* **Finish these patches** we made in class:   
  - `01.multiband.filter.maxpat`  
  - `multiband.pfftCore.maxpat`  

<!-- realtime pfft~ -->
#### Terms, Concepts, Objects, Shortcuts   
- frequency domain  
- Fast Fourier Transform (FFT)  
- spectrogram  
- real numbers   
- FFT size  
- spectral frame size   
- hop size   
- imaginary numbers   
- multiband filter   
- `<pfft~>`  
- `<fftin~>`  
- `<fftout~>`  
- `<dspstate~>`  

* * *

## Week 14: {{ site.week-14 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-14-topic }}</span>    

#### Tutorials   
* [Charles Stankievech, _Headphones: Sound Without Space_](https://www.stankievech.net/projects/aaradio/headphones.html){:target="_blank"}     
    
#### Listening   
* Bernhard Leightner, excerpts from _Kopfräume—Headscapes_ (2003). _Listen on **headphones only**, not speakers:_   
  - [*HT_A*](https://www.stankievech.net/projects/aaradio/media/04%20HT_A.mp3){:target="_blank"}           
  - [*WLB*](https://www.stankievech.net/projects/aaradio/media/05%20WLB.mp3){:target="_blank"}                
      
#### Assignments  
* **Finish these patches** we made in class:   
  - `quad.panner.v01.maxpat`  
  - `_MAIN.PATCH.template.maxpat`  
  - `lg.spat.v01.maxpat`   
  - `lg.sound.out.v02.maxpat`   

<!-- spatial -->
#### Terms, Concepts, Objects, Shortcuts   
- spatial audio   
- surround panner  
- quadrophonic sound   
- equal power panning   
- binaural  
- sources   
- speakers   
- XYZ coordinates  
- AED coordinates (azimuth, elevation, distance)   
- `<spat5.oper~>`  
- `<spat5.spat~>`  

* * *

## Week 15: {{ site.week-15 }}   
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-15-topic }}</span>    

#### Tutorials 

#### Listening   

#### Assignments  

#### Terms, Concepts, Objects, Shortcuts   

* * *
