DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 15939.

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
| Intel      | Core i5-3570 CPU                 |      | 682   | [5B088318CCA6](<Desktop/Others/Others/Others/5B088318CCA6>) |
| Intel      | Celeron N5095                    | 2.00 | 541   | [C6AB3DE49B70](<Desktop/Techvision/TVI7309/TVI7309X/C6AB3DE49B70>) |
| Intel      | Celeron J4125                    | 2.00 | 426   | [BCF676A737B9](<Desktop/Yanling/YL-GML4/YL-GML4 V1/BCF676A737B9>) |
| AMD        | GX-412TC SOC                     |      | 352   | [298F3BCFED28](<Desktop/PC Engines/APU/APU2/298F3BCFED28>) |
| Intel      | Celeron J3160                    | 1.60 | 222   | [83BFF061B508](<Desktop/Protectli/FW4/FW4B/83BFF061B508>) |
| Intel      | Core i5-6500                     | 3.20 | 161   | [6BF14C3EEA92](<Desktop/Dell/OptiPlex/OptiPlex 5050/6BF14C3EEA92>) |
| Intel      | 11th Gen Core i7-1165G7          | 2.80 | 159   | [A507B33A2599](<Notebook/Acer/Aspire/Aspire A514-54/A507B33A2599>) |
| Intel      | Celeron J1900                    | 1.99 | 142   | [791DD65A631D](<Mini Pc/AMI/Aptio/Aptio CRB/791DD65A631D>) |
| Intel      | Celeron J6412                    | 2.00 | 130   | [1922775E4B35](<Desktop/Protectli/VP/VP2420/1922775E4B35>) |
| Intel      | Core i5-7200U                    | 2.50 | 125   | [05A9A7C0C984](<Desktop/Protectli/FW/FW6/05A9A7C0C984>) |
| Intel      | Core i5-3470                     | 3.20 | 112   | [4D6634DEA948](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/4D6634DEA948>) |
| Intel      | Celeron J1900                    | 1.99 | 111   | [BECB1849DED7](<Desktop/NF533MS/1/1.0/BECB1849DED7>) |
| Intel      | Core 2 Duo                       |      | 97    | [4536BD9030FB](<Desktop/Dell/OptiPlex/OptiPlex XE/4536BD9030FB>) |
| Intel      | Core i5-8250U                    | 1.60 | 93    | [2C2262582E5F](<Desktop/Protectli/FW/FW6/2C2262582E5F>) |
| AMD        | GX-415GA SOC with Radeon HD G... |      | 90    | [9340AB326342](<Desktop/Fujitsu/FUTRO/FUTRO S920/9340AB326342>) |
| Intel      | Core i5-4590                     | 3.30 | 88    | [D809ED94D574](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/D809ED94D574>) |
| Intel      | Core i5-4570                     | 3.20 | 87    | [411C647054B3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/411C647054B3>) |
| Intel      | Celeron J3455                    | 1.50 | 85    | [1D33BC023AEE](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/1D33BC023AEE>) |
| Intel      | Atom C3558                       | 2.20 | 85    | [7AE23EBB7F42](<Firewall/Sophos/XG/XG/7AE23EBB7F42>) |
| Intel      | Core i3-N305                     |      | 82    | [FAB51E93E08F](<Desktop/CWWK/CW-ADLN-6/CW-ADLN-6L/FAB51E93E08F>) |
| Intel      | Celeron N3450                    | 1.10 | 82    | [C9BB3F2E7142](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/C9BB3F2E7142>) |
| AMD        | GX-420CA SOC with Radeon HD G... |      | 80    | [B7519A452CC8](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/B7519A452CC8>) |
| AMD        | RX-427BB with AMD Radeon R7 G... |      | 80    | [A32A2114410D](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/A32A2114410D>) |
| Intel      | Pentium Silver J5005             | 1.50 | 79    | [092F978DF489](<Desktop/Tarox/ECO/ECO 60-1/092F978DF489>) |
| Intel      | Core i5-2520M                    | 2.50 | 78    | [227676215FBC](<Notebook/Dell/Latitude/Latitude E5520/227676215FBC>) |
| Intel      | Celeron J4105                    | 1.50 | 77    | [ABEA02A7130C](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 SD-BS-CJ41G-300-101-K 05-20-2022 17:09:09/ABEA02A7130C>) |
| Intel      | Core i7-8550U                    | 1.80 | 74    | [172EB0F90B6B](<Notebook/Dell/Inspiron/Inspiron 3476/172EB0F90B6B>) |
| Intel      | Core i5-2400                     | 3.10 | 74    | [1E7AADCED672](<Desktop/Intel/B75/B75 V1.5/1E7AADCED672>) |
| Intel      | 12th Gen Core i3-1220P           |      | 73    | [083DD1D4B843](<Desktop/CWWK/CW-MBX-AD/CW-MBX-AD12/083DD1D4B843>) |
| Intel      | Core i7-3770                     | 3.40 | 73    | [3C9F9755E7AF](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/3C9F9755E7AF>) |
| Intel      | Atom D525                        | 1.80 | 72    | [ACEE12AFED7C](<Desktop/Others/Others/Others/ACEE12AFED7C>) |
| Intel      | Core i3-6100                     | 3.70 | 67    | [E2BB5D4C13D5](<Firewall/Sophos/SG/SG/E2BB5D4C13D5>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 63    | [8824A77888E6](<Desktop/ASRock/B550/B550 PG Riptide/8824A77888E6>) |
| Intel      | Core i7-7500U                    | 2.70 | 62    | [2E1E572B93F6](<Desktop/Others/Others/Others/2E1E572B93F6>) |
| Intel      | Core i5-5200U                    | 2.20 | 62    | [00393957E031](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G2/00393957E031>) |
| Intel      | Celeron N3150                    | 1.60 | 62    | [AF4D4B697A5A](<Mini Pc/AMI/Aptio/Aptio CRB/AF4D4B697A5A>) |
| Intel      | Core i7-6700                     | 3.40 | 62    | [C344E2F23032](<Desktop/Lenovo/ThinkCentre/ThinkCentre M910s 10MK000TUS/C344E2F23032>) |
| Intel      | 12th Gen Core i5-12450H          |      | 61    | [8C6FBD7DA83F](<Desktop/Micro Computer (HK) Tech Limited/Venus/Venus Series/8C6FBD7DA83F>) |
| Intel      | Pentium N3700                    | 1.60 | 61    | [470D286AF79E](<Mini Pc/AMI/Aptio/Aptio CRB/470D286AF79E>) |
| AMD        | Ryzen Embedded V1500B            |      | 60    | [C04E393AA347](<Notebook/Deciso/NetBoard-A/NetBoard-A10/C04E393AA347>) |
| AMD        | EPYC 3201 8-Core                 |      | 59    | [A6303D5D03E7](<Notebook/Deciso/Netboard/Netboard A20/A6303D5D03E7>) |
| Intel      | Core i3-7100U                    | 2.40 | 59    | [4AAC7657BB80](<Desktop/Protectli/FW/FW6/4AAC7657BB80>) |
| Intel      | Core i5-10210U                   | 1.60 | 58    | [979107FD74EF](<Desktop/Others/QCML/QCML02/979107FD74EF>) |
| Intel      | Core i5-6500T                    | 2.50 | 58    | [C7CE62E20239](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/C7CE62E20239>) |
| Intel      | Core i5-8500T                    | 2.10 | 57    | [8443A789142D](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0LN00/8443A789142D>) |
| Intel      | Core i5-6300U                    | 2.40 | 57    | [DB76283F4C94](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/DB76283F4C94>) |
| Intel      | Atom E3930                       | 1.30 | 57    | [9043AF911ACC](<Desktop/Supermicro/SYS-E50/SYS-E50-9AP-WIFI/9043AF911ACC>) |
| Intel      | Core i5-7500                     | 3.40 | 56    | [188C552DDBCA](<Desktop/Intel/SKYBAY/SKYBAY/188C552DDBCA>) |
| Intel      | Core i5-3320M                    | 2.60 | 56    | [7B50C1C06629](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2392AQU/7B50C1C06629>) |
| Intel      | Celeron N3160                    | 1.60 | 55    | [574869791328](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/574869791328>) |
| Intel      | Pentium Gold G7400               |      | 54    | [6CC06CC88050](<Desktop/Hewlett-Packard/Pro/Pro SFF 400 G9 Desktop PC/6CC06CC88050>) |
| Intel      | Atom E3845                       | 1.91 | 54    | [8ADEC04D007D](<Desktop/Others/PICO/PICO PC/8ADEC04D007D>) |
| Intel      | Core i5-5300U                    | 2.30 | 54    | [876EE2BA23D5](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS14400/876EE2BA23D5>) |
| Intel      | Celeron 3865U                    | 1.80 | 51    | [F512CCD351F8](<Desktop/Others/YL-SKUL6-7/YL-SKUL6-7 Series/F512CCD351F8>) |
| Intel      | Core i5-8500                     | 3.00 | 51    | [C6ADB9C2B501](<Desktop/Dell/OptiPlex/OptiPlex 3060/C6ADB9C2B501>) |
| Intel      | Core i7-7700                     | 3.60 | 51    | [03E8F0C5DFD4](<Desktop/Seneca/pro/pro758577/03E8F0C5DFD4>) |
| Intel      | Atom C2558                       | 2.40 | 50    | [A6B12F942AE3](<Firewall/Sophos/SG/SG/A6B12F942AE3>) |
| Intel      | Core i5-6200U                    | 2.30 | 50    | [C14747EBBA5F](<Desktop/Others/Others/Others/C14747EBBA5F>) |
| AMD        | G-T40E                           |      | 47    | [5EFDB84B2ED9](<Desktop/PC Engines/APU/APU/5EFDB84B2ED9>) |
| Intel      | Core i7-4770                     | 3.40 | 47    | [0B80A0FC07C8](<Desktop/ASUSTek Computer/All/All Series/0B80A0FC07C8>) |
| Intel      | Xeon D-1518                      | 2.20 | 44    | [AFA8BDAED78C](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/AFA8BDAED78C>) |
| AMD        | GX-222GC SOC with Radeon R5E ... |      | 43    | [2DD8ADC1BA9C](<Desktop/Fujitsu/FUTRO/FUTRO S920/2DD8ADC1BA9C>) |
| Intel      | Xeon E3-1220 v3                  | 3.10 | 42    | [8EAAF5840300](<Server/Dell/PowerEdge/PowerEdge R220/8EAAF5840300>) |
| Intel      | Pentium J3710                    | 1.60 | 42    | [DD1A0E9587EB](<Desktop/Protectli/FW4/FW4C/DD1A0E9587EB>) |
| Intel      | 11th Gen Core i5-11400           | 2.60 | 41    | [A4B67C4F3183](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS WIFI/A4B67C4F3183>) |
| Intel      | Atom C3758R                      | 2.40 | 41    | [5EEBE7C04C87](<Desktop/Others/QDNV/QDNV01/5EEBE7C04C87>) |
| Intel      | Celeron N4100                    | 1.10 | 40    | [56190C3D1DD0](<Desktop/Others/Others/Others/56190C3D1DD0>) |
| Intel      | Core i3-4130                     | 3.40 | 40    | [9DB557D41A53](<Desktop/Gigabyte Technology/H81/H81M-S2PV/9DB557D41A53>) |
| Intel      | Celeron J3060                    | 1.60 | 40    | [62D01E0042E1](<Desktop/Protectli/FW2/FW2B/62D01E0042E1>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 39    | [0B1139A6F1F5](<Desktop/Gigabyte Technology/B450/B450 AORUS M/0B1139A6F1F5>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 39    | [6A2F5C29A9C7](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/6A2F5C29A9C7>) |
| Intel      | Core i7-8700                     | 3.20 | 39    | [6BDC7B8870F4](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T70046GE/6BDC7B8870F4>) |
| Intel      | Core i3-4160                     | 3.60 | 39    | [7942CFB9B709](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 TWR/7942CFB9B709>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 38    | [5A691685FFA7](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/5A691685FFA7>) |
| Intel      | Atom C2758                       | 2.40 | 38    | [FACB77970B4F](<Server/Supermicro/A1/A1SRM-2758F/FACB77970B4F>) |
| Intel      | Core i3-8100                     | 3.60 | 37    | [06DFE3481702](<Desktop/Dell/OptiPlex/OptiPlex 3060/06DFE3481702>) |
| Intel      | Core i3-3220                     | 3.30 | 37    | [990365CAA9B9](<Desktop/Intel/MAHOBAY/MAHOBAY/990365CAA9B9>) |
| Intel      | Core i7-4790                     | 3.60 | 37    | [A2907B62F846](<Desktop/Dell/OptiPlex/OptiPlex 9020/A2907B62F846>) |
| Intel      | Core i5-4210U                    | 1.70 | 37    | [06461F81F7E5](<Notebook/Dell/Latitude/Latitude E5440/06461F81F7E5>) |
| Intel      | Core 2 Duo                       |      | 36    | [5DA131C8EBCB](<Notebook/Dell/Studio/Studio 1535/5DA131C8EBCB>) |
| Intel      | Celeron 2955U                    | 1.40 | 36    | [EDC5787D326C](<Notebook/Others/Others/Others/EDC5787D326C>) |
| Intel      | Pentium G4400                    | 3.30 | 36    | [1F3BBD248640](<Firewall/Sophos/SG/SG/1F3BBD248640>) |
| Intel      | Atom C3758                       | 2.20 | 36    | [8C54A7A1A238](<Desktop/Others/QDNV/QDNV01/8C54A7A1A238>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 35    | [52D593AA2EDF](<Desktop/Gigabyte Technology/B450/B450 GAMING X/52D593AA2EDF>) |
| Intel      | Core i5-9500                     | 3.00 | 35    | [953934CE866D](<Desktop/Dell/OptiPlex/OptiPlex 5070/953934CE866D>) |
| Intel      | Core i5-3570                     | 3.40 | 35    | [E655728809C3](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/E655728809C3>) |
| Intel      | Atom C2358                       | 1.74 | 35    | [5C3C65DB486D](<Firewall/Sophos/XG/XG/5C3C65DB486D>) |
| Intel      | Core i7-10510U                   | 1.80 | 34    | [B86550AF98F9](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20R1CTO1WW/B86550AF98F9>) |
| Intel      | Core i5-7400                     | 3.00 | 34    | [2839BC04B431](<Desktop/Lenovo/ThinkCentre/ThinkCentre M710s 10M7000QUS/2839BC04B431>) |
| Intel      | Core i7-2600                     | 3.40 | 34    | [7CCE113E04BD](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/7CCE113E04BD>) |
| Intel      | Celeron J1800                    | 2.41 | 33    | [FE9DEAC75ABC](<Notebook/IGEL Technology/H830/H830C/FE9DEAC75ABC>) |
| Intel      | Core i5-4200U                    | 1.60 | 33    | [081CEAC5CC7C](<Notebook/Dell/Inspiron/Inspiron 5737/081CEAC5CC7C>) |
| Intel      | Core i5-6400                     | 2.70 | 33    | [B5176543A12F](<Desktop/Dell/Inspiron/Inspiron 3650/B5176543A12F>) |
| Intel      | Core i5-7300U                    | 2.60 | 32    | [270A05DC1CA3](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L8S7T301/270A05DC1CA3>) |
| Intel      | 12th Gen Core i9-12900K          |      | 32    | [F52546B77C9F](<Desktop/Gigabyte Technology/Z690/Z690 AORUS ULTRA/F52546B77C9F>) |
| Intel      | Xeon E3-1220 V2                  | 3.10 | 32    | [960904C931E3](<Server/Dell/PowerEdge/PowerEdge R210 II/960904C931E3>) |
| Intel      | Xeon E3-1270 v3                  | 3.50 | 32    | [3C786505AF3D](<Server/Arbyte Computers/Silex/Silex T115 G2/3C786505AF3D>) |
| Intel      | Core i5-5250U                    | 1.60 | 32    | [93283B42A29D](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-502/93283B42A29D>) |
| Intel      | Core i5-8365U                    | 1.60 | 31    | [C95E82575E70](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S61A13/C95E82575E70>) |
| Intel      | Atom N450                        | 1.66 | 31    | [67BAA3F19D5C](<Firewall/Sophos/UTM/UTM/67BAA3F19D5C>) |
| Intel      | Xeon X3430                       | 2.40 | 31    | [9095994E2A14](<Server/Dell/PowerEdge/PowerEdge R210/9095994E2A14>) |
| Intel      | Core i3-2120 @ 3.30GH            |      | 31    | [499CD7FF5143](<Desktop/Dell/OptiPlex/OptiPlex 790/499CD7FF5143>) |
| Intel      | Xeon E31220                      | 3.10 | 31    | [D8729BF1B415](<Server/Dell/PowerEdge/PowerEdge R210 II/D8729BF1B415>) |
| Intel      | Core i3-4010U                    | 1.70 | 31    | [5626462FDA5E](<Desktop/Intel/D34010WYK/D34010WYK H14771-303/5626462FDA5E>) |
| Intel      | Core i3-10100                    | 3.60 | 30    | [C6A2FA6B6854](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-E/C6A2FA6B6854>) |
| Intel      | 13th Gen Core i7-13700K          |      | 30    | [249D6DBBBCD1](<Desktop/Gigabyte Technology/Z790/Z790 AORUS MASTER X/249D6DBBBCD1>) |
| Intel      | Core i3-2100 @ 3.10GH            |      | 30    | [4DBBE1BD2BDD](<Desktop/Lenovo/ThinkStation/ThinkStation E30 7783RR8/4DBBE1BD2BDD>) |
| Intel      | Core i5-4590T                    | 2.00 | 30    | [094D5DEC994C](<Desktop/Lenovo/SHARKBAY/SHARKBAY SDK0E50510 WIN/094D5DEC994C>) |
| Intel      | Core i3-5005U                    | 2.00 | 30    | [FE8B6FA10038](<Notebook/Dell/Inspiron/Inspiron 3458/FE8B6FA10038>) |
| Intel      | Xeon D-2123IT                    | 2.20 | 30    | [291CAD28A9A2](<Desktop/Supermicro/SYS-5019/SYS-5019D-4C-FN8TP/291CAD28A9A2>) |
| Intel      | Core i3-8100T                    | 3.10 | 29    | [550BDB2994BE](<Desktop/Gigabyte Technology/H110/H110MSTX-HD3/550BDB2994BE>) |
| Intel      | 13th Gen Core i5-13500H          |      | 29    | [C5604EC02E55](<Notebook/Lenovo/ThinkBook/ThinkBook 14 G6 IRL 21KG/C5604EC02E55>) |
| Intel      | Core i3-4005U                    | 1.70 | 29    | [B5F092FF9D00](<Notebook/Hewlett-Packard/250/250 G3/B5F092FF9D00>) |
| Intel      | Core 2 Quad CPU                  |      | 28    | [A17E98339FDE](<Desktop/Dell/OptiPlex/OptiPlex 780/A17E98339FDE>) |
| Intel      | Core i3-7100                     | 3.90 | 28    | [5A953B1C086E](<Desktop/Dell/Inspiron/Inspiron 3268/5A953B1C086E>) |
| Intel      | Celeron 1037U                    | 1.80 | 28    | [0D560AE65281](<Notebook/Others/Others/Others/0D560AE65281>) |
| Intel      | Pentium G3420                    | 3.20 | 28    | [3518481CC1FD](<Firewall/Sophos/SG/SG/3518481CC1FD>) |
| Intel      | Core i5-8400T                    | 1.70 | 27    | [97F96F1C6E47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7002CUS/97F96F1C6E47>) |
| Intel      | Core i5-10400                    | 2.90 | 27    | [F5CD7FAF4149](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F5CD7FAF4149>) |
| Intel      | CPU Version                      |      | 27    | [E467C8D41683](<Desktop/Dell/OptiPlex/OptiPlex 760/E467C8D41683>) |
| Intel      | Xeon E5620                       | 2.40 | 27    | [84BDFD822076](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c G7/84BDFD822076>) |
| Intel      | Core i3-3240                     | 3.40 | 27    | [64F45715CE8B](<Desktop/Digital Defense/Defense/Defense Appliance/64F45715CE8B>) |
| Intel      | Core i5-6600                     | 3.30 | 27    | [093325A429D4](<Desktop/Dell/OptiPlex/OptiPlex 5050/093325A429D4>) |
| Intel      | Core i5-8350U                    | 1.70 | 26    | [7E111470199B](<Notebook/Dell/Latitude/Latitude 7390/7E111470199B>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 26    | [777151F0CD36](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/777151F0CD36>) |
| Intel      | Core i5-2500 @ 3.30GH            |      | 26    | [6B6884BC4BC9](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/6B6884BC4BC9>) |
| Intel      | Core i3-4150                     | 3.50 | 26    | [F278CD3C9EB3](<Desktop/Dell/OptiPlex/OptiPlex 7020/F278CD3C9EB3>) |
| Intel      | Core i7-6600U                    | 2.60 | 26    | [C9FF146E15AC](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/C9FF146E15AC>) |
| Intel      | Celeron G3900                    | 2.80 | 26    | [CE0869FCF468](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-A/CE0869FCF468>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 25    | [71C3039673A5](<Desktop/Gigabyte Technology/A320/A320M-S2H/71C3039673A5>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 25    | [E48968775D12](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E48968775D12>) |
| Intel      | Core i5-3210M                    | 2.50 | 25    | [6864C7245AE0](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK LH532/6864C7245AE0>) |
| Intel      | Core i7-3520M                    | 2.90 | 25    | [6E92680FFC7C](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2344BPU/6E92680FFC7C>) |
| Intel      | Xeon E3-1230 V2                  | 3.30 | 25    | [840BA46D757A](<Desktop/Lenovo/ThinkStation/ThinkStation E31 255547U/840BA46D757A>) |
| Intel      | Xeon E5-2650 v2                  | 2.60 | 25    | [FB4F503A548B](<Server/Dell/OEM-R/OEM-R 720xd/FB4F503A548B>) |
| Intel      | Core i5-4300U                    | 1.90 | 25    | [CCDD877687EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/CCDD877687EF>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 24    | [78D2A736577D](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7CTO1WW/78D2A736577D>) |
| Intel      | Celeron J4115                    | 1.80 | 24    | [888F1D595D01](<Desktop/Hardkernel/ODROID-H/ODROID-H2/888F1D595D01>) |
| Intel      | Core i5-8400                     | 2.80 | 24    | [2DF499195648](<Desktop/ASRock/Z370M/Z370M Pro4/2DF499195648>) |
| Intel      | Celeron N2840                    | 2.16 | 24    | [BF6F66287842](<Desktop/OEM/PB-1900/PB-1900-A/BF6F66287842>) |
| Intel      | Core i5-4460                     | 3.20 | 24    | [A36BE47555F3](<Desktop/Gigabyte Technology/H81/H81M-HD2/A36BE47555F3>) |
| Intel      | Core i5-4570T                    | 2.90 | 24    | [A67A14BFDAB3](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAS2A100/A67A14BFDAB3>) |
| Intel      | Core i3-4030U                    | 1.90 | 24    | [393D348F4FFF](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/393D348F4FFF>) |
| Intel      | Celeron N3350                    | 1.10 | 24    | [43646C128B3E](<Desktop/AAEON/UP-APL/UP-APL01/43646C128B3E>) |
| AMD        | GX-424CC SOC with Radeon R5E ... |      | 23    | [F6A9C8CC3802](<Desktop/Fujitsu/FUTRO/FUTRO S930/F6A9C8CC3802>) |
| AMD        | FX-6300 Six-Core                 |      | 23    | [6BC0BC80DADF](<Desktop/MSI/MS/MS-7699/6BC0BC80DADF>) |
| AMD        | FX-8350 Eight-Core               |      | 23    | [C676AD8F2DCD](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX/C676AD8F2DCD>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 23    | [189D05B00FD4](<Desktop/Gigabyte Technology/B450M/B450M DS3H/189D05B00FD4>) |
| Intel      | Core i7-8650U                    | 1.90 | 23    | [3518312BB794](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S29D1V/3518312BB794>) |
| Intel      | Celeron N2940                    | 1.83 | 23    | [775D7156D090](<Mini Pc/AMI/Aptio/Aptio CRB/775D7156D090>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 22    | [721988A29B56](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/721988A29B56>) |
| Intel      | Celeron N2930                    | 1.83 | 22    | [B3E85E38A1FA](<Desktop/Others/Others/Others/B3E85E38A1FA>) |
| Intel      | Celeron G1820                    | 2.70 | 22    | [EEABA873E8BE](<Desktop/CheckPoint/PB-15/PB-15-00/EEABA873E8BE>) |
| Intel      | Xeon E3-1225 v3                  | 3.20 | 22    | [79198451BEE2](<Firewall/Sophos/SG/SG/79198451BEE2>) |
| Intel      | Core i3-6006U                    | 2.00 | 22    | [2D23F1BDB2E3](<Notebook/Lenovo/IdeaPad/IdeaPad 320-14IKB 80YF/2D23F1BDB2E3>) |
| AMD        | EPYC 3251 8-Core                 |      | 21    | [5B4B645508B1](<Server/Supermicro/Super/Super Server/5B4B645508B1>) |
| Intel      | Core i7-8750H                    | 2.20 | 21    | [9F09F6EF7AF2](<Notebook/Gigabyte Technology/AERO/AERO 15WV8/9F09F6EF7AF2>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 21    | [E58D0587DEA6](<Desktop/Intel/DG45ID/DG45ID AAE27729-307/E58D0587DEA6>) |
| Intel      | Core i7-5500U                    | 2.40 | 21    | [1972229C2148](<Notebook/ASUSTek Computer/X555/X555LB/1972229C2148>) |
| Intel      | Celeron N3050                    | 1.60 | 21    | [A7C1D61DCA70](<Desktop/Gigabyte Technology/N3050/N3050ND3H/A7C1D61DCA70>) |
| Intel      | Pentium N3710                    | 1.60 | 21    | [2F5922F5B08F](<Notebook/Seco/UDOO/UDOO x86/2F5922F5B08F>) |
| Intel      | Atom C3508                       | 1.60 | 21    | [3E73C01CF7DD](<Firewall/Sophos/XG/XG/3E73C01CF7DD>) |
| AMD        | EPYC 3101 4-Core                 |      | 20    | [2190829AF96C](<Notebook/Deciso/Netboard/Netboard A20/2190829AF96C>) |
| AMD        | Athlon 3000G with Radeon Vega... |      | 20    | [584E6A023C13](<Desktop/MSI/MS-7/MS-7B89/584E6A023C13>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 20    | [E9BBBCF20ACB](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IU_FX506IU/E9BBBCF20ACB>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 20    | [D58789922AA5](<Desktop/Gigabyte Technology/B550/B550 GAMING X V2/D58789922AA5>) |
| AMD        | Ryzen 7 5825U with Radeon Gra... |      | 20    | [C9FA99041D6A](<Notebook/Infinix/YL51/YL51A5/C9FA99041D6A>) |
| Intel      | Pentium G4560                    | 3.50 | 20    | [F487BB81A2FD](<Desktop/MSI/MS-7/MS-7A15/F487BB81A2FD>) |
| Intel      | Atom E3827                       | 1.74 | 20    | [59447D09AC57](<Mini Pc/Sophos/SG/SG/59447D09AC57>) |
| Intel      | Core i3-4330                     | 3.50 | 20    | [1EA109DBEF4C](<Firewall/Sophos/SG/SG/1EA109DBEF4C>) |
| Intel      | Core i3-5010U                    | 2.10 | 20    | [463035F97B90](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLA455CD/463035F97B90>) |
| Intel      | Core i7-4600U                    | 2.10 | 20    | [F2953127C3B7](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/F2953127C3B7>) |
| Intel      | Core i7-6500U                    | 2.50 | 20    | [35A7C406512F](<Notebook/Dell/Inspiron/Inspiron 5559/35A7C406512F>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 19    | [2AC65064750C](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K-BR/2AC65064750C>) |
| Intel      | 11th Gen Core i7-11800H          | 2.30 | 19    | [4A0A2736C7E2](<Notebook/Alienware/m15/m15 R6/4A0A2736C7E2>) |
| Intel      | Core 2 CPU                       |      | 19    | [5BE297D9EF83](<Desktop/Supermicro/X7/X7DBU/5BE297D9EF83>) |
| Intel      | Core i7-7700K                    | 4.20 | 19    | [022647FB956A](<Desktop/MSI/MS-7/MS-7A69/022647FB956A>) |
| Intel      | Core i7-10750H                   | 2.60 | 19    | [B293808AAB50](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15IMH05 81Y4/B293808AAB50>) |
| Intel      | Core i5-2540M                    | 2.60 | 19    | [076CB5136E42](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 417153U/076CB5136E42>) |
| Intel      | Core i7-3770K                    | 3.50 | 19    | [FEE7ABA2F6FE](<Desktop/ASUSTek Computer/Maximus/Maximus V FORMULA/FEE7ABA2F6FE>) |
| Intel      | Core i5-4570S                    | 2.90 | 19    | [708653C4FADC](<Desktop/Dell/OptiPlex/OptiPlex 3020/708653C4FADC>) |
| Intel      | Pentium G3220                    | 3.00 | 19    | [D510A20C35C7](<Desktop/MSI/MS/MS-7817/D510A20C35C7>) |
| Intel      | Core i5-4250U                    | 1.30 | 19    | [D40D4FF13EC2](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/D40D4FF13EC2>) |
| Intel      | Xeon E3-1225 v5                  | 3.30 | 19    | [ADCC6FE7AC5D](<Desktop/Hewlett-Packard/Z240/Z240 Tower Workstation/ADCC6FE7AC5D>) |
| AMD        | GX-420MC SOC                     |      | 18    | [A318E154E42C](<Desktop/Deciso/Netboard/Netboard A8/A318E154E42C>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 18    | [3EA73278F4B4](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/3EA73278F4B4>) |
| Intel      | Celeron N4000                    | 1.10 | 18    | [1CA53BDCBE1F](<Notebook/Samsung Electronics/530/530XBB/1CA53BDCBE1F>) |
| Intel      | Core i7-8565U                    | 1.80 | 18    | [AA19B2B50853](<Mini Pc/Intel Client Systems/CM8/CM8I7CB8N/AA19B2B50853>) |
| Intel      | Core i7-9750H                    | 2.60 | 18    | [3D1A48FB0BE4](<Notebook/Lenovo/ThinkPad/ThinkPad P73 20QRCTO1WW/3D1A48FB0BE4>) |
| Intel      | Core i3-9100                     | 3.60 | 18    | [E5EE048DB0DB](<Desktop/Dell/OptiPlex/OptiPlex 5070/E5EE048DB0DB>) |
| Intel      | Core i5-7500T                    | 2.70 | 18    | [C082D07F0153](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR006XUS/C082D07F0153>) |
| Intel      | Core i5-3230M                    | 2.60 | 18    | [BA40DAA623AD](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2342CTO/BA40DAA623AD>) |
| Intel      | Core i3-4170                     | 3.70 | 18    | [0A8D2BAA3BC6](<Desktop/MSI/MS/MS-7851/0A8D2BAA3BC6>) |
| Intel      | Core i3-6100T                    | 3.20 | 18    | [A052B356AB16](<Desktop/Dell/OptiPlex/OptiPlex 7040/A052B356AB16>) |
| Intel      | Core i7-6700K                    | 4.00 | 18    | [CB499DAAD104](<Desktop/ASUSTek Computer/Z170/Z170 PRO GAMING/CB499DAAD104>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 17    | [6344ED7EF1F3](<Notebook/MSI/Modern/Modern 15 A5M/6344ED7EF1F3>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 17    | [2B92B5D7C148](<Mini Pc/AZW/SER/SER/2B92B5D7C148>) |
| Intel      | Core i3-1005G1                   | 1.20 | 17    | [116441499573](<Desktop/BESSTAR Tech/X/X35G/116441499573>) |
| Intel      | Core i3-10110U                   | 2.10 | 17    | [F75BDEE7C380](<Notebook/Notebook/NL40/NL40_50CU/F75BDEE7C380>) |
| Intel      | Core i5-2400S                    | 2.50 | 17    | [6DECBE7232EA](<Desktop/Dell/OptiPlex/OptiPlex 990/6DECBE7232EA>) |
| Intel      | Xeon E5645                       | 2.40 | 17    | [5F38A9E69360](<Server/Dell/PowerEdge/PowerEdge T710/5F38A9E69360>) |
| Intel      | Xeon X5650                       | 2.67 | 17    | [1D2F571EDBB2](<Desktop/Intel/Thurley/Thurley/1D2F571EDBB2>) |
| Intel      | Xeon E3-1225 V2                  | 3.20 | 17    | [5156E4E71E5B](<Desktop/Intel/S1200KP/S1200KP AAG34877-201/5156E4E71E5B>) |
| Intel      | Core i7-4790K                    | 4.00 | 17    | [B0A13E0905BC](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/B0A13E0905BC>) |
| Intel      | Core i3-6100U                    | 2.30 | 17    | [9798A4AC1CE8](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S1P100/9798A4AC1CE8>) |
| Intel      | Atom D2550                       | 1.86 | 17    | [21BF06410E7E](<Desktop/Quanmax/KEEX/KEEX-1660/21BF06410E7E>) |
| AMD        | GX-416RA SOC                     |      | 16    | [EE2111A74632](<Desktop/Deciso/Netboard/Netboard A10/EE2111A74632>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 16    | [5C7E06AB8947](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947>) |
| Intel      | Celeron N4020                    | 1.10 | 16    | [142CB8E360A2](<Desktop/Quantum engineering/HackBoard/HackBoard 2/142CB8E360A2>) |
| Intel      | Core i3-8130U                    | 2.20 | 16    | [277E90DECDB8](<Notebook/Notebook/N7/N7x0WU/277E90DECDB8>) |
| Intel      | Core i5-8265U                    | 1.60 | 16    | [D81E2CC4D6ED](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N9S48S00/D81E2CC4D6ED>) |
| Intel      | Pentium Gold G5400               | 3.70 | 16    | [2A0AB0754890](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-E R2.0/2A0AB0754890>) |
| Intel      | Core i7-10700                    | 2.90 | 16    | [D09DF3E176F6](<Desktop/Dell/OptiPlex/OptiPlex 7090/D09DF3E176F6>) |
| Intel      | Core i5-4590S                    | 3.00 | 16    | [1433EF696DC8](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/1433EF696DC8>) |
| Intel      | Core i7-5600U                    | 2.60 | 16    | [1E567F3F8EA2](<Notebook/Dell/Latitude/Latitude E7250/1E567F3F8EA2>) |
| Intel      | Xeon D-2146NT                    | 2.30 | 16    | [D63E9E5805F3](<Desktop/Supermicro/SYS-1019/SYS-1019D-FHN13TP/D63E9E5805F3>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 15    | [D99D56BFE2EE](<Notebook/TUXEDO/Aura/Aura 15 Gen1/D99D56BFE2EE>) |
| Intel      | Celeron J4005                    | 2.00 | 15    | [A8F3D6ECF0A3](<Desktop/ASUSTek Computer/PRIME/PRIME J4005I-C/A8F3D6ECF0A3>) |
| Intel      | Core i5-8265U                    | 1.60 | 15    | [8679CE3F618D](<Desktop/Others/Others/Others/8679CE3F618D>) |
| Intel      | Core i3-8145U                    | 2.10 | 15    | [CBA2A1C9FA7E](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/CBA2A1C9FA7E>) |
| Intel      | Core i7-8700T                    | 2.40 | 15    | [135DBB4F3AC1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SJ9900/135DBB4F3AC1>) |
| Intel      | Xeon E-2224                      | 3.40 | 15    | [4BE5147F2077](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/4BE5147F2077>) |
| Intel      | Core i3-10105                    | 3.70 | 15    | [C73EB2EAA4D9](<Desktop/Gigabyte Technology/B560M/B560M DS3H/C73EB2EAA4D9>) |
| Intel      | Celeron J1900                    | 1.99 | 15    | [C31CA5CEBF82](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82>) |
| Intel      | Core i3-3217U                    | 1.80 | 15    | [D137378D48DA](<Notebook/Samsung Electronics/530U3/530U3C-530U4C-532U3C/D137378D48DA>) |
| Intel      | Xeon E3-1220L V2                 | 2.30 | 15    | [24CA137F4D1D](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/24CA137F4D1D>) |
| Intel      | Core i7-5550U                    | 2.00 | 15    | [0F4DE190765B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0F4DE190765B>) |
| Intel      | Celeron N3060                    | 1.60 | 15    | [8ABEEDC83F3E](<Desktop/Gigabyte Technology/MZBSWIP-SI/MZBSWIP-SI/8ABEEDC83F3E>) |
| Intel      | Pentium N4200                    | 1.10 | 15    | [BD9328180E73](<Desktop/ASRock/IMB/IMB-157/BD9328180E73>) |
| Intel      | Xeon E3-1220 v5                  | 3.00 | 15    | [567B7E95080C](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/567B7E95080C>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 14    | [5803150B030B](<Desktop/ASRockRack/X470/X470D4U/5803150B030B>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 14    | [171D391A3B09](<Notebook/Lenovo/ThinkPad/ThinkPad E595 20NFCTO1WW/171D391A3B09>) |
| AMD        | Ryzen 5 4600G with Radeon Gra... |      | 14    | [5B8AD470F22A](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/5B8AD470F22A>) |
| Intel      | Core i7-8565U                    | 1.80 | 14    | [5C823D1C16BB](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2S0QE00/5C823D1C16BB>) |
| Intel      | Xeon E3-1220 v6                  | 3.00 | 14    | [5A39BB0BDC3A](<Server/Supermicro/Super/Super Server/5A39BB0BDC3A>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 14    | [F1C70CF9EA47](<Desktop/ASRock/G31/G31M-VS2/F1C70CF9EA47>) |
| Intel      | Atom E3826                       | 1.46 | 14    | [A85394C35939](<Mini Pc/Sophos/SG/SG/A85394C35939>) |
| Intel      | Celeron G1610T                   | 2.30 | 14    | [CCCC48E1B709](<Desktop/Columbus Micro/AIO/AIO 650/CCCC48E1B709>) |
| Intel      | Core i5-3570K                    | 3.40 | 14    | [E45C5EBC46A3](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/E45C5EBC46A3>) |
| Intel      | Xeon E3-1231 v3                  | 3.40 | 14    | [6AAC242150BC](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC>) |
| Intel      | Xeon E3-1246 v3                  | 3.50 | 14    | [A72A5E92109B](<Desktop/MSI/MS/MS-7823/A72A5E92109B>) |
| Intel      | Xeon E5-2620 v3                  | 2.40 | 14    | [0425700A5D7A](<Desktop/Supermicro/X10/X10DAi/0425700A5D7A>) |
| Intel      | Xeon E5-2630 v3                  | 2.40 | 14    | [3C6E0747C879](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 Gen9/3C6E0747C879>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 14    | [8F6CC5AF444D](<Notebook/ASUSTek Computer/GL752/GL752VW/8F6CC5AF444D>) |
| Intel      | Core i5 M 520                    | 2.40 | 14    | [AFE5A5E7EE61](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3626HMG/AFE5A5E7EE61>) |
| AMD        | GX-217GA SOC with Radeon HD G... |      | 13    | [051ECEDC5E0D](<Desktop/Fujitsu/FUTRO/FUTRO S720/051ECEDC5E0D>) |
| AMD        | Ryzen 7 3800X 8-Core             |      | 13    | [182E02185F7E](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/182E02185F7E>) |
| AMD        | Ryzen 5 5600H with Radeon Gra... |      | 13    | [08887551DE0D](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/08887551DE0D>) |
| Intel      | 11th Gen Core i7-1195G7          | 2.90 | 13    | [B8682FC1F33D](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-fq4xxx/B8682FC1F33D>) |
| Intel      | Core i7-9700                     | 3.00 | 13    | [901346ED1DB6](<Desktop/Others/Others/Others/901346ED1DB6>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
|            | 123456789012345678 DIMM L... | 2 GB     |      | 2133 | 225   | [ABEA02A7130C](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 SD-BS-CJ41G-300-101-K 05-20-2022 17:09:09/ABEA02A7130C>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 1333 | 200   | [298F3BCFED28](<Desktop/PC Engines/APU/APU2/298F3BCFED28>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 123   | [9340AB326342](<Desktop/Fujitsu/FUTRO/FUTRO S920/9340AB326342>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 120   | [FE8B6FA10038](<Notebook/Dell/Inspiron/Inspiron 3458/FE8B6FA10038>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 98    | [97F96F1C6E47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7002CUS/97F96F1C6E47>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 90    | [ED6331540CC6](<Desktop/Others/Others/Others/ED6331540CC6>) |
| Crucial    | CT16G48C40S5.M8A1 SODIMM     | 16 GB    | DDR5 | 4800 | 88    | [4F08019C0B58](<Desktop/Others/Others/Others/4F08019C0B58>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 80    | [DAE01F206530](<Notebook/Hewlett-Packard/2000/2000/DAE01F206530>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 77    | [D40D4FF13EC2](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/D40D4FF13EC2>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1600 | 71    | [62D01E0042E1](<Desktop/Protectli/FW2/FW2B/62D01E0042E1>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 70    | [6DECBE7232EA](<Desktop/Dell/OptiPlex/OptiPlex 990/6DECBE7232EA>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 69    | [5B7604B36E00](<Notebook/Lenovo/ThinkPad/ThinkPad X220 Tablet 4294CTO/5B7604B36E00>) |
| Crucial    | CT16G56C46S5.M8G1 SODIMM     | 16 GB    | DDR5 | 5600 | 67    | [DDF011EC6CA5](<Desktop/Others/Others/Others/DDF011EC6CA5>) |
| Samsung    | M425R1GB4BB0-CQKOL SODIMM    | 8 GB     | DDR5 | 4800 | 66    | [446B340214F7](<Notebook/Hewlett-Packard/OMEN/OMEN by Transcend Gaming Laptop 16-u0xxx/446B340214F7>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 64    | [67BAA3F19D5C](<Firewall/Sophos/UTM/UTM/67BAA3F19D5C>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 60    | [7EC6497CE797](<Desktop/Techvision/TVI7309/TVI7309X/7EC6497CE797>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 59    | [5C52545E635C](<Firewall/Sophos/UTM/UTM/5C52545E635C>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 55    | [5626462FDA5E](<Desktop/Intel/D34010WYK/D34010WYK H14771-303/5626462FDA5E>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2400 | 55    | [270A05DC1CA3](<Notebook/Lenovo/ThinkPad/ThinkPad T480s 20L8S7T301/270A05DC1CA3>) |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 2667 | 54    | [0EF0D2083CC5](<Desktop/Micro Computer (HK) Tech Limited/MT4/MT4UB1/0EF0D2083CC5>) |
| Transcend  | TS1GLH64V6BL SODIMM          | 8 GB     | DDR4 | 2667 | 53    | [C04E393AA347](<Notebook/Deciso/NetBoard-A/NetBoard-A10/C04E393AA347>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 52    | [FDE04DEC0E85](<Desktop/Gigabyte Technology/H97/H97M-HD3/FDE04DEC0E85>) |
|            | Module                       | 8 GB     |      | 1600 | 52    | [83BFF061B508](<Desktop/Protectli/FW4/FW4B/83BFF061B508>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 50    | [D686EDC3BBCE](<Desktop/Gigabyte Technology/M68/M68MT-S2/D686EDC3BBCE>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 49    | [97F96F1C6E47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7002CUS/97F96F1C6E47>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1867 | 49    | [265362033E58](<Notebook/Dell/Precision/Precision M2800/265362033E58>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 48    | [06461F81F7E5](<Notebook/Dell/Latitude/Latitude E5440/06461F81F7E5>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 48    | [D3DA0C0284E7](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/D3DA0C0284E7>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 47    | [3AF63952CC98](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/3AF63952CC98>) |
|            | Module(s) DIMM               | 4 GB     |      |      | 46    | [5C0556A6AFDF](<Desktop/ADI Engineering/RCC-VE/RCC-VE/5C0556A6AFDF>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 46    | [332BB6458825](<Desktop/Intel/SHARKBAY/SHARKBAY/332BB6458825>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2400 | 44    | [6C905BC6A168](<Notebook/Timi/TM/TM1703/6C905BC6A168>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 44    | [77799D4C2077](<Desktop/Dell/OptiPlex/OptiPlex 3050/77799D4C2077>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 43    | [2313F3E68915](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/2313F3E68915>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 43    | [0D9DDA1725D5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/0D9DDA1725D5>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 43    | [CADF62F49BBE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SBP100/CADF62F49BBE>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3200 | 42    | [C0A2DE23D858](<Desktop/ASUSTek Computer/Maximus/Maximus VIII RANGER/C0A2DE23D858>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 42    | [8D46EE05F6A4](<Notebook/Dell/Inspiron/Inspiron 3421/8D46EE05F6A4>) |
| Crucial    | CT8G48C40S5.M4A1 SODIMM      | 8 GB     | DDR5 | 4800 | 42    | [B3C0EDAF7B10](<Desktop/AZW/EQ/EQ/B3C0EDAF7B10>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 42    | [4761B154C878](<Desktop/ASUSTek Computer/All/All Series/4761B154C878>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 42    | [332BB6458825](<Desktop/Intel/SHARKBAY/SHARKBAY/332BB6458825>) |
| Kimtigo    | KT8GS3EDF SODIMM             | 8 GB     | DDR3 | 1600 | 41    | [0F4DE190765B](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0F4DE190765B>) |
|            | Module SODIMM                | 8 GB     | DDR3 | 1600 | 40    | [E6CECB6E29C9](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9>) |
| Micron     | 8ATF1G64HZ-3G2R1 SODIMM      | 8 GB     | DDR4 | 3200 | 39    | [05A9A7C0C984](<Desktop/Protectli/FW/FW6/05A9A7C0C984>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 39    | [1A2389C11321](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK U727/1A2389C11321>) |
| Samsung    | M471B1G73DB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 39    | [DD1A0E9587EB](<Desktop/Protectli/FW4/FW4C/DD1A0E9587EB>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 39    | [09495C62591E](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23255RG/09495C62591E>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 39    | [B4B6B27A4EEC](<Desktop/Others/Others/Others/B4B6B27A4EEC>) |
| Micron     | 8KTF51264HZ-1G9P1 SODIMM     | 4 GB     | DDR3 | 1867 | 38    | [828A2BA9D7BD](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/828A2BA9D7BD>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 37    | [081CEAC5CC7C](<Notebook/Dell/Inspiron/Inspiron 5737/081CEAC5CC7C>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 37    | [D655FBF97972](<Desktop/ASRock/HM55/HM55-MXM/D655FBF97972>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 667  | 37    | [F51C60C8DB04](<Desktop/PC Engines/APU/APU3/F51C60C8DB04>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 37    | [1BEFC499B247](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1BEFC499B247>) |
| Samsung    | M471B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 37    | [FBE9DAEBDEB0](<Desktop/Protectli/FW2/FW2B/FBE9DAEBDEB0>) |
| SK hynix   | HMT451U6BFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 36    | [D408B8C3AD1D](<Desktop/Dell/OptiPlex/OptiPlex 9020/D408B8C3AD1D>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1600 | 35    | [28C7D92419F0](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/28C7D92419F0>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 8 GB     | DDR3 | 1600 | 35    | [369A7E60305A](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2344DUC/369A7E60305A>) |
| Micron     | Module Row Of Chips LPDDR4   | 8 GB     |      | 3200 | 33    | [B2DD1B4F5D94](<Mini Pc/Universal Devices/eisy/eisy home next/B2DD1B4F5D94>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 33    | [50D622C2AE69](<Desktop/Supermicro/X7/X7SLA/50D622C2AE69>) |
| SK hynix   | HMT451U6BFR8A-PB DIMM        | 4 GB     | DDR3 | 1600 | 32    | [46E0E548D95D](<Desktop/Dell/OptiPlex/OptiPlex XE2/46E0E548D95D>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 31    | [3F34AD565132](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/3F34AD565132>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 31    | [B1EAE5C24DD5](<Desktop/Supermicro/C7/C7SIM-Q/B1EAE5C24DD5>) |
| Crucial    | CT102464BF160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 30    | [DD626DF56514](<Mini Pc/AMI/Aptio/Aptio CRB/DD626DF56514>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 30    | [7C1611E1F506](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SBD800/7C1611E1F506>) |
| Transcend  | TS1GLH64V6BL SODIMM          | 8 GB     | DDR4 | 2667 | 30    | [74C8FD805018](<Notebook/Deciso/NetBoard-A/NetBoard-A20/74C8FD805018>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 29    | [19BEAC158F0D](<Desktop/Fujitsu/FUTRO/FUTRO S920/19BEAC158F0D>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 29    | [9AC8F9D166D7](<Desktop/Gigabyte Technology/H55/H55M-UD2H/9AC8F9D166D7>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 29    | [0EE337AFB3DF](<Desktop/Others/Others/Others/0EE337AFB3DF>) |
| Samsung    | M471B1G73EB0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 29    | [CA7B7D69D01A](<Desktop/Protectli/FW4/FW4C/CA7B7D69D01A>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 28    | [D4182ED25A3F](<Desktop/Fujitsu/FUTRO/FUTRO S930/D4182ED25A3F>) |
| Samsung    | M393A2G40DB0-CPB DIMM        | 16 GB    | DDR4 | 2133 | 28    | [D63E9E5805F3](<Desktop/Supermicro/SYS-1019/SYS-1019D-FHN13TP/D63E9E5805F3>) |
| Corsair    | CMSX16GX5M1A4800C40 SODIMM   | 16 GB    | DDR5 | 4800 | 27    | [0AD064A4C2A3](<Desktop/Others/Others/Others/0AD064A4C2A3>) |
| Crucial    | CT102464BF160B.M16 DIMM      | 8 GB     | DDR3 | 1600 | 27    | [9B23FE481FFF](<Desktop/Protectli/FW4/FW4A/9B23FE481FFF>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 27    | [AE24C08B5E5A](<Desktop/Others/Others/Others/AE24C08B5E5A>) |
| Samsung    | M471B5173QH0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 27    | [574869791328](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/574869791328>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 27    | [DB76283F4C94](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/DB76283F4C94>) |
| SK hynix   | HMA81GU6AFR8N-UH DIMM        | 8 GB     | DDR4 | 2400 | 27    | [C344E2F23032](<Desktop/Lenovo/ThinkCentre/ThinkCentre M910s 10MK000TUS/C344E2F23032>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 800  | 26    | [F7B3CCE6B341](<Desktop/Supermicro/X7/X7SPA-H/F7B3CCE6B341>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 26    | [FF4BA70AEC61](<Mini Pc/CompuLab/Intense-PC/Intense-PC/FF4BA70AEC61>) |
| SK hynix   | HMT351U6EFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 25    | [18D706410B00](<Desktop/Lenovo/ThinkCentre/ThinkCentre M82 29291G5/18D706410B00>) |
| Micron     | Module Row Of Chips LPDDR5   | 4 GB     |      | 6400 | 25    | [1E0857AB8F83](<Desktop/Shenzhen Simo Innovation Technology/SI-B/SI-B160/1E0857AB8F83>) |
| Samsung    | Module Row Of Chips LPDDR5   | 2 GB     |      | 6400 | 25    | [50FB875C0A87](<Desktop/Others/Others/Others/50FB875C0A87>) |
| Kingston   | 99U5469-045.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 24    | [574869791328](<Mini Pc/ZOTAC/ZBOX-CI325/ZBOX-CI325NANO/574869791328>) |
| Micron     | 18KSF1G72AZ-1G6E1 DIMM       | 8 GB     | DDR3 | 1600 | 24    | [5156E4E71E5B](<Desktop/Intel/S1200KP/S1200KP AAG34877-201/5156E4E71E5B>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 24    | [8443A789142D](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0LN00/8443A789142D>) |
| Samsung    | M391B1G73QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 24    | [3C786505AF3D](<Server/Arbyte Computers/Silex/Silex T115 G2/3C786505AF3D>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2400 | 24    | [24A571577B26](<Notebook/Dell/Precision/Precision 5510/24A571577B26>) |
| Crucial    | CT16G4SFRA32A.M16FR SODIMM   | 16 GB    | DDR4 | 3200 | 23    | [1922775E4B35](<Desktop/Protectli/VP/VP2420/1922775E4B35>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3200 | 23    | [B639862E6D96](<Desktop/MSI/MS-7/MS-7C94/B639862E6D96>) |
| Kingston   | CBD26D4S9S8K1C-8 SODIMM      | 8 GB     | DDR4 | 2667 | 23    | [1D45AC26ECAB](<Desktop/Protectli/VP/VP4630/1D45AC26ECAB>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 23    | [1B11E1CCC3B6](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/1B11E1CCC3B6>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1600 | 23    | [A9713C230463](<Desktop/MSI/MS/MS-7851/A9713C230463>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 667  | 23    | [6DEC02A18C93](<Desktop/ASUSTek Computer/P5/P5Q-E/6DEC02A18C93>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 800  | 23    | [2568AEED30BE](<Desktop/CheckPoint/T-120/T-120-00/2568AEED30BE>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 1333 | 23    | [A663EAB4AAB3](<Notebook/Panasonic/CF-C1/CF-C1BT02EGE/A663EAB4AAB3>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     | DDR3 | 1333 | 23    | [088CE120E14E](<Notebook/Hewlett-Packard/ProBook/ProBook 6550b/088CE120E14E>) |
| Samsung    | Module DIMM                  | 8 GB     | DDR4 | 2133 | 23    | [3021EB0E0867](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/3021EB0E0867>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3200 | 22    | [5A39BB0BDC3A](<Server/Supermicro/Super/Super Server/5A39BB0BDC3A>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 2933 | 22    | [6DF5E8D1AA98](<Desktop/Gigabyte Technology/Z370P/Z370P D3/6DF5E8D1AA98>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 22    | [989E160D6069](<Desktop/Others/Others/Others/989E160D6069>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1866 | 21    | [FEE7ABA2F6FE](<Desktop/ASUSTek Computer/Maximus/Maximus V FORMULA/FEE7ABA2F6FE>) |
| Crucial    | CT32G48C40S5.C16A1 SODIMM    | 32 GB    | DDR5 | 4800 | 21    | [70F1D623E29B](<Desktop/Protectli/VP/VP6650/70F1D623E29B>) |
| Crucial    | CT32G4SFD832A.M16FF SODIMM   | 32 GB    | DDR4 | 3200 | 21    | [D100F99D4D9A](<Desktop/Protectli/VP/VP2420/D100F99D4D9A>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 21    | [CCDD877687EF](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/CCDD877687EF>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 21    | [F1500AF8F65D](<Notebook/Lenovo/ThinkPad/ThinkPad W530 24491A0/F1500AF8F65D>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 21    | [896C37708FA8](<Desktop/Gigabyte Technology/P35/P35-DS3/896C37708FA8>) |
|            | Module DIMM                  | 8 GB     |      | 1333 | 21    | [DD1567741F3D](<Desktop/Gigabyte Technology/P67/P67A-UD3-B3/DD1567741F3D>) |
| Samsung    | M378B5273DH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 21    | [D5F5AB04415C](<Desktop/Dell/OptiPlex/OptiPlex 3010/D5F5AB04415C>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 21    | [499CD7FF5143](<Desktop/Dell/OptiPlex/OptiPlex 790/499CD7FF5143>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2667 | 21    | [9FF406482649](<Notebook/Dell/Latitude/Latitude 5500/9FF406482649>) |
| A-DATA     | Module SODIMM                | 4 GB     | DDR3 | 1600 | 20    | [580AC4B6E62C](<Firewall/Sophos/SG/SG/580AC4B6E62C>) |
| A-DATA     | Module DIMM                  | 4 GB     | DDR4 | 1866 | 20    | [03D9ECF60193](<Firewall/Sophos/SG/SG/03D9ECF60193>) |
|            | 123456789012345678 SODIMM... | 4 GB     |      | 2400 | 20    | [42CE11F0781A](<Notebook/GPD/MicroPC/MicroPC/42CE11F0781A>) |
| Crucial    | CT102464BA160B.C16 DIMM      | 8 GB     | DDR3 | 1600 | 20    | [A72A5E92109B](<Desktop/MSI/MS/MS-7823/A72A5E92109B>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 20    | [099E2BB8370C](<Mini Pc/CompuLab/fitlet/fitlet2/099E2BB8370C>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 20    | [44DA5DFA8B11](<Desktop/Fujitsu/FUTRO/FUTRO S920/44DA5DFA8B11>) |
| SK hynix   | Module DIMM                  | 8 GB     | DDR4 | 2133 | 20    | [889C510137B7](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/889C510137B7>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 20    | [364BABD01752](<Desktop/Shuttle/DS81/DS81D/364BABD01752>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 20    | [1861D8AF67DB](<Notebook/ASUSTek Computer/F3/F3E/1861D8AF67DB>) |
|            | Module DIMM SDRAM            | 4 GB     |      |      | 20    | [102239A60F80](<Desktop/ASRock/G41/G41C-GS/102239A60F80>) |
| Samsung    | M378B5173EB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 20    | [840BA46D757A](<Desktop/Lenovo/ThinkStation/ThinkStation E31 255547U/840BA46D757A>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 20    | [4536BD9030FB](<Desktop/Dell/OptiPlex/OptiPlex XE/4536BD9030FB>) |
| Samsung    | M393B1G70QH0-YK0 DIMM        | 8 GB     | DDR3 | 1600 | 20    | [FB4F503A548B](<Server/Dell/OEM-R/OEM-R 720xd/FB4F503A548B>) |
| Samsung    | M425R1GB4BB0-CWMOD SODIMM    | 8 GB     | DDR5 | 5600 | 20    | [469676FC704A](<Desktop/SJRC/ADLN-6/ADLN-6L/469676FC704A>) |
| Samsung    | M471A1G44BB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 20    | [F7C87E35B991](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21E300E4VN/F7C87E35B991>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 20    | [186230BA990C](<Desktop/Fujitsu/FUTRO/FUTRO S940/186230BA990C>) |
| Crucial    | CT16G48C40S5.C8A1 SODIMM     | 16 GB    | DDR5 | 4800 | 19    | [FAB51E93E08F](<Desktop/CWWK/CW-ADLN-6/CW-ADLN-6L/FAB51E93E08F>) |
| Crucial    | CT16G4SFRA32A.C8FF SODIMM    | 16 GB    | DDR4 | 3200 | 19    | [EFECAFE485DB](<Desktop/Protectli/VP/VP2420/EFECAFE485DB>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 19    | [6F663840EB1A](<Notebook/Lenovo/ThinkPad/ThinkPad T430s 2355A61/6F663840EB1A>) |
| Kingston   | 99U5428-018.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 19    | [A85394C35939](<Mini Pc/Sophos/SG/SG/A85394C35939>) |
| Micron     | 8ATF1G64AZ-2G6E1 DIMM        | 8 GB     | DDR4 | 2667 | 19    | [953934CE866D](<Desktop/Dell/OptiPlex/OptiPlex 5070/953934CE866D>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 19    | [1E7AADCED672](<Desktop/Intel/B75/B75 V1.5/1E7AADCED672>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 19    | [BCF676A737B9](<Desktop/Yanling/YL-GML4/YL-GML4 V1/BCF676A737B9>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 19    | [C95E82575E70](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S61A13/C95E82575E70>) |
| A-DATA     | Module DIMM                  | 4 GB     | DDR4 | 2133 | 18    | [7AE23EBB7F42](<Firewall/Sophos/XG/XG/7AE23EBB7F42>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3000 | 18    | [F22560B94679](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-E R2.0/F22560B94679>) |
| Crucial    | CT8G4SFRA266.M8FRS SODIMM    | 8 GB     | DDR4 | 2667 | 18    | [9ACC289FE09D](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700A9GE/9ACC289FE09D>) |
| SK hynix   | HMT325U6CFR8C-PB DIMM        | 2 GB     | DDR3 | 1600 | 18    | [411C647054B3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/411C647054B3>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 18    | [7C5695F762A8](<Desktop/Dell/OptiPlex/OptiPlex 3010/7C5695F762A8>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 2400 | 18    | [A80A3EFD1849](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-D R2.0/A80A3EFD1849>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3200 | 18    | [D8B47EFBED59](<Desktop/ASRock/H610/H610M-HDV/D8B47EFBED59>) |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 18    | [5A15F3E201EC](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S6LB00/5A15F3E201EC>) |
| Micron     | MTC4C10163S1SC48BA1 SODIMM   | 8 GB     | DDR5 | 4800 | 18    | [61BF15FF7450](<Desktop/Others/Others/Others/61BF15FF7450>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 18    | [4FA723339383](<Desktop/Dell/OptiPlex/OptiPlex 9020/4FA723339383>) |
| SK hynix   | HMA451U6AFR8N-TF DIMM        | 4 GB     | DDR4 | 2133 | 18    | [61FB451ED7B0](<Desktop/Dell/OptiPlex/OptiPlex 7040/61FB451ED7B0>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 8 GB     | DDR4 | 3200 | 18    | [C024967576F5](<Desktop/Dell/OptiPlex/OptiPlex 3050/C024967576F5>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 17    | [BC115D14D7CD](<Desktop/Dell/OptiPlex/OptiPlex 3020/BC115D14D7CD>) |
| Crucial    | BLS4G3D1609DS1S00. DIMM      | 4 GB     | DDR3 | 1600 | 17    | [FEE7ABA2F6FE](<Desktop/ASUSTek Computer/Maximus/Maximus V FORMULA/FEE7ABA2F6FE>) |
| Crucial    | CT32G4SFD832A.C16FF SODIMM   | 32 GB    | DDR4 | 3200 | 17    | [813ECD0196A2](<All In One/Others/Others/Others/813ECD0196A2>) |
| Crucial    | CT8G4SFRA32A.M4FF SODIMM     | 8 GB     | DDR4 | 3200 | 17    | [CDA0C551D5A1](<Desktop/Others/Others/Others/CDA0C551D5A1>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 17    | [5B7604B36E00](<Notebook/Lenovo/ThinkPad/ThinkPad X220 Tablet 4294CTO/5B7604B36E00>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 17    | [1E567F3F8EA2](<Notebook/Dell/Latitude/Latitude E7250/1E567F3F8EA2>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 17    | [78D2A736577D](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7CTO1WW/78D2A736577D>) |
| Micron     | 53D512M64D4RQ-046 Row Of ... | 8 GB     |      | 4800 | 17    | [8BD1F5B08D54](<Desktop/Protectli/V/V1410/8BD1F5B08D54>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 17    | [8A212EB33D5D](<Notebook/Sony/VGN-NS21/VGN-NS21M_S/8A212EB33D5D>) |
|            | Module DIMM                  | 8 GB     | DDR4 | 2400 | 17    | [B25240F6F3BE](<Desktop/Dell EMC/EDGE/EDGE620/B25240F6F3BE>) |
| Samsung    | 53D512M64D4RQ-046 Row Of ... | 4 GB     |      | 3200 | 17    | [AE6D213BDEC6](<Desktop/Intel/Jasper/Jasper Lake Client Platform/AE6D213BDEC6>) |
| Samsung    | M378A5244CB0-CRC DIMM        | 4 GB     | DDR4 | 2666 | 17    | [49E7876F5B17](<Desktop/Dell/OptiPlex/OptiPlex 3050/49E7876F5B17>) |
| Samsung    | M378B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 17    | [B5B98FF1F16A](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/B5B98FF1F16A>) |
| Samsung    | M378B5273CH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 17    | [5854515B05B3](<Desktop/Dell/OptiPlex/OptiPlex 7010/5854515B05B3>) |
| Samsung    | M425R2GA3BB0-CQKOL SODIMM    | 16 GB    | DDR5 | 4800 | 17    | [31219D9D2B79](<Desktop/Others/Others/Others/31219D9D2B79>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 17    | [092F978DF489](<Desktop/Tarox/ECO/ECO 60-1/092F978DF489>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 17    | [8CD78D59E9FD](<Notebook/Dell/Precision/Precision 7730/8CD78D59E9FD>) |
| Team       | TEAMGROUP-SD4-3200 SODIMM    | 8 GB     | DDR4 | 3200 | 17    | [D4F5A584866B](<Desktop/MW/GMLK-2/GMLK-2_5G4L/D4F5A584866B>) |
| A-DATA     | Module DIMM                  | 2 GB     | DDR4 | 2133 | 16    | [7AE23EBB7F42](<Firewall/Sophos/XG/XG/7AE23EBB7F42>) |
| Crucial    | CT32G48C40S5.M16A1 SODIMM    | 32 GB    | DDR5 | 4800 | 16    | [7C87E035E436](<Desktop/Others/Others/Others/7C87E035E436>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 16    | [9A8F75FAF4AE](<Desktop/Intel/MB/MB331/9A8F75FAF4AE>) |
| Kingston   | KF3200C16D4/16GX DIMM        | 16 GB    | DDR4 | 3200 | 16    | [3715D7E2D2CB](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/3715D7E2D2CB>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 16    | [4A0A2736C7E2](<Notebook/Alienware/m15/m15 R6/4A0A2736C7E2>) |
| Samsung    | M378A1K43CB2-CRC DIMM        | 8 GB     | DDR4 | 2667 | 16    | [C5F3C35B3E96](<Desktop/ASUSTek Computer/RS200/RS200-E9-PS2/C5F3C35B3E96>) |
| Samsung    | M378A1K43CB2-CTD DIMM        | 8 GB     | DDR4 | 2667 | 16    | [827A61CBBD61](<Desktop/Lenovo/ThinkCentre/ThinkCentre M700 10KQ000BAU/827A61CBBD61>) |
| Samsung    | M378B1G73DB0-CK0 DIMM        | 8 GB     | DDR3 | 1600 | 16    | [C7D09B2D1E0E](<Desktop/Gigabyte Technology/Z77/Z77N-WIFI/C7D09B2D1E0E>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 1333 | 16    | [61FC662EAE31](<Desktop/Dell/XPS/XPS 8700/61FC662EAE31>) |
| Samsung    | M391A2K43BB1-CTD DIMM        | 16 GB    | DDR4 | 3200 | 16    | [4BE5147F2077](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/4BE5147F2077>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 16    | [5A72F153EB6B](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G2 ITL 20VE/5A72F153EB6B>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 16    | [4699A1C5DDD2](<Desktop/Others/Q/Q-790/4699A1C5DDD2>) |
| Samsung    | Module DIMM                  | 4 GB     | DDR4 | 2133 | 16    | [ADCC6FE7AC5D](<Desktop/Hewlett-Packard/Z240/Z240 Tower Workstation/ADCC6FE7AC5D>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 16    | [45AB03A8B762](<Desktop/MW/GMLK-2/GMLK-2_5G4L/45AB03A8B762>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 16    | [9ACC289FE09D](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700A9GE/9ACC289FE09D>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2400 | 16    | [AB7340D1EA9E](<Desktop/Others/Others/Others/AB7340D1EA9E>) |
| SK hynix   | HMA851S6DJR6N-XN SODIMM      | 4 GB     | DDR4 | 3200 | 16    | [29B4B60D889F](<Desktop/Techvision/TVI7309/TVI7309X/29B4B60D889F>) |
| Corsair    | CMK32GX4M2A2666C16 DIMM      | 16 GB    | DDR4 | 3000 | 15    | [C93DC8453B81](<Server/Supermicro/Super/Super Server/C93DC8453B81>) |
| Crucial    | CT4G4SFS824A.C8FF SODIMM     | 4 GB     | DDR4 | 2666 | 15    | [8437C7FF889A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/8437C7FF889A>) |
|            | DDR4 NB 8G 2666 SODIMM       | 8 GB     | DDR4 | 2667 | 15    | [EF81A850C399](<Desktop/AZW/U/U59/EF81A850C399>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1334 | 15    | [FAA82AA0FCCC](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/FAA82AA0FCCC>) |
| G.Skill    | F4-2400C16-8GRS SODIMM       | 8 GB     | DDR4 | 2400 | 15    | [B739F78A0359](<Desktop/Others/Others/Others/B739F78A0359>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 15    | [7D4BE3A53DA8](<Notebook/Others/Others/Others/7D4BE3A53DA8>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 15    | [C11A501BC1E3](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS01Y00/C11A501BC1E3>) |
| Samsung    | M471B5173EB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 15    | [E525FF3A9462](<Desktop/MiTAC/E/E220/E525FF3A9462>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 15    | [08F8F58B7E7F](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537N24/08F8F58B7E7F>) |
| Super T... | SUPERTALENT02 DIMM           | 4 GB     | DDR3 | 1600 | 15    | [A599BAB282E4](<Desktop/MSI/MS/MS-7680/A599BAB282E4>) |
| Team       | TEAMGROUP-SD4-3200 SODIMM    | 16 GB    | DDR4 | 3200 | 15    | [BEA032AF51EF](<Desktop/Others/Others/Others/BEA032AF51EF>) |
| Transcend  | TS1GLH64V6B3 SODIMM          | 8 GB     | DDR4 | 1333 | 15    | [E4E773637A71](<Notebook/Deciso/Netboard/Netboard A20/E4E773637A71>) |
| Transcend  | TS512MSK64W6H DIMM           | 4 GB     | DDR3 | 1600 | 15    | [B3E85E38A1FA](<Desktop/Others/Others/Others/B3E85E38A1FA>) |
| A-DATA     | Module DIMM                  | 4 GB     | DDR3 | 1600 | 14    | [A6B12F942AE3](<Firewall/Sophos/SG/SG/A6B12F942AE3>) |
| Corsair    | CMK16GX4M2E3200C16 DIMM      | 8 GB     | DDR4 | 3200 | 14    | [022647FB956A](<Desktop/MSI/MS-7/MS-7A69/022647FB956A>) |
| Corsair    | CML8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 14    | [D029BE2432FC](<Desktop/ASRock/H81/H81M-ITX-WiFi/D029BE2432FC>) |
| Crucial    | CT16G4SFD824A.C16FDD SODIMM  | 16 GB    | DDR4 | 3200 | 14    | [7C094C5E47A4](<Desktop/Protectli/VP/VP2420/7C094C5E47A4>) |
| Crucial    | CT8G4SFRA32A.M8FR SODIMM     | 8 GB     | DDR4 | 3200 | 14    | [5445B8A25AAA](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G7/5445B8A25AAA>) |
| Elpida     | Module SODIMM                | 4 GB     | DDR3 | 1600 | 14    | [C99A8135BA59](<Mini Pc/Apple/Macmini7/Macmini7,1/C99A8135BA59>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 14    | [3886A58B61CD](<Notebook/Dell/Precision/Precision 7540/3886A58B61CD>) |
| Micron     | 36ASF2G72PZ-2G1A2 DIMM       | 16 GB    | DDR4 | 2133 | 14    | [E2402DD4F5E7](<Desktop/Gigabyte Technology/X99/X99-UD4P-CF/E2402DD4F5E7>) |
| Micron     | Module SODIMM                | 8 GB     | DDR4 | 3200 | 14    | [C6A55F870C2A](<Desktop/Others/Others/Others/C6A55F870C2A>) |
|            | Module SODIMM                | 16 GB    | DDR4 | 3200 | 14    | [CFE984C704A7](<Mini Pc/AZW/EQ/EQ/CFE984C704A7>) |
|            | Module DIMM                  | 4 GB     | DDR2 | 800  | 14    | [25E7EC363A0E](<Desktop/Lex/Pineview-D/Pineview-D/25E7EC363A0E>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 14    | [94523861AB79](<Notebook/Dell/Latitude/Latitude 7490/94523861AB79>) |
| Samsung    | M471B5173DB0-YK0 DIMM        | 4 GB     | DDR3 | 1600 | 14    | [86DE59C5D6AC](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/86DE59C5D6AC>) |
| SK hynix   | HMA81GU6JJR8N-VK DIMM        | 8 GB     | DDR4 | 2667 | 14    | [05CEE64A4622](<Desktop/Dell/OptiPlex/OptiPlex 3070/05CEE64A4622>) |
| SK hynix   | HMT41GU6BFR8A-PB DIMM        | 8 GB     | DDR3 | 1600 | 14    | [B5176543A12F](<Desktop/Dell/Inspiron/Inspiron 3650/B5176543A12F>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM      | 2 GB     | DDR2 | 975  | 14    | [0EDC23A34E52](<Notebook/Dell/Studio/Studio 1537/0EDC23A34E52>) |
| Corsair    | CMK32GX4M2E3200C16 DIMM      | 16 GB    | DDR4 | 3600 | 13    | [6A2F5C29A9C7](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/6A2F5C29A9C7>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 13    | [9343098F3B9C](<Notebook/Google/Peppy/Peppy/9343098F3B9C>) |
| Kimtigo    | KT8GS3EDF DIMM               | 8 GB     | DDR3 | 1600 | 13    | [7A02637E4B4B](<Mini Pc/AMI/Aptio/Aptio CRB/7A02637E4B4B>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1333 | 13    | [3B894902BCBF](<Desktop/Others/DH61BR/DH61BR G32662-203/3B894902BCBF>) |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     |      | 1333 | 13    | [C76736734DEA](<Desktop/Dell/Studio/Studio XPS 7100/C76736734DEA>) |
| Kingston   | KHX1600C9S3L/4G SODIMM       | 4 GB     | DDR3 | 1600 | 13    | [93283B42A29D](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-502/93283B42A29D>) |
| Kingston   | KNWMX1-ETB SODIMM            | 4 GB     | DDR3 | 1600 | 13    | [E30D4ED913B0](<Desktop/WYSE/ZQ/ZQ Class/E30D4ED913B0>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 13    | [8DF4EF90D1E7](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga 20R6S36000/8DF4EF90D1E7>) |
| Patriot    | PSD38G1600L2S SODIMM         | 8 GB     | DDR3 | 1600 | 13    | [A5E813EE10A7](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/A5E813EE10A7>) |
|            | Module DIMM                  | 1 GB     | DDR2 | 800  | 13    | [7615DDDC42D9](<Desktop/ASUSTek Computer/P5/P5KR/7615DDDC42D9>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 13    | [DD5639A44B24](<Desktop/ASUSTek Computer/M4/M4A78/DD5639A44B24>) |
|            | Module                       | 4 GB     |      | 1600 | 13    | [7ED448217BCB](<Desktop/Protectli/FW4/FW4B/7ED448217BCB>) |
|            | Module DIMM                  | 4 GB     |      | 1600 | 13    | [C738C2FAC8AD](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/C738C2FAC8AD>) |
| Samsung    | M391A2K43BB1-CPB DIMM        | 16 GB    | DDR4 | 2133 | 13    | [3C075767F6F9](<Server/Supermicro/Super/Super Server/3C075767F6F9>) |
| Samsung    | M393A1G40DB0-CPB DIMM        | 8 GB     | DDR4 | 2133 | 13    | [E2402DD4F5E7](<Desktop/Gigabyte Technology/X99/X99-UD4P-CF/E2402DD4F5E7>) |
| Samsung    | M425R1GB4BB0-CQKOD SODIMM    | 8 GB     | DDR5 | 4800 | 13    | [2619F261F425](<Desktop/Shenzhen suqiao computer technology/miniPC/miniPC/2619F261F425>) |
| Samsung    | M471A1K43CB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 13    | [93BC81DA3210](<Desktop/Techvision/TVI7309/TVI7309X/93BC81DA3210>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 13    | [C34EAD07ED4F](<Notebook/Dell/Inspiron/Inspiron 13-7368/C34EAD07ED4F>) |
| Samsung    | Module DIMM                  | 2 GB     | DDR3 | 1333 | 13    | [7A258B888D3B](<Desktop/Dell/Inspiron/Inspiron 620/7A258B888D3B>) |
| SK hynix   | HMA41GU6AFR8N-TF DIMM        | 8 GB     | DDR4 | 2133 | 13    | [FFF4CCB2BC29](<Desktop/Dell/OptiPlex/OptiPlex 7040/FFF4CCB2BC29>) |
| SK hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 13    | [0F9F8CE6AF8E](<Desktop/Fujitsu/D3433-S2/D3433-S2 S26361-D3433-S2/0F9F8CE6AF8E>) |
| Team       | TEAMGROUP-SD3-1600 SODIMM    | 8 GB     | DDR3 | 1600 | 13    | [0FF329336F67](<Notebook/Hewlett-Packard/ProBook/ProBook 4430s/0FF329336F67>) |
| Transcend  | TS1GLK72V6H DIMM             | 8 GB     | DDR3 | 1600 | 13    | [FACB77970B4F](<Server/Supermicro/A1/A1SRM-2758F/FACB77970B4F>) |
| 48spaces   | 0123456789012345678901234... | 1 GB     | DDR2 | 800  | 12    | [748764C99987](<Notebook/Samsung Electronics/N150/N150-N210-N220/748764C99987>) |
| ATP        | X4G08QA8BNWESO-7-TO1 SODIMM  | 8 GB     | DDR4 | 3200 | 12    | [D70ADA8B97ED](<Desktop/Thomas-Krenn.AG/LES/LES network 6L/D70ADA8B97ED>) |
| Corsair    | CMK32GX4M2D3600C18 DIMM      | 16 GB    | DDR4 | 3600 | 12    | [733ABA726486](<Desktop/ASRock/B550/B550 Taichi/733ABA726486>) |
| Corsair    | CMZ16GX3M2A1600C10 DIMM      | 8 GB     | DDR3 | 1600 | 12    | [C49AFF509C9F](<Desktop/ASUSTek Computer/All/All Series/C49AFF509C9F>) |
| Crucial    | CT16G4SFRA266.M16FRS SODIMM  | 16 GB    | DDR4 | 2667 | 12    | [3EC9D288B498](<Desktop/Protectli/VP/VP2420/3EC9D288B498>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 12    | [AE0932E3E09A](<Desktop/ASUSTek Computer/All/All Series/AE0932E3E09A>) |
| Crucial    | CT51264BF160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 12    | [1D0B26F11B14](<Mini Pc/AMI/Aptio/Aptio CRB/1D0B26F11B14>) |
| Crucial    | CT51264BF160BJ.C8F SODIMM    | 4 GB     | DDR3 | 1600 | 12    | [769D5E8A39B2](<Desktop/Intel/DQ77KB/DQ77KB AAG81483-501/769D5E8A39B2>) |
| Crucial    | CT8G4SFRA32A.M4FEA SODIMM    | 8 GB     | DDR4 | 3200 | 12    | [2EB01FA3B290](<Desktop/Others/Others/Others/2EB01FA3B290>) |
| G.Skill    | F3-1600C9-8GXM DIMM          | 8 GB     | DDR3 | 1600 | 12    | [C891D0801C33](<Desktop/ASUSTek Computer/All/All Series/C891D0801C33>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3000 | 12    | [0B1139A6F1F5](<Desktop/Gigabyte Technology/B450/B450 AORUS M/0B1139A6F1F5>) |
| G.Skill    | F4-3200C22-8GRS SODIMM       | 8 GB     | DDR4 | 3200 | 12    | [F7C87E35B991](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21E300E4VN/F7C87E35B991>) |
| SK hynix   | HMT41GU6MFR8C-PB DIMM        | 8 GB     | DDR3 | 1600 | 12    | [B1E11EE78C18](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/B1E11EE78C18>) |
| Kingston   | KF3200C16D4/8GX DIMM         | 8 GB     | DDR4 | 3200 | 12    | [4B9EEC569377](<Desktop/Dell/Vostro/Vostro 3020 T/4B9EEC569377>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 12    | [A507B33A2599](<Notebook/Acer/Aspire/Aspire A514-54/A507B33A2599>) |
| Micron     | 8ATF1G64AZ-2G3B1 DIMM        | 8 GB     | DDR4 | 2400 | 12    | [F4C76D9BF2E8](<Firewall/Sophos/SG/SG/F4C76D9BF2E8>) |
| Micron     | 8ATF1G64HZ-2G3E1 SODIMM      | 8 GB     | DDR4 | 2400 | 12    | [3527D4C112FF](<Desktop/Intel/SKYBAY/SKYBAY/3527D4C112FF>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 54.1  |         | 74    | [F6177B63E7](https://bsd-hardware.info/?probe=f6177b63e7) |
| SANYO      | 45N1773 LION   | 23.2  |         | 38    | [D3A7DE0E4B](https://bsd-hardware.info/?probe=d3a7de0e4b) |
| LGC        | 45N1127 LION   | 23.5  |         | 35    | [D3A7DE0E4B](https://bsd-hardware.info/?probe=d3a7de0e4b) |
| Hewlett... | PABAS024123... | 52.5  |         | 33    | [54CD46759E](https://bsd-hardware.info/?probe=54cd46759e) |
| Lenovo     | PABAS024123... | 22.6  |         | 25    | [9EA21FA783](https://bsd-hardware.info/?probe=9ea21fa783) |
| OEM        | standard LiON  | 80.1  |         | 25    | [B880BE6D5F](https://bsd-hardware.info/?probe=b880be6d5f) |
| Samsung    | Serial numb... | 37.0  |         | 25    | [D5E4A58748](https://bsd-hardware.info/?probe=d5e4a58748) |
| SANYO      | 45N1775 LION   | 24.4  |         | 25    | [D515224367](https://bsd-hardware.info/?probe=d515224367) |
| LGC        | 45N1113 LION   | 23.5  |         | 23    | [D515224367](https://bsd-hardware.info/?probe=d515224367) |
| MSI        | BIF0_9         | 52.4  |         | 22    | [C26A915201](https://bsd-hardware.info/?probe=c26a915201) |
| SANYO      | 45N1023 LION   | 81.3  |         | 22    | [86EFB87E9E](https://bsd-hardware.info/?probe=86efb87e9e) |
| Compal     | PABAS024123... | 52.5  |         | 21    | [82E530D2C7](https://bsd-hardware.info/?probe=82e530d2c7) |
| Sony       | 45N1111 LiP    | 23.2  |         | 18    | [8A1F8B7EAD](https://bsd-hardware.info/?probe=8a1f8b7ead) |
| ASUSTek    | A32-K55        | 48.0  |         | 17    | [127D44B4FC](https://bsd-hardware.info/?probe=127d44b4fc) |
| Samsung    | SR Real LION   | 39.0  |         | 16    | [9D6127F039](https://bsd-hardware.info/?probe=9d6127f039) |
| SMPNz45... | bq20z45189A... | 87.5  |         | 16    | [F990A4641F](https://bsd-hardware.info/?probe=f990a4641f) |
| State:	... | Serial numb... | 45.0  |         | 15    | [0CD9C4BF36](https://bsd-hardware.info/?probe=0cd9c4bf36) |
| AMD Bat... |  Real Lion     | 50.0  | Li-ion  | 14    | [DE145E7CE4](https://bsd-hardware.info/?probe=de145e7ce4) |
| Hewlett... | Primary LIon   | 45    |         | 12    | [FC3020F308](https://bsd-hardware.info/?probe=fc3020f308) |
| Intel SR 1 | SR Real Real   | 35.0  |         | 12    | [884F11539A](https://bsd-hardware.info/?probe=884f11539a) |
| SANYO      | 45N1001 LION   | 56.2  |         | 12    | [1432F4E11C](https://bsd-hardware.info/?probe=1432f4e11c) |
| SANYO      | 45N1767 LION   | 47.5  |         | 11    | [DC8D596EA1](https://bsd-hardware.info/?probe=dc8d596ea1) |
| SANYO      | 92P1137 LION   | 47.5  |         | 11    | [4318A318E5](https://bsd-hardware.info/?probe=4318a318e5) |
| State:	... | Serial numb... | 23.6  |         | 11    | [DAC20ACAC9](https://bsd-hardware.info/?probe=dac20acac9) |
| LGC        | 45N1011 LION   | 86.6  |         | 10    | [4F62B90287](https://bsd-hardware.info/?probe=4f62b90287) |
| Notebook   | BAT LION       | 62    |         | 10    | [4E83C12F96](https://bsd-hardware.info/?probe=4e83c12f96) |
| NVT        | Framewo LION   | 55.0  |         | 10    | [C374E02DCB](https://bsd-hardware.info/?probe=c374e02dcb) |
| SANYO      | 42T4861 LION   | 57.7  |         | 10    | [1646BB53AB](https://bsd-hardware.info/?probe=1646bb53ab) |
| SMP        | 01AV421 LiP    | 24.0  |         | 10    | [32C06C5669](https://bsd-hardware.info/?probe=32c06c5669) |
| Hewlett... | Primary LIon   | 42    |         | 9     | [65370691EC](https://bsd-hardware.info/?probe=65370691ec) |
| Hewlett... | Primary LIon   | 43    |         | 9     | [4B6DAA1F1C](https://bsd-hardware.info/?probe=4b6daa1f1c) |
| Lenovo ... | Serial numb... | 28.5  |         | 9     | [518698BCE2](https://bsd-hardware.info/?probe=518698bce2) |
| LGC        | 5B10W139 LiP   | 50.5  |         | 9     | [6EEBAFD5AD](https://bsd-hardware.info/?probe=6eebafd5ad) |
| LGC        | AC14B8K LION   | 48.9  |         | 9     | [69FF95EED9](https://bsd-hardware.info/?probe=69ff95eed9) |
| SANYO      | 42T4763 LION   | 44.0  |         | 9     | [8C20A09638](https://bsd-hardware.info/?probe=8c20a09638) |
| Hewlett... | Primary LIon   | 40    |         | 8     | [464059D8B1](https://bsd-hardware.info/?probe=464059d8b1) |
| Hewlett... | Primary LIon   | 56    |         | 8     | [4BAE8CD192](https://bsd-hardware.info/?probe=4bae8cd192) |
| LGC        | 01AV478 LiP    | 57.0  |         | 8     | [F6D1411DEF](https://bsd-hardware.info/?probe=f6d1411def) |
| LGC        | 45N1735 LION   | 47.5  |         | 8     | [875EEB5304](https://bsd-hardware.info/?probe=875eeb5304) |
| LGC        | 45N1738 LION   | 71.1  |         | 8     | [7750C38CD0](https://bsd-hardware.info/?probe=7750c38cd0) |
| Notebook   | BAT LION       | 74    |         | 8     | [988F54B681](https://bsd-hardware.info/?probe=988f54b681) |
| SANYO      | 45N1777 LION   | 71.3  |         | 8     | [AA3A0567B3](https://bsd-hardware.info/?probe=aa3a0567b3) |
| SANYO      | Li_Ion_4000... | 47.5  |         | 8     | [474DDB6777](https://bsd-hardware.info/?probe=474ddb6777) |
| SMP        | 00NY493 LiP    | 90.0  |         | 8     | [FA70F945FE](https://bsd-hardware.info/?probe=fa70f945fe) |
| SMPNz451   | bq20z451       | 69.0  |         | 8     | [95F19036DB](https://bsd-hardware.info/?probe=95f19036db) |
| Sony       | Serial numb... | 51.1  |         | 8     | [081979C837](https://bsd-hardware.info/?probe=081979c837) |
| Celxpert   | 01AV424 LiP    | 24.1  |         | 7     | [19A5AED9CD](https://bsd-hardware.info/?probe=19a5aed9cd) |
| Hewlett... | Primary LIon   | 46    |         | 7     | [5E09879203](https://bsd-hardware.info/?probe=5e09879203) |
| Hewlett... | Primary LIon   | 48    |         | 7     | [EA10AC1F83](https://bsd-hardware.info/?probe=ea10ac1f83) |
| Hewlett... | Primary LIon   | 50    |         | 7     | [1ABB405F84](https://bsd-hardware.info/?probe=1abb405f84) |
| LGC        | 01AV489 LiP    | 23.9  |         | 7     | [99F8DF70A7](https://bsd-hardware.info/?probe=99f8df70a7) |
| LGC        | 45N1005 LION   | 56.2  |         | 7     | [DDF37E7B17](https://bsd-hardware.info/?probe=ddf37e7b17) |
| Panasonic  | AS16A5K LION   | 41.4  |         | 7     | [A8F794F3FB](https://bsd-hardware.info/?probe=a8f794f3fb) |
| SANYO      | 45N1734 LION   | 47.5  |         | 7     | [E3B9C9632C](https://bsd-hardware.info/?probe=e3b9c9632c) |
| SANYO      | 45N1779 LION   | 99.5  |         | 7     | [34B156C20C](https://bsd-hardware.info/?probe=34b156c20c) |
| SANYO      | AL12A32 LION   | 37.0  |         | 7     | [31A71A6CB4](https://bsd-hardware.info/?probe=31a71a6cb4) |
| SMP        | 00HW023 LiP    | 23.5  |         | 7     | [8C91D180A9](https://bsd-hardware.info/?probe=8c91d180a9) |
| SMP        | 01AV430 LiP    | 57.0  |         | 7     | [898DBBC136](https://bsd-hardware.info/?probe=898dbbc136) |
| SMP        | 45N1071 LiP    | 46.0  |         | 7     | [CEC90DDD1B](https://bsd-hardware.info/?probe=cec90ddd1b) |
| SMP        | L16M2PB2 LiP   | 35.0  |         | 7     | [67EA149C61](https://bsd-hardware.info/?probe=67ea149c61) |
| Sunwoda    | 5B10W13975 LiP | 57.0  |         | 7     | [1F7A60F418](https://bsd-hardware.info/?probe=1f7a60f418) |
| Hewlett... | Primary        | 48    |         | 6     | [45D3874955](https://bsd-hardware.info/?probe=45d3874955) |
| Hewlett... | Primary LIon   | 38    |         | 6     | [80C808DE34](https://bsd-hardware.info/?probe=80c808de34) |
| LGC        | 00HW028 LiP    | 52.3  |         | 6     | [A7843447C0](https://bsd-hardware.info/?probe=a7843447c0) |
| LGC        | 02DL007 LiP    | 50.5  |         | 6     | [4E006E39F5](https://bsd-hardware.info/?probe=4e006e39f5) |
| LGC        | 45N1029 LION   | 93.2  |         | 6     | [0644799933](https://bsd-hardware.info/?probe=0644799933) |
| LGC        | AP18C8K LION   | 48.0  |         | 6     | [C8E5CE4E55](https://bsd-hardware.info/?probe=c8e5ce4e55) |
| Notebook   | BAT LION       | 49    |         | 6     | [8A2BBA8635](https://bsd-hardware.info/?probe=8a2bba8635) |
| NVT        | FRANGWA LION   | 60.6  |         | 6     | [41AB1DA986](https://bsd-hardware.info/?probe=41ab1da986) |
| SANYO      | 00HW022 LiP    | 23.5  |         | 6     | [0CEB5CFBF8](https://bsd-hardware.info/?probe=0ceb5cfbf8) |
| SANYO      | 01AV405 LION   | 26.3  |         | 6     | [56FA0D4656](https://bsd-hardware.info/?probe=56fa0d4656) |
| SANYO      | 01AV425 LION   | 48.8  |         | 6     | [C074ABF948](https://bsd-hardware.info/?probe=c074abf948) |
| SANYO      | 42T4799 LION   | 86.6  |         | 6     | [E63BC464F2](https://bsd-hardware.info/?probe=e63bc464f2) |
| SANYO      | PABAS024123... | 55.9  |         | 6     | [93FAAAFF91](https://bsd-hardware.info/?probe=93faaaff91) |
| SMP        | DELL GPM036... | 97.0  |         | 6     | [928A571C76](https://bsd-hardware.info/?probe=928a571c76) |
| SMP        | L16M2PB1 LiP   | 30.0  |         | 6     | [B67644F2B3](https://bsd-hardware.info/?probe=b67644f2b3) |
| SONYCor    | AP13J4K LION   | 44.7  |         | 6     | [7D888B2DD9](https://bsd-hardware.info/?probe=7d888b2dd9) |
| ASUSTek    | K53--52        | 48.4  |         | 5     | [4F0C073344](https://bsd-hardware.info/?probe=4f0c073344) |
| ASUSTek    | X550A26        | 33.2  |         | 5     | [6EB57B9354](https://bsd-hardware.info/?probe=6eb57b9354) |
| Celxpert   | 01AV448 LiP    | 45.7  |         | 5     | [E8B73C0891](https://bsd-hardware.info/?probe=e8b73c0891) |
| Celxpert   | 01AY969 LiP    | 80.4  |         | 5     | [C0DCFEC41D](https://bsd-hardware.info/?probe=c0dcfec41d) |
| CPT-COS    | L16C2PB2 LiP   | 30.6  |         | 5     | [ED15CA801E](https://bsd-hardware.info/?probe=ed15ca801e) |
| DPON016    | ASMB016        | 50.2  |         | 5     | [5916D9274D](https://bsd-hardware.info/?probe=5916d9274d) |
| DPONz45... | bq20z45189A... | 71.5  |         | 5     | [A7587990E0](https://bsd-hardware.info/?probe=a7587990e0) |
| Hewlett... | Primary        | 34    |         | 5     | [4C5AA5C3EA](https://bsd-hardware.info/?probe=4c5aa5c3ea) |
| Hewlett... | Primary LIon   | 32    |         | 5     | [8D3420DB99](https://bsd-hardware.info/?probe=8d3420db99) |
| Hewlett... | Primary LIon   | 35    |         | 5     | [17834256CA](https://bsd-hardware.info/?probe=17834256ca) |
| Hewlett... | Primary LIon   | 44    |         | 5     | [FACF720E84](https://bsd-hardware.info/?probe=facf720e84) |
| Hewlett... | Serial numb... | 12.0  |         | 5     | [E0C8E95E52](https://bsd-hardware.info/?probe=e0c8e95e52) |
| Intel SR 1 | Harris Beac... | 33.1  |         | 5     | [2FD4B148BB](https://bsd-hardware.info/?probe=2fd4b148bb) |
| LG         | LGES-LG LION   | 72.0  |         | 5     | [9F9235FCD6](https://bsd-hardware.info/?probe=9f9235fcd6) |
| LGC        | 01AV490 LiP    | 23.9  |         | 5     | [A64FE205A9](https://bsd-hardware.info/?probe=a64fe205a9) |
| LGC        | 42T4911 LION   | 51.3  |         | 5     | [1FE30AEF50](https://bsd-hardware.info/?probe=1fe30aef50) |
| LGC        | 45N1025 LION   | 57.7  |         | 5     | [BFBC6BECA8](https://bsd-hardware.info/?probe=bfbc6beca8) |
| LGC        | 45N1049 LION   | 40.4  |         | 5     | [934FF561A5](https://bsd-hardware.info/?probe=934ff561a5) |
| LGC        | 45N1079 LION   | 64.1  |         | 5     | [482CBA9F2F](https://bsd-hardware.info/?probe=482cba9f2f) |
| LGC        | AP18E8M Li-Ion | 57.5  |         | 5     | [94F04895FE](https://bsd-hardware.info/?probe=94f04895fe) |
| LGC        | L16L2PB2 LiP   | 30.0  |         | 5     | [4BD0423B13](https://bsd-hardware.info/?probe=4bd0423b13) |
| Notebook   | BAT LION       | 35    |         | 5     | [4AC0707C49](https://bsd-hardware.info/?probe=4ac0707c49) |
| Razer      | Blade Li-I     | 95.2  |         | 5     | [BE6F32CE1D](https://bsd-hardware.info/?probe=be6f32ce1d) |
| Samsung... | DELL P8TC72... | 86.6  |         | 5     | [B586C78D26](https://bsd-hardware.info/?probe=b586c78d26) |
| SANYO      | 45N1037 LION   | 44.0  |         | 5     | [3EB843C23A](https://bsd-hardware.info/?probe=3eb843c23a) |
| SANYO      | 45N1172 LION   | 62.6  |         | 5     | [8406CAD5BE](https://bsd-hardware.info/?probe=8406cad5be) |
| SANYO      | 45N1769 LION   | 56.2  |         | 5     | [7463E05C88](https://bsd-hardware.info/?probe=7463e05c88) |
| SANYO      | AS10D31 Lion   | 47.5  |         | 5     | [07DA5932A6](https://bsd-hardware.info/?probe=07da5932a6) |
| SIMPLO     | PABAS024123... | 68.8  |         | 5     | [742D648570](https://bsd-hardware.info/?probe=742d648570) |
| SMP        | 00HW029 LiP    | 52.1  |         | 5     | [91106574A4](https://bsd-hardware.info/?probe=91106574a4) |
| SMP        | 01AV447 LiP    | 45.7  |         | 5     | [6DF8B611A2](https://bsd-hardware.info/?probe=6df8b611a2) |
| SMP        | 02DL008 LiP    | 50.5  |         | 5     | [4EA2230818](https://bsd-hardware.info/?probe=4ea2230818) |
| SMP        | 5B10W138 LiP   | 45.7  |         | 5     | [B16A33C476](https://bsd-hardware.info/?probe=b16a33c476) |
| SMP        | DELL DM3WC6... | 60.0  |         | 5     | [F6F77A8B31](https://bsd-hardware.info/?probe=f6f77a8b31) |
| SMP        | DELL G8VCF6... | 52.0  |         | 5     | [AC396BECE7](https://bsd-hardware.info/?probe=ac396bece7) |
| SMP        | DELL TP1GT6... | 60.0  |         | 5     | [26185F189E](https://bsd-hardware.info/?probe=26185f189e) |
| Standard   | SR Real LION   | 61.4  |         | 5     | [3400AC8782](https://bsd-hardware.info/?probe=3400ac8782) |
| ASUSTek    | 1015PE         | 47.5  |         | 4     | [DC06C76CF9](https://bsd-hardware.info/?probe=dc06c76cf9) |
| ASUSTek    | K55--47        | 51.7  |         | 4     | [6FA29C4E4D](https://bsd-hardware.info/?probe=6fa29c4e4d) |
| ASUSTek    | X202-51        | 38.0  |         | 4     | [0ED385A36D](https://bsd-hardware.info/?probe=0ed385a36d) |
| Hewlett... | Primary        | 31    |         | 4     | [77F3D49B2E](https://bsd-hardware.info/?probe=77f3d49b2e) |
| Hewlett... | Primary LIon   | 36    |         | 4     | [AC725CC2BD](https://bsd-hardware.info/?probe=ac725cc2bd) |
| Hewlett... | Primary LIon   | 37    |         | 4     | [92C676E033](https://bsd-hardware.info/?probe=92c676e033) |
| Hewlett... | Primary LIon   | 39    |         | 4     | [0DE2223643](https://bsd-hardware.info/?probe=0de2223643) |
| Hewlett... | Primary LIon   | 41    |         | 4     | [4E4E2DA2FC](https://bsd-hardware.info/?probe=4e4e2da2fc) |
| Hewlett... | Primary LIon   | 47    |         | 4     | [8C0329672D](https://bsd-hardware.info/?probe=8c0329672d) |
| Hewlett... | Primary LIon   | 55    |         | 4     | [CAD0E50EA5](https://bsd-hardware.info/?probe=cad0e50ea5) |
| Hewlett... | Primary LION   | 41    |         | 4     | [FC481181A6](https://bsd-hardware.info/?probe=fc481181a6) |
| LG         | PABAS024123... | 49.0  |         | 4     | [262110252B](https://bsd-hardware.info/?probe=262110252b) |
| LGC        | 01AV445 LiP    | 45.0  |         | 4     | [86866CE217](https://bsd-hardware.info/?probe=86866ce217) |
| LGC        | 01AV470 LiP    | 47.9  |         | 4     | [D864971168](https://bsd-hardware.info/?probe=d864971168) |
| LGC        | 01AV492 LION   | 71.1  |         | 4     | [99F8DF70A7](https://bsd-hardware.info/?probe=99f8df70a7) |
| LGC        | 42T4865 LION   | 57.7  |         | 4     | [2FE3FF7E06](https://bsd-hardware.info/?probe=2fe3ff7e06) |
| LGC        | 45N1147 LION   | 56.2  |         | 4     | [B532F1CE9C](https://bsd-hardware.info/?probe=b532f1ce9c) |
| LGC        | 45N1749 LiP    | 34.0  |         | 4     | [7D7F564886](https://bsd-hardware.info/?probe=7d7f564886) |
| LGC        | DELL 49VTP ... | 57.7  |         | 4     | [DE97E0B2FC](https://bsd-hardware.info/?probe=de97e0b2fc) |
| LGC KT0... | AP18C8K LION   | 48.0  |         | 4     | [375C9F30CD](https://bsd-hardware.info/?probe=375c9f30cd) |
| Notebook   | BAT LION       | 48    |         | 4     | [88B9892DD2](https://bsd-hardware.info/?probe=88b9892dd2) |
| Notebook   | BAT LION       | 53    |         | 4     | [E2F93CE841](https://bsd-hardware.info/?probe=e2f93ce841) |
| Notebook   | BAT LION       | 60    |         | 4     | [9A62677EA8](https://bsd-hardware.info/?probe=9a62677ea8) |
| OEM        | FX50442        | 48.0  |         | 4     | [F8C10BF25A](https://bsd-hardware.info/?probe=f8c10bf25a) |
| Panasonic  | 42T4793 LION   | 51.3  |         | 4     | [664D48690E](https://bsd-hardware.info/?probe=664d48690e) |
| SANYO      | 00323341343... | 55.9  |         | 4     | [F4C2BF9852](https://bsd-hardware.info/?probe=f4c2bf9852) |
| SANYO      | 01AV419 LION   | 24.0  |         | 4     | [2CC969595A](https://bsd-hardware.info/?probe=2cc969595a) |
| SANYO      | 42T4791 LION   | 47.5  |         | 4     | [C0A6490FC8](https://bsd-hardware.info/?probe=c0a6490fc8) |
| SANYO      | 42T4940 LION   | 86.6  |         | 4     | [2DB86B4DFF](https://bsd-hardware.info/?probe=2db86b4dff) |
| SANYO      | 45N1013 LION   | 56.2  |         | 4     | [63D0CDE972](https://bsd-hardware.info/?probe=63d0cde972) |
| SANYO      | AL10B31        | 48.8  |         | 4     | [F8D6BB3095](https://bsd-hardware.info/?probe=f8d6bb3095) |
| SANYO      | AL15A32 LION   | 37.0  |         | 4     | [8B71E16AF3](https://bsd-hardware.info/?probe=8b71e16af3) |
| SANYO      | GRAPE32 LION   | 48.8  |         | 4     | [DFFC2E116D](https://bsd-hardware.info/?probe=dffc2e116d) |
| SIMPLO     | BASE-BAT LiP   | 53.0  |         | 4     | [8836AA08EC](https://bsd-hardware.info/?probe=8836aa08ec) |
| SMP        | 45N1736 LION   | 47.5  |         | 4     | [E41FE01667](https://bsd-hardware.info/?probe=e41fe01667) |
| SMP        | 5B10W139 LiP   | 50.5  |         | 4     | [052C7D6FDF](https://bsd-hardware.info/?probe=052c7d6fdf) |
| SMP        | 5B10W13906 LiP | 50.5  |         | 4     | [150320A6B1](https://bsd-hardware.info/?probe=150320a6b1) |
| SMP        | 5B10W13931 LiP | 51.0  |         | 4     | [2B103A6D58](https://bsd-hardware.info/?probe=2b103a6d58) |
| SMP        | 5B10W13973 LiP | 57.0  |         | 4     | [ED79EA60C4](https://bsd-hardware.info/?probe=ed79ea60c4) |
| SMP        | 5B11C732 LiP   | 57.0  |         | 4     | [0F475F8E5D](https://bsd-hardware.info/?probe=0f475f8e5d) |
| SMP        | DELL GD1JP6... | 68.0  |         | 4     | [FD917CF2F0](https://bsd-hardware.info/?probe=fd917cf2f0) |
| SMP        | DELL VN3N04... | 41.4  |         | 4     | [6FC0671DC6](https://bsd-hardware.info/?probe=6fc0671dc6) |
| SMP        | L17M2PB7 LiP   | 30.0  |         | 4     | [20090CB5C6](https://bsd-hardware.info/?probe=20090cb5c6) |
| SMP        | L20M2PF0 LiP   | 38.0  |         | 4     | [202A277C32](https://bsd-hardware.info/?probe=202a277c32) |
| SMP-SDI2.8 | DELL FW1MN3... | 41.4  |         | 4     | [8CA5137564](https://bsd-hardware.info/?probe=8ca5137564) |
| Sunwoda    | L19D4PH3 LiP   | 61.0  |         | 4     | [020E17C2F8](https://bsd-hardware.info/?probe=020e17c2f8) |
| ASUSTek    | F82--22        | 46.2  |         | 3     | [A952B43F14](https://bsd-hardware.info/?probe=a952b43f14) |
| ASUSTek    | UX31-35        | 47.9  |         | 3     | [93655CDD83](https://bsd-hardware.info/?probe=93655cdd83) |
| ASUSTek    | X453-42        | 31.7  |         | 3     | [51933883D6](https://bsd-hardware.info/?probe=51933883d6) |
| ASUSTek    | X550A30        | 44.2  |         | 3     | [EDD7342AA3](https://bsd-hardware.info/?probe=edd7342aa3) |
| Celxpert   | 5B10W138 LiP   | 45.7  |         | 3     | [83B87DAC52](https://bsd-hardware.info/?probe=83b87dac52) |
| Celxpert   | 5B10W13959 LiP | 94.0  |         | 3     | [5C1DFE489A](https://bsd-hardware.info/?probe=5c1dfe489a) |
| Celxpert   | L20C4PC1 LiP   | 80.0  |         | 3     | [89A61ACA01](https://bsd-hardware.info/?probe=89a61aca01) |
| DGFGE      | 597077-3S Real | 65.0  |         | 3     | [1E903ACB93](https://bsd-hardware.info/?probe=1e903acb93) |
| DPON013    | ASMB013        | 50.2  |         | 3     | [5F364EC930](https://bsd-hardware.info/?probe=5f364ec930) |
| Dynapack   | HB4593R1ECW... | 56.3  |         | 3     | [7D9A498768](https://bsd-hardware.info/?probe=7d9a498768) |
| Hewlett... | Primary        | 47    |         | 3     | [19DDFA696D](https://bsd-hardware.info/?probe=19ddfa696d) |
| Hewlett... | Primary LIon   |       |         | 3     | [718126149C](https://bsd-hardware.info/?probe=718126149c) |
| Hewlett... | Primary LIon   | 34    |         | 3     | [0B79535C7F](https://bsd-hardware.info/?probe=0b79535c7f) |
| Hewlett... | Primary LIon   | 64    |         | 3     | [E2D694053A](https://bsd-hardware.info/?probe=e2d694053a) |
| Hewlett... | Primary LIon   | 90    |         | 3     | [95AADF59D9](https://bsd-hardware.info/?probe=95aadf59d9) |
| Lenovo     | Serial numb... | 28.5  |         | 3     | [E2DAD0B43A](https://bsd-hardware.info/?probe=e2dad0b43a) |
| Lenovo     | BASE-BAT LiP   | 45.0  |         | 3     | [EB136E5D7E](https://bsd-hardware.info/?probe=eb136e5d7e) |
| Lenovo     | LCFC Li Pol... | 22.6  |         | 3     | [E7C9D50432](https://bsd-hardware.info/?probe=e7c9d50432) |
| LGC        | 01AV432 LiP    | 51.0  |         | 3     | [C27BA488AA](https://bsd-hardware.info/?probe=c27ba488aa) |
| LGC        | 01AV494 LiP    | 57.0  |         | 3     | [BBC44A72CC](https://bsd-hardware.info/?probe=bbc44a72cc) |
| LGC        | 5B10W138 LiP   | 45.0  |         | 3     | [3D50BA4D85](https://bsd-hardware.info/?probe=3d50ba4d85) |
| LGC        | 5B10W13960 LiP | 68.0  |         | 3     | [5F31E6DC7E](https://bsd-hardware.info/?probe=5f31e6dc7e) |
| LGC        | 5B10X026 LiP   | 45.0  |         | 3     | [B4ADFDDDC6](https://bsd-hardware.info/?probe=b4adfdddc6) |
| LGC        | AP19B8K LION   | 41.8  |         | 3     | [6D4FA8616C](https://bsd-hardware.info/?probe=6d4fa8616c) |
| LGC        | L17L3PG1 LiP   | 52.5  |         | 3     | [D8F8901AE7](https://bsd-hardware.info/?probe=d8f8901ae7) |
| LGC        | LNV-45N1 LION  | 71.1  |         | 3     | [A56783D219](https://bsd-hardware.info/?probe=a56783d219) |
| Murata     | AP18C4K Li-Ion | 47.9  |         | 3     | [415AA43C5C](https://bsd-hardware.info/?probe=415aa43c5c) |
| Notebook   | BAT LION       | 36    |         | 3     | [04CA736537](https://bsd-hardware.info/?probe=04ca736537) |
| NVT        | FRANDBA LION   | 85.0  |         | 3     | [587525EBAB](https://bsd-hardware.info/?probe=587525ebab) |
| Panasonic  | 42T4620 LION   | 84.2  |         | 3     | [46766BC381](https://bsd-hardware.info/?probe=46766bc381) |
| Panasonic  | 42T4801 LION   | 84.2  |         | 3     | [0990E7253E](https://bsd-hardware.info/?probe=0990e7253e) |
| Panasonic  | 45N1143 LION   | 38.9  |         | 3     | [D9EFC1E30B](https://bsd-hardware.info/?probe=d9efc1e30b) |
| Panasonic  | 92P1133 LION   | 84.2  |         | 3     | [3497EE2FCC](https://bsd-hardware.info/?probe=3497ee2fcc) |
| Panasonic  | AP16M5J Li-Ion | 37.0  |         | 3     | [81827CCBCA](https://bsd-hardware.info/?probe=81827ccbca) |
| Panasonic  | AP19B5K LION   | 39.7  |         | 3     | [3D830AD581](https://bsd-hardware.info/?probe=3d830ad581) |
| Panasonic  | Li_Ion_4000... | 47.5  |         | 3     | [FAE71F7E35](https://bsd-hardware.info/?probe=fae71f7e35) |
| Samsung... | DELL MT2648... | 86.6  |         | 3     | [08FE78379D](https://bsd-hardware.info/?probe=08fe78379d) |
| SANYO      | 45N1173 LION   | 94.0  |         | 3     | [37CB237CE2](https://bsd-hardware.info/?probe=37cb237ce2) |
| SANYO      | 45N1177 LION   | 62.6  |         | 3     | [A41F95A475](https://bsd-hardware.info/?probe=a41f95a475) |
| SANYO      | AC14B13J LION  | 37.3  |         | 3     | [7027C4EFD5](https://bsd-hardware.info/?probe=7027c4efd5) |
| SANYO      | AP13J3K LION   | 45.9  |         | 3     | [E2E0A1953D](https://bsd-hardware.info/?probe=e2e0a1953d) |
| SANYO      | AS07A31 Lion   | 48.8  |         | 3     | [C2025D1B60](https://bsd-hardware.info/?probe=c2025d1b60) |
| SANYO      | L09S6Y02 LION  | 38.9  |         | 3     | [256915976D](https://bsd-hardware.info/?probe=256915976d) |
| SDI        | Dell LION      | 49    |         | 3     | [6911E08B7E](https://bsd-hardware.info/?probe=6911e08b7e) |
| SIMPLO     | Li_Ion_4000... | 48.8  |         | 3     | [5C123882B9](https://bsd-hardware.info/?probe=5c123882b9) |
| SMP        | 00HW003 LiP    | 50.1  |         | 3     | [341BAE363A](https://bsd-hardware.info/?probe=341bae363a) |
| SMP        | 00UR891 LiP    | 32.0  |         | 3     | [7809EC60BF](https://bsd-hardware.info/?probe=7809ec60bf) |
| SMP        | 01AV406 LiP    | 26.1  |         | 3     | [A5FE1BD04D](https://bsd-hardware.info/?probe=a5fe1bd04d) |
| SMP        | 01AV431 LiP    | 57.0  |         | 3     | [4F57A0FE86](https://bsd-hardware.info/?probe=4f57a0fe86) |
| SMP        | 01AV446 LiP    | 45.3  |         | 3     | [D8315913B0](https://bsd-hardware.info/?probe=d8315913b0) |
| SMP        | 01AV452 LiP    | 24.0  |         | 3     | [5CAAAD73BD](https://bsd-hardware.info/?probe=5caaad73bd) |
| SMP        | 01AV471 LiP    | 48.0  |         | 3     | [28D67AB74A](https://bsd-hardware.info/?probe=28d67ab74a) |
| SMP        | 02DL014 LiP    | 57.0  |         | 3     | [1271688C43](https://bsd-hardware.info/?probe=1271688c43) |
| SMP        | 5B10W51827 LiP | 50.5  |         | 3     | [7158BA18D1](https://bsd-hardware.info/?probe=7158ba18d1) |
| SMP        | DELL 71JF45... | 74.0  |         | 3     | [B4A35AA7B0](https://bsd-hardware.info/?probe=b4a35aa7b0) |
| SMP        | DELL 7V69Y5... | 62.0  |         | 3     | [9E798CBFC8](https://bsd-hardware.info/?probe=9e798cbfc8) |
| SMP        | DELL CRT6P2... | 99.9  |         | 3     | [7E1C664559](https://bsd-hardware.info/?probe=7e1c664559) |
| SMP        | DELL JHXPY5... | 57.5  |         | 3     | [EC74AF083F](https://bsd-hardware.info/?probe=ec74af083f) |
| SMP        | DELL VM7329... | 42.0  |         | 3     | [65071F6E52](https://bsd-hardware.info/?probe=65071f6e52) |
| SMP        | DELL Y3F7Y6... | 42.0  |         | 3     | [F31CC32515](https://bsd-hardware.info/?probe=f31cc32515) |
| SMP        | L14M4P23 LION  | 60.0  |         | 3     | [3653895B8E](https://bsd-hardware.info/?probe=3653895b8e) |
| SMP        | L17M3PG1 LiP   | 52.5  |         | 3     | [3DFF76A9DD](https://bsd-hardware.info/?probe=3dff76a9dd) |
| SMP        | L19M4PG LION   | 51.0  |         | 3     | [039591CE70](https://bsd-hardware.info/?probe=039591ce70) |
| Sony       | 45N1705 LiP    | 47.1  |         | 3     | [17FD94A4C0](https://bsd-hardware.info/?probe=17fd94a4c0) |
| State:	... | PA5109U-1BRS   | 47.5  | Li-ion  | 3     | [F27EA283CF](https://bsd-hardware.info/?probe=f27ea283cf) |
| TPS        | S10            | 44.7  |         | 3     | [FD081A3636](https://bsd-hardware.info/?probe=fd081a3636) |
| WB SR 1    | WB Lion Lion   | 41.8  |         | 3     | [7BA189FF8A](https://bsd-hardware.info/?probe=7ba189ff8a) |
| 30G020     | AP18C8K LION   | 48.0  |         | 2     | [5B03E6F7EC](https://bsd-hardware.info/?probe=5b03e6f7ec) |
| 333-2C-... | BN03051XL LION | 45.8  |         | 2     | [AF65FE5D3A](https://bsd-hardware.info/?probe=af65fe5d3a) |
| APL MRD    |  Lion          |       | Li-ion  | 2     | [584ECF8423](https://bsd-hardware.info/?probe=584ecf8423) |
| Apower     | AEC3756153-... | 37.0  |         | 2     | [86DF31742E](https://bsd-hardware.info/?probe=86df31742e) |
| AS19MZF    | C302-50 LION   | 39.0  |         | 2     | [D9DF48C781](https://bsd-hardware.info/?probe=d9df48c781) |
| AS3GWAF3KC | GA50358 OOI0   | 90.0  |         | 2     | [C926EC5BAF](https://bsd-hardware.info/?probe=c926ec5baf) |
| ASUSTek    | 1215B          | 56.2  |         | 2     | [1CCF85F60D](https://bsd-hardware.info/?probe=1ccf85f60d) |
| ASUSTek    | G74--52        | 78.0  |         | 2     | [6B7CF8FCAC](https://bsd-hardware.info/?probe=6b7cf8fcac) |
| ASUSTek    | G75--52        | 66.0  |         | 2     | [2EDE0A1468](https://bsd-hardware.info/?probe=2ede0a1468) |
| ASUSTek    | K52F-44        | 57.2  |         | 2     | [BC31C4707C](https://bsd-hardware.info/?probe=bc31c4707c) |
| ASUSTek    | K56--30        | 44.6  |         | 2     | [1263A5FB37](https://bsd-hardware.info/?probe=1263a5fb37) |
| ASUSTek    | K72--52        | 72.6  |         | 2     | [CE5FCBDC3E](https://bsd-hardware.info/?probe=ce5fcbdc3e) |
| ASUSTek    | N56--52        | 57.7  |         | 2     | [C1AF06BF99](https://bsd-hardware.info/?probe=c1af06bf99) |
| ASUSTek    | UX325 LIon     | 67.3  |         | 2     | [1F76A6C28C](https://bsd-hardware.info/?probe=1f76a6c28c) |
| ASUSTek    | X551-26        | 37.4  |         | 2     | [30209D394A](https://bsd-hardware.info/?probe=30209d394a) |
| ASUSTek    | X555-50        | 37.3  |         | 2     | [9C0C41B663](https://bsd-hardware.info/?probe=9c0c41b663) |
| BYD        | DELL 7FHHV8... | 56.0  |         | 2     | [1725DB4DA9](https://bsd-hardware.info/?probe=1725db4da9) |
| BYD        | DELL 9W9MX8... | 42.0  |         | 2     | [12D707EAC2](https://bsd-hardware.info/?probe=12d707eac2) |
| BYD        | DELL M59JH3... | 84.3  |         | 2     | [F9481E59B6](https://bsd-hardware.info/?probe=f9481e59b6) |
| BYD        | L22B4PC0 LiP   | 80.0  |         | 2     | [3FA8964010](https://bsd-hardware.info/?probe=3fa8964010) |
| BYD2022    | L22B4PE0 LiP   | 60.0  |         | 2     | [221E1F01F4](https://bsd-hardware.info/?probe=221e1f01f4) |
| Celxpert   | 01AV475 LiP    | 54.1  |         | 2     | [B6C70A48EA](https://bsd-hardware.info/?probe=b6c70a48ea) |
| Celxpert   | 02DL019 LiP    | 48.1  |         | 2     | [0273F2F271](https://bsd-hardware.info/?probe=0273f2f271) |

