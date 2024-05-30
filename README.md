
    Most roms (for example LineageOS) automatically includes vendor/extra/product.mk (or vendor/lineage-priv/keys/keys.mk in Lineage 21 or newer). If your rom doesn't, add -include vendor/extra/product.mk (or -include vendor/lineage-priv/keys/keys.mk) to your device tree.
    When everything worked fine, your builds should be signed with dev-keys.

tambahkan commit ini https://github.com/LineageOS/android_build_soong/commit/7d4531838a6a1bd0d4d47d48080d83786510ad98
atur ke vendor/extra/product.mk untuk los 20 ke bawah {jika los based rom, kalu romlain kek pixel gk usah}