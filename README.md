# companion-module-green-go-intercom

See HELP.md and LICENSE

# OSC messages
## Documentation
### Green-GO
https://manual.greengoconnect.com/en/glossary/?h=
### QLab 5
https://qlab.app/docs/v5/networking/network-cues/#osc-messages-without-durations
### grandMA3
https://help.malighting.com/grandMA3/latest/?p=keyword_sendosc.html
### grandMA2 (OSC_Mate)
https://www.dropbox.com/scl/fi/j2sf4egmjtg3rpf5nw63n/OSC_Mate-manual.pdf?rlkey=gfg4pdhtzrb7ybvkoq5dc0snr&dl=0
## Identify
### Device identify on
QLab 5
```
/ggo/cmd/identify 1
```
grandMA3
```
SendOSC [ID] /ggo/cmd/identify,i,1
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/identify,i,1"
```
### Device identify off
QLab 5
```
/ggo/cmd/identify 0
```
grandMA3
```
SendOSC [ID] /ggo/cmd/identify,i,0
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/identify,i,0"
```
## Call
### Send call signal
QLab 5
```
/ggo/cmd/channel/call 1 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/call,ii,1,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/call,ii,1,[chId]"
```
### Send alert call signal
QLab 5
```
/ggo/cmd/channel/call 2 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/call,ii,2,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/call,ii,2,[chId]"
```
### Stop sending call signal
QLab 5
```
/ggo/cmd/channel/call 0 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/call,ii,0,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/call,ii,0,[chId]"
```
## Cue
### Send attention signal
QLab 5
```
/ggo/cmd/channel/cue 2 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,2,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,2,[chId]"
```
### Send ready signal
QLab 5
```
/ggo/cmd/channel/cue 3 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,3,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,3,[chId]"
```
### Send go signal
QLab 5
```
/ggo/cmd/channel/cue 4 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,4,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,4,[chId]"
```
### Send hold signal
QLab 5
```
/ggo/cmd/channel/cue 5 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,5,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,5,[chId]"
```
### Stop sending cue signal
QLab 5
```
/ggo/cmd/channel/cue 0 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,0,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,0,[chId]"
```
### Stop sending cue signal (direct)
QLab 5
```
/ggo/cmd/channel/cue 1 {chId}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/channel/cue,ii,1,[chId]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/channel/cue,ii,1,[chId]"
```
