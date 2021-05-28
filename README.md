DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 2759.

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

Count  — number of computers with this device installed,
Probe  — latest probe ID of this device.

### Cpu

| MFG        | Name                           | GHz  | Count | Probe      |
|------------|--------------------------------|------|-------|------------|
| AMD        | GX-412TC SOC                   |      | 93    | DC79BE2CD4 |
| Intel      | Celeron J3160                  | 1.60 | 49    | 7B8AAB7F3A |
| Intel      | Core i5-7200U                  | 2.50 | 41    | CC7F385529 |
| Intel      | Core 2 Duo                     |      | 30    | FCBFBC2DFA |
| Intel      | Celeron J1900                  | 1.99 | 28    | 54D58E79B6 |
| Intel      | Celeron J3455                  | 1.50 | 27    | C9218EE21D |
| Intel      | Core i5-3570 CPU               |      | 23    | 901FAAE6DF |
| Intel      | Core i7-7500U                  | 2.70 | 22    | 70E9642EEE |
| Intel      | Core i5-2520M                  | 2.50 | 21    | C6D626C350 |
| Intel      | Core i5-3320M                  | 2.60 | 21    | 1E9F399D73 |
| Intel      | Core i5-8250U                  | 1.60 | 20    | 10AF242F8B |
| Intel      | Core i7-8550U                  | 1.80 | 20    | F8BFC70F13 |
| Intel      | Core i3-7100U                  | 2.40 | 20    | BAD0367EC8 |
| Intel      | Celeron J1900                  | 1.99 | 20    | 1C67BF34D5 |
| AMD        | GX-420CA SOC with Radeon HD... |      | 18    | DE3D6DCDF5 |
| Intel      | Core i7-3770                   | 3.40 | 16    | 3A4E33EB4D |
| Intel      | Core i5-4590                   | 3.30 | 16    | 915E62DC4A |
| Intel      | Core i5-6500                   | 3.20 | 16    | 76241E9DDF |
| Intel      | Celeron J4115                  | 1.80 | 15    | 31A9BF167B |
| Intel      | Atom D525                      | 1.80 | 15    | 119095C02A |
| Intel      | Core i5-2400                   | 3.10 | 15    | 783DF52955 |
| Intel      | Core i5-6200U                  | 2.30 | 15    | AF72876FD2 |
| Intel      | Core i5-3470                   | 3.20 | 14    | 7C333C4F82 |
| Intel      | Core i5-5300U                  | 2.30 | 14    | DCA8BA9D37 |
| Intel      | Celeron J4105                  | 1.50 | 13    | 08D15AE852 |
| Intel      | Core i5-4570                   | 3.20 | 13    | 195358C8A7 |
| AMD        | Ryzen 7 3700X 8-Core           |      | 12    | 7FC73D2DB3 |
| AMD        | Ryzen 7 2700X Eight-Core       |      | 12    | 8D2FCC286D |
| Intel      | Core i5-8365U                  | 1.60 | 12    | 2538B038ED |
| Intel      | Core i5-5200U                  | 2.20 | 12    | 89CA4554CA |
| Intel      | Xeon D-1518                    | 2.20 | 12    | B36520C1BA |
| AMD        | FX-8350 Eight-Core             |      | 11    | AB8235808D |
| Intel      | Core i5-10210U                 | 1.60 | 11    | A09FBE5FCC |
| Intel      | Xeon E5620                     | 2.40 | 11    | EF99FFC696 |
| Intel      | Core i3-3220                   | 3.30 | 11    | D4713F1CC0 |
| Intel      | Xeon E5-2650 v2                | 2.60 | 11    | 1E629D4C5A |
| Intel      | Pentium N3700                  | 1.60 | 11    | 9CF9861053 |
| Intel      | Core i3-8145U                  | 2.10 | 10    | BD8BEA4A6A |
| Intel      | Atom E3845                     | 1.91 | 10    | 22D40E3B3D |
| Intel      | Core i7-3770K                  | 3.50 | 10    | FC02A4314B |
| Intel      | Core i5-4200U                  | 1.60 | 10    | 7F5CFF0E01 |
| Intel      | Celeron N3150                  | 1.60 | 10    | 03D2A695B2 |
| Intel      | Core i5-6300U                  | 2.40 | 10    | 821C81E652 |
| Intel      | Core i7-6600U                  | 2.60 | 10    | 2B97986DE1 |
| Intel      | Core i3-6100                   | 3.70 | 10    | D36FCCF7B7 |
| AMD        | G-T40E                         |      | 9     | 7B4678C7EF |
| AMD        | Ryzen 5 3600 6-Core            |      | 9     | 39A46CE44E |
| AMD        | Ryzen 5 2400G with Radeon V... |      | 9     | 421DA89770 |
| Intel      | Core i3-1005G1                 | 1.20 | 9     | AE1BFCCF22 |
| Intel      | Celeron 3865U                  | 1.80 | 9     | A707BEAE6F |
| Intel      | Xeon X3430                     | 2.40 | 9     | A6CB9D7C3F |
| Intel      | Core i7-4790K                  | 4.00 | 9     | D6131126D1 |
| Intel      | Celeron 2955U                  | 1.40 | 9     | D3D9DC620F |
| Intel      | Core i3-4030U                  | 1.90 | 9     | 5A128DD6A3 |
| Intel      | Celeron N3160                  | 1.60 | 9     | B736031BFD |
| Intel      | Celeron N3450                  | 1.10 | 9     | E59BF5453D |
| Intel      | Atom C3558                     | 2.20 | 9     | 89C0064AEB |
| AMD        | RX-427BB with AMD Radeon R7... |      | 8     | DF43B9C68E |
| AMD        | Ryzen 7 2700 Eight-Core        |      | 8     | 9E03A76684 |
| Intel      | Celeron N4100                  | 1.10 | 8     | 836E25BADB |
| Intel      | Core i7-8565U                  | 1.80 | 8     | 7C642E5E7D |
| Intel      | Core 2 Quad CPU                |      | 8     | 67B6B45D83 |
| Intel      | Core i7-8700                   | 3.20 | 8     | 6E874538CB |
| Intel      | Core i7-7700                   | 3.60 | 8     | 90D705DD1E |
| Intel      | Core i5-2500 @ 3.30GH          |      | 8     | 2AB72E6776 |
| Intel      | Xeon E31220                    | 3.10 | 8     | 41C7E5E015 |
| Intel      | Celeron N2940                  | 1.83 | 8     | 1C1759F8EC |
| Intel      | Core i3-3240                   | 3.40 | 8     | 2757850646 |
| Intel      | Core i7-3520M                  | 2.90 | 8     | ED80DC9019 |
| Intel      | Xeon E3-1220 V2                | 3.10 | 8     | 3E650BE93D |
| Intel      | Core i3-4130                   | 3.40 | 8     | 8D808611E9 |
| Intel      | Core i3-4150                   | 3.50 | 8     | E44BEDB9CA |
| Intel      | Core i3-4160                   | 3.60 | 8     | 59EFED23B2 |
| Intel      | Core i7-4770                   | 3.40 | 8     | F81908CDF4 |
| Intel      | Core i3-5010U                  | 2.10 | 8     | 5FE156B619 |
| Intel      | Core i5-5250U                  | 1.60 | 8     | 7DACCCD5F5 |
| Intel      | Core i7-4600U                  | 2.10 | 8     | 6EC8FD788A |
| Intel      | Atom C2358                     | 1.74 | 8     | 7E6BEE8355 |
| AMD        | Ryzen 7 1700 Eight-Core        |      | 7     | 6251043541 |
| AMD        | Ryzen 9 3900X 12-Core          |      | 7     | 62B9EA2794 |
| AMD        | Ryzen 5 2600 Six-Core          |      | 7     | ED656E816F |
| Intel      | Core 2 Duo                     |      | 7     | DF2D210D67 |
| Intel      | Core i7-8750H                  | 2.20 | 7     | 676F16AC86 |
| Intel      | Core i5-3210M                  | 2.50 | 7     | C559882754 |
| Intel      | Core i5-3570                   | 3.40 | 7     | 351B13FD3B |
| Intel      | Core i5-4210U                  | 1.70 | 7     | 076DC91B26 |
| Intel      | Core i5-4300U                  | 1.90 | 7     | 1DBD9A5CEE |
| Intel      | Celeron J3060                  | 1.60 | 7     | 302561BF98 |
| Intel      | Atom C2558                     | 2.40 | 7     | 8D2F78F042 |
| Intel      | Celeron 3855U                  | 1.60 | 7     | EF18FBE1C6 |
| Intel      | Atom E3930                     | 1.30 | 7     | C02CC5A715 |
| AMD        | Ryzen 3 1200 Quad-Core         |      | 6     | E9CA160A2D |
| AMD        | Ryzen 9 3950X 16-Core          |      | 6     | 325186171A |
| AMD        | Ryzen 5 3500U with Radeon V... |      | 6     | D776625073 |
| Intel      | Celeron J4125                  | 2.00 | 6     | 33B86A7DF2 |
| Intel      | Core i5-8350U                  | 1.70 | 6     | 96CC0C27B0 |
| Intel      | Core i7-7600U                  | 2.80 | 6     | 88C27E65D7 |
| Intel      | Core 2 Quad Q6600              | 2.40 | 6     | 49594D3213 |
| Intel      | Pentium G4560                  | 3.50 | 6     | 8FDB8D2B93 |
| Intel      | Atom N270                      | 1.60 | 6     | 614326A3D3 |
| Intel      | Core i3-2100 @ 3.10GH          |      | 6     | 273E379D9F |
| Intel      | Core i3-2120 @ 3.30GH          |      | 6     | FFE4972D83 |
| Intel      | Core i5-2540M                  | 2.60 | 6     | 6BBADBA65D |
| Intel      | Celeron J1900                  | 1.99 | 6     | 3E211C52EA |
| Intel      | Celeron J1800                  | 2.41 | 6     | C832372CCB |
| Intel      | Core i3-3227U                  | 1.90 | 6     | 9050866FB2 |
| Intel      | Pentium G3220                  | 3.00 | 6     | 5ACA6C03C1 |
| Intel      | Atom C2758                     | 2.40 | 6     | DCCBE18982 |
| Intel      | Core i3-6006U                  | 2.00 | 6     | F9C67B360F |
| Intel      | Pentium N4200                  | 1.10 | 6     | AA6B495C8A |
| Intel      | Core i7-6700                   | 3.40 | 6     | C98CB0E438 |
| Intel      | Pentium G4400                  | 3.30 | 6     | DA48CA6303 |
| AMD        | FX-8320 Eight-Core             |      | 5     | A03927CC2E |
| AMD        | Ryzen 5 1600 Six-Core          |      | 5     | 6317BD7DBD |
| AMD        | EPYC 3101 4-Core               |      | 5     | F4A0F0941B |
| AMD        | Ryzen 3 3100 4-Core            |      | 5     | 9181A2479B |
| AMD        | Ryzen 7 4800H with Radeon G... |      | 5     | 23AE99E489 |
| Intel      | Celeron J4005                  | 2.00 | 5     | 8D8683565A |
| Intel      | Core i7-8565U                  | 1.80 | 5     | 270BD22B8D |
| Intel      | Core i5-8265U                  | 1.60 | 5     | E1F691AC78 |
| Intel      | Core i5-7300U                  | 2.60 | 5     | E27342AB94 |
| Intel      | Core i7-9750H                  | 2.60 | 5     | D5ADF152A7 |
| Intel      | Core i3-8100                   | 3.60 | 5     | CB97F230B8 |
| Intel      | Core i5-7300HQ                 | 2.50 | 5     | E84B5B6E5F |
| Intel      | Core i7-7700HQ                 | 2.80 | 5     | C65B4D297A |
| Intel      | Xeon E3-1220 v6                | 3.00 | 5     | EFE3DBF989 |
| Intel      | Core i3-10100                  | 3.60 | 5     | 808260BDEE |
| Intel      | Core 2 Duo E8500               | 3.16 | 5     | E67DE92CB9 |
| Intel      | CPU Version                    |      | 5     | E78392BC4C |
| Intel      | Core i5-2430M                  | 2.40 | 5     | 32F03AA888 |
| Intel      | Core i7-2600                   | 3.40 | 5     | F30A9505DD |
| Intel      | Core i7-2640M                  | 2.80 | 5     | 837F5D3DA2 |
| Intel      | Xeon E5645                     | 2.40 | 5     | F54B954AC8 |
| Intel      | Core i5-3570K                  | 3.40 | 5     | 2BBA0377AE |
| Intel      | Core i3-4170                   | 3.70 | 5     | 62376C16A4 |
| Intel      | Pentium G3420                  | 3.20 | 5     | 2713D38658 |
| Intel      | Xeon E3-1220 v3                | 3.10 | 5     | 2338AA8FFF |
| Intel      | Xeon E3-1225 v3                | 3.20 | 5     | 0D491A998A |
| Intel      | Core i7-5600U                  | 2.60 | 5     | 107AC19795 |
| Intel      | Core i3-4005U                  | 1.70 | 5     | 7C8C842FA7 |
| Intel      | Core i7-4510U                  | 2.00 | 5     | 6501322932 |
| Intel      | Pentium N3710                  | 1.60 | 5     | 13316CB067 |
| Intel      | Core i7-6500U                  | 2.50 | 5     | B00DC0301A |
| Intel      | Celeron J3455E                 | 1.50 | 5     | E6A555B397 |
| Intel      | Celeron J3355                  | 2.00 | 5     | BFB7BE7747 |
| Intel      | Core i7-6700K                  | 4.00 | 5     | E2D2BB7F28 |
| Intel      | Xeon E3-1225 v5                | 3.30 | 5     | 977A39E287 |
| Intel      | Atom C3758                     | 2.20 | 5     | 44E10AC014 |
| Intel      | Atom 330 @                     |      | 5     | A5F2E926FB |
| Intel      | Atom D2550                     | 1.86 | 5     | 8D59B379FD |
| AMD        | Phenom II X4 965               |      | 4     | 1C30F7523F |
| AMD        | FX-6100 Six-Core               |      | 4     | E69BE420DF |
| AMD        | Ryzen 3 2200G with Radeon V... |      | 4     | 41A2A2E434 |
| AMD        | Ryzen 3 3200G with Radeon V... |      | 4     | EF29C46355 |
| AMD        | Ryzen 5 3400G with Radeon V... |      | 4     | 83AACCEB4C |
| AMD        | Ryzen 5 3550H with Radeon V... |      | 4     | A3604F6E56 |
| AMD        | Ryzen 7 4700U with Radeon G... |      | 4     | 792FB07DD9 |
| AMD        | Ryzen 7 PRO 4750U with Rade... |      | 4     | BD88655975 |
| Intel      | Core i7-1065G7                 | 1.30 | 4     | C2D56FC369 |
| Intel      | Core i3-8130U                  | 2.20 | 4     | 70760365D0 |
| Intel      | Core i7-10510U                 | 1.80 | 4     | 6E8891F184 |
| Intel      | Core 2 Duo T7250               | 2.00 | 4     | F63D65B78C |
| Intel      | Core 2 CPU                     |      | 4     | 1BD280A155 |
| Intel      | Xeon E-2224                    | 3.40 | 4     | 25E20C3F35 |
| Intel      | Core i3-9100                   | 3.60 | 4     | B77CEEED88 |
| Intel      | Core i3-9100F                  | 3.60 | 4     | D8B645D95D |
| Intel      | Core i5-7400                   | 3.00 | 4     | 0303E38148 |
| Intel      | Core i5-7500                   | 3.40 | 4     | DB95470F69 |
| Intel      | Core i7-7700K                  | 4.20 | 4     | CF965A3A5B |
| Intel      | Core i7-10750H                 | 2.60 | 4     | A40E426983 |
| Intel      | Core 2 Duo E8400               | 3.00 | 4     | 22FA0D8178 |
| Intel      | Core 2 Duo E7300               | 2.66 | 4     | 1186D46AC9 |
| Intel      | Xeon E5506                     | 2.13 | 4     | 5F9F2C2232 |
| Intel      | Xeon E5520                     | 2.27 | 4     | 2B539FCF18 |
| Intel      | Core i3-2350M                  | 2.30 | 4     | DEF6A6516D |
| Intel      | Core i5-2410M                  | 2.30 | 4     | 6BF1F5FE84 |
| Intel      | Core i7-2630QM                 | 2.00 | 4     | 270CA253A3 |
| Intel      | Xeon E31230                    | 3.20 | 4     | 65C50D5505 |
| Intel      | Xeon E31245 @ 3.30GH           |      | 4     | 09A6FA7762 |
| Intel      | Xeon X5650                     | 2.67 | 4     | 4E391C1361 |
| Intel      | Xeon X5680                     | 3.33 | 4     | 806C6F796E |
| Intel      | Celeron 1037U                  | 1.80 | 4     | A379C24586 |
| Intel      | Celeron G1610T                 | 2.30 | 4     | 80CF566074 |
| Intel      | Xeon E3-1220L V2               | 2.30 | 4     | 24962F6D31 |
| Intel      | Xeon E3-1270 V2                | 3.50 | 4     | 0F2ACA0E38 |
| Intel      | Core i5-4300M                  | 2.60 | 4     | 7660F9B6DB |
| Intel      | Core i5-4570T                  | 2.90 | 4     | 7FC044CDB6 |
| Intel      | Core i7-4790                   | 3.60 | 4     | B5FE536096 |
| Intel      | Xeon E3-1226 v3                | 3.30 | 4     | 536E6B5FDF |
| Intel      | Core i3-5005U                  | 2.00 | 4     | EE894449AF |
| Intel      | Core i7-5500U                  | 2.40 | 4     | 61C248A1E6 |
| Intel      | Core i7-5550U                  | 2.00 | 4     | BA0C41EF47 |
| Intel      | Core i3-4010U                  | 1.70 | 4     | E38FF4E233 |
| Intel      | Atom x5-Z8350                  | 1.44 | 4     | 636DFB334B |
| Intel      | Celeron N3350                  | 1.10 | 4     | 9FDA2F2DA0 |
| Intel      | Core i5-6400                   | 2.70 | 4     | 31F0629346 |
| Intel      | Core i7-6700HQ                 | 2.60 | 4     | 1CDBAD9DFE |
| Intel      | Core i5 M 520                  | 2.40 | 4     | 109F3AFA21 |
| Intel      | Core i7-4770K                  | 3.50 | 4     | 69A811CAE5 |
| Intel      | Core i7-4790K                  | 4.00 | 4     | 694204751B |
| AMD        | A4-5000 APU with Radeon HD ... |      | 3     | C781A4CBAD |
| AMD        | Athlon 5350 APU with Radeon R3 |      | 3     | 835842D361 |
| AMD        | E-450 APU with Radeon HD Gr... |      | 3     | 3EFF93BFB5 |
| AMD        | FX-6300 Six-Core               |      | 3     | CEC3CB521D |
| AMD        | A4-5000 APU with Radeon HD ... |      | 3     | 8AC3AC6974 |
| AMD        | GX-416RA SOC                   |      | 3     | A2DCF48CB5 |
| AMD        | Ryzen 5 3600X 6-Core           |      | 3     | 12E20C2CB0 |
| AMD        | Ryzen 7 5800X 8-Core           |      | 3     | CF9B0C65BD |
| AMD        | Ryzen 9 5900X 12-Core          |      | 3     | 4D15A3FFE3 |
| AMD        | FX-8320E Eight-Core            |      | 3     | CC3151BC6F |
| AMD        | Turion II Neo N54L Dual-Core   |      | 3     | 080EFAF98A |
| Intel      | Pentium Silver J5005           | 1.50 | 3     | 1CEF60D042 |
| Intel      | Core i7-8665U                  | 1.90 | 3     | 4376ACCB5E |
| Intel      | Core i5-7267U                  | 3.10 | 3     | 78C12A0D35 |
| Intel      | Core 2 Duo T7300               | 2.00 | 3     | C9E6341E78 |
| Intel      | Pentium Dual E2180             | 2.00 | 3     | E26ECEF661 |
| Intel      | Core 2 4300                    | 1.80 | 3     | FC1C23BEE2 |
| Intel      | Core 2 T7200                   | 2.00 | 3     | F6E7638F87 |
| Intel      | Core i5-8400                   | 2.80 | 3     | 17A763A917 |
| Intel      | Core i5-8600K                  | 3.60 | 3     | 6C4E7B2D67 |
| Intel      | Celeron G4900                  | 3.10 | 3     | 905A9096C2 |
| Intel      | Core i5-9400                   | 2.90 | 3     | 215398B88F |
| Intel      | Core i5-10400                  | 2.90 | 3     | 9478973D4C |
| Intel      | Core 2 Duo P7550               | 2.26 | 3     | 3A9335691F |
| Intel      | Core 2 Duo P8400               | 2.26 | 3     | 981517A51A |
| Intel      | Core 2 Duo P8600               | 2.40 | 3     | F8CE633ED7 |
| Intel      | Core 2 Duo E7200               | 2.53 | 3     | 425210021C |
| Intel      | Core 2 Quad                    |      | 3     | DB19B8D71C |
| Intel      | Core i7 920                    | 2.67 | 3     | 4EAC97C85C |
| Intel      | Xeon E5504                     | 2.00 | 3     | 867F7180AF |
| Intel      | Core i7                        |      | 3     | 0B60C1CB25 |
| Intel      | Genuine CPU                    |      | 3     | C1A55B1147 |
| Intel      | Core i5 650                    | 3.20 | 3     | 12058880BC |
| Intel      | Core i5 M 520                  | 2.40 | 3     | 65F5931910 |
| Intel      | Core i5-2320                   | 3.00 | 3     | 26724735DB |
| Intel      | Core i5-2450M                  | 2.50 | 3     | 2939C4CB17 |
| Intel      | Core i7-2600K                  | 3.40 | 3     | D3742D3898 |
| Intel      | Xeon E5-2450L 0                | 1.80 | 3     | 91CFCF0274 |
| Intel      | Xeon E5-2660 0                 | 2.20 | 3     | EDA4A540C7 |
| Intel      | Celeron N2930                  | 1.83 | 3     | B5856DC812 |
| Intel      | Core i3-3217U                  | 1.80 | 3     | 04161CCCA1 |
| Intel      | Core i3-3225                   | 3.30 | 3     | 16F36A045F |
| Intel      | Core i5-3230M                  | 2.60 | 3     | 229587FBD5 |
| Intel      | Core i5-3317U                  | 1.70 | 3     | F286C1E784 |
| Intel      | Core i5-3340M                  | 2.70 | 3     | 8D24817728 |
| Intel      | Core i5-3427U                  | 1.80 | 3     | E1F811E98E |
| Intel      | Core i5-3570S                  | 3.10 | 3     | 86D164C878 |
| Intel      | Core i7-3632QM                 | 2.20 | 3     | C52B593262 |
| Intel      | Core i7-3740QM                 | 2.70 | 3     | 2C985C22EF |
| Intel      | Pentium G2020                  | 2.90 | 3     | D07AD10827 |

