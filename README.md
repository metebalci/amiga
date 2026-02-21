
This repo contains miscellaneous things for Amiga computers.

## MiSTer_share.adf

This is a standard 3.5" DD containing the expanded contents of [MiSTer_share.lha](https://github.com/MiSTer-devel/Minimig-AGA_MiSTer/blob/3ab91cd9220d4d047886d215b515227cbe568bdd/extra/MiSTer_share.lha); DEVS:dummy.device, DEVS:MountList and L:MiSTerFileSystem. It also contains Mister_share.lha, [lha.run](https://aminet.net/package/util/arc/lha) and the expanded contents of lha.run. 

adf file is created with WinUAE (standard 3.5" DD), then on Minimig core on MiSTer FPGA, it is renamed, MiSTer_share.lha and lha.run is copied into it, then lha.run and then lha_68020 x MiSTer_share.lha executed.
