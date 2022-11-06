#  MIDISourceController

### ⚠️ WORK IN PROGRESS ⚠️

This repo will contain a `CoreMIDI` (source only) controller in Swift that works with `MIDIEventPacket` (32-bit UMP and MIDI 2.0 compatible). The idea is to use this controller in Swift apps to emulate controllers (specially ribbons and faders).
The scope is intended to be simple, only an output of general purpose controllers that everyone will be able to map to any parameter (providing you're able to do it, like Ableton's MIDI custom mapping).

#### References:

[CoreMIDI API](https://developer.apple.com/documentation/coremidi/)
[Panos Matsinopoulos Primitive MIDI Controller post](https://medium.com/programming-for-music/primitive-midi-controller-8f7a923d4f19)
[CircuitBread JB Magoncia's clarifications on how does a MIDI operate](https://www.circuitbread.com/tutorials/midi-controller-knobs-buttons)
[Gene de Lisa's `MIDIPacket` & `MIDIPacketList` reports](https://www.rockhoppertech.com/blog/core-midi-midipacket-midipacketlist-and-builders-2)
The [MIDI Specification](https://amei.or.jp/midistandardcommittee/MIDI2.0/MIDI2.0-DOCS/M2-104-UM_v1-0_UMP_and_MIDI_2-0_Protocol_Specification.pdf) and the [Control Change Table](https://www.midi.org/specifications-old/item/table-3-control-change-messages-data-bytes-2)
