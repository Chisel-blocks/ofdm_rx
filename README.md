OFDM Receiver Module
====================

This module is an OFDM receiver made from three Chisel circuit blocks:

- f2_symbol_sync
- ofdm_demodulator
- channel_equalizer

It is initially intended just to check that an OFDM signal can traverse
the entire signal path make a modest amount of sense.
