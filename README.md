DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 9437.

Contents
--------

1. [ About ](#about)
2. [ Devices ](#devices)
   * [ Cpu ](#cpu)
   * [ Memory ](#memory)
   * [ Battery ](#battery)

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}

    ( e.g. Notebook/Dell/XPS/XPS 15 9550/323DFD9291C0 )

Devices
-------

Top 250 most popular devices in each category.

Count  - number of computers with this device installed,
Report - link to DMI report.

### Cpu

| MFG        | Name                             | GHz  | Count | Report |
|------------|----------------------------------|------|-------|--------|
| AMD        | GX-412TC SOC                     |      | 247   | [BA38FE419DBF](<Desktop/PC Engines/APU/APU2/BA38FE419DBF>) |
| Intel      | Celeron J4125                    | 2.00 | 227   | [1A9E9336AA29](<Desktop/Others/Others/Others/1A9E9336AA29>) |
| Intel      | Celeron N5095                    | 2.00 | 211   | [E613798C5600](<Desktop/Hardkernel/ODROID-H/ODROID-H3/E613798C5600>) |
| Intel      | Celeron J3160                    | 1.60 | 163   | [D6B753657A49](<Desktop/Protectli/FW4/FW4B/D6B753657A49>) |
| Intel      | Celeron J1900                    | 1.99 | 92    | [F72AFC021F41](<Mini Pc/AMI/Aptio/Aptio CRB/F72AFC021F41>) |
| Intel      | Core i5-7200U                    | 2.50 | 91    | [D1A40FF08255](<Desktop/Others/Others/Others/D1A40FF08255>) |
| Intel      | Core i5-6500                     | 3.20 | 78    | [8D6280FED79B](<Desktop/Dell/OptiPlex/OptiPlex 5040/8D6280FED79B>) |
| Intel      | Core 2 Duo                       |      | 73    | [946464813E4A](<Desktop/Dell/OptiPlex/OptiPlex 960/946464813E4A>) |
| Intel      | 11th Gen Core i7-1165G7          | 2.80 | 71    | [420EF0844B72](<Desktop/Supermicro/SYS-E100/SYS-E100-12T-C/420EF0844B72>) |
| Intel      | Core i5-8250U                    | 1.60 | 69    | [E23EA081B264](<Notebook/Hewlett-Packard/ProBook/ProBook 640 G4/E23EA081B264>) |
| Intel      | Core i5-3470                     | 3.20 | 69    | [5BB8ED71697F](<Desktop/YENTEK/ITX-B75/ITX-B75R1/5BB8ED71697F>) |
| Intel      | Celeron J1900                    | 1.99 | 65    | [0B68D1D0C335](<Mini Pc/AMI/Aptio/Aptio CRB/0B68D1D0C335>) |
| Intel      | Celeron J3455                    | 1.50 | 62    | [3487CD2A0FE8](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8>) |
| Intel      | Core i5-4570                     | 3.20 | 60    | [4BA15FF3127D](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/4BA15FF3127D>) |
| Intel      | Core i5-2520M                    | 2.50 | 59    | [F147F7B5D3C5](<Notebook/Panasonic/CF-53/CF-53AAGHYDM/F147F7B5D3C5>) |
| Intel      | Core i5-3570 CPU                 |      | 57    | [B76DE9336864](<Desktop/Others/T/T100/B76DE9336864>) |
| AMD        | GX-420CA SOC with Radeon HD G... |      | 56    | [804C8B446779](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/804C8B446779>) |
| Intel      | Core i5-4590                     | 3.30 | 54    | [295D902A3E56](<Desktop/Dell/OptiPlex/OptiPlex 3020/295D902A3E56>) |
| Intel      | Atom D525                        | 1.80 | 53    | [EDCF6BFE74C6](<Desktop/Others/Others/Others/EDCF6BFE74C6>) |
| Intel      | Core i3-7100U                    | 2.40 | 51    | [9BA0256CC9A4](<Desktop/Protectli/FW/FW6/9BA0256CC9A4>) |
| Intel      | Core i7-7500U                    | 2.70 | 50    | [A81E6D09A273](<Desktop/Others/Others/Others/A81E6D09A273>) |
| Intel      | Core i5-2400                     | 3.10 | 50    | [A7487A4DF12B](<Desktop/Intel/MAHOBAY/MAHOBAY/A7487A4DF12B>) |
| AMD        | GX-415GA SOC with Radeon HD G... |      | 49    | [FEAC2384E90C](<Desktop/Fujitsu/FUTRO/FUTRO S920/FEAC2384E90C>) |
| AMD        | RX-427BB with AMD Radeon R7 G... |      | 49    | [B0451E2BD475](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/B0451E2BD475>) |
| Intel      | Celeron J4105                    | 1.50 | 48    | [7C2F5651DB91](<Mini Pc/AWOW/AK34/AK34Pro/7C2F5651DB91>) |
| Intel      | Core i7-8550U                    | 1.80 | 48    | [2BCD3A50A70F](<Desktop/Protectli/FW/FW6/2BCD3A50A70F>) |
| Intel      | Core i7-3770                     | 3.40 | 47    | [6E3F5994ED54](<Desktop/Gigabyte Technology/H77/H77N-WIFI/6E3F5994ED54>) |
| Intel      | Core i5-5200U                    | 2.20 | 46    | [0FD1E037978C](<Notebook/Lenovo/ThinkPad/ThinkPad L450 20DSS1S402/0FD1E037978C>) |
| Intel      | Celeron N3150                    | 1.60 | 45    | [B72B0E66A1D0](<Desktop/ZOTAC/Others/Others/B72B0E66A1D0>) |
| Intel      | Celeron N3450                    | 1.10 | 44    | [B3D254AA719B](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/B3D254AA719B>) |
| Intel      | Core i5-3320M                    | 2.60 | 43    | [4A02B8E7AE26](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23255NG/4A02B8E7AE26>) |
| Intel      | Core i5-6300U                    | 2.40 | 42    | [3E8E50D3AAD2](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FCS13H00/3E8E50D3AAD2>) |
| Intel      | Atom C3558                       | 2.20 | 41    | [28F0FD3282AE](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/28F0FD3282AE>) |
| Intel      | Pentium N3700                    | 1.60 | 40    | [8054EC01AC51](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51>) |
| Intel      | Celeron 3865U                    | 1.80 | 37    | [05FB3F550CBF](<Desktop/Others/Others/Others/05FB3F550CBF>) |
| Intel      | Atom E3930                       | 1.30 | 36    | [E5BB2C01E37E](<Firewall/Sophos/XG/XG/E5BB2C01E37E>) |
| Intel      | Pentium Silver J5005             | 1.50 | 35    | [008D25A435CA](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/008D25A435CA>) |
| Intel      | Atom E3845                       | 1.91 | 35    | [E04B0718D9FE](<Desktop/CNCTION-IAF-E3845/Others/Others/E04B0718D9FE>) |
| Intel      | Core i5-5300U                    | 2.30 | 35    | [1D8EDC67587A](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/1D8EDC67587A>) |
| Intel      | Core i5-6200U                    | 2.30 | 34    | [69543A27CE5E](<Desktop/Others/Others/Others/69543A27CE5E>) |
| Intel      | Core i3-6100                     | 3.70 | 33    | [A4A14A42DEC0](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/A4A14A42DEC0>) |
| AMD        | G-T40E                           |      | 32    | [456105B8D8BA](<Desktop/PC Engines/apu/apu1/456105B8D8BA>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 32    | [67967DDE531E](<Desktop/MSI/MS-7/MS-7B86/67967DDE531E>) |
| Intel      | Core i5-10210U                   | 1.60 | 32    | [B48ED7162411](<Notebook/Lenovo/ThinkBook/ThinkBook 14-IML 20RV/B48ED7162411>) |
| Intel      | 11th Gen Core i5-11400           | 2.60 | 32    | [A34062E540B0](<Desktop/ASUSTek Computer/PRIME/PRIME B560M-A AC/A34062E540B0>) |
| Intel      | Core i3-4160                     | 3.60 | 31    | [54266AFBE61A](<Desktop/Intel/SHARKBAY/SHARKBAY/54266AFBE61A>) |
| Intel      | Celeron 2955U                    | 1.40 | 30    | [9343098F3B9C](<Notebook/Google/Peppy/Peppy/9343098F3B9C>) |
| Intel      | Celeron N3160                    | 1.60 | 30    | [F19B9213C2D1](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/F19B9213C2D1>) |
| Intel      | Xeon D-1518                      | 2.20 | 30    | [5A4A6C8BA8CA](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/5A4A6C8BA8CA>) |
| Intel      | Core 2 Duo                       |      | 29    | [849F8FB334AD](<Firewall/Sophos/UTM/UTM/849F8FB334AD>) |
| Intel      | Core i3-8100                     | 3.60 | 29    | [D58DA6B93E88](<Server/Supermicro/Super/Super Server/D58DA6B93E88>) |
| Intel      | Core i7-7700                     | 3.60 | 29    | [E4FE9CCC81FB](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G3 SFF/E4FE9CCC81FB>) |
| Intel      | Core i5-3570                     | 3.40 | 29    | [4F9E73525C74](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/4F9E73525C74>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 28    | [8AE8FFB5342F](<Desktop/ASRock/B450/B450 Steel Legend/8AE8FFB5342F>) |
| Intel      | Core i7-4770                     | 3.40 | 28    | [5B663F303B58](<Desktop/Intel/DH87RL/DH87RL AAG74240-400/5B663F303B58>) |
| Intel      | Xeon E3-1220 v3                  | 3.10 | 28    | [84A39098466A](<Server/Fujitsu/PRIMERGY/PRIMERGY RX100 S8/84A39098466A>) |
| Intel      | Atom C2558                       | 2.40 | 28    | [187D17A31A14](<Firewall/Others/Others/Others/187D17A31A14>) |
| Intel      | Celeron N4100                    | 1.10 | 27    | [B565A5A319EC](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/B565A5A319EC>) |
| Intel      | Core i5-7500                     | 3.40 | 27    | [7833F465DC51](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/7833F465DC51>) |
| AMD        | Ryzen Embedded V1500B            |      | 26    | [051064EC5D5D](<Notebook/Deciso/NetBoard-A/NetBoard-A10/051064EC5D5D>) |
| Intel      | Celeron J6412                    | 2.00 | 26    | [FACF4F35BB2A](<Mini Pc/Intel/NUC62R/NUC62R 2C/FACF4F35BB2A>) |
| Intel      | Xeon E31220                      | 3.10 | 26    | [0338EE9299EB](<Server/Fujitsu/PRIMERGY/PRIMERGY RX100 S7/0338EE9299EB>) |
| Intel      | Core i3-3220                     | 3.30 | 26    | [09AB318CDA52](<Desktop/ASRock/H61/H61M-HVS/09AB318CDA52>) |
| Intel      | Core i3-4130                     | 3.40 | 26    | [DA8417B6E571](<Desktop/MSI/MS/MS-7850/DA8417B6E571>) |
| Intel      | Core i7-6700                     | 3.40 | 26    | [D34CBCF72E47](<Desktop/Dell/OptiPlex/OptiPlex 7040/D34CBCF72E47>) |
| AMD        | GX-222GC SOC with Radeon R5E ... |      | 25    | [E0EB88891C6C](<Desktop/Fujitsu/FUTRO/FUTRO S920/E0EB88891C6C>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 25    | [097C24A5E2E2](<Desktop/ASRock/X570/X570 PG Velocita/097C24A5E2E2>) |
| Intel      | Core i7-10510U                   | 1.80 | 25    | [D7A3CD7157C0](<Desktop/Others/Others/Others/D7A3CD7157C0>) |
| Intel      | Celeron J1800                    | 2.41 | 25    | [B6CD8CD35969](<Desktop/Others/Others/Others/B6CD8CD35969>) |
| Intel      | Core i5-4200U                    | 1.60 | 25    | [0A0656F75850](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0A0656F75850>) |
| Intel      | Core i7-8700                     | 3.20 | 24    | [1BEF995E51D9](<Desktop/Supermicro/SYS-E300/SYS-E300-9C/1BEF995E51D9>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 23    | [7EE5E91A5C37](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/7EE5E91A5C37>) |
| Intel      | Atom N450                        | 1.66 | 23    | [030427880E54](<Firewall/Sophos/UTM/UTM/030427880E54>) |
| Intel      | Xeon X3430                       | 2.40 | 23    | [29E43F11A505](<Server/Dell/PowerEdge/PowerEdge R210/29E43F11A505>) |
| Intel      | Core i3-2120 @ 3.30GH            |      | 23    | [F80BBA9F918E](<Desktop/Dell/OptiPlex/OptiPlex 390/F80BBA9F918E>) |
| Intel      | Core i7-2600                     | 3.40 | 23    | [A061B041BBF6](<Desktop/Foxconn/H61/H61M-H61M-S/A061B041BBF6>) |
| Intel      | Core i7-4790                     | 3.60 | 23    | [BBBF308D5C62](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 TWR/BBBF308D5C62>) |
| Intel      | Core i3-4010U                    | 1.70 | 23    | [91D215A5C4F7](<Notebook/Intel/H81/H81U/91D215A5C4F7>) |
| AMD        | EPYC 3201 8-Core                 |      | 22    | [162896F7FCF9](<Notebook/Deciso/NetBoard-A/NetBoard-A20/162896F7FCF9>) |
| Intel      | Xeon E5620                       | 2.40 | 22    | [286B1300263F](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/286B1300263F>) |
| Intel      | Xeon E3-1220 V2                  | 3.10 | 22    | [36872CFF8ECA](<Server/Hewlett-Packard/ProLiant/ProLiant DL320e Gen8/36872CFF8ECA>) |
| Intel      | Xeon E5-2650 v2                  | 2.60 | 22    | [1AF57826CF89](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/1AF57826CF89>) |
| Intel      | Core i5-4210U                    | 1.70 | 22    | [10A8028C9F99](<Notebook/Lenovo/Flex/Flex 2-15 20405/10A8028C9F99>) |
| Intel      | Celeron J3060                    | 1.60 | 22    | [EE3235442DAF](<Desktop/Protectli/FW2/FW2B/EE3235442DAF>) |
| Intel      | Atom C2758                       | 2.40 | 22    | [948F73A5F67A](<Mini Pc/Supermicro/A1/A1SAi/948F73A5F67A>) |
| Intel      | Core i5-6500T                    | 2.50 | 22    | [E53CD437F40A](<Desktop/Dell/OptiPlex/OptiPlex 7040/E53CD437F40A>) |
| AMD        | FX-8350 Eight-Core               |      | 21    | [55CAA0D2979E](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/55CAA0D2979E>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 21    | [721988A29B56](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/721988A29B56>) |
| Intel      | Celeron J4115                    | 1.80 | 21    | [D15B59962C50](<Desktop/Hardkernel/ODROID-H/ODROID-H2/D15B59962C50>) |
| Intel      | Core i5-7400                     | 3.00 | 21    | [B5BC6B88CCF7](<Desktop/Dell/Inspiron/Inspiron 3268/B5BC6B88CCF7>) |
| Intel      | Core i3-10100                    | 3.60 | 21    | [82CE853FF0D7](<Desktop/ASRock/B460/B460M-HDV/82CE853FF0D7>) |
| Intel      | Core i3-5005U                    | 2.00 | 21    | [35A74EE93D78](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/35A74EE93D78>) |
| Intel      | Core i5-5250U                    | 1.60 | 21    | [C9D03D675712](<Desktop/Intel/QHSW/QHSW02/C9D03D675712>) |
| Intel      | Core i3-4005U                    | 1.70 | 21    | [800DC4E1CDAC](<Notebook/Dell/Inspiron/Inspiron 3442/800DC4E1CDAC>) |
| Intel      | Atom C2358                       | 1.74 | 21    | [142A4346F311](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F18/142A4346F311>) |
| Intel      | Xeon D-2123IT                    | 2.20 | 21    | [A4593F9EBC3F](<Desktop/Supermicro/SYS-E302/SYS-E302-9D/A4593F9EBC3F>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 20    | [96D8FD49C0BC](<Desktop/ASUSTek Computer/P5K/P5K SE-EPU/96D8FD49C0BC>) |
| Intel      | CPU Version                      |      | 20    | [238B820A0516](<Notebook/LG Electronics/COLUMBIA/COLUMBIA/238B820A0516>) |
| Intel      | Celeron N2940                    | 1.83 | 20    | [A3DBD4D871FE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE>) |
| Intel      | Core i3-3240                     | 3.40 | 20    | [4F423173767B](<Desktop/Dell/OptiPlex/OptiPlex 7010/4F423173767B>) |
| Intel      | Core i7-3520M                    | 2.90 | 20    | [6487D6320759](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E752/6487D6320759>) |
| Intel      | Xeon E3-1230 V2                  | 3.30 | 20    | [69978AB0AF21](<Desktop/Supermicro/X9/X9SCL-X9SCM/69978AB0AF21>) |
| Intel      | Core 2 Quad CPU                  |      | 19    | [88F5E1B86CBA](<Desktop/Gigabyte Technology/G31/G31M-S2L/88F5E1B86CBA>) |
| Intel      | Core i3-2100 @ 3.10GH            |      | 19    | [50A84B489F41](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/50A84B489F41>) |
| Intel      | Core i5-3210M                    | 2.50 | 19    | [26D21821107F](<Notebook/Samsung Electronics/300E4/300E4C-300E5C-300E7C/26D21821107F>) |
| Intel      | Xeon E3-1270 v3                  | 3.50 | 19    | [1A2C93D358DD](<Server/Supermicro/X10/X10SLH-N6-ST031/1A2C93D358DD>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 18    | [2325A856795F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F>) |
| Intel      | Core i5-8365U                    | 1.60 | 18    | [BF7EDEBFE051](<Desktop/Others/Others/Others/BF7EDEBFE051>) |
| Intel      | Core i5-7300U                    | 2.60 | 18    | [9AC25391B4C3](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HMS06Q1D/9AC25391B4C3>) |
| Intel      | Core i5-8500                     | 3.00 | 18    | [8B92F9224A5E](<Desktop/Gigabyte Technology/Z370/Z370 HD3/8B92F9224A5E>) |
| Intel      | Core i3-7100                     | 3.90 | 18    | [5E67B6376C6A](<Desktop/Shuttle/XH/XH110/5E67B6376C6A>) |
| Intel      | Core i5-10400                    | 2.90 | 18    | [C955C1EB3B0C](<Desktop/MSI/MS-7/MS-7D20/C955C1EB3B0C>) |
| Intel      | Core i3-4150                     | 3.50 | 18    | [428E34A7C4C4](<Desktop/Gigabyte Technology/H81/H81M-D2V/428E34A7C4C4>) |
| Intel      | Pentium G3220                    | 3.00 | 18    | [0BE9EF1D92A6](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/0BE9EF1D92A6>) |
| Intel      | Core i7-4600U                    | 2.10 | 18    | [3AF261B74E3D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3AF261B74E3D>) |
| Intel      | Core i5-6400                     | 2.70 | 18    | [9A9EB9A15ABA](<Desktop/Acer/Aspire/Aspire TC-780/9A9EB9A15ABA>) |
| Intel      | Core i7-8750H                    | 2.20 | 17    | [8EB695D386EB](<Notebook/Dell/G5/G5 5587/8EB695D386EB>) |
| Intel      | Core i5-2500 @ 3.30GH            |      | 17    | [F9D70B3F61AF](<Desktop/Shuttle/DS/DS61/F9D70B3F61AF>) |
| Intel      | Celeron 1037U                    | 1.80 | 17    | [E67EA1943459](<Notebook/Shuttle/DS/DS437/E67EA1943459>) |
| Intel      | Core i5-4570T                    | 2.90 | 17    | [93E8E996FA3C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAS0UT00/93E8E996FA3C>) |
| Intel      | Pentium G3420                    | 3.20 | 17    | [26942D8D6A9C](<Firewall/Sophos/SG/SG/26942D8D6A9C>) |
| Intel      | Core i3-6006U                    | 2.00 | 17    | [13FB3523EE71](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15ISK 80XH/13FB3523EE71>) |
| Intel      | Core i7-6500U                    | 2.50 | 17    | [35A7C406512F](<Notebook/Dell/Inspiron/Inspiron 5559/35A7C406512F>) |
| Intel      | Core i7-6600U                    | 2.60 | 17    | [0F59EDF43A82](<Notebook/Dell/Latitude/Latitude E5570/0F59EDF43A82>) |
| Intel      | Pentium G4400                    | 3.30 | 17    | [2E0405C43F74](<Desktop/ASRock/H110/H110M-ITX/2E0405C43F74>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 16    | [0CDD8B581280](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K II/0CDD8B581280>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 16    | [93DC5F7B5AAA](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/93DC5F7B5AAA>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 16    | [CA69BE9A5534](<Desktop/ASRock/X570S/X570S PG Riptide/CA69BE9A5534>) |
| Intel      | Core i5-8350U                    | 1.70 | 16    | [BD0ED8EF7DB5](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LBS0FH00/BD0ED8EF7DB5>) |
| Intel      | Xeon E3-1225 v3                  | 3.20 | 16    | [D7A8EA6F6B9F](<Firewall/Sophos/SG/SG/D7A8EA6F6B9F>) |
| Intel      | Core i5-4300U                    | 1.90 | 16    | [DC9FF593E3E2](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ005SUS/DC9FF593E3E2>) |
| Intel      | Atom C3758                       | 2.20 | 16    | [F11285BC0983](<Server/Supermicro/Super/Super Server/F11285BC0983>) |
| AMD        | FX-6300 Six-Core                 |      | 15    | [88A73B2C8E7E](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 15    | [25E14418372B](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 15    | [63762628C1D4](<Desktop/MSI/MS-7/MS-7B79/63762628C1D4>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 15    | [5C7E06AB8947](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947>) |
| Intel      | Core i7-8565U                    | 1.80 | 15    | [578D3382155D](<Desktop/Shuttle/DS10/DS10U/578D3382155D>) |
| Intel      | Core i7-10750H                   | 2.60 | 15    | [71CCA11D28B6](<Notebook/Monster/ABRA/ABRA A7 V11.2/71CCA11D28B6>) |
| Intel      | Core i5-2540M                    | 2.60 | 15    | [57AA3F56F3EA](<Notebook/Hewlett-Packard/Others/Others/57AA3F56F3EA>) |
| Intel      | Core i3-5010U                    | 2.10 | 15    | [892B0188C626](<Desktop/Datto/SSD/SSD/892B0188C626>) |
| AMD        | EPYC 3101 4-Core                 |      | 14    | [A8CC11BE6FA1](<Notebook/Deciso/NetBoard-A/NetBoard-A20/A8CC11BE6FA1>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 14    | [435F418C7DE2](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 14    | [EB9A81DC78CC](<Notebook/TUXEDO/Pulse/Pulse 15 Gen1/EB9A81DC78CC>) |
| Intel      | Core i3-1005G1                   | 1.20 | 14    | [3C84623AD933](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M60e 11LU000XAC/3C84623AD933>) |
| Intel      | Core 2 CPU                       |      | 14    | [82F1FE229BCF](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/82F1FE229BCF>) |
| Intel      | Pentium Gold G7400               |      | 14    | [DB157C8A29C5](<Desktop/Dell/Inspiron/Inspiron 3910/DB157C8A29C5>) |
| Intel      | Core i5-8400                     | 2.80 | 14    | [EE72BB208FC3](<Desktop/Gigabyte Technology/H370/H370M-D3H/EE72BB208FC3>) |
| Intel      | Core i5-9500                     | 3.00 | 14    | [41E13E2C9189](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G6 SFF/41E13E2C9189>) |
| Intel      | Pentium G4560                    | 3.50 | 14    | [85F37DF659E7](<Desktop/ASUSTek Computer/H110/H110I-PLUS/85F37DF659E7>) |
| Intel      | Celeron G1820                    | 2.70 | 14    | [8955C14B9421](<Firewall/Sophos/SG/SG/8955C14B9421>) |
| Intel      | Core i5-4570S                    | 2.90 | 14    | [E09EF3162DF3](<Firewall/Sophos/SG/SG/E09EF3162DF3>) |
| Intel      | Core i3-4030U                    | 1.90 | 14    | [BBD3502ACAFB](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/BBD3502ACAFB>) |
| AMD        | Athlon 3000G with Radeon Vega... |      | 13    | [27DA135076D6](<Desktop/MSI/MS-7/MS-7B89/27DA135076D6>) |
| Intel      | Core i3-8145U                    | 2.10 | 13    | [D359F3413E35](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/D359F3413E35>) |
| Intel      | 12th Gen Core i9-12900K          |      | 13    | [441B708DBD6C](<Desktop/MSI/MS-7/MS-7D59/441B708DBD6C>) |
| Intel      | Pentium Gold G5400               | 3.70 | 13    | [873B0729310E](<Desktop/MSI/MS-7/MS-7C09/873B0729310E>) |
| Intel      | Celeron J1900                    | 1.99 | 13    | [FC5120937F9C](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FC5120937F9C>) |
| Intel      | Celeron N2930                    | 1.83 | 13    | [26568100DB40](<Desktop/Others/Others/Others/26568100DB40>) |
| Intel      | Celeron G1610T                   | 2.30 | 13    | [36E7C68AA33D](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D>) |
| Intel      | Core i5-4590S                    | 3.00 | 13    | [1503C0BD2782](<Desktop/Dell/OptiPlex/OptiPlex 3020/1503C0BD2782>) |
| Intel      | Core i5-4590T                    | 2.00 | 13    | [2256C0E25C58](<Desktop/Dell/OptiPlex/OptiPlex 9020M/2256C0E25C58>) |
| Intel      | Xeon E3-1231 v3                  | 3.40 | 13    | [C40A237C6EFF](<Server/Supermicro/X10/X10SLH-N6-ST031/C40A237C6EFF>) |
| Intel      | Core i7-5550U                    | 2.00 | 13    | [07E9F2DE21F0](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/07E9F2DE21F0>) |
| Intel      | Xeon E5-2630 v3                  | 2.40 | 13    | [006D640A4E82](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82>) |
| Intel      | Celeron N3350                    | 1.10 | 13    | [B128AA683D4A](<Notebook/Irbis/NB/NB78/B128AA683D4A>) |
| Intel      | Celeron J4005                    | 2.00 | 12    | [A3C224C7E38D](<Desktop/ASRock/J4005/J4005B-ITX/A3C224C7E38D>) |
| Intel      | Celeron N4020                    | 1.10 | 12    | [969ADE3929EE](<Notebook/Chuwi/Others/Others/969ADE3929EE>) |
| Intel      | Core i5-8265U                    | 1.60 | 12    | [7A14B1FE5621](<Desktop/Others/Others/Others/7A14B1FE5621>) |
| Intel      | Core i7-8565U                    | 1.80 | 12    | [DEFB15FCD1BA](<Notebook/Others/Others/Others/DEFB15FCD1BA>) |
| Intel      | Core i5-8265U                    | 1.60 | 12    | [0993E73A2A97](<Notebook/Acer/Swift/Swift SF314-56/0993E73A2A97>) |
| Intel      | Core i7-9750H                    | 2.60 | 12    | [018D5474C571](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc1xxx/018D5474C571>) |
| Intel      | Core i3-9100                     | 3.60 | 12    | [385915D54B9D](<Desktop/Others/T360/T360D11/385915D54B9D>) |
| Intel      | Core i7-7700K                    | 4.20 | 12    | [90B8DCF14D16](<Desktop/MSI/MS-7/MS-7A71/90B8DCF14D16>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 12    | [C8BCBAB0A3A6](<Desktop/Lenovo/ThinkCentre/ThinkCentre M57p 6073ATU/C8BCBAB0A3A6>) |
| Intel      | Xeon E5520                       | 2.27 | 12    | [86E57128AC4E](<Server/Supermicro/X8/X8DTL/86E57128AC4E>) |
| Intel      | Core i5-2400S                    | 2.50 | 12    | [472E1FAA4B5F](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite USDT PC/472E1FAA4B5F>) |
| Intel      | Xeon E5645                       | 2.40 | 12    | [34F0B81A9C93](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93>) |
| Intel      | Atom E3827                       | 1.74 | 12    | [08C47B090CF6](<Mini Pc/Dell/Edge/Edge Gateway 5100/08C47B090CF6>) |
| Intel      | Core i5-3230M                    | 2.60 | 12    | [AD023293EF8F](<Notebook/Lenovo/G400s/G400s 20244/AD023293EF8F>) |
| Intel      | Core i5-3570K                    | 3.40 | 12    | [E10661B1DB42](<Desktop/ASUSTek Computer/P8/P8H77-V/E10661B1DB42>) |
| Intel      | Core i7-3770K                    | 3.50 | 12    | [81B7F9268A6F](<Desktop/ECS/Z77/Z77H2-AX/81B7F9268A6F>) |
| Intel      | Core i5-4460                     | 3.20 | 12    | [729ED9C2D525](<Desktop/ASRock/H81M-VG4/H81M-VG4 R2.0/729ED9C2D525>) |
| Intel      | Core i7-4790K                    | 4.00 | 12    | [4E415A131D74](<Desktop/Gigabyte Technology/Z97/Z97X-UD3H-BK/4E415A131D74>) |
| Intel      | Core i7-5500U                    | 2.40 | 12    | [EE7FF0B1EA12](<Notebook/Dell/XPS/XPS 13 9343/EE7FF0B1EA12>) |
| Intel      | Core i7-5600U                    | 2.60 | 12    | [F784FC43DD4A](<Notebook/Dell/Latitude/Latitude E5450/F784FC43DD4A>) |
| Intel      | Core i5-4250U                    | 1.30 | 12    | [427EC7AA7E9D](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/427EC7AA7E9D>) |
| Intel      | Celeron N3050                    | 1.60 | 12    | [5317E70D06CC](<Mini Pc/AMI/Aptio/Aptio CRB/5317E70D06CC>) |
| Intel      | Pentium N4200                    | 1.10 | 12    | [23F29A5F79A0](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0>) |
| Intel      | Core i7-6700K                    | 4.00 | 12    | [9FCEC82B3F4D](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9FCEC82B3F4D>) |
| Intel      | Xeon E3-1225 v5                  | 3.30 | 12    | [F7CE2619878B](<Desktop/Others/Others/Others/F7CE2619878B>) |
| Intel      | Atom D2550                       | 1.86 | 12    | [F7D6D6A23A9C](<Desktop/Intel/ITX-M2F/ITX-M2F VER:1.2A/F7D6D6A23A9C>) |
|            | Unknown                          |      | 12    | [66C97E231B7A](<Desktop/friendlyelec/nanopi-m/nanopi-m4/66C97E231B7A>) |
| AMD        | GX-416RA SOC                     |      | 11    | [75C3892DF002](<Desktop/Deciso/Netboard/Netboard A10/75C3892DF002>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 11    | [69AAAA30BEFA](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 11    | [98026F7F98B8](<Notebook/Acer/Swift/Swift SF314-42/98026F7F98B8>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 11    | [304E9CF54A4D](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/304E9CF54A4D>) |
| Intel      | 12th Gen Core i5-12450H          |      | 11    | [1F56DDC702EE](<Notebook/Samsung Electronics/750/750XEE/1F56DDC702EE>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 11    | [A098A01ACD0B](<Desktop/Intel/DG41TY/DG41TY AAE47335-300/A098A01ACD0B>) |
| Intel      | Xeon X5650                       | 2.67 | 11    | [209AA94D6139](<Server/Dell/PowerEdge/PowerEdge R710/209AA94D6139>) |
| Intel      | Core i3-3217U                    | 1.80 | 11    | [75F0D02471E0](<Desktop/Intel/D33217CK/D33217CK G76541-300/75F0D02471E0>) |
| Intel      | Pentium G2020                    | 2.90 | 11    | [62181A4AA263](<Desktop/MSI/MS/MS-7788/62181A4AA263>) |
| Intel      | Xeon E3-1220L V2                 | 2.30 | 11    | [7046F64B97D5](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5>) |
| Intel      | Core i3-4170                     | 3.70 | 11    | [B6637613A7A9](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10DS0015UK/B6637613A7A9>) |
| Intel      | Xeon E5-2620 v3                  | 2.40 | 11    | [FDECFF575FFE](<Desktop/Intel/X/X99/FDECFF575FFE>) |
| Intel      | Pentium N3710                    | 1.60 | 11    | [501DB0F9324A](<Notebook/ASUSTek Computer/X541/X541SA/501DB0F9324A>) |
| Intel      | Atom C3508                       | 1.60 | 11    | [A69CDBD127C3](<Firewall/Sophos/SG/SG/A69CDBD127C3>) |
| Intel      | Core i5 M 520                    | 2.40 | 11    | [CDBD8C566708](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 10    | [95C452956946](<Mini Pc/AZW/SER/SER/95C452956946>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 10    | [1AC653AE7D99](<Notebook/Lenovo/ThinkPad/ThinkPad E495 20NEA00QUS/1AC653AE7D99>) |
| AMD        | Ryzen 9 5950X 16-Core            |      | 10    | [30A1CCEF9C6D](<Desktop/MSI/MS-7/MS-7C91/30A1CCEF9C6D>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 10    | [568B35CB6B3E](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 82MS/568B35CB6B3E>) |
| Intel      | Core i3-8130U                    | 2.20 | 10    | [0F4F53753F3F](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15IKB 81DE/0F4F53753F3F>) |
| Intel      | Core i7-8650U                    | 1.90 | 10    | [C7702426F249](<Notebook/Dell/Latitude/Latitude 5590/C7702426F249>) |
| Intel      | Core i7-8665U                    | 1.90 | 10    | [4AA6713C450D](<Notebook/Dell/Latitude/Latitude 7300/4AA6713C450D>) |
| Intel      | Xeon E-2224                      | 3.40 | 10    | [8ADCB2DEFF43](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/8ADCB2DEFF43>) |
| Intel      | Core i7-9700K                    | 3.60 | 10    | [0B8E30771563](<Desktop/Gigabyte Technology/Z390/Z390 UD/0B8E30771563>) |
| Intel      | Celeron 847                      | 1.10 | 10    | [03AE41FF2676](<Desktop/ASUSTek Computer/C8/C8HM70-I-HDMI/03AE41FF2676>) |
| Intel      | Core i5-2320                     | 3.00 | 10    | [991490F8B248](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/991490F8B248>) |
| Intel      | Core i5-2410M                    | 2.30 | 10    | [3FAF9A510F7E](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/3FAF9A510F7E>) |
| Intel      | Core i7-3630QM                   | 2.40 | 10    | [4DF0035923F6](<All In One/Sony/SVL2412/SVL2412Z1EB/4DF0035923F6>) |
| Intel      | Core i7-4500U                    | 1.80 | 10    | [E8F5780120BE](<Notebook/Dell/Inspiron/Inspiron 7437/E8F5780120BE>) |
| Intel      | Pentium J3710                    | 1.60 | 10    | [CBD906C03555](<Desktop/Protectli/FW4/FW4C/CBD906C03555>) |
| Intel      | Atom C2750                       | 2.40 | 10    | [3725A0512D11](<Mini Pc/Supermicro/A1/A1SAi/3725A0512D11>) |
| Intel      | Core i3-6100U                    | 2.30 | 10    | [1279B1AC4E76](<Notebook/Gigabyte Technology/GB-BSi3/GB-BSi3A-6100/1279B1AC4E76>) |
| Intel      | Celeron J3355                    | 2.00 | 10    | [19E0C45EF6F5](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5>) |
| Intel      | Celeron G3900                    | 2.80 | 10    | [D5B0B257B774](<Desktop/ASRock/H110/H110M-ITX/D5B0B257B774>) |
| Intel      | Core i3-6100T                    | 3.20 | 10    | [E5BBD8484B41](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41>) |
| Intel      | Core i5-6600                     | 3.30 | 10    | [641267472D3E](<Desktop/Dell/OptiPlex/OptiPlex 5040/641267472D3E>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 10    | [1E96694D224A](<Notebook/MSI/GE62/GE62 6QC/1E96694D224A>) |
| Intel      | Xeon E3-1220 v5                  | 3.00 | 10    | [EE1C3178D933](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML30 Gen9/EE1C3178D933>) |
| AMD        | Phenom II X4 965                 |      | 9     | [744AC1B0247E](<Desktop/ASUSTek Computer/Crosshair/Crosshair IV Formula/744AC1B0247E>) |
| AMD        | GX-420MC SOC                     |      | 9     | [C50E8EC41318](<Desktop/Deciso/Netboard/Netboard A10 GEN2 Model G/C50E8EC41318>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 9     | [D2F4997BDC50](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ALC05 82LN/D2F4997BDC50>) |
| AMD        | Ryzen 3 3100 4-Core              |      | 9     | [E61B38FEC56C](<Desktop/ASRock/AB350M/AB350M Pro4-F/E61B38FEC56C>) |
| Intel      | Celeron N4000                    | 1.10 | 9     | [238192324C8D](<Desktop/Others/Others/Others/238192324C8D>) |
| Intel      | Core i7-1065G7                   | 1.30 | 9     | [5C5CB03A3738](<Tablet/Microsoft/Surface/Surface Pro 7/5C5CB03A3738>) |
| Intel      | Core i7-7600U                    | 2.80 | 9     | [D1B32CCBB59E](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HMS04P00/D1B32CCBB59E>) |
| Intel      | Core i5-8400T                    | 1.70 | 9     | [28E5E7D47C76](<Desktop/Dell/OptiPlex/OptiPlex 3060/28E5E7D47C76>) |
| Intel      | Core i5-8500T                    | 2.10 | 9     | [21D0AA739B48](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G4 DM/21D0AA739B48>) |
| Intel      | Core i5-9400                     | 2.90 | 9     | [B1655A8348EC](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 9     | [397F866BA692](<Notebook/Lenovo/ThinkPad/ThinkPad T470p 20J7S0BR00/397F866BA692>) |
| Intel      | Xeon E3-1220 v6                  | 3.00 | 9     | [013B4CDFD8CC](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 9     | [FC30D7A61B36](<Notebook/Lenovo/ThinkPad/ThinkPad X200 74591P0/FC30D7A61B36>) |
| Intel      | Xeon E5506                       | 2.13 | 9     | [E66E2D232A52](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/E66E2D232A52>) |
| Intel      | Xeon X3450                       | 2.67 | 9     | [79B0CE18B98F](<Server/Intel/S3420/S3420GP/79B0CE18B98F>) |
| Intel      | Genuine CPU                      |      | 9     | [53CC7CFA1A08](<Notebook/Samsung Electronics/Q430/Q430-Q530/53CC7CFA1A08>) |
| Intel      | Core i5-2430M                    | 2.40 | 9     | [025B1A353D7F](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/025B1A353D7F>) |
| Intel      | Celeron N2840                    | 2.16 | 9     | [EBB04AD5722C](<Notebook/Lenovo/G50-30/G50-30 80G0/EBB04AD5722C>) |
| Intel      | Atom E3826                       | 1.46 | 9     | [6744EE7F5532](<Mini Pc/Sophos/SG/SG/6744EE7F5532>) |
| Intel      | Core i3-3227U                    | 1.90 | 9     | [875F73879468](<Mini Pc/ZOTAC/ZBOX-ID42/ZBOX-ID42-BE/875F73879468>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
|            | Module SODIMM                | 4 GB     | DDR3 | 1333 | 133   | [F147F7B5D3C5](<Notebook/Panasonic/CF-53/CF-53AAGHYDM/F147F7B5D3C5>) |
|            | 123456789012345678 DIMM      | 4 GB     | DDR4 | 2400 | 129   | [9EF0E5CE8350](<Mini Pc/BESSTAR Tech/GK/GK41/9EF0E5CE8350>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 83    | [54266AFBE61A](<Desktop/Intel/SHARKBAY/SHARKBAY/54266AFBE61A>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 70    | [F44B66C9B720](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/F44B66C9B720>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 56    | [93E8E996FA3C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAS0UT00/93E8E996FA3C>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 54    | [0D6CEE283756](<Desktop/Others/Others/Others/0D6CEE283756>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 53    | [BD1A816BB8CA](<Desktop/MSI/MS/MS-7788/BD1A816BB8CA>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 50    | [AD483E0D64C3](<Notebook/Acer/V5/V5-131/AD483E0D64C3>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 48    | [008D25A435CA](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/008D25A435CA>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 47    | [3E0BFFE82927](<Notebook/Fujitsu Siemens/AMILO/AMILO Li3710/3E0BFFE82927>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 46    | [96D8FD49C0BC](<Desktop/ASUSTek Computer/P5K/P5K SE-EPU/96D8FD49C0BC>) |
|            | Module(s) DIMM               | 4 GB     |      |      | 46    | [5C0556A6AFDF](<Desktop/ADI Engineering/RCC-VE/RCC-VE/5C0556A6AFDF>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1867 | 40    | [6FBB1F806232](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/6FBB1F806232>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1600 | 39    | [C40A237C6EFF](<Server/Supermicro/X10/X10SLH-N6-ST031/C40A237C6EFF>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 39    | [427EC7AA7E9D](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/427EC7AA7E9D>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 38    | [0BE9EF1D92A6](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/0BE9EF1D92A6>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 38    | [1A21E5A60999](<Desktop/Fujitsu/FUTRO/FUTRO S920/1A21E5A60999>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 35    | [970BC5F94457](<Desktop/Gigabyte Technology/GA-880/GA-880GM-USB3/970BC5F94457>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 34    | [1E96694D224A](<Notebook/MSI/GE62/GE62 6QC/1E96694D224A>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 33    | [4BA15FF3127D](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/4BA15FF3127D>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 33    | [AAE762B30C9B](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0TT1N/AAE762B30C9B>) |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 2667 | 33    | [E613798C5600](<Desktop/Hardkernel/ODROID-H/ODROID-H3/E613798C5600>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 32    | [2507D5CBA552](<Desktop/Lenovo/ThinkStation/ThinkStation E32 30A1000SUS/2507D5CBA552>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 32    | [31A33F545802](<Desktop/Fujitsu/FMVW77/FMVW77MB/31A33F545802>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 32    | [1396938A5877](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3626WNP/1396938A5877>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 31    | [BABAA8FE0078](<Notebook/Others/Others/Others/BABAA8FE0078>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1600 | 30    | [CBB2B6C4BB30](<System On Chip/SiComputer/Embedded/Embedded/CBB2B6C4BB30>) |
|            | Module                       | 8 GB     |      | 1600 | 30    | [D6B753657A49](<Desktop/Protectli/FW4/FW4B/D6B753657A49>) |
| Transcend  | TS1GLH64V6BL SODIMM          | 8 GB     | DDR4 | 2667 | 30    | [051064EC5D5D](<Notebook/Deciso/NetBoard-A/NetBoard-A10/051064EC5D5D>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 29    | [8D46EE05F6A4](<Notebook/Dell/Inspiron/Inspiron 3421/8D46EE05F6A4>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 29    | [CD2E2E09A918](<Desktop/ASRock/G31/G31M-S/CD2E2E09A918>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 29    | [AE8B668C53BF](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AW008PUK/AE8B668C53BF>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3200 | 28    | [2C34712FE131](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 28    | [47DA8A08488F](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4242PN3/47DA8A08488F>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 27    | [F22A05D6ABEA](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F22A05D6ABEA>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 27    | [1A9E9336AA29](<Desktop/Others/Others/Others/1A9E9336AA29>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 26    | [904B5AD84383](<Notebook/Hewlett-Packard/Pavilion/Pavilion TS Sleekbook 14/904B5AD84383>) |
| Micron     | 8KTF51264HZ-1G9P1 SODIMM     | 4 GB     | DDR3 | 1867 | 25    | [B0451E2BD475](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/B0451E2BD475>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 25    | [CD2E2E09A918](<Desktop/ASRock/G31/G31M-S/CD2E2E09A918>) |
| Samsung    | M471B1G73DB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 25    | [5317E70D06CC](<Mini Pc/AMI/Aptio/Aptio CRB/5317E70D06CC>) |
| Kimtigo    | KT8GS3EDF SODIMM             | 8 GB     | DDR3 | 1600 | 24    | [07E9F2DE21F0](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/07E9F2DE21F0>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 24    | [142A4346F311](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F18/142A4346F311>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 24    | [2507D5CBA552](<Desktop/Lenovo/ThinkStation/ThinkStation E32 30A1000SUS/2507D5CBA552>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 8 GB     | DDR3 | 1600 | 24    | [6555DD747575](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4270CTO/6555DD747575>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 23    | [16DE1B8D4A3E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000YMX/16DE1B8D4A3E>) |
| SK hynix   | HMT451U6BFR8A-PB DIMM        | 4 GB     | DDR3 | 1600 | 23    | [6AC7605DC636](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/6AC7605DC636>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 23    | [892B0188C626](<Desktop/Datto/SSD/SSD/892B0188C626>) |
| Samsung    | M471B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 23    | [36EC70330593](<Desktop/Protectli/FW4/FW4C/36EC70330593>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 23    | [129B039C5617](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S5Q507/129B039C5617>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 667  | 22    | [B8D7D8366BA0](<Desktop/PC Engines/apu/apu4/B8D7D8366BA0>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 22    | [D6765403633D](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/D6765403633D>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 22    | [777704B959E8](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Extreme 20MF000QUS/777704B959E8>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 22    | [6EF6C3723B2F](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4243F39/6EF6C3723B2F>) |
| Crucial    | CT102464BF160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 21    | [55A5595258A6](<Desktop/Protectli/FW4/FW4B/55A5595258A6>) |
| Crucial    | CT102464BF160B.M16 DIMM      | 8 GB     | DDR3 | 1600 | 21    | [E04B0718D9FE](<Desktop/CNCTION-IAF-E3845/Others/Others/E04B0718D9FE>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 21    | [13CC6AC4B4CE](<Notebook/Lenovo/IdeaPad/IdeaPad 3 14ITL05 81X7/13CC6AC4B4CE>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 800  | 20    | [38971379B55D](<Desktop/Others/Others/Others/38971379B55D>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     |      | 1333 | 20    | [DD7F4E7F628C](<Notebook/Toshiba/Satellite/Satellite L675D/DD7F4E7F628C>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 19    | [970BC5F94457](<Desktop/Gigabyte Technology/GA-880/GA-880GM-USB3/970BC5F94457>) |
| Samsung    | M393B1G70QH0-YK0 DIMM        | 8192 MB  | DDR3 | 1600 | 19    | [2173A116CDDD](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 19    | [CC5F553B231D](<Notebook/Lenovo/ThinkPad/ThinkPad L590 20Q7U04602/CC5F553B231D>) |
| Samsung    | M471B5173QH0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 19    | [D37DD9A17A3E](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/D37DD9A17A3E>) |
| SK hynix   | HMT451U6BFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 18    | [295D902A3E56](<Desktop/Dell/OptiPlex/OptiPlex 3020/295D902A3E56>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 2667 | 18    | [ECF1DB67DC0F](<Desktop/Komplett/PC/PC/ECF1DB67DC0F>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 18    | [C180CD7578A7](<Desktop/Fujitsu/FUTRO/FUTRO S920/C180CD7578A7>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 18    | [3011E271D386](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/3011E271D386>) |
| SK hynix   | HMT351U6EFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 17    | [22A8E9290A87](<Desktop/Lenovo/ThinkStation/ThinkStation E31 25524E5/22A8E9290A87>) |
| Kingston   | 99U5469-045.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 17    | [8195211210A2](<Mini Pc/AMI/Aptio/Aptio CRB/8195211210A2>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 17    | [6115A1403193](<Notebook/Others/Others/Others/6115A1403193>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 17    | [0BE9EF1D92A6](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/0BE9EF1D92A6>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 667  | 17    | [8E702FFCE116](<Desktop/ASUSTek Computer/P5E-VM/P5E-VM SE/8E702FFCE116>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 800  | 17    | [620A9A129299](<Desktop/CheckPoint/T-110/T-110-00/620A9A129299>) |
|            | Module SODIMM                | 8 GB     | DDR3 | 1600 | 17    | [0189D3C3009B](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B>) |
| Samsung    | M391B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 17    | [E59BEB3D3EFB](<Desktop/ASRockRack/C226M/C226M WS/E59BEB3D3EFB>) |
| Samsung    | M393A2G40DB0-CPB DIMM        | 16 GB    | DDR4 | 2133 | 17    | [26A500B3E26E](<Desktop/Supermicro/SYS-E200/SYS-E200-9A/26A500B3E26E>) |
| Crucial    | CT102464BA160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 16    | [FB278EBEB515](<Desktop/Dell/Vostro/Vostro 3900/FB278EBEB515>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 16    | [4F9E73525C74](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/4F9E73525C74>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1600 | 16    | [2B5473C76A7D](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 16    | [3AE451B22603](<Desktop/iBASE/Mi/Mi956/3AE451B22603>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 1333 | 16    | [38C417FC7E84](<Desktop/PC Engines/apu/apu1/38C417FC7E84>) |
| Samsung    | M378B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 16    | [58B8C5BDE4AF](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/58B8C5BDE4AF>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1600 | 15    | [DA8417B6E571](<Desktop/MSI/MS/MS-7850/DA8417B6E571>) |
| Micron     | Module Row Of Chips LPDDR4   | 8 GB     |      | 3200 | 15    | [3A0470604DE5](<Desktop/GoWin Solution/R86/R86S/3A0470604DE5>) |
|            | Module DIMM                  | 8 GB     |      | 1333 | 15    | [45CFE4976667](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/45CFE4976667>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 15    | [6784016BD1CE](<Desktop/Hewlett-Packard/p6/p6-2105la/6784016BD1CE>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 15    | [3C84623AD933](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M60e 11LU000XAC/3C84623AD933>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 2400 | 14    | [185A7A32806D](<Desktop/Gigabyte Technology/B250M-Gaming/B250M-Gaming 3/185A7A32806D>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 14    | [5760D7831E6B](<Desktop/Gigabyte Technology/M52/M52L-S3P/5760D7831E6B>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 14    | [AB58D13F8BD8](<Desktop/Dell/OptiPlex/OptiPlex 780/AB58D13F8BD8>) |
| Samsung    | M471B1G73EB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 14    | [9F7173C75BFC](<Desktop/Protectli/FW4/FW4B/9F7173C75BFC>) |
| Samsung    | Module DIMM                  | 8 GB     | DDR4 | 2133 | 14    | [505624285B70](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G3 SFF/505624285B70>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 14    | [0BE715FB5F85](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/0BE715FB5F85>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 13    | [5C14E92D5780](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780>) |
| Crucial    | BLS4G3D1609DS1S00. DIMM      | 4 GB     | DDR3 | 1600 | 13    | [44F0867AF848](<Desktop/MSI/MS/MS-7851/44F0867AF848>) |
| G.Skill    | F4-2400C16-8GRS SODIMM       | 8 GB     | DDR4 | 2400 | 13    | [1C5BA913A08B](<Mini Pc/Intel/NUC7i5BNB/NUC7i5BNB J31144-305/1C5BA913A08B>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3200 | 13    | [63762628C1D4](<Desktop/MSI/MS-7/MS-7B79/63762628C1D4>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3200 | 13    | [441B708DBD6C](<Desktop/MSI/MS-7/MS-7D59/441B708DBD6C>) |
| SK hynix   | HMT325U6CFR8C-PB DIMM        | 2 GB     | DDR3 | 1600 | 13    | [188D1EFAA755](<Desktop/Dell/OptiPlex/OptiPlex 7020/188D1EFAA755>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 13    | [9343098F3B9C](<Notebook/Google/Peppy/Peppy/9343098F3B9C>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 13    | [E8819DE1DB7B](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 13    | [35B6BE9BC592](<Notebook/Lenovo/ThinkPad/ThinkPad T61 7659CA1/35B6BE9BC592>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 13    | [DD5639A44B24](<Desktop/ASUSTek Computer/M4/M4A78/DD5639A44B24>) |
| Samsung    | M378B5273CH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 13    | [1E88E6C2C003](<Desktop/Dell/OptiPlex/OptiPlex 9010/1E88E6C2C003>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 13    | [A2EECE4A8548](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/A2EECE4A8548>) |
| Crucial    | CT16G4SFD824A.C16FDD SODIMM  | 16 GB    | DDR4 | 2400 | 12    | [A81E6D09A273](<Desktop/Others/Others/Others/A81E6D09A273>) |
| Crucial    | CT4G4SFS824A.C8FF SODIMM     | 4 GB     | DDR4 | 2666 | 12    | [28E40DCE07F1](<Desktop/Others/Others/Others/28E40DCE07F1>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 12    | [4A02B8E7AE26](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23255NG/4A02B8E7AE26>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 12    | [AD05D1EEF352](<Notebook/Lenovo/ThinkPad/ThinkPad T540p 20BFS10W03/AD05D1EEF352>) |
| Kingston   | 99U5428-018.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 12    | [D030347326A1](<Desktop/Protectli/FW4/FW4B/D030347326A1>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 12    | [45F75AF4170E](<Desktop/Gigabyte Technology/H81/H81M-H/45F75AF4170E>) |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     |      | 1333 | 12    | [C76736734DEA](<Desktop/Dell/Studio/Studio XPS 7100/C76736734DEA>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 12    | [0993E73A2A97](<Notebook/Acer/Swift/Swift SF314-56/0993E73A2A97>) |
| Micron     | 8ATF1G64HZ-3G2R1 SODIMM      | 8 GB     | DDR4 | 3200 | 12    | [95C452956946](<Mini Pc/AZW/SER/SER/95C452956946>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 800  | 12    | [9909AA40BD35](<Desktop/Hewlett-Packard/Compaq/Compaq dx2200 MT/9909AA40BD35>) |
|            | Module DIMM SDRAM            | 4 GB     |      |      | 12    | [51FDE28C136B](<Desktop/Others/Others/Others/51FDE28C136B>) |
| Samsung    | M378B1G73DB0-CK0 DIMM        | 8 GB     | DDR3 | 1600 | 12    | [A48813D91C55](<Desktop/ASUSTek Computer/M5A97/M5A97 PLUS/A48813D91C55>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2133 | 12    | [6F011113499A](<Desktop/Others/Others/Others/6F011113499A>) |
| SK hynix   | HMA451U6AFR8N-TF DIMM        | 4 GB     | DDR4 | 2133 | 12    | [D34CBCF72E47](<Desktop/Dell/OptiPlex/OptiPlex 7040/D34CBCF72E47>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 12    | [09CD68C8BFFB](<Desktop/Dell/OptiPlex/OptiPlex 7060/09CD68C8BFFB>) |
| SK hynix   | HMA81GU6AFR8N-UH DIMM        | 8 GB     | DDR4 | 2400 | 12    | [60AB8F278277](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 12    | [80B2435E242F](<Desktop/Techvision/TVI7309/TVI7309X/80B2435E242F>) |
| Super T... | SUPERTALENT02 DIMM           | 4 GB     | DDR3 | 1600 | 12    | [326C5B4DA0B2](<Desktop/Equus Computer Systems/Nobilis/Nobilis/326C5B4DA0B2>) |
| A-DATA     | Module DIMM                  | 4 GB     | DDR4 | 1866 | 11    | [A69CDBD127C3](<Firewall/Sophos/SG/SG/A69CDBD127C3>) |
| Corsair    | CMK32GX4M2A2666C16 DIMM      | 16 GB    | DDR4 | 3000 | 11    | [8AE8FFB5342F](<Desktop/ASRock/B450/B450 Steel Legend/8AE8FFB5342F>) |
| Corsair    | CML8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 11    | [584D4BE57ECB](<Desktop/ASUSTek Computer/H110I-PLUS/H110I-PLUS D3/584D4BE57ECB>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 11    | [8ADBA957E4CE](<Desktop/Fujitsu/FUTRO/FUTRO S920/8ADBA957E4CE>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1334 | 11    | [3FAF9A510F7E](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/3FAF9A510F7E>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 11    | [B34B31EC74C2](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 USDT/B34B31EC74C2>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3200 | 11    | [D4F85CE4A0A4](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO WIFI/D4F85CE4A0A4>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 11    | [9A0A4A699834](<Notebook/Panasonic/CF-30/CF-30KAPAXAM/9A0A4A699834>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 11    | [E865EFD8EF3C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7003HUS/E865EFD8EF3C>) |
| Samsung    | M378B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 11    | [B5B98FF1F16A](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/B5B98FF1F16A>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 11    | [2512BEDDF249](<Desktop/Dell/OptiPlex/OptiPlex 3020/2512BEDDF249>) |
| Samsung    | M391A2K43BB1-CTD DIMM        | 16 GB    | DDR4 | 3200 | 11    | [B5598C1C1101](<Server/Gigabyte Technology/MX31/MX31-BS0/B5598C1C1101>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 11    | [568B35CB6B3E](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 82MS/568B35CB6B3E>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 11    | [AA49891CA91A](<Desktop/Others/HX/HX90/AA49891CA91A>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 11    | [1B4FDBE8C755](<Desktop/Others/Others/Others/1B4FDBE8C755>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 11    | [484652E02452](<Desktop/Protectli/FW/FW6/484652E02452>) |
| Samsung    | Module DIMM                  | 4 GB     | DDR4 | 2133 | 11    | [E4163FD1A0E2](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G4 SFF/E4163FD1A0E2>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 11    | [27B57CFF23E1](<Desktop/Techvision/TVI7309/TVI7309X/27B57CFF23E1>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 11    | [A27F623F9015](<Notebook/Dell/Precision/Precision 7720/A27F623F9015>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 11    | [E6B678FB89BC](<Notebook/Dell/Precision/Precision M4500/E6B678FB89BC>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 32 GB    | DDR4 | 3200 | 11    | [A701CB00EA19](<Desktop/ASUSTek Computer/P10S-E/P10S-E Series/A701CB00EA19>) |
| Transcend  | TS1GLH64V6B3 SODIMM          | 8 GB     | DDR4 | 1333 | 11    | [5690A52166B9](<Notebook/Deciso/Netboard/Netboard A20/5690A52166B9>) |
| A-DATA     | Module SODIMM                | 4 GB     | DDR3 | 1600 | 10    | [F3E9F6363666](<Firewall/Sophos/SG/SG/F3E9F6363666>) |
|            | 123456789012345678 SODIMM... | 4 GB     |      | 2133 | 10    | [969ADE3929EE](<Notebook/Chuwi/Others/Others/969ADE3929EE>) |
| Corsair    | CMZ16GX3M2A1600C10 DIMM      | 8 GB     | DDR3 | 1600 | 10    | [2447DC6632F6](<Desktop/MSI/MS/MS-7923/2447DC6632F6>) |
| Crucial    | CT16G4SFRA266.M16FRS SODIMM  | 16 GB    | DDR4 | 2667 | 10    | [C27B3124C077](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L7002CUS/C27B3124C077>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 10    | [A2FE41ACF78C](<Desktop/Dell/OptiPlex/OptiPlex 7010/A2FE41ACF78C>) |
| Crucial    | CT51264BF160BJ.C8F SODIMM    | 4 GB     | DDR3 | 1600 | 10    | [B2D974E7849B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 10    | [CF46071DFEB6](<Desktop/Fujitsu/FUTRO/FUTRO S920/CF46071DFEB6>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 10    | [427EC7AA7E9D](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/427EC7AA7E9D>) |
| Kingston   | KF3200C16D4/16GX DIMM        | 16 GB    | DDR4 | 3200 | 10    | [BD8BD7D4DA30](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30>) |
| Kingston   | KHX1600C9S3L/4G SODIMM       | 4 GB     | DDR3 | 1600 | 10    | [BF425CFC0EFE](<Desktop/Gigabyte Technology/GB-BXi7/GB-BXi7-5775R/BF425CFC0EFE>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 10    | [822DD2DA99EA](<Notebook/Dell/Latitude/Latitude 5591/822DD2DA99EA>) |
| Ramaxel    | RMR5030MN68F9F1600 DIMM      | 4 GB     | DDR3 | 1600 | 10    | [DFDBA5E1859E](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 10    | [AD023293EF8F](<Notebook/Lenovo/G400s/G400s 20244/AD023293EF8F>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 10    | [71D6760A716E](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/71D6760A716E>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 10    | [729EE71A6DC0](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E700/729EE71A6DC0>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 10    | [4FC1EF03B793](<Notebook/ASUSTek Computer/K501/K501UQ/4FC1EF03B793>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 10    | [AEDD8EECA9D9](<Desktop/Others/Others/Others/AEDD8EECA9D9>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM      | 2 GB     | DDR2 | 975  | 10    | [0D2F6FFDCD3E](<Notebook/Dell/Studio/Studio 1537/0D2F6FFDCD3E>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 9     | [044194CF0302](<Notebook/Samsung Electronics/N150/N150-N210-N220/044194CF0302>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3000 | 9     | [A058A7EF96C1](<Desktop/MSI/MS-7/MS-7C87/A058A7EF96C1>) |
| Corsair    | CMX8GX3M2A1333C9 DIMM        | 4 GB     | DDR3 | 1333 | 9     | [4E328D0D3327](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/4E328D0D3327>) |
| Crucial    | CT8G4SFRA32A.M4FF SODIMM     | 8 GB     | DDR4 | 3200 | 9     | [FD57BFFDB0F8](<Desktop/Others/Others/Others/FD57BFFDB0F8>) |
| Crucial    | CT8G4SFS824A.C8FP SODIMM     | 8 GB     | DDR4 | 2400 | 9     | [4918EE420737](<Desktop/Protectli/VP/VP2410/4918EE420737>) |
|            | DDR4 NB 8G 2400 SODIMM       | 8 GB     | DDR4 | 2133 | 9     | [C7E99520D0C2](<Desktop/AZW/GK/GK55/C7E99520D0C2>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 9     | [15AC08F3D214](<Desktop/Gigabyte Technology/Z87/Z87X-UD4H/15AC08F3D214>) |
| Kingston   | CBD26D4S9S8K1C-8 SODIMM      | 8 GB     | DDR4 | 2667 | 9     | [355A9EB4D1D7](<Desktop/Others/Others/Others/355A9EB4D1D7>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 9     | [C8D336657732](<Notebook/Dell/Inspiron/Inspiron 5558/C8D336657732>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 9     | [2805CF1FB3D9](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4001PUS/2805CF1FB3D9>) |
| Micron     | 8ATF1G64AZ-2G6E1 DIMM        | 8 GB     | DDR4 | 2667 | 9     | [E0AD4EAE27C2](<Desktop/Dell/OptiPlex/OptiPlex 3060/E0AD4EAE27C2>) |
| Micron     | 9ASF1G72AZ-2G3B1 DIMM        | 8 GB     | DDR4 | 2400 | 9     | [A0E6ECE7A60C](<Desktop/Dell/PowerEdge/PowerEdge T30/A0E6ECE7A60C>) |
| Micron     | Module DIMM                  | 2 GB     | DDR3 | 1333 | 9     | [B1EAE5C24DD5](<Desktop/Supermicro/C7/C7SIM-Q/B1EAE5C24DD5>) |
|            | Module SODIMM                | 1 GB     | DDR2 |      | 9     | [F8A3C017EE1C](<Notebook/LG Electronics/E500/E500-L.A2M4A2/F8A3C017EE1C>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 9     | [3A7D355EEBE4](<Notebook/Pegatron/T12/T12Ah/3A7D355EEBE4>) |
|            | Module DIMM                  | 2 GB     | DDR2 |      | 9     | [58461932D03F](<Desktop/ASUSTek Computer/P5/P5BV-E/58461932D03F>) |
|            | Module DIMM                  | 4 GB     |      | 1600 | 9     | [BB62608DEE46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/BB62608DEE46>) |
|            | Module FB-DIMM               | 4 GB     | DDR2 | 667  | 9     | [FFA4A8B12A92](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92>) |
|            | Module DIMM                  | 4 GB     | DDR2 | 800  | 9     | [2E3CE84B8F4E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58 7360EUU/2E3CE84B8F4E>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 800  | 9     | [EDCF6BFE74C6](<Desktop/Others/Others/Others/EDCF6BFE74C6>) |
|            | Module(s) DIMM               | 8 GB     |      |      | 9     | [85EA4DD31903](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/85EA4DD31903>) |
| Samsung    | M471B1G73DH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 9     | [A3DBD4D871FE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 9     | [269B716399A8](<Notebook/Lenovo/B590/B590 20208/269B716399A8>) |
| Samsung    | M471B5173DB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 9     | [A922120AB5BC](<Desktop/Protectli/FW4/FW4B/A922120AB5BC>) |
| Samsung    | M471B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 9     | [0A17E5D0481E](<Desktop/Protectli/FW4/FW4C/0A17E5D0481E>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 9     | [FC30D7A61B36](<Notebook/Lenovo/ThinkPad/ThinkPad X200 74591P0/FC30D7A61B36>) |
| Samsung    | Module SODIMM                | 2 GB     | DDR3 | 1067 | 9     | [963B07D38FEF](<Notebook/Apple/MacBookPro5/MacBookPro5,1/963B07D38FEF>) |
| SK hynix   | HMA41GU6AFR8N-TF DIMM        | 8 GB     | DDR4 | 2133 | 9     | [068FD2492251](<Desktop/Dell/OptiPlex/OptiPlex 7040/068FD2492251>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2400 | 9     | [DA2700E6778C](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C>) |
| SK hynix   | HMT351U7BFR8A-H9 DIMM        | 4 GB     | DDR3 | 1333 | 9     | [71ACCE4AED93](<Desktop/Dell/Precision/Precision WorkStation T3500/71ACCE4AED93>) |
| Corsair    | CMV4GX3M1A1333C9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [A72462873DBB](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB>) |
| Crucial    | CT51264BF160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 8     | [8FD132FDB61B](<Desktop/Protectli/FW4/FW4B/8FD132FDB61B>) |
| Crucial    | CT8G4SFRA266.C8FE SODIMM     | 8 GB     | DDR4 | 2667 | 8     | [656127D6D11E](<Desktop/Protectli/VP/VP2410/656127D6D11E>) |
| G.Skill    | F3-1600C9-8GRSL SODIMM       | 8 GB     | DDR3 | 1600 | 8     | [FEAC2384E90C](<Desktop/Fujitsu/FUTRO/FUTRO S920/FEAC2384E90C>) |
| G.Skill    | F4-2400C16-4GRS SODIMM       | 4 GB     | DDR4 | 2400 | 8     | [F914C37F4CEB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/F914C37F4CEB>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3000 | 8     | [82CE853FF0D7](<Desktop/ASRock/B460/B460M-HDV/82CE853FF0D7>) |
| SK hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [711AEC50914C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/711AEC50914C>) |
| Kingston   | 9965745-002.A00G DIMM        | 16 GB    | DDR4 | 3000 | 8     | [69AAAA30BEFA](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 8     | [D59156C0581D](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C720/D59156C0581D>) |
| Kingston   | 99U5700-028.A00G SODIMM      | 8 GB     | DDR4 | 2400 | 8     | [0108DB586B13](<Desktop/Yanling/YL-KBR6/YL-KBR6L/0108DB586B13>) |
| Kingston   | KHX2400C14S4/16G SODIMM      | 16 GB    | DDR4 | 2400 | 8     | [722F4261A23A](<Desktop/Others/Others/Others/722F4261A23A>) |
| Kingston   | KNWMX1-ETB SODIMM            | 4 GB     | DDR3 | 1600 | 8     | [1ED960B9F220](<Notebook/Dell/Inspiron/Inspiron 15-3552/1ED960B9F220>) |
| Micron     | 18KSF1G72AZ-1G6E1 DIMM       | 8 GB     | DDR3 | 1600 | 8     | [1E9D45F9BBB9](<Server/Supermicro/X10/X10SLH-N6-ST031/1E9D45F9BBB9>) |
| Micron     | 18KSF1G72AZ-1G6P1 DIMM       | 8 GB     | DDR3 | 1600 | 8     | [C306D0A87402](<Server/Dell/PowerEdge/PowerEdge R220/C306D0A87402>) |
| Micron     | 36ASF2G72PZ-2G1A2 DIMM       | 16 GB    | DDR4 | 2133 | 8     | [01583CC46F7E](<Server/Supermicro/Super/Super Server/01583CC46F7E>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 8     | [5D866F2C859D](<Desktop/Others/Others/Others/5D866F2C859D>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 8     | [6FD7DBD4591D](<Desktop/Others/Others/Others/6FD7DBD4591D>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 8     | [83961A908C73](<Notebook/Acer/Aspire/Aspire 5742/83961A908C73>) |
| Nanya      | NT4GC64B8HG0NF-DI DIMM       | 4 GB     | DDR3 | 1600 | 8     | [ECCDB090F800](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3209D9U/ECCDB090F800>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 667  | 8     | [A098A01ACD0B](<Desktop/Intel/DG41TY/DG41TY AAE47335-300/A098A01ACD0B>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1066 | 8     | [4FE486AA9D43](<Desktop/Intel/D2500HN/D2500HN AAG81480-500/4FE486AA9D43>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1600 | 8     | [76E8E3B1FF36](<Desktop/Gigabyte Technology/F2/F2A55-DS3/76E8E3B1FF36>) |
|            | Module DIMM                  | 2 GB     |      |      | 8     | [B132F7D469BF](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-BR/B132F7D469BF>) |
|            | Module DIMM                  | 8 GB     | DDR4 | 2400 | 8     | [3D854A7B1556](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556>) |
| Ramaxel    | RMR5030EF68F9W1600 DIMM      | 4 GB     | DDR3 | 1600 | 8     | [BF32CF4AE8C8](<Desktop/Lenovo/H515/H515 10125/BF32CF4AE8C8>) |
| Ramaxel    | RMR5040ED58E9W1600 DIMM      | 4 GB     | DDR3 | 1600 | 8     | [9A6BFC6540AF](<Desktop/Hewlett-Packard/p7/p7-1154/9A6BFC6540AF>) |
| Samsung    | M378A1K43CB2-CRC DIMM        | 8 GB     | DDR4 | 2400 | 8     | [68608DB16288](<Desktop/Lenovo/ThinkCentre/ThinkCentre M710s 10M8S0FW00/68608DB16288>) |
| Samsung    | M378A5244CB0-CRC DIMM        | 4 GB     | DDR4 | 2666 | 8     | [0138F543D0DE](<Desktop/Lenovo/V520S-08IKL/V520S-08IKL Desktop 10NNS04A00/0138F543D0DE>) |
| Samsung    | M378B5173EB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [AE1164BF35BB](<Desktop/Dell/OptiPlex/OptiPlex 3020/AE1164BF35BB>) |
| Samsung    | M391B5273CH0-YH9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [58573A8F2438](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438>) |
| Samsung    | M391B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [509895109D80](<Desktop/Supermicro/X9/X9SCL-X9SCM/509895109D80>) |
| Samsung    | M391B5273DH0-YH9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [0338EE9299EB](<Server/Fujitsu/PRIMERGY/PRIMERGY RX100 S7/0338EE9299EB>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2400 | 8     | [CAE76C99B2A2](<Notebook/Lenovo/ThinkPad/ThinkPad T470 W10DG 20JNS02000/CAE76C99B2A2>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 8     | [E2372EFC6D66](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 8     | [32F9A01194D0](<Notebook/Hewlett-Packard/Notebook/Notebook/32F9A01194D0>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 8     | [79AF40064822](<Notebook/Acer/Aspire/Aspire 7738/79AF40064822>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 8     | [C601B6CDC429](<Notebook/Shuttle/DS/DS437T/C601B6CDC429>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 8     | [A24B1BCD0AFA](<Desktop/Fujitsu/D3313/D3313-S3/A24B1BCD0AFA>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 8     | [36F11B0BD1E3](<Desktop/Others/Others/Others/36F11B0BD1E3>) |
| SK hynix   | HMA81GU6JJR8N-VK DIMM        | 8 GB     | DDR4 | 2667 | 8     | [6BC81BE1C8AC](<Desktop/Dell/OptiPlex/OptiPlex 7060/6BC81BE1C8AC>) |
| SK hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 8     | [499FE3F2614A](<Mini Pc/Intel Client Systems/NUC8/NUC8i7HVK/499FE3F2614A>) |
| SK hynix   | HMA851S6DJR6N-XN SODIMM      | 4 GB     | DDR4 | 3200 | 8     | [D576894A0B1E](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/D576894A0B1E>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 8     | [70007FC12D79](<Desktop/Acer/Aspire/Aspire XC-830-UW90/70007FC12D79>) |
| SK hynix   | Module SODIMM                | 2 GB     | DDR3 | 1600 | 8     | [D33FDFE25C32](<Notebook/Apple/MacBookAir5/MacBookAir5,1/D33FDFE25C32>) |
| Transcend  | TS1GLK72V6H DIMM             | 8 GB     | DDR3 | 1600 | 8     | [C4A6ABA0D4AF](<Desktop/Intel/DENLOW_WS/DENLOW_WS/C4A6ABA0D4AF>) |
|            | BRBN1G48G16C2666 SODIMM      | 8 GB     | DDR4 | 2400 | 7     | [F6BD223DB78D](<Desktop/Others/Others/Others/F6BD223DB78D>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3200 | 7     | [C0F6B83E60A9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9>) |
| Crucial    | CT51264BF160BJ.M8F DIMM      | 4 GB     | DDR3 | 1600 | 7     | [A4D89EA96DC4](<Server/Supermicro/Super/Super Server/A4D89EA96DC4>) |
| Crucial    | CT51264BF160BJ.M8F SODIMM    | 4 GB     | DDR3 | 1600 | 7     | [7972F62180EF](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/7972F62180EF>) |
| Crucial    | CT8G4SFRA32A.C8FN SODIMM     | 8 GB     | DDR4 | 3200 | 7     | [694F5E7E230F](<Mini Pc/BYTENUC/AZ/AZ51/694F5E7E230F>) |
| G.Skill    | F3-1600C9-8GXM DIMM          | 8 GB     | DDR3 | 1600 | 7     | [35F33329CB60](<Desktop/ASUSTek Computer/All/All Series/35F33329CB60>) |
| G.Skill    | F4-2400C16-16GRS SODIMM      | 16 GB    | DDR4 | 2400 | 7     | [92AC2C8CE893](<Notebook/Lenovo/ThinkPad/ThinkPad E595 20NF0002BM/92AC2C8CE893>) |
| G.Skill    | F4-3200C16-16GIS DIMM        | 16 GB    | DDR4 | 3200 | 7     | [B0DA7750724C](<Desktop/Gigabyte Technology/H610I/H610I DDR4/B0DA7750724C>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 7     | [284E69188279](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 7     | [A8CF95C34089](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/A8CF95C34089>) |
| SK hynix   | HMT325U6BFR8C-H9 DIMM        | 2 GB     | DDR3 | 1333 | 7     | [AC9F58576E1B](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B>) |
| SK hynix   | HMT41GU7BFR8A-PB DIMM        | 8 GB     | DDR3 | 1600 | 7     | [6D7609593826](<Server/Dell/PowerEdge/PowerEdge R220/6D7609593826>) |
| SK hynix   | Module DIMM                  | 8 GB     | DDR4 | 2133 | 7     | [C940FCA75474](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/C940FCA75474>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 43.0  |         | 41    | [FF14982AD9](https://bsd-hardware.info/?probe=ff14982ad9) |
| SANYO      | 45N1773 LION   | 23.2  |         | 28    | [4867945CFB](https://bsd-hardware.info/?probe=4867945cfb) |
| LGC        | 45N1127 LION   | 23.5  |         | 25    | [B09ACFFE7B](https://bsd-hardware.info/?probe=b09acffe7b) |
| Hewlett... | PABAS024123... | 31.1  |         | 22    | [93EA83EEF5](https://bsd-hardware.info/?probe=93ea83eef5) |
| Lenovo     | PABAS024123... | 42.8  |         | 20    | [55DC82AF1C](https://bsd-hardware.info/?probe=55dc82af1c) |
| Samsung    | Serial numb... | 48.8  |         | 19    | [EA55A6FECF](https://bsd-hardware.info/?probe=ea55a6fecf) |
| SANYO      | 45N1775 LION   | 23.2  |         | 19    | [4867945CFB](https://bsd-hardware.info/?probe=4867945cfb) |
| LGC        | 45N1113 LION   | 23.5  |         | 18    | [89A5EE25F9](https://bsd-hardware.info/?probe=89a5ee25f9) |
| OEM        | standard LiON  | 91.2  |         | 17    | [BEE20C6A4C](https://bsd-hardware.info/?probe=bee20c6a4c) |
| MSI        | BIF0_9         | 42.4  |         | 16    | [7C3FD3C9CA](https://bsd-hardware.info/?probe=7c3fd3c9ca) |
| Samsung    | SR Real LION   | 43.1  |         | 14    | [7CAED06FDB](https://bsd-hardware.info/?probe=7caed06fdb) |
| Sony       | 45N1111 LiP    | 23.2  |         | 14    | [7750C38CD0](https://bsd-hardware.info/?probe=7750c38cd0) |
| SANYO      | 45N1023 LION   | 64.1  |         | 13    | [EDF47CB2D4](https://bsd-hardware.info/?probe=edf47cb2d4) |
| SANYO      | 45N1001 LION   | 56.2  |         | 11    | [CF016CE514](https://bsd-hardware.info/?probe=cf016ce514) |
| ASUSTek    | A32-K55        | 48.0  |         | 10    | [9BAC0139F1](https://bsd-hardware.info/?probe=9bac0139f1) |
| Compal     | PABAS024123... | 86.0  |         | 10    | [1438237430](https://bsd-hardware.info/?probe=1438237430) |
| SANYO      | 42T4861 LION   | 57.7  |         | 10    | [1646BB53AB](https://bsd-hardware.info/?probe=1646bb53ab) |
| SANYO      | 45N1767 LION   | 47.5  |         | 9     | [2DF7C991F0](https://bsd-hardware.info/?probe=2df7c991f0) |
| State:	... | Serial numb... | 38.0  |         | 9     | [5E687FCC83](https://bsd-hardware.info/?probe=5e687fcc83) |
| Hewlett... | Primary LIon   | 40    |         | 8     | [464059D8B1](https://bsd-hardware.info/?probe=464059d8b1) |
| LGC        | 45N1738 LION   | 71.1  |         | 8     | [7750C38CD0](https://bsd-hardware.info/?probe=7750c38cd0) |
| Notebook   | BAT LION       | 62    |         | 8     | [64316408F0](https://bsd-hardware.info/?probe=64316408f0) |
| SANYO      | 42T4763 LION   | 84.2  |         | 8     | [94095D4C11](https://bsd-hardware.info/?probe=94095d4c11) |
| SANYO      | 92P1137 LION   | 56.2  |         | 8     | [BBA228DDC9](https://bsd-hardware.info/?probe=bba228ddc9) |
| SMP        | 01AV421 LiP    | 24.0  |         | 8     | [DD6C3FA0F7](https://bsd-hardware.info/?probe=dd6c3fa0f7) |
| Hewlett... | Primary LIon   | 42    |         | 7     | [6CC978F98F](https://bsd-hardware.info/?probe=6cc978f98f) |
| Hewlett... | Primary LIon   | 43    |         | 7     | [5807159F51](https://bsd-hardware.info/?probe=5807159f51) |
| Hewlett... | Primary LIon   | 45    |         | 7     | [C83B0DDA87](https://bsd-hardware.info/?probe=c83b0dda87) |
| Hewlett... | Primary LIon   | 56    |         | 7     | [F603E648C7](https://bsd-hardware.info/?probe=f603e648c7) |
| Lenovo ... | Serial numb... | 41.4  |         | 7     | [A52E13CF4E](https://bsd-hardware.info/?probe=a52e13cf4e) |
| LGC        | 45N1011 LION   | 93.6  |         | 7     | [9A3CBE1893](https://bsd-hardware.info/?probe=9a3cbe1893) |
| Panasonic  | AS16A5K LION   | 41.4  |         | 7     | [A8F794F3FB](https://bsd-hardware.info/?probe=a8f794f3fb) |
| SANYO      | 45N1777 LION   | 71.3  |         | 7     | [DF62882C3B](https://bsd-hardware.info/?probe=df62882c3b) |
| SANYO      | 45N1779 LION   | 99.5  |         | 7     | [34B156C20C](https://bsd-hardware.info/?probe=34b156c20c) |
| SMP        | 45N1071 LiP    | 46.0  |         | 7     | [CEC90DDD1B](https://bsd-hardware.info/?probe=cec90ddd1b) |
| Sony       | Serial numb... | 37.5  |         | 7     | [932FACD689](https://bsd-hardware.info/?probe=932facd689) |
| State:	... | Serial numb... | 45.0  |         | 7     | [FB4EEC9C34](https://bsd-hardware.info/?probe=fb4eec9c34) |
| Hewlett... | Primary LIon   | 38    |         | 6     | [80C808DE34](https://bsd-hardware.info/?probe=80c808de34) |
| Intel SR 1 | SR Real Real   | 34.2  |         | 6     | [471EFBC788](https://bsd-hardware.info/?probe=471efbc788) |
| LGC        | 45N1005 LION   | 47.5  |         | 6     | [0F001F65D2](https://bsd-hardware.info/?probe=0f001f65d2) |
| LGC        | 45N1735 LION   | 47.5  |         | 6     | [BC7585EC56](https://bsd-hardware.info/?probe=bc7585ec56) |
| Notebook   | BAT LION       | 49    |         | 6     | [8A2BBA8635](https://bsd-hardware.info/?probe=8a2bba8635) |
| Notebook   | BAT LION       | 74    |         | 6     | [17D766D55A](https://bsd-hardware.info/?probe=17d766d55a) |
| NVT        | Framewo LION   | 55.0  |         | 6     | [5D6CB039EA](https://bsd-hardware.info/?probe=5d6cb039ea) |
| SANYO      | 01AV405 LION   | 26.3  |         | 6     | [56FA0D4656](https://bsd-hardware.info/?probe=56fa0d4656) |
| SANYO      | Li_Ion_4000... | 37.0  |         | 6     | [3D62C50607](https://bsd-hardware.info/?probe=3d62c50607) |
| SMP        | 00NY493 LiP    | 90.0  |         | 6     | [D9D7368322](https://bsd-hardware.info/?probe=d9d7368322) |
| AMD Bat... |  Real Lion     | 55.4  | Li-ion  | 5     | [3D7BF4205B](https://bsd-hardware.info/?probe=3d7bf4205b) |
| Hewlett... | Serial numb... | 12.0  |         | 5     | [E0C8E95E52](https://bsd-hardware.info/?probe=e0c8e95e52) |
| LGC        | 01AV478 LiP    | 57.0  |         | 5     | [AA70F61A87](https://bsd-hardware.info/?probe=aa70f61a87) |
| LGC        | 02DL007 LiP    | 50.5  |         | 5     | [087D40BA7C](https://bsd-hardware.info/?probe=087d40ba7c) |
| LGC        | 45N1025 LION   | 57.7  |         | 5     | [3EE0F54D2F](https://bsd-hardware.info/?probe=3ee0f54d2f) |
| LGC        | AC14B8K LION   | 48.9  |         | 5     | [104C10F9B0](https://bsd-hardware.info/?probe=104c10f9b0) |
| LGC        | AP18C8K Li-Ion | 48.0  |         | 5     | [AA89C48CB7](https://bsd-hardware.info/?probe=aa89c48cb7) |
| Notebook   | BAT LION       | 35    |         | 5     | [4AC0707C49](https://bsd-hardware.info/?probe=4ac0707c49) |
| SANYO      | 00HW022 LiP    | 23.5  |         | 5     | [6C895CB96F](https://bsd-hardware.info/?probe=6c895cb96f) |
| SANYO      | 45N1769 LION   | 56.2  |         | 5     | [7463E05C88](https://bsd-hardware.info/?probe=7463e05c88) |
| SANYO      | AL12A32 LION   | 37.0  |         | 5     | [D680E0D05D](https://bsd-hardware.info/?probe=d680e0d05d) |
| SIMPLO     | PABAS024123... | 68.8  |         | 5     | [742D648570](https://bsd-hardware.info/?probe=742d648570) |
| SMP        | 01AV430 LiP    | 57.0  |         | 5     | [6D9C564A33](https://bsd-hardware.info/?probe=6d9c564a33) |
| ASUSTek    | K55--47        | 51.7  |         | 4     | [6FA29C4E4D](https://bsd-hardware.info/?probe=6fa29c4e4d) |
| Celxpert   | 01AV424 LiP    | 24.1  |         | 4     | [6D7B30D2C4](https://bsd-hardware.info/?probe=6d7b30d2c4) |
| Celxpert   | 01AY969 LiP    | 80.4  |         | 4     | [B4805CD318](https://bsd-hardware.info/?probe=b4805cd318) |
| CPT-COS    | L16C2PB2 LiP   | 30.6  |         | 4     | [C2BA6ACA7D](https://bsd-hardware.info/?probe=c2ba6aca7d) |
| DPON016    | ASMB016        | 50.2  |         | 4     | [6F2790802D](https://bsd-hardware.info/?probe=6f2790802d) |
| Hewlett... | Primary        | 48    |         | 4     | [73E328AD87](https://bsd-hardware.info/?probe=73e328ad87) |
| Hewlett... | Primary LIon   | 35    |         | 4     | [9C4BE9DEAB](https://bsd-hardware.info/?probe=9c4be9deab) |
| Hewlett... | Primary LIon   | 37    |         | 4     | [92C676E033](https://bsd-hardware.info/?probe=92c676e033) |
| Hewlett... | Primary LIon   | 46    |         | 4     | [0307C109B5](https://bsd-hardware.info/?probe=0307c109b5) |
| Hewlett... | Primary LIon   | 48    |         | 4     | [7B44E1591F](https://bsd-hardware.info/?probe=7b44e1591f) |
| LG         | PABAS024123... | 49.0  |         | 4     | [262110252B](https://bsd-hardware.info/?probe=262110252b) |
| LGC        | 00HW028 LiP    | 52.3  |         | 4     | [9C85F07244](https://bsd-hardware.info/?probe=9c85f07244) |
| LGC        | 01AV445 LiP    | 45.0  |         | 4     | [86866CE217](https://bsd-hardware.info/?probe=86866ce217) |
| LGC        | 01AV490 LiP    | 23.9  |         | 4     | [A4366E53BA](https://bsd-hardware.info/?probe=a4366e53ba) |
| LGC        | 42T4911 LION   | 56.2  |         | 4     | [51F0A87F01](https://bsd-hardware.info/?probe=51f0a87f01) |
| LGC        | 45N1029 LION   | 103.5 |         | 4     | [148A268A0F](https://bsd-hardware.info/?probe=148a268a0f) |
| LGC        | DELL 49VTP ... | 57.7  |         | 4     | [DE97E0B2FC](https://bsd-hardware.info/?probe=de97e0b2fc) |
| Notebook   | BAT LION       | 60    |         | 4     | [9A62677EA8](https://bsd-hardware.info/?probe=9a62677ea8) |
| OEM        | FX50442        | 48.0  |         | 4     | [F8C10BF25A](https://bsd-hardware.info/?probe=f8c10bf25a) |
| Samsung... | DELL P8TC72... | 33.3  |         | 4     | [A776EBF7F4](https://bsd-hardware.info/?probe=a776ebf7f4) |
| SANYO      | 42T4791 LION   | 47.5  |         | 4     | [C0A6490FC8](https://bsd-hardware.info/?probe=c0a6490fc8) |
| SANYO      | 42T4799 LION   | 86.6  |         | 4     | [D341F3C6F6](https://bsd-hardware.info/?probe=d341f3c6f6) |
| SANYO      | 42T4940 LION   | 86.6  |         | 4     | [5CE3DFE4A2](https://bsd-hardware.info/?probe=5ce3dfe4a2) |
| SANYO      | 45N1037 LION   | 39.0  |         | 4     | [B1377872CD](https://bsd-hardware.info/?probe=b1377872cd) |
| SANYO      | 45N1734 LION   | 72.4  |         | 4     | [2776D8C350](https://bsd-hardware.info/?probe=2776d8c350) |
| SANYO      | PABAS024123... | 55.9  |         | 4     | [DCC5D3116F](https://bsd-hardware.info/?probe=dcc5d3116f) |
| SMP        | 00HW023 LiP    | 23.5  |         | 4     | [692DF89C1F](https://bsd-hardware.info/?probe=692df89c1f) |
| SMP        | 00HW029 LiP    | 52.1  |         | 4     | [4CBD9F9314](https://bsd-hardware.info/?probe=4cbd9f9314) |
| SMP        | 02DL008 LiP    | 50.5  |         | 4     | [32207EA5D9](https://bsd-hardware.info/?probe=32207ea5d9) |
| SMP        | 5B10W138 LiP   | 45.3  |         | 4     | [64A11E18DA](https://bsd-hardware.info/?probe=64a11e18da) |
| SMP        | 5B10W139 LiP   | 50.5  |         | 4     | [C626B32508](https://bsd-hardware.info/?probe=c626b32508) |
| SMP        | DELL GPM036... | 97.0  |         | 4     | [EE8980FEC1](https://bsd-hardware.info/?probe=ee8980fec1) |
| SMP        | DELL VN3N04... | 41.4  |         | 4     | [6FC0671DC6](https://bsd-hardware.info/?probe=6fc0671dc6) |
| SMP        | L16M2PB1 LiP   | 30.0  |         | 4     | [BE9A45F529](https://bsd-hardware.info/?probe=be9a45f529) |
| SMP        | L16M2PB2 LiP   | 35.0  |         | 4     | [B8D2C0D81D](https://bsd-hardware.info/?probe=b8d2c0d81d) |
| SMPNz451   | bq20z451       | 57.7  |         | 4     | [3DD9E3557C](https://bsd-hardware.info/?probe=3dd9e3557c) |
| SONYCor    | AP13J4K LION   | 44.7  |         | 4     | [E063619F03](https://bsd-hardware.info/?probe=e063619f03) |
| Sunwoda    | 5B10W13975 LiP | 57.0  |         | 4     | [63B73012E6](https://bsd-hardware.info/?probe=63b73012e6) |
| Sunwoda    | L19D4PH3 LiP   | 61.0  |         | 4     | [95695F78C5](https://bsd-hardware.info/?probe=95695f78c5) |
| ASUSTek    | UX31-35        | 47.9  |         | 3     | [93655CDD83](https://bsd-hardware.info/?probe=93655cdd83) |
| ASUSTek    | X202-51        | 38.0  |         | 3     | [BDBE613858](https://bsd-hardware.info/?probe=bdbe613858) |
| Celxpert   | 01AV448 LiP    | 45.7  |         | 3     | [9CFE2DD858](https://bsd-hardware.info/?probe=9cfe2dd858) |
| DPONz45... | bq20z45189A... | 46.8  |         | 3     | [0D398D5C59](https://bsd-hardware.info/?probe=0d398d5c59) |
| Hewlett... | Primary LIon   |       |         | 3     | [718126149C](https://bsd-hardware.info/?probe=718126149c) |
| Hewlett... | Primary LIon   | 34    |         | 3     | [0B79535C7F](https://bsd-hardware.info/?probe=0b79535c7f) |
| Hewlett... | Primary LIon   | 36    |         | 3     | [7596B602C6](https://bsd-hardware.info/?probe=7596b602c6) |
| Hewlett... | Primary LIon   | 39    |         | 3     | [77C17E4A2F](https://bsd-hardware.info/?probe=77c17e4a2f) |
| Hewlett... | Primary LIon   | 47    |         | 3     | [7BD69EE984](https://bsd-hardware.info/?probe=7bd69ee984) |
| Hewlett... | Primary LIon   | 64    |         | 3     | [E70725DD32](https://bsd-hardware.info/?probe=e70725dd32) |
| Lenovo     | Serial numb... | 28.5  |         | 3     | [911A1723A2](https://bsd-hardware.info/?probe=911a1723a2) |
| Lenovo     | BASE-BAT LiP   | 45.0  |         | 3     | [EB136E5D7E](https://bsd-hardware.info/?probe=eb136e5d7e) |
| LGC        | 01AV432 LiP    | 51.0  |         | 3     | [C27BA488AA](https://bsd-hardware.info/?probe=c27ba488aa) |
| LGC        | 01AV489 LiP    | 23.9  |         | 3     | [6D7B30D2C4](https://bsd-hardware.info/?probe=6d7b30d2c4) |
| LGC        | 42T4865 LION   | 64.1  |         | 3     | [8C7992E557](https://bsd-hardware.info/?probe=8c7992e557) |
| LGC        | 45N1049 LION   | 40.4  |         | 3     | [6F1FD71366](https://bsd-hardware.info/?probe=6f1fd71366) |
| LGC        | 45N1079 LION   | 62.2  |         | 3     | [8E798CA6EF](https://bsd-hardware.info/?probe=8e798ca6ef) |
| LGC        | 45N1147 LION   | 60.7  |         | 3     | [6D372DB804](https://bsd-hardware.info/?probe=6d372db804) |
| LGC        | 5B10W138 LiP   | 45.0  |         | 3     | [3D50BA4D85](https://bsd-hardware.info/?probe=3d50ba4d85) |
| LGC        | 5B10W139 LiP   | 50.5  |         | 3     | [AF190C38E9](https://bsd-hardware.info/?probe=af190c38e9) |
| LGC        | AP18E8M Li-Ion | 57.5  |         | 3     | [6E97A003EC](https://bsd-hardware.info/?probe=6e97a003ec) |
| LGC KT0... | AP18C8K LION   | 48.0  |         | 3     | [820E7DA3C8](https://bsd-hardware.info/?probe=820e7da3c8) |
| LGC        | L17L3PG1 LiP   | 52.5  |         | 3     | [D8F8901AE7](https://bsd-hardware.info/?probe=d8f8901ae7) |
| Notebook   | BAT LION       | 48    |         | 3     | [E83D522905](https://bsd-hardware.info/?probe=e83d522905) |
| Panasonic  | 45N1143 LION   | 38.9  |         | 3     | [D9EFC1E30B](https://bsd-hardware.info/?probe=d9efc1e30b) |
| Panasonic  | 92P1133 LION   | 84.2  |         | 3     | [3497EE2FCC](https://bsd-hardware.info/?probe=3497ee2fcc) |
| Panasonic  | AP16M5J Li-Ion | 37.0  |         | 3     | [81827CCBCA](https://bsd-hardware.info/?probe=81827ccbca) |
| Panasonic  | Li_Ion_4000... | 47.5  |         | 3     | [FAE71F7E35](https://bsd-hardware.info/?probe=fae71f7e35) |
| Samsung... | DELL MT2648... | 86.6  |         | 3     | [08FE78379D](https://bsd-hardware.info/?probe=08fe78379d) |
| SANYO      | 01AV425 LION   | 47.5  |         | 3     | [7DF625B1DF](https://bsd-hardware.info/?probe=7df625b1df) |
| SANYO      | 45N1172 LION   | 62.6  |         | 3     | [786669CC9C](https://bsd-hardware.info/?probe=786669cc9c) |
| SANYO      | 45N1173 LION   | 94.0  |         | 3     | [4A700F43F8](https://bsd-hardware.info/?probe=4a700f43f8) |
| SANYO      | AL10B31        | 48.8  |         | 3     | [F456E964DB](https://bsd-hardware.info/?probe=f456e964db) |
| SANYO      | AP13J3K LION   | 45.9  |         | 3     | [E2E0A1953D](https://bsd-hardware.info/?probe=e2e0a1953d) |
| SANYO      | AS10D31 Lion   | 48.8  |         | 3     | [385751DBC3](https://bsd-hardware.info/?probe=385751dbc3) |
| SANYO      | GRAPE32 LION   | 48.8  |         | 3     | [6A1B523EFB](https://bsd-hardware.info/?probe=6a1b523efb) |
| SDI        | Dell LION      | 49    |         | 3     | [6911E08B7E](https://bsd-hardware.info/?probe=6911e08b7e) |
| SMP        | 00HW003 LiP    | 50.1  |         | 3     | [341BAE363A](https://bsd-hardware.info/?probe=341bae363a) |
| SMP        | 01AV446 LiP    | 45.3  |         | 3     | [83EE1D297D](https://bsd-hardware.info/?probe=83ee1d297d) |
| SMP        | 5B10W13931 LiP | 51.0  |         | 3     | [85E94A1288](https://bsd-hardware.info/?probe=85e94a1288) |
| SMP        | 5B10W13973 LiP | 57.0  |         | 3     | [ADD8280600](https://bsd-hardware.info/?probe=add8280600) |
| SMP        | 5B11C732 LiP   | 57.0  |         | 3     | [EF85735453](https://bsd-hardware.info/?probe=ef85735453) |
| SMP        | DELL 71JF45... | 74.0  |         | 3     | [B4A35AA7B0](https://bsd-hardware.info/?probe=b4a35aa7b0) |
| SMP        | DELL 7V69Y5... | 62.0  |         | 3     | [9E798CBFC8](https://bsd-hardware.info/?probe=9e798cbfc8) |
| SMP        | DELL DM3WC6... | 60.0  |         | 3     | [254ACB5DF8](https://bsd-hardware.info/?probe=254acb5df8) |
| SMP        | DELL JHXPY5... | 57.5  |         | 3     | [EC74AF083F](https://bsd-hardware.info/?probe=ec74af083f) |
| SMP        | DELL Y3F7Y6... | 42.0  |         | 3     | [F31CC32515](https://bsd-hardware.info/?probe=f31cc32515) |
| SMP        | L17M2PB7 LiP   | 30.0  |         | 3     | [883DBF15E4](https://bsd-hardware.info/?probe=883dbf15e4) |
| SMP        | L17M3PG1 LiP   | 52.5  |         | 3     | [57C3A4005A](https://bsd-hardware.info/?probe=57c3a4005a) |
| SMP-SDI2.8 | DELL FW1MN3... | 41.4  |         | 3     | [4DFA2F0148](https://bsd-hardware.info/?probe=4dfa2f0148) |
| SMPNz45... | bq20z45189A... | 86.0  |         | 3     | [45BFFD3275](https://bsd-hardware.info/?probe=45bffd3275) |
| Sony       | 45N1705 LiP    | 47.1  |         | 3     | [17FD94A4C0](https://bsd-hardware.info/?probe=17fd94a4c0) |
| TPS        | S10            | 44.7  |         | 3     | [FD081A3636](https://bsd-hardware.info/?probe=fd081a3636) |
| APL MRD    |  Lion          |       | Li-ion  | 2     | [584ECF8423](https://bsd-hardware.info/?probe=584ecf8423) |
| ASUSTek    | 1015PE         | 47.5  |         | 2     | [EFEA0EFB2B](https://bsd-hardware.info/?probe=efea0efb2b) |
| ASUSTek    | 1215B          | 56.2  |         | 2     | [1CCF85F60D](https://bsd-hardware.info/?probe=1ccf85f60d) |
| ASUSTek    | G74--52        | 78.0  |         | 2     | [6B7CF8FCAC](https://bsd-hardware.info/?probe=6b7cf8fcac) |
| ASUSTek    | K56--30        | 44.6  |         | 2     | [1263A5FB37](https://bsd-hardware.info/?probe=1263a5fb37) |
| ASUSTek    | N56--52        | 57.7  |         | 2     | [3B7E2EE70B](https://bsd-hardware.info/?probe=3b7e2ee70b) |
| ASUSTek    | UX325 LIon     | 67.3  |         | 2     | [692E2F0837](https://bsd-hardware.info/?probe=692e2f0837) |
| ASUSTek    | X550A26        | 34.6  |         | 2     | [9D406D735E](https://bsd-hardware.info/?probe=9d406d735e) |
| BYD        | DELL 9W9MX8... | 42.0  |         | 2     | [BC5EB8E237](https://bsd-hardware.info/?probe=bc5eb8e237) |
| Celxpert   | 01AV475 LiP    | 54.1  |         | 2     | [64D42B9C5F](https://bsd-hardware.info/?probe=64d42b9c5f) |
| Celxpert   | 5B10W138 LiP   | 45.7  |         | 2     | [8B112AA100](https://bsd-hardware.info/?probe=8b112aa100) |
| Celxpert   | L19C3PD6 LiP   | 52.5  |         | 2     | [A919E85270](https://bsd-hardware.info/?probe=a919e85270) |
| DGFGE      | 597077-3S Real | 65.0  |         | 2     | [80F6445F54](https://bsd-hardware.info/?probe=80f6445f54) |
| DPON013    | ASMB013        | 50.2  |         | 2     | [015F0A0A6D](https://bsd-hardware.info/?probe=015f0a0a6d) |
| DPONz45... | bq20z451NQT... | 46.8  |         | 2     | [EEED92AB62](https://bsd-hardware.info/?probe=eeed92ab62) |
| Dynapack   | HB4593R1ECW... | 56.3  |         | 2     | [F9FDC75B45](https://bsd-hardware.info/?probe=f9fdc75b45) |
| Dynapack   | HB6081V1ECW... | 55.2  |         | 2     | [E1B5D66244](https://bsd-hardware.info/?probe=e1b5d66244) |
| Dynapack   | HB9790T7ECW... | 82.9  |         | 2     | [CED12F0B41](https://bsd-hardware.info/?probe=ced12f0b41) |
| Fujitsu    | CP700283-01... | 76.7  |         | 2     | [5C07C1A47E](https://bsd-hardware.info/?probe=5c07c1a47e) |
| Hewlett... | Primary        | 31    |         | 2     | [D57E5B1B88](https://bsd-hardware.info/?probe=d57e5b1b88) |
| Hewlett... | Primary        | 34    |         | 2     | [25E43BE096](https://bsd-hardware.info/?probe=25e43be096) |
| Hewlett... | Primary        | 35    |         | 2     | [75B9EF6EE6](https://bsd-hardware.info/?probe=75b9ef6ee6) |
| Hewlett... | Primary        | 47    |         | 2     | [3C11FC31B2](https://bsd-hardware.info/?probe=3c11fc31b2) |
| Hewlett... | Primary        | 55    |         | 2     | [EF66D7A110](https://bsd-hardware.info/?probe=ef66d7a110) |
| Hewlett... | Primary        | 95    |         | 2     | [476193BFD0](https://bsd-hardware.info/?probe=476193bfd0) |
| Hewlett... | Primary LIon   | 24    |         | 2     | [6E82F69C4C](https://bsd-hardware.info/?probe=6e82f69c4c) |
| Hewlett... | Primary LIon   | 25    |         | 2     | [507E85C092](https://bsd-hardware.info/?probe=507e85c092) |
| Hewlett... | Primary LIon   | 29    |         | 2     | [C4F7B8A774](https://bsd-hardware.info/?probe=c4f7b8a774) |
| Hewlett... | Primary LIon   | 41    |         | 2     | [7C997CE022](https://bsd-hardware.info/?probe=7c997ce022) |
| Hewlett... | Primary LIon   | 44    |         | 2     | [3C404C9D20](https://bsd-hardware.info/?probe=3c404c9d20) |
| Hewlett... | Primary LIon   | 50    |         | 2     | [03CB6C6C7F](https://bsd-hardware.info/?probe=03cb6c6c7f) |
| Hewlett... | Primary LIon   | 55    |         | 2     | [D8FB34DE12](https://bsd-hardware.info/?probe=d8fb34de12) |
| Hewlett... | Primary LIon   | 90    |         | 2     | [86875F01C2](https://bsd-hardware.info/?probe=86875f01c2) |
| Intel SR 1 | Harris Beac... | 32.7  |         | 2     | [2F90D5C2BD](https://bsd-hardware.info/?probe=2f90d5c2bd) |
| JingYi     | 08K8193 LION   | 81.3  |         | 2     | [A2B9975FE2](https://bsd-hardware.info/?probe=a2b9975fe2) |
| Lenovo     | LCFC Li Pol... | 23.8  |         | 2     | [C4FD2595E6](https://bsd-hardware.info/?probe=c4fd2595e6) |
| LG         | LGC-LGC LION   | 72.8  |         | 2     | [5777CB6DC6](https://bsd-hardware.info/?probe=5777cb6dc6) |
| LGC        | 00HW002 LiP    | 50.2  |         | 2     | [EDA0880C67](https://bsd-hardware.info/?probe=eda0880c67) |
| LGC        | 00NY486 LION   | 47.5  |         | 2     | [2AEA9384AC](https://bsd-hardware.info/?probe=2aea9384ac) |
| LGC        | 01AV420 LiP    | 23.9  |         | 2     | [866724656A](https://bsd-hardware.info/?probe=866724656a) |
| LGC        | 01AV423 LiP    | 23.9  |         | 2     | [866724656A](https://bsd-hardware.info/?probe=866724656a) |
| LGC        | 01AV470 LiP    | 47.9  |         | 2     | [FB6C7B3B09](https://bsd-hardware.info/?probe=fb6c7b3b09) |
| LGC        | 01AV492 LION   | 71.1  |         | 2     | [B816902C0B](https://bsd-hardware.info/?probe=b816902c0b) |
| LGC        | 01AV494 LiP    | 57.0  |         | 2     | [A9928BD16E](https://bsd-hardware.info/?probe=a9928bd16e) |
| LGC        | 02DL004 LiP    | 51.0  |         | 2     | [2DA32E59B0](https://bsd-hardware.info/?probe=2da32e59b0) |
| LGC        | 42T4653 LION   | 56.2  |         | 2     | [26F8459193](https://bsd-hardware.info/?probe=26f8459193) |
| LGC        | 42T4912 LION   | 84.3  |         | 2     | [BAA0E928A8](https://bsd-hardware.info/?probe=baa0e928a8) |
| LGC        | 45N1749 LiP    | 34.0  |         | 2     | [0E448AF5F5](https://bsd-hardware.info/?probe=0e448af5f5) |
| LGC        | AC14B18J LION  | 36.7  |         | 2     | [A17D96DDE0](https://bsd-hardware.info/?probe=a17d96dde0) |
| LGC        | L16L2PB2 LiP   | 30.0  |         | 2     | [E2A5A65135](https://bsd-hardware.info/?probe=e2a5a65135) |
| LGC-LGC... | DELL C27RW ... | 42.0  |         | 2     | [089B61BB38](https://bsd-hardware.info/?probe=089b61bb38) |
| LGC-LGC... | DELL FDRHM0... | 42.0  |         | 2     | [C2D56FC369](https://bsd-hardware.info/?probe=c2d56fc369) |
| LGC-LGC... | DELL RDYCT6... | 91.0  |         | 2     | [46E9438BF9](https://bsd-hardware.info/?probe=46e9438bf9) |
| LGC-LGC6.5 | DELL 2XXFW0... | 51.0  |         | 2     | [7319560506](https://bsd-hardware.info/?probe=7319560506) |
| LGC        | LNV-45N1 LION  | 47.0  |         | 2     | [0A6985F078](https://bsd-hardware.info/?probe=0a6985f078) |
| MSI        | MS-16W1        | 51.3  |         | 2     | [CEDF98C955](https://bsd-hardware.info/?probe=cedf98c955) |
| Notebook   | BAT LION       | 31    |         | 2     | [4ADFEAA072](https://bsd-hardware.info/?probe=4adfeaa072) |
| Notebook   | BAT LION       | 33    |         | 2     | [D2560F69F7](https://bsd-hardware.info/?probe=d2560f69f7) |
| Notebook   | BAT LION       | 36    |         | 2     | [792FB07DD9](https://bsd-hardware.info/?probe=792fb07dd9) |
| Notebook   | BAT LION       | 44    |         | 2     | [B7C06932A3](https://bsd-hardware.info/?probe=b7c06932a3) |
| Notebook   | BAT LION       | 53    |         | 2     | [F99C9F56B7](https://bsd-hardware.info/?probe=f99c9f56b7) |
| PAC        | CP656337-01... | 47.5  |         | 2     | [D9FD7E54CF](https://bsd-hardware.info/?probe=d9fd7e54cf) |
| PAC        | CP700280-01... | 48.6  |         | 2     | [1062220932](https://bsd-hardware.info/?probe=1062220932) |
| PAC        | PC-VP-WP93-... | 47.5  |         | 2     | [50A5ED6B41](https://bsd-hardware.info/?probe=50a5ed6b41) |
| Panasonic  | 004A354D363... | 37.0  |         | 2     | [570B96D0F7](https://bsd-hardware.info/?probe=570b96d0f7) |
| Panasonic  | 42T4620 LION   | 84.2  |         | 2     | [7D36D27958](https://bsd-hardware.info/?probe=7d36d27958) |
| Panasonic  | 42T4793 LION   | 56.2  |         | 2     | [9F9CB3E201](https://bsd-hardware.info/?probe=9f9cb3e201) |
| Panasonic  | 42T4801 LION   | 94.0  |         | 2     | [1433351032](https://bsd-hardware.info/?probe=1433351032) |
| Panasonic  | AP19B5K LION   | 39.7  |         | 2     | [7FB743C654](https://bsd-hardware.info/?probe=7fb743c654) |
| Panasonic  | AS10B5E LION   | 64.8  |         | 2     | [1617262A28](https://bsd-hardware.info/?probe=1617262a28) |
| Panasonic  | CF-VZSU46 LION | 91.0  |         | 2     | [1C918B79B0](https://bsd-hardware.info/?probe=1c918b79b0) |
| Razer      | Blade Li-I     | 65.0  |         | 2     | [34AC291019](https://bsd-hardware.info/?probe=34ac291019) |
| Samsung    | DELL 92 LION   | 67.0  |         | 2     | [CF598483CF](https://bsd-hardware.info/?probe=cf598483cf) |
| Samsung SD | DELL XRDW25... | 41.4  |         | 2     | [BB13E61DE1](https://bsd-hardware.info/?probe=bb13e61de1) |
| Samsung... | DELL 7DWMT1... | 98.2  |         | 2     | [2F848FD2C0](https://bsd-hardware.info/?probe=2f848fd2c0) |
| Samsung... | DELL C4HCW6... | 42.0  |         | 2     | [39B4581223](https://bsd-hardware.info/?probe=39b4581223) |
| SANYO      | 00323341343... | 55.9  |         | 2     | [CA34DAC813](https://bsd-hardware.info/?probe=ca34dac813) |
| SANYO      | 42T4710 LION   | 77.0  |         | 2     | [70A56029E7](https://bsd-hardware.info/?probe=70a56029e7) |
| SANYO      | 42T4751 LION   | 48.6  |         | 2     | [A1561DACB2](https://bsd-hardware.info/?probe=a1561dacb2) |
| SANYO      | 45N1027 LION   | 86.6  |         | 2     | [06C6A282CA](https://bsd-hardware.info/?probe=06c6a282ca) |
| SANYO      | 45N1089 LiP    | 46.8  |         | 2     | [D5BBBB8CBE](https://bsd-hardware.info/?probe=d5bbbb8cbe) |
| SANYO      | 45N1105 LION   | 47.5  |         | 2     | [9EA67D3893](https://bsd-hardware.info/?probe=9ea67d3893) |
| SANYO      | 45N1170 LION   | 101.5 |         | 2     | [D642970071](https://bsd-hardware.info/?probe=d642970071) |
| SANYO      | 45N1175 LION   | 85.9  |         | 2     | [791C826F7D](https://bsd-hardware.info/?probe=791c826f7d) |
| SANYO      | 45N1177 LION   | 62.6  |         | 2     | [55DEBB2F24](https://bsd-hardware.info/?probe=55debb2f24) |
| SANYO      | AC13C34 LION   | 30.0  |         | 2     | [513C7FF4BE](https://bsd-hardware.info/?probe=513c7ff4be) |
| SANYO      | AC14B13J LION  | 37.7  |         | 2     | [400EF90A79](https://bsd-hardware.info/?probe=400ef90a79) |
| SANYO      | AL15A32 LION   | 37.0  |         | 2     | [7A4EB565FE](https://bsd-hardware.info/?probe=7a4eb565fe) |
| SANYO      | AS09C31 LION   | 47.5  |         | 2     | [96D745589C](https://bsd-hardware.info/?probe=96d745589c) |
| SANYO      | DELL 96JC94... | 57.7  |         | 2     | [8D92A4E37E](https://bsd-hardware.info/?probe=8d92a4e37e) |
| SANYO      | DELL M7T5F8... | 66.6  |         | 2     | [3F2E8586A7](https://bsd-hardware.info/?probe=3f2e8586a7) |
| SANYO      | DELL RG0490... | 62.2  |         | 2     | [66DED228EA](https://bsd-hardware.info/?probe=66ded228ea) |
| SANYO      | GC86508SAT0    | 23.8  |         | 2     | [1CBFCE4D7E](https://bsd-hardware.info/?probe=1cbfce4d7e) |
| SANYO      | L09S6Y02 LION  | 38.9  |         | 2     | [A0D1F01226](https://bsd-hardware.info/?probe=a0d1f01226) |
| SANYO      | PABAS024 LION  | 54.2  |         | 2     | [21407195E3](https://bsd-hardware.info/?probe=21407195e3) |
| SDI        | Dell LION      | 5     |         | 2     | [6DA8F97BCD](https://bsd-hardware.info/?probe=6da8f97bcd) |
| SIMPLO     | AS10D75 LION   | 48.8  |         | 2     | [DB00ABB833](https://bsd-hardware.info/?probe=db00abb833) |
| SIMPLO     | Li_Ion_4000... | 48.8  |         | 2     | [0513869BE8](https://bsd-hardware.info/?probe=0513869be8) |

