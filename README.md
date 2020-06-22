DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by BSD users at https://bsd-hardware.info.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 180.

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
| Intel      | Core i5-3320M                  | 2.60 | 4     | F4E8FFB5DC |
| Intel      | Core i5-3570 CPU               |      | 3     | 3979CDA9AA |
| Intel      | Core 2 Quad Q6600              | 2.40 | 3     | CF6ACC34AC |
| Intel      | Core i5-2520M                  | 2.50 | 3     | 324265FE3F |
| Intel      | Core i5-2540M                  | 2.60 | 3     | 7C8A68918A |
| AMD        | AMD Ryzen 7 2700 Eight-Core    |      | 2     | C7C50D64CF |
| AMD        | FX-8350 Eight-Core             |      | 2     | 4E60D4674A |
| Intel      | Celeron J4005                  | 2.00 | 2     | E44A7E90E0 |
| Intel      | Core i5-8250U                  | 1.60 | 2     | 2D0DC32CED |
| Intel      | Core i7-7500U                  | 2.70 | 2     | 1887B030C4 |
| Intel      | Core 2 CPU                     |      | 2     | EE60EB3DC8 |
| Intel      | Core i7 920                    | 2.67 | 2     | 66BBED8D59 |
| Intel      | Xeon X3430                     | 2.40 | 2     | 0D8C6DA5DB |
| Intel      | Core i5-2430M                  | 2.40 | 2     | 7042848932 |
| Intel      | Core i7-2640M                  | 2.80 | 2     | 2EBFA76C28 |
| Intel      | Celeron J1900                  | 1.99 | 2     | 79FE3017EF |
| Intel      | Core i7-3770                   | 3.40 | 2     | 0F7697B73A |
| Intel      | Core i5-4300U                  | 1.90 | 2     | C65CDB97DE |
| Intel      | Xeon Bronze 3104               | 1.70 | 2     | 1DB4784753 |
| Intel      | Celeron J3455                  | 1.50 | 2     | 1C8E18B787 |
| Intel      | Core i5 M 560                  | 2.67 | 2     | 6394AE37A8 |
| AMD        | AMD Ryzen 3 1200 Quad-Core     |      | 1     | A49CF5C20B |
| AMD        | AMD Ryzen 5 1600 Six-Core      |      | 1     | B4C4C676C4 |
| AMD        | AMD Ryzen 7 1700 Eight-Core    |      | 1     | 0D931FF2A1 |
| AMD        | AMD Ryzen 9 3950X 16-Core      |      | 1     | C039FF6AB2 |
| AMD        | AMD Ryzen 5 2400G with Rade... |      | 1     | AA58B291B3 |
| AMD        | AMD Ryzen Threadripper 2950... |      | 1     | 29DBE3892C |
| AMD        | AMD Ryzen 5 PRO 2500U w/ Ra... |      | 1     | 010DB0AED4 |
| AMD        | AMD Ryzen 7 1700 Eight-Core    |      | 1     | 44681211FF |
| AMD        | AMD Ryzen 7 2700 Eight-Core    |      | 1     | 7C311EE004 |
| AMD        | AMD Ryzen 7 2700X Eight-Core   |      | 1     | 20FAC3B208 |
| AMD        | GX-420CA SOC with Radeon HD... |      | 1     | 23F8ADB299 |
| AMD        | Phenom 9550 Quad-Core          |      | 1     | 66BCE86F33 |
| AMD        | Athlon II X2 240               |      | 1     | CC5724ACBC |
| AMD        | Sempron 145                    |      | 1     | D99AE1AAD1 |
| AMD        | Turion X2 Dual-Core Mobile ... |      | 1     | E8BED535A9 |
| AMD        | FX-8320 Eight-Core             |      | 1     | DB03BEF1C6 |
| AMD        | FX-8320E Eight-Core            |      | 1     | EB5651F31C |
| AMD        | Athlon X4 750K Quad Core       |      | 1     | 09BFDEAFBD |
| AMD        | Phenom 9150e Quad-Core         |      | 1     | 55755E9AB9 |
| Intel      | Pentium 4                      | 2.66 | 1     | 1BCC2B8E0B |
| Intel      | Pentium 4 ("GenuineIntel" 6... | 2.80 | 1     | 8B9481BAF2 |
| Intel      | Pentium 4                      | 3.00 | 1     | 5B1DC84DA5 |
| Intel      | Pentium D CPU                  |      | 1     | 59E3624DE7 |
| Intel      | Xeon                           | 2.66 | 1     | 9A893E2CC9 |
| Intel      | Pentium M processor ("Genui... | 1.60 | 1     | 6B65FCF9C1 |
| Intel      | Pentium M                      |      | 1     | 1E849F86CF |
| Intel      | Celeron M processor            | 1.70 | 1     | 1F098AC490 |
| Intel      | Core i5-7200U                  | 2.50 | 1     | 4199E37B56 |
| Intel      | Core i7-7600U                  | 2.80 | 1     | 7DEF094AFB |
| Intel      | Core 2 4300                    | 1.80 | 1     | C2067BB99A |
| Intel      | Core 2 6320                    | 1.86 | 1     | 3984F45545 |
| Intel      | Core i7-9750H                  | 2.60 | 1     | 96FCD8FC28 |
| Intel      | Xeon E-2286M                   | 2.40 | 1     | AA891D8F27 |
| Intel      | Core i7-7700HQ                 | 2.80 | 1     | DC7BB56859 |
| Intel      | Core i7-7700K                  | 4.20 | 1     | 528E378206 |
| Intel      | Core i7-7820HQ                 | 2.90 | 1     | 81EFA4B3D3 |
| Intel      | Xeon E3-1220 v6                | 3.00 | 1     | E59AEBEE71 |
| Intel      | Core 2 Duo E8500               | 3.16 | 1     | 84E9E67AA2 |
| Intel      | Core 2 Duo P8600               | 2.40 | 1     | 2FD46CB7C7 |
| Intel      | Core 2 Duo E7200               | 2.53 | 1     | 8F72D18BFF |
| Intel      | Xeon E5504                     | 2.00 | 1     | E2AB2682CB |
| Intel      | Atom D510                      | 1.66 | 1     | C7EA6CABCA |
| Intel      | Core i3 530                    | 2.93 | 1     | 534617FE54 |
| Intel      | Core i3 M 350                  | 2.27 | 1     | 239EEA83C6 |
| Intel      | Core i5 M 430 @ 2.27GH         |      | 1     | 6A6B06FC67 |
| Intel      | Core i5-2320                   | 3.00 | 1     | 14E00AA09F |
| Intel      | Core i7-2600K                  | 3.40 | 1     | 9FEA968A19 |
| Intel      | Core i7-2700K                  | 3.50 | 1     | 94C4617D4E |
| Intel      | Xeon E31220                    | 3.10 | 1     | 6CF7F9EA4B |
| Intel      | Xeon E5630                     | 2.53 | 1     | B43DB1D84E |
| Intel      | Xeon E5-2690                   | 2.90 | 1     | AAC1EEB66A |
| Intel      | Celeron N2830                  | 2.16 | 1     | 6CB240A9F6 |
| Intel      | Celeron 1007U                  | 1.50 | 1     | 705B7E8F47 |
| Intel      | Core i3-3120M                  | 2.50 | 1     | 9A751DDFD8 |
| Intel      | Core i5-3470                   | 3.20 | 1     | 4620A00CCC |
| Intel      | Core i7-3520M                  | 2.90 | 1     | 59C5B6D6B9 |
| Intel      | Core i7-3630QM                 | 2.40 | 1     | 04CD35A77B |
| Intel      | Core i7-3667U                  | 2.00 | 1     | 8ED0FEE673 |
| Intel      | Core i7-3740QM                 | 2.70 | 1     | A7761EE829 |
| Intel      | Celeron G1820                  | 2.70 | 1     | 5D38B05178 |
| Intel      | Core i5-4340M                  | 2.90 | 1     | 79EC87B2DB |
| Intel      | Core i7-4900MQ                 | 2.80 | 1     | 23EC663F87 |
| Intel      | Pentium G3220                  | 3.00 | 1     | E10B99BE8B |
| Intel      | Pentium G3240                  | 3.10 | 1     | AEA3696F41 |
| Intel      | Xeon E3-1225 v3                | 3.20 | 1     | DEA751EDF7 |
| Intel      | Pentium 3805U                  | 1.90 | 1     | B38C2A2E8F |
| Intel      | Core i7-5500U                  | 2.40 | 1     | 07036EAB43 |
| Intel      | Xeon E5-2407 v2                | 2.40 | 1     | 1F4D1E4607 |
| Intel      | Core i5-4250U                  | 1.30 | 1     | 90E967F56B |
| Intel      | Celeron J3060                  | 1.60 | 1     | 55BE2FAB24 |
| Intel      | Core i3-6006U                  | 2.00 | 1     | 709A3DB7DE |
| Intel      | Core i5-6200U                  | 2.30 | 1     | 6C7374D0AB |
| Intel      | Core i5-6260U                  | 1.80 | 1     | 6B854263E7 |
| Intel      | Core i7-6600U                  | 2.60 | 1     | 68840C222B |
| Intel      | Xeon E5-2660 v4                | 2.00 | 1     | B44FE94131 |
| Intel      | Pentium J4205                  | 1.50 | 1     | BB67F0E80B |
| Intel      | Core i5-6440HQ                 | 2.60 | 1     | DFD9A97EFC |
| Intel      | Core i7-6700K                  | 4.00 | 1     | 2FC2952380 |
| Intel      | Core i7-6820HQ                 | 2.70 | 1     | 1A7976D306 |
| Intel      | Xeon E3-1240 v5                | 3.50 | 1     | 360E63CC66 |
| Intel      | Atom N470                      | 1.83 | 1     | 1E5D0A4D7A |
| Intel      | Core i5-4570S                  | 2.90 | 1     | D65F5372EC |
| Intel      | Core i5 M 520                  | 2.40 | 1     | 0087B62853 |
| Intel      | Core i7-2620M                  | 2.70 | 1     | DC34D6FD02 |
| Intel      | Core i7-4770                   | 3.40 | 1     | 9F0AD7BBCF |
| Intel      | Pentium M processor            | 1.60 | 1     | 0D292BCA2F |
| VIA        | C3                             |      | 1     | 21B471F0F6 |

### Memory

| MFG        | Name               | Size     | Type | MT/s | Count | Probe      |
|------------|--------------------|----------|------|------|-------|------------|
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 5     | 324265FE3F |
| Samsung    | M471B1G73QH0-YK... | 8192 MB  | DDR3 | 1600 | 4     | D615B5020D |
| Samsung    | M471B5273CH0-CH... | 4096 MB  | DDR3 | 1333 | 4     | 9BA8051E48 |
| Samsung    | M471B5273DH0-CK... | 4096 MB  | DDR3 | 1600 | 4     | 59C5B6D6B9 |
| SK Hynix   | HMA81GS6AFR8N-U... | 8192 MB  | DDR4 | 2400 | 4     | 7B85836A46 |
| Crucial    | CT102464BA160B.... | 8192 MB  | DDR3 | 1333 | 3     | EF6B630DDD |
|            | Module DIMM        | 2048 MB  | DDR2 | 667  | 3     | C7EA6CABCA |
|            | Module DIMM SDRAM  | 512 MB   |      |      | 3     | 1F098AC490 |
| Samsung    | M471A1K43CB1-CR... | 8192 MB  | DDR4 | 2400 | 3     | 2D0DC32CED |
| Samsung    | M471B5173DB0-YK... | 4096 MB  | DDR3 | 1600 | 3     | 56D1B97DC1 |
| Kingston   | 99U5428-042.A00... | 4096 MB  | DDR3 | 1334 | 2     | 6394AE37A8 |
|            | Module SODIMM DDR  | 1024 MB  |      |      | 2     | 1BCC2B8E0B |
|            | Module SODIMM      | 1024 MB  | DDR2 |      | 2     | EE60EB3DC8 |
|            | Module DIMM SDRAM  | 1024 MB  |      |      | 2     | 1F098AC490 |
|            | Module DIMM        | 2048 MB  | DDR2 |      | 2     | EE60EB3DC8 |
|            | Module DIMM        | 2048 MB  | DDR2 | 800  | 2     | C2067BB99A |
|            | Module DIMM        | 4096 MB  |      | 1333 | 2     | D99AE1AAD1 |
|            | Module DIMM        | 8192 MB  |      | 1066 | 2     | 66BBED8D59 |
| Samsung    | M393A2K40BB2-CT... | 16384 MB | DDR4 | 2666 | 2     | 1DB4784753 |
| Samsung    | M471B5273DH0-CH... | 4096 MB  | DDR3 | 1334 | 2     | 0087B62853 |
|            | Module DIMM DDR    | 2048 MB  |      | 800  | 1     | E8BED535A9 |
|            | Module DIMM DDR    | 1024 MB  |      | 800  | 1     | E8BED535A9 |
| A-DATA     | DDR4 3000 DIMM     | 16384 MB | DDR4 | 3000 | 1     | B4C4C676C4 |
| A-DATA     | MI64C1D1629Z1 DIMM | 8192 MB  | DDR3 | 1333 | 1     | 0F7697B73A |
| Corsair    | CM3X4GSD1066 SO... | 4096 MB  | DDR3 | 1066 | 1     | 0087B62853 |
| Corsair    | CMK16GX4M1A2666... | 16384 MB | DDR4 | 2666 | 1     | C7C50D64CF |
| Corsair    | CMK16GX4M2Z2666... | 8192 MB  |      | 2666 | 1     | 20FAC3B208 |
| Corsair    | CMK32GX4M2A2666... | 16384 MB |      | 2666 | 1     | 7C311EE004 |
| Corsair    | CMK32GX4M2B3200... | 16384 MB |      | 2933 | 1     | 44681211FF |
| Corsair    | CMSO8GX3M1A1600... | 8192 MB  | DDR3 | 1600 | 1     | 04CD35A77B |
| Corsair    | CMSX8GX3M1A1600... | 8192 MB  | DDR3 | 1333 | 1     | C240E3A1EA |
| Corsair    | CMV8GX3M1A1600C... | 8192 MB  | DDR3 | 1333 | 1     | 94C4617D4E |
| Corsair    | CMX8GX3M2A1600C... | 4096 MB  | DDR3 | 667  | 1     | EB5651F31C |
| Corsair    | CMZ16GX3M4A1600... | 4096 MB  | DDR3 | 1333 | 1     | 0F7697B73A |
| Crucial    | BLS4G3D1609DS1S... | 4096 MB  | DDR3 | 800  | 1     | EB5651F31C |
| Crucial    | BLS4G4D240FSE.8... | 4096 MB  | DDR4 | 2400 | 1     | A49CF5C20B |
| Crucial    | BLS8G3D1609DS1S... | 8192 MB  | DDR3 | 1333 | 1     | 9FEA968A19 |
| Crucial    | BLS8G4D240FSA.1... | 8192 MB  | DDR4 | 2400 | 1     | 2FC2952380 |
| Crucial    | BLS8G4D240FSEK.... | 8192 MB  | DDR4 | 2400 | 1     | 0D931FF2A1 |
| Crucial    | CT102464BF160B.... | 8192 MB  | DDR3 | 1600 | 1     | 90E967F56B |
| Crucial    | CT16G4SFD824A.C... | 16384 MB | DDR4 | 2133 | 1     | 6B854263E7 |
| Crucial    | CT8G4SFD8213.C1... | 8192 MB  | DDR4 | 2133 | 1     | 1A7976D306 |
| CSX        | V01D3SF8GB52852... | 8192 MB  | DDR3 | 1333 | 1     | 7C8A68918A |
| G.Skill    | F4-3000C16-8GIS... | 8192 MB  | DDR4 | 2133 | 1     | AA58B291B3 |
| GOODRAM    | GR1600S3V64L11/... | 8192 MB  | DDR3 | 1600 | 1     | B38C2A2E8F |
| Hewlett... | 669238-071 DIMM    | 4096 MB  | DDR3 | 1600 | 1     | AEA3696F41 |
| SK Hynix   | HMA81GS6AFR8N-U... | 8192 MB  | DDR4 | 2400 | 1     | 310BD9E4AF |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1333 | 1     | A95465CDDA |
| SK Hynix   | HMT41GU6BFR8C-P... | 8192 MB  | DDR3 | 1600 | 1     | 81F39F3061 |
| SK Hynix   | HMT41GU6MFR8C-P... | 8192 MB  | DDR3 | 1600 | 1     | 81F39F3061 |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 1     | A7761EE829 |
| SK Hynix   | HMT451S6MFR8C-P... | 4096 MB  | DDR3 | 1600 | 1     | 8060B3FFE1 |
| SK Hynix   | HMT31GR7CFR4C-P... | 8192 MB  | DDR3 | 1600 | 1     | AAC1EEB66A |
| Kingston   | 9905402-544.A00... | 4096 MB  | DDR3 | 1333 | 1     | D65F5372EC |
| Kingston   | 9905403-518.A00... | 8192 MB  | DDR3 | 1600 | 1     | 33782EF7F1 |
| Kingston   | 9905471-074.A DIMM | 8192 MB  | DDR3 | 1600 | 1     | 09BFDEAFBD |
| Kingston   | 9905624-026.A00... | 8192 MB  | DDR4 | 2400 | 1     | D910596224 |
| Kingston   | 9905630-066.A00... | 16384 MB | DDR4 | 2667 | 1     | 96FCD8FC28 |
| Kingston   | 9965426-037.A00... | 4096 MB  |      | 1333 | 1     | 6B7FBA08DD |
| Kingston   | 9965433-154.A00... | 8192 MB  | DDR3 | 1333 | 1     | 1F4D1E4607 |
| Kingston   | 9965525-058.A00... | 8192 MB  | DDR3 | 1333 | 1     | 6CF7F9EA4B |
| Kingston   | 99U5403-034.A00... | 4096 MB  | DDR3 | 1333 | 1     | 4620A00CCC |
| Kingston   | 99U5403-166.A00... | 8192 MB  | DDR3 | 1600 | 1     | 33782EF7F1 |
| Kingston   | 99U5428-018.A00... | 8192 MB  | DDR3 | 1600 | 1     | BB67F0E80B |
| Kingston   | 99U5428-046.A00... | 4096 MB  | DDR3 | 1333 | 1     | 9728D93191 |
| Kingston   | 99U5469-041.A00... | 4096 MB  | DDR3 | 1333 | 1     | 2B357D5FA1 |
| Kingston   | 99U5471-020.A00... | 4096 MB  | DDR3 | 1333 | 1     | 4620A00CCC |
| Kingston   | 99U5471-039.A DIMM | 8192 MB  | DDR3 | 1600 | 1     | 09BFDEAFBD |
| Kingston   | 99U5474-028.A00... | 4096 MB  | DDR3 | 1333 | 1     | 5D38B05178 |
| Kingston   | 99U5584-010.A00... | 4096 MB  | DDR3 | 1333 | 1     | 4620A00CCC |
| Kingston   | ACR16D3LS1KFG/4... | 4096 MB  | DDR3 | 1600 | 1     | 6CB240A9F6 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 1     | DB03BEF1C6 |
| Kingston   | KHX1600C9S3L/8G... | 8192 MB  | DDR3 | 1600 | 1     | 07036EAB43 |
| Kingston   | KHX2400C11D3/8G... | 8192 MB  | DDR3 | 2400 | 1     | 9F0AD7BBCF |
| Kingston   | KHX2400C15S4/16... | 16384 MB | DDR4 | 2400 | 1     | 9649F2D700 |
| Kingston   | KHX3000C15/16GX... | 16384 MB | DDR4 | 2400 | 1     | 29DBE3892C |
| Kingston   | Module DIMM        | 1024 MB  | DDR2 | 667  | 1     | 9A893E2CC9 |
| Micron     | 16ATF1G64HZ-2G1... | 8192 MB  | DDR4 | 2133 | 1     | 1A7976D306 |
| Micron     | 16ATF2G64HZ-3G2... | 16384 MB | DDR4 | 3200 | 1     | 528E378206 |
| Micron     | 18ASF2G72AZ-2G1... | 16384 MB | DDR4 | 2133 | 1     | 360E63CC66 |
| Micron     | 18ASF2G72HZ-2G6... | 16384 MB | DDR4 | 2667 | 1     | AA891D8F27 |
| Micron     | 18KSF1G72AZ-1G6... | 8192 MB  | DDR3 | 1600 | 1     | DEA751EDF7 |
| Micron     | 8JTF12864AZ-1G4... | 1024 MB  | DDR3 | 1333 | 1     | 534617FE54 |
| Micron     | MT52L512M32D2PF... | 4096 MB  |      | 1867 | 1     | 4199E37B56 |
| Nanya      | NT4GC64B8HG0NS-... | 4096 MB  | DDR3 | 1067 | 1     | 6A6B06FC67 |
|            | Module DIMM        | 1024 MB  |      | 1333 | 1     | C06E03CDA0 |
|            | Module DIMM        | 1024 MB  | DDR2 | 667  | 1     | 4EBC960E9C |
|            | Module DIMM SDRAM  | 1024 MB  |      | 266  | 1     | 6B65FCF9C1 |
|            | Module DIMM SDR... | 1024 MB  |      | 266  | 1     | 0D292BCA2F |
|            | Module DIMM        | 2048 MB  |      | 1066 | 1     | CC5724ACBC |
|            | Module DIMM        | 2048 MB  |      | 667  | 1     | 66BCE86F33 |
|            | Module DIMM DDR    | 2048 MB  |      | 667  | 1     | 8F72D18BFF |
|            | Module DIMM DDR    | 2048 MB  |      | 800  | 1     | CF6ACC34AC |
|            | Module SODIMM RAM  | 2048 MB  |      |      | 1     | 1E5D0A4D7A |
|            | Module DIMM SDRAM  | 2048 MB  |      |      | 1     | 2FD46CB7C7 |
|            | Module DIMM        | 4096 MB  | DDR2 | 667  | 1     | 97732C8106 |
|            | Module DIMM        | 512 MB   |      | 667  | 1     | 59E3624DE7 |
|            | Module SODIMM DDR  | 512 MB   |      |      | 1     | 1E849F86CF |
|            | Module DIMM        | 512 MB   | DDR2 |      | 1     | 3984F45545 |
|            | Module DIMM        | 8192 MB  |      | 1333 | 1     | C06E03CDA0 |
|            | Module DIMM        | 8192 MB  |      | 400  | 1     | E7F015C6DA |
|            | Module DIMM        | 8192 MB  | DDR3 | 1600 | 1     | AEA3696F41 |
| Samsung    | K4EBE304EB-EGCF... | 8192 MB  |      | 1867 | 1     | BB2FCF8D92 |
| Samsung    | K4EBE304EE-EGCF... | 8192 MB  |      | 1867 | 1     | 68840C222B |
| Samsung    | M378A4G43MB1-CT... | 32 GB    | DDR4 | 2666 | 1     | C039FF6AB2 |
| Samsung    | M391B5173QH0-YK... | 4096 MB  | DDR3 | 1600 | 1     | DEA751EDF7 |
| Samsung    | M391B5273DH0-YH... | 4096 MB  | DDR3 | 1333 | 1     | 6CF7F9EA4B |
| Samsung    | M393B1G70BH0-YK... | 8192 MB  | DDR3 | 1600 | 1     | AAC1EEB66A |
| Samsung    | M393B1G73QH0-YK... | 8192 MB  | DDR3 | 1600 | 1     | E2AB2682CB |
| Samsung    | M393B1K70BH1-CH... | 8192 MB  | DDR3 | 1333 | 1     | B43DB1D84E |
| Samsung    | M393B1K70DH0-YK... | 8192 MB  | DDR3 | 1600 | 1     | AAC1EEB66A |
| Samsung    | M471A1G43DB0-CP... | 8192 MB  | DDR4 | 2133 | 1     | DFD9A97EFC |
| Samsung    | M471A1K43CB1-CT... | 8192 MB  |      | 2667 | 1     | 010DB0AED4 |
| Samsung    | M471A5244CB0-CR... | 4096 MB  | DDR4 | 2133 | 1     | 709A3DB7DE |
| Samsung    | M471B1G73DB0-YK... | 8192 MB  | DDR3 | 1600 | 1     | 79EC87B2DB |
| Samsung    | M471B5173BH0-CK... | 4096 MB  | DDR3 | 1600 | 1     | EAB6164233 |
| Samsung    | M471B5173CB0-YK... | 4096 MB  | DDR3 | 1600 | 1     | 7042848932 |
| Samsung    | M471B5173QH0-YK... | 4096 MB  | DDR3 | 1600 | 1     | 9A751DDFD8 |
| Samsung    | M471B5174BM0-YH... | 4096 MB  | DDR3 | 1333 | 1     | 8ED0FEE673 |
| Samsung    | M471B5773CHS-CH... | 2048 MB  | DDR3 | 1333 | 1     | 9728D93191 |
| Samsung    | Module SODIMM      | 8192 MB  | DDR4 | 2133 | 1     | 6C7374D0AB |
| SK Hynix   | H9CCNNNBJTMLAR-... | 4096 MB  |      | 1867 | 1     | 1887B030C4 |
| SK Hynix   | HMA81GU7AFR8N-U... | 8192 MB  | DDR4 | 2400 | 1     | E59AEBEE71 |
| SK Hynix   | HMA82GR7JJR8N-V... | 16384 MB | DDR4 | 2667 | 1     | B44FE94131 |
| SK Hynix   | HMA82GS6CJR8N-V... | 16384 MB | DDR4 | 2133 | 1     | 7DEF094AFB |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1067 | 1     | 239EEA83C6 |
| SK Hynix   | Module SODIMM      | 4096 MB  | DDR3 | 1333 | 1     | DC34D6FD02 |

### Battery

| MFG        | Name          | Wh    | Type    | Count | Probe      |
|------------|---------------|-------|---------|-------|------------|
| Hewlett... | Primary LIon  | 4     |         | 3     | 6C7374D0AB |
| LGC        | 45N1738 LION  | 71.1  |         | 2     | DFD9A97EFC |
| SANYO      | 45N1037 LION  | 44.0  |         | 2     | F4E8FFB5DC |
| ASUSTEK    | Z943222       | 47.3  |         | 1     | 1F098AC490 |
| BYD        | DELL GW0K9... | 8.5   |         | 1     | AA891D8F27 |
| LGC        | 45N1005 LION  | 47.5  |         | 1     | 05ED5EB1E4 |
| LGC        | L16L2PB2 LiP  | 30.0  |         | 1     | 709A3DB7DE |
| LGC-LGC... | DELL RNP72... | 7.9   |         | 1     | 4199E37B56 |
| Notebook   | BAT LION      | 3     |         | 1     | 9649F2D700 |
| Notebook   | BAT LION      | 6     |         | 1     | 96FCD8FC28 |
| Panasonic  | 45N1143 LION  | 38.9  |         | 1     | EAB6164233 |
| PANASONIC  | AS10B5E LION  | 6.0   |         | 1     | 239EEA83C6 |
| SANYO      | 42T4940 LION  | 86.6  |         | 1     | E8A2F44B21 |
| SANYO      | 45N1001 LION  | 5.6   |         | 1     | 0087B62853 |
| SANYO      | 45N1023 LION  | 93.2  |         | 1     | A95465CDDA |
| SANYO      | 45N1172 LION  | 62.6  |         | 1     | 8060B3FFE1 |
| SANYO      | 45N1767 LION  | 47.5  |         | 1     | C65CDB97DE |
| SANYO      | 45N1769 LION  | 56.2  |         | 1     | 79EC87B2DB |
| SANYO      | 45N1773 LION  | 23.2  |         | 1     | 7DEF094AFB |
| SANYO      | 92P1137 LION  | 71.3  |         | 1     | EE60EB3DC8 |
| Sanyo      | DELL 911MD... | 4.4   |         | 1     | 7C8A68918A |
| Sanyo      | DELL JXK73... | 9.0   |         | 1     | 04CD35A77B |
| SANYO      | L09S6Y02 LION | 38.9  |         | 1     | 9728D93191 |
| Simplo     | SDI ICR186... | 3.4   |         | 1     | DC7BB56859 |
| SMP        | 00HW029 LiP   | 52.1  |         | 1     | 68840C222B |
| SMP        | 00NY493 LiP   | 90.0  |         | 1     | 81EFA4B3D3 |
| SMP        | 01AV430 LiP   | 57.0  |         | 1     | BB2FCF8D92 |
| SMP        | 45N1071 LiP   | 46.0  |         | 1     | 8ED0FEE673 |
| SMP        | DELL 7V69Y... | 8.2   |         | 1     | 1A7976D306 |
| SMP        | DELL TP1GT... | 7.9   |         | 1     | 1887B030C4 |
| SMP-SDI2.8 | DELL FW1MN... | 2.8   |         | 1     | B38C2A2E8F |
| Sony       | 45N1111 LiP   | 23.2  |         | 1     | C65CDB97DE |
| Sony       | 93P5030 LION  | 74.9  |         | 1     | F08ACC6929 |
| Sony       | PABAS024 LION | 47.5  |         | 1     | F1C2BCAE9D |
| Sony       | VGP-BPS26 ... | 43.2  |         | 1     | 9A751DDFD8 |

