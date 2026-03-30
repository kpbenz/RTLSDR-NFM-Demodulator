# Introduction
This Jupyter notebook implements a complete Narrow FM (NFM) demodulation pipeline using a raw IQ sample file captured via an RTL-SDR dongle. The goal is to receive, process, and decode a narrowband FM signal — in this case tuned to 144.470 MHz (2m amateur band) — and produce a playable audio output.

The primary motivation to put this notebook together was my personal curiosity in how FM demodulation with SDR receivers works in detail, but after it was finished I thought it might be interesting for other people too.

More details here: 
<a href="https://github.com/kpbenz/RTLSDR-NFM-Demodulator/blob/main/RTLSDR-NFM-Demodulator.pdf" target="_blank">PDF</a> or 
<a href="https://github.com/kpbenz/RTLSDR-NFM-Demodulator/blob/main/RTLSDR-NFM-Demodulator.html" target="_blank">HTML</a> .
