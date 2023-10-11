# Stuttterz
.lv2 plugin for Mod / double stutter effect


Max gen~ plugin compiled with Christosku docker container

BPM : obvious

DIV_L  and  DIV_R : Time division 1/4 note, 1/8 note , etc ….but also odd division 5tuplet…11tuplet which could give interesting polyrythmic effects at slow tempo

DOUBLE: when engaged, left and right are active, disengaged only DIV_L is active

ZTUTTER :  trig the stutter effect

Dry/Wet: obvious

DAMP:  at 1 infinite feedback , at less fade out

RANDOM: when engaged, random tempo/division on each trig

RANGE : random range

TAIL : add a tail when stopping stutter (artifacts with random…)

ENV : add an envelop to avoid clicks


—————————

Mod devices installation
• Copy the zwabo-stuttterz.lv2 folder to your Mod:

scp -rp <path to zwabo-stuttterz.lv2> root@192.168.51.1:/root/.lv2

• Enter password "mod"
• Reboot Mod
