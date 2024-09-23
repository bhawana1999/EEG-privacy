# EEG-privacy

Paper (IEEE BSN 2024): 

Authors: Abdul Aziz, Bhawana Chhaglani (co-primary author), Amirmohammad Radmehr, Joseph Collins, Jeremy Gummeson, Sunghoon Ivan Lee, Ravi Karkar, and Phuc Nguyen

## Abstract

EEG signals contain highly sensitive information
about an individual’s mental state, cognitive processes, and health
conditions, making privacy preservation crucial. With the rise
of commercial headwear capable of capturing EEG signals,
developing robust mechanisms for ensuring privacy of such data
is imperative. This work aims to protect EEG data privacy in
cloud-based processing systems by sending intermediate output
after neural network layer splitting to the cloud. We propose a
novel holistic Combined Privacy Metric (CPM) that quantifies
privacy leakage between raw EEG signals and intermediate
outputs. Our study focuses on EEG-based seizure detection using
a 1D CNN architecture, achieving accuracy of 96.25%. We
evaluate various splitting configurations to optimize the trade-off
between privacy preservation and computational efficiency. We
find that splitting after the second convolutional layer achieves
a CPM of 0.82 with a modest client-side model size of 509kB.
This approach significantly enhances EEG data privacy while
enabling effective cloud-based analysis, potentially facilitating
wider adoption of secure EEG technologies in healthcare and
research applications.
