# Keychron K3v2 RGB Optical ISO

K3v2 RGB Optical ISO with VIA support.

Use the "Design" tab to upload the keyboard_via_iso.json file at https://usevia.app/ as this keyboard is not registered in via-keyboards repository (mainly due to lack of unique vendorId:productId as my device came with a generic one only).

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb keychron/k3/rgb/v2/optical_iso -km via_iso
    
or 
    
    make keychron/k3/rgb/v2/optical_iso:via_iso

* * *

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).