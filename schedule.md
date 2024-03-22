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
<!-- * Review [Detailed Breakdown of Grading.](/MHL-Synthesis-Techniques/grading/){:target="_blank"}   -->

#### Listening   
<!-- * [Hugh Le Caine, _Dripsody_ (1955)](https://youtu.be/zvHSvSBwFYM?si=5ZvFFPUpYwWrJ08L){:target="_blank"}  
* [Joshua Banks Mailman‘s analysis of _Dripsody_](/MHL-studio-methods/assets/images/Mailman.Dripsody.Analysis.png){:target="_blank"}   -->

#### Tutorials     

#### Listening   

#### Downloads  
<!-- * [Interacting With `bach.roll` boiler patches](https://github.com/einbahnstrasse/interacting-with-bach-roll){:target="_blank"}      -->

#### Assignments _(always due before the next class!)_   
* Install + Authorize MaxMSP    

#### Terms, Concepts, Objects, Shortcuts   
- patch   
- object box `cmd. + n`  
- patch cable (or patch cord)   
- lock/unlock patch `cmd. + e`  
- message box `m`  
- comment box `c`  
- control rate (Max)  
- signal rate (MSP)  
- resize boxes `cmd. + j`   
- duplicate an object `option + click + drag`   
- open help file: `option + click` on any object   

* * *

## Week 2: {{ site.week-02 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-02-topic }}</span>    

#### Tutorials   

#### Listening   

#### Assignments   

#### Terms, Concepts, Objects, Shortcuts   
- oscillator   
- sine wave `<cycle~>` 
- sawtooth wave `<phasor~>` 
- triangle wave `<tri~>` 
- square wave `<rect~>`   
- duty cycle   
- filter   
- lowpass (LP) filter `<onepole~>`  
- highpass (HP) filter   
- bandpass filter `<svf~>`    

* * *

## Week 3: {{ site.week-03 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-03-topic }}</span>    

#### Tutorials   

#### Listening   

#### Assignments   

#### New Terms, Concepts, Objects, Shortcuts   
- frequency  
- amplitude   
- phase   
- additive synthesis   
- oscillator bank   
- ADSR (attack, decay, sustain, release)  
- envelope   
- fusion   
- fundamental   
- partial   
- harmonic    
- overtone   
- timbre   
- `<cycle~>`  
- `<kslider~>`  
- `<line~>`  
- `<function>`  
- `<spectroscope~>`  
- `<zmap>`  
- `<multislider>`  

* * *  

## Week 4: {{ site.week-04 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-04-topic }}</span>    

### Tutorials   

### Listening   

#### Assignments   

#### New Terms, Concepts, Objects, Shortcuts   
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

#### Listening   

#### Assignments   

#### New Terms, Concepts, Objects, Shortcuts   
- real-time synthesis   
- live input signal  
- delay line    
- flanger   
- constructive interference   
- destructive interference   
- envelope follower   
- audio buffer   
- `<tapin~>`  
- `<tapout~>`  
- `<comb~>`  
- `<peakamp~>`  

* * *   

## Week 6: {{ site.week-06 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-06-topic }}</span>    

#### Tutorials  

#### Listening   

#### Assignments  
<!-- * <span style="color: red;"><em>Deadline to send + receive XLR Cable Coiling videos.</em></span>   -->

#### New Terms, Concepts, Objects, Shortcuts   
- subtractive synthesis   
- filter sweep   
- resonant bandpass filter   
- white noise   
- pink noise   
- filter bank   
- source-filter model   
- `<noise~>`  
- `<pink~>`  
- `<lores~>`  
- `<reson~>`  
- `<comb~>`  
- `<biquad~>`  
- `<resonators~>`  

* * *

## Week 7: {{ site.week-07 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-07-topic }}</span>    

#### Tutorials    
<!-- * [Introduction to <pfft~> Boiler Patches](https://github.com/einbahnstrasse/week.7.boiler.pfft/){:target="_blank"}      -->

#### Listening   

#### Assignments   

#### New Terms, Concepts, Objects, Shortcuts   
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

#### Listening   


#### Assignments      

<!-- <iframe src="https://player.vimeo.com/video/371859612?h=bb2544d760&title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>   -->

<!-- sampling -->
#### New Terms, Concepts, Objects, Shortcuts   
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

### Listening   

#### Assignments   
<!-- * Start assembling and formatting your piece using today's concert patch template!   -->

<!-- event mgmt -->
#### New Terms, Concepts, Objects, Shortcuts   
- event   
- main patch ("parent" patch)   
- subpatcher `p` 
- abstraction    
- initialization ("init")   
- rewind to event    
- `preset`  
- `counter`   

* * *

## Week 10: {{ site.week-10 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-10-topic }}</span>    

#### Tutorials  

### Listening   

#### Assignments   

<!-- interface design -->
#### New Terms, Concepts, Objects, Shortcuts   
- GUI (graphical user interface)   
- performer interface      
- UI objects: buttons, toggles, dials, sliders, meters, etc.    
- `<mira.frame>`  
- `<mira.multitouch>`  
- `<mira.motion>`  
- network IP address  

* * *

## Week 11: {{ site.week-11 }}  
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-11-topic }}</span>    

### Tutorials 

### Listening   

### Assignments   
<!-- * [Concert Patch Checkpoint](https://einbahnstrasse.github.io/MHL-Synthesis-Techniques/final-mixed-piece/#21-checkpoints){:target="_blank"}     -->

<!-- cao -->
#### New Terms, Concepts, Objects, Shortcuts   
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

#### Assignments  

<!-- granular -->
#### New Terms, Concepts, Objects, Shortcuts   
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

### Listening   

#### Assignments   

<!-- realtime pfft~ -->
#### New Terms, Concepts, Objects, Shortcuts   
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

### Listening   

### Assignments  

<!-- spatial -->
#### New Terms, Concepts, Objects, Shortcuts   
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

### Listening   

#### Assignments  

#### New Terms, Concepts, Objects, Shortcuts   

* * *
<!-- 
## Week 16: {{ site.week-15 }}   
### {{ site.week-16-topic }}    

#### Tutorials 

### Listening   
* John Chowning, **_Stria_** (1977)   

{% include video id="fTU1v0bPRE4" provider="youtube" %}    

#### Assignments  

* * *  

## Week 17: {{ site.week-15 }}   
### {{ site.week-17-topic }}    

#### Tutorials 

### Listening   
* John Chowning, **_Stria_** (1977)   

{% include video id="fTU1v0bPRE4" provider="youtube" %}    

#### Assignments  

* * *   -->