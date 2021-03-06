## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=False, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadISIGHistory', page=16, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140501_225820-pg-16-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 904L,
           'packets.transmit': 939L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 1297L,
         'packets.transmit': 1297L}}
```
```
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadISIGHistory'> {'page': 16}
response: ReadISIGHistory:size[2048]:[page][0]:data[2048]:
hexdump:
```python
0000   0x40 0x17 0x67 0x17 0x5c 0x17 0x27 0x17    @.g.\.'.
0008   0x22 0x00 0xee 0x16 0x22 0x00 0xbe 0x16    "..."...
0010   0x22 0x00 0xab 0x16 0x22 0x00 0xa2 0x16    "..."...
0018   0x22 0x00 0x86 0x16 0x56 0x16 0x06 0x16    "...V...
0020   0xc8 0x15 0xbb 0x15 0x4a 0x16 0xfe 0x16    ....J...
0028   0xda 0x16 0xa2 0x16 0x47 0x16 0x0f 0x16    ....G...
0030   0xa6 0x15 0x9a 0x15 0x62 0x15 0xc5 0x14    ....b...
0038   0xe4 0x13 0x97 0x13 0x5e 0x13 0xf2 0x12    ....^...
0040   0x22 0x00 0x64 0x12 0x22 0x00 0xbe 0x11    ".d."...
0048   0x16 0x11 0x05 0x11 0x63 0x10 0x17 0x0f    ....c...
0050   0x76 0x0d 0xa9 0x0b 0x22 0x00 0x22 0x00    v...".".
0058   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0060   0xbd 0x0a 0x9a 0x0a 0xef 0x0a 0x22 0x00    ......".
0068   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0070   0x22 0x00 0x0f 0x00 0xf3 0x0a 0xb2 0x0a    ".......
0078   0xe9 0x09 0xee 0x09 0x6c 0x0b 0x81 0x0c    ....l...
0080   0x22 0x0c 0x9b 0x0b 0xc2 0x0a 0x9e 0x09    ".......
0088   0x5d 0x09 0xce 0x09 0x1c 0x0b 0x18 0x0c    ].......
0090   0xd3 0x0c 0xc3 0x0b 0xa5 0x0b 0x55 0x0c    ......U.
0098   0x5f 0x0c 0x1a 0x0b 0x2c 0x0a 0x00 0x0a    _...,...
00A0   0x22 0x0b 0xeb 0x0c 0x07 0x0d 0xc8 0x0c    ".......
00A8   0x92 0x0c 0xc7 0x0d 0x00 0x0e 0x22 0x00    ......".
00B0   0xbe 0x0d 0x44 0x0d 0x89 0x0c 0x1d 0x0c    ..D.....
00B8   0x0c 0x0c 0x08 0x0c 0x39 0x0b 0x85 0x0a    ....9...
00C0   0xb1 0x09 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
00C8   0x22 0x00 0x22 0x00 0x0e 0x00 0x81 0x08    ".".....
00D0   0x95 0x08 0xb4 0x09 0x22 0x00 0x22 0x00    ....".".
00D8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
00E0   0x0f 0x00 0xa5 0x09 0x8e 0x09 0x72 0x09    ......r.
00E8   0xff 0x08 0x3c 0x09 0x1b 0x0a 0x22 0x00    ..<...".
00F0   0x51 0x0a 0x22 0x00 0x4d 0x0a 0x22 0x00    Q.".M.".
00F8   0x5f 0x0a 0x22 0x00 0x93 0x09 0x22 0x00    _."...".
0100   0x45 0x09 0x22 0x00 0x52 0x0a 0x22 0x00    E.".R.".
0108   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...
0110   0x22 0x00 0x0b 0x0a 0x22 0x00 0x99 0x09    "..."...
0118   0x0c 0x08 0x60 0x07 0xaa 0x06 0x14 0x06    ..`.....
0120   0xa3 0x06 0x07 0x07 0xa0 0x06 0x3a 0x06    ......:.
0128   0xea 0x06 0xf5 0x06 0xa7 0x06 0x21 0x07    ......!.
0130   0xe4 0x07 0xdc 0x06 0xcd 0x05 0x2f 0x07    ....../.
0138   0xfc 0x06 0x44 0x07 0x25 0x07 0xf2 0x06    ..D.%...
0140   0xf0 0x06 0xeb 0x06 0xa7 0x06 0x86 0x06    ........
0148   0x27 0x06 0x79 0x05 0x6e 0x05 0xe6 0x05    '.y.n...
0150   0xd8 0x06 0x2d 0x08 0x3a 0x09 0xc8 0x09    ..-.:...
0158   0xec 0x09 0x13 0x0b 0x9d 0x0b 0xa6 0x0b    ........
0160   0x5a 0x0c 0x4d 0x0c 0xf8 0x0c 0x6f 0x0d    Z.M...o.
0168   0x05 0x0c 0x76 0x0b 0x93 0x0b 0x25 0x0b    ..v...%.
0170   0x27 0x0b 0x95 0x0a 0x90 0x0a 0xf2 0x0b    '.......
0178   0x57 0x0b 0x1b 0x0b 0x68 0x0a 0x61 0x0a    W...h.a.
0180   0x89 0x09 0xda 0x07 0x6e 0x07 0x39 0x07    ....n.9.
0188   0x98 0x07 0x64 0x08 0x10 0x0a 0x9b 0x0a    ..d.....
0190   0xb5 0x0a 0x1d 0x0a 0xe7 0x09 0x3f 0x0a    ......?.
0198   0x9b 0x0d 0x87 0x0e 0x65 0x0f 0x81 0x10    ....e...
01A0   0x37 0x10 0x22 0x00 0xac 0x0f 0x20 0x0f    7."... .
01A8   0xe7 0x0f 0x22 0x00 0x7c 0x0f 0x22 0x00    ..".|.".
01B0   0xad 0x0e 0x22 0x00 0x76 0x0c 0x22 0x00    ..".v.".
01B8   0x3e 0x0c 0x22 0x00 0x23 0x0c 0x89 0x0b    >.".#...
01C0   0x22 0x00 0x3f 0x0b 0x22 0x00 0x12 0x0a    ".?."...
01C8   0x5b 0x09 0x47 0x09 0x80 0x08 0x03 0x09    [.G.....
01D0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
01D8   0x22 0x00 0x0e 0x00 0x1d 0x0a 0xd6 0x09    ".......
01E0   0x72 0x0a 0x22 0x00 0x22 0x00 0x22 0x00    r.".".".
01E8   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...
01F0   0x36 0x09 0x29 0x07 0x11 0x07 0xae 0x06    6.).....
01F8   0x05 0x08 0xc9 0x07 0x23 0x07 0x56 0x07    ....#.V.
0200   0x5b 0x07 0x88 0x07 0x68 0x07 0xa8 0x06    [...h...
0208   0x17 0x06 0x71 0x06 0x95 0x06 0xbb 0x06    ..q.....
0210   0x59 0x07 0xee 0x07 0x80 0x08 0xef 0x08    Y.......
0218   0xd1 0x08 0xc0 0x09 0xc5 0x0a 0xe8 0x0b    ........
0220   0xe2 0x0b 0xf7 0x0b 0x86 0x0d 0x0f 0x0f    ........
0228   0x81 0x0f 0xe2 0x0f 0x22 0x00 0x45 0x0f    ....".E.
0230   0x1b 0x0f 0x87 0x11 0x6e 0x11 0x3a 0x11    ....n.:.
0238   0x37 0x11 0x3b 0x11 0x22 0x00 0x22 0x00    7.;.".".
0240   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0248   0x0a 0x11 0xd5 0x0f 0x23 0x0f 0x18 0x0f    ....#...
0250   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0258   0x22 0x00 0x22 0x00 0x0f 0x00 0x71 0x0f    "."...q.
0260   0xc0 0x0f 0xc6 0x0f 0xa2 0x0f 0x52 0x0f    ......R.
0268   0xe5 0x0e 0xc6 0x0e 0x99 0x0e 0x4e 0x0e    ......N.
0270   0xe7 0x0d 0x7a 0x0d 0x33 0x0d 0x1c 0x0d    ..z.3...
0278   0xd7 0x0c 0x60 0x0c 0xde 0x0b 0x69 0x0b    ..`...i.
0280   0xef 0x0a 0x65 0x0a 0xf9 0x09 0x9b 0x09    ..e.....
0288   0x41 0x09 0xe6 0x08 0x7f 0x08 0x48 0x08    A.....H.
0290   0x2d 0x08 0x19 0x08 0xfe 0x07 0xe4 0x07    -.......
0298   0xd5 0x07 0xc2 0x07 0xa7 0x07 0x91 0x07    ........
02A0   0x8f 0x07 0xc3 0x07 0xdd 0x07 0xc9 0x07    ........
02A8   0xb3 0x07 0xa0 0x07 0x93 0x07 0x7e 0x07    ......~.
02B0   0x5d 0x07 0x45 0x07 0x22 0x00 0x2c 0x07    ].E.".,.
02B8   0x22 0x00 0xe1 0x06 0x83 0x06 0x4b 0x06    ".....K.
02C0   0x2d 0x06 0x5a 0x06 0x79 0x06 0x65 0x06    -.Z.y.e.
02C8   0x2c 0x06 0xeb 0x05 0xc3 0x05 0x9e 0x05    ,.......
02D0   0x7a 0x05 0x5e 0x05 0x8f 0x05 0xac 0x05    z.^.....
02D8   0x9e 0x05 0x67 0x05 0x22 0x05 0xfc 0x04    ..g."...
02E0   0xea 0x04 0x2c 0x05 0x87 0x05 0x94 0x05    ..,.....
02E8   0x9d 0x05 0x92 0x05 0x89 0x05 0x22 0x00    ......".
02F0   0x35 0x05 0x22 0x00 0xaa 0x04 0x51 0x04    5."...Q.
02F8   0x1d 0x04 0x10 0x04 0x04 0x04 0xed 0x03    ........
0300   0xce 0x03 0xc5 0x03 0xed 0x03 0x4c 0x04    ......L.
0308   0xaa 0x04 0x82 0x05 0x44 0x06 0x62 0x07    ....D.b.
0310   0x08 0x09 0x76 0x09 0xcf 0x09 0x2a 0x0a    ..v...*.
0318   0x22 0x00 0xc1 0x0a 0x22 0x00 0x71 0x0b    "...".q.
0320   0x22 0x00 0xdd 0x0b 0x22 0x00 0x33 0x0c    "...".3.
0328   0x22 0x00 0x8c 0x0c 0x22 0x00 0xe7 0x0c    "..."...
0330   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0338   0x08 0x00 0x22 0x00 0x49 0x0d 0x2b 0x0d    ..".I.+.
0340   0x71 0x0c 0x7b 0x0c 0x13 0x0d 0x38 0x0d    q.{...8.
0348   0x8b 0x0a 0x23 0x09 0x2e 0x0b 0x42 0x0b    ..#...B.
0350   0xe8 0x0a 0x7b 0x09 0x4e 0x0a 0xf8 0x08    ..{.N...
0358   0x6b 0x08 0xa4 0x09 0x71 0x0a 0x6f 0x09    k...q.o.
0360   0x50 0x09 0x84 0x09 0xf6 0x08 0xba 0x08    P.......
0368   0x3b 0x08 0x85 0x07 0xe5 0x07 0x07 0x08    ;.......
0370   0xdf 0x07 0xc8 0x07 0xde 0x07 0xc0 0x07    ........
0378   0xff 0x07 0x3f 0x08 0x5d 0x08 0x8a 0x08    ..?.]...
0380   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0388   0x22 0x00 0x0e 0x00 0x22 0x00 0x22 0x00    "...".".
0390   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0398   0x47 0x08 0x0b 0x08 0x7e 0x08 0x22 0x00    G...~.".
03A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
03A8   0x22 0x00 0x0f 0x00 0xc2 0x08 0x84 0x08    ".......
03B0   0x32 0x08 0x44 0x08 0x45 0x08 0x35 0x08    2.D.E.5.
03B8   0x34 0x08 0xb0 0x07 0x2f 0x08 0x2a 0x08    4.../.*.
03C0   0x86 0x07 0x11 0x07 0xdf 0x06 0xc7 0x06    ........
03C8   0x8f 0x06 0x36 0x06 0xe9 0x05 0xff 0x05    ..6.....
03D0   0xc8 0x05 0x05 0x06 0x79 0x06 0x04 0x07    ....y...
03D8   0xaa 0x07 0xc5 0x07 0x86 0x07 0xfa 0x07    ........
03E0   0xe3 0x07 0x07 0x08 0x25 0x08 0x2e 0x08    ....%...
03E8   0xca 0x08 0x1a 0x09 0xec 0x08 0xc8 0x08    ........
03F0   0xa0 0x08 0xc0 0x08 0x18 0x08 0xc4 0x07    ........
03F8   0xb0 0x07 0xd7 0x07 0x02 0x08 0xfd 0x07    ........
0400   0x90 0x07 0xb9 0x07 0x7f 0x08 0x0a 0x09    ........
0408   0x8b 0x09 0x2e 0x0a 0xe1 0x0a 0xe2 0x0a    ........
0410   0x86 0x0a 0x45 0x0a 0x3d 0x0a 0x8e 0x09    ..E.=...
0418   0x35 0x09 0x77 0x08 0x0e 0x08 0xa1 0x07    5.w.....
0420   0x52 0x07 0x48 0x07 0x3c 0x07 0x24 0x07    R.H.<.$.
0428   0xf4 0x06 0x4b 0x07 0x02 0x07 0x39 0x06    ..K...9.
0430   0x08 0x06 0xe1 0x05 0xbe 0x05 0x3e 0x05    ......>.
0438   0x38 0x05 0x8f 0x05 0x1d 0x06 0xfc 0x05    8.......
0440   0x22 0x00 0x7f 0x05 0x4b 0x05 0x46 0x05    "...K.F.
0448   0x8b 0x05 0x76 0x05 0xae 0x05 0x0e 0x06    ..v.....
0450   0x74 0x06 0xf7 0x06 0xd5 0x06 0x8c 0x06    t.......
0458   0x9b 0x06 0x6d 0x06 0x3b 0x06 0x05 0x06    ..m.;...
0460   0x58 0x06 0x9d 0x06 0x88 0x06 0x62 0x06    X.....b.
0468   0xdb 0x05 0x81 0x05 0x10 0x05 0x8b 0x04    ........
0470   0x95 0x04 0xe7 0x04 0x10 0x05 0xae 0x04    ........
0478   0x2d 0x04 0xf3 0x03 0x22 0x00 0xee 0x03    -..."...
0480   0x41 0x04 0xa1 0x04 0x22 0x05 0xf3 0x04    A..."...
0488   0x7c 0x04 0x95 0x04 0xa9 0x04 0x1f 0x05    |.......
0490   0x22 0x00 0x40 0x05 0x22 0x00 0xd3 0x04    ".@."...
0498   0x8b 0x04 0x28 0x04 0xce 0x03 0x22 0x00    ..(...".
04A0   0xc8 0x03 0x4e 0x04 0xc0 0x04 0xa1 0x04    ..N.....
04A8   0x2e 0x04 0x6e 0x04 0xa2 0x04 0x70 0x05    ..n...p.
04B0   0xe3 0x05 0x22 0x06 0x22 0x06 0xdd 0x05    .."."...
04B8   0xef 0x05 0xe2 0x05 0x07 0x06 0xde 0x06    ........
04C0   0xb6 0x06 0x13 0x07 0x85 0x07 0x05 0x08    ........
04C8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
04D0   0x22 0x00 0x0e 0x00 0x89 0x08 0x21 0x08    ".....!.
04D8   0x6e 0x07 0x53 0x07 0x22 0x00 0x22 0x00    n.S.".".
04E0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
04E8   0x0f 0x00 0x85 0x08 0x67 0x08 0x74 0x08    ....g.t.
04F0   0x1c 0x09 0xfc 0x08 0x17 0x08 0x2e 0x08    ........
04F8   0xfc 0x07 0xdc 0x07 0xce 0x07 0xbe 0x07    ........
0500   0x74 0x06 0x49 0x07 0x7c 0x08 0xf6 0x08    t.I.|...
0508   0xe0 0x08 0xa2 0x08 0xfb 0x08 0x6b 0x09    ......k.
0510   0xe6 0x09 0x65 0x0a 0xcf 0x0a 0x04 0x0b    ..e.....
0518   0xfa 0x0a 0x27 0x0b 0xef 0x0a 0x1c 0x0a    ..'.....
0520   0xa7 0x09 0x81 0x09 0x4b 0x09 0x48 0x09    ....K.H.
0528   0x27 0x09 0xfc 0x09 0xae 0x0a 0x0d 0x0a    '.......
0530   0xfc 0x09 0xff 0x09 0xed 0x09 0x3a 0x0a    ......:.
0538   0x01 0x0b 0x6c 0x0b 0x70 0x0b 0x4a 0x0b    ..l.p.J.
0540   0x7a 0x0b 0xb7 0x0b 0xc0 0x0b 0xc9 0x0b    z.......
0548   0xc8 0x0b 0xc0 0x0b 0x9a 0x0b 0xea 0x0a    ........
0550   0xf6 0x09 0xc6 0x09 0x80 0x09 0xfe 0x08    ........
0558   0x50 0x08 0x25 0x08 0x12 0x08 0xf0 0x07    P.%.....
0560   0x99 0x07 0x31 0x07 0xe4 0x06 0xbe 0x06    ..1.....
0568   0xab 0x06 0x81 0x06 0x64 0x06 0xe8 0x07    ....d...
0570   0x82 0x09 0xd1 0x09 0xc9 0x09 0xa8 0x09    ........
0578   0x6c 0x09 0x2c 0x09 0x01 0x09 0xec 0x08    l.,.....
0580   0x10 0x09 0x59 0x09 0x6e 0x09 0x22 0x00    ..Y.n.".
0588   0x22 0x09 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0590   0x22 0x00 0x08 0x00 0x22 0x00 0x22 0x00    "...".".
0598   0x22 0x00 0x22 0x00 0x0b 0x00 0x22 0x00    "."...".
05A0   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...
05A8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
05B0   0x0d 0x00 0x22 0x00 0x00 0x00 0x22 0x00    .."...".
05B8   0x00 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
05C0   0x22 0x00 0x08 0x00 0x22 0x00 0x16 0x01    "..."...
05C8   0x22 0x00 0x58 0x09 0x22 0x00 0x5a 0x0d    ".X.".Z.
05D0   0x22 0x00 0x30 0x11 0x22 0x00 0x2a 0x12    ".0.".*.
05D8   0x22 0x00 0x22 0x12 0x22 0x00 0x36 0x12    ".".".6.
05E0   0x22 0x00 0x00 0x11 0x22 0x00 0x44 0x11    "...".D.
05E8   0x22 0x00 0x9c 0x12 0x22 0x00 0x40 0x13    "...".@.
05F0   0x22 0x00 0x1a 0x13 0x22 0x00 0x9c 0x12    "..."...
05F8   0x22 0x00 0x7e 0x12 0x22 0x00 0x22 0x13    ".~.".".
0600   0x22 0x00 0xae 0x13 0x22 0x00 0x0e 0x13    "..."...
0608   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0610   0x22 0x00 0x0e 0x00 0x22 0x00 0x4c 0x12    "...".L.
0618   0x22 0x00 0x2a 0x12 0xca 0x11 0x22 0x00    ".*...".
0620   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0628   0x22 0x00 0x0f 0x00 0x62 0x11 0x06 0x11    "...b...
0630   0x7f 0x10 0xde 0x0f 0xf0 0x0e 0x29 0x0e    ......).
0638   0x6f 0x0d 0x93 0x0c 0xba 0x0b 0x30 0x0b    o.....0.
0640   0xcd 0x0a 0x4b 0x0a 0x00 0x0a 0x14 0x09    ..K.....
0648   0xd5 0x07 0xe1 0x06 0x09 0x06 0x73 0x05    ......s.
0650   0x9b 0x05 0x3e 0x05 0x4c 0x05 0xa6 0x05    ..>.L...
0658   0xe5 0x05 0x04 0x06 0xe9 0x05 0x93 0x05    ........
0660   0x49 0x05 0x2e 0x05 0xd0 0x04 0x7d 0x04    I.....}.
0668   0x55 0x04 0x38 0x04 0x1e 0x04 0x0a 0x04    U.8.....
0670   0x05 0x04 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
0678   0x22 0x00 0x22 0x00 0x0e 0x00 0xb1 0x04    ".".....
0680   0xe4 0x04 0x22 0x00 0xec 0x04 0xb1 0x05    ..".....
0688   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0690   0x22 0x00 0x22 0x00 0x0f 0x00 0x1b 0x06    ".".....
0698   0xdb 0x05 0x56 0x05 0x76 0x05 0xb1 0x05    ..V.v...
06A0   0xe1 0x05 0xa7 0x05 0x59 0x05 0x63 0x05    ....Y.c.
06A8   0x56 0x05 0x22 0x05 0x02 0x05 0x3c 0x05    V."...<.
06B0   0x22 0x00 0x89 0x05 0xdb 0x05 0x34 0x06    ".....4.
06B8   0xdc 0x06 0xf4 0x06 0xf0 0x06 0x3e 0x07    ......>.
06C0   0x24 0x08 0x99 0x08 0x1e 0x09 0xda 0x09    $.......
06C8   0x16 0x0a 0x47 0x0a 0x1f 0x0a 0xba 0x09    ..G.....
06D0   0x7c 0x09 0x42 0x09 0x34 0x09 0x1c 0x09    |.B.4...
06D8   0x3e 0x09 0x63 0x09 0x9a 0x09 0x33 0x0a    >.c...3.
06E0   0x22 0x0b 0x2b 0x0b 0x0c 0x0b 0xb8 0x0a    ".+.....
06E8   0x7f 0x0a 0xa2 0x0a 0x00 0x0b 0x80 0x0b    ........
06F0   0x9c 0x0b 0xe7 0x0b 0xf7 0x0b 0x01 0x0c    ........
06F8   0xfc 0x0b 0x8c 0x0c 0x4f 0x0d 0x7b 0x0d    ....O.{.
0700   0x98 0x0d 0x85 0x0d 0x7e 0x0d 0xb9 0x0d    ....~...
0708   0xb0 0x0d 0x87 0x0d 0x43 0x0d 0xd0 0x0c    ....C...
0710   0x9f 0x0c 0x77 0x0c 0x29 0x0c 0x78 0x0b    ..w.).x.
0718   0xca 0x0a 0x34 0x0a 0xbb 0x09 0x72 0x09    ..4...r.
0720   0x34 0x09 0x0a 0x09 0x10 0x09 0x12 0x09    4.......
0728   0xe6 0x08 0xc2 0x08 0xb1 0x08 0xaa 0x08    ........
0730   0xff 0x08 0xbe 0x09 0x73 0x09 0xe6 0x08    ....s...
0738   0x22 0x00 0xa5 0x08 0xb1 0x08 0x22 0x00    ".....".
0740   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...
0748   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0750   0x0c 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".
0758   0x22 0x00 0x0c 0x00 0xf8 0x08 0x59 0x09    ".....Y.
0760   0xaa 0x09 0x65 0x09 0x22 0x00 0x22 0x00    ..e.".".
0768   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...
0770   0x1b 0x09 0x03 0x09 0x05 0x09 0x09 0x09    ........
0778   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
0780   0x22 0x00 0x22 0x00 0x0f 0x00 0x69 0x08    "."...i.
0788   0x33 0x08 0x22 0x00 0x64 0x08 0x66 0x08    3.".d.f.
0790   0x7a 0x08 0x14 0x09 0x92 0x09 0x05 0x09    z.......
0798   0x54 0x08 0xcc 0x07 0x3b 0x07 0x22 0x00    T...;.".
07A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
07A8   0x0e 0x00 0xc5 0x06 0x69 0x06 0x73 0x06    ....i.s.
07B0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".
07B8   0x22 0x00 0x22 0x00 0x0f 0x00 0x90 0x06    ".".....
07C0   0x13 0x06 0xeb 0x05 0x3b 0x06 0x21 0x07    ....;.!.
07C8   0x71 0x07 0xe1 0x07 0xb1 0x08 0x34 0x09    q.....4.
07D0   0x26 0x09 0xa2 0x08 0x01 0x09 0x1e 0x09    &.......
07D8   0xd8 0x08 0x22 0x00 0xe5 0x08 0x22 0x00    .."...".
07E0   0x02 0x09 0x22 0x00 0xea 0x08 0x22 0x00    .."...".
07E8   0x1f 0x09 0x77 0x09 0x22 0x00 0x55 0x09    ..w.".U.
07F0   0x3e 0x09 0x22 0x00 0x22 0x00 0x22 0x00    >.".".".
07F8   0x22 0x00 0x08 0x00 0x93 0x00 0xf7 0x00    ".......
```
#### decoded:
```python
'0000   0x40 0x17 0x67 0x17 0x5c 0x17 0x27 0x17    @.g.\\.\'.\n0008   0x22 0x00 0xee 0x16 0x22 0x00 0xbe 0x16    "..."...\n0010   0x22 0x00 0xab 0x16 0x22 0x00 0xa2 0x16    "..."...\n0018   0x22 0x00 0x86 0x16 0x56 0x16 0x06 0x16    "...V...\n0020   0xc8 0x15 0xbb 0x15 0x4a 0x16 0xfe 0x16    ....J...\n0028   0xda 0x16 0xa2 0x16 0x47 0x16 0x0f 0x16    ....G...\n0030   0xa6 0x15 0x9a 0x15 0x62 0x15 0xc5 0x14    ....b...\n0038   0xe4 0x13 0x97 0x13 0x5e 0x13 0xf2 0x12    ....^...\n0040   0x22 0x00 0x64 0x12 0x22 0x00 0xbe 0x11    ".d."...\n0048   0x16 0x11 0x05 0x11 0x63 0x10 0x17 0x0f    ....c...\n0050   0x76 0x0d 0xa9 0x0b 0x22 0x00 0x22 0x00    v...".".\n0058   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0060   0xbd 0x0a 0x9a 0x0a 0xef 0x0a 0x22 0x00    ......".\n0068   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0070   0x22 0x00 0x0f 0x00 0xf3 0x0a 0xb2 0x0a    ".......\n0078   0xe9 0x09 0xee 0x09 0x6c 0x0b 0x81 0x0c    ....l...\n0080   0x22 0x0c 0x9b 0x0b 0xc2 0x0a 0x9e 0x09    ".......\n0088   0x5d 0x09 0xce 0x09 0x1c 0x0b 0x18 0x0c    ].......\n0090   0xd3 0x0c 0xc3 0x0b 0xa5 0x0b 0x55 0x0c    ......U.\n0098   0x5f 0x0c 0x1a 0x0b 0x2c 0x0a 0x00 0x0a    _...,...\n00A0   0x22 0x0b 0xeb 0x0c 0x07 0x0d 0xc8 0x0c    ".......\n00A8   0x92 0x0c 0xc7 0x0d 0x00 0x0e 0x22 0x00    ......".\n00B0   0xbe 0x0d 0x44 0x0d 0x89 0x0c 0x1d 0x0c    ..D.....\n00B8   0x0c 0x0c 0x08 0x0c 0x39 0x0b 0x85 0x0a    ....9...\n00C0   0xb1 0x09 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n00C8   0x22 0x00 0x22 0x00 0x0e 0x00 0x81 0x08    ".".....\n00D0   0x95 0x08 0xb4 0x09 0x22 0x00 0x22 0x00    ....".".\n00D8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n00E0   0x0f 0x00 0xa5 0x09 0x8e 0x09 0x72 0x09    ......r.\n00E8   0xff 0x08 0x3c 0x09 0x1b 0x0a 0x22 0x00    ..<...".\n00F0   0x51 0x0a 0x22 0x00 0x4d 0x0a 0x22 0x00    Q.".M.".\n00F8   0x5f 0x0a 0x22 0x00 0x93 0x09 0x22 0x00    _."...".\n0100   0x45 0x09 0x22 0x00 0x52 0x0a 0x22 0x00    E.".R.".\n0108   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...\n0110   0x22 0x00 0x0b 0x0a 0x22 0x00 0x99 0x09    "..."...\n0118   0x0c 0x08 0x60 0x07 0xaa 0x06 0x14 0x06    ..`.....\n0120   0xa3 0x06 0x07 0x07 0xa0 0x06 0x3a 0x06    ......:.\n0128   0xea 0x06 0xf5 0x06 0xa7 0x06 0x21 0x07    ......!.\n0130   0xe4 0x07 0xdc 0x06 0xcd 0x05 0x2f 0x07    ....../.\n0138   0xfc 0x06 0x44 0x07 0x25 0x07 0xf2 0x06    ..D.%...\n0140   0xf0 0x06 0xeb 0x06 0xa7 0x06 0x86 0x06    ........\n0148   0x27 0x06 0x79 0x05 0x6e 0x05 0xe6 0x05    \'.y.n...\n0150   0xd8 0x06 0x2d 0x08 0x3a 0x09 0xc8 0x09    ..-.:...\n0158   0xec 0x09 0x13 0x0b 0x9d 0x0b 0xa6 0x0b    ........\n0160   0x5a 0x0c 0x4d 0x0c 0xf8 0x0c 0x6f 0x0d    Z.M...o.\n0168   0x05 0x0c 0x76 0x0b 0x93 0x0b 0x25 0x0b    ..v...%.\n0170   0x27 0x0b 0x95 0x0a 0x90 0x0a 0xf2 0x0b    \'.......\n0178   0x57 0x0b 0x1b 0x0b 0x68 0x0a 0x61 0x0a    W...h.a.\n0180   0x89 0x09 0xda 0x07 0x6e 0x07 0x39 0x07    ....n.9.\n0188   0x98 0x07 0x64 0x08 0x10 0x0a 0x9b 0x0a    ..d.....\n0190   0xb5 0x0a 0x1d 0x0a 0xe7 0x09 0x3f 0x0a    ......?.\n0198   0x9b 0x0d 0x87 0x0e 0x65 0x0f 0x81 0x10    ....e...\n01A0   0x37 0x10 0x22 0x00 0xac 0x0f 0x20 0x0f    7."... .\n01A8   0xe7 0x0f 0x22 0x00 0x7c 0x0f 0x22 0x00    ..".|.".\n01B0   0xad 0x0e 0x22 0x00 0x76 0x0c 0x22 0x00    ..".v.".\n01B8   0x3e 0x0c 0x22 0x00 0x23 0x0c 0x89 0x0b    >.".#...\n01C0   0x22 0x00 0x3f 0x0b 0x22 0x00 0x12 0x0a    ".?."...\n01C8   0x5b 0x09 0x47 0x09 0x80 0x08 0x03 0x09    [.G.....\n01D0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n01D8   0x22 0x00 0x0e 0x00 0x1d 0x0a 0xd6 0x09    ".......\n01E0   0x72 0x0a 0x22 0x00 0x22 0x00 0x22 0x00    r.".".".\n01E8   0x22 0x00 0x22 0x00 0x22 0x00 0x0f 0x00    "."."...\n01F0   0x36 0x09 0x29 0x07 0x11 0x07 0xae 0x06    6.).....\n01F8   0x05 0x08 0xc9 0x07 0x23 0x07 0x56 0x07    ....#.V.\n0200   0x5b 0x07 0x88 0x07 0x68 0x07 0xa8 0x06    [...h...\n0208   0x17 0x06 0x71 0x06 0x95 0x06 0xbb 0x06    ..q.....\n0210   0x59 0x07 0xee 0x07 0x80 0x08 0xef 0x08    Y.......\n0218   0xd1 0x08 0xc0 0x09 0xc5 0x0a 0xe8 0x0b    ........\n0220   0xe2 0x0b 0xf7 0x0b 0x86 0x0d 0x0f 0x0f    ........\n0228   0x81 0x0f 0xe2 0x0f 0x22 0x00 0x45 0x0f    ....".E.\n0230   0x1b 0x0f 0x87 0x11 0x6e 0x11 0x3a 0x11    ....n.:.\n0238   0x37 0x11 0x3b 0x11 0x22 0x00 0x22 0x00    7.;.".".\n0240   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0248   0x0a 0x11 0xd5 0x0f 0x23 0x0f 0x18 0x0f    ....#...\n0250   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0258   0x22 0x00 0x22 0x00 0x0f 0x00 0x71 0x0f    "."...q.\n0260   0xc0 0x0f 0xc6 0x0f 0xa2 0x0f 0x52 0x0f    ......R.\n0268   0xe5 0x0e 0xc6 0x0e 0x99 0x0e 0x4e 0x0e    ......N.\n0270   0xe7 0x0d 0x7a 0x0d 0x33 0x0d 0x1c 0x0d    ..z.3...\n0278   0xd7 0x0c 0x60 0x0c 0xde 0x0b 0x69 0x0b    ..`...i.\n0280   0xef 0x0a 0x65 0x0a 0xf9 0x09 0x9b 0x09    ..e.....\n0288   0x41 0x09 0xe6 0x08 0x7f 0x08 0x48 0x08    A.....H.\n0290   0x2d 0x08 0x19 0x08 0xfe 0x07 0xe4 0x07    -.......\n0298   0xd5 0x07 0xc2 0x07 0xa7 0x07 0x91 0x07    ........\n02A0   0x8f 0x07 0xc3 0x07 0xdd 0x07 0xc9 0x07    ........\n02A8   0xb3 0x07 0xa0 0x07 0x93 0x07 0x7e 0x07    ......~.\n02B0   0x5d 0x07 0x45 0x07 0x22 0x00 0x2c 0x07    ].E.".,.\n02B8   0x22 0x00 0xe1 0x06 0x83 0x06 0x4b 0x06    ".....K.\n02C0   0x2d 0x06 0x5a 0x06 0x79 0x06 0x65 0x06    -.Z.y.e.\n02C8   0x2c 0x06 0xeb 0x05 0xc3 0x05 0x9e 0x05    ,.......\n02D0   0x7a 0x05 0x5e 0x05 0x8f 0x05 0xac 0x05    z.^.....\n02D8   0x9e 0x05 0x67 0x05 0x22 0x05 0xfc 0x04    ..g."...\n02E0   0xea 0x04 0x2c 0x05 0x87 0x05 0x94 0x05    ..,.....\n02E8   0x9d 0x05 0x92 0x05 0x89 0x05 0x22 0x00    ......".\n02F0   0x35 0x05 0x22 0x00 0xaa 0x04 0x51 0x04    5."...Q.\n02F8   0x1d 0x04 0x10 0x04 0x04 0x04 0xed 0x03    ........\n0300   0xce 0x03 0xc5 0x03 0xed 0x03 0x4c 0x04    ......L.\n0308   0xaa 0x04 0x82 0x05 0x44 0x06 0x62 0x07    ....D.b.\n0310   0x08 0x09 0x76 0x09 0xcf 0x09 0x2a 0x0a    ..v...*.\n0318   0x22 0x00 0xc1 0x0a 0x22 0x00 0x71 0x0b    "...".q.\n0320   0x22 0x00 0xdd 0x0b 0x22 0x00 0x33 0x0c    "...".3.\n0328   0x22 0x00 0x8c 0x0c 0x22 0x00 0xe7 0x0c    "..."...\n0330   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0338   0x08 0x00 0x22 0x00 0x49 0x0d 0x2b 0x0d    ..".I.+.\n0340   0x71 0x0c 0x7b 0x0c 0x13 0x0d 0x38 0x0d    q.{...8.\n0348   0x8b 0x0a 0x23 0x09 0x2e 0x0b 0x42 0x0b    ..#...B.\n0350   0xe8 0x0a 0x7b 0x09 0x4e 0x0a 0xf8 0x08    ..{.N...\n0358   0x6b 0x08 0xa4 0x09 0x71 0x0a 0x6f 0x09    k...q.o.\n0360   0x50 0x09 0x84 0x09 0xf6 0x08 0xba 0x08    P.......\n0368   0x3b 0x08 0x85 0x07 0xe5 0x07 0x07 0x08    ;.......\n0370   0xdf 0x07 0xc8 0x07 0xde 0x07 0xc0 0x07    ........\n0378   0xff 0x07 0x3f 0x08 0x5d 0x08 0x8a 0x08    ..?.]...\n0380   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0388   0x22 0x00 0x0e 0x00 0x22 0x00 0x22 0x00    "...".".\n0390   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0398   0x47 0x08 0x0b 0x08 0x7e 0x08 0x22 0x00    G...~.".\n03A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n03A8   0x22 0x00 0x0f 0x00 0xc2 0x08 0x84 0x08    ".......\n03B0   0x32 0x08 0x44 0x08 0x45 0x08 0x35 0x08    2.D.E.5.\n03B8   0x34 0x08 0xb0 0x07 0x2f 0x08 0x2a 0x08    4.../.*.\n03C0   0x86 0x07 0x11 0x07 0xdf 0x06 0xc7 0x06    ........\n03C8   0x8f 0x06 0x36 0x06 0xe9 0x05 0xff 0x05    ..6.....\n03D0   0xc8 0x05 0x05 0x06 0x79 0x06 0x04 0x07    ....y...\n03D8   0xaa 0x07 0xc5 0x07 0x86 0x07 0xfa 0x07    ........\n03E0   0xe3 0x07 0x07 0x08 0x25 0x08 0x2e 0x08    ....%...\n03E8   0xca 0x08 0x1a 0x09 0xec 0x08 0xc8 0x08    ........\n03F0   0xa0 0x08 0xc0 0x08 0x18 0x08 0xc4 0x07    ........\n03F8   0xb0 0x07 0xd7 0x07 0x02 0x08 0xfd 0x07    ........\n0400   0x90 0x07 0xb9 0x07 0x7f 0x08 0x0a 0x09    ........\n0408   0x8b 0x09 0x2e 0x0a 0xe1 0x0a 0xe2 0x0a    ........\n0410   0x86 0x0a 0x45 0x0a 0x3d 0x0a 0x8e 0x09    ..E.=...\n0418   0x35 0x09 0x77 0x08 0x0e 0x08 0xa1 0x07    5.w.....\n0420   0x52 0x07 0x48 0x07 0x3c 0x07 0x24 0x07    R.H.<.$.\n0428   0xf4 0x06 0x4b 0x07 0x02 0x07 0x39 0x06    ..K...9.\n0430   0x08 0x06 0xe1 0x05 0xbe 0x05 0x3e 0x05    ......>.\n0438   0x38 0x05 0x8f 0x05 0x1d 0x06 0xfc 0x05    8.......\n0440   0x22 0x00 0x7f 0x05 0x4b 0x05 0x46 0x05    "...K.F.\n0448   0x8b 0x05 0x76 0x05 0xae 0x05 0x0e 0x06    ..v.....\n0450   0x74 0x06 0xf7 0x06 0xd5 0x06 0x8c 0x06    t.......\n0458   0x9b 0x06 0x6d 0x06 0x3b 0x06 0x05 0x06    ..m.;...\n0460   0x58 0x06 0x9d 0x06 0x88 0x06 0x62 0x06    X.....b.\n0468   0xdb 0x05 0x81 0x05 0x10 0x05 0x8b 0x04    ........\n0470   0x95 0x04 0xe7 0x04 0x10 0x05 0xae 0x04    ........\n0478   0x2d 0x04 0xf3 0x03 0x22 0x00 0xee 0x03    -..."...\n0480   0x41 0x04 0xa1 0x04 0x22 0x05 0xf3 0x04    A..."...\n0488   0x7c 0x04 0x95 0x04 0xa9 0x04 0x1f 0x05    |.......\n0490   0x22 0x00 0x40 0x05 0x22 0x00 0xd3 0x04    ".@."...\n0498   0x8b 0x04 0x28 0x04 0xce 0x03 0x22 0x00    ..(...".\n04A0   0xc8 0x03 0x4e 0x04 0xc0 0x04 0xa1 0x04    ..N.....\n04A8   0x2e 0x04 0x6e 0x04 0xa2 0x04 0x70 0x05    ..n...p.\n04B0   0xe3 0x05 0x22 0x06 0x22 0x06 0xdd 0x05    .."."...\n04B8   0xef 0x05 0xe2 0x05 0x07 0x06 0xde 0x06    ........\n04C0   0xb6 0x06 0x13 0x07 0x85 0x07 0x05 0x08    ........\n04C8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n04D0   0x22 0x00 0x0e 0x00 0x89 0x08 0x21 0x08    ".....!.\n04D8   0x6e 0x07 0x53 0x07 0x22 0x00 0x22 0x00    n.S.".".\n04E0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n04E8   0x0f 0x00 0x85 0x08 0x67 0x08 0x74 0x08    ....g.t.\n04F0   0x1c 0x09 0xfc 0x08 0x17 0x08 0x2e 0x08    ........\n04F8   0xfc 0x07 0xdc 0x07 0xce 0x07 0xbe 0x07    ........\n0500   0x74 0x06 0x49 0x07 0x7c 0x08 0xf6 0x08    t.I.|...\n0508   0xe0 0x08 0xa2 0x08 0xfb 0x08 0x6b 0x09    ......k.\n0510   0xe6 0x09 0x65 0x0a 0xcf 0x0a 0x04 0x0b    ..e.....\n0518   0xfa 0x0a 0x27 0x0b 0xef 0x0a 0x1c 0x0a    ..\'.....\n0520   0xa7 0x09 0x81 0x09 0x4b 0x09 0x48 0x09    ....K.H.\n0528   0x27 0x09 0xfc 0x09 0xae 0x0a 0x0d 0x0a    \'.......\n0530   0xfc 0x09 0xff 0x09 0xed 0x09 0x3a 0x0a    ......:.\n0538   0x01 0x0b 0x6c 0x0b 0x70 0x0b 0x4a 0x0b    ..l.p.J.\n0540   0x7a 0x0b 0xb7 0x0b 0xc0 0x0b 0xc9 0x0b    z.......\n0548   0xc8 0x0b 0xc0 0x0b 0x9a 0x0b 0xea 0x0a    ........\n0550   0xf6 0x09 0xc6 0x09 0x80 0x09 0xfe 0x08    ........\n0558   0x50 0x08 0x25 0x08 0x12 0x08 0xf0 0x07    P.%.....\n0560   0x99 0x07 0x31 0x07 0xe4 0x06 0xbe 0x06    ..1.....\n0568   0xab 0x06 0x81 0x06 0x64 0x06 0xe8 0x07    ....d...\n0570   0x82 0x09 0xd1 0x09 0xc9 0x09 0xa8 0x09    ........\n0578   0x6c 0x09 0x2c 0x09 0x01 0x09 0xec 0x08    l.,.....\n0580   0x10 0x09 0x59 0x09 0x6e 0x09 0x22 0x00    ..Y.n.".\n0588   0x22 0x09 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0590   0x22 0x00 0x08 0x00 0x22 0x00 0x22 0x00    "...".".\n0598   0x22 0x00 0x22 0x00 0x0b 0x00 0x22 0x00    "."...".\n05A0   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...\n05A8   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n05B0   0x0d 0x00 0x22 0x00 0x00 0x00 0x22 0x00    .."...".\n05B8   0x00 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n05C0   0x22 0x00 0x08 0x00 0x22 0x00 0x16 0x01    "..."...\n05C8   0x22 0x00 0x58 0x09 0x22 0x00 0x5a 0x0d    ".X.".Z.\n05D0   0x22 0x00 0x30 0x11 0x22 0x00 0x2a 0x12    ".0.".*.\n05D8   0x22 0x00 0x22 0x12 0x22 0x00 0x36 0x12    ".".".6.\n05E0   0x22 0x00 0x00 0x11 0x22 0x00 0x44 0x11    "...".D.\n05E8   0x22 0x00 0x9c 0x12 0x22 0x00 0x40 0x13    "...".@.\n05F0   0x22 0x00 0x1a 0x13 0x22 0x00 0x9c 0x12    "..."...\n05F8   0x22 0x00 0x7e 0x12 0x22 0x00 0x22 0x13    ".~.".".\n0600   0x22 0x00 0xae 0x13 0x22 0x00 0x0e 0x13    "..."...\n0608   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0610   0x22 0x00 0x0e 0x00 0x22 0x00 0x4c 0x12    "...".L.\n0618   0x22 0x00 0x2a 0x12 0xca 0x11 0x22 0x00    ".*...".\n0620   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0628   0x22 0x00 0x0f 0x00 0x62 0x11 0x06 0x11    "...b...\n0630   0x7f 0x10 0xde 0x0f 0xf0 0x0e 0x29 0x0e    ......).\n0638   0x6f 0x0d 0x93 0x0c 0xba 0x0b 0x30 0x0b    o.....0.\n0640   0xcd 0x0a 0x4b 0x0a 0x00 0x0a 0x14 0x09    ..K.....\n0648   0xd5 0x07 0xe1 0x06 0x09 0x06 0x73 0x05    ......s.\n0650   0x9b 0x05 0x3e 0x05 0x4c 0x05 0xa6 0x05    ..>.L...\n0658   0xe5 0x05 0x04 0x06 0xe9 0x05 0x93 0x05    ........\n0660   0x49 0x05 0x2e 0x05 0xd0 0x04 0x7d 0x04    I.....}.\n0668   0x55 0x04 0x38 0x04 0x1e 0x04 0x0a 0x04    U.8.....\n0670   0x05 0x04 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n0678   0x22 0x00 0x22 0x00 0x0e 0x00 0xb1 0x04    ".".....\n0680   0xe4 0x04 0x22 0x00 0xec 0x04 0xb1 0x05    ..".....\n0688   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0690   0x22 0x00 0x22 0x00 0x0f 0x00 0x1b 0x06    ".".....\n0698   0xdb 0x05 0x56 0x05 0x76 0x05 0xb1 0x05    ..V.v...\n06A0   0xe1 0x05 0xa7 0x05 0x59 0x05 0x63 0x05    ....Y.c.\n06A8   0x56 0x05 0x22 0x05 0x02 0x05 0x3c 0x05    V."...<.\n06B0   0x22 0x00 0x89 0x05 0xdb 0x05 0x34 0x06    ".....4.\n06B8   0xdc 0x06 0xf4 0x06 0xf0 0x06 0x3e 0x07    ......>.\n06C0   0x24 0x08 0x99 0x08 0x1e 0x09 0xda 0x09    $.......\n06C8   0x16 0x0a 0x47 0x0a 0x1f 0x0a 0xba 0x09    ..G.....\n06D0   0x7c 0x09 0x42 0x09 0x34 0x09 0x1c 0x09    |.B.4...\n06D8   0x3e 0x09 0x63 0x09 0x9a 0x09 0x33 0x0a    >.c...3.\n06E0   0x22 0x0b 0x2b 0x0b 0x0c 0x0b 0xb8 0x0a    ".+.....\n06E8   0x7f 0x0a 0xa2 0x0a 0x00 0x0b 0x80 0x0b    ........\n06F0   0x9c 0x0b 0xe7 0x0b 0xf7 0x0b 0x01 0x0c    ........\n06F8   0xfc 0x0b 0x8c 0x0c 0x4f 0x0d 0x7b 0x0d    ....O.{.\n0700   0x98 0x0d 0x85 0x0d 0x7e 0x0d 0xb9 0x0d    ....~...\n0708   0xb0 0x0d 0x87 0x0d 0x43 0x0d 0xd0 0x0c    ....C...\n0710   0x9f 0x0c 0x77 0x0c 0x29 0x0c 0x78 0x0b    ..w.).x.\n0718   0xca 0x0a 0x34 0x0a 0xbb 0x09 0x72 0x09    ..4...r.\n0720   0x34 0x09 0x0a 0x09 0x10 0x09 0x12 0x09    4.......\n0728   0xe6 0x08 0xc2 0x08 0xb1 0x08 0xaa 0x08    ........\n0730   0xff 0x08 0xbe 0x09 0x73 0x09 0xe6 0x08    ....s...\n0738   0x22 0x00 0xa5 0x08 0xb1 0x08 0x22 0x00    ".....".\n0740   0x22 0x00 0x22 0x00 0x22 0x00 0x08 0x00    "."."...\n0748   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0750   0x0c 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ..".".".\n0758   0x22 0x00 0x0c 0x00 0xf8 0x08 0x59 0x09    ".....Y.\n0760   0xaa 0x09 0x65 0x09 0x22 0x00 0x22 0x00    ..e.".".\n0768   0x22 0x00 0x22 0x00 0x22 0x00 0x0e 0x00    "."."...\n0770   0x1b 0x09 0x03 0x09 0x05 0x09 0x09 0x09    ........\n0778   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n0780   0x22 0x00 0x22 0x00 0x0f 0x00 0x69 0x08    "."...i.\n0788   0x33 0x08 0x22 0x00 0x64 0x08 0x66 0x08    3.".d.f.\n0790   0x7a 0x08 0x14 0x09 0x92 0x09 0x05 0x09    z.......\n0798   0x54 0x08 0xcc 0x07 0x3b 0x07 0x22 0x00    T...;.".\n07A0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n07A8   0x0e 0x00 0xc5 0x06 0x69 0x06 0x73 0x06    ....i.s.\n07B0   0x22 0x00 0x22 0x00 0x22 0x00 0x22 0x00    ".".".".\n07B8   0x22 0x00 0x22 0x00 0x0f 0x00 0x90 0x06    ".".....\n07C0   0x13 0x06 0xeb 0x05 0x3b 0x06 0x21 0x07    ....;.!.\n07C8   0x71 0x07 0xe1 0x07 0xb1 0x08 0x34 0x09    q.....4.\n07D0   0x26 0x09 0xa2 0x08 0x01 0x09 0x1e 0x09    &.......\n07D8   0xd8 0x08 0x22 0x00 0xe5 0x08 0x22 0x00    .."...".\n07E0   0x02 0x09 0x22 0x00 0xea 0x08 0x22 0x00    .."...".\n07E8   0x1f 0x09 0x77 0x09 0x22 0x00 0x55 0x09    ..w.".U.\n07F0   0x3e 0x09 0x22 0x00 0x22 0x00 0x22 0x00    >.".".".\n07F8   0x22 0x00 0x08 0x00 0x93 0x00 0xf7 0x00    ".......'
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 938L,
           'packets.transmit': 974L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 1337L,
         'packets.transmit': 1337L}}
```
