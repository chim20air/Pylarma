# Pylarma
## Some simple CLI python based alarm

Dependencies:
- playsound
- pynput

***Right now is working on an Arch-based linux, further testing is needed***
For now this proyect is working as a timer. In the future this will allow to work as alarm or timer.

Example:

To set the timer to 1:30 hours using sound.wav file
```
./pylarma -ho 1 -m 30 -af sound.wav
```

### TODO list
- [ ] the script must be able to work either as an alarm or a timer
- [ ] When the space is pressed, the alarm sound must stop inmediately
- [ ] improve keylogger
- [ ] many more things
