# EEG-ReMake

*Accepting suggestions, just create a new issue.* 🤝

This project is based on work of OpenEEG project and Olimex's implementation of it. This project is free to use, but is bound by Creative Commons Attribution-Sharealike license. More info can be found at: <http://openeeg.sourceforge.net>

## Photos

For photos refer to [/img/README.md](/img/README.md)

## Schematics

The schematic and design files are in Autodesk Eagle file-formats. Inspired by: <https://www.olimex.com/Products/EEG/OpenEEG/EEG-SMT/>

## Documentation

I translated the original documentation and format shifted it to markdown. Documentation content list:

1. [Introduction](./doc/0_introduction.md)
1. [Theory](./doc/1_theory.md)
1. [Goals](./doc/2_goals.md)
1. [Methodology](./doc/3_methodology.md)
1. [Results](./doc/4_results.md)
1. [Discussion](./doc/5_discussion.md)
1. [Conclusion](./doc/6_conclusion.md)
1. [Literature](./doc/7_literature.md)

Please mind that this was a high school project and the documentation is not highly sophisticated. But I hope it will be of interest to you.

## The goal

The goal of this project was to customize EEG-SMT by Olimex and design electrodes producable in school environment. I tried to keep expandability of this system open by introducing few new connectors.

## Not perfect

This design definitely has its flaws, but it was tested and proved working. Using eye closing test while measuring at occipital lobe produced apparent alpha wave increase:

![brainwave_recording](/img/sample.JPG "Brainwave recording")

## Software

As for software, I used open-source project BrainBay, which can be found here: <http://www.shifz.org/brainbay/>

## Finished Product

![Final assembly](/img/1.jpg)

I can also provide some guidelines on the final assembly.

## Interview about this project

<https://vedanadosah.cvtisr.sk/eeg-ako-studentsky-projekt>

Hopefully this project will help somebody. 🤗
