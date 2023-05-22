This is a supplementary material for the speech separation experiment.
This directory structure is listed below:

.
├── moving-0
│   ├── Example1
│   │   ├── att_track0.wav
│   │   ├── att_track1.wav
│   │   ├── info.txt
│   │   ├── mix.wav
│   │   ├── source_track0.wav
│   │   ├── source_track1.wav
│   │   ├── tiv_track0.wav
│   │   ├── tiv_track1.wav
│   │   └── visualization.pdf
│   ├── ...
│   └── Example5
├── moving-1
├── moving-2
└── README.txt

Each example has
(1) a mixture ("mix.wav"),
(2) two ground truth sources (source_track0.wav, source_track1.wav),
(3) two separated signals of TIV-IVA and ATT-IVA,
(4) visualization.pdf, and
(5) info.txt

The wav file name of separated signals were formatted as "[method]_[track_ID].wav".
"tiv" in [method] indicates TIV-IVA, and "att" indicates ATT-IVA.
[track_ID] indicates the ID of four separated signals with the range of 0 through 1.

visualization.pdf shows the results of ATT-IVA which contains attention weights and the spectrograms of separated signals.

info.txt includes SDR score.
Please note that the two ground truth sources had reverberation and these were used as reference signals for the SDR calculation.