---
layout: default
title: K3s kubernetes cluster on raspberry pis
---

# K3s kubernetes cluster on raspberry pis

## Pre-requisites

- [Raspberry Pi](https://www.amazon.de/-/en/dp/B07WHWR4LH?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1)
- [Switch](https://www.amazon.de/-/en/dp/B08LZJ2H9S?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- [PoE Hat](https://www.amazon.de/-/en/dp/B091YZ2QSM?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- [Raspberry Pi Rack Case](https://www.amazon.de/-/en/dp/B085ZZV66P?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

## Phase 1 - Installing and configuring Raspberry Pi

To install OS on the Raspberry Pi I inserted the SD card in my computer and used [Raspberry Pi Imager](https://www.raspberrypi.com/software/). This software is pretty simple to use, select the Raspberry Pi model, OS and storage (SD card inserted in the beginning).

![Raspberry Pi Imager](../Images/k3s-on-raspberry-pis/raspberry-pi-imager.jpg)

In this case I used the Raspberry Pi OS lite (64-bit), reason being is that this OS has the bare minimum and as the name indicates, it is light.