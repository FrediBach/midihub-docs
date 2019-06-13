# USB Output

The exit point of MIDI data. The data that reaches this pipe will be sent through the MIDI OUT connector with the matching letter. See [The USB MIDI Port Mapping](the_usb_midi_port_mapping) for OS device mapping to USB port letter used by the device.

The first 4 USB MIDI ports on the computer map to A, B, C, D letters. The 5th USB MIDI port is reserved for Editor communication and shouldn't be used.

| Parameter | Description                    |
| --------- | ------------------------------ |
| Bypass    | Whether processing is enabled. Prefer bypassing Input pipes. |
| Destination | The destination of MIDI data. |

[List of Pipes](index.md#the-list-of-pipes)