VENDOR=Juniper
NAME=vSRX
IMAGE_FORMAT=qcow
IMAGE_GLOB=*.qcow2
IMAGE=ffp-12.1X47-D15.4-packetmode.qcow2

# match versions like:
# 12.1X47-D15.4
VERSION=$(shell echo $(IMAGE) | sed -e 's/junos-vsrx3-x86-64-//' | sed -e 's/.qcow2//')

-include ../makefile-sanity.include
-include ../makefile.include
