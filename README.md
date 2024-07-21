# Qplt
[![Alire](https://img.shields.io/endpoint?url=https://alire.ada.dev/badges/qplt.json)](https://alire.ada.dev/crates/qplt.html)

Quick Plot: an Ada-GUI program to quickly produce a plot of a data set

## Usage
type

qplt -?

for usage instructions, or read the code that outputs them.

## Dependencies
Qplt requires Ada GUI (https://github.com/jrcarter/Ada_GUI) and the PragmAda Reusable Components (https://github.com/jrcarter/PragmARC). Those unfamiliar with Ada GUI should install it, run the test programs, and be familiar with its Readme before running Qplt.

## Sample Input
The files qplt_sine.txt, qplt_sombrero.txt, and qplt_wpop.txt contain sample data for Qplt.

qplt_sine.txt contains a sine curve. Suggested use:

qplt np -t Sine qplt_sine.txt

qplt_sombrero.txt contains the "Sombrero" curve, sin x / x (with the limit of 1 plotted for x = 0). Suggested use:

qplt np -t Sombrero qplt_sombrero.txt

qplt_wpop.txt contains values of world population since 1600. Suggested use:

qplt -t "World Population" -x Year -y "Population in billions" qplt_wpop.txt

The sample input files are proveded under the CC BY-SA license (https://creativecommons.org/licenses/by-sa/4.0/).
