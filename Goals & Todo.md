# PROS
- Ultra low noise
- Ultra low inter-module noise
- Protection + safety features
- 3u boat compatible (not taller then 3u)
- Standard 84hp (19") and 104hp compatible (not wider then 50hp)
- Wide range of voltage input solutions
- Good heat handling/dissipation
- Good price
- Good documentation
- Readily avalible parts
- A range of PCB manufaturing options (design not totaly resticted by super thick pcb or any kind of special treatment)

# CONS
- This system uses more power in standby then a passive system  
- This system is less efficient then a passive system (duh)  
- ~~This system does not distribute CV and gate signals  

# TODO
- Power Input 15–21V (15 is best, most laptop chargers are 19V) Surge capability value?  
- Solve power input question for external power supply, TPS84259? 
- Re arrange pcb design for better spacing (Make space for heatsinks and bigger caps)  
- Move bigger caps before regulators (Smaller noise caps behind is fine)  
- Bigger caps on input rails  
- Solve magic smoke from negative input cap (16v may not be high enough on the caps, should have gone 30v+)  
- Put diodes after fuses to stop flooding on a critical fail  
- Create place for testing logs  
- Update PCB silk layer before next prototype  
- Create decision matrix on different configurations
- Test prototype in system  
- Do death test with video  
- Create clip on dc module with perf board (Test clipping strength)
– Create Eagle clip on module template. And add specs to Wiki
– Create Wiki entry on how to patch CV-GATE over busboard.
– Add graphics to board, incl. OSHW cert brand and labeling

# DONE
- first prototype built and tested  
- fix error in v4 diode protection  
- Organise Open Source Certificate