### Memory

| MFG        | Name               | Size     | Type | MT/s | Count | Probe      |
|------------|--------------------|----------|------|------|-------|------------|
|            | Module SODIMM      | 4 GB     | DDR3 | 1333 | 46    | DC79BE2CD4 |
|            | 123456789012345... | 1536 MB  |      | 2400 | 30    | 33B86A7DF2 |
|            | Module(s) DIMM     | 4 GB     |      |      | 28    | 65DBB75598 |
| Samsung    | M471B5173QH0-YK... | 4 GB     | DDR3 | 1600 | 28    | DE3D6DCDF5 |
| Samsung    | M471B5273DH0-CH... | 4 GB     | DDR3 | 1334 | 19    | C6D626C350 |
| SK Hynix   | HMA81GS6AFR8N-U... | 8 GB     | DDR4 | 2400 | 17    | 0CDDBDEE33 |
| SK Hynix   | HMT451S6BFR8A-P... | 4 GB     | DDR3 | 1600 | 16    | DCA8BA9D37 |
| Samsung    | M471B5173DB0-YK... | 4 GB     | DDR3 | 1600 | 16    | DF43B9C68E |
|            | Module DIMM        | 4 GB     | DDR3 | 1333 | 15    | 867F7180AF |
| Samsung    | M471A1K43CB1-CT... | 8 GB     | DDR4 | 2667 | 15    | 10AF242F8B |
| Samsung    | M471B5273CH0-CH... | 4 GB     | DDR3 | 1333 | 15    | F46976D85D |
| Samsung    | M471A1K43CB1-CR... | 8 GB     | DDR4 | 2400 | 14    | EBD44C21D9 |
| Samsung    | M471B1G73QH0-YK... | 8 GB     | DDR3 | 1600 | 14    | 2939C4CB17 |
|            | Module DIMM        | 2048 MB  | DDR2 | 800  | 13    | 00DC46F0A1 |
| Samsung    | M378B5173QH0-CK... | 4 GB     | DDR3 | 1600 | 13    | BC3913FEAD |
| Samsung    | M471B1G73EB0-YK... | 8 GB     | DDR3 | 1600 | 13    | 107AC19795 |
| SK Hynix   | HMT351S6CFR8C-P... | 4 GB     | DDR3 | 1600 | 12    | C52B593262 |
| Samsung    | M471A2K43CB1-CT... | 16 GB    | DDR4 | 2667 | 12    | 31A9BF167B |
| Crucial    | CT102464BA160B.... | 8 GB     | DDR3 | 1600 | 11    | 24B107B13C |
| Crucial    | CT102464BF160B.... | 8 GB     | DDR3 | 1600 | 11    | 0303E38148 |
| SK Hynix   | HMT41GS6BFR8A-P... | 8 GB     | DDR3 | 1600 | 11    | 11FE52BE5E |
| SK Hynix   | HMT451S6AFR8A-P... | 4 GB     | DDR3 | 1600 | 11    | 9050866FB2 |
| Micron     | 8KTF51264HZ-1G6... | 4 GB     | DDR3 | 1600 | 11    | B4B6CFFF1F |
|            | Module DIMM SDRAM  | 1 GB     |      |      | 11    | E67DE92CB9 |
|            | Module SODIMM      | 2 GB     | DDR2 | 667  | 11    | 5DE4060089 |
|            | Module DIMM        | 2 GB     | DDR2 | 800  | 11    | B8F4885EF9 |
| Samsung    | M378B5173DB0-CK... | 4 GB     | DDR3 | 1600 | 11    | 2757850646 |
| SK Hynix   | HMT351U6CFR8C-P... | 4 GB     | DDR3 | 1600 | 10    | 16F36A045F |
|            | Module SODIMM      | 4 GB     | DDR3 | 667  | 10    | B893DF12A1 |
| Samsung    | M471A5244CB0-CT... | 4 GB     | DDR4 | 2667 | 10    | D776625073 |
| Samsung    | M471B1G73DB0-YK... | 8 GB     | DDR3 | 1600 | 10    | 76400372D1 |
| Samsung    | M471B5273DH0-CK... | 4 GB     | DDR3 | 1600 | 10    | 520982317E |
| Samsung    | M471B5773DH0-CH... | 2 GB     | DDR3 | 1333 | 10    | 6398601E16 |
| Crucial    | CT102464BF160B.... | 8 GB     | DDR3 | 1600 | 9     | CE844DDB61 |
| Crucial    | CT102464BF160B.... | 8 GB     | DDR3 | 1600 | 9     | 5FE156B619 |
| SK Hynix   | HMT451U6AFR8C-P... | 4 GB     | DDR3 | 1600 | 9     | 16F36A045F |
| Micron     | Module Row Of C... | 8 GB     |      | 3200 | 9     | AE1BFCCF22 |
|            | Module SODIMM      | 2048 MB  | DDR2 | 667  | 9     | B90180457C |
|            | Module DIMM        | 4 GB     |      | 1333 | 9     | F1A0CEC414 |
| Samsung    | M471A5244CB0-CR... | 4 GB     | DDR4 | 2400 | 9     | 96CC0C27B0 |
| Samsung    | M471B1G73QH0-YK... | 8 GB     | DDR3 | 1600 | 9     | 7B8AAB7F3A |
| Crucial    | CT16G4SFD824A.C... | 16 GB    | DDR4 | 2400 | 8     | BAD0367EC8 |
| SK Hynix   | HMT451U6BFR8A-P... | 4 GB     | DDR3 | 1600 | 8     | 7C333C4F82 |
| Micron     | 8JTF51264AZ-1G6... | 4 GB     | DDR3 | 1600 | 8     | 2757850646 |
|            | Module DIMM        | 2 GB     | DDR2 | 667  | 8     | 254186DAD4 |
|            | Module DIMM        | 2 GB     | DDR3 | 1333 | 8     | CD1101B9A1 |
|            | Module DIMM SDRAM  | 2 GB     |      |      | 8     | 9A8E4A1328 |
|            | Module DIMM        | 8 GB     | DDR3 | 1600 | 8     | 80CF566074 |
| Samsung    | M393B1G70QH0-YK... | 8192 MB  | DDR3 | 1600 | 8     | 8F4B51DABD |
| Samsung    | M471B5173EB0-YK... | 4 GB     | DDR3 | 1600 | 8     | 60E497B426 |
| Samsung    | M471B5773CHS-CH... | 2 GB     | DDR3 | 1333 | 8     | C1A55B1147 |
| Corsair    | CMK16GX4M2B3200... | 8 GB     | DDR4 | 3200 | 7     | 62B9EA2794 |
| Crucial    | BLS8G3D1609DS1S... | 8 GB     | DDR3 | 1600 | 7     | 8D808611E9 |
| SK Hynix   | HMT351S6EFR8A-P... | 4 GB     | DDR3 | 1600 | 7     | 1E9F399D73 |
| SK Hynix   | HMT451U6BFR8C-P... | 4 GB     | DDR3 | 1600 | 7     | 0867602100 |
|            | Module             | 8 GB     |      | 1600 | 7     | 47AA4D946C |
| Samsung    | M378B5273DH0-CK... | 4 GB     | DDR3 | 1600 | 7     | D52B838306 |
| Samsung    | M378B5673FH0-CH... | 2 GB     | DDR3 | 1333 | 7     | FCBFBC2DFA |
| Samsung    | M471B5173QH0-YK... | 4 GB     | DDR3 | 1600 | 7     | 54D58E79B6 |
| SK Hynix   | HMA41GS6AFR8N-T... | 8 GB     | DDR4 | 2133 | 7     | 1CDBAD9DFE |
| Crucial    | CT51264BF160B.C... | 4 GB     | DDR3 | 1600 | 6     | 7C8C842FA7 |
| G.Skill    | F4-3200C16-16GV... | 16 GB    | DDR4 | 3200 | 6     | 23196AA66B |
| G.Skill    | F4-3200C16-8GVK... | 8 GB     | DDR4 | 3200 | 6     | 9F6632DE8B |
| SK Hynix   | HMT351S6CFR8C-H... | 4 GB     | DDR3 | 1333 | 6     | EDBF1FF1C6 |
| Kingston   | 99U5471-054.A00... | 8 GB     | DDR3 | 1600 | 6     | C23066D56D |
| Kingston   | KHX1600C9D3/4GX... | 4 GB     | DDR3 | 1600 | 6     | 87E5651FD1 |
| Kingston   | KHX2400C15/8G DIMM | 8 GB     | DDR4 | 2400 | 6     | D8B645D95D |
| Kingston   | KHX3200C16D4/8G... | 8192 MB  | DDR4 | 3200 | 6     | C996E74EBC |
| Micron     | 16KTF1G64HZ-1G6... | 8 GB     | DDR3 | 1600 | 6     | 91D2CD471C |
| Micron     | 8KTF51264HZ-1G6... | 4 GB     | DDR3 | 1600 | 6     | 8FDA503F16 |
| Nanya      | NT4GC64B8HG0NF-... | 4 GB     | DDR3 | 1600 | 6     | 56A672AF0A |
|            | Module SODIMM      | 2 GB     | DDR2 | 800  | 6     | CC17EEA606 |
|            | Module SODIMM      | 2 GB     | DDR3 | 1333 | 6     | 8FC426B107 |
|            | Module DIMM        | 4096 MB  |      | 1333 | 6     | 1C30F7523F |
|            | Module DIMM        | 8192 MB  | DDR3 | 1600 | 6     | 9E7F246E3F |
| Ramaxel    | RMSA3260ME78HAF... | 8 GB     | DDR4 | 2667 | 6     | 94D082C57C |
| Samsung    | K4EBE304EB-EGCG... | 8 GB     |      | 2133 | 6     | 9773669778 |
| Samsung    | M378B5173EB0-CK... | 4 GB     | DDR3 | 1600 | 6     | AC108DEEA2 |
| Samsung    | M471A1K43DB1-CT... | 8 GB     | DDR4 | 2667 | 6     | 038FBABFE8 |
| Samsung    | M471B5673FH0-CF... | 2 GB     |      | 1066 | 6     | BDBD2D0A05 |
| 48spaces   | 012345678901234... | 2048 MB  | DDR2 | 667  | 5     | EFF02DAFE1 |
| Corsair    | CMZ8GX3M2A1600C... | 4 GB     | DDR3 | 1600 | 5     | 273E379D9F |
| Crucial    | CT102464BF160B.... | 8 GB     | DDR3 | 1600 | 5     | 336700855A |
| Crucial    | CT51264BF160BJ.... | 4 GB     | DDR3 | 1600 | 5     | BA598B52FE |
| SK Hynix   | HMT351S6EFR8C-P... | 4 GB     | DDR3 | 1600 | 5     | 120665D4D3 |
| Kingston   | 9965745-002.A00... | 16 GB    | DDR4 | 3000 | 5     | 6251043541 |
| Kingston   | 99U5428-018.A00... | 8 GB     | DDR3 | 1600 | 5     | 11B96442FF |
| Kingston   | 99U5469-045.A00... | 4 GB     | DDR3 | 1600 | 5     | 5C7EA7FB7D |
| Kingston   | 99U5474-028.A00... | 4096 MB  | DDR3 | 1333 | 5     | 68D5D3C6CD |
| Kingston   | KHX2666C15S4/16... | 16 GB    | DDR4 | 2667 | 5     | 5B7C43FA1F |
| Micron     | 4ATS1G64HZ-2G6E... | 8 GB     | DDR4 | 2667 | 5     | CD016E96EE |
| Nanya      | NT2GC64B88B0NS-... | 2 GB     | DDR3 | 1333 | 5     | BE44400312 |
|            | Module SODIMM      | 2 GB     | DDR3 | 800  | 5     | 119095C02A |
|            | Module DIMM        | 4096 MB  |      | 1600 | 5     | A49FF2B77A |
|            | Module DIMM        | 4096 MB  | DDR3 | 1333 | 5     | 467F7683F6 |
|            | Module DIMM        | 8 GB     |      | 1333 | 5     | 35F1D21B73 |
|            | Module DIMM        | 8 GB     | DDR3 | 1333 | 5     | CB38D39AC4 |
|            | Module(s) DIMM     | 8 GB     |      |      | 5     | 92EE9B3619 |
| Samsung    | M378B5273DH0-CH... | 4 GB     | DDR3 | 1333 | 5     | AB8235808D |
| Samsung    | M378B5773DH0-CH... | 2048 MB  | DDR3 | 1333 | 5     | 1D6F23A5DE |
| Samsung    | M393A2G40DB0-CP... | 16 GB    | DDR4 | 2133 | 5     | B36520C1BA |
| Samsung    | M471A1K43BB0-CP... | 8 GB     | DDR4 | 2133 | 5     | C2A9D1B9A6 |
| Samsung    | M471B5173BH0-CK... | 4 GB     | DDR3 | 1600 | 5     | 1E9F399D73 |
| SK Hynix   | HMA82GS6CJR8N-V... | 16 GB    | DDR4 | 2667 | 5     | 270BD22B8D |
| Corsair    | CMK32GX4M2A2666... | 16384 MB | DDR4 | 2667 | 4     | 6E874538CB |
| Corsair    | CML8GX3M2A1600C... | 4 GB     | DDR3 | 1600 | 4     | D714F07288 |
| Corsair    | CMSO16GX4M1A213... | 16 GB    | DDR4 | 2133 | 4     | 70E9642EEE |
| Corsair    | CMZ16GX3M2A1600... | 8 GB     | DDR3 | 1600 | 4     | 915E62DC4A |
| Crucial    | CT51264BF160BJ.... | 4 GB     | DDR3 | 1600 | 4     | 51276D60E0 |
| Elpida     | EBJ41UF8BCS0-DJ... | 4096 MB  |      | 1333 | 4     | 981517A51A |
| Elpida     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 4     | 4A0982DB2B |
| G.Skill    | F4-3000C16-8GIS... | 8 GB     | DDR4 | 2933 | 4     | 808260BDEE |
| SK Hynix   | HMT425S6AFR6A-P... | 2 GB     | DDR3 | 1600 | 4     | E2B6DBFE40 |
| SK Hynix   | HMT351U6CFR8C-H... | 4 GB     | DDR3 | 1333 | 4     | 1A780B9A95 |
| SK Hynix   | HMT351U6EFR8C-P... | 4 GB     | DDR3 | 1600 | 4     | 56A672AF0A |
| SK Hynix   | HMT451S6MFR8C-P... | 4 GB     | DDR3 | 1600 | 4     | DE1F3FDB0F |
| Kingston   | 99U5428-018.A00... | 8 GB     | DDR3 | 1600 | 4     | 89CA4554CA |
| Kingston   | 99U5469-045.A00... | 4 GB     | DDR3 | 1600 | 4     | A332EFD9D9 |
| Kingston   | 99U5700-028.A00... | 8 GB     | DDR4 | 2400 | 4     | 7CCC7E8AB6 |
| Kingston   | CBD26D4S9S1ME-8... | 8 GB     | DDR4 | 2667 | 4     | A3604F6E56 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 4     | E6354DE524 |
| Kingston   | KHX1600C9S3L/4G... | 4 GB     | DDR3 | 1600 | 4     | AA6B495C8A |
| Kingston   | KHX1600C9S3L/8G... | 8192 MB  | DDR3 | 1600 | 4     | 076DC91B26 |
| Kingston   | KHX1866C10D3/4G... | 4096 MB  | DDR3 | 1867 | 4     | 60DEDD3DCC |
| Kingston   | KHX1866C10D3/8G... | 8192 MB  | DDR3 | 1867 | 4     | 40FF6C6D9D |
| Kingston   | KHX2400C14S4/8G... | 8 GB     | DDR4 | 2400 | 4     | 491A0135A0 |
| Kingston   | KHX2400C15/16G ... | 16 GB    | DDR4 | 2400 | 4     | E2D2BB7F28 |
| Kingston   | KHX2666C16/8G DIMM | 8 GB     | DDR4 | 2667 | 4     | 20052B0D55 |
| Micron     | 16KTF51264HZ-1G... | 4 GB     | DDR3 | 1600 | 4     | C559882754 |
| Micron     | 18ASF2G72AZ-2G3... | 16 GB    | DDR4 | 2400 | 4     | 9A0602D408 |
| Micron     | 18KSF1G72AZ-1G6... | 8192 MB  | DDR3 | 1600 | 4     | B13BC6C946 |
| Micron     | 4ATF51264HZ-2G3... | 4 GB     | DDR4 | 2400 | 4     | CDBA99222D |
| Micron     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 4     | 6501322932 |
| Patriot    | PSD38G1600L2S S... | 8 GB     | DDR3 | 1600 | 4     | 0DEF6CB38E |
|            | Module SODIMM DDR  | 1024 MB  |      |      | 4     | BDD45ACD8D |
|            | Module DIMM        | 2048 MB  | DDR2 | 667  | 4     | BA7D356667 |
|            | Module DIMM SDRAM  | 2048 MB  |      |      | 4     | 5BA6DA7C5F |
|            | Module SODIMM      | 2 GB     | DDR2 |      | 4     | 650F6A1B70 |
|            | Module SODIMM      | 4096 MB  | DDR3 | 1333 | 4     | 576F4DB9E1 |
|            | Module DIMM        | 4 GB     | DDR3 | 1600 | 4     | 3055C06D45 |
|            | Module DIMM SDRAM  | 4 GB     |      |      | 4     | 3C39D32973 |
|            | Module DIMM        | 8192 MB  | DDR3 | 1333 | 4     | 9CE2294C44 |
| Ramaxel    | RMT3170MN68F9F1... | 4 GB     | DDR3 | 1600 | 4     | 0A6985F078 |
| Samsung    | K4EBE304EB-EGCF... | 8 GB     |      | 1867 | 4     | 4993AD0FEB |
| Samsung    | M378B5273CH0-CH... | 4 GB     | DDR3 | 1333 | 4     | AB8235808D |
| Samsung    | M391A2K43BB1-CP... | 16 GB    | DDR4 | 2133 | 4     | B34EE32475 |
| Samsung    | M391B1G73QH0-YK... | 8 GB     | DDR3 | 1600 | 4     | 3105ED01BE |
| Samsung    | M391B5273CH0-YH... | 4 GB     | DDR3 | 1333 | 4     | 0A0B18540B |
| Samsung    | M393B2G70BH0-CK... | 16 GB    | DDR3 | 1600 | 4     | 6DDE87584C |
| Samsung    | M471A2K43CB1-CR... | 16 GB    | DDR4 | 2400 | 4     | 6B2ABD4DF5 |
| Samsung    | M471B1G73DB0-YK... | 8 GB     | DDR3 | 1600 | 4     | 2F0EE1A1F0 |
| Samsung    | M471B1G73DH0-YK... | 8 GB     | DDR3 | 1600 | 4     | 1C1759F8EC |
| Samsung    | M471B5674QH0-YK... | 2 GB     | DDR3 | 1600 | 4     | B570778EF7 |
| SK Hynix   | HMA451S6AFR8N-T... | 4 GB     | DDR4 | 2133 | 4     | DA926F1065 |
| SK Hynix   | HMA81GS6CJR8N-V... | 8 GB     | DDR4 | 2667 | 4     | 1DCB55D9FE |
| SK Hynix   | HMA81GS6JJR8N-V... | 8 GB     | DDR4 | 2667 | 4     | 337A8B5A3D |
| SK Hynix   | HYMP125S64CP8-S... | 2 GB     |      | 975  | 4     | 1BD280A155 |
| Transcend  | TS1GLH64V6B SODIMM | 8 GB     | DDR4 | 1333 | 4     | F4A0F0941B |
| ATP        | AW12P6438BLK0S ... | 4 GB     | DDR3 | 1600 | 3     | B736031BFD |
| Corsair    | CMK32GX4M2B3000... | 16384 MB | DDR4 | 2134 | 3     | 05D3AB8D4B |
| Corsair    | CMSO32GX4M2A213... | 16 GB    | DDR4 | 2133 | 3     | 7259F5CFA8 |
| Corsair    | CMSO4GX3M1A1333... | 4 GB     | DDR3 | 1333 | 3     | 5056D58118 |
| Corsair    | CMSO8GX3M1C1600... | 8 GB     | DDR3 | 1600 | 3     | 7EA373882A |
| Corsair    | CMSX16GX4M2A240... | 8 GB     | DDR4 | 2400 | 3     | 215D0A6FF3 |
| Corsair    | CMSX8GX3M1A1600... | 8 GB     | DDR3 | 1333 | 3     | 8BFCFF9039 |
| Corsair    | CMV4GX3M1A1333C... | 4 GB     | DDR3 | 1333 | 3     | A4FB7AE326 |
| Corsair    | CMX8GX3M2A1333C... | 4096 MB  | DDR3 | 1333 | 3     | 18B86B645A |
| Corsair    | CMZ16GX3M4A1600... | 4 GB     | DDR3 | 1600 | 3     | 783DF52955 |
| Crucial    | CT4G4SFS824A.C8... | 4 GB     | DDR4 | 2400 | 3     | 2DD1C94C37 |
| Crucial    | CT51264BA160B.C... | 4 GB     | DDR3 | 1600 | 3     | 3BD9E63CA9 |
| Crucial    | CT51264BF160BJ.... | 4 GB     | DDR3 | 1600 | 3     | 2C106472CB |
| Crucial    | CT8G4DFS8266.M8... | 8192 MB  | DDR4 | 2667 | 3     | 80E7C230D7 |
| G.Skill    | F3-12800CL9-4GB... | 4 GB     | DDR3 | 1600 | 3     | B608A5E466 |
| G.Skill    | F3-12800CL9-4GB... | 4 GB     | DDR3 | 1600 | 3     | B608A5E466 |
| G.Skill    | F4-2666C19-8GNT... | 8 GB     | DDR4 | 2666 | 3     | B77CEEED88 |
| Goldenmars | GMT8G04SCL116P-... | 8 GB     | DDR3 | 1600 | 3     | 354DC80671 |
| SK Hynix   | HMT325S6CFR8C-P... | 2 GB     | DDR3 | 1600 | 3     | 4433B8842F |
| SK Hynix   | HMT41GS6AFR8A-P... | 8 GB     | DDR3 | 1600 | 3     | 903D74F8E7 |
| SK Hynix   | HMT41GU6MFR8C-P... | 8 GB     | DDR3 | 1600 | 3     | AF5D6A85EF |
| SK Hynix   | HMT41GU7BFR8A-P... | 8 GB     | DDR3 | 1600 | 3     | 6CBE8CABB7 |
| SK Hynix   | HMT325U6CFR8C-H... | 2048 MB  | DDR3 | 1333 | 3     | 1D6F23A5DE |
| Kimtigo    | KT4GS3ED8 DIMM     | 4 GB     | DDR3 | 1600 | 3     | 1C67BF34D5 |
| Kingston   | 9905702-017.A00... | 8 GB     | DDR4 | 2400 | 3     | CB97F230B8 |
| Kingston   | 9965525-085.A00... | 4 GB     | DDR3 | 1333 | 3     | ABDFF2FD05 |
| Kingston   | 9965525-118.A00... | 8 GB     | DDR3 | 1600 | 3     | D6312ECF58 |
| Kingston   | 9965669-031.A00... | 16 GB    | DDR4 | 2400 | 3     | 21D6DB75F5 |
| Kingston   | 99U5428-040.A01... | 4096 MB  | DDR3 | 1333 | 3     | 1565D5D570 |
| Kingston   | 99U5471-020.A00... | 4 GB     | DDR3 | 1333 | 3     | 93995C5C65 |
| Kingston   | 99U5584-010.A00... | 4096 MB  | DDR3 | 1866 | 3     | 3E474F93CF |
| Kingston   | 99U5663-006.A00G   | 16 GB    | DDR4 | 2133 | 3     | 914E765B39 |
| Kingston   | KHX1600C10D3/8G... | 8 GB     | DDR3 | 1600 | 3     | B5FE536096 |
| Kingston   | KHX2133C13S4/8G... | 8192 MB  | DDR4 | 2133 | 3     | A1CE8DDE18 |
| Kingston   | KHX2400C11D3/8G... | 8 GB     | DDR3 | 2400 | 3     | 629D15378D |
| Kingston   | KHX2400C14S4/16... | 16 GB    | DDR4 | 2400 | 3     | 852A900303 |
| Kingston   | KHX2400C15D4/4G... | 4 GB     | DDR4 | 2400 | 3     | B33294491E |
| Kingston   | KHX2666C15S4/8G... | 8 GB     | DDR4 | 2667 | 3     | 578C174991 |
| Kingston   | Module DIMM        | 2048 MB  | DDR2 | 800  | 3     | 8DD5CD14A9 |
| Kingston   | Module DIMM        | 4 GB     | DDR3 | 1600 | 3     | AB53037FDB |
| Micron     | 16ATF2G64AZ-3G2... | 16 GB    | DDR4 | 3200 | 3     | 547FD655F0 |
| Micron     | 16JTF1G64AZ-1G6... | 8192 MB  | DDR3 | 1600 | 3     | E6354DE524 |
| Micron     | 16JTF51264AZ-1G... | 4 GB     | DDR3 | 1333 | 3     | E4E80D663F |
| Micron     | 18KSF1G72AZ-1G6... | 8 GB     | DDR3 | 1600 | 3     | EDE56150A6 |
| Micron     | 36ASF2G72PZ-2G1... | 16 GB    | DDR4 | 2133 | 3     | 636A269A2A |
| Micron     | 36ASF4G72PZ-2G3... | 32 GB    | DDR4 | 2400 | 3     | 4710D6000D |
| Micron     | 4ATF51264HZ-2G6... | 4 GB     | DDR4 | 2400 | 3     | 8CE7E3A180 |
| Micron     | 8ATF1G64HZ-2G3E... | 8 GB     | DDR4 | 2400 | 3     | 638F5594FC |
| Micron     | 8ATF1G64HZ-3G2J... | 8 GB     | DDR4 | 3200 | 3     | D5ADF152A7 |
| Micron     | 8JTF25664AZ-1G4... | 2 GB     | DDR3 | 1333 | 3     | BEF38BD379 |
| Micron     | 8KTF51264HDZ-1G... | 4096 MB  | DDR3 | 1600 | 3     | 57018EDD10 |
| Micron     | Module DIMM        | 2 GB     | DDR3 | 1333 | 3     | 26724735DB |
| Nanya      | NT4GC64B8HG0NS-... | 4 GB     | DDR3 | 1600 | 3     | 4FF3FA22FF |
| Patriot    | PSD38G1600L2S DIMM | 8 GB     | DDR3 | 1600 | 3     | 16C7D6A5A8 |
|            | Module SODIMM      | 1024 MB  | DDR2 |      | 3     | B417DF513F |
|            | Module DIMM SDRAM  | 1024 MB  |      |      | 3     | 8776B186C1 |
|            | Module DIMM        | 1 GB     |      | 667  | 3     | 83768C8856 |
|            | Module DIMM        | 1 GB     | DDR2 | 800  | 3     | E26ECEF661 |
|            | Module DIMM        | 2048 MB  |      | 800  | 3     | A56A9C50FC |
|            | Module SODIMM      | 2048 MB  | DDR2 |      | 3     | FEF3D94E6C |
|            | Module SODIMM      | 2048 MB  | DDR3 | 1600 | 3     | 1D1512889F |
|            | Module SODIMM S... | 2048 MB  |      |      | 3     | A76303A060 |
|            | Module DIMM        | 2 GB     |      | 800  | 3     | F6EAA55ADA |
|            | Module SODIMM DDR  | 512 MB   |      |      | 3     | E6E0A1294C |
|            | Module DIMM SDRAM  | 512 MB   |      |      | 3     | 29A839ABBD |
|            | Module DIMM        | 8192 MB  |      | 1333 | 3     | BE7BEA92E1 |
|            | Module SODIMM      | 8 GB     | DDR3 | 1600 | 3     | 9A0B59F88A |
| Samsung    | K4E6E304EE-EGCF... | 4 GB     |      | 1867 | 3     | 821C81E652 |
| Samsung    | K4E6E304EE-EGCF... | 4 GB     |      | 1867 | 3     | 821C81E652 |
| Samsung    | M378A1K43CB2-CR... | 8 GB     | DDR4 | 2400 | 3     | FD03138DFC |
| Samsung    | M378B1G73DB0-CK... | 8 GB     | DDR3 | 1600 | 3     | E436C22F0D |
| Samsung    | M378B5273CH0-CK... | 4096 MB  | DDR3 | 1600 | 3     | 18B86B645A |
| Samsung    | M378B5773CH0-CH... | 2 GB     | DDR3 | 1333 | 3     | 12058880BC |
| Samsung    | M391A2K43BB1-CR... | 16 GB    | DDR4 | 2400 | 3     | CE899D0480 |
| Samsung    | M391A2K43BB1-CT... | 16 GB    | DDR4 | 2667 | 3     | ED4949FB58 |
| Samsung    | M391B5273DH0-CK... | 4 GB     | DDR3 | 1600 | 3     | 41C7E5E015 |
| Samsung    | M391B5773DH0-YK... | 2 GB     | DDR3 | 1600 | 3     | 41C7E5E015 |
| Samsung    | M393B1K70CH0-CH... | 8 GB     | DDR3 | 1333 | 3     | 77F48D8337 |
| Samsung    | M393B1K70DH0-YH... | 8192 MB  | DDR3 | 1333 | 3     | AC57AB9EF6 |
| Samsung    | M471A1G43DB0-CP... | 8 GB     | DDR4 | 2133 | 3     | E27342AB94 |
| Samsung    | M471A1K43BB1-CR... | 8192 MB  | DDR4 | 2400 | 3     | FAA7BECF82 |
| Samsung    | M471A2G44AM0-CT... | 16 GB    | DDR4 | 2667 | 3     | 7C642E5E7D |
| Samsung    | M471A5244BB0-CR... | 4096 MB  | DDR4 | 2400 | 3     | B17963CD30 |
| Samsung    | M471B5173CB0-YK... | 4 GB     | DDR3 | 1600 | 3     | 3D1A635D8E |
| Samsung    | M471B5173DB0-YK... | 4 GB     | DDR3 | 1600 | 3     | 7E013EA910 |
| Samsung    | M471B5273CH0-YK... | 4 GB     | DDR3 | 1600 | 3     | 50CAF95A09 |
| Samsung    | M471B5674-M0-YK... | 4 GB     | DDR3 | 1600 | 3     | B60382DA32 |
| Samsung    | Module SODIMM      | 2048 MB  | DDR3 | 1333 | 3     | C9A8D5ADE5 |
| Samsung    | Module DIMM        | 2 GB     | DDR3 | 1333 | 3     | 26724735DB |
| Samsung    | Module DIMM        | 4 GB     | DDR3 | 1600 | 3     | BFB7BE7747 |
| Samsung    | Module SODIMM      | 8192 MB  | DDR4 | 2133 | 3     | 40AD0612DE |
| Samsung    | Module SODIMM      | 8 GB     | DDR4 | 2133 | 3     | 2B97986DE1 |

