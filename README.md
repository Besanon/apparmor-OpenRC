apparmor-OpenRC

This repository tries to expand and adapt the achievements in apparmor policies of Alexandre Pujol, Mikhail Morfikov, Mikhail Kurinnoi and others to the OpenRC init system. Most of the available work in apparmor policing is developed and tested to run under SYSTEMD init systems. Many of the profiles written by these authors can readily be run under linux distributions with NON-SYSTEMD init systems.

This attempt is still in early development. OpenRC so far can´t get completly confined up to now. Some parts already work and - your are invited to help fulfilling this gab if you wish to get a more secure linux with runit as base.

Use these profiles at your own risk and keep in mind that most of them will need some adaptation in some other environment.

In the directory Setup i will give some general hints on how the machines i was working on were configured and set up.
