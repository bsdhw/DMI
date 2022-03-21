DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 5413.

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
| AMD        | GX-412TC SOC                     |      | 177   | [5BC2136A359B](<Desktop/PC Engines/APU/APU2/5BC2136A359B>) |
| Intel      | Celeron J3160                    | 1.60 | 108   | [E5290014AF68](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68>) |
| Intel      | Core i5-7200U                    | 2.50 | 65    | [3EFC335326E0](<Desktop/Protectli/FW/FW6/3EFC335326E0>) |
| Intel      | Celeron J4125                    | 2.00 | 56    | [3631A0AAC7E1](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1>) |
| Intel      | Celeron J1900                    | 1.99 | 54    | [A58F88E6A7C3](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3>) |
| Intel      | Core 2 Duo                       |      | 43    | [99F71E27B77F](<Desktop/Dell/OptiPlex/OptiPlex 760/99F71E27B77F>) |
| Intel      | Core i5-8250U                    | 1.60 | 42    | [C384134D9772](<Desktop/Protectli/FW/FW6/C384134D9772>) |
| Intel      | Core i5-2520M                    | 2.50 | 42    | [AD955BCC7F71](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71>) |
| Intel      | Core i5-6500                     | 3.20 | 41    | [BB03C210EA63](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/BB03C210EA63>) |
| Intel      | Core i5-3470                     | 3.20 | 40    | [78AA11104573](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573>) |
| Intel      | Celeron J3455                    | 1.50 | 40    | [833E5514E5F2](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2>) |
| Intel      | Core i5-3570 CPU                 |      | 39    | [0B598C0816A1](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1>) |
| Intel      | Celeron J1900                    | 1.99 | 37    | [E8776A861ADD](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD>) |
| Intel      | Core i7-7500U                    | 2.70 | 36    | [3BDFC2AF1E56](<Desktop/Others/Others/Others/3BDFC2AF1E56>) |
| Intel      | Core i5-4570                     | 3.20 | 36    | [968E3838A942](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/968E3838A942>) |
| Intel      | Core i7-8550U                    | 1.80 | 35    | [FE16B0524669](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KSCTO1WW/FE16B0524669>) |
| Intel      | Core i3-7100U                    | 2.40 | 35    | [D99C85D0E548](<Desktop/Others/Others/Others/D99C85D0E548>) |
| Intel      | Atom D525                        | 1.80 | 34    | [7CA5763D4ADE](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE>) |
| Intel      | Core i5-2400                     | 3.10 | 34    | [627DB658CDA1](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C700/627DB658CDA1>) |
| AMD        | GX-420CA SOC with Radeon HD G... |      | 33    | [C3570F36DCFC](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3570F36DCFC>) |
| Intel      | Core i5-3320M                    | 2.60 | 31    | [08273574C200](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349AK1/08273574C200>) |
| Intel      | Core i7-3770                     | 3.40 | 31    | [5FE57A5AC09A](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A>) |
| Intel      | Celeron N3150                    | 1.60 | 29    | [87684C325536](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536>) |
| Intel      | Core i5-5200U                    | 2.20 | 28    | [D5565FC249CA](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/D5565FC249CA>) |
| Intel      | Core i5-4590                     | 3.30 | 27    | [E0896C7E47C7](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7>) |
| Intel      | Core i5-5300U                    | 2.30 | 26    | [CDAB4EDF622D](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS0VH08/CDAB4EDF622D>) |
| Intel      | Atom C3558                       | 2.20 | 26    | [00F1FC522527](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527>) |
| AMD        | RX-427BB with AMD Radeon R7 G... |      | 25    | [E658728E0DEE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E658728E0DEE>) |
| Intel      | Celeron 3865U                    | 1.80 | 25    | [7C58F64C2AFE](<Desktop/Protectli/FW/FW6/7C58F64C2AFE>) |
| Intel      | Celeron J4105                    | 1.50 | 24    | [6159C9CD886E](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E>) |
| Intel      | Atom E3845                       | 1.91 | 23    | [E2622583A8FD](<Desktop/Protectli/FW/FW1/E2622583A8FD>) |
| Intel      | Celeron N3450                    | 1.10 | 22    | [2D5523DF5C7C](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C>) |
| Intel      | Core i5-6200U                    | 2.30 | 21    | [BEB3261FFD05](<Notebook/Lenovo/ThinkPad/ThinkPad L570 W10DG 20JRS0RC02/BEB3261FFD05>) |
| AMD        | G-T40E                           |      | 20    | [BE5B5D847307](<Desktop/PC Engines/apu/apu1/BE5B5D847307>) |
| Intel      | Core i5-10210U                   | 1.60 | 20    | [CDFA57B84A24](<Desktop/Others/Others/Others/CDFA57B84A24>) |
| Intel      | Core i5-6300U                    | 2.40 | 20    | [DCA0C34D1413](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS4KH02/DCA0C34D1413>) |
| Intel      | Celeron J4115                    | 1.80 | 19    | [84E5622E626C](<Desktop/HARDKERNEL/ODROID-H/ODROID-H2/84E5622E626C>) |
| Intel      | Xeon D-1518                      | 2.20 | 19    | [381363A61F71](<Desktop/Hewlett-Packard/ProLiant/ProLiant EC200a/381363A61F71>) |
| AMD        | FX-8350 Eight-Core               |      | 18    | [0CADD393A87F](<Desktop/Gigabyte Technology/970/970A-D3P/0CADD393A87F>) |
| Intel      | Xeon E5-2650 v2                  | 2.60 | 18    | [EB12821F0875](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/EB12821F0875>) |
| Intel      | Celeron 2955U                    | 1.40 | 18    | [E461B743FFCE](<Notebook/Packard Bell/EasyNote/EasyNote TE69HW/E461B743FFCE>) |
| Intel      | Core i5-4200U                    | 1.60 | 18    | [20CABF26F23B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/20CABF26F23B>) |
| Intel      | Pentium N3700                    | 1.60 | 18    | [C88F6ADFB7E1](<Mini Pc/AMI/Aptio/Aptio CRB/C88F6ADFB7E1>) |
| Intel      | Celeron N3160                    | 1.60 | 18    | [686FE3922C3C](<Desktop/NU591/1/1.0/686FE3922C3C>) |
| Intel      | Atom E3930                       | 1.30 | 18    | [F8EC425F9C5B](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B>) |
| Intel      | Core i3-6100                     | 3.70 | 18    | [20267FB91925](<Desktop/Shuttle/SZ/SZ270/20267FB91925>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 17    | [172CA9AD2823](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 17    | [796624B869DA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA>) |
| Intel      | Core 2 Duo                       |      | 17    | [9A78F7D13F17](<Firewall/Sophos/UTM/UTM/9A78F7D13F17>) |
| Intel      | Xeon X3430                       | 2.40 | 17    | [29CC5C091FD8](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8>) |
| Intel      | Xeon E31220                      | 3.10 | 17    | [19696ACD0153](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153>) |
| Intel      | Core i3-3220                     | 3.30 | 17    | [1B8E9987FB7C](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C>) |
| Intel      | 11th Gen Core i7-1165G7          | 2.80 | 16    | [B3B09B220C14](<Notebook/Dell/Inspiron/Inspiron 5502/B3B09B220C14>) |
| Intel      | Core i7-10510U                   | 1.80 | 16    | [01401D10170F](<Desktop/Others/Others/Others/01401D10170F>) |
| Intel      | Core 2 Quad CPU                  |      | 16    | [EA117E39981F](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F>) |
| Intel      | Core i7-7700                     | 3.60 | 16    | [676B0F8582A3](<Desktop/Others/Others/Others/676B0F8582A3>) |
| Intel      | Core i3-2120 @ 3.30GH            |      | 16    | [9BB07B88EC4F](<Desktop/Intel/MAHOBAY/MAHOBAY/9BB07B88EC4F>) |
| Intel      | Core i7-4770                     | 3.40 | 16    | [BA63A6683747](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AU003DUK/BA63A6683747>) |
| Intel      | Core i5-5250U                    | 1.60 | 16    | [AF9575EB36EB](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/AF9575EB36EB>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 15    | [8688CDEE1483](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/8688CDEE1483>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 15    | [35055183F5DC](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR VI HERO/35055183F5DC>) |
| Intel      | Celeron N4100                    | 1.10 | 15    | [E3DDA56CAF35](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35>) |
| Intel      | Pentium Silver J5005             | 1.50 | 15    | [092F978DF489](<Desktop/Tarox/ECO/ECO 60-1/092F978DF489>) |
| Intel      | Core i5-8365U                    | 1.60 | 15    | [DA52B559F013](<Desktop/Others/Others/Others/DA52B559F013>) |
| Intel      | Celeron N2940                    | 1.83 | 15    | [FEA9A2F7C9FB](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB>) |
| Intel      | Core i5-3210M                    | 2.50 | 15    | [1EA9F55BD71B](<Notebook/Samsung Electronics/350V5/350V5C-350V5X-350V4C-350V4X-351V5C-351V5X-351V4C-351V4X-3540VC-3540VX-3440VC-3440VX/1EA9F55BD71B>) |
| Intel      | Core i5-3570                     | 3.40 | 15    | [0EF2C2D53CDB](<Desktop/MSI/MS/MS-7808/0EF2C2D53CDB>) |
| Intel      | Core i3-4160                     | 3.60 | 15    | [AB0ECF15BC89](<Desktop/Dell/OptiPlex/OptiPlex 3020/AB0ECF15BC89>) |
| Intel      | Celeron J3060                    | 1.60 | 15    | [B2DE43774AE7](<Desktop/Protectli/FW2/FW2B/B2DE43774AE7>) |
| Intel      | Atom C2558                       | 2.40 | 15    | [6D67E9999ACD](<Firewall/Sophos/SG/SG/6D67E9999ACD>) |
| Intel      | Core i5-2500 @ 3.30GH            |      | 14    | [5FF9535C321A](<Desktop/ASRock/H61/H61M-U3S3/5FF9535C321A>) |
| Intel      | Celeron J1800                    | 2.41 | 14    | [4AB5523176BA](<Desktop/ASRock/D1800/D1800M/4AB5523176BA>) |
| Intel      | Xeon E3-1220 V2                  | 3.10 | 14    | [442E10F8175B](<Server/Dell/PowerEdge/PowerEdge R210 II/442E10F8175B>) |
| Intel      | Core i7-4790                     | 3.60 | 14    | [F53B14F3D07E](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E>) |
| Intel      | Core i5-4210U                    | 1.70 | 14    | [491D65A1BD89](<Notebook/Lenovo/Z50-70/Z50-70 20354/491D65A1BD89>) |
| Intel      | Core i7-6700                     | 3.40 | 14    | [92E92186ABE5](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 13    | [7BDC1EF97D67](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 13    | [EC3A0F7E0A0B](<Desktop/ASUSTek Computer/P5/P5M2/EC3A0F7E0A0B>) |
| Intel      | Core i7-8700                     | 3.20 | 13    | [14EC34681B60](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G4 SFF/14EC34681B60>) |
| Intel      | CPU Version                      |      | 13    | [923B7E640A88](<Notebook/Acer/Aspire/Aspire 5930/923B7E640A88>) |
| Intel      | Atom N450                        | 1.66 | 13    | [E2F07739895A](<Notebook/ASUSTek Computer/1001/1001PX/E2F07739895A>) |
| Intel      | Core i7-3520M                    | 2.90 | 13    | [6FBB1F806232](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/6FBB1F806232>) |
| Intel      | Core i3-4130                     | 3.40 | 13    | [DCE5C1B8B6B6](<Desktop/Intel/H/H81/DCE5C1B8B6B6>) |
| Intel      | Core i3-4005U                    | 1.70 | 13    | [270D70C7FD1C](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/270D70C7FD1C>) |
| Intel      | Core i5-4300U                    | 1.90 | 13    | [8E86E40B0A52](<Notebook/Dell/Latitude/Latitude E5440/8E86E40B0A52>) |
| Intel      | Core i7-6600U                    | 2.60 | 13    | [720DC2256764](<Notebook/Dell/Latitude/Latitude 7480/720DC2256764>) |
|            | Unknown                          |      | 13    | [66C97E231B7A](<Desktop/friendlyelec/nanopi-m/nanopi-m4/66C97E231B7A>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 12    | [3EA73278F4B4](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/3EA73278F4B4>) |
| Intel      | Core i7-8565U                    | 1.80 | 12    | [3C494D1552EB](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB>) |
| Intel      | Core i7-8750H                    | 2.20 | 12    | [62D7C65FC1E9](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX504GD_FX80GD/62D7C65FC1E9>) |
| Intel      | Core i7-2600                     | 3.40 | 12    | [211A5564976B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M81 5048WG6/211A5564976B>) |
| Intel      | Xeon E5620                       | 2.40 | 12    | [B03FF48F1575](<Server/Dell/PowerEdge/PowerEdge R710/B03FF48F1575>) |
| Intel      | Celeron J1900                    | 1.99 | 12    | [C31CA5CEBF82](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82>) |
| Intel      | Core i3-3240                     | 3.40 | 12    | [9983D9259942](<Desktop/Intel/H/H61/9983D9259942>) |
| Intel      | Core i3-4150                     | 3.50 | 12    | [CAE61970AA22](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22>) |
| Intel      | Xeon E3-1220 v3                  | 3.10 | 12    | [B77E3EF73ADC](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/B77E3EF73ADC>) |
| Intel      | Core i3-4010U                    | 1.70 | 12    | [E3EBE3669073](<Notebook/Dell/Inspiron/Inspiron 3537/E3EBE3669073>) |
| Intel      | Atom C2358                       | 1.74 | 12    | [DF94A20C5413](<Mini Pc/Supermicro/A1/A1SAi/DF94A20C5413>) |
| Intel      | Atom C2758                       | 2.40 | 12    | [9D30C6309EE3](<Mini Pc/Supermicro/A1/A1SAi/9D30C6309EE3>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 11    | [63762628C1D4](<Desktop/MSI/MS-7/MS-7B79/63762628C1D4>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 11    | [6F28C57B7391](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-F GAMING/6F28C57B7391>) |
| Intel      | Core i5-7300U                    | 2.60 | 11    | [3A5791A2C489](<Notebook/Dell/Latitude/Latitude 7480/3A5791A2C489>) |
| Intel      | Core 2 CPU                       |      | 11    | [8CFF73D19B7A](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1951FEG/8CFF73D19B7A>) |
| Intel      | Core i5-7400                     | 3.00 | 11    | [83B5EB75C02F](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F>) |
| Intel      | Core i3-10100                    | 3.60 | 11    | [2491BD9CFCF1](<Desktop/ASRock/B460/B460M-HDV/2491BD9CFCF1>) |
| Intel      | 11th Gen Core i5-11400           | 2.60 | 11    | [E69659E3B5AD](<Desktop/Dell/Inspiron/Inspiron 3891/E69659E3B5AD>) |
| Intel      | Core i7-3770K                    | 3.50 | 11    | [D5FB9BCC8299](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/D5FB9BCC8299>) |
| Intel      | Xeon E3-1225 v3                  | 3.20 | 11    | [C68E45CBB411](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411>) |
| Intel      | Core i3-5005U                    | 2.00 | 11    | [E6CECB6E29C9](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9>) |
| Intel      | Core i3-4030U                    | 1.90 | 11    | [8D72983BE759](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759>) |
| Intel      | Core i7-4600U                    | 2.10 | 11    | [5B022BB303EA](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ006HUS/5B022BB303EA>) |
| Intel      | Atom C3758                       | 2.20 | 11    | [A578CB3E5D0D](<Desktop/Others/Others/Others/A578CB3E5D0D>) |
| Intel      | Core i3-1005G1                   | 1.20 | 10    | [116441499573](<Desktop/BESSTAR Tech/X/X35G/116441499573>) |
| Intel      | Core i3-8145U                    | 2.10 | 10    | [01369C49D273](<Desktop/Shuttle/DS10/DS10U/01369C49D273>) |
| Intel      | Core i3-8100                     | 3.60 | 10    | [DC3709C1C54A](<Desktop/Gigabyte Technology/B360N/B360N WIFI/DC3709C1C54A>) |
| Intel      | Core i7-10750H                   | 2.60 | 10    | [CF159C44766D](<Notebook/MSI/GF63/GF63 Thin 10SCSR/CF159C44766D>) |
| Intel      | Celeron N2930                    | 1.83 | 10    | [914846B53150](<Desktop/AOPEN/DE/DE3250/914846B53150>) |
| Intel      | Celeron 1037U                    | 1.80 | 10    | [34CE6C299230](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230>) |
| Intel      | Xeon E3-1230 V2                  | 3.30 | 10    | [AAD39B96E388](<Desktop/Seneca/pro/pro379410/AAD39B96E388>) |
| Intel      | Core i7-4790K                    | 4.00 | 10    | [A8C9B255DC33](<Desktop/Gigabyte Technology/Z97/Z97X-SLI/A8C9B255DC33>) |
| Intel      | Core i3-6006U                    | 2.00 | 10    | [58429869386D](<Notebook/Lenovo/E31-80/E31-80 80MX/58429869386D>) |
| Intel      | Xeon D-2123IT                    | 2.20 | 10    | [AB927389C02E](<Server/Supermicro/Super/Super Server/AB927389C02E>) |
| Intel      | Pentium G4400                    | 3.30 | 10    | [FBC14B60FBA4](<Desktop/Dell/OptiPlex/OptiPlex 3050/FBC14B60FBA4>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 9     | [B7ED32E7D2CE](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/B7ED32E7D2CE>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 9     | [1472F852C675](<Desktop/Gigabyte Technology/B450M/B450M S2H/1472F852C675>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 9     | [40C6F3FD48CC](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 9     | [F36FD56B8299](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/F36FD56B8299>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 9     | [7DE2E889826B](<Desktop/Gigabyte Technology/X570/X570 I AORUS PRO WIFI/7DE2E889826B>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 9     | [C4886ECF4649](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 9     | [57FCF8719ACE](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE>) |
| Intel      | Core i5-8350U                    | 1.70 | 9     | [EA208CC61F28](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L8S1GX00/EA208CC61F28>) |
| Intel      | Core i5-8265U                    | 1.60 | 9     | [4C68E3D2FBB0](<Desktop/Others/Others/Others/4C68E3D2FBB0>) |
| Intel      | Xeon E-2224                      | 3.40 | 9     | [EBD53B4A056D](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D>) |
| Intel      | Core i5-7500                     | 3.40 | 9     | [E3ED1B71BC40](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40>) |
| Intel      | Core i3-2100 @ 3.10GH            |      | 9     | [63F3785F6509](<Desktop/Dell/OptiPlex/OptiPlex 390/63F3785F6509>) |
| Intel      | Core i5-2540M                    | 2.60 | 9     | [D2E0D93C2306](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236MBU/D2E0D93C2306>) |
| Intel      | Xeon E5645                       | 2.40 | 9     | [34F0B81A9C93](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93>) |
| Intel      | Celeron G1610T                   | 2.30 | 9     | [2FF94B730913](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/2FF94B730913>) |
| Intel      | Core i5-3570K                    | 3.40 | 9     | [929553D2B892](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892>) |
| Intel      | Core i5-4570S                    | 2.90 | 9     | [CF3530F1EDC6](<Firewall/Sophos/SG/SG/CF3530F1EDC6>) |
| Intel      | Pentium G3220                    | 3.00 | 9     | [6D01993D9C81](<Desktop/ASRock/E3/E3C224D2I/6D01993D9C81>) |
| Intel      | Pentium G3420                    | 3.20 | 9     | [298F8B128A1A](<Firewall/Sophos/SG/SG/298F8B128A1A>) |
| Intel      | Core i3-5010U                    | 2.10 | 9     | [937E718E5858](<Desktop/Acer/RevoOne/RevoOne RL85/937E718E5858>) |
| Intel      | Core i7-6700K                    | 4.00 | 9     | [05035287165A](<Desktop/MSI/MS-7/MS-7A16/05035287165A>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 8     | [6B516E615857](<Notebook/Sony/VPCYB45/VPCYB45JB/6B516E615857>) |
| AMD        | FX-6300 Six-Core                 |      | 8     | [BBDCED21D8D8](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8>) |
| AMD        | EPYC 3201 8-Core                 |      | 8     | [94D2C7F0ED24](<Notebook/Deciso/Netboard/Netboard A20/94D2C7F0ED24>) |
| Intel      | Core i7-7600U                    | 2.80 | 8     | [FE02391BB20C](<Notebook/Dell/Latitude/Latitude 7380/FE02391BB20C>) |
| Intel      | Core i7-9750H                    | 2.60 | 8     | [DA4017866B4B](<Notebook/Dell/G5/G5 5590/DA4017866B4B>) |
| Intel      | Core i3-9100                     | 3.60 | 8     | [D7C138E79E23](<Desktop/ASUSTek Computer/P11C-I/P11C-I Series/D7C138E79E23>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 8     | [207E53FA804A](<Notebook/MSI/GT75VR/GT75VR 7RF/207E53FA804A>) |
| Intel      | Core i5-10400                    | 2.90 | 8     | [ABC523DBEA27](<Desktop/ASUSTek Computer/ASUS/ASUS ExpertCenter D500SA_D500SA/ABC523DBEA27>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 8     | [1CFEF99BC722](<Desktop/ASUSTek Computer/P5/P5G41T-M/1CFEF99BC722>) |
| Intel      | Xeon E5520                       | 2.27 | 8     | [EDFF20587D82](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82>) |
| Intel      | Atom N270                        | 1.60 | 8     | [B5CD347664FA](<Desktop/MSI/U/U-100/B5CD347664FA>) |
| Intel      | Xeon X5650                       | 2.67 | 8     | [2B064C7B2306](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306>) |
| Intel      | Core i3-3225                     | 3.30 | 8     | [630D25B19798](<Desktop/Dell/OptiPlex/OptiPlex 9010/630D25B19798>) |
| Intel      | Core i3-3227U                    | 1.90 | 8     | [B45D5D5687A2](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2>) |
| Intel      | Xeon E3-1220L V2                 | 2.30 | 8     | [BD571BB0E41F](<Desktop/Supermicro/X9/X9SCL-X9SCM/BD571BB0E41F>) |
| Intel      | Core i5-4590S                    | 3.00 | 8     | [B0BF23CC4C13](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G2.5 SFF/B0BF23CC4C13>) |
| Intel      | Xeon E3-1270 v3                  | 3.50 | 8     | [2DDB2C21F9DF](<Server/Supermicro/X10/X10SLH-N6-ST031/2DDB2C21F9DF>) |
| Intel      | Core i7-5550U                    | 2.00 | 8     | [4325757775B6](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/4325757775B6>) |
| Intel      | Core i7-5600U                    | 2.60 | 8     | [E6AE328AD30B](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CMCTO1WW/E6AE328AD30B>) |
| Intel      | Pentium N3710                    | 1.60 | 8     | [06EE75887F21](<Desktop/Supermicro/SYS-E200/SYS-E200-9B/06EE75887F21>) |
| Intel      | Atom C2750                       | 2.40 | 8     | [DB4E9ECD1274](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274>) |
| Intel      | Celeron 3855U                    | 1.60 | 8     | [546AB2CFDB35](<Desktop/Intel/SKYBAY/SKYBAY/546AB2CFDB35>) |
| Intel      | Core i7-6500U                    | 2.50 | 8     | [35A7C406512F](<Notebook/Dell/Inspiron/Inspiron 5559/35A7C406512F>) |
| Intel      | Celeron N3350                    | 1.10 | 8     | [BCAD2CB6073B](<Notebook/Jumper/EZbook/EZbook/BCAD2CB6073B>) |
| Intel      | Pentium N4200                    | 1.10 | 8     | [0B30B3251176](<Desktop/Kontron Europe/COMe-mAL10/COMe-mAL10.0/0B30B3251176>) |
| Intel      | Core i5-6400                     | 2.70 | 8     | [E7F431D0444B](<Desktop/Others/Others/Others/E7F431D0444B>) |
| Intel      | Atom D2550                       | 1.86 | 8     | [E4A2F6B13DE8](<Desktop/GuoGuang/IC2/IC2M1028V-6/E4A2F6B13DE8>) |
| Intel      | Core i5 M 520                    | 2.40 | 8     | [B0EAFA5FD723](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537WEE/B0EAFA5FD723>) |
| AMD        | GX-415GA SOC with Radeon HD G... |      | 7     | [6E2617BD266B](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B>) |
| AMD        | Ryzen 5 1600 Six-Core            |      | 7     | [C761D124FF11](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/C761D124FF11>) |
| AMD        | EPYC 3101 4-Core                 |      | 7     | [CA85E9DB0093](<Server/Supermicro/Super/Super Server/CA85E9DB0093>) |
| AMD        | Ryzen 3 3100 4-Core              |      | 7     | [C62ACC88C9AE](<Desktop/Gigabyte Technology/B550M/B550M AORUS ELITE/C62ACC88C9AE>) |
| AMD        | Ryzen 9 3950X 16-Core            |      | 7     | [C90D36EB23CC](<Desktop/Gigabyte Technology/X570/X570 I AORUS PRO WIFI/C90D36EB23CC>) |
| AMD        | Athlon 3000G with Radeon Vega... |      | 7     | [81F06CA07673](<Desktop/MSI/MS-7/MS-7C52/81F06CA07673>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 7     | [0940BAB70ED0](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512DA_F512DA/0940BAB70ED0>) |
| Intel      | Core i7-1065G7                   | 1.30 | 7     | [84AAC084FB8A](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A>) |
| Intel      | Core i7-8565U                    | 1.80 | 7     | [69CAD6B3B2BA](<Notebook/Lenovo/Yoga/Yoga S730-13IWL 81J0/69CAD6B3B2BA>) |
| Intel      | Core i5-8265U                    | 1.60 | 7     | [E94C63DB8904](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G5/E94C63DB8904>) |
| Intel      | Core i5-8500                     | 3.00 | 7     | [0475C8F7BA1E](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G4 SFF/0475C8F7BA1E>) |
| Intel      | Pentium Gold G5400               | 3.70 | 7     | [F2BDC9CA4D70](<Desktop/MSI/MS-7/MS-7C09/F2BDC9CA4D70>) |
| Intel      | Core i5-9400                     | 2.90 | 7     | [18414185F33D](<Desktop/GALAX/B365/B365M/18414185F33D>) |
| Intel      | Core i5-7300HQ                   | 2.50 | 7     | [2663B977A92F](<Notebook/Dell/Inspiron/Inspiron 15 7000 Gaming/2663B977A92F>) |
| Intel      | Core i7-7700K                    | 4.20 | 7     | [B28241EA93D9](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/B28241EA93D9>) |
| Intel      | Core i7-10700                    | 2.90 | 7     | [1C484EF0D1E5](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A R2.0/1C484EF0D1E5>) |
| Intel      | Genuine CPU                      |      | 7     | [375DCC2AA0F0](<Notebook/Lenovo/IdeaPad/IdeaPad Z360/375DCC2AA0F0>) |
| Intel      | Core i5-2430M                    | 2.40 | 7     | [5EF98B1DA6B5](<Notebook/Dell/Inspiron/Inspiron N5110/5EF98B1DA6B5>) |
| Intel      | Core i7-2640M                    | 2.80 | 7     | [B6B9C54EEBB2](<Notebook/Dell/Precision/Precision M4600/B6B9C54EEBB2>) |
| Intel      | Core i3-3217U                    | 1.80 | 7     | [D771CCA40E31](<Notebook/ASUSTek Computer/S550/S550CA/D771CCA40E31>) |
| Intel      | Core i5-3230M                    | 2.60 | 7     | [D8442DC4CB7A](<Notebook/Lenovo/G580/G580 20150/D8442DC4CB7A>) |
| Intel      | Core i5-3317U                    | 1.70 | 7     | [2ABD09D4BEE1](<Notebook/ASUSTek Computer/UX31/UX31A/2ABD09D4BEE1>) |
| Intel      | Celeron G1820                    | 2.70 | 7     | [8CAA583F1507](<Desktop/CheckPoint/PB-15/PB-15-00/8CAA583F1507>) |
| Intel      | Core i3-4170                     | 3.70 | 7     | [FF2593BC5B73](<Desktop/Lenovo/IdeaCentre/IdeaCentre 300S-08IHH 90F10030US/FF2593BC5B73>) |
| Intel      | Core i5-4300M                    | 2.60 | 7     | [DB867CFAF011](<Notebook/Lenovo/ThinkPad/ThinkPad L440 20ASS0FP00/DB867CFAF011>) |
| Intel      | Xeon E3-1231 v3                  | 3.40 | 7     | [FB6CF499445D](<Server/Dell/PowerEdge/PowerEdge R220/FB6CF499445D>) |
| Intel      | Core i5-4250U                    | 1.30 | 7     | [0D192CE1B155](<Desktop/Intel/D54250WYK/D54250WYK H13922-304/0D192CE1B155>) |
| Intel      | Core i7-4510U                    | 2.00 | 7     | [37E78B085068](<Notebook/Lenovo/G40-70/G40-70 20369/37E78B085068>) |
| Intel      | Core i3-6100U                    | 2.30 | 7     | [0039727ADB4A](<Notebook/Lenovo/ThinkPad/ThinkPad 13 20GJCTO1WW/0039727ADB4A>) |
| Intel      | Xeon E3-1225 v5                  | 3.30 | 7     | [82CE853FF0D7](<Desktop/Dell/PowerEdge/PowerEdge T30/82CE853FF0D7>) |
| Intel      | Core i5 M 560                    | 2.67 | 7     | [4A58F0F69086](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086>) |
| AMD        | GX-222GC SOC with Radeon R5E ... |      | 6     | [5163FE0BC7B4](<Desktop/Fujitsu/FUTRO/FUTRO S920/5163FE0BC7B4>) |
| AMD        | Phenom II X4 965                 |      | 6     | [9CF14B98B99F](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F>) |
| AMD        | GX-416RA SOC                     |      | 6     | [E03FD4943E71](<Desktop/Deciso/Netboard/Netboard A10 V2/E03FD4943E71>) |
| AMD        | Ryzen 3 1200 Quad-Core           |      | 6     | [478B36E0E39C](<Desktop/ASRock/B450M/B450M Pro4/478B36E0E39C>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 6     | [7FB1A29EA377](<Notebook/HUAWEI/HLY-WX9/HLY-WX9XX/7FB1A29EA377>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 6     | [3509F5558F2E](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E>) |
| Intel      | Celeron J4005                    | 2.00 | 6     | [683FDC0E9AB5](<Mini Pc/Intel/NUC7/NUC7CJYS/683FDC0E9AB5>) |
| Intel      | Core i7-8665U                    | 1.90 | 6     | [C98487030311](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/C98487030311>) |
| Intel      | Core i7-9700                     | 3.00 | 6     | [C29AA24281D9](<Desktop/Others/Others/Others/C29AA24281D9>) |
| Intel      | Pentium G4560                    | 3.50 | 6     | [1E747FA168DD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD>) |
| Intel      | Xeon E3-1220 v6                  | 3.00 | 6     | [85D49F3DE87A](<Desktop/ASUSTek Computer/P10S-I/P10S-I Series/85D49F3DE87A>) |
| Intel      | Celeron E3400                    | 2.60 | 6     | [55A5BF807E33](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 6     | [E9390A708CD5](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800p Small Form Factor/E9390A708CD5>) |
| Intel      | Core 2 Duo E8500                 | 3.16 | 6     | [48A53A6EA736](<Desktop/Intel/DQ35JO/DQ35JO AAD82085-804/48A53A6EA736>) |
| Intel      | Core 2 Duo P7550                 | 2.26 | 6     | [797E25488CC3](<All In One/Apple/iMac9/iMac9,1/797E25488CC3>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 6     | [C751E92B8FCE](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE>) |
| Intel      | Xeon E5506                       | 2.13 | 6     | [68889627DD42](<Desktop/Supermicro/X8/X8STi/68889627DD42>) |
| Intel      | Core i3 M 330                    | 2.13 | 6     | [71DA77711A2C](<Notebook/Hewlett-Packard/G/G62/71DA77711A2C>) |
| Intel      | Celeron 847                      | 1.10 | 6     | [E9D6CCEC8110](<Desktop/Gigabyte Technology/C847/C847N/E9D6CCEC8110>) |
| Intel      | Core i3-2310M                    | 2.10 | 6     | [9B429D40BBF7](<Notebook/Itautec/Infoway/Infoway w7535/9B429D40BBF7>) |
| Intel      | Core i5-2320                     | 3.00 | 6     | [92A54C63F0AC](<Desktop/Seneca/pro/pro396949/92A54C63F0AC>) |
| Intel      | Core i5-2410M                    | 2.30 | 6     | [C1B114424074](<Notebook/Positivo/C14/C14CR01/C1B114424074>) |
| Intel      | Xeon X5680                       | 3.33 | 6     | [BC5E988EF981](<Server/Dell/PowerEdge/PowerEdge R710/BC5E988EF981>) |
| Intel      | Atom E3827                       | 1.74 | 6     | [7FBC058A3FA5](<Desktop/CNCTION-IAF-E3845/Others/Others/7FBC058A3FA5>) |
| Intel      | Core i7-3630QM                   | 2.40 | 6     | [AA24216EF412](<Notebook/ASUSTek Computer/N56/N56VB/AA24216EF412>) |
| Intel      | Xeon E3-1265L V2                 | 2.50 | 6     | [8FC9AB486481](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/8FC9AB486481>) |
| Intel      | Core i5-4460                     | 3.20 | 6     | [45C5EA8AF26A](<Desktop/ASRock/H97M/H97M Pro4/45C5EA8AF26A>) |
| Intel      | Core i5-4570T                    | 2.90 | 6     | [A53CA903F1D9](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAA0WGUK/A53CA903F1D9>) |
| Intel      | Core i5-4590T                    | 2.00 | 6     | [CA71A0B560A0](<Desktop/Dell/OptiPlex/OptiPlex 9020M/CA71A0B560A0>) |
| Intel      | Celeron 3215U                    | 1.70 | 6     | [874341B78AF4](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/874341B78AF4>) |
| Intel      | Xeon E5-2630 v3                  | 2.40 | 6     | [647219C1BB29](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29>) |
| Intel      | Core i7-4500U                    | 1.80 | 6     | [2A9F2B9082A0](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0>) |
| Intel      | Celeron N3050                    | 1.60 | 6     | [7C93D5BC2B5B](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B>) |
| Intel      | Atom x5-Z8350                    | 1.44 | 6     | [1AF1AD1E39F7](<Desktop/AAEON/UP-CHT/UP-CHT01/1AF1AD1E39F7>) |
| Intel      | Celeron J3455E                   | 1.50 | 6     | [E8F03AADB8BD](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD>) |
| Intel      | Celeron J3355                    | 2.00 | 6     | [D68EAE11C8E7](<Desktop/ASRock/J3355/J3355B-ITX/D68EAE11C8E7>) |
| Intel      | Core i3-6100T                    | 3.20 | 6     | [1B69982CCB71](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/1B69982CCB71>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 6     | [2BD0319875C3](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3>) |
| Intel      | Core i7-6820HQ                   | 2.70 | 6     | [E6AAE60B4973](<Notebook/Dell/Precision/Precision 7710/E6AAE60B4973>) |
| Intel      | Atom 330 @                       |      | 6     | [C7570785CFF9](<Desktop/Foxconn/45/45CS/C7570785CFF9>) |
| Intel      | Atom D2500                       | 1.86 | 6     | [DE6EF4C31B55](<Desktop/Intel/D2500CC/D2500CC AAG81477-401/DE6EF4C31B55>) |
| AMD        | GX-217GA SOC with Radeon HD G... |      | 5     | [2EF21B21A43F](<Desktop/Fujitsu/FUTRO/FUTRO S720/2EF21B21A43F>) |
| AMD        | FX-6100 Six-Core                 |      | 5     | [407FD650ABF2](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/407FD650ABF2>) |
| AMD        | FX-8320 Eight-Core               |      | 5     | [0C8C6FDA249C](<Desktop/MSI/MS/MS-7693/0C8C6FDA249C>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 5     | [4E83FD0E25CF](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/4E83FD0E25CF>) |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 5     | [5E03AED6E452](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1CTO1WW/5E03AED6E452>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 5     | [7FCEC9A2C51B](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
|            | Module SODIMM                | 4 GB     | DDR3 | 1333 | 97    | [FD5944A53320](<Desktop/PC Engines/APU/APU2/FD5944A53320>) |
|            | 123456789012345678 DIMM      | 4 GB     | DDR4 | 2400 | 70    | [1960C8C916FA](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 54    | [8E86E40B0A52](<Notebook/Dell/Latitude/Latitude E5440/8E86E40B0A52>) |
|            | Module(s) DIMM               | 4 GB     |      |      | 47    | [5C0556A6AFDF](<Desktop/ADI Engineering/RCC-VE/RCC-VE/5C0556A6AFDF>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 45    | [BADAE72EA873](<Notebook/Lenovo/ThinkPad/ThinkPad X201 32492EU/BADAE72EA873>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 38    | [29CC5C091FD8](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8>) |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 34    | [D2E0D93C2306](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236MBU/D2E0D93C2306>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 32    | [C29AA24281D9](<Desktop/Others/Others/Others/C29AA24281D9>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 31    | [6E2617BD266B](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 27    | [7A36C31A2F7E](<Notebook/ASUSTek Computer/M51/M51Sr/7A36C31A2F7E>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 27    | [738C6FFEC885](<Notebook/TWINHEAD/U12/U12CT/738C6FFEC885>) |
| SK Hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 26    | [4F89B9A156FF](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS1JN00/4F89B9A156FF>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 24    | [1DF42E107A56](<Desktop/IEESA/P5K/P5K PRO/1DF42E107A56>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1600 | 23    | [FB200A1FDF0B](<Desktop/Intel/DH77EB/DH77EB AAG39073-400/FB200A1FDF0B>) |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 2667 | 23    | [3E8F8F48759C](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/3E8F8F48759C>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 23    | [7AF33DC5AA71](<Notebook/Lenovo/ThinkPad/ThinkPad X220 Tablet 4298B65/7AF33DC5AA71>) |
| SK Hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 23    | [720DC2256764](<Notebook/Dell/Latitude/Latitude 7480/720DC2256764>) |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 22    | [1B8E9987FB7C](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 22    | [C8BE8A361EFE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C8BE8A361EFE>) |
| SK Hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 21    | [BA63A6683747](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AU003DUK/BA63A6683747>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 21    | [627DB658CDA1](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C700/627DB658CDA1>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 20    | [BBDCED21D8D8](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 20    | [A739DC61372B](<Notebook/Hewlett-Packard/Notebook/Notebook/A739DC61372B>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 19    | [676B0F8582A3](<Desktop/Others/Others/Others/676B0F8582A3>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 19    | [96A056EA1F97](<Desktop/Others/Others/Others/96A056EA1F97>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 667  | 19    | [FD6B88F600B7](<Desktop/PC Engines/APU/APU2/FD6B88F600B7>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 19    | [5B022BB303EA](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ006HUS/5B022BB303EA>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 18    | [9E84A9D36F15](<Desktop/ASRock/G41/G41C-VS/9E84A9D36F15>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 18    | [F53B14F3D07E](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 18    | [38D472657A7B](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN0048IA/38D472657A7B>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3200 | 17    | [707C9EE26C47](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47>) |
| Crucial    | CT102464BF160B.M16 DIMM      | 8 GB     | DDR3 | 1600 | 17    | [CA550B479DD0](<Desktop/Protectli/FW/FW1/CA550B479DD0>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 17    | [CDDE53EE5395](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9470m/CDDE53EE5395>) |
|            | Module                       | 8 GB     |      | 1600 | 17    | [CDB353BB4B34](<Desktop/Protectli/FW4/FW4B/CDB353BB4B34>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 17    | [6159C9CD886E](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E>) |
| SK Hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 16    | [9BF99287F7BD](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7A0B7MS/9BF99287F7BD>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 16    | [F53B14F3D07E](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 16    | [E3EBE3669073](<Notebook/Dell/Inspiron/Inspiron 3537/E3EBE3669073>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 16    | [771FB79FBCC7](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HHCTO1WW/771FB79FBCC7>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 16    | [C23302E095F0](<Notebook/Lenovo/IdeaPad/IdeaPad N585/C23302E095F0>) |
| SK Hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 15    | [78AA11104573](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 15    | [D558B9848658](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/D558B9848658>) |
| Samsung    | M471B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 15    | [CB694C8A4BF0](<Desktop/Protectli/FW4/FW4B/CB694C8A4BF0>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 15    | [92636C571F98](<Desktop/ASUSTek Computer/All/All Series/92636C571F98>) |
| Crucial    | CT102464BF160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 14    | [55A5595258A6](<Desktop/Protectli/FW4/FW4B/55A5595258A6>) |
| Kingston   | 99U5469-045.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 14    | [A58F88E6A7C3](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 14    | [0411A5C6D40D](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/0411A5C6D40D>) |
| Samsung    | M393B1G70QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 14    | [FF3DB6477637](<Server/Dell/OEM-R/OEM-R 720xd/FF3DB6477637>) |
| Crucial    | CT102464BA160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 13    | [A72A5E92109B](<Desktop/Others/Others/Others/A72A5E92109B>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1600 | 13    | [8B1209E2156C](<Desktop/AMD/X/X64/8B1209E2156C>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 13    | [DD5639A44B24](<Desktop/ASUSTek Computer/M4/M4A78/DD5639A44B24>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 667  | 13    | [EC3A0F7E0A0B](<Desktop/ASUSTek Computer/P5/P5M2/EC3A0F7E0A0B>) |
|            | Module SODIMM                | 8 GB     | DDR3 | 1600 | 13    | [E6CECB6E29C9](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     |      | 1333 | 13    | [16806C85881A](<Notebook/Lenovo/ThinkPad/ThinkPad SL510 2847R96/16806C85881A>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 12    | [7C93D5BC2B5B](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 2667 | 12    | [172CA9AD2823](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 800  | 12    | [A53D9E70F611](<Desktop/Others/Others/Others/A53D9E70F611>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1600 | 12    | [B514BDB172DC](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC>) |
| Samsung    | M378B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 12    | [0EF2C2D53CDB](<Desktop/MSI/MS/MS-7808/0EF2C2D53CDB>) |
| Samsung    | M471B5173QH0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 12    | [F8095F72B981](<Desktop/Others/YL-J3160/YL-J3160L4/F8095F72B981>) |
| SK Hynix   | HMT451U6BFR8A-PB DIMM        | 4 GB     | DDR3 | 1600 | 11    | [7942CFB9B709](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 TWR/7942CFB9B709>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 2400 | 11    | [A597A88660BB](<Desktop/ASRock/X470/X470 Gaming-ITX-ac/A597A88660BB>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 11    | [A9FC3E123192](<Notebook/ASUSTek Computer/1215/1215B/A9FC3E123192>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 800  | 11    | [0CA75ED82994](<Desktop/Supermicro/X7/X7SPA-H/0CA75ED82994>) |
|            | Module DIMM                  | 8 GB     |      | 1333 | 11    | [BBDCED21D8D8](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 11    | [4EEF21A68D4B](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C720/4EEF21A68D4B>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1600 | 10    | [1B931DE47D32](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/1B931DE47D32>) |
| Crucial    | CT16G4SFD824A.C16FDD SODIMM  | 16 GB    | DDR4 | 2400 | 10    | [7EBB25830BD7](<Desktop/Others/Others/Others/7EBB25830BD7>) |
| SK Hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 10    | [6962C79082CE](<Desktop/MSI/MS-9/MS-9A68/6962C79082CE>) |
| SK Hynix   | HMT451U6BFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 10    | [CAE61970AA22](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 10    | [5F93CB56E5D3](<Notebook/Lenovo/ThinkPad/ThinkPad X220 Tablet 42962WU/5F93CB56E5D3>) |
| Micron     | Module Row Of Chips LPDDR4   | 8 GB     |      | 3200 | 10    | [116441499573](<Desktop/BESSTAR Tech/X/X35G/116441499573>) |
| Samsung    | M393A2G40DB0-CPB DIMM        | 16 GB    | DDR4 | 2133 | 10    | [647219C1BB29](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 10    | [CF9C6401E02D](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/CF9C6401E02D>) |
| Samsung    | M471B1G73DB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 10    | [C21C5015F18D](<Desktop/Protectli/FW4/FW4B/C21C5015F18D>) |
| Corsair    | CML8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 9     | [203573A20C1C](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E720/203573A20C1C>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 9     | [9E3287D69794](<Notebook/Dell/Latitude/Latitude E5510/9E3287D69794>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3200 | 9     | [63762628C1D4](<Desktop/MSI/MS-7/MS-7B79/63762628C1D4>) |
| SK Hynix   | HMT351U6EFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 9     | [84B49072FBC7](<Desktop/Dell/OptiPlex/OptiPlex 9010/84B49072FBC7>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 9     | [E461B743FFCE](<Notebook/Packard Bell/EasyNote/EasyNote TE69HW/E461B743FFCE>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3200 | 9     | [19ABCB4216CF](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/19ABCB4216CF>) |
| Micron     | 8KTF51264HZ-1G9P1 SODIMM     | 4 GB     | DDR3 | 1867 | 9     | [5163FE0BC7B4](<Desktop/Fujitsu/FUTRO/FUTRO S920/5163FE0BC7B4>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 9     | [3A7D355EEBE4](<Notebook/Pegatron/T12/T12Ah/3A7D355EEBE4>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 1333 | 9     | [A80AD42ABF4E](<Notebook/PCSTICK/Others/Others/A80AD42ABF4E>) |
|            | Module(s) DIMM               | 8 GB     |      |      | 9     | [85EA4DD31903](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/85EA4DD31903>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 9     | [7DA907972285](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/7DA907972285>) |
| Corsair    | CMX8GX3M2A1333C9 DIMM        | 4 GB     |      | 1333 | 8     | [38D0B4D8000D](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D>) |
| Corsair    | CMZ16GX3M2A1600C10 DIMM      | 8 GB     | DDR3 | 1600 | 8     | [478D9BF28C74](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/478D9BF28C74>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1333 | 8     | [B804F93C38F2](<Notebook/Dell/Latitude/Latitude E5430 non-vPro/B804F93C38F2>) |
| SK Hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 8     | [3675D1C32D5B](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2347G7G/3675D1C32D5B>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 8     | [280D6DCE2A7B](<Desktop/Hewlett-Packard/Elite/Elite 7500 Series MT/280D6DCE2A7B>) |
| Micron     | 9ASF1G72AZ-2G3B1 DIMM        | 8 GB     | DDR4 | 2400 | 8     | [82CE853FF0D7](<Desktop/Dell/PowerEdge/PowerEdge T30/82CE853FF0D7>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 800  | 8     | [1DF42E107A56](<Desktop/IEESA/P5K/P5K PRO/1DF42E107A56>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 8     | [303F3801FE99](<Desktop/ASUSTek Computer/M4A785TD-V/M4A785TD-V EVO/303F3801FE99>) |
| Samsung    | M378B5273CH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 8     | [699073C65965](<Desktop/RUNING/B75M/B75M INTEL H3V/699073C65965>) |
| Samsung    | M391B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 8     | [09FA3CB37C02](<Server/Swyx Solutions/SwyxExpress/SwyxExpress/09FA3CB37C02>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 8     | [35A56C7E9951](<Desktop/ShenZhen MinWin Technology/3865/3865U-6L/35A56C7E9951>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 8     | [DB27396229F8](<Notebook/Lenovo/Legion/Legion Y540-15IRH 81SX/DB27396229F8>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 8     | [02CF0EC8D77A](<Desktop/Protectli/FW/FW6/02CF0EC8D77A>) |
| Samsung    | M471B1G73DH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 8     | [FEA9A2F7C9FB](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 8     | [D771CCA40E31](<Notebook/ASUSTek Computer/S550/S550CA/D771CCA40E31>) |
| Samsung    | Module DIMM                  | 4 GB     | DDR4 | 2133 | 8     | [B4C9208C5643](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/B4C9208C5643>) |
| SK Hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 8     | [EA208CC61F28](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L8S1GX00/EA208CC61F28>) |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 8     | [BADAE72EA873](<Notebook/Lenovo/ThinkPad/ThinkPad X201 32492EU/BADAE72EA873>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 7     | [0C4D2C0C9274](<Notebook/Samsung Electronics/N/N100/0C4D2C0C9274>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 7     | [3E33018D012F](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/3E33018D012F>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 7     | [DCACBEC3B3A0](<Desktop/Dell/OptiPlex/OptiPlex 780/DCACBEC3B3A0>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3200 | 7     | [7E67E37C7634](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/7E67E37C7634>) |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 7     | [4817D15C5C95](<Notebook/ASUSTek Computer/U31/U31SD/4817D15C5C95>) |
| SK Hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 7     | [D0B94644586B](<Notebook/Dell/Inspiron/Inspiron 3521/D0B94644586B>) |
| Kingston   | 99U5428-018.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 7     | [E99B538EFA3F](<Desktop/PAIQ/EC3/EC3-BT19D4L/E99B538EFA3F>) |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 7     | [590935D8F1B7](<Desktop/ASRock/C70/C70M1/590935D8F1B7>) |
| Kingston   | 99U5700-028.A00G SODIMM      | 8 GB     | DDR4 | 2400 | 7     | [25AB1CC97BC0](<Desktop/Protectli/FW6/FW6E/25AB1CC97BC0>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 7     | [60F05A981BBB](<Desktop/ASRock/AM1/AM1H-ITX/60F05A981BBB>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 7     | [4E12BDD6F465](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/4E12BDD6F465>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 7     | [4E387A733CF9](<Notebook/Acer/TravelMate/TravelMate 5760G/4E387A733CF9>) |
| Nanya      | NT4GC64B8HG0NF-DI DIMM       | 4 GB     | DDR3 | 1600 | 7     | [B452BC284D9D](<Desktop/Dell/OptiPlex/OptiPlex 3010/B452BC284D9D>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 667  | 7     | [A098A01ACD0B](<Desktop/Intel/DG41TY/DG41TY AAE47335-300/A098A01ACD0B>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 7     | [505133B14946](<Notebook/Lenovo/ThinkPad/ThinkPad R60e 0658W2M/505133B14946>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1066 | 7     | [963CAF7FA0EE](<Desktop/Intel/DN2800MT/DN2800MT AAG23738-600/963CAF7FA0EE>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 7     | [68889627DD42](<Desktop/Supermicro/X8/X8STi/68889627DD42>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 7     | [467C3D4C3D7D](<Desktop/iXsystems/AMZ-FREENASMINI-DISKLESS-IXN/AMZ-FREENASMINI-DISKLESS-IXN/467C3D4C3D7D>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 7     | [19B59C75C139](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7002CUS/19B59C75C139>) |
| Ramaxel    | RMT3170MN68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 7     | [F9E4D2EC31AB](<Notebook/Lenovo/G480/G480 20149/F9E4D2EC31AB>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 7     | [4CA8BC93BA74](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74>) |
| Samsung    | M378B1G73DB0-CK0 DIMM        | 8 GB     | DDR3 | 1600 | 7     | [43A679AEDAD3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 TWR/43A679AEDAD3>) |
| Samsung    | M378B5173EB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 7     | [77F26F7C95C4](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/77F26F7C95C4>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 7     | [16ED21598C0F](<Desktop/Dell/OptiPlex/OptiPlex 9010/16ED21598C0F>) |
| Samsung    | M391B5273CH0-YH9 DIMM        | 4 GB     | DDR3 | 1333 | 7     | [2AEB8D3520AF](<Server/Dell/PowerEdge/PowerEdge T310/2AEB8D3520AF>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 7     | [F36FD56B8299](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/F36FD56B8299>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 7     | [092F978DF489](<Desktop/Tarox/ECO/ECO 60-1/092F978DF489>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 7     | [9BA4726CBC1C](<Notebook/Toshiba/PORTEGE/PORTEGE M780/9BA4726CBC1C>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 7     | [12A699DD3987](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/12A699DD3987>) |
| SK Hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2133 | 7     | [2BD0319875C3](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3>) |
| SK Hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 7     | [F95318B57CEC](<Desktop/Others/Others/Others/F95318B57CEC>) |
| SK Hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 7     | [3478B69C1113](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KS005BRI/3478B69C1113>) |
| Super T... | SUPERTALENT02 DIMM           | 2 GB     | DDR3 | 1333 | 7     | [A20CE8F588F2](<Server/Trustwave/TS/TS-150/A20CE8F588F2>) |
| Transcend  | TS1GLH64V6B3 SODIMM          | 8 GB     | DDR4 | 1333 | 7     | [E6C07F974FDF](<Notebook/Deciso/Netboard/Netboard A20/E6C07F974FDF>) |
| ATP        | AW12P6438BLK0S DIMM          | 4 GB     | DDR3 | 1600 | 6     | [B46CD6868798](<Desktop/NF541/1/1.0/B46CD6868798>) |
| Corsair    | CMSO16GX4M1A2133C15 SODIMM   | 16 GB    | DDR4 | 2133 | 6     | [B866458DD3FC](<Desktop/Others/Others/Others/B866458DD3FC>) |
| Corsair    | CMSO8GX3M1C1600C11 SODIMM    | 8 GB     | DDR3 | 1600 | 6     | [384980EB885D](<Notebook/Dell/Latitude/Latitude E7450/384980EB885D>) |
| Corsair    | CMV4GX3M1A1333C9 DIMM        | 4 GB     | DDR3 | 1333 | 6     | [DE132CAE57CE](<Desktop/ASUSTek Computer/F2/F2A85-M/DE132CAE57CE>) |
| Crucial    | BLS4G3D1609DS1S00. DIMM      | 4 GB     | DDR3 | 1600 | 6     | [FC4E6B9DA406](<Desktop/ASUSTek Computer/All/All Series/FC4E6B9DA406>) |
| Crucial    | CT4G4SFS824A.C8FF SODIMM     | 4 GB     | DDR4 | 2400 | 6     | [7C58F64C2AFE](<Desktop/Protectli/FW/FW6/7C58F64C2AFE>) |
| Crucial    | CT51264BF160BJ.C8F SODIMM    | 4 GB     | DDR3 | 1600 | 6     | [16123572AAD5](<Mini Pc/CompuLab/fitlet/fitlet2/16123572AAD5>) |
| Crucial    | CT51264BF160BJ.M8F DIMM      | 4 GB     | DDR3 | 1600 | 6     | [7AF86A68764E](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E>) |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 6     | [491D65A1BD89](<Notebook/Lenovo/Z50-70/Z50-70 20354/491D65A1BD89>) |
| SK Hynix   | HMT325S6CFR8C-PB SODIMM      | 2 GB     | DDR3 | 1600 | 6     | [1B8E9987FB7C](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C>) |
| SK Hynix   | HMT325U6CFR8C-PB DIMM        | 2 GB     | DDR3 | 1600 | 6     | [630D25B19798](<Desktop/Dell/OptiPlex/OptiPlex 9010/630D25B19798>) |
| SK Hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1333 | 6     | [1B931DE47D32](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/1B931DE47D32>) |
| SK Hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 6     | [BB53092842EE](<Desktop/Intel/DCP847SKE/DCP847SKE G80890-107/BB53092842EE>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 6     | [733DE472055D](<Desktop/ASUSTek Computer/All/All Series/733DE472055D>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 6     | [733DE472055D](<Desktop/ASUSTek Computer/All/All Series/733DE472055D>) |
| Kingston   | KHX1600C10D3/8GX DIMM        | 8 GB     | DDR3 | 1600 | 6     | [A11B14F4032A](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/A11B14F4032A>) |
| Kingston   | KHX1600C9S3L/4G SODIMM       | 4 GB     | DDR3 | 1600 | 6     | [938874BCC36D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/938874BCC36D>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 6     | [58578EBA1828](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/58578EBA1828>) |
| Kingston   | KHX2400C14S4/8G SODIMM       | 8 GB     | DDR4 | 2400 | 6     | [BA57FC9C5E6C](<Desktop/ASRock/J5040/J5040-ITX/BA57FC9C5E6C>) |
| Kingston   | KHX2400C15/16G DIMM          | 16 GB    | DDR4 | 2400 | 6     | [1B846BF54775](<Desktop/ASUSTek Computer/TUF/TUF B365M-PLUS GAMING/1B846BF54775>) |
| Kingston   | KHX2666C15S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 6     | [ABE20D4E9177](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177>) |
| Micron     | 16KTF1G64HZ-1G6N1 SODIMM     | 8 GB     | DDR3 | 1600 | 6     | [A5FE30CD215B](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 DM/A5FE30CD215B>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 6     | [4154E650F617](<Desktop/Lenovo/IdeaCentre/IdeaCentre B545 10100/4154E650F617>) |
| Micron     | 18KSF1G72AZ-1G6P1 DIMM       | 8 GB     | DDR3 | 1600 | 6     | [CF3530F1EDC6](<Firewall/Sophos/SG/SG/CF3530F1EDC6>) |
| Micron     | 36ASF2G72PZ-2G1A2 DIMM       | 16 GB    | DDR4 | 2133 | 6     | [7894CF899C67](<Desktop/KLLISRE/X99-B5/X99-B5 V1.0/7894CF899C67>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 6     | [A17BA6584F09](<Notebook/Dell/Latitude/Latitude E5470/A17BA6584F09>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 6     | [8D5A2ED4C475](<Notebook/Lenovo/ThinkPad/ThinkPad T490s 20NYS3TU00/8D5A2ED4C475>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 6     | [9E562482276E](<Desktop/Gigabyte Technology/G31/G31M-ES2C/9E562482276E>) |
|            | Module FB-DIMM               | 2 GB     | DDR2 | 667  | 6     | [551885437D04](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 800  | 6     | [6A3BAA65B383](<Desktop/Others/Others/Others/6A3BAA65B383>) |
|            | Module DIMM SDRAM            | 4 GB     |      |      | 6     | [55A5BF807E33](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 6     | [FE70FB1F858A](<Desktop/MSI/MS/MS-9129/FE70FB1F858A>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 6     | [7A23185583F9](<Desktop/Intel/DENLOW_WS/DENLOW_WS/7A23185583F9>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 6     | [D6775F31A0B7](<Desktop/Hewlett-Packard/HPE-570/HPE-570f/D6775F31A0B7>) |
| Samsung    | M391B5173QH0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 6     | [19696ACD0153](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 6     | [09E47D6108B5](<Notebook/Lenovo/V310-14IKB/V310-14IKB 80T2/09E47D6108B5>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2400 | 6     | [160442CAFE60](<Desktop/Others/Others/Others/160442CAFE60>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 6     | [DCA0C34D1413](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS4KH02/DCA0C34D1413>) |
| Samsung    | M471B5173DB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 6     | [576F6CF2C638](<Desktop/ZOTAC/Others/Others/576F6CF2C638>) |
| Samsung    | M471B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 6     | [F3E260798AA5](<Desktop/Lenovo/ThinkCentre/ThinkCentre M600 10GB000TRU/F3E260798AA5>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 6     | [2EF21B21A43F](<Desktop/Fujitsu/FUTRO/FUTRO S720/2EF21B21A43F>) |
| SK Hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 6     | [DA4017866B4B](<Notebook/Dell/G5/G5 5590/DA4017866B4B>) |
| SK Hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2400 | 6     | [5B70EA1A7528](<Notebook/Lenovo/ThinkPad/ThinkPad T470s W10DG 20JTS0A900/5B70EA1A7528>) |
| Corsair    | CMK32GX4M2A2666C16 DIMM      | 16 GB    | DDR4 | 2667 | 5     | [9903E554229B](<Desktop/ASRock/H370/H370M-ITX-ac/9903E554229B>) |
| Crucial    | CT8G4SFRA266.C8FE SODIMM     | 8 GB     | DDR4 | 2667 | 5     | [45F90C839016](<Desktop/Protectli/FW6/FW6D/45F90C839016>) |
| G.Skill    | F4-2400C16-16GRS SODIMM      | 16 GB    | DDR4 | 2400 | 5     | [75AD313C46BF](<Desktop/Others/Others/Others/75AD313C46BF>) |
| G.Skill    | F4-2400C16-4GRS SODIMM       | 4 GB     | DDR4 | 2400 | 5     | [5472E9DDAC21](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21>) |
| G.Skill    | F4-2400C16-8GRS SODIMM       | 8 GB     | DDR4 | 2400 | 5     | [3BDFC2AF1E56](<Desktop/Others/Others/Others/3BDFC2AF1E56>) |
| SK Hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 5     | [F20A633E5003](<Notebook/Acer/Aspire/Aspire A315-23/F20A633E5003>) |
| SK Hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 1600 | 5     | [846500491E77](<Notebook/Hewlett-Packard/Stream/Stream Notebook PC 11/846500491E77>) |
| SK Hynix   | HMT41GU7BFR8A-PB DIMM        | 8 GB     | DDR3 | 1600 | 5     | [F049CD09521E](<Server/Dell/PowerEdge/PowerEdge R220/F049CD09521E>) |
| SK Hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 1600 | 5     | [845132047FF4](<Notebook/ASUSTek Computer/X555/X555LA/845132047FF4>) |
| SK Hynix   | HMT325U6CFR8C-H9 DIMM        | 2 GB     | DDR3 | 1333 | 5     | [E1BC5C7732DD](<Desktop/Lenovo/ThinkCentre/ThinkCentre M71e 3134C3U/E1BC5C7732DD>) |
| Kimtigo    | KT4GS3ED8 DIMM               | 4 GB     | DDR3 | 1600 | 5     | [46F2ABAF9115](<Mini Pc/AMI/Aptio/Aptio CRB/46F2ABAF9115>) |
| Kingston   | 9965525-116.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 5     | [CDCF2A093383](<Desktop/ASRock/E3/E3C226D2I/CDCF2A093383>) |
| Kingston   | 9965745-002.A00G DIMM        | 16 GB    | DDR4 | 3000 | 5     | [9A04D58CD175](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175>) |
| Kingston   | 99U5428-040.A01LF SODIMM     | 4 GB     | DDR3 | 1333 | 5     | [6C5362B21727](<Desktop/EXTRA Computer/D3003/D3003-S2/6C5362B21727>) |
| Kingston   | CBD26D4S9S1ME-8 SODIMM       | 8 GB     | DDR4 | 2667 | 5     | [C58B62159DE0](<Desktop/BESSTAR Tech/UM/UM270/C58B62159DE0>) |
| Kingston   | KHX1866C10D3/4G DIMM         | 4 GB     | DDR3 | 1867 | 5     | [FC0312FDD801](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/FC0312FDD801>) |
| Kingston   | KHX2400C14S4/16G SODIMM      | 16 GB    | DDR4 | 2400 | 5     | [2CD30E743AF3](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3>) |
| Kingston   | KHX2666C15S4/8G SODIMM       | 8 GB     | DDR4 | 2667 | 5     | [4C15498EEAD1](<Desktop/ASRock/A300/A300M-STX/4C15498EEAD1>) |
| Kingston   | Module SODIMM                | 4 GB     | DDR3 | 1333 | 5     | [FA1265ADE548](<Mini Pc/Apple/Macmini5/Macmini5,1/FA1265ADE548>) |
| Micron     | 16ATF1G64HZ-2G1A2 SODIMM     | 8 GB     | DDR4 | 2133 | 5     | [E6AAE60B4973](<Notebook/Dell/Precision/Precision 7710/E6AAE60B4973>) |
| Micron     | 16JTF51264AZ-1G4M1 DIMM      | 4 GB     | DDR3 | 1333 | 5     | [6D2B4AECE84E](<Desktop/Dell/OptiPlex/OptiPlex 790/6D2B4AECE84E>) |
| Micron     | 16KTF1G64HZ-1G6E1 DIMM       | 8 GB     | DDR3 | 1600 | 5     | [F72AFC021F41](<Mini Pc/AMI/Aptio/Aptio CRB/F72AFC021F41>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 5     | [791A09644467](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IH_FA506IH/791A09644467>) |
| Micron     | 4ATF51264HZ-2G3E1 SODIMM     | 4 GB     | DDR4 | 2400 | 5     | [510E40E5A8D2](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X712DAP_M712DA/510E40E5A8D2>) |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8 GB     | DDR4 | 3200 | 5     | [D2CB8BAABEFC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC>) |
| Micron     | 8JTF25664AZ-1G4D1 DIMM       | 2 GB     | DDR3 | 1333 | 5     | [7DA907972285](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/7DA907972285>) |
| Patriot    | PSD38G1600L2S SODIMM         | 8 GB     | DDR3 | 1600 | 5     | [D2292E0C5E07](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07>) |
|            | Module SODIMM                | 1 GB     | DDR2 |      | 5     | [505133B14946](<Notebook/Lenovo/ThinkPad/ThinkPad R60e 0658W2M/505133B14946>) |
|            | Module DIMM DDR              | 2 GB     |      | 1333 | 5     | [4E8B511BEAAC](<Desktop/ASUSTek Computer/P7/P7H55-M/4E8B511BEAAC>) |
|            | Module DIMM                  | 2 GB     | DDR2 |      | 5     | [38C292CE2082](<Desktop/Pegatron/IPM41/IPM41-D3/38C292CE2082>) |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 5     | [D7C334EEC193](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/D7C334EEC193>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 5     | [D9E53536E7D5](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/D9E53536E7D5>) |
|            | Module DIMM                  | 4 GB     |      | 1600 | 5     | [5B5ADE5E3B56](<Desktop/ASUSTek Computer/M5/M5A88-M/5B5ADE5E3B56>) |
|            | Module FB-DIMM               | 4 GB     | DDR2 | 667  | 5     | [551885437D04](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04>) |
|            | Module DIMM                  | 4 GB     | DDR2 | 800  | 5     | [5BEEAB14F9A7](<Desktop/Lex/Pineview-D/Pineview-D/5BEEAB14F9A7>) |
|            | Module SODIMM                | 4 GB     | DDR2 | 800  | 5     | [7CA5763D4ADE](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1333 | 5     | [EA850AA13DB1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/EA850AA13DB1>) |
|            | Module DIMM                  | 8 GB     | DDR4 | 2400 | 5     | [381363A61F71](<Desktop/Hewlett-Packard/ProLiant/ProLiant EC200a/381363A61F71>) |
| Ramaxel    | RMR5030MN68F9F1600 DIMM      | 4 GB     | DDR3 | 1600 | 5     | [3F8BEBB470E5](<Desktop/Dell/OptiPlex/OptiPlex 7010/3F8BEBB470E5>) |
| Ramaxel    | RMR5040ED58E9W1600 DIMM      | 4 GB     | DDR3 | 1600 | 5     | [F53B14F3D07E](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E>) |
| Samsung    | M391A2K43BB1-CPB DIMM        | 16 GB    | DDR4 | 2133 | 5     | [4C2A3BFED0EE](<Server/Supermicro/Super/Super Server/4C2A3BFED0EE>) |
| Samsung    | M391A2K43BB1-CTD DIMM        | 16 GB    | DDR4 | 2667 | 5     | [8E3B68877E47](<Server/Supermicro/Super/Super Server/8E3B68877E47>) |
| Samsung    | M391B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 5     | [DD6E77F0A481](<Server/Supermicro/X10/X10SLH-N6-ST031/DD6E77F0A481>) |
| Samsung    | M393B5170FH0-CH9 DIMM        | 4 GB     |      | 1333 | 5     | [B6E6FA55AFB2](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2>) |
| Samsung    | M471A2G44AM0-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 5     | [3C494D1552EB](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 5     | [31699ACF8451](<Notebook/WOOKING/X/X5/31699ACF8451>) |
| Samsung    | M471B5173CB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 5     | [DCC288803E27](<Notebook/HASEE Computer/CW35/CW35S/DCC288803E27>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     |      | 1067 | 5     | [DB693EA33F49](<Notebook/Lenovo/G550/G550 2958/DB693EA33F49>) |
| SK Hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 5     | [D2EB797FBDB6](<Notebook/Lenovo/ThinkPad/ThinkPad T470s W10DG 20JS001FGE/D2EB797FBDB6>) |
| SK Hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 5     | [62D7C65FC1E9](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX504GD_FX80GD/62D7C65FC1E9>) |
| SK Hynix   | HMA851U6AFR6N-UH DIMM        | 4 GB     | DDR4 | 2400 | 5     | [E3ED1B71BC40](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40>) |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 5     | [DDA6C3FBF9B0](<Notebook/Toshiba/Satellite/Satellite C855-1U4/DDA6C3FBF9B0>) |
| SK Hynix   | HMT351U7BFR8A-H9 DIMM        | 4 GB     | DDR3 | 1333 | 5     | [FA9EEF8E1FF1](<Server/Dell/PowerEdge/PowerEdge R310/FA9EEF8E1FF1>) |
| SK Hynix   | Module SODIMM                | 4 GB     | DDR3 | 1600 | 5     | [60ED6011F0FC](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60ED6011F0FC>) |
| Transcend  | TS1GLK72V6H DIMM             | 8192 MB  | DDR3 | 1600 | 5     | [B77E3EF73ADC](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/B77E3EF73ADC>) |
|            | 123456789012345678 SODIMM... | 1536 MB  |      | 2133 | 4     | [BCAD2CB6073B](<Notebook/Jumper/EZbook/EZbook/BCAD2CB6073B>) |
|            | AW24P64F8BLK0S DIMM          | 8 GB     | DDR3 | 1600 | 4     | [279EB59964E3](<Desktop/Others/YL-J3160/YL-J3160L4/279EB59964E3>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 2933 | 4     | [E6F16180BA3A](<Desktop/ASRock/B460M/B460M Pro4/E6F16180BA3A>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3200 | 4     | [734460839920](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO/734460839920>) |
| Corsair    | CML16GX3M2A1600C10 DIMM      | 8 GB     | DDR3 | 1600 | 4     | [E5B301480E98](<Desktop/ASUSTek Computer/All/All Series/E5B301480E98>) |
| Corsair    | CML16GX3M2A1600C9 DIMM       | 8 GB     | DDR3 | 1600 | 4     | [0F0FB0273B8E](<Desktop/ASUSTek Computer/All/All Series/0F0FB0273B8E>) |
| Corsair    | CMSO32GX4M2A2133C15 SODIMM   | 16 GB    | DDR4 | 2133 | 4     | [FBAB5FACE2AA](<Notebook/Shuttle/DS77/DS77U/FBAB5FACE2AA>) |
| Corsair    | CMSO4GX3M1A1333C9 SODIMM     | 4 GB     |      | 1333 | 4     | [D86A261F2083](<Notebook/Lenovo/G550/G550 2958/D86A261F2083>) |
| Corsair    | CMSX64GX4M2A2666C18 SODIMM   | 32 GB    | DDR4 | 2667 | 4     | [5BEE2A4C3CA7](<Notebook/Dell/Precision/Precision 7530/5BEE2A4C3CA7>) |
| Corsair    | CMZ16GX3M4A1600C9 DIMM       | 4 GB     | DDR3 | 1600 | 4     | [8241528A2428](<Desktop/Gigabyte Technology/H97/H97N-WIFI/8241528A2428>) |
| Crucial    | BLS4G4D240FSE.8FBD DIMM      | 4 GB     | DDR4 | 2400 | 4     | [8AC618CED035](<Desktop/MSI/MS/MS-7996/8AC618CED035>) |
| Crucial    | BLS8G4D240FSB.16FBD DIMM     | 8 GB     | DDR4 | 2933 | 4     | [8123071B0896](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896>) |
| Crucial    | CT16G4SFRA266.C8FE SODIMM    | 16 GB    | DDR4 | 2667 | 4     | [3E9671E20678](<Desktop/Others/MANIFOLD/MANIFOLD 2-C/3E9671E20678>) |
| Crucial    | CT16G4SFRA266.M16FRS SODIMM  | 16 GB    | DDR4 | 2667 | 4     | [B15ABD94737B](<Desktop/Protectli/FW/FW6/B15ABD94737B>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| SANYO      | 45N1773 LION   | 23.2  |         | 24    | [2AF47B6502](https://bsd-hardware.info/?probe=2af47b6502) |
| ASUSTek    | ASUS           | 76.0  |         | 22    | [20CDC9D999](https://bsd-hardware.info/?probe=20cdc9d999) |
| LGC        | 45N1127 LION   | 23.5  |         | 14    | [BC2860431E](https://bsd-hardware.info/?probe=bc2860431e) |
| Lenovo     | PABAS024123... | 25.9  |         | 13    | [BC5296EE7D](https://bsd-hardware.info/?probe=bc5296ee7d) |
| Samsung    | Serial numb... | 48.8  |         | 13    | [3125D76BA4](https://bsd-hardware.info/?probe=3125d76ba4) |
| Hewlett... | PABAS024123... | 41.0  |         | 12    | [766E62F699](https://bsd-hardware.info/?probe=766e62f699) |
| SANYO      | 45N1775 LION   | 23.2  |         | 11    | [DEAC163B52](https://bsd-hardware.info/?probe=deac163b52) |
| OEM        | standard LiON  | 46.7  |         | 10    | [4FBB430947](https://bsd-hardware.info/?probe=4fbb430947) |
| Compal     | PABAS024123... | 41.0  |         | 9     | [A6D7796CEA](https://bsd-hardware.info/?probe=a6d7796cea) |
| MSI        | BIF0_9         | 67.7  |         | 9     | [61E3F35EE8](https://bsd-hardware.info/?probe=61e3f35ee8) |
| SANYO      | 45N1001 LION   | 60.7  |         | 9     | [973ADE9E4A](https://bsd-hardware.info/?probe=973ade9e4a) |
| SANYO      | 42T4861 LION   | 57.7  |         | 8     | [DD4D3A9DCC](https://bsd-hardware.info/?probe=dd4d3a9dcc) |
| SANYO      | 45N1023 LION   | 66.6  |         | 8     | [2DBB2679F1](https://bsd-hardware.info/?probe=2dbb2679f1) |
| Sony       | 45N1111 LiP    | 23.2  |         | 8     | [87BC0B8924](https://bsd-hardware.info/?probe=87bc0b8924) |
| LGC        | 45N1113 LION   | 23.5  |         | 7     | [89A74889AE](https://bsd-hardware.info/?probe=89a74889ae) |
| LGC        | 45N1738 LION   | 71.1  |         | 7     | [3EF1595AF6](https://bsd-hardware.info/?probe=3ef1595af6) |
| SANYO      | 42T4763 LION   | 47.5  |         | 7     | [8BD2318FB6](https://bsd-hardware.info/?probe=8bd2318fb6) |
| Hewlett... | Primary LIon   | 40    |         | 6     | [E2CC942E3E](https://bsd-hardware.info/?probe=e2cc942e3e) |
| Hewlett... | Primary LIon   | 43    |         | 6     | [494195B923](https://bsd-hardware.info/?probe=494195b923) |
| LGC        | 45N1005 LION   | 47.5  |         | 6     | [0F001F65D2](https://bsd-hardware.info/?probe=0f001f65d2) |
| SANYO      | 92P1137 LION   | 71.3  |         | 6     | [88B86ECF8B](https://bsd-hardware.info/?probe=88b86ecf8b) |
| Hewlett... | Primary LIon   | 42    |         | 5     | [937ED102D1](https://bsd-hardware.info/?probe=937ed102d1) |
| Hewlett... | Primary LIon   | 56    |         | 5     | [130803FAD8](https://bsd-hardware.info/?probe=130803fad8) |
| Hewlett... | Serial numb... | 12.0  |         | 5     | [E0C8E95E52](https://bsd-hardware.info/?probe=e0c8e95e52) |
| Lenovo ... | Serial numb... | 41.4  |         | 5     | [AB71ED7239](https://bsd-hardware.info/?probe=ab71ed7239) |
| LGC        | 02DL007 LiP    | 50.5  |         | 5     | [087D40BA7C](https://bsd-hardware.info/?probe=087d40ba7c) |
| LGC        | 45N1011 LION   | 93.6  |         | 5     | [66C64C1AF9](https://bsd-hardware.info/?probe=66c64c1af9) |
| LGC        | 45N1735 LION   | 47.5  |         | 5     | [2AF47B6502](https://bsd-hardware.info/?probe=2af47b6502) |
| Notebook   | BAT LION       | 35    |         | 5     | [4AC0707C49](https://bsd-hardware.info/?probe=4ac0707c49) |
| Notebook   | BAT LION       | 62    |         | 5     | [1099E6C574](https://bsd-hardware.info/?probe=1099e6c574) |
| NVT        | Framewo LION   | 55.0  |         | 5     | [1F58E0594F](https://bsd-hardware.info/?probe=1f58e0594f) |
| Samsung    | SR Real LION   | 39.0  |         | 5     | [B344605891](https://bsd-hardware.info/?probe=b344605891) |
| SANYO      | 00HW022 LiP    | 23.5  |         | 5     | [6C895CB96F](https://bsd-hardware.info/?probe=6c895cb96f) |
| SANYO      | 01AV405 LION   | 26.3  |         | 5     | [DBB0E378D5](https://bsd-hardware.info/?probe=dbb0e378d5) |
| SANYO      | 45N1767 LION   | 47.5  |         | 5     | [BA0270C8F8](https://bsd-hardware.info/?probe=ba0270c8f8) |
| SANYO      | 45N1777 LION   | 71.3  |         | 5     | [4BA527DC9B](https://bsd-hardware.info/?probe=4ba527dc9b) |
| SANYO      | 45N1779 LION   | 99.5  |         | 5     | [B6DFFE77EB](https://bsd-hardware.info/?probe=b6dffe77eb) |
| ASUSTek    | A32-K55        | 48.0  |         | 4     | [11BBFCE5D4](https://bsd-hardware.info/?probe=11bbfce5d4) |
| Hewlett... | Primary LIon   | 38    |         | 4     | [D4FFC24C6F](https://bsd-hardware.info/?probe=d4ffc24c6f) |
| Hewlett... | Primary LIon   | 45    |         | 4     | [F3C014B120](https://bsd-hardware.info/?probe=f3c014b120) |
| Intel SR 1 | SR Real Real   | 35.0  |         | 4     | [7D648BCDC7](https://bsd-hardware.info/?probe=7d648bcdc7) |
| LGC        | 00HW028 LiP    | 52.3  |         | 4     | [9C85F07244](https://bsd-hardware.info/?probe=9c85f07244) |
| LGC        | 01AV445 LiP    | 45.0  |         | 4     | [BE311B6A34](https://bsd-hardware.info/?probe=be311b6a34) |
| LGC        | 45N1029 LION   | 103.5 |         | 4     | [148A268A0F](https://bsd-hardware.info/?probe=148a268a0f) |
| LGC        | DELL 49VTP ... | 57.7  |         | 4     | [DE97E0B2FC](https://bsd-hardware.info/?probe=de97e0b2fc) |
| Notebook   | BAT LION       | 49    |         | 4     | [A376201681](https://bsd-hardware.info/?probe=a376201681) |
| Notebook   | BAT LION       | 74    |         | 4     | [713B33351F](https://bsd-hardware.info/?probe=713b33351f) |
| PANASONIC  | AS16A5K LION   | 31.7  |         | 4     | [2A8624EE35](https://bsd-hardware.info/?probe=2a8624ee35) |
| SANYO      | 45N1037 LION   | 39.0  |         | 4     | [B1377872CD](https://bsd-hardware.info/?probe=b1377872cd) |
| SANYO      | PABAS024123... | 56.8  |         | 4     | [B14C4C1AC5](https://bsd-hardware.info/?probe=b14c4c1ac5) |
| SMP        | 01AV421 LiP    | 24.0  |         | 4     | [2F1BA02130](https://bsd-hardware.info/?probe=2f1ba02130) |
| SMP        | 01AV430 LiP    | 57.0  |         | 4     | [4993AD0FEB](https://bsd-hardware.info/?probe=4993ad0feb) |
| SMP        | 45N1071 LiP    | 46.0  |         | 4     | [28BBEB8B2E](https://bsd-hardware.info/?probe=28bbeb8b2e) |
| SMP        | DELL GPM036... | 97.0  |         | 4     | [EE8980FEC1](https://bsd-hardware.info/?probe=ee8980fec1) |
| Sony       | Serial numb... | 37.5  |         | 4     | [03EF84679C](https://bsd-hardware.info/?probe=03ef84679c) |
| ASUSTek    | K55--47        | 57.7  |         | 3     | [C7C812C2C9](https://bsd-hardware.info/?probe=c7c812c2c9) |
| ASUSTek    | X202-51        | 38.0  |         | 3     | [7F4E6F4541](https://bsd-hardware.info/?probe=7f4e6f4541) |
| CPT-COS    | L16C2PB2 LiP   | 30.6  |         | 3     | [6BDE68715E](https://bsd-hardware.info/?probe=6bde68715e) |
| Hewlett... | Primary        | 48    |         | 3     | [27F912E4E4](https://bsd-hardware.info/?probe=27f912e4e4) |
| Hewlett... | Primary LIon   | 35    |         | 3     | [606D75E6A1](https://bsd-hardware.info/?probe=606d75e6a1) |
| Hewlett... | Primary LIon   | 37    |         | 3     | [D23636ABB2](https://bsd-hardware.info/?probe=d23636abb2) |
| Hewlett... | Primary LIon   | 46    |         | 3     | [BB5A564A50](https://bsd-hardware.info/?probe=bb5a564a50) |
| LGC        | 01AV432 LiP    | 51.0  |         | 3     | [C27BA488AA](https://bsd-hardware.info/?probe=c27ba488aa) |
| LGC        | 01AV478 LiP    | 57.0  |         | 3     | [556FCB7E5E](https://bsd-hardware.info/?probe=556fcb7e5e) |
| LGC        | 42T4865 LION   | 64.1  |         | 3     | [8C7992E557](https://bsd-hardware.info/?probe=8c7992e557) |
| LGC        | 42T4911 LION   | 56.2  |         | 3     | [82F5612822](https://bsd-hardware.info/?probe=82f5612822) |
| LGC        | 45N1025 LION   | 57.7  |         | 3     | [B8729E39E1](https://bsd-hardware.info/?probe=b8729e39e1) |
| LGC        | 5B10W138 LiP   | 45.0  |         | 3     | [3D50BA4D85](https://bsd-hardware.info/?probe=3d50ba4d85) |
| LGC        | L17L3PG1 LiP   | 52.5  |         | 3     | [D8F8901AE7](https://bsd-hardware.info/?probe=d8f8901ae7) |
| Notebook   | BAT LION       | 60    |         | 3     | [47C30B962D](https://bsd-hardware.info/?probe=47c30b962d) |
| OEM        | FX50442        | 48.0  |         | 3     | [2D72B6939D](https://bsd-hardware.info/?probe=2d72b6939d) |
| PANASONIC  | Li_Ion_4000... | 47.5  |         | 3     | [FAE71F7E35](https://bsd-hardware.info/?probe=fae71f7e35) |
| Samsung... | DELL MT2648... | 86.6  |         | 3     | [08FE78379D](https://bsd-hardware.info/?probe=08fe78379d) |
| Samsung... | DELL P8TC72... | 73.3  |         | 3     | [D31F35BB29](https://bsd-hardware.info/?probe=d31f35bb29) |
| SANYO      | 45N1172 LION   | 62.6  |         | 3     | [786669CC9C](https://bsd-hardware.info/?probe=786669cc9c) |
| SANYO      | 45N1769 LION   | 56.2  |         | 3     | [CBA9255F4A](https://bsd-hardware.info/?probe=cba9255f4a) |
| SANYO      | AL12A32 Lion   | 37.0  |         | 3     | [851EEA349F](https://bsd-hardware.info/?probe=851eea349f) |
| SANYO      | GRAPE32 LION   | 48.8  |         | 3     | [6A1B523EFB](https://bsd-hardware.info/?probe=6a1b523efb) |
| SANYO      | Li_Ion_4000... | 47.5  |         | 3     | [BD22FC8A49](https://bsd-hardware.info/?probe=bd22fc8a49) |
| SIMPLO     | PABAS024123... | 4.3   |         | 3     | [E22DA97709](https://bsd-hardware.info/?probe=e22da97709) |
| SMP        | 00HW029 LiP    | 52.1  |         | 3     | [821C81E652](https://bsd-hardware.info/?probe=821c81e652) |
| SMP        | 00NY493 LiP    | 90.0  |         | 3     | [E4F43CFCAD](https://bsd-hardware.info/?probe=e4f43cfcad) |
| SMP        | 5B10W13931 LiP | 51.0  |         | 3     | [85E94A1288](https://bsd-hardware.info/?probe=85e94a1288) |
| SMP        | 5B11C732 LiP   | 57.0  |         | 3     | [6C208C85A5](https://bsd-hardware.info/?probe=6c208c85a5) |
| SMP        | DELL 71JF45... | 74.0  |         | 3     | [B4A35AA7B0](https://bsd-hardware.info/?probe=b4a35aa7b0) |
| SMP        | DELL VN3N04... | 41.4  |         | 3     | [7C6B2F2013](https://bsd-hardware.info/?probe=7c6b2f2013) |
| SMP        | L16M2PB1 LiP   | 30.0  |         | 3     | [87C8EE9B4C](https://bsd-hardware.info/?probe=87c8ee9b4c) |
| SMPNz451   | bq20z451       | 57.7  |         | 3     | [AA484C30A8](https://bsd-hardware.info/?probe=aa484c30a8) |
| ASUSTek    | 1015PE         | 47.5  |         | 2     | [EFEA0EFB2B](https://bsd-hardware.info/?probe=efea0efb2b) |
| ASUSTek    | 1215B          | 56.2  |         | 2     | [1CCF85F60D](https://bsd-hardware.info/?probe=1ccf85f60d) |
| ASUSTek    | K56--30        | 44.6  |         | 2     | [1263A5FB37](https://bsd-hardware.info/?probe=1263a5fb37) |
| ASUSTek    | UX31-35        | 50.6  |         | 2     | [9FEBAB6C01](https://bsd-hardware.info/?probe=9febab6c01) |
| Celxpert   | 01AV424 LiP    | 24.1  |         | 2     | [22B35A127A](https://bsd-hardware.info/?probe=22b35a127a) |
| Celxpert   | 01AV448 LiP    | 45.7  |         | 2     | [901005EDD3](https://bsd-hardware.info/?probe=901005edd3) |
| Celxpert   | 01AV475 LiP    | 54.1  |         | 2     | [F8801C62BC](https://bsd-hardware.info/?probe=f8801c62bc) |
| Celxpert   | 01AY969 LiP    | 80.4  |         | 2     | [6D5E1A13D0](https://bsd-hardware.info/?probe=6d5e1a13d0) |
| DPON016    | ASMB016        | 52.0  |         | 2     | [E0CF5200DE](https://bsd-hardware.info/?probe=e0cf5200de) |
| DYNAPACK   | HB4593R1ECW... | 56.3  |         | 2     | [F9FDC75B45](https://bsd-hardware.info/?probe=f9fdc75b45) |
| Hewlett... | Primary        | 55    |         | 2     | [EF66D7A110](https://bsd-hardware.info/?probe=ef66d7a110) |
| Hewlett... | Primary        | 95    |         | 2     | [476193BFD0](https://bsd-hardware.info/?probe=476193bfd0) |
| Hewlett... | Primary LIon   | 47    |         | 2     | [767B44A6AE](https://bsd-hardware.info/?probe=767b44a6ae) |
| Hewlett... | Primary LIon   | 55    |         | 2     | [D8FB34DE12](https://bsd-hardware.info/?probe=d8fb34de12) |
| Hewlett... | Primary LIon   | 64    |         | 2     | [CDC6F54D97](https://bsd-hardware.info/?probe=cdc6f54d97) |
| Intel SR 1 | Harris Beac... | 32.7  |         | 2     | [2F90D5C2BD](https://bsd-hardware.info/?probe=2f90d5c2bd) |
| Lenovo     | BASE-BAT LiP   | 36.5  |         | 2     | [66B8FC8279](https://bsd-hardware.info/?probe=66b8fc8279) |
| LG         | PABAS024123... | 48.9  |         | 2     | [74B11992D7](https://bsd-hardware.info/?probe=74b11992d7) |
| LGC        | 00NY486 LION   | 47.5  |         | 2     | [2AEA9384AC](https://bsd-hardware.info/?probe=2aea9384ac) |
| LGC        | 01AV420 LiP    | 23.9  |         | 2     | [E27342AB94](https://bsd-hardware.info/?probe=e27342ab94) |
| LGC        | 01AV423 LiP    | 23.9  |         | 2     | [E27342AB94](https://bsd-hardware.info/?probe=e27342ab94) |
| LGC        | 45N1049 LION   | 40.4  |         | 2     | [990E05C219](https://bsd-hardware.info/?probe=990e05c219) |
| LGC        | 45N1079 LION   | 62.2  |         | 2     | [DBD5C6E5E3](https://bsd-hardware.info/?probe=dbd5c6e5e3) |
| LGC        | 45N1147 LION   | 56.2  |         | 2     | [C51F274F90](https://bsd-hardware.info/?probe=c51f274f90) |
| LGC        | 45N1749 LiP    | 34.0  |         | 2     | [0E448AF5F5](https://bsd-hardware.info/?probe=0e448af5f5) |
| LGC        | 5B10W139 LiP   | 50.5  |         | 2     | [D910C79D75](https://bsd-hardware.info/?probe=d910c79d75) |
| LGC        | AC14B8K LION   | 48.9  |         | 2     | [4F02660D9C](https://bsd-hardware.info/?probe=4f02660d9c) |
| LGC        | AP18C8K Li-Ion | 48.0  |         | 2     | [F613CB0452](https://bsd-hardware.info/?probe=f613cb0452) |
| LGC-LGC... | DELL C27RW ... | 42.0  |         | 2     | [089B61BB38](https://bsd-hardware.info/?probe=089b61bb38) |
| LGC-LGC... | DELL FDRHM0... | 42.0  |         | 2     | [C2D56FC369](https://bsd-hardware.info/?probe=c2d56fc369) |
| LGC-LGC... | DELL RDYCT6... | 91.0  |         | 2     | [46E9438BF9](https://bsd-hardware.info/?probe=46e9438bf9) |
| LGC        | LNV-45N1 LION  | 47.0  |         | 2     | [0A6985F078](https://bsd-hardware.info/?probe=0a6985f078) |
| Notebook   | BAT LION       | 31    |         | 2     | [4ADFEAA072](https://bsd-hardware.info/?probe=4adfeaa072) |
| Notebook   | BAT LION       | 33    |         | 2     | [D2560F69F7](https://bsd-hardware.info/?probe=d2560f69f7) |
| Notebook   | BAT LION       | 36    |         | 2     | [792FB07DD9](https://bsd-hardware.info/?probe=792fb07dd9) |
| Notebook   | BAT LION       | 48    |         | 2     | [F9C37F2C8D](https://bsd-hardware.info/?probe=f9c37f2c8d) |
| Notebook   | BAT LION       | 53    |         | 2     | [F99C9F56B7](https://bsd-hardware.info/?probe=f99c9f56b7) |
| Panasonic  | 42T4620 LION   | 84.2  |         | 2     | [7D36D27958](https://bsd-hardware.info/?probe=7d36d27958) |
| Panasonic  | 45N1143 LION   | 43.3  |         | 2     | [DB2A9E5E6F](https://bsd-hardware.info/?probe=db2a9e5e6f) |
| Panasonic  | 92P1133 LION   | 84.2  |         | 2     | [9CC0F26F6F](https://bsd-hardware.info/?probe=9cc0f26f6f) |
| PANASONIC  | AP19B5K LION   | 39.7  |         | 2     | [7FB743C654](https://bsd-hardware.info/?probe=7fb743c654) |
| PANASONIC  | AS10B5E LION   | 64.8  |         | 2     | [1617262A28](https://bsd-hardware.info/?probe=1617262a28) |
| Samsung SD | DELL XRDW25... | 41.4  |         | 2     | [BB13E61DE1](https://bsd-hardware.info/?probe=bb13e61de1) |
| Samsung... | DELL 7DWMT1... | 98.2  |         | 2     | [2F848FD2C0](https://bsd-hardware.info/?probe=2f848fd2c0) |
| SANYO      | 01AV425 LION   | 47.5  |         | 2     | [6B2ABD4DF5](https://bsd-hardware.info/?probe=6b2abd4df5) |
| SANYO      | 42T4710 LION   | 77.0  |         | 2     | [70A56029E7](https://bsd-hardware.info/?probe=70a56029e7) |
| SANYO      | 42T4791 LION   | 56.2  |         | 2     | [5D7840D28E](https://bsd-hardware.info/?probe=5d7840d28e) |
| SANYO      | 42T4799 LION   | 96.1  |         | 2     | [E937639ADC](https://bsd-hardware.info/?probe=e937639adc) |
| SANYO      | 42T4940 LION   | 86.6  |         | 2     | [C5E7D3037F](https://bsd-hardware.info/?probe=c5e7d3037f) |
| SANYO      | 45N1027 LION   | 86.6  |         | 2     | [06C6A282CA](https://bsd-hardware.info/?probe=06c6a282ca) |
| SANYO      | 45N1173 LION   | 85.9  |         | 2     | [683ECA8C23](https://bsd-hardware.info/?probe=683eca8c23) |
| SANYO      | 45N1175 LION   | 85.9  |         | 2     | [791C826F7D](https://bsd-hardware.info/?probe=791c826f7d) |
| SANYO      | 45N1177 LION   | 62.6  |         | 2     | [55DEBB2F24](https://bsd-hardware.info/?probe=55debb2f24) |
| SANYO      | 45N1734 LION   | 47.5  |         | 2     | [4AE2360503](https://bsd-hardware.info/?probe=4ae2360503) |
| SANYO      | AP13J3K LION   | 45.3  |         | 2     | [D15CAACA04](https://bsd-hardware.info/?probe=d15caaca04) |
| Sanyo      | DELL M7T5F8... | 66.6  |         | 2     | [3F2E8586A7](https://bsd-hardware.info/?probe=3f2e8586a7) |
| SANYO      | PABAS024 LION  | 54.2  |         | 2     | [21407195E3](https://bsd-hardware.info/?probe=21407195e3) |
| SIMPLO     | AS10D75 LION   | 48.8  |         | 2     | [CC83218496](https://bsd-hardware.info/?probe=cc83218496) |
| Simplo     | Li_Ion_4000... | 48.8  |         | 2     | [0513869BE8](https://bsd-hardware.info/?probe=0513869be8) |
| SMP        | 00HW023 LiP    | 23.5  |         | 2     | [DBB0E378D5](https://bsd-hardware.info/?probe=dbb0e378d5) |
| SMP        | 01AV446 LiP    | 45.3  |         | 2     | [1A2F28F5CC](https://bsd-hardware.info/?probe=1a2f28f5cc) |
| SMP        | 01AV447 LiP    | 45.7  |         | 2     | [98072B8DB6](https://bsd-hardware.info/?probe=98072b8db6) |
| SMP        | 01AV471 LiP    | 48.0  |         | 2     | [FF53F0763C](https://bsd-hardware.info/?probe=ff53f0763c) |
| SMP        | 02DL008 LiP    | 50.5  |         | 2     | [6311D603FF](https://bsd-hardware.info/?probe=6311d603ff) |
| SMP        | 02DL014 LiP    | 57.0  |         | 2     | [D377309110](https://bsd-hardware.info/?probe=d377309110) |
| SMP        | 02DL028 LiP    | 90.0  |         | 2     | [5B08C1DE3D](https://bsd-hardware.info/?probe=5b08c1de3d) |
| SMP        | 5B10W139 LiP   | 50.5  |         | 2     | [D028FC63D4](https://bsd-hardware.info/?probe=d028fc63d4) |
| SMP        | DELL 39DY56... | 38.0  |         | 2     | [DC37C53E48](https://bsd-hardware.info/?probe=dc37c53e48) |
| SMP        | DELL 4HJXXD... | 99.9  |         | 2     | [CE29DAF5AD](https://bsd-hardware.info/?probe=ce29daf5ad) |
| SMP        | DELL 7V69Y5... | 62.0  |         | 2     | [AF72876FD2](https://bsd-hardware.info/?probe=af72876fd2) |
| SMP        | DELL 909H53... | 48.2  |         | 2     | [6EC8FD788A](https://bsd-hardware.info/?probe=6ec8fd788a) |
| SMP        | DELL C5KG60... | 40.0  |         | 2     | [465DD01C0D](https://bsd-hardware.info/?probe=465dd01c0d) |
| SMP        | DELL CRT6P2... | 99.9  |         | 2     | [529768F8C8](https://bsd-hardware.info/?probe=529768f8c8) |
| SMP        | DELL DM3WC6... | 60.0  |         | 2     | [DEFAEE0E5C](https://bsd-hardware.info/?probe=defaee0e5c) |
| SMP        | DELL GD1JP6... | 68.0  |         | 2     | [D4D653FBA8](https://bsd-hardware.info/?probe=d4d653fba8) |
| SMP        | DELL JHXPY5... | 57.5  |         | 2     | [4CC0FD57A5](https://bsd-hardware.info/?probe=4cc0fd57a5) |
| SMP        | DELL TP1GT6... | 60.0  |         | 2     | [F8BFC70F13](https://bsd-hardware.info/?probe=f8bfc70f13) |
| SMP        | DELL Y3F7Y6... | 42.0  |         | 2     | [3DBC09A4DF](https://bsd-hardware.info/?probe=3dbc09a4df) |
| SMP        | DELL Y61CV1... | 48.8  |         | 2     | [ABE1869A95](https://bsd-hardware.info/?probe=abe1869a95) |
| SMP        | L17M2PB7 LiP   | 30.0  |         | 2     | [CEB18E38A3](https://bsd-hardware.info/?probe=ceb18e38a3) |
| SMP-LG2.8  | DELL FW1MN3... | 41.4  |         | 2     | [8F8CC52F23](https://bsd-hardware.info/?probe=8f8cc52f23) |
| SMP        | LNV-45N1 LION  | 47.5  |         | 2     | [BF95CDEB53](https://bsd-hardware.info/?probe=bf95cdeb53) |
| SMP-SDI2.8 | DELL FW1MN3... | 41.4  |         | 2     | [B89DA90904](https://bsd-hardware.info/?probe=b89da90904) |
| SMPNz45... | bq20z45189A... | 87.5  |         | 2     | [6D580E8270](https://bsd-hardware.info/?probe=6d580e8270) |
| SMPNz95    | bq20z95        | 44.0  |         | 2     | [61C7028E83](https://bsd-hardware.info/?probe=61c7028e83) |
| Sony       | 45N1705 LiP    | 47.1  |         | 2     | [4E7ACE8A39](https://bsd-hardware.info/?probe=4e7ace8a39) |
| Sony       | VGP-BPS26  ... | 45.4  |         | 2     | [C471FB3F82](https://bsd-hardware.info/?probe=c471fb3f82) |
| State:	... | Serial numb... | 23.6  |         | 2     | [8D0AC5E551](https://bsd-hardware.info/?probe=8d0ac5e551) |
| State:	... | Serial numb... | 42.0  |         | 2     | [8CBE3D4581](https://bsd-hardware.info/?probe=8cbe3d4581) |
| State:	... | G71C000AH31... | 54.5  |         | 2     | [6357D0D51F](https://bsd-hardware.info/?probe=6357d0d51f) |
| State:	... | PA5109U-1BRS   | 48.6  | Li-ion  | 2     | [9FB68E38D8](https://bsd-hardware.info/?probe=9fb68e38d8) |
| Sunwoda    | 5B10W13975 LiP | 57.0  |         | 2     | [AD4F0D967D](https://bsd-hardware.info/?probe=ad4f0d967d) |
| Sunwoda    | L19D4PH3 LiP   | 61.0  |         | 2     | [2A54A0C338](https://bsd-hardware.info/?probe=2a54a0c338) |
| TPS        | S10            | 44.7  |         | 2     | [EDC2C4EC36](https://bsd-hardware.info/?probe=edc2c4ec36) |
| 11-83      | KP03036 LION   | 24.4  |         | 1     | [5300A49632](https://bsd-hardware.info/?probe=5300a49632) |
| 11-85      | OA04041 LION   | 29.1  |         | 1     | [E3F26D7245](https://bsd-hardware.info/?probe=e3f26d7245) |
| 13-14      | MO06062 LION   | 36.8  |         | 1     | [4637A9EEFF](https://bsd-hardware.info/?probe=4637a9eeff) |
| 13-42      | OA04041 LION   | 20.1  |         | 1     | [C2DA1DD654](https://bsd-hardware.info/?probe=c2da1dd654) |
| 131-42-6E  | HS03031 LION   | 27.8  |         | 1     | [1758596E26](https://bsd-hardware.info/?probe=1758596e26) |
| 313-54-41  | BI03041XL LION | 29.6  |         | 1     | [F27578615F](https://bsd-hardware.info/?probe=f27578615f) |
| 333-1C-    | SD03045 LION   | 45.0  |         | 1     | [4FFE68C199](https://bsd-hardware.info/?probe=4ffe68c199) |
| 333-2C-... | BN03051XL LION | 47.2  |         | 1     | [40A0D1E964](https://bsd-hardware.info/?probe=40a0d1e964) |
| 333-42-2A  | HV02032XL LION | 26.0  |         | 1     | [40624B04C0](https://bsd-hardware.info/?probe=40624b04c0) |
| 333-42-... | LK03055XL LION | 50.8  |         | 1     | [F45A4133BC](https://bsd-hardware.info/?probe=f45a4133bc) |
| 333-54-... | LK03055XL LION | 56.7  |         | 1     | [ADC45416CE](https://bsd-hardware.info/?probe=adc45416ce) |
| Acer       | Panasonic_LiON | 57.7  |         | 1     | [56A5581907](https://bsd-hardware.info/?probe=56a5581907) |
|            | AEC4347154 ... | 38.5  |         | 1     | [1970F517FD](https://bsd-hardware.info/?probe=1970f517fd) |
| ANKER13    | ASMB013        | 46.0  |         | 1     | [2CBA98F24B](https://bsd-hardware.info/?probe=2cba98f24b) |
| APL MRD    |  Lion          | 59.3  | Li-ion  | 1     | [BC44D767CC](https://bsd-hardware.info/?probe=bc44d767cc) |
| AS19IVD    | C300-42 LION   | 48.3  |         | 1     | [9BA239A4A3](https://bsd-hardware.info/?probe=9ba239a4a3) |
| ASUSTek    | Serial numb... | 51.7  |         | 1     | [C52B593262](https://bsd-hardware.info/?probe=c52b593262) |
| ASUSTek    | 1000           | 27.6  |         | 1     | [DA8689C840](https://bsd-hardware.info/?probe=da8689c840) |
| ASUSTek    | 1005P          | 23.2  |         | 1     | [648081D75B](https://bsd-hardware.info/?probe=648081d75b) |
| ASUSTek    | 1015BX         | 56.2  |         | 1     | [5834A52924](https://bsd-hardware.info/?probe=5834a52924) |
| ASUSTek    | 900A           | 36.9  |         | 1     | [A76303A060](https://bsd-hardware.info/?probe=a76303a060) |
| ASUSTek    | A6-4224        | 69.9  |         | 1     | [593C12AA06](https://bsd-hardware.info/?probe=593c12aa06) |
| ASUSTek    | F3---24        | 51.3  |         | 1     | [936A577D1A](https://bsd-hardware.info/?probe=936a577d1a) |
| ASUSTek    | F80--22        | 46.2  |         | 1     | [5F2DF13F5B](https://bsd-hardware.info/?probe=5f2df13f5b) |
| ASUSTek    | G73-52         | 78.0  |         | 1     | [6CA36A455D](https://bsd-hardware.info/?probe=6ca36a455d) |
| ASUSTek    | G74--52        | 78.0  |         | 1     | [96BEE8D702](https://bsd-hardware.info/?probe=96bee8d702) |
| ASUSTek    | G75--52        | 78.0  |         | 1     | [9B84D1E7E6](https://bsd-hardware.info/?probe=9b84d1e7e6) |
| ASUSTek    | G750-59        | 89.2  |         | 1     | [37BE4EA27A](https://bsd-hardware.info/?probe=37be4ea27a) |
| ASUSTek    | K53--52        | 55.0  |         | 1     | [975E9CCBE2](https://bsd-hardware.info/?probe=975e9ccbe2) |
| ASUSTek    | K55--44        | 49.5  |         | 1     | [4A0982DB2B](https://bsd-hardware.info/?probe=4a0982db2b) |
| ASUSTek    | K72--52        | 72.6  |         | 1     | [B36FF0B052](https://bsd-hardware.info/?probe=b36ff0b052) |
| ASUSTek    | M70--26        | 78.0  |         | 1     | [A2EE0C9EDB](https://bsd-hardware.info/?probe=a2ee0c9edb) |
| ASUSTek    | N55--52        | 57.2  |         | 1     | [7EFB6557A2](https://bsd-hardware.info/?probe=7efb6557a2) |
| ASUSTek    | N56--51        | 56.1  |         | 1     | [9FB23E0394](https://bsd-hardware.info/?probe=9fb23e0394) |
| ASUSTek    | N56--52        | 48.8  |         | 1     | [F53B3FBA5C](https://bsd-hardware.info/?probe=f53b3fba5c) |
| ASUSTek    | S551-45        | 50.7  |         | 1     | [42792115E3](https://bsd-hardware.info/?probe=42792115e3) |
| ASUSTek    | TP50042        | 48.3  |         | 1     | [6501322932](https://bsd-hardware.info/?probe=6501322932) |
| ASUSTek    | U31-58         | 81.2  |         | 1     | [A07366611D](https://bsd-hardware.info/?probe=a07366611d) |
| ASUSTek    | UL50-22        | 72.8  |         | 1     | [07F11B6604](https://bsd-hardware.info/?probe=07f11b6604) |
| ASUSTek    | UX21-48        | 35.5  |         | 1     | [FE08D28D4C](https://bsd-hardware.info/?probe=fe08d28d4c) |
| ASUSTek    | UX3-44         | 50.1  |         | 1     | [E9D8F7DE51](https://bsd-hardware.info/?probe=e9d8f7de51) |
| ASUSTek    | X402--38       | 38.0  |         | 1     | [1A2DF26F19](https://bsd-hardware.info/?probe=1a2df26f19) |
| ASUSTek    | X403 LIon      | 72.7  |         | 1     | [902B4298D4](https://bsd-hardware.info/?probe=902b4298d4) |
| ASUSTek    | X453-42        | 29.4  |         | 1     | [CFC7D86B5A](https://bsd-hardware.info/?probe=cfc7d86b5a) |
| ASUSTek    | X502--38       | 38.0  |         | 1     | [45F61AB19E](https://bsd-hardware.info/?probe=45f61ab19e) |
| ASUSTek    | X540-30        | 33.2  |         | 1     | [C5751C736C](https://bsd-hardware.info/?probe=c5751c736c) |
| ASUSTek    | X550A26        | 32.2  |         | 1     | [26AEF04E22](https://bsd-hardware.info/?probe=26aef04e22) |
| ASUSTek    | X550A30        | 44.2  |         | 1     | [E056F1C77C](https://bsd-hardware.info/?probe=e056f1c77c) |
| ASUSTek    | X550E26        | 37.4  |         | 1     | [A88CFD7FDD](https://bsd-hardware.info/?probe=a88cfd7fdd) |
| ASUSTek    | X555-50        | 37.3  |         | 1     | [74D43CCD10](https://bsd-hardware.info/?probe=74d43ccd10) |
| ASUSTek    | Z943222        | 47.3  |         | 1     | [83106A58EF](https://bsd-hardware.info/?probe=83106a58ef) |
| BYD        | DELL 1VX1H0... | 42.0  |         | 1     | [ED41C18CFC](https://bsd-hardware.info/?probe=ed41c18cfc) |
| BYD        | DELL 7FHHV8... | 56.0  |         | 1     | [91C803FDF2](https://bsd-hardware.info/?probe=91c803fdf2) |
| BYD        | DELL DVG8M1... | 54.9  |         | 1     | [91750755E4](https://bsd-hardware.info/?probe=91750755e4) |
| BYD        | DELL FP86V0... | 51.0  |         | 1     | [7C1EFA11B9](https://bsd-hardware.info/?probe=7c1efa11b9) |
| BYD        | DELL GHXKY8... | 64.0  |         | 1     | [6A2635237F](https://bsd-hardware.info/?probe=6a2635237f) |
| BYD        | DELL GW0K90... | 97.0  |         | 1     | [AA891D8F27](https://bsd-hardware.info/?probe=aa891d8f27) |
| BYD        | DELL K3JK90... | 62.0  |         | 1     | [12EAE7A62E](https://bsd-hardware.info/?probe=12eae7a62e) |
| BYD        | DELL K3JK97... | 62.0  |         | 1     | [9E479E9C50](https://bsd-hardware.info/?probe=9e479e9c50) |
| BYD        | DELL KG7VF8... | 60.0  |         | 1     | [2AD87768AF](https://bsd-hardware.info/?probe=2ad87768af) |
| BYD        | DELL M4GWP0... | 51.0  |         | 1     | [97319295EE](https://bsd-hardware.info/?probe=97319295ee) |
| BYD        | DELL M59JH0... | 86.0  |         | 1     | [A1C2EAEE5F](https://bsd-hardware.info/?probe=a1c2eaee5f) |
| BYD        | DELL MJMVV0... | 28.0  |         | 1     | [909AB22D27](https://bsd-hardware.info/?probe=909ab22d27) |
| BYD        | DELL PG8YJ1... | 41.0  |         | 1     | [F1796D75ED](https://bsd-hardware.info/?probe=f1796d75ed) |
| BYD        | DELL TMFYT8... | 75.0  |         | 1     | [E7925AA387](https://bsd-hardware.info/?probe=e7925aa387) |
| BYD        | DELL TXD030... | 53.0  |         | 1     | [80D7BF959A](https://bsd-hardware.info/?probe=80d7bf959a) |
| BYD        | DELL XX3T79... | 50.0  |         | 1     | [CC8C604FA6](https://bsd-hardware.info/?probe=cc8c604fa6) |
| Celxpert   | 01AV466 LiP    | 45.7  |         | 1     | [038FBABFE8](https://bsd-hardware.info/?probe=038fbabfe8) |