### Battery

| MFG        | Name          | Wh    | Type    | Count | Probe      |
|------------|---------------|-------|---------|-------|------------|
| ASUSTek    | ASUS          | 33.3  |         | 12    | A9C4506364 |
| SANYO      | 45N1773 LION  | 23.2  |         | 11    | 88C27E65D7 |
| Samsung    | Serial num... | 57.7  |         | 9     | DD4310D56F |
| Lenovo     | PABAS02412... | 39.6  |         | 8     | 89CA4554CA |
| Hewlett... | PABAS02412... | 41.9  |         | 7     | 3CB0E979F8 |
| LGC        | 45N1127 LION  | 23.5  |         | 7     | 107AC19795 |
| LGC        | 45N1005 LION  | 47.5  |         | 6     | 0F001F65D2 |
| OEM        | standard LiON | 46.7  |         | 6     | DF77DD6562 |
| SANYO      | 45N1001 LION  | 47.5  |         | 6     | 4FF3FA22FF |
| Sony       | 45N1111 LiP   | 23.2  |         | 6     | 72FB01F474 |
| LGC        | 45N1738 LION  | 71.1  |         | 5     | 88C27E65D7 |
| SANYO      | 42T4861 LION  | 57.7  |         | 5     | C6D626C350 |
| SANYO      | 45N1767 LION  | 47.5  |         | 5     | 11FE52BE5E |
| SANYO      | 45N1775 LION  | 23.2  |         | 5     | 7C7573EB45 |
| Hewlett... | Primary LIon  | 42    |         | 4     | 2B97986DE1 |
| Hewlett... | Primary LIon  | 43    |         | 4     | 2FB1BC911F |
| LGC        | 45N1113 LION  | 23.5  |         | 4     | 107AC19795 |
| SANYO      | 45N1779 LION  | 99.5  |         | 4     | 7660F9B6DB |
| SANYO      | 92P1137 LION  | 48.8  |         | 4     | D223A9B1FB |
| SMP        | 01AV430 LiP   | 57.0  |         | 4     | 4993AD0FEB |
| Hewlett... | Primary LIon  | 56    |         | 3     | 32DFD5E52A |
| LGC        | 00HW028 LiP   | 52.0  |         | 3     | F8F9140D92 |
| LGC        | 02DL007 LiP   | 50.5  |         | 3     | 9458FBEB87 |
| LGC        | 45N1011 LION  | 93.6  |         | 3     | 2C985C22EF |
| LGC        | 45N1029 LION  | 86.6  |         | 3     | 837F5D3DA2 |
| LGC        | 45N1735 LION  | 47.5  |         | 3     | 0F9B8D2E3B |
| LGC        | 5B10W138 LiP  | 45.0  |         | 3     | 94D082C57C |
| Notebook   | BAT LION      | 49    |         | 3     | D4D0B819BC |
| Notebook   | BAT LION      | 62    |         | 3     | 229587FBD5 |
| SANYO      | 42T4763 LION  | 56.2  |         | 3     | B4D22F4179 |
| SANYO      | 45N1023 LION  | 57.7  |         | 3     | AB871769F0 |
| SANYO      | 45N1037 LION  | 48.8  |         | 3     | 661877D8C9 |
| SANYO      | 45N1777 LION  | 71.3  |         | 3     | AA3DEADEDD |
| SANYO      | GRAPE32 LION  | 48.8  |         | 3     | 6A1B523EFB |
| SMP        | 00HW029 LiP   | 52.1  |         | 3     | 821C81E652 |
| SMP        | 01AV421 LiP   | 24.0  |         | 3     | 22B35A127A |
| SMP        | 45N1071 LiP   | 46.0  |         | 3     | B659B95D1A |
| SMP        | DELL 71JF4... | 74.0  |         | 3     | B4A35AA7B0 |
| SMP        | DELL GPM03... | 97.0  |         | 3     | 7D5F7B5033 |
| ASUSTek    | K55--47       | 57.7  |         | 2     | E1E4548D22 |
| Celxpert   | 01AV424 LiP   | 24.1  |         | 2     | 22B35A127A |
| Celxpert   | 01AY969 LiP   | 80.4  |         | 2     | 045A80D8BC |
| Compal     | PABAS02412... | 48.9  |         | 2     | E7D6ECE4BA |
| DYNAPACK   | HB4593R1EC... | 56.3  |         | 2     | F9FDC75B45 |
| Hewlett... | Primary       | 48    |         | 2     | 258EF16ACE |
| Hewlett... | Primary LIon  | 35    |         | 2     | F9C67B360F |
| Hewlett... | Primary LIon  | 37    |         | 2     | 63038D613F |
| Hewlett... | Primary LIon  | 38    |         | 2     | 57DE8A523C |
| Hewlett... | Primary LIon  | 40    |         | 2     | 11011ECEE1 |
| Hewlett... | Primary LIon  | 45    |         | 2     | 1FCDE7C0E1 |
| Hewlett... | Primary LIon  | 46    |         | 2     | 0D35B2F5D8 |
| Hewlett... | Serial num... | 31.1  |         | 2     | AE2DE01D19 |
| Intel SR 1 | SR Real Real  | 36.3  |         | 2     | BC138C0580 |
| Lenovo ... | Serial num... | 41.4  |         | 2     | D3D9DC620F |
| LG         | PABAS02412... | 48.9  |         | 2     | 74B11992D7 |
| LGC        | 01AV420 LiP   | 23.9  |         | 2     | E27342AB94 |
| LGC        | 01AV423 LiP   | 23.9  |         | 2     | E27342AB94 |
| LGC        | 01AV432 LiP   | 51.0  |         | 2     | 96CC0C27B0 |
| LGC        | 01AV445 LiP   | 45.0  |         | 2     | 270BD22B8D |
| LGC        | 01AV478 LiP   | 57.0  |         | 2     | A8508F91DE |
| LGC        | 42T4865 LION  | 64.1  |         | 2     | F46976D85D |
| LGC        | 45N1025 LION  | 64.1  |         | 2     | 3E9AAB9818 |
| LGC        | 45N1147 LION  | 56.2  |         | 2     | C51F274F90 |
| LGC        | 5B10W139 LiP  | 50.5  |         | 2     | BD88655975 |
| LGC        | DELL 49VTP    | 57.7  | Li-ion  | 2     | 9050866FB2 |
| LGC-LGC... | DELL FDRHM... | 42.0  |         | 2     | C2D56FC369 |
| LGC        | LNV-45N1 LION | 47.0  |         | 2     | 0A6985F078 |
| MSI        | BIF0_9        | 51.4  |         | 2     | A40E426983 |
| Notebook   | BAT LION      | 35    |         | 2     | 8F39C38E2E |
| Notebook   | BAT LION      | 36    |         | 2     | 792FB07DD9 |
| Notebook   | BAT LION      | 60    |         | 2     | E84B5B6E5F |
| Notebook   | BAT LION      | 74    |         | 2     | 0BD96EF663 |
| OEM        | FX50442       | 48.0  |         | 2     | 1952513DB8 |
| PANASONIC  | AS16A5K LION  | 41.4  |         | 2     | 240171B234 |
| Samsung... | DELL P8TC7... | 44.4  |         | 2     | DCA8BA9D37 |
| SANYO      | 00HW022 LiP   | 23.5  |         | 2     | 8325C794B3 |
| SANYO      | 01AV405 LION  | 26.3  |         | 2     | 8325C794B3 |
| SANYO      | 01AV425 LION  | 47.5  |         | 2     | 6B2ABD4DF5 |
| SANYO      | 42T4791 LION  | 56.2  |         | 2     | 5D7840D28E |
| SANYO      | 42T4940 LION  | 86.6  |         | 2     | C5E7D3037F |
| SANYO      | 45N1172 LION  | 57.2  |         | 2     | 6E8CAEE5D8 |
| SANYO      | 45N1173 LION  | 85.9  |         | 2     | 683ECA8C23 |
| SANYO      | 45N1177 LION  | 62.6  |         | 2     | 55DEBB2F24 |
| SANYO      | AL12A32 LION  | 32.6  |         | 2     | EDBF1FF1C6 |
| SANYO      | AP13J3K LION  | 45.3  |         | 2     | D15CAACA04 |
| SANYO      | PABAS02412... | 55.9  |         | 2     | E2B6DBFE40 |
| SMP        | 00NY493 LiP   | 90.0  |         | 2     | D8CF9E878E |
| SMP        | 02DL008 LiP   | 50.5  |         | 2     | E1F691AC78 |
| SMP        | DELL 39DY5... | 38.0  |         | 2     | DC37C53E48 |
| SMP        | DELL 4HJXX... | 99.9  |         | 2     | CE29DAF5AD |
| SMP        | DELL 7V69Y... | 62.0  |         | 2     | AF72876FD2 |
| SMP        | DELL 909H5... | 48.2  |         | 2     | 6EC8FD788A |
| SMP        | DELL C5KG6... | 40.0  |         | 2     | 465DD01C0D |
| SMP        | DELL DM3WC... | 60.0  |         | 2     | DEFAEE0E5C |
| SMP        | DELL TP1GT... | 60.0  |         | 2     | F8BFC70F13 |
| SMP        | DELL VN3N0... | 40.3  |         | 2     | 4DA402FDA8 |
| SMP        | DELL Y61CV... | 48.8  |         | 2     | ABE1869A95 |
| SMP-SDI2.8 | DELL FW1MN... | 41.4  |         | 2     | B89DA90904 |
| Sony       | 45N1705 LiP   | 47.1  |         | 2     | E9155D12C7 |
| State:	... | G71C000AH3... | 54.5  |         | 2     | 6357D0D51F |
| State:	... | PA5109U-1BRS  | 48.6  | Li-ion  | 2     | 9FB68E38D8 |
| 13-14      | MO06062 LION  | 36.8  |         | 1     | 4637A9EEFF |
| 313-54-41  | BI03041XL ... | 29.6  |         | 1     | F27578615F |
| 333-1C-    | SD03045 LION  | 45.0  |         | 1     | 4FFE68C199 |
| 333-54-... | LK03055XL ... | 56.7  |         | 1     | ADC45416CE |
| Acer       | Panasonic_... | 57.7  |         | 1     | 56A5581907 |
| ASUSTek    | Serial num... | 51.7  |         | 1     | C52B593262 |
| ASUSTek    | 1015BX        | 56.2  |         | 1     | 5834A52924 |
| ASUSTek    | 1015PE        | 47.5  |         | 1     | C6E717C1E9 |
| ASUSTek    | 900A          | 36.9  |         | 1     | A76303A060 |
| ASUSTek    | A6-4224       | 69.9  |         | 1     | 593C12AA06 |
| ASUSTek    | G75--52       | 78.0  |         | 1     | 9B84D1E7E6 |
| ASUSTek    | G750-59       | 89.2  |         | 1     | 37BE4EA27A |
| ASUSTek    | K53--52       | 55.0  |         | 1     | 975E9CCBE2 |
| ASUSTek    | K55--44       | 49.5  |         | 1     | 4A0982DB2B |
| ASUSTek    | K56--30       | 43.0  |         | 1     | F286C1E784 |
| ASUSTek    | K72--52       | 72.6  |         | 1     | B36FF0B052 |
| ASUSTek    | M70--26       | 78.0  |         | 1     | A2EE0C9EDB |
| ASUSTek    | N55--52       | 57.2  |         | 1     | 7EFB6557A2 |
| ASUSTek    | N56--51       | 56.1  |         | 1     | 9FB23E0394 |
| ASUSTek    | S551-45       | 50.7  |         | 1     | 42792115E3 |
| ASUSTek    | TP50042       | 48.3  |         | 1     | 6501322932 |
| ASUSTek    | X202-51       | 38.0  |         | 1     | F69506DB3B |
| ASUSTek    | X402--38      | 38.0  |         | 1     | 1A2DF26F19 |
| ASUSTek    | X453-42       | 29.4  |         | 1     | CFC7D86B5A |
| ASUSTek    | X550A26       | 32.2  |         | 1     | 26AEF04E22 |
| ASUSTek    | X550A30       | 44.2  |         | 1     | E056F1C77C |
| ASUSTek    | X550E26       | 37.4  |         | 1     | A88CFD7FDD |
| ASUSTek    | X555-50       | 37.3  |         | 1     | 74D43CCD10 |
| ASUSTek    | Z943222       | 47.3  |         | 1     | 1F098AC490 |
| BYD        | DELL FP86V... | 51.0  |         | 1     | 7C1EFA11B9 |
| BYD        | DELL GHXKY... | 64.0  |         | 1     | 6A2635237F |
| BYD        | DELL GW0K9... | 97.0  |         | 1     | AA891D8F27 |
| BYD        | DELL K3JK9... | 62.0  |         | 1     | 12EAE7A62E |
| BYD        | DELL KG7VF... | 60.0  |         | 1     | 2AD87768AF |
| BYD        | DELL M4GWP... | 51.0  |         | 1     | 23AE99E489 |
| BYD        | DELL M59JH... | 86.0  |         | 1     | A1C2EAEE5F |
| BYD        | DELL TXD03... | 53.0  |         | 1     | 80D7BF959A |
| Celxpert   | 01AV448 LiP   | 45.7  |         | 1     | 5A393BC680 |
| Celxpert   | 01AV466 LiP   | 45.7  |         | 1     | 038FBABFE8 |
| Celxpert   | 01AV475 LiP   | 54.1  |         | 1     | 9773669778 |
| Celxpert   | 02DL019 LiP   | 48.1  |         | 1     | CD016E96EE |
| Celxpert   | 5B10W138 LiP  | 57.0  |         | 1     | 2D93A6BEBC |
| Celxpert   | 5B10W139 LiP  | 48.1  |         | 1     | 3DF4ABB2E9 |
| Celxpert   | L18C3PF6 L... | 36.0  |         | 1     | B6AE43880D |
| Celxpert   | L19C4PC0 LiP  | 60.0  |         | 1     | 9FED35D792 |
| Celxpert   | L19C4PC1 LiP  | 80.0  |         | 1     | 2BE8CF963C |
| Clevo      | C410X         | 48.8  |         | 1     | 81C48D156A |
| Compal     | 0033314234... | 36.7  |         | 1     | 045CF81F15 |
| Compal     | PA3465U  L... | 56.6  |         | 1     | 6B81593DE9 |
| CPT-COS    | L16C2PB2 LiP  | 30.6  |         | 1     | 1F226262CC |
| CPT-LGS3   | L15C3A03 LION | 23.8  |         | 1     | C5E824B558 |
| Dell       | W670DILB 0... | 57.7  |         | 1     | 0B60C1CB25 |
| Desay      | HB4593J6EC... | 41.2  |         | 1     | D776625073 |
| DPON013    | ASMB013       | 50.2  |         | 1     | 9ECA3B0463 |
| DPON016    | ASMB016       | 50.2  |         | 1     | ED3684513F |
| DPONz45... | bq20z4510G... | 46.8  |         | 1     | 6CCED6FCF0 |
| DPONz45... | bq20z4516J... | 87.5  |         | 1     | 0621ACAB4E |
| DPONz45... | bq20z451K1... | 84.5  |         | 1     | 052524523B |
| DPONz45... | bq20z451V9... | 54.5  |         | 1     | 3A9335691F |
| DPONz95... | bq20z951F4M0A | 130.0 |         | 1     | 56414400C1 |
| ECS        | CMPC LiON     | 47.5  |         | 1     | 3979CDA9AA |
| EGOWAY3... | A1321Y309Y... | 72.0  |         | 1     | 0AB44E95DF |
| Fujitsu    | CP302628 LION | 28.8  |         | 1     | AC880C0076 |
| Fujitsu    | CP335319-0... | 83.5  |         | 1     | 57506CBDCF |
| Fujitsu    | CP656338-0... | 62.2  |         | 1     | FC2F449A8A |
| Fujitsu    | CP656340-0... | 72.0  |         | 1     | D3D033F879 |
| Fujitsu    | CP671399-0... | 28.1  |         | 1     | D3D033F879 |
| Fujitsu    | CP700283-0... | 76.7  |         | 1     | 845C584693 |
| Fujitsu    | CP700286-0... | 72.4  |         | 1     | 37245ACA21 |
| Fujitsu    | CP709256-0... | 28.1  |         | 1     | 845C584693 |
| Hewlett... | Primary       | 40    |         | 1     | 42ECF97502 |
| Hewlett... | Primary       | 41    |         | 1     | BB8BEB97BE |
| Hewlett... | Primary       | 516   |         | 1     | 5E5632D9B6 |
| Hewlett... | Primary       | 55    |         | 1     | 14857EB6B7 |
| Hewlett... | Primary       | 70    |         | 1     | 7B7C8BF457 |
| Hewlett... | Primary       | 798   |         | 1     | 19F307FF6D |
| Hewlett... | Primary       | 89    |         | 1     | 56844725D1 |
| Hewlett... | Primary       | 95    |         | 1     | 316FFB0740 |
| Hewlett... | Primary LIon  |       |         | 1     | 256E0AE719 |
| Hewlett... | Primary LIon  | 29    |         | 1     | ED80DC9019 |
| Hewlett... | Primary LIon  | 34    |         | 1     | 365EBDAF9C |
| Hewlett... | Primary LIon  | 36    |         | 1     | C559882754 |
| Hewlett... | Primary LIon  | 47    |         | 1     | ADA1119026 |
| Hewlett... | Primary LIon  | 48    |         | 1     | F808E6BB4A |
| Hewlett... | Primary LIon  | 49    |         | 1     | 60D9540D35 |
| Hewlett... | Primary LIon  | 50    |         | 1     | 1F3FA432DC |
| Hewlett... | Primary LIon  | 55    |         | 1     | 6BC6C5B2BF |
| Hewlett... | Primary LIon  | 57    |         | 1     | C1F086E90C |
| Hewlett... | Primary LIon  | 58    |         | 1     | C240E3A1EA |
| Hewlett... | Primary LIon  | 59    |         | 1     | 23EC663F87 |
| Hewlett... | Primary LIon  | 60    |         | 1     | 78D9A31074 |
| Hewlett... | Primary LIon  | 67    |         | 1     | D615B5020D |
| Hewlett... | Primary LIon  | 86    |         | 1     | 40AD0612DE |
| Hewlett... | Primary       | 38    |         | 1     | C355A6280B |
| Hewlett... | Primary       | 54    |         | 1     | 3AE7EEBB87 |
| Hewlett... | Primary LIon  | 38    |         | 1     | 10AF242F8B |
| Hewlett... | Primary LIon  | 43    |         | 1     | B0B4CA9F27 |
| Hewlett... | Primary LIon  | 44    |         | 1     | 47221A4D1D |
| JingYi     | 08K8193 LION  | 48.8  |         | 1     | 926FE13D8F |
| LG         | LGC-LGC LION  | 72.8  |         | 1     | D8EE6BC4E3 |
| LGC        | 00HW002 LiP   | 50.2  |         | 1     | 6A4B5B90B7 |
| LGC        | 00NY486 LION  | 47.5  |         | 1     | 0AA6A9A921 |
| LGC        | 01AV490 LiP   | 23.9  |         | 1     | 771D8EAD80 |
| LGC        | 01AV494 LiP   | 57.0  |         | 1     | 16206C4970 |
| LGC        | 02DL004 LiP   | 51.0  |         | 1     | 8D1C80C2CB |
| LGC        | 02DL011 LiP   | 57.0  |         | 1     | 0EEA690916 |
| LGC        | 42T4912 LION  | 93.6  |         | 1     | 4E693BFCB2 |
| LGC        | 42T4951 LION  | 57.7  |         | 1     | 6A96E2C5B1 |
| LGC        | 42T4969 LION  | 93.6  |         | 1     | A502198932 |
| LGC        | 45N1749 LiP   | 34.0  |         | 1     | 6CD0B0ED25 |
| LGC        | 5B10W13958... | 94.0  |         | 1     | 342E914968 |
| LGC        | AC14B18 Li... | 36.7  |         | 1     | 1AC21E1660 |
| LGC        | AC14B8K LION  | 48.9  |         | 1     | C3ACC4D372 |
| LGC        | AP18E8M Li... | 57.5  |         | 1     | 337A8B5A3D |
| LGC        | DELL 991XP... | 41.4  |         | 1     | C096E37BE5 |
| LGC        | Dell LION     | 73    |         | 1     | 1BF6E913C2 |
| LGC        | L16L2PB2 LiP  | 30.0  |         | 1     | 0309E4AC24 |
| LGC        | L17L3PG1 LiP  | 52.5  |         | 1     | DCE3BA8C99 |
| LGC        | L18L3PF6 LION | 52.5  |         | 1     | CD2AD2800E |
| LGC-LGC2.8 | DELL HMYXT... | 62.2  |         | 1     | BEE421A110 |
| LGC-LGC2.8 | DELL HMYXT... | 62.2  |         | 1     | 8D24817728 |
| LGC-LGC2.8 | DELL T1G4M... | 41.4  |         | 1     | AA90EF6E4B |
| LGC-LGC... | DELL 991XP... | 41.4  |         | 1     | 2C61FCEE12 |
| LGC-LGC... | DELL 3VC9Y... | 42.0  |         | 1     | B84364959D |
| LGC-LGC3.6 | DELL G95J5... | 53.3  |         | 1     | 0A8E2A2E29 |
| LGC-LGC... | DELL GK3D3... | 51.0  |         | 1     | B94AE57278 |
| LGC-LGC... | DELL 10X1J... | 68.0  |         | 1     | 7DEF696A61 |
| LGC-LGC... | DELL 10X1J... | 68.0  |         | 1     | D07A4DC2C7 |
| LGC-LGC... | DELL 49HG8... | 51.0  |         | 1     | F242897C33 |
| LGC-LGC... | DELL 62MJV... | 56.0  |         | 1     | 6BB3B7AA11 |
| LGC-LGC6.9 | DELL W57CV... | 51.8  |         | 1     | 0E736E5E31 |
| LGC-LGC... | DELL 2X39G... | 60.0  |         | 1     | 78D3823932 |
| LGC-LGC... | DELL MYJ96... | 60.0  |         | 1     | 9D900F918C |
| LGC-LGC... | DELL RNP72... | 60.0  |         | 1     | 4199E37B56 |
| LGC-LGC... | DELL DV9NT... | 68.0  |         | 1     | 9B38A72DD4 |
| LGC-LGC... | DELL X77XY... | 68.0  |         | 1     | 2538B038ED |
| LGC        | LNV-42T484... | 47.5  |         | 1     | A201C5F713 |
| LGC        | PA5186U-1BRS  | 45.0  |         | 1     | 9CF9861053 |
|            | MS-1491? L... | 65.5  |         | 1     | 099FBCBEC8 |
| MSI Corp.? | MS-16GH? L... | 48.8  |         | 1     | 35AD1FB80B |
| MSI        | MS-16Q3       | 80.3  |         | 1     | 4031D186C2 |
| MSI Corp.? | MS-N033? L... | 57.7  |         | 1     | 650F6A1B70 |
| NEC        | PC-VP-BP94... | 29.6  |         | 1     | B9F8E78467 |
| Newer T... | A1494 Tech... | 84.0  |         | 1     | 1C9FEEF8E7 |
| Notebook   | BAT LION      | 33    |         | 1     | C184B13749 |
| Notebook   | BAT LION      | 44    |         | 1     | 70760365D0 |
| Notebook   | BAT LION      | 48    |         | 1     | D9661207D7 |
| Notebook   | BAT LION      | 53    |         | 1     | 35AA6590C6 |
| Notebook   | BAT LION      | 67    |         | 1     | 17ED006376 |

