DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 8675.

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
| AMD        | GX-412TC SOC                     |      | 236   | [1A431BAA436D](<Desktop/PC Engines/APU/APU2/1A431BAA436D>) |
| Intel      | Celeron J4125                    | 2.00 | 195   | [1EDF1016D6B2](<Desktop/Others/Others/Others/1EDF1016D6B2>) |
| Intel      | Celeron N5095                    | 2.00 | 159   | [7B7F81AC1DFE](<Desktop/Others/Others/Others/7B7F81AC1DFE>) |
| Intel      | Celeron J3160                    | 1.60 | 153   | [124BE58E7612](<Desktop/Others/YL-J3160/YL-J3160L4/124BE58E7612>) |
| Intel      | Core i5-7200U                    | 2.50 | 87    | [D60D770CAE1B](<Notebook/Lenovo/IdeaPad/IdeaPad 310-14IKB 80TU/D60D770CAE1B>) |
| Intel      | Celeron J1900                    | 1.99 | 83    | [5C14E92D5780](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780>) |
| Intel      | Core 2 Duo                       |      | 69    | [C67C08C62EEE](<Desktop/Dell/OptiPlex/OptiPlex 380/C67C08C62EEE>) |
| Intel      | Core i5-6500                     | 3.20 | 68    | [3256005C34E3](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3>) |
| Intel      | Core i5-3470                     | 3.20 | 65    | [DFDBA5E1859E](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E>) |
| Intel      | Core i5-8250U                    | 1.60 | 63    | [9802B6BB4623](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L8002WMX/9802B6BB4623>) |
| Intel      | Celeron J3455                    | 1.50 | 62    | [3487CD2A0FE8](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8>) |
| Intel      | 11th Gen Core i7-1165G7          | 2.80 | 59    | [2BCE064BBD99](<Notebook/Star Labs/StarBook/StarBook/2BCE064BBD99>) |
| Intel      | Celeron J1900                    | 1.99 | 59    | [2CC23D52E14F](<Mini Pc/AMI/Aptio/Aptio CRB/2CC23D52E14F>) |
| Intel      | Core i5-2520M                    | 2.50 | 55    | [6EF6C3723B2F](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4243F39/6EF6C3723B2F>) |
| Intel      | Core i5-4570                     | 3.20 | 55    | [C840DA9F22BC](<Desktop/Dell/OptiPlex/OptiPlex 9020/C840DA9F22BC>) |
| AMD        | GX-420CA SOC with Radeon HD G... |      | 53    | [2691FA941D87](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87>) |
| Intel      | Core i3-7100U                    | 2.40 | 50    | [2278924F334A](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-307/2278924F334A>) |
| Intel      | Core i5-4590                     | 3.30 | 49    | [B41A8964B213](<Desktop/Dell/OptiPlex/OptiPlex 3020/B41A8964B213>) |
| Intel      | Core i7-7500U                    | 2.70 | 48    | [6B1DED8023A3](<Desktop/Others/Others/Others/6B1DED8023A3>) |
| Intel      | Atom D525                        | 1.80 | 48    | [5B265979975E](<Desktop/Others/Others/Others/5B265979975E>) |
| Intel      | Core i7-8550U                    | 1.80 | 46    | [E36B3935C888](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs1xx/E36B3935C888>) |
| AMD        | RX-427BB with AMD Radeon R7 G... |      | 45    | [51D56BADAD82](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82>) |
| Intel      | Core i5-3570 CPU                 |      | 45    | [C93FEB0B59C9](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V5535/C93FEB0B59C9>) |
| Intel      | Celeron J4105                    | 1.50 | 45    | [A940BF140853](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/A940BF140853>) |
| Intel      | Core i5-2400                     | 3.10 | 45    | [E4BF25D116F4](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91p 7033A2G/E4BF25D116F4>) |
| Intel      | Core i7-3770                     | 3.40 | 43    | [3577E3899A73](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73>) |
| Intel      | Celeron N3150                    | 1.60 | 42    | [6E70FB5A2725](<Desktop/ZOTAC/Others/Others/6E70FB5A2725>) |
| Intel      | Celeron N3450                    | 1.10 | 42    | [574A3DFD4C34](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/574A3DFD4C34>) |
| AMD        | GX-415GA SOC with Radeon HD G... |      | 41    | [582E158CFA66](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66>) |
| Intel      | Core i5-3320M                    | 2.60 | 41    | [0189D3C3009B](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B>) |
| Intel      | Core i5-5200U                    | 2.20 | 40    | [799DBF53903B](<Notebook/Samsung Electronics/270E5/270E5K-270E5Q-271E5K-2570EK/799DBF53903B>) |
| Intel      | Pentium N3700                    | 1.60 | 39    | [08DBAE3B5E67](<Server/Supermicro/Super/Super Server/08DBAE3B5E67>) |
| Intel      | Atom C3558                       | 2.20 | 37    | [3D854A7B1556](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556>) |
| Intel      | Celeron 3865U                    | 1.80 | 36    | [122D444C7C33](<Desktop/Protectli/FW/FW6/122D444C7C33>) |
| Intel      | Core i5-6300U                    | 2.40 | 36    | [E2372EFC6D66](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66>) |
| Intel      | Core i5-5300U                    | 2.30 | 35    | [5718430B3004](<Notebook/Toshiba/dynabook/dynabook R63-P/5718430B3004>) |
| Intel      | Pentium Silver J5005             | 1.50 | 33    | [53D0F9939362](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362>) |
| Intel      | Atom E3845                       | 1.91 | 33    | [DA0DE8A52BA6](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6>) |
| Intel      | Core i5-6200U                    | 2.30 | 33    | [98E69F639C1F](<Notebook/Lenovo/ThinkPad/ThinkPad 13 20GJCTO1WW/98E69F639C1F>) |
| Intel      | Atom E3930                       | 1.30 | 32    | [810780DBBB1C](<Firewall/Sophos/SG/SG/810780DBBB1C>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 31    | [D4F85CE4A0A4](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO WIFI/D4F85CE4A0A4>) |
| Intel      | Core i5-10210U                   | 1.60 | 31    | [5F2605C0CFF4](<Notebook/Google/Kohaku/Kohaku/5F2605C0CFF4>) |
| Intel      | Celeron N3160                    | 1.60 | 30    | [F19B9213C2D1](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/F19B9213C2D1>) |
| AMD        | G-T40E                           |      | 29    | [EF7F214F3D54](<Desktop/PC Engines/apu/apu1/EF7F214F3D54>) |
| Intel      | Xeon D-1518                      | 2.20 | 29    | [6D245ECF5FC4](<Server/Supermicro/Super/Super Server/6D245ECF5FC4>) |
| Intel      | Core i5-3570                     | 3.40 | 28    | [C462E9B00C11](<Desktop/Dell/OptiPlex/OptiPlex 7010/C462E9B00C11>) |
| Intel      | Xeon E3-1220 v3                  | 3.10 | 28    | [84A39098466A](<Server/Fujitsu/PRIMERGY/PRIMERGY RX100 S8/84A39098466A>) |
| Intel      | Core i3-6100                     | 3.70 | 28    | [584D4BE57ECB](<Desktop/ASUSTek Computer/H110I-PLUS/H110I-PLUS D3/584D4BE57ECB>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 27    | [FFA88723BDD5](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5>) |
| Intel      | Celeron N4100                    | 1.10 | 27    | [B565A5A319EC](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/B565A5A319EC>) |
| Intel      | Core i3-4160                     | 3.60 | 27    | [422496C48BF5](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5>) |
| Intel      | Core i7-7700                     | 3.60 | 26    | [CAE53A19F03D](<Desktop/Gigabyte Technology/H270/H270M-DS3H/CAE53A19F03D>) |
| Intel      | Celeron 2955U                    | 1.40 | 26    | [2F8609C684A1](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/2F8609C684A1>) |
| Intel      | Atom C2558                       | 2.40 | 26    | [565D06ED3C8E](<Firewall/Sophos/SG/SG/565D06ED3C8E>) |
| AMD        | Ryzen Embedded V1500B            |      | 25    | [2DD46B265269](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269>) |
| Intel      | Core i3-8100                     | 3.60 | 25    | [A0F3B9E10A40](<Desktop/Dell/Inspiron/Inspiron 3470/A0F3B9E10A40>) |
| Intel      | Celeron J1800                    | 2.41 | 25    | [B6CD8CD35969](<Desktop/Others/Others/Others/B6CD8CD35969>) |
| Intel      | Core i3-3220                     | 3.30 | 25    | [BD1A816BB8CA](<Desktop/MSI/MS/MS-7788/BD1A816BB8CA>) |
| Intel      | Core i7-4770                     | 3.40 | 25    | [B091C964714D](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHA0X9LS/B091C964714D>) |
| Intel      | Core i5-4200U                    | 1.60 | 25    | [A75D47C729F9](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 2nd 20A7002FUS/A75D47C729F9>) |
| AMD        | GX-222GC SOC with Radeon R5E ... |      | 24    | [3A4A89D57DB6](<Desktop/Fujitsu/FUTRO/FUTRO S920/3A4A89D57DB6>) |
| Intel      | Core i7-10510U                   | 1.80 | 24    | [E5E4D871BE14](<Desktop/Others/Others/Others/E5E4D871BE14>) |
| Intel      | Core 2 Duo                       |      | 24    | [63258707728A](<Desktop/Dell/OptiPlex/OptiPlex 755/63258707728A>) |
| Intel      | Core i5-7500                     | 3.40 | 24    | [3C676EC0E951](<Desktop/Dell/OptiPlex/OptiPlex 7050/3C676EC0E951>) |
| Intel      | 11th Gen Core i5-11400           | 2.60 | 24    | [BD8BD7D4DA30](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30>) |
| Intel      | Xeon E31220                      | 3.10 | 24    | [E8FB187A75BE](<Desktop/Supermicro/X9/X9SCL-X9SCM/E8FB187A75BE>) |
| Intel      | Core i3-4130                     | 3.40 | 23    | [AE1164BF35BB](<Desktop/Dell/OptiPlex/OptiPlex 3020/AE1164BF35BB>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 22    | [75E66F2BE030](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/75E66F2BE030>) |
| Intel      | Xeon X3430                       | 2.40 | 22    | [FFDCE5AE5207](<Server/Dell/PowerEdge/PowerEdge R210/FFDCE5AE5207>) |
| Intel      | Core i7-2600                     | 3.40 | 22    | [3D8B6CD6994B](<Desktop/Dell/OptiPlex/OptiPlex 790/3D8B6CD6994B>) |
| Intel      | Xeon E5-2650 v2                  | 2.60 | 22    | [1AF57826CF89](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/1AF57826CF89>) |
| Intel      | Celeron J3060                    | 1.60 | 22    | [EE3235442DAF](<Desktop/Protectli/FW2/FW2B/EE3235442DAF>) |
| AMD        | FX-8350 Eight-Core               |      | 21    | [55CAA0D2979E](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/55CAA0D2979E>) |
| AMD        | EPYC 3201 8-Core                 |      | 21    | [37BBC645886F](<Notebook/Deciso/OPNsense/OPNsense Appliance/37BBC645886F>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 21    | [8D63433E0169](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/8D63433E0169>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 21    | [0BC00FD32A34](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/0BC00FD32A34>) |
| Intel      | Celeron J4115                    | 1.80 | 21    | [D15B59962C50](<Desktop/Hardkernel/ODROID-H/ODROID-H2/D15B59962C50>) |
| Intel      | Core i3-10100                    | 3.60 | 21    | [F54ADC493621](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621>) |
| Intel      | Atom N450                        | 1.66 | 21    | [EFBED6E2C955](<Firewall/Sophos/UTM/UTM/EFBED6E2C955>) |
| Intel      | Core i3-2120 @ 3.30GH            |      | 21    | [DA6E39A347EC](<Desktop/Sonic Foundry/Mediasite/Mediasite Recorder/DA6E39A347EC>) |
| Intel      | Xeon E5620                       | 2.40 | 21    | [8ACC974830FF](<Server/Dell/PowerEdge/PowerEdge R410/8ACC974830FF>) |
| Intel      | Xeon E3-1220 V2                  | 3.10 | 21    | [CDAF2C982352](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/CDAF2C982352>) |
| Intel      | Core i7-4790                     | 3.60 | 21    | [C7649894A9FD](<Desktop/Dell/OptiPlex/OptiPlex 7020/C7649894A9FD>) |
| Intel      | Core i5-5250U                    | 1.60 | 21    | [C9D03D675712](<Desktop/Intel/QHSW/QHSW02/C9D03D675712>) |
| Intel      | Core i3-4010U                    | 1.70 | 21    | [574B8D8CFA38](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38>) |
| Intel      | Core i7-8700                     | 3.20 | 20    | [0FC3EEDA5ED5](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0FC3EEDA5ED5>) |
| Intel      | Celeron N2940                    | 1.83 | 20    | [A3DBD4D871FE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE>) |
| Intel      | Core i3-4005U                    | 1.70 | 20    | [43C06475780D](<Notebook/Hewlett-Packard/Notebook/Notebook/43C06475780D>) |
| Intel      | Atom C2358                       | 1.74 | 20    | [1592D21853FE](<Firewall/Sophos/SG/SG/1592D21853FE>) |
| Intel      | Atom C2758                       | 2.40 | 20    | [6F22C4CD7334](<Desktop/ADI Engineering/RCC/RCC/6F22C4CD7334>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 19    | [93887C3B2294](<Desktop/Dell/Vostro/Vostro 410/93887C3B2294>) |
| Intel      | Core i5-3210M                    | 2.50 | 19    | [26D21821107F](<Notebook/Samsung Electronics/300E4/300E4C-300E5C-300E7C/26D21821107F>) |
| Intel      | Core i3-5005U                    | 2.00 | 19    | [69AC5E94B55B](<Notebook/Google/Lulu/Lulu/69AC5E94B55B>) |
| Intel      | Core i5-4210U                    | 1.70 | 19    | [E7764A5A3B91](<Notebook/Dell/Latitude/Latitude 3540/E7764A5A3B91>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 18    | [2325A856795F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F>) |
| Intel      | Core 2 Quad CPU                  |      | 18    | [0B0590EEA521](<Desktop/Gigabyte Technology/G31/G31M-S2L/0B0590EEA521>) |
| Intel      | Celeron J6412                    | 2.00 | 18    | [F9E7BE26C82B](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B>) |
| Intel      | CPU Version                      |      | 18    | [F4BFABD756AB](<Notebook/Dell/Vostro/Vostro 1400/F4BFABD756AB>) |
| Intel      | Core i7-3520M                    | 2.90 | 18    | [0AA9D55FD9C6](<Notebook/Dell/Latitude/Latitude E6330/0AA9D55FD9C6>) |
| Intel      | Xeon E3-1230 V2                  | 3.30 | 18    | [1D10666FC295](<Desktop/Supermicro/X9/X9SCL-X9SCM/1D10666FC295>) |
| Intel      | Xeon E3-1270 v3                  | 3.50 | 18    | [CC17D6E49ED3](<Desktop/Supermicro/PIO-518/PIO-518D-N6TRF-ST031/CC17D6E49ED3>) |
| Intel      | Xeon D-2123IT                    | 2.20 | 18    | [5565DD11099D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D>) |
| Intel      | Core i7-6700                     | 3.40 | 18    | [AABFEF40A2A3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/AABFEF40A2A3>) |
| Intel      | Core i5-8365U                    | 1.60 | 17    | [AB4C518C252E](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20QES53R00/AB4C518C252E>) |
| Intel      | Core i5-10400                    | 2.90 | 17    | [7A1467166A0C](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-K/7A1467166A0C>) |
| Intel      | Core i3-4150                     | 3.50 | 17    | [75719EC9648A](<Desktop/Samsung Electronics/DeskTop/DeskTop System/75719EC9648A>) |
| Intel      | Core i7-4600U                    | 2.10 | 17    | [4A55E51D2962](<Notebook/Dell/Latitude/Latitude E7240/4A55E51D2962>) |
| Intel      | Core i5-6400                     | 2.70 | 17    | [7B89078673EA](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA>) |
| Intel      | Core i5-6500T                    | 2.50 | 17    | [700E5ED9C506](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/700E5ED9C506>) |
| Intel      | Core i5-8350U                    | 1.70 | 16    | [BD0ED8EF7DB5](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LBS0FH00/BD0ED8EF7DB5>) |
| Intel      | Core i7-8750H                    | 2.20 | 16    | [44BEE70144E5](<Notebook/Alienware/m/m15/44BEE70144E5>) |
| Intel      | Core i5-2500 @ 3.30GH            |      | 16    | [CFD7F415A438](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/CFD7F415A438>) |
| Intel      | Core i3-3240                     | 3.40 | 16    | [C263747DB078](<Desktop/ASUSTek Computer/P8/P8H77-I/C263747DB078>) |
| Intel      | Core i5-4300U                    | 1.90 | 16    | [DC9FF593E3E2](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ005SUS/DC9FF593E3E2>) |
| Intel      | Core i3-6006U                    | 2.00 | 16    | [32F9A01194D0](<Notebook/Hewlett-Packard/Notebook/Notebook/32F9A01194D0>) |
| Intel      | Core i7-6500U                    | 2.50 | 16    | [E27607696E33](<Desktop/Others/Others/Others/E27607696E33>) |
| Intel      | Core i7-6600U                    | 2.60 | 16    | [60067DC63CDD](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0PY04/60067DC63CDD>) |
| AMD        | FX-6300 Six-Core                 |      | 15    | [88A73B2C8E7E](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 15    | [2C34712FE131](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 15    | [0D81A0A9A717](<Desktop/CSL-Computer/A/A0000001/0D81A0A9A717>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 15    | [6F28C57B7391](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-F GAMING/6F28C57B7391>) |
| Intel      | Core i5-7300U                    | 2.60 | 15    | [28B8640D287D](<Notebook/Lenovo/ThinkPad/ThinkPad T470 20HES0EV0A/28B8640D287D>) |
| Intel      | Core i5-7400                     | 3.00 | 15    | [BE025EF0F7BC](<Desktop/ASUSTek Computer/H110/H110M-CS-BR/BE025EF0F7BC>) |
| Intel      | Core i7-10750H                   | 2.60 | 15    | [71CCA11D28B6](<Notebook/Monster/ABRA/ABRA A7 V11.2/71CCA11D28B6>) |
| Intel      | Core i5-2540M                    | 2.60 | 15    | [B3184192C411](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291LF6/B3184192C411>) |
| Intel      | Celeron 1037U                    | 1.80 | 15    | [C601B6CDC429](<Notebook/Shuttle/DS/DS437T/C601B6CDC429>) |
| Intel      | Core i5-4570T                    | 2.90 | 15    | [F5B923B560C8](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000KUS/F5B923B560C8>) |
| Intel      | Pentium G3220                    | 3.00 | 15    | [255D1BAAA00A](<Desktop/ASRock/H81/H81M-HDS/255D1BAAA00A>) |
| Intel      | Pentium G3420                    | 3.20 | 15    | [4509562A3078](<Firewall/Sophos/SG/SG/4509562A3078>) |
| Intel      | Xeon E3-1225 v3                  | 3.20 | 15    | [4CDC5514E15A](<Desktop/Lenovo/70F3S00K00/70F3S00K00 ThinkServer RS140/4CDC5514E15A>) |
| Intel      | Pentium G4400                    | 3.30 | 15    | [C96A2A643802](<Server/HPE/MM10/MM10Gen9/C96A2A643802>) |
| Intel      | Atom C3758                       | 2.20 | 15    | [7636541B48D5](<Desktop/Citrix/CB/CB-1100/7636541B48D5>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 14    | [435F418C7DE2](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 14    | [BB7614C3933F](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 14    | [4EC4B3A73B66](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66>) |
| Intel      | Core i7-8565U                    | 1.80 | 14    | [FF4B44FE1922](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922>) |
| Intel      | Core 2 CPU                       |      | 14    | [82F1FE229BCF](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/82F1FE229BCF>) |
| Intel      | Core i5-8500                     | 3.00 | 14    | [27920E53DEC4](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G4 SFF/27920E53DEC4>) |
| Intel      | Core i3-7100                     | 3.90 | 14    | [5A953B1C086E](<Desktop/Dell/Inspiron/Inspiron 3268/5A953B1C086E>) |
| Intel      | Core i3-2100 @ 3.10GH            |      | 14    | [A8401CC99B60](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite/A8401CC99B60>) |
| Intel      | Core i3-5010U                    | 2.10 | 14    | [03D7E19416AB](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/03D7E19416AB>) |
| AMD        | EPYC 3101 4-Core                 |      | 13    | [750B7003408F](<Notebook/Deciso/Netboard/Netboard A20/750B7003408F>) |
| AMD        | Athlon 3000G with Radeon Vega... |      | 13    | [60899A106B63](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-R/60899A106B63>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 13    | [6CEA289E0B55](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506II_FA506II/6CEA289E0B55>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 13    | [694A3578664F](<Desktop/MSI/MS-7/MS-7C35/694A3578664F>) |
| Intel      | Core i3-1005G1                   | 1.20 | 13    | [913B173AD9EB](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509JA_X509JA/913B173AD9EB>) |
| Intel      | Core i5-8400                     | 2.80 | 13    | [AD929F3542C5](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/AD929F3542C5>) |
| Intel      | Celeron J1900                    | 1.99 | 13    | [FC5120937F9C](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FC5120937F9C>) |
| Intel      | Celeron N2930                    | 1.83 | 13    | [26568100DB40](<Desktop/Others/Others/Others/26568100DB40>) |
| Intel      | Celeron G1610T                   | 2.30 | 13    | [36E7C68AA33D](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D>) |
| Intel      | Celeron G1820                    | 2.70 | 13    | [F1CCA1405D6B](<Desktop/Intel/DENLOW_WS/DENLOW_WS/F1CCA1405D6B>) |
| Intel      | Core i5-4590S                    | 3.00 | 13    | [1503C0BD2782](<Desktop/Dell/OptiPlex/OptiPlex 3020/1503C0BD2782>) |
| Intel      | Xeon E5-2630 v3                  | 2.40 | 13    | [006D640A4E82](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82>) |
| Intel      | Core i3-4030U                    | 1.90 | 13    | [D0338B0236D8](<Notebook/Lenovo/G50-70/G50-70 20351/D0338B0236D8>) |
| Intel      | Core i5-8265U                    | 1.60 | 12    | [7A14B1FE5621](<Desktop/Others/Others/Others/7A14B1FE5621>) |
| Intel      | Core i3-8145U                    | 2.10 | 12    | [6E17CA251085](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085>) |
| Intel      | Core i5-9500                     | 3.00 | 12    | [AD9E7BA16449](<Desktop/Dell/OptiPlex/OptiPlex 3070/AD9E7BA16449>) |
| Intel      | Pentium Gold G5400               | 3.70 | 12    | [1C596F08C310](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310>) |
| Intel      | Pentium G4560                    | 3.50 | 12    | [854A8DF08688](<Desktop/MSI/MS-7/MS-7A82/854A8DF08688>) |
| Intel      | Xeon E5520                       | 2.27 | 12    | [86E57128AC4E](<Server/Supermicro/X8/X8DTL/86E57128AC4E>) |
| Intel      | Core i5-2400S                    | 2.50 | 12    | [472E1FAA4B5F](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite USDT PC/472E1FAA4B5F>) |
| Intel      | Xeon E5645                       | 2.40 | 12    | [34F0B81A9C93](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93>) |
| Intel      | Core i5-3230M                    | 2.60 | 12    | [AD023293EF8F](<Notebook/Lenovo/G400s/G400s 20244/AD023293EF8F>) |
| Intel      | Core i5-4570S                    | 2.90 | 12    | [BB72C05BDA1A](<Desktop/Hewlett-Packard/RP5/RP5 Retail System Model 5810/BB72C05BDA1A>) |
| Intel      | Core i5-4590T                    | 2.00 | 12    | [634E1D4A13FA](<Desktop/Intel/DENLOW_WS/DENLOW_WS/634E1D4A13FA>) |
| Intel      | Core i7-4790K                    | 4.00 | 12    | [4E415A131D74](<Desktop/Gigabyte Technology/Z97/Z97X-UD3H-BK/4E415A131D74>) |
| Intel      | Xeon E3-1231 v3                  | 3.40 | 12    | [701CCB4D71F6](<Server/Supermicro/X10/X10SLH-N6-ST031/701CCB4D71F6>) |
| Intel      | Core i7-5550U                    | 2.00 | 12    | [BE188DCB9F9B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/BE188DCB9F9B>) |
| Intel      | Core i7-5600U                    | 2.60 | 12    | [F784FC43DD4A](<Notebook/Dell/Latitude/Latitude E5450/F784FC43DD4A>) |
| Intel      | Celeron N3350                    | 1.10 | 12    | [8D2CC3B43BC9](<Mini Pc/EXTRA Computer/exone/exone Business 5501/8D2CC3B43BC9>) |
| Intel      | Pentium N4200                    | 1.10 | 12    | [23F29A5F79A0](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0>) |
| Intel      | Core i7-6700K                    | 4.00 | 12    | [9FCEC82B3F4D](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9FCEC82B3F4D>) |
| Intel      | Xeon E3-1225 v5                  | 3.30 | 12    | [F7CE2619878B](<Desktop/Others/Others/Others/F7CE2619878B>) |
|            | Unknown                          |      | 12    | [66C97E231B7A](<Desktop/friendlyelec/nanopi-m/nanopi-m4/66C97E231B7A>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 11    | [69AAAA30BEFA](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 11    | [98026F7F98B8](<Notebook/Acer/Swift/Swift SF314-42/98026F7F98B8>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 11    | [304E9CF54A4D](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/304E9CF54A4D>) |
| Intel      | Celeron J4005                    | 2.00 | 11    | [81C544E74614](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614>) |
| Intel      | Celeron N4020                    | 1.10 | 11    | [56FFB83441F6](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop E410MAB_E410MA/56FFB83441F6>) |
| Intel      | Core i7-8565U                    | 1.80 | 11    | [0864712EF5A1](<Notebook/MSI/PS63/PS63 Modern 8M/0864712EF5A1>) |
| Intel      | Core i5-8265U                    | 1.60 | 11    | [CC5F553B231D](<Notebook/Lenovo/ThinkPad/ThinkPad L590 20Q7U04602/CC5F553B231D>) |
| Intel      | 12th Gen Core i9-12900K          |      | 11    | [967511C3CD54](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54>) |
| Intel      | 12th Gen Core i5-12450H          |      | 11    | [1F56DDC702EE](<Notebook/Samsung Electronics/750/750XEE/1F56DDC702EE>) |
| Intel      | Core i7-9750H                    | 2.60 | 11    | [90B9B48D8A4A](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A>) |
| Intel      | Core i7-7700K                    | 4.20 | 11    | [B7230E03FF9B](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO/B7230E03FF9B>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 11    | [A098A01ACD0B](<Desktop/Intel/DG41TY/DG41TY AAE47335-300/A098A01ACD0B>) |
| Intel      | Xeon X5650                       | 2.67 | 11    | [209AA94D6139](<Server/Dell/PowerEdge/PowerEdge R710/209AA94D6139>) |
| Intel      | Atom E3827                       | 1.74 | 11    | [28509DA82898](<Mini Pc/Sophos/SG/SG/28509DA82898>) |
| Intel      | Core i3-3217U                    | 1.80 | 11    | [75F0D02471E0](<Desktop/Intel/D33217CK/D33217CK G76541-300/75F0D02471E0>) |
| Intel      | Core i5-3570K                    | 3.40 | 11    | [46CCAEB3C831](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/46CCAEB3C831>) |
| Intel      | Core i7-3770K                    | 3.50 | 11    | [D5FB9BCC8299](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/D5FB9BCC8299>) |
| Intel      | Pentium G2020                    | 2.90 | 11    | [62181A4AA263](<Desktop/MSI/MS/MS-7788/62181A4AA263>) |
| Intel      | Xeon E3-1220L V2                 | 2.30 | 11    | [4FED9738980F](<Server/Others/CMB-A9/CMB-A9SC2/4FED9738980F>) |
| Intel      | Core i3-4170                     | 3.70 | 11    | [B6637613A7A9](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10DS0015UK/B6637613A7A9>) |
| Intel      | Core i5-4460                     | 3.20 | 11    | [6FE35DFB48FB](<Desktop/Dell/Inspiron/Inspiron 3847/6FE35DFB48FB>) |
| Intel      | Core i5-4250U                    | 1.30 | 11    | [3042A48B20AE](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/3042A48B20AE>) |
| Intel      | Pentium N3710                    | 1.60 | 11    | [501DB0F9324A](<Notebook/ASUSTek Computer/X541/X541SA/501DB0F9324A>) |
| Intel      | Atom D2550                       | 1.86 | 11    | [149584AC1589](<Desktop/CONTEC/G1/G1-EMB-CV1-iD2550/149584AC1589>) |
| Intel      | Core i5 M 520                    | 2.40 | 11    | [CDBD8C566708](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708>) |
| AMD        | GX-416RA SOC                     |      | 10    | [8179CF905F02](<Desktop/Deciso/Netboard/Netboard A10 V2/8179CF905F02>) |
| AMD        | Ryzen 9 5950X 16-Core            |      | 10    | [30A1CCEF9C6D](<Desktop/MSI/MS-7/MS-7C91/30A1CCEF9C6D>) |
| Intel      | Xeon E-2224                      | 3.40 | 10    | [8ADCB2DEFF43](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/8ADCB2DEFF43>) |
| Intel      | Core i3-9100                     | 3.60 | 10    | [B0D0D8EEB859](<Desktop/Gigabyte Technology/H310M/H310M S2H/B0D0D8EEB859>) |
| Intel      | Core i7-9700K                    | 3.60 | 10    | [0B8E30771563](<Desktop/Gigabyte Technology/Z390/Z390 UD/0B8E30771563>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 10    | [57ED8659F24B](<Desktop/ASUSTek Computer/P5/P5KPL-VM-TWPC/57ED8659F24B>) |
| Intel      | Core i5-2320                     | 3.00 | 10    | [991490F8B248](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/991490F8B248>) |
| Intel      | Core i7-5500U                    | 2.40 | 10    | [52BC095DFB2B](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/52BC095DFB2B>) |
| Intel      | Xeon E5-2620 v3                  | 2.40 | 10    | [3F969F9A8971](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/3F969F9A8971>) |
| Intel      | Celeron N3050                    | 1.60 | 10    | [A477A77FB147](<Desktop/ASUSTek Computer/All/All Series/A477A77FB147>) |
| Intel      | Core i3-6100U                    | 2.30 | 10    | [1279B1AC4E76](<Notebook/Gigabyte Technology/GB-BSi3/GB-BSi3A-6100/1279B1AC4E76>) |
| Intel      | Celeron J3355                    | 2.00 | 10    | [19E0C45EF6F5](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5>) |
| Intel      | Core i3-6100T                    | 3.20 | 10    | [E5BBD8484B41](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41>) |
| Intel      | Core i5-6600                     | 3.30 | 10    | [641267472D3E](<Desktop/Dell/OptiPlex/OptiPlex 5040/641267472D3E>) |
| AMD        | GX-420MC SOC                     |      | 9     | [66D580EA81A4](<Desktop/Deciso/Netboard/Netboard A10 GEN2 Model G/66D580EA81A4>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 9     | [284E69188279](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 9     | [D2F4997BDC50](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ALC05 82LN/D2F4997BDC50>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 9     | [FEA87D7859AC](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX431DA_UM431DA/FEA87D7859AC>) |
| Intel      | Core i3-8130U                    | 2.20 | 9     | [94CBCA0E43E1](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1>) |
| Intel      | Core i7-7600U                    | 2.80 | 9     | [D1B32CCBB59E](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HMS04P00/D1B32CCBB59E>) |
| Intel      | Core i5-9400                     | 2.90 | 9     | [B1655A8348EC](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 9     | [397F866BA692](<Notebook/Lenovo/ThinkPad/ThinkPad T470p 20J7S0BR00/397F866BA692>) |
| Intel      | Xeon E3-1220 v6                  | 3.00 | 9     | [013B4CDFD8CC](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC>) |
| Intel      | Genuine CPU                      |      | 9     | [53CC7CFA1A08](<Notebook/Samsung Electronics/Q430/Q430-Q530/53CC7CFA1A08>) |
| Intel      | Core i5-2410M                    | 2.30 | 9     | [C82A08E0A847](<Notebook/Sony/VPCSB11/VPCSB11FX/C82A08E0A847>) |
| Intel      | Core i5-2430M                    | 2.40 | 9     | [025B1A353D7F](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/025B1A353D7F>) |
| Intel      | Atom E3826                       | 1.46 | 9     | [6744EE7F5532](<Mini Pc/Sophos/SG/SG/6744EE7F5532>) |
| Intel      | Core i3-3227U                    | 1.90 | 9     | [875F73879468](<Mini Pc/ZOTAC/ZBOX-ID42/ZBOX-ID42-BE/875F73879468>) |
| Intel      | Core i5-3317U                    | 1.70 | 9     | [F5C18D527820](<Notebook/Samsung Electronics/700T1/700T1C/F5C18D527820>) |
| Intel      | Core i7-3630QM                   | 2.40 | 9     | [7B74CE72D78E](<Notebook/Lenovo/ThinkPad/ThinkPad T530 24297XG/7B74CE72D78E>) |
| Intel      | Core i7-4500U                    | 1.80 | 9     | [84732EE686BD](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20CD0038MB/84732EE686BD>) |
| Intel      | Celeron 3855U                    | 1.60 | 9     | [9CF135372FE7](<Desktop/Intel/SKYBAY/SKYBAY/9CF135372FE7>) |
| Intel      | Celeron G3900                    | 2.80 | 9     | [03969864EEC6](<Desktop/Gigabyte Technology/H110/H110-D3A/03969864EEC6>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 9     | [2BD0319875C3](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3>) |
| Intel      | Atom C3508                       | 1.60 | 9     | [B5B03B155640](<Firewall/Sophos/SG/SG/B5B03B155640>) |
| AMD        | Athlon 5350 APU with Radeon R3   |      | 8     | [4BA6B6BAA584](<Desktop/Acer/Veriton/Veriton X2120G/4BA6B6BAA584>) |
| AMD        | GX-217GA SOC with Radeon HD G... |      | 8     | [910C910B916A](<Desktop/Fujitsu/FUTRO/FUTRO S720/910C910B916A>) |
| AMD        | GX-424CC SOC with Radeon R5E ... |      | 8     | [A79450FE3567](<Desktop/Fujitsu/FUTRO/FUTRO S930/A79450FE3567>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 8     | [6B516E615857](<Notebook/Sony/VPCYB45/VPCYB45JB/6B516E615857>) |
| AMD        | Ryzen 3 3100 4-Core              |      | 8     | [EF0D0832952B](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/EF0D0832952B>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 8     | [391D7C198E40](<Desktop/MSI/MS-7/MS-7C37/391D7C198E40>) |
| AMD        | Ryzen 9 3950X 16-Core            |      | 8     | [5D2BD7522E5C](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO/5D2BD7522E5C>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 8     | [13DA4A6E533F](<Desktop/BESSTAR Tech/UM/UM350/13DA4A6E533F>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 8     | [62E46F1F6D6F](<Notebook/Lenovo/Legion/Legion S7 15ACH6 82K8/62E46F1F6D6F>) |
| Intel      | Core i7-1065G7                   | 1.30 | 8     | [CF8B97A58534](<Notebook/Acer/Swift/Swift SF313-52/CF8B97A58534>) |
| Intel      | Core i7-8650U                    | 1.90 | 8     | [D0D1FC93D3D7](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 6th 20KGS6J30W/D0D1FC93D3D7>) |
| Intel      | Core i3-10110U                   | 2.10 | 8     | [D70ADA8B97ED](<Desktop/Thomas-Krenn.AG/LES/LES network 6L/D70ADA8B97ED>) |
| Intel      | Core i7-8665U                    | 1.90 | 8     | [411845E48AFC](<Notebook/Dell/Latitude/Latitude 5400/411845E48AFC>) |
| Intel      | Pentium Gold G7400               |      | 8     | [91009F733814](<Desktop/ASRock/Z690/Z690M-ITX-ax/91009F733814>) |
| Intel      | Core i5-8400T                    | 1.70 | 8     | [1F40335DE972](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/1F40335DE972>) |
| Intel      | Core i7-10700                    | 2.90 | 8     | [9AABBF15235B](<Desktop/ASRock/H470/H470M-STX/9AABBF15235B>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
|            | Module SODIMM                | 4 GB     | DDR3 | 1333 | 126   | [1A431BAA436D](<Desktop/PC Engines/APU/APU2/1A431BAA436D>) |
|            | 123456789012345678 DIMM L... | 1536 MB  |      | 2400 | 122   | [3487CD2A0FE8](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 79    | [646ECE0C848D](<Notebook/Fujitsu/CELSIUS/CELSIUS H730/646ECE0C848D>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 66    | [F784FC43DD4A](<Notebook/Dell/Latitude/Latitude E5450/F784FC43DD4A>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 54    | [0D6CEE283756](<Desktop/Others/Others/Others/0D6CEE283756>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 54    | [116CFBBA835E](<Notebook/Samsung Electronics/305E4/305E4A-305E5A-305E7A/116CFBBA835E>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 53    | [BD1A816BB8CA](<Desktop/MSI/MS/MS-7788/BD1A816BB8CA>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 48    | [A1AC5CC7301E](<Desktop/Fujitsu/FUTRO/FUTRO S920/A1AC5CC7301E>) |
|            | Module(s) DIMM               | 4 GB     |      |      | 46    | [5C0556A6AFDF](<Desktop/ADI Engineering/RCC-VE/RCC-VE/5C0556A6AFDF>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 42    | [ABBAD64ECA84](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 40    | [773B06736C0B](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 40    | [DA2700E6778C](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 37    | [0189D3C3009B](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 37    | [92E6177F9568](<Desktop/Advantech/UTC-520/UTC-520C/92E6177F9568>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1600 | 37    | [096EAD705813](<Mini Pc/AMI/Aptio/Aptio CRB/096EAD705813>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 37    | [0FD1E037978C](<Notebook/Lenovo/ThinkPad/ThinkPad L450 20DSS1S402/0FD1E037978C>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1867 | 36    | [3520928A502A](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS04200/3520928A502A>) |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 2667 | 33    | [913B173AD9EB](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509JA_X509JA/913B173AD9EB>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 32    | [EC084C5059C4](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/EC084C5059C4>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 32    | [31A33F545802](<Desktop/Fujitsu/FMVW77/FMVW77MB/31A33F545802>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 31    | [0D48ADEA90BB](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 31    | [3EA896404AEF](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/3EA896404AEF>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 30    | [17B230FDF0AF](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi3/17B230FDF0AF>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 29    | [810780DBBB1C](<Firewall/Sophos/SG/SG/810780DBBB1C>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1600 | 29    | [08DBAE3B5E67](<Server/Supermicro/Super/Super Server/08DBAE3B5E67>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 28    | [B41A8964B213](<Desktop/Dell/OptiPlex/OptiPlex 3020/B41A8964B213>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 |      | 28    | [D47A564CEC1C](<Desktop/Intel/H/H61/D47A564CEC1C>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 27    | [F0BF9405D436](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B60061MB/F0BF9405D436>) |
| Transcend  | TS1GLH64V6BL SODIMM          | 8 GB     | DDR4 | 2667 | 27    | [8CF3D0B8B46A](<Notebook/Deciso/NetBoard-A/NetBoard-A10/8CF3D0B8B46A>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 26    | [977AFD28A6C7](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/977AFD28A6C7>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 26    | [C70F5DBC2D60](<Desktop/Dell/OptiPlex/OptiPlex 7020/C70F5DBC2D60>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 26    | [A906B312696E](<Desktop/ASRock/G41/G41M-GS3/A906B312696E>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 26    | [E36B3935C888](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs1xx/E36B3935C888>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 26    | [B2969C7863CE](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/B2969C7863CE>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3200 | 25    | [846C1320086A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 25    | [B0D09A247CBD](<Notebook/Lenovo/ThinkPad/ThinkPad T430u 33522D5/B0D09A247CBD>) |
|            | Module                       | 8 GB     |      | 1600 | 25    | [B3E6FA2B6696](<Desktop/Protectli/FW4/FW4B/B3E6FA2B6696>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 24    | [90F085143625](<Desktop/Others/Others/Others/90F085143625>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 23    | [16DE1B8D4A3E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000YMX/16DE1B8D4A3E>) |
| Micron     | 8KTF51264HZ-1G9P1 SODIMM     | 4 GB     | DDR3 | 1867 | 23    | [3A4A89D57DB6](<Desktop/Fujitsu/FUTRO/FUTRO S920/3A4A89D57DB6>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 22    | [646ECE0C848D](<Notebook/Fujitsu/CELSIUS/CELSIUS H730/646ECE0C848D>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 667  | 22    | [B8D7D8366BA0](<Desktop/PC Engines/apu/apu4/B8D7D8366BA0>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 22    | [D6765403633D](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/D6765403633D>) |
| Samsung    | M471B1G73DB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 22    | [B01DE72F7AFE](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 22    | [582E158CFA66](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 22    | [6EF6C3723B2F](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4243F39/6EF6C3723B2F>) |
| Crucial    | CT102464BF160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 21    | [FB549302E487](<Desktop/Others/Others/Others/FB549302E487>) |
| SK hynix   | HMT451U6BFR8A-PB DIMM        | 4 GB     | DDR3 | 1600 | 21    | [00625658453F](<Desktop/Dell/OptiPlex/OptiPlex 3020/00625658453F>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 21    | [FA8DF9417D6B](<Desktop/Dell/OptiPlex/OptiPlex 9010/FA8DF9417D6B>) |
| Samsung    | M471B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 21    | [2CC23D52E14F](<Mini Pc/AMI/Aptio/Aptio CRB/2CC23D52E14F>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 21    | [753EE6D71A9C](<Notebook/Acer/Nitro/Nitro AN515-54/753EE6D71A9C>) |
| Crucial    | CT102464BF160B.M16 DIMM      | 8 GB     | DDR3 | 1600 | 20    | [53C7F6F288FD](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/53C7F6F288FD>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 20    | [88A73B2C8E7E](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 20    | [E5E4D871BE14](<Desktop/Others/Others/Others/E5E4D871BE14>) |
| Kimtigo    | KT8GS3EDF SODIMM             | 8 GB     | DDR3 | 1600 | 19    | [87173F8A684A](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/87173F8A684A>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 800  | 19    | [5B265979975E](<Desktop/Others/Others/Others/5B265979975E>) |
| Samsung    | M393B1G70QH0-YK0 DIMM        | 8192 MB  | DDR3 | 1600 | 19    | [2173A116CDDD](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 19    | [CC5F553B231D](<Notebook/Lenovo/ThinkPad/ThinkPad L590 20Q7U04602/CC5F553B231D>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     | DDR3 | 1333 | 19    | [D0957E945A9B](<Notebook/Hewlett-Packard/G/G62/D0957E945A9B>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 18    | [8D91CF576B8C](<Mini Pc/Wortmann AG/1009834/1009834_2160112/8D91CF576B8C>) |
| Samsung    | M471B5173QH0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 18    | [16B5E32F691C](<Desktop/Others/YL-J3160/YL-J3160L4/16B5E32F691C>) |
| SK hynix   | HMT451U6BFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 17    | [B091C964714D](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHA0X9LS/B091C964714D>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 2667 | 17    | [C93BC8E8AB68](<Desktop/Dell/OptiPlex/OptiPlex 7060/C93BC8E8AB68>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 17    | [F5C18D527820](<Notebook/Samsung Electronics/700T1/700T1C/F5C18D527820>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 17    | [3E9A6AB48C81](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/3E9A6AB48C81>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 667  | 17    | [8E702FFCE116](<Desktop/ASUSTek Computer/P5E-VM/P5E-VM SE/8E702FFCE116>) |
|            | Module SODIMM                | 8 GB     | DDR3 | 1600 | 17    | [0189D3C3009B](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 17    | [45A5AF223B49](<Desktop/Techvision/TVI7309/TVI7309X/45A5AF223B49>) |
| SK hynix   | HMT351U6EFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 16    | [58B8C5BDE4AF](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/58B8C5BDE4AF>) |
| Kingston   | 99U5469-045.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 16    | [4F433C551703](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 16    | [CC460235E058](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058>) |
| Samsung    | M378B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 16    | [58B8C5BDE4AF](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/58B8C5BDE4AF>) |
| Samsung    | M391B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 16    | [C3FCB4EC4FB7](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7>) |
| Samsung    | M393A2G40DB0-CPB DIMM        | 16 GB    | DDR4 | 2133 | 16    | [73426A08BED9](<Server/Supermicro/Super/Super Server/73426A08BED9>) |
| Crucial    | CT102464BA160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 15    | [8FCF1BD7C6F6](<Desktop/MSI/MS/MS-7922/8FCF1BD7C6F6>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1600 | 15    | [2B5473C76A7D](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 15    | [51D56BADAD82](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 800  | 15    | [08DD4DB5BD47](<Desktop/Others/Others/Others/08DD4DB5BD47>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 14    | [FEC2A61DDF2F](<Notebook/Acer/Aspire/Aspire E3-112/FEC2A61DDF2F>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 1333 | 14    | [3BB03503D97A](<Desktop/PC Engines/APU/APU2/3BB03503D97A>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 14    | [AB58D13F8BD8](<Desktop/Dell/OptiPlex/OptiPlex 780/AB58D13F8BD8>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 13    | [5C14E92D5780](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1600 | 13    | [72252A65C123](<Desktop/MSI/MS/MS-7850/72252A65C123>) |
| G.Skill    | F4-2400C16-8GRS SODIMM       | 8 GB     | DDR4 | 2400 | 13    | [1C5BA913A08B](<Mini Pc/Intel/NUC7i5BNB/NUC7i5BNB J31144-305/1C5BA913A08B>) |
| SK hynix   | HMT325U6CFR8C-PB DIMM        | 2 GB     | DDR3 | 1600 | 13    | [188D1EFAA755](<Desktop/Dell/OptiPlex/OptiPlex 7020/188D1EFAA755>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 13    | [E8819DE1DB7B](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 13    | [75E712C98F14](<Notebook/Hewlett-Packard/2000/2000/75E712C98F14>) |
| Micron     | Module Row Of Chips LPDDR4   | 8 GB     |      | 3200 | 13    | [DC27A10D2225](<Desktop/GoWin Solution/R86/R86S/DC27A10D2225>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 13    | [DD5639A44B24](<Desktop/ASUSTek Computer/M4/M4A78/DD5639A44B24>) |
|            | Module DIMM                  | 8 GB     |      | 1333 | 13    | [D368C2DF58A0](<Desktop/ASUSTek Computer/Rampage/Rampage II Extreme/D368C2DF58A0>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 13    | [9AD7E9EC1C99](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G1 MT/9AD7E9EC1C99>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 13    | [0D84D83C0828](<Desktop/Others/Others/Others/0D84D83C0828>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 13    | [BCFFA48DEF38](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 14-bf0xx/BCFFA48DEF38>) |
| Crucial    | CT16G4SFD824A.C16FDD SODIMM  | 16 GB    | DDR4 | 2400 | 12    | [6E992B41BC1D](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3200 | 12    | [C36158131652](<Desktop/Gigabyte Technology/X570/X570 AORUS PRO/C36158131652>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3200 | 12    | [A2C8D1D5308F](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/A2C8D1D5308F>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 12    | [F4DD26C4B19C](<Desktop/Dell/OptiPlex/OptiPlex 3020/F4DD26C4B19C>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 2400 | 12    | [628DE1D18663](<Desktop/ASUSTek Computer/PRIME/PRIME B560M-A/628DE1D18663>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 12    | [B1A7D0E55D2F](<Desktop/Gigabyte Technology/G31/G31M-ES2L/B1A7D0E55D2F>) |
| Samsung    | M378B1G73DB0-CK0 DIMM        | 8 GB     | DDR3 | 1600 | 12    | [67A31DE42401](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/67A31DE42401>) |
| Samsung    | M378B5273CH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 12    | [713DEF408BD9](<Desktop/Dell/OptiPlex/OptiPlex 3020/713DEF408BD9>) |
| Samsung    | M471B1G73EB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 12    | [28509DA82898](<Mini Pc/Sophos/SG/SG/28509DA82898>) |
| Samsung    | Module DIMM                  | 8 GB     | DDR4 | 2133 | 12    | [C940FCA75474](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/C940FCA75474>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 12    | [700E5ED9C506](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/700E5ED9C506>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 12    | [09CD68C8BFFB](<Desktop/Dell/OptiPlex/OptiPlex 7060/09CD68C8BFFB>) |
| SK hynix   | HMA81GU6AFR8N-UH DIMM        | 8 GB     | DDR4 | 2400 | 12    | [DECD973F3D35](<Desktop/Dell/Inspiron/Inspiron 3880/DECD973F3D35>) |
| Super T... | SUPERTALENT02 DIMM           | 4 GB     | DDR3 | 1600 | 12    | [326C5B4DA0B2](<Desktop/Equus Computer Systems/Nobilis/Nobilis/326C5B4DA0B2>) |
| Corsair    | CML8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 11    | [584D4BE57ECB](<Desktop/ASUSTek Computer/H110I-PLUS/H110I-PLUS D3/584D4BE57ECB>) |
| Crucial    | BLS4G3D1609DS1S00. DIMM      | 4 GB     | DDR3 | 1600 | 11    | [2447DC6632F6](<Desktop/MSI/MS/MS-7923/2447DC6632F6>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 11    | [8ADBA957E4CE](<Desktop/Fujitsu/FUTRO/FUTRO S920/8ADBA957E4CE>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 11    | [B34B31EC74C2](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 USDT/B34B31EC74C2>) |
| Kingston   | 99U5428-018.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 11    | [E97B8F7ECEA0](<Desktop/Protectli/FW2/FW2B/E97B8F7ECEA0>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3200 | 11    | [D4F85CE4A0A4](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO WIFI/D4F85CE4A0A4>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 11    | [7EA279221D69](<Notebook/Apple/MacBookAir1/MacBookAir1,1/7EA279221D69>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 800  | 11    | [8212C6F20BD6](<Firewall/Sophos/UTM/UTM/8212C6F20BD6>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 11    | [9A0A4A699834](<Notebook/Panasonic/CF-30/CF-30KAPAXAM/9A0A4A699834>) |
|            | Module DIMM SDRAM            | 4 GB     |      |      | 11    | [E3E28FDE7220](<Desktop/CheckPoint/T-180/T-180-00/E3E28FDE7220>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 11    | [BD0ED8EF7DB5](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LBS0FH00/BD0ED8EF7DB5>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 11    | [484652E02452](<Desktop/Protectli/FW/FW6/484652E02452>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 11    | [A27F623F9015](<Notebook/Dell/Precision/Precision 7720/A27F623F9015>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 11    | [E6B678FB89BC](<Notebook/Dell/Precision/Precision M4500/E6B678FB89BC>) |
| Transcend  | TS1GLH64V6B3 SODIMM          | 8 GB     | DDR4 | 1333 | 11    | [5690A52166B9](<Notebook/Deciso/Netboard/Netboard A20/5690A52166B9>) |
| Corsair    | CMZ16GX3M2A1600C10 DIMM      | 8 GB     | DDR3 | 1600 | 10    | [2447DC6632F6](<Desktop/MSI/MS/MS-7923/2447DC6632F6>) |
| Crucial    | CT16G4SFRA266.M16FRS SODIMM  | 16 GB    | DDR4 | 2667 | 10    | [C27B3124C077](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L7002CUS/C27B3124C077>) |
| Crucial    | CT4G4SFS824A.C8FF SODIMM     | 4 GB     | DDR4 | 2666 | 10    | [7C58F64C2AFE](<Desktop/Protectli/FW/FW6/7C58F64C2AFE>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 10    | [A2FE41ACF78C](<Desktop/Dell/OptiPlex/OptiPlex 7010/A2FE41ACF78C>) |
| Crucial    | CT51264BF160BJ.C8F SODIMM    | 4 GB     | DDR3 | 1600 | 10    | [B2D974E7849B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1334 | 10    | [A98402A68E93](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2518C3U/A98402A68E93>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 10    | [CF46071DFEB6](<Desktop/Fujitsu/FUTRO/FUTRO S920/CF46071DFEB6>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 10    | [6CA67514147C](<Desktop/Wortmann AG/terra/terra MiniPC/6CA67514147C>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 10    | [011635FB7E4D](<Notebook/Google/Peppy/Peppy/011635FB7E4D>) |
| Kingston   | KF3200C16D4/16GX DIMM        | 16 GB    | DDR4 | 3200 | 10    | [BD8BD7D4DA30](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30>) |
| Kingston   | KHX1600C9S3L/4G SODIMM       | 4 GB     | DDR3 | 1600 | 10    | [BF425CFC0EFE](<Desktop/Gigabyte Technology/GB-BXi7/GB-BXi7-5775R/BF425CFC0EFE>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 10    | [822DD2DA99EA](<Notebook/Dell/Latitude/Latitude 5591/822DD2DA99EA>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 10    | [C6979EAEDA22](<Desktop/Techvision/TVI7309/TVI7309X/C6979EAEDA22>) |
| Ramaxel    | RMR5030MN68F9F1600 DIMM      | 4 GB     | DDR3 | 1600 | 10    | [DFDBA5E1859E](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 10    | [AD023293EF8F](<Notebook/Lenovo/G400s/G400s 20244/AD023293EF8F>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 10    | [E7BEAAFD5268](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 10    | [991490F8B248](<Desktop/ASUSTek Computer/P8Z68-V/P8Z68-V LX/991490F8B248>) |
| Samsung    | M391A2K43BB1-CTD DIMM        | 16 GB    | DDR4 | 3200 | 10    | [8E3B68877E47](<Server/Supermicro/Super/Super Server/8E3B68877E47>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 10    | [1C68DE0A8C5A](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming F15 FX506LH_FX506LH/1C68DE0A8C5A>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 10    | [ACBB8335DDB2](<Desktop/ASRock/4X4-4000/4X4-4000 Series/ACBB8335DDB2>) |
| Samsung    | Module DIMM                  | 4 GB     | DDR4 | 2133 | 10    | [14C09DF0E49F](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/14C09DF0E49F>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2133 | 10    | [2BD0319875C3](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 10    | [ABD1D8237899](<Desktop/Others/Others/Others/ABD1D8237899>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM      | 2 GB     | DDR2 | 975  | 10    | [0D2F6FFDCD3E](<Notebook/Dell/Studio/Studio 1537/0D2F6FFDCD3E>) |
| A-DATA     | Module DIMM                  | 4 GB     | DDR4 | 1866 | 9     | [B5B03B155640](<Firewall/Sophos/SG/SG/B5B03B155640>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3000 | 9     | [A058A7EF96C1](<Desktop/MSI/MS-7/MS-7C87/A058A7EF96C1>) |
| Corsair    | CMK32GX4M2A2666C16 DIMM      | 16 GB    | DDR4 | 3000 | 9     | [B137BD3A9552](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-I GAMING/B137BD3A9552>) |
| Crucial    | CT8G4SFS824A.C8FP SODIMM     | 8 GB     | DDR4 | 2400 | 9     | [4918EE420737](<Desktop/Protectli/VP/VP2410/4918EE420737>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 9     | [D4860BF08C58](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2347GZU/D4860BF08C58>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 9     | [364E3B4375AA](<Desktop/Fujitsu/FUTRO/FUTRO S920/364E3B4375AA>) |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 9     | [6F76C07AE338](<Desktop/ASRock/B85/B85M-DGS/6F76C07AE338>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 9     | [C8D336657732](<Notebook/Dell/Inspiron/Inspiron 5558/C8D336657732>) |
| Micron     | 9ASF1G72AZ-2G3B1 DIMM        | 8 GB     | DDR4 | 2400 | 9     | [A0E6ECE7A60C](<Desktop/Dell/PowerEdge/PowerEdge T30/A0E6ECE7A60C>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 9     | [3A7D355EEBE4](<Notebook/Pegatron/T12/T12Ah/3A7D355EEBE4>) |
|            | Module DIMM                  | 4 GB     |      | 1600 | 9     | [BB62608DEE46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/BB62608DEE46>) |
|            | Module FB-DIMM               | 4 GB     | DDR2 | 667  | 9     | [FFA4A8B12A92](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92>) |
|            | Module(s) DIMM               | 8 GB     |      |      | 9     | [85EA4DD31903](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/85EA4DD31903>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 9     | [DA069FB4F97A](<Desktop/ASRock/E350/E350M1/DA069FB4F97A>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 9     | [EFBEE07E8E43](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14ITL05 82FE/EFBEE07E8E43>) |
| Samsung    | M471B1G73DH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 9     | [A3DBD4D871FE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 9     | [269B716399A8](<Notebook/Lenovo/B590/B590 20208/269B716399A8>) |
| Samsung    | Module SODIMM                | 2 GB     | DDR3 | 1067 | 9     | [67709B10CE79](<All In One/Apple/iMac10/iMac10,1/67709B10CE79>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2400 | 9     | [DA2700E6778C](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 9     | [B5081BB45457](<Notebook/Medion/E/E15415/B5081BB45457>) |
| SK hynix   | HMT351U7BFR8A-H9 DIMM        | 4 GB     | DDR3 | 1333 | 9     | [71ACCE4AED93](<Desktop/Dell/Precision/Precision WorkStation T3500/71ACCE4AED93>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 32 GB    | DDR4 | 3200 | 9     | [4EC4B3A73B66](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 8     | [6C22C71F3BF1](<Notebook/Samsung Electronics/NC210/NC210-NC110/6C22C71F3BF1>) |
| Corsair    | CMV4GX3M1A1333C9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [A72462873DBB](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB>) |
| Corsair    | CMX8GX3M2A1333C9 DIMM        | 4 GB     |      | 1333 | 8     | [38D0B4D8000D](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D>) |
| Crucial    | CT8G4SFRA32A.M4FF SODIMM     | 8 GB     | DDR4 | 3200 | 8     | [81A2DE4E6553](<Desktop/Techvision/TVI7309/TVI7309X/81A2DE4E6553>) |
|            | DDR4 NB 8G 2400 SODIMM       | 8 GB     | DDR4 | 2133 | 8     | [44A8A11B3BDA](<Desktop/AZW/Green/Green G1/44A8A11B3BDA>) |
| G.Skill    | F4-2400C16-4GRS SODIMM       | 4 GB     | DDR4 | 2400 | 8     | [F914C37F4CEB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/F914C37F4CEB>) |
| SK hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [711AEC50914C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/711AEC50914C>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 8     | [AE411B80FDD5](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 8     | [D59156C0581D](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C720/D59156C0581D>) |
| Kingston   | 99U5700-028.A00G SODIMM      | 8 GB     | DDR4 | 2400 | 8     | [0108DB586B13](<Desktop/Yanling/YL-KBR6/YL-KBR6L/0108DB586B13>) |
| Kingston   | KHX2400C14S4/16G SODIMM      | 16 GB    | DDR4 | 2400 | 8     | [722F4261A23A](<Desktop/Others/Others/Others/722F4261A23A>) |
| Kingston   | KNWMX1-ETB SODIMM            | 4 GB     | DDR3 | 1600 | 8     | [1ED960B9F220](<Notebook/Dell/Inspiron/Inspiron 15-3552/1ED960B9F220>) |
| Micron     | 18KSF1G72AZ-1G6P1 DIMM       | 8 GB     | DDR3 | 1600 | 8     | [C306D0A87402](<Server/Dell/PowerEdge/PowerEdge R220/C306D0A87402>) |
| Micron     | 36ASF2G72PZ-2G1A2 DIMM       | 16 GB    | DDR4 | 2133 | 8     | [01583CC46F7E](<Server/Supermicro/Super/Super Server/01583CC46F7E>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 8     | [FFA6D6E4D3C7](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7>) |
| Micron     | 8ATF1G64AZ-2G6E1 DIMM        | 8 GB     | DDR4 | 2667 | 8     | [AC9368A7D243](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243>) |
| Micron     | 8ATF1G64HZ-3G2R1 SODIMM      | 8 GB     | DDR4 | 3200 | 8     | [AF56A25ED207](<Desktop/Techvision/TVI7309/TVI7309X/AF56A25ED207>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 8     | [83961A908C73](<Notebook/Acer/Aspire/Aspire 5742/83961A908C73>) |
| Nanya      | NT4GC64B8HG0NF-DI DIMM       | 4 GB     | DDR3 | 1600 | 8     | [ECCDB090F800](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3209D9U/ECCDB090F800>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 667  | 8     | [A098A01ACD0B](<Desktop/Intel/DG41TY/DG41TY AAE47335-300/A098A01ACD0B>) |
|            | Module DIMM                  | 2 GB     | DDR2 |      | 8     | [1AFE69015387](<Desktop/Pegatron/IPM41/IPM41-D3/1AFE69015387>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1066 | 8     | [4FE486AA9D43](<Desktop/Intel/D2500HN/D2500HN AAG81480-500/4FE486AA9D43>) |
|            | Module DIMM                  | 8 GB     | DDR4 | 2400 | 8     | [3D854A7B1556](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556>) |
| Ramaxel    | RMR5030EF68F9W1600 DIMM      | 4 GB     | DDR3 | 1600 | 8     | [BF32CF4AE8C8](<Desktop/Lenovo/H515/H515 10125/BF32CF4AE8C8>) |
| Ramaxel    | RMR5040ED58E9W1600 DIMM      | 4 GB     | DDR3 | 1600 | 8     | [9A6BFC6540AF](<Desktop/Hewlett-Packard/p7/p7-1154/9A6BFC6540AF>) |
| Samsung    | M378A5244CB0-CRC DIMM        | 4 GB     | DDR4 | 2666 | 8     | [3C676EC0E951](<Desktop/Dell/OptiPlex/OptiPlex 7050/3C676EC0E951>) |
| Samsung    | M378B5173EB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [AE1164BF35BB](<Desktop/Dell/OptiPlex/OptiPlex 3020/AE1164BF35BB>) |
| Samsung    | M391B5273CH0-YH9 DIMM        | 4 GB     | DDR3 | 1333 | 8     | [58573A8F2438](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438>) |
| Samsung    | M391B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [509895109D80](<Desktop/Supermicro/X9/X9SCL-X9SCM/509895109D80>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 8     | [988E312ED9CE](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S29E0T/988E312ED9CE>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 8     | [E2372EFC6D66](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 8     | [32F9A01194D0](<Notebook/Hewlett-Packard/Notebook/Notebook/32F9A01194D0>) |
| Samsung    | M471B5173DB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [7742E54655A6](<Desktop/Protectli/FW4/FW4B/7742E54655A6>) |
| Samsung    | M471B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [AF93BF149B22](<Mini Pc/Broachlink/NOAH/NOAH V2 E3845/AF93BF149B22>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     |      | 1067 | 8     | [79AF40064822](<Notebook/Acer/Aspire/Aspire 7738/79AF40064822>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 8     | [08F8F58B7E7F](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537N24/08F8F58B7E7F>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 8     | [C601B6CDC429](<Notebook/Shuttle/DS/DS437T/C601B6CDC429>) |
| SK hynix   | HMA451U6AFR8N-TF DIMM        | 4 GB     | DDR4 | 2133 | 8     | [3D1F66AD891A](<Desktop/Dell/OptiPlex/OptiPlex 7040/3D1F66AD891A>) |
| SK hynix   | HMA81GU6JJR8N-VK DIMM        | 8 GB     | DDR4 | 2667 | 8     | [6BC81BE1C8AC](<Desktop/Dell/OptiPlex/OptiPlex 7060/6BC81BE1C8AC>) |
| SK hynix   | Module SODIMM                | 2 GB     | DDR3 | 1600 | 8     | [D33FDFE25C32](<Notebook/Apple/MacBookAir5/MacBookAir5,1/D33FDFE25C32>) |
| A-DATA     | Module SODIMM                | 4 GB     | DDR3 | 1600 | 7     | [3195F9C34BC5](<Firewall/Sophos/SG/SG/3195F9C34BC5>) |
|            | 123456789012345678 SODIMM... | 2 GB     |      | 2133 | 7     | [FB3B23285CAC](<Convertible/BESSTAR Tech/GK/GK45/FB3B23285CAC>) |
|            | BRBN1G48G16C2666 SODIMM      | 8 GB     | DDR4 | 2400 | 7     | [F6BD223DB78D](<Desktop/Others/Others/Others/F6BD223DB78D>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3200 | 7     | [C0F6B83E60A9](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9>) |
| Crucial    | CT51264BF160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 7     | [880CB52E6BC3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M53 10DES00F00/880CB52E6BC3>) |
| Crucial    | CT51264BF160BJ.M8F DIMM      | 4 GB     | DDR3 | 1600 | 7     | [A4D89EA96DC4](<Server/Supermicro/Super/Super Server/A4D89EA96DC4>) |
| G.Skill    | F3-1600C9-8GXM DIMM          | 8 GB     | DDR3 | 1600 | 7     | [35F33329CB60](<Desktop/ASUSTek Computer/All/All Series/35F33329CB60>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3000 | 7     | [2E6510A36D4C](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/2E6510A36D4C>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 7     | [284E69188279](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 7     | [A8CF95C34089](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/A8CF95C34089>) |
| SK hynix   | HMT325U6BFR8C-H9 DIMM        | 2 GB     | DDR3 | 1333 | 7     | [AC9F58576E1B](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B>) |
| SK hynix   | HMT41GU7BFR8A-PB DIMM        | 8 GB     | DDR3 | 1600 | 7     | [9E8019EC4938](<Server/Others/A/A04/9E8019EC4938>) |
| SK hynix   | Module DIMM                  | 8 GB     | DDR4 | 2133 | 7     | [C940FCA75474](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/C940FCA75474>) |
| Kingston   | 9965525-116.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 7     | [CDCF2A093383](<Desktop/ASRock/E3/E3C226D2I/CDCF2A093383>) |
| Kingston   | 9965745-002.A00G DIMM        | 16 GB    | DDR4 | 3000 | 7     | [69AAAA30BEFA](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 7     | [3FDB45F5C47B](<Desktop/ASRock/A75/A75M-HVS/3FDB45F5C47B>) |
| Kingston   | CBD26D4S9S1ME-8 SODIMM       | 8 GB     | DDR4 | 2667 | 7     | [DCBED3DDCE53](<Desktop/Yanling/YL-KBR6/YL-KBR6L/DCBED3DDCE53>) |
| Kingston   | CBD26D4S9S8K1C-8 SODIMM      | 8 GB     | DDR4 | 2667 | 7     | [99A90100BE42](<Notebook/BESSTAR Tech/U/U820/99A90100BE42>) |
| Kingston   | KF2666C15S4/8G SODIMM        | 8 GB     | DDR4 | 2667 | 7     | [859216D2030F](<Desktop/Techvision/TVI7309/TVI7309X/859216D2030F>) |
| Kingston   | KHX1600C10D3/ DIMM           | 8 GB     | DDR3 | 1866 | 7     | [01BF845968C7](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/01BF845968C7>) |
| Kingston   | KHX2400C15/16G DIMM          | 16 GB    | DDR4 | 2400 | 7     | [0E3AB23CF5CC](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC>) |
| Kingston   | KHX2666C15S4/8G SODIMM       | 8 GB     | DDR4 | 2667 | 7     | [1279B1AC4E76](<Notebook/Gigabyte Technology/GB-BSi3/GB-BSi3A-6100/1279B1AC4E76>) |
| Micron     | 16JTF51264AZ-1G4M1 DIMM      | 4 GB     | DDR3 | 1333 | 7     | [9A6BFC6540AF](<Desktop/Hewlett-Packard/p7/p7-1154/9A6BFC6540AF>) |
| Micron     | 16KTF1G64HZ-1G6N1 SODIMM     | 8 GB     | DDR3 | 1600 | 7     | [C52BB6778463](<Notebook/Acer/Aspire/Aspire 5251/C52BB6778463>) |
| Micron     | 18KSF1G72AZ-1G6E1 DIMM       | 8 GB     | DDR3 | 1600 | 7     | [4FED9738980F](<Server/Others/CMB-A9/CMB-A9SC2/4FED9738980F>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 7     | [284E69188279](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 7     | [5F223CD2630E](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 7     | [AB6AFBD06501](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ITL6 82H8/AB6AFBD06501>) |
| Micron     | Module DIMM                  | 2 GB     | DDR3 | 1333 | 7     | [032FDEA67E2A](<Mini Pc/AMI/Aptio/Aptio CRB/032FDEA67E2A>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1600 | 7     | [565D06ED3C8E](<Firewall/Sophos/SG/SG/565D06ED3C8E>) |
|            | Module SODIMM                | 2 GB     | DDR3 |      | 7     | [3016737B9102](<Notebook/Sony/SVE1511/SVE1511C5E/3016737B9102>) |
|            | Module DIMM                  | 2 GB     |      |      | 7     | [4235E38A16E7](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 7     | [68889627DD42](<Desktop/Supermicro/X8/X8STi/68889627DD42>) |
|            | Module DIMM                  | 4 GB     | DDR2 | 800  | 7     | [6A773F9DB6FF](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 800  | 7     | [378DFF1E0E83](<Desktop/ASUSTek Computer/AT5/AT5NM10T-I/378DFF1E0E83>) |
|            | Module SODIMM                | 4 GB     | DDR3 |      | 7     | [3016737B9102](<Notebook/Sony/SVE1511/SVE1511C5E/3016737B9102>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 7     | [14E350AAC0F3](<Desktop/ASUSTek Computer/P5/P5LD2/14E350AAC0F3>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 7     | [57493B85D99A](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML10 v2/57493B85D99A>) |
| Ramaxel    | RMT3170MN68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 7     | [F9E4D2EC31AB](<Notebook/Lenovo/G480/G480 20149/F9E4D2EC31AB>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 7     | [4CA8BC93BA74](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74>) |
| Samsung    | M378A1K43CB2-CRC DIMM        | 8 GB     | DDR4 | 2400 | 7     | [BE025EF0F7BC](<Desktop/ASUSTek Computer/H110/H110M-CS-BR/BE025EF0F7BC>) |
| Samsung    | M378B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 7     | [BB72C05BDA1A](<Desktop/Hewlett-Packard/RP5/RP5 Retail System Model 5810/BB72C05BDA1A>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 32.0  |         | 38    | [115BD3BC38](https://bsd-hardware.info/?probe=115bd3bc38) |
| SANYO      | 45N1773 LION   | 23.2  |         | 28    | [4867945CFB](https://bsd-hardware.info/?probe=4867945cfb) |
| LGC        | 45N1127 LION   | 23.5  |         | 23    | [7D7FA2BBC9](https://bsd-hardware.info/?probe=7d7fa2bbc9) |
| Hewlett... | PABAS024123... | 41.6  |         | 21    | [1DF045FFD0](https://bsd-hardware.info/?probe=1df045ffd0) |
| Lenovo     | PABAS024123... | 42.8  |         | 20    | [A35053AD38](https://bsd-hardware.info/?probe=a35053ad38) |
| SANYO      | 45N1775 LION   | 23.2  |         | 19    | [4867945CFB](https://bsd-hardware.info/?probe=4867945cfb) |
| LGC        | 45N1113 LION   | 23.5  |         | 17    | [7D7FA2BBC9](https://bsd-hardware.info/?probe=7d7fa2bbc9) |
| Samsung    | Serial numb... | 48.8  |         | 16    | [E32A104392](https://bsd-hardware.info/?probe=e32a104392) |
| MSI        | BIF0_9         | 52.0  |         | 15    | [371F734E07](https://bsd-hardware.info/?probe=371f734e07) |
| OEM        | standard LiON  | 52.2  |         | 15    | [0F4DD9A9BC](https://bsd-hardware.info/?probe=0f4dd9a9bc) |
| Sony       | 45N1111 LiP    | 23.2  |         | 14    | [7750C38CD0](https://bsd-hardware.info/?probe=7750c38cd0) |
| Samsung    | SR Real LION   | 54.4  |         | 12    | [47D2204F58](https://bsd-hardware.info/?probe=47d2204f58) |
| SANYO      | 45N1023 LION   | 47.5  |         | 12    | [2FF46D6B7C](https://bsd-hardware.info/?probe=2ff46d6b7c) |
| SANYO      | 45N1001 LION   | 56.2  |         | 11    | [CF016CE514](https://bsd-hardware.info/?probe=cf016ce514) |
| Compal     | PABAS024123... | 86.0  |         | 10    | [1438237430](https://bsd-hardware.info/?probe=1438237430) |
| ASUSTek    | A32-K55        | 48.0  |         | 9     | [F9DB95D778](https://bsd-hardware.info/?probe=f9db95d778) |
| SANYO      | 42T4861 LION   | 57.7  |         | 9     | [E99738632D](https://bsd-hardware.info/?probe=e99738632d) |
| LGC        | 45N1738 LION   | 71.1  |         | 8     | [7750C38CD0](https://bsd-hardware.info/?probe=7750c38cd0) |
| SANYO      | 42T4763 LION   | 84.2  |         | 8     | [94095D4C11](https://bsd-hardware.info/?probe=94095d4c11) |
| SANYO      | 45N1767 LION   | 47.5  |         | 8     | [932E722B2D](https://bsd-hardware.info/?probe=932e722b2d) |
| SMP        | 01AV421 LiP    | 24.0  |         | 8     | [DD6C3FA0F7](https://bsd-hardware.info/?probe=dd6c3fa0f7) |
| Hewlett... | Primary LIon   | 40    |         | 7     | [7BF7249432](https://bsd-hardware.info/?probe=7bf7249432) |
| Hewlett... | Primary LIon   | 42    |         | 7     | [6CC978F98F](https://bsd-hardware.info/?probe=6cc978f98f) |
| Hewlett... | Primary LIon   | 43    |         | 7     | [5807159F51](https://bsd-hardware.info/?probe=5807159f51) |
| Hewlett... | Primary LIon   | 56    |         | 7     | [F603E648C7](https://bsd-hardware.info/?probe=f603e648c7) |
| Lenovo ... | Serial numb... | 41.4  |         | 7     | [A52E13CF4E](https://bsd-hardware.info/?probe=a52e13cf4e) |
| LGC        | 45N1011 LION   | 93.6  |         | 7     | [9A3CBE1893](https://bsd-hardware.info/?probe=9a3cbe1893) |
| Notebook   | BAT LION       | 62    |         | 7     | [0BC2996A6D](https://bsd-hardware.info/?probe=0bc2996a6d) |
| SANYO      | 45N1777 LION   | 71.3  |         | 7     | [DF62882C3B](https://bsd-hardware.info/?probe=df62882c3b) |
| SANYO      | 45N1779 LION   | 99.5  |         | 7     | [200A92D510](https://bsd-hardware.info/?probe=200a92d510) |
| SANYO      | 92P1137 LION   | 47.5  |         | 7     | [7AB5339EEE](https://bsd-hardware.info/?probe=7ab5339eee) |
| Sony       | Serial numb... | 37.5  |         | 7     | [932FACD689](https://bsd-hardware.info/?probe=932facd689) |
| State:	... | Serial numb... | 38.1  | Li-ion  | 7     | [7636A0EF8F](https://bsd-hardware.info/?probe=7636a0ef8f) |
| Hewlett... | Primary LIon   | 38    |         | 6     | [80C808DE34](https://bsd-hardware.info/?probe=80c808de34) |
| LGC        | 45N1005 LION   | 47.5  |         | 6     | [0F001F65D2](https://bsd-hardware.info/?probe=0f001f65d2) |
| LGC        | 45N1735 LION   | 47.5  |         | 6     | [BC7585EC56](https://bsd-hardware.info/?probe=bc7585ec56) |
| Notebook   | BAT LION       | 49    |         | 6     | [8A2BBA8635](https://bsd-hardware.info/?probe=8a2bba8635) |
| Notebook   | BAT LION       | 74    |         | 6     | [17D766D55A](https://bsd-hardware.info/?probe=17d766d55a) |
| NVT        | Framewo LION   | 55.0  |         | 6     | [5D6CB039EA](https://bsd-hardware.info/?probe=5d6cb039ea) |
| SANYO      | 01AV405 LION   | 26.3  |         | 6     | [56FA0D4656](https://bsd-hardware.info/?probe=56fa0d4656) |
| SANYO      | Li_Ion_4000... | 37.0  |         | 6     | [3D62C50607](https://bsd-hardware.info/?probe=3d62c50607) |
| SMP        | 00NY493 LiP    | 90.0  |         | 6     | [8CB09E34EC](https://bsd-hardware.info/?probe=8cb09e34ec) |
| SMP        | 45N1071 LiP    | 46.0  |         | 6     | [1A31B27B2A](https://bsd-hardware.info/?probe=1a31b27b2a) |
| State:	... | Serial numb... | 54.0  |         | 6     | [B480A98B22](https://bsd-hardware.info/?probe=b480a98b22) |
| Hewlett... | Primary LIon   | 45    |         | 5     | [BABE4BB620](https://bsd-hardware.info/?probe=babe4bb620) |
| Hewlett... | Serial numb... | 12.0  |         | 5     | [E0C8E95E52](https://bsd-hardware.info/?probe=e0c8e95e52) |
| LGC        | 01AV478 LiP    | 57.0  |         | 5     | [AA70F61A87](https://bsd-hardware.info/?probe=aa70f61a87) |
| LGC        | 02DL007 LiP    | 50.5  |         | 5     | [087D40BA7C](https://bsd-hardware.info/?probe=087d40ba7c) |
| LGC        | 45N1025 LION   | 57.7  |         | 5     | [3EE0F54D2F](https://bsd-hardware.info/?probe=3ee0f54d2f) |
| LGC        | AP18C8K Li-Ion | 48.0  |         | 5     | [AA89C48CB7](https://bsd-hardware.info/?probe=aa89c48cb7) |
| Notebook   | BAT LION       | 35    |         | 5     | [4AC0707C49](https://bsd-hardware.info/?probe=4ac0707c49) |
| Panasonic  | AS16A5K LION   | 41.4  |         | 5     | [9C092C9CD7](https://bsd-hardware.info/?probe=9c092c9cd7) |
| SANYO      | 00HW022 LiP    | 23.5  |         | 5     | [6C895CB96F](https://bsd-hardware.info/?probe=6c895cb96f) |
| SANYO      | 45N1769 LION   | 56.2  |         | 5     | [7463E05C88](https://bsd-hardware.info/?probe=7463e05c88) |
| SANYO      | AL12A32 LION   | 37.0  |         | 5     | [D680E0D05D](https://bsd-hardware.info/?probe=d680e0d05d) |
| ASUSTek    | K55--47        | 51.7  |         | 4     | [6FA29C4E4D](https://bsd-hardware.info/?probe=6fa29c4e4d) |
| Celxpert   | 01AV424 LiP    | 24.1  |         | 4     | [6D7B30D2C4](https://bsd-hardware.info/?probe=6d7b30d2c4) |
| Hewlett... | Primary        | 48    |         | 4     | [73E328AD87](https://bsd-hardware.info/?probe=73e328ad87) |
| Hewlett... | Primary LIon   | 35    |         | 4     | [9C4BE9DEAB](https://bsd-hardware.info/?probe=9c4be9deab) |
| Hewlett... | Primary LIon   | 37    |         | 4     | [92C676E033](https://bsd-hardware.info/?probe=92c676e033) |
| Hewlett... | Primary LIon   | 46    |         | 4     | [0307C109B5](https://bsd-hardware.info/?probe=0307c109b5) |
| Intel SR 1 | SR Real Real   | 35.0  |         | 4     | [7D648BCDC7](https://bsd-hardware.info/?probe=7d648bcdc7) |
| LGC        | 00HW028 LiP    | 52.3  |         | 4     | [9C85F07244](https://bsd-hardware.info/?probe=9c85f07244) |
| LGC        | 01AV445 LiP    | 45.0  |         | 4     | [86866CE217](https://bsd-hardware.info/?probe=86866ce217) |
| LGC        | 01AV490 LiP    | 23.9  |         | 4     | [A4366E53BA](https://bsd-hardware.info/?probe=a4366e53ba) |
| LGC        | 45N1029 LION   | 103.5 |         | 4     | [148A268A0F](https://bsd-hardware.info/?probe=148a268a0f) |
| LGC        | DELL 49VTP ... | 57.7  |         | 4     | [DE97E0B2FC](https://bsd-hardware.info/?probe=de97e0b2fc) |
| Notebook   | BAT LION       | 60    |         | 4     | [9A62677EA8](https://bsd-hardware.info/?probe=9a62677ea8) |
| OEM        | FX50442        | 48.0  |         | 4     | [F8C10BF25A](https://bsd-hardware.info/?probe=f8c10bf25a) |
| Samsung... | DELL P8TC72... | 33.3  |         | 4     | [A776EBF7F4](https://bsd-hardware.info/?probe=a776ebf7f4) |
| SANYO      | 42T4791 LION   | 47.5  |         | 4     | [C0A6490FC8](https://bsd-hardware.info/?probe=c0a6490fc8) |
| SANYO      | 42T4799 LION   | 86.6  |         | 4     | [D341F3C6F6](https://bsd-hardware.info/?probe=d341f3c6f6) |
| SANYO      | 45N1037 LION   | 39.0  |         | 4     | [B1377872CD](https://bsd-hardware.info/?probe=b1377872cd) |
| SANYO      | 45N1734 LION   | 72.4  |         | 4     | [2776D8C350](https://bsd-hardware.info/?probe=2776d8c350) |
| SANYO      | PABAS024123... | 55.9  |         | 4     | [DCC5D3116F](https://bsd-hardware.info/?probe=dcc5d3116f) |
| SIMPLO     | PABAS024123... | 97.7  |         | 4     | [6D55881F6A](https://bsd-hardware.info/?probe=6d55881f6a) |
| SMP        | 00HW029 LiP    | 52.1  |         | 4     | [4CBD9F9314](https://bsd-hardware.info/?probe=4cbd9f9314) |
| SMP        | 01AV430 LiP    | 57.0  |         | 4     | [4993AD0FEB](https://bsd-hardware.info/?probe=4993ad0feb) |
| SMP        | 02DL008 LiP    | 50.5  |         | 4     | [32207EA5D9](https://bsd-hardware.info/?probe=32207ea5d9) |
| SMP        | 5B10W138 LiP   | 45.3  |         | 4     | [64A11E18DA](https://bsd-hardware.info/?probe=64a11e18da) |
| SMP        | 5B10W139 LiP   | 50.5  |         | 4     | [C626B32508](https://bsd-hardware.info/?probe=c626b32508) |
| SMP        | DELL GPM036... | 97.0  |         | 4     | [EE8980FEC1](https://bsd-hardware.info/?probe=ee8980fec1) |
| SMP        | DELL VN3N04... | 41.4  |         | 4     | [6FC0671DC6](https://bsd-hardware.info/?probe=6fc0671dc6) |
| SMPNz451   | bq20z451       | 57.7  |         | 4     | [3DD9E3557C](https://bsd-hardware.info/?probe=3dd9e3557c) |
| SONYCor    | AP13J4K LION   | 44.7  |         | 4     | [E063619F03](https://bsd-hardware.info/?probe=e063619f03) |
| Sunwoda    | 5B10W13975 LiP | 57.0  |         | 4     | [63B73012E6](https://bsd-hardware.info/?probe=63b73012e6) |
| ASUSTek    | UX31-35        | 47.9  |         | 3     | [93655CDD83](https://bsd-hardware.info/?probe=93655cdd83) |
| ASUSTek    | X202-51        | 38.0  |         | 3     | [BDBE613858](https://bsd-hardware.info/?probe=bdbe613858) |
| Celxpert   | 01AV448 LiP    | 45.7  |         | 3     | [9CFE2DD858](https://bsd-hardware.info/?probe=9cfe2dd858) |
| Celxpert   | 01AY969 LiP    | 80.4  |         | 3     | [1AF600B3AE](https://bsd-hardware.info/?probe=1af600b3ae) |
| CPT-COS    | L16C2PB2 LiP   | 30.6  |         | 3     | [6BDE68715E](https://bsd-hardware.info/?probe=6bde68715e) |
| DPON016    | ASMB016        | 50.2  |         | 3     | [7AEF0A996B](https://bsd-hardware.info/?probe=7aef0a996b) |
| DPONz45... | bq20z45189A... | 46.8  |         | 3     | [0D398D5C59](https://bsd-hardware.info/?probe=0d398d5c59) |
| Hewlett... | Primary LIon   |       |         | 3     | [718126149C](https://bsd-hardware.info/?probe=718126149c) |
| Hewlett... | Primary LIon   | 36    |         | 3     | [7596B602C6](https://bsd-hardware.info/?probe=7596b602c6) |
| Hewlett... | Primary LIon   | 39    |         | 3     | [77C17E4A2F](https://bsd-hardware.info/?probe=77c17e4a2f) |
| Hewlett... | Primary LIon   | 47    |         | 3     | [7BD69EE984](https://bsd-hardware.info/?probe=7bd69ee984) |
| Hewlett... | Primary LIon   | 64    |         | 3     | [E70725DD32](https://bsd-hardware.info/?probe=e70725dd32) |
| Lenovo     | BASE-BAT LiP   | 45.0  |         | 3     | [EB136E5D7E](https://bsd-hardware.info/?probe=eb136e5d7e) |
| LGC        | 01AV432 LiP    | 51.0  |         | 3     | [C27BA488AA](https://bsd-hardware.info/?probe=c27ba488aa) |
| LGC        | 01AV489 LiP    | 23.9  |         | 3     | [6D7B30D2C4](https://bsd-hardware.info/?probe=6d7b30d2c4) |
| LGC        | 42T4865 LION   | 64.1  |         | 3     | [8C7992E557](https://bsd-hardware.info/?probe=8c7992e557) |
| LGC        | 42T4911 LION   | 56.2  |         | 3     | [82F5612822](https://bsd-hardware.info/?probe=82f5612822) |
| LGC        | 45N1049 LION   | 40.4  |         | 3     | [6F1FD71366](https://bsd-hardware.info/?probe=6f1fd71366) |
| LGC        | 45N1147 LION   | 60.7  |         | 3     | [6D372DB804](https://bsd-hardware.info/?probe=6d372db804) |
| LGC        | 5B10W138 LiP   | 45.0  |         | 3     | [3D50BA4D85](https://bsd-hardware.info/?probe=3d50ba4d85) |
| LGC        | 5B10W139 LiP   | 50.5  |         | 3     | [AF190C38E9](https://bsd-hardware.info/?probe=af190c38e9) |
| LGC        | AC14B8K LION   | 48.9  |         | 3     | [0A58077C49](https://bsd-hardware.info/?probe=0a58077c49) |
| LGC        | AP18E8M Li-Ion | 57.5  |         | 3     | [6E97A003EC](https://bsd-hardware.info/?probe=6e97a003ec) |
| LGC        | L17L3PG1 LiP   | 52.5  |         | 3     | [D8F8901AE7](https://bsd-hardware.info/?probe=d8f8901ae7) |
| Notebook   | BAT LION       | 48    |         | 3     | [E83D522905](https://bsd-hardware.info/?probe=e83d522905) |
| Panasonic  | 45N1143 LION   | 38.9  |         | 3     | [20DF9D5DF2](https://bsd-hardware.info/?probe=20df9d5df2) |
| Panasonic  | 92P1133 LION   | 84.2  |         | 3     | [3497EE2FCC](https://bsd-hardware.info/?probe=3497ee2fcc) |
| Panasonic  | AP16M5J Li-Ion | 37.0  |         | 3     | [81827CCBCA](https://bsd-hardware.info/?probe=81827ccbca) |
| Panasonic  | Li_Ion_4000... | 47.5  |         | 3     | [FAE71F7E35](https://bsd-hardware.info/?probe=fae71f7e35) |
| Samsung... | DELL MT2648... | 86.6  |         | 3     | [08FE78379D](https://bsd-hardware.info/?probe=08fe78379d) |
| SANYO      | 42T4940 LION   | 86.6  |         | 3     | [E5A43DD311](https://bsd-hardware.info/?probe=e5a43dd311) |
| SANYO      | 45N1172 LION   | 62.6  |         | 3     | [786669CC9C](https://bsd-hardware.info/?probe=786669cc9c) |
| SANYO      | 45N1173 LION   | 94.0  |         | 3     | [4A700F43F8](https://bsd-hardware.info/?probe=4a700f43f8) |
| SANYO      | AP13J3K LION   | 45.9  |         | 3     | [E2E0A1953D](https://bsd-hardware.info/?probe=e2e0a1953d) |
| SANYO      | GRAPE32 LION   | 48.8  |         | 3     | [6A1B523EFB](https://bsd-hardware.info/?probe=6a1b523efb) |
| SDI        | Dell LION      | 49    |         | 3     | [6911E08B7E](https://bsd-hardware.info/?probe=6911e08b7e) |
| SMP        | 00HW003 LiP    | 50.1  |         | 3     | [341BAE363A](https://bsd-hardware.info/?probe=341bae363a) |
| SMP        | 00HW023 LiP    | 23.5  |         | 3     | [56FA0D4656](https://bsd-hardware.info/?probe=56fa0d4656) |
| SMP        | 5B10W13931 LiP | 51.0  |         | 3     | [85E94A1288](https://bsd-hardware.info/?probe=85e94a1288) |
| SMP        | 5B11C732 LiP   | 57.0  |         | 3     | [EF85735453](https://bsd-hardware.info/?probe=ef85735453) |
| SMP        | DELL 71JF45... | 74.0  |         | 3     | [B4A35AA7B0](https://bsd-hardware.info/?probe=b4a35aa7b0) |
| SMP        | DELL 7V69Y5... | 62.0  |         | 3     | [9E798CBFC8](https://bsd-hardware.info/?probe=9e798cbfc8) |
| SMP        | DELL JHXPY5... | 57.5  |         | 3     | [EC74AF083F](https://bsd-hardware.info/?probe=ec74af083f) |
| SMP        | DELL Y3F7Y6... | 42.0  |         | 3     | [F31CC32515](https://bsd-hardware.info/?probe=f31cc32515) |
| SMP        | L16M2PB1 LiP   | 30.0  |         | 3     | [87C8EE9B4C](https://bsd-hardware.info/?probe=87c8ee9b4c) |
| SMP        | L16M2PB2 LiP   | 35.0  |         | 3     | [3345F50844](https://bsd-hardware.info/?probe=3345f50844) |
| SMP        | L17M2PB7 LiP   | 30.0  |         | 3     | [883DBF15E4](https://bsd-hardware.info/?probe=883dbf15e4) |
| SMP        | L17M3PG1 LiP   | 52.5  |         | 3     | [57C3A4005A](https://bsd-hardware.info/?probe=57c3a4005a) |
| Sony       | 45N1705 LiP    | 47.1  |         | 3     | [17FD94A4C0](https://bsd-hardware.info/?probe=17fd94a4c0) |
| Sunwoda    | L19D4PH3 LiP   | 61.0  |         | 3     | [FCFA6205D8](https://bsd-hardware.info/?probe=fcfa6205d8) |
| TPS        | S10            | 44.7  |         | 3     | [FD081A3636](https://bsd-hardware.info/?probe=fd081a3636) |
| AMD Bat... |  Real Lion     | 55.4  | Li-ion  | 2     | [448F9265F2](https://bsd-hardware.info/?probe=448f9265f2) |
| APL MRD    |  Lion          |       | Li-ion  | 2     | [584ECF8423](https://bsd-hardware.info/?probe=584ecf8423) |
| ASUSTek    | 1015PE         | 47.5  |         | 2     | [EFEA0EFB2B](https://bsd-hardware.info/?probe=efea0efb2b) |
| ASUSTek    | 1215B          | 56.2  |         | 2     | [1CCF85F60D](https://bsd-hardware.info/?probe=1ccf85f60d) |
| ASUSTek    | K56--30        | 44.6  |         | 2     | [1263A5FB37](https://bsd-hardware.info/?probe=1263a5fb37) |
| ASUSTek    | N56--52        | 57.7  |         | 2     | [3B7E2EE70B](https://bsd-hardware.info/?probe=3b7e2ee70b) |
| ASUSTek    | UX325 LIon     | 67.3  |         | 2     | [692E2F0837](https://bsd-hardware.info/?probe=692e2f0837) |
| ASUSTek    | X550A26        | 34.6  |         | 2     | [9D406D735E](https://bsd-hardware.info/?probe=9d406d735e) |
| BYD        | DELL 9W9MX8... | 42.0  |         | 2     | [BC5EB8E237](https://bsd-hardware.info/?probe=bc5eb8e237) |
| Celxpert   | 01AV475 LiP    | 54.1  |         | 2     | [64D42B9C5F](https://bsd-hardware.info/?probe=64d42b9c5f) |
| Celxpert   | L19C3PD6 LiP   | 52.5  |         | 2     | [A919E85270](https://bsd-hardware.info/?probe=a919e85270) |
| DGFGE      | 597077-3S Real | 65.0  |         | 2     | [80F6445F54](https://bsd-hardware.info/?probe=80f6445f54) |
| DPON013    | ASMB013        | 50.2  |         | 2     | [015F0A0A6D](https://bsd-hardware.info/?probe=015f0a0a6d) |
| DPONz45... | bq20z451NQT... | 46.8  |         | 2     | [EEED92AB62](https://bsd-hardware.info/?probe=eeed92ab62) |
| Dynapack   | HB4593R1ECW... | 56.3  |         | 2     | [F9FDC75B45](https://bsd-hardware.info/?probe=f9fdc75b45) |
| Dynapack   | HB9790T7ECW... | 82.9  |         | 2     | [CED12F0B41](https://bsd-hardware.info/?probe=ced12f0b41) |
| Fujitsu    | CP700283-01... | 76.7  |         | 2     | [5C07C1A47E](https://bsd-hardware.info/?probe=5c07c1a47e) |
| Hewlett... | Primary        | 34    |         | 2     | [25E43BE096](https://bsd-hardware.info/?probe=25e43be096) |
| Hewlett... | Primary        | 35    |         | 2     | [75B9EF6EE6](https://bsd-hardware.info/?probe=75b9ef6ee6) |
| Hewlett... | Primary        | 47    |         | 2     | [3C11FC31B2](https://bsd-hardware.info/?probe=3c11fc31b2) |
| Hewlett... | Primary        | 55    |         | 2     | [EF66D7A110](https://bsd-hardware.info/?probe=ef66d7a110) |
| Hewlett... | Primary        | 95    |         | 2     | [476193BFD0](https://bsd-hardware.info/?probe=476193bfd0) |
| Hewlett... | Primary LIon   | 25    |         | 2     | [507E85C092](https://bsd-hardware.info/?probe=507e85c092) |
| Hewlett... | Primary LIon   | 29    |         | 2     | [C4F7B8A774](https://bsd-hardware.info/?probe=c4f7b8a774) |
| Hewlett... | Primary LIon   | 34    |         | 2     | [1DC503F21D](https://bsd-hardware.info/?probe=1dc503f21d) |
| Hewlett... | Primary LIon   | 41    |         | 2     | [7C997CE022](https://bsd-hardware.info/?probe=7c997ce022) |
| Hewlett... | Primary LIon   | 44    |         | 2     | [3C404C9D20](https://bsd-hardware.info/?probe=3c404c9d20) |
| Hewlett... | Primary LIon   | 48    |         | 2     | [2A9D4E9B0B](https://bsd-hardware.info/?probe=2a9d4e9b0b) |
| Hewlett... | Primary LIon   | 50    |         | 2     | [03CB6C6C7F](https://bsd-hardware.info/?probe=03cb6c6c7f) |
| Hewlett... | Primary LIon   | 55    |         | 2     | [D8FB34DE12](https://bsd-hardware.info/?probe=d8fb34de12) |
| Hewlett... | Primary LIon   | 90    |         | 2     | [86875F01C2](https://bsd-hardware.info/?probe=86875f01c2) |
| Intel SR 1 | Harris Beac... | 32.7  |         | 2     | [2F90D5C2BD](https://bsd-hardware.info/?probe=2f90d5c2bd) |
| JingYi     | 08K8193 LION   | 81.3  |         | 2     | [A2B9975FE2](https://bsd-hardware.info/?probe=a2b9975fe2) |
| Lenovo     | Serial numb... | 31.7  |         | 2     | [DA4BD87FEE](https://bsd-hardware.info/?probe=da4bd87fee) |
| Lenovo     | LCFC Li Pol... | 23.8  |         | 2     | [C4FD2595E6](https://bsd-hardware.info/?probe=c4fd2595e6) |
| LG         | LGC-LGC LION   | 72.8  |         | 2     | [5777CB6DC6](https://bsd-hardware.info/?probe=5777cb6dc6) |
| LG         | PABAS024123... | 48.9  |         | 2     | [74B11992D7](https://bsd-hardware.info/?probe=74b11992d7) |
| LGC        | 00HW002 LiP    | 50.2  |         | 2     | [EDA0880C67](https://bsd-hardware.info/?probe=eda0880c67) |
| LGC        | 00NY486 LION   | 47.5  |         | 2     | [2AEA9384AC](https://bsd-hardware.info/?probe=2aea9384ac) |
| LGC        | 01AV420 LiP    | 23.9  |         | 2     | [866724656A](https://bsd-hardware.info/?probe=866724656a) |
| LGC        | 01AV423 LiP    | 23.9  |         | 2     | [866724656A](https://bsd-hardware.info/?probe=866724656a) |
| LGC        | 01AV492 LION   | 71.1  |         | 2     | [B816902C0B](https://bsd-hardware.info/?probe=b816902c0b) |
| LGC        | 01AV494 LiP    | 57.0  |         | 2     | [A9928BD16E](https://bsd-hardware.info/?probe=a9928bd16e) |
| LGC        | 02DL004 LiP    | 51.0  |         | 2     | [2DA32E59B0](https://bsd-hardware.info/?probe=2da32e59b0) |
| LGC        | 42T4653 LION   | 56.2  |         | 2     | [26F8459193](https://bsd-hardware.info/?probe=26f8459193) |
| LGC        | 42T4912 LION   | 84.3  |         | 2     | [BAA0E928A8](https://bsd-hardware.info/?probe=baa0e928a8) |
| LGC        | 45N1079 LION   | 62.2  |         | 2     | [DBD5C6E5E3](https://bsd-hardware.info/?probe=dbd5c6e5e3) |
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
| Panasonic  | 004A354D363... | 37.0  |         | 2     | [570B96D0F7](https://bsd-hardware.info/?probe=570b96d0f7) |
| Panasonic  | 42T4620 LION   | 84.2  |         | 2     | [7D36D27958](https://bsd-hardware.info/?probe=7d36d27958) |
| Panasonic  | 42T4793 LION   | 56.2  |         | 2     | [9F9CB3E201](https://bsd-hardware.info/?probe=9f9cb3e201) |
| Panasonic  | 42T4801 LION   | 94.0  |         | 2     | [1433351032](https://bsd-hardware.info/?probe=1433351032) |
| Panasonic  | AP19B5K LION   | 39.7  |         | 2     | [7FB743C654](https://bsd-hardware.info/?probe=7fb743c654) |
| Panasonic  | AS10B5E LION   | 64.8  |         | 2     | [1617262A28](https://bsd-hardware.info/?probe=1617262a28) |
| Panasonic  | CF-VZSU46 LION | 91.0  |         | 2     | [F686E3756C](https://bsd-hardware.info/?probe=f686e3756c) |
| Razer      | Blade Li-I     | 65.0  |         | 2     | [34AC291019](https://bsd-hardware.info/?probe=34ac291019) |
| Samsung    | DELL 92 LION   | 67.0  |         | 2     | [CF598483CF](https://bsd-hardware.info/?probe=cf598483cf) |
| Samsung SD | DELL XRDW25... | 41.4  |         | 2     | [BB13E61DE1](https://bsd-hardware.info/?probe=bb13e61de1) |
| Samsung... | DELL 7DWMT1... | 98.2  |         | 2     | [2F848FD2C0](https://bsd-hardware.info/?probe=2f848fd2c0) |
| Samsung... | DELL C4HCW6... | 42.0  |         | 2     | [39B4581223](https://bsd-hardware.info/?probe=39b4581223) |
| SANYO      | 01AV425 LION   | 47.5  |         | 2     | [6B2ABD4DF5](https://bsd-hardware.info/?probe=6b2abd4df5) |
| SANYO      | 42T4710 LION   | 77.0  |         | 2     | [70A56029E7](https://bsd-hardware.info/?probe=70a56029e7) |
| SANYO      | 42T4751 LION   | 48.6  |         | 2     | [A1561DACB2](https://bsd-hardware.info/?probe=a1561dacb2) |
| SANYO      | 45N1027 LION   | 86.6  |         | 2     | [06C6A282CA](https://bsd-hardware.info/?probe=06c6a282ca) |
| SANYO      | 45N1089 LiP    | 46.8  |         | 2     | [D5BBBB8CBE](https://bsd-hardware.info/?probe=d5bbbb8cbe) |
| SANYO      | 45N1175 LION   | 85.9  |         | 2     | [791C826F7D](https://bsd-hardware.info/?probe=791c826f7d) |
| SANYO      | 45N1177 LION   | 62.6  |         | 2     | [55DEBB2F24](https://bsd-hardware.info/?probe=55debb2f24) |
| SANYO      | AC13C34 LION   | 30.0  |         | 2     | [513C7FF4BE](https://bsd-hardware.info/?probe=513c7ff4be) |
| SANYO      | AC14B13J LION  | 37.7  |         | 2     | [400EF90A79](https://bsd-hardware.info/?probe=400ef90a79) |
| SANYO      | AL10B31        | 48.8  |         | 2     | [08DC464D1B](https://bsd-hardware.info/?probe=08dc464d1b) |
| SANYO      | AL15A32 LION   | 37.0  |         | 2     | [7A4EB565FE](https://bsd-hardware.info/?probe=7a4eb565fe) |
| SANYO      | AS09C31 LION   | 47.5  |         | 2     | [96D745589C](https://bsd-hardware.info/?probe=96d745589c) |
| SANYO      | AS10D31 LION   | 47.5  |         | 2     | [1E97A0B938](https://bsd-hardware.info/?probe=1e97a0b938) |
| SANYO      | DELL 96JC94... | 57.7  |         | 2     | [8D92A4E37E](https://bsd-hardware.info/?probe=8d92a4e37e) |
| SANYO      | DELL M7T5F8... | 66.6  |         | 2     | [3F2E8586A7](https://bsd-hardware.info/?probe=3f2e8586a7) |
| SANYO      | DELL RG0490... | 62.2  |         | 2     | [66DED228EA](https://bsd-hardware.info/?probe=66ded228ea) |
| SANYO      | GC86508SAT0    | 23.8  |         | 2     | [1CBFCE4D7E](https://bsd-hardware.info/?probe=1cbfce4d7e) |
| SANYO      | L09S6Y02 LION  | 38.9  |         | 2     | [A0D1F01226](https://bsd-hardware.info/?probe=a0d1f01226) |
| SANYO      | PABAS024 LION  | 54.2  |         | 2     | [21407195E3](https://bsd-hardware.info/?probe=21407195e3) |
| SDI        | Dell LION      | 5     |         | 2     | [6DA8F97BCD](https://bsd-hardware.info/?probe=6da8f97bcd) |
| SIMPLO     | AS10D75 LION   | 48.8  |         | 2     | [DB00ABB833](https://bsd-hardware.info/?probe=db00abb833) |
| SIMPLO     | Li_Ion_4000... | 48.8  |         | 2     | [0513869BE8](https://bsd-hardware.info/?probe=0513869be8) |
| SMP        | 00UR891 LiP    | 32.0  |         | 2     | [A4366E53BA](https://bsd-hardware.info/?probe=a4366e53ba) |
| SMP        | 01AV431 LiP    | 57.0  |         | 2     | [0B48F96D1E](https://bsd-hardware.info/?probe=0b48f96d1e) |
| SMP        | 01AV446 LiP    | 45.3  |         | 2     | [1A2F28F5CC](https://bsd-hardware.info/?probe=1a2f28f5cc) |
| SMP        | 01AV447 LiP    | 45.7  |         | 2     | [98072B8DB6](https://bsd-hardware.info/?probe=98072b8db6) |
| SMP        | 01AV471 LiP    | 48.0  |         | 2     | [FF53F0763C](https://bsd-hardware.info/?probe=ff53f0763c) |
| SMP        | 02DL014 LiP    | 57.0  |         | 2     | [C052D7CAB0](https://bsd-hardware.info/?probe=c052d7cab0) |
| SMP        | 02DL028 LiP    | 90.0  |         | 2     | [B2024820D1](https://bsd-hardware.info/?probe=b2024820d1) |
| SMP        | 45N1736 LION   | 47.5  |         | 2     | [F53C625EFD](https://bsd-hardware.info/?probe=f53c625efd) |
| SMP        | 5B10W13973 LiP | 57.0  |         | 2     | [CAAD4323BA](https://bsd-hardware.info/?probe=caad4323ba) |
| SMP        | DELL 39DY56... | 38.0  |         | 2     | [DC37C53E48](https://bsd-hardware.info/?probe=dc37c53e48) |
| SMP        | DELL 4HJXXD... | 99.9  |         | 2     | [CE29DAF5AD](https://bsd-hardware.info/?probe=ce29daf5ad) |
| SMP        | DELL 909H53... | 48.2  |         | 2     | [6EC8FD788A](https://bsd-hardware.info/?probe=6ec8fd788a) |
| SMP        | DELL C5KG60... | 40.0  |         | 2     | [465DD01C0D](https://bsd-hardware.info/?probe=465dd01c0d) |
| SMP        | DELL CRT6P2... | 99.9  |         | 2     | [A3DA09AE5E](https://bsd-hardware.info/?probe=a3da09ae5e) |
| SMP        | DELL DM3WC6... | 60.0  |         | 2     | [DEFAEE0E5C](https://bsd-hardware.info/?probe=defaee0e5c) |
| SMP        | DELL GD1JP6... | 68.0  |         | 2     | [58B577382A](https://bsd-hardware.info/?probe=58b577382a) |

