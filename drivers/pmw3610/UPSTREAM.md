Source: https://github.com/sirocominfo/zmk-pmw3610-driver
Revision: 3aac7b28aff5afddf2a3dcffcb0b00805f7922ca

Local change: guard central-only keymap access when building a split peripheral.
The peripheral always reports MOVE events. Auto mouse and scrolling are handled
by the dongle input listener. Original copyright/license headers are retained.
