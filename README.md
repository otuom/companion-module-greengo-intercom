# companion-module-green-go-intercom

See HELP.md and LICENSE

# OSC messages
## Documentation
### Green-GO
https://manual.greengoconnect.com/en/software/properties/channels/
### QLab 5
https://qlab.app/docs/v5/networking/network-cues/#osc-messages-without-durations
### grandMA3
https://help.malighting.com/grandMA3/latest/?p=keyword_sendosc.html
### grandMA2 (OSC_Mate)
https://www.dropbox.com/scl/fi/j2sf4egmjtg3rpf5nw63n/OSC_Mate-manual.pdf?rlkey=gfg4pdhtzrb7ybvkoq5dc0snr&dl=0
## Identify device
QLab 5
```
/ggo/cmd/identify {boolean}
```
grandMA3
```
SendOSC [ID] /ggo/cmd/identify,i,[boolean]
```
grandMA2 (OSC_Mate)
```
Plugin OSC_Mate "/ggo/cmd/identify,i,[boolean]"
```
## Call
### Enable call
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
### Enable Alert call
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
### Disable call
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
### Attention
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
### Ready
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
### Go
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
### Hold
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
### Disable
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
### Disable (direct)
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
