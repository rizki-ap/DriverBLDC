# DriverBLDC
Rancangan Motor-Driver BLDC untuk Sepeda-motor-listrik VOLTA

VERSI 0.5
Spesifikasi Input
- masukan Speed (throtle), 3-wire (+5V??, GND, 1v - 4v2 DC analog)
- masukan hall-sensor, 5-wire (+5V??, GND, hall-U, hall-V, hall-W)
- masukan "max-speed", 3 pilihan
- masukan enable
- masukan reverse
- power: 60V-DC, maks 40A
- masukan brake

Spesifikasi Output
- fasa motor BLDC, 3-wire (U,V,W), 60V, ~25A
- motor speed (pulse?), ke display/dashboard

Spesifikasi Fungsi
- mengendalikan motor BLDC, 60V (nominal), 1500W

Alternatif IC BLDC controller
https://www.mouser.co.id/datasheet/2/408/TB6586FG_datasheet_en_20160224-1115412.pdf
https://www.mouser.co.id/datasheet/2/408/TC78B042FTG_datasheet_en_20190412-1548214.pdf
https://www.mouser.co.id/datasheet/2/408/TB67B054FTG_datasheet_en_20171108-1313577.pdf
https://www.mouser.co.id/datasheet/2/408/TB6551FAG_datasheet_en_20120928-1150843.pdf
https://www.mouser.co.id/datasheet/2/348/bd63002amuv-e-1873827.pdf
https://www.mouser.co.id/datasheet/2/348/bd63001amuv-e-1873922.pdf
https://www.mouser.co.id/datasheet/2/277/MP6538-1384095.pdf
https://fscdn.rohm.com/en/products/databook/datasheet/ic/motor/brushless/bm62300muv-e.pdf
https://www.mouser.co.id/datasheet/2/348/bd63030evk-c-e-1873783.pdf
https://www.ti.com/lit/ds/symlink/uc2625-ep.pdf

Tutorial
https://www.maximintegrated.com/en/design/technical-documents/tutorials/1/1832.html
https://pdfserv.maximintegrated.com/en/an/AN1832.pdf
https://www.ti.com/lit/an/slvaf66/slvaf66.pdf
https://www.ti.com/lit/ml/slua618a/slua618a.pdf
https://www.ti.com/lit/an/slva714d/slva714d.pdf
https://www.ti.com/lit/an/slva959b/slva959b.pdf
https://www.ti.com/lit/an/slla385a/slla385a.pdf
https://www.ti.com/lit/an/slva321a/slva321a.pdf
https://www.ti.com/lit/an/slva835a/slva835a.pdf
https://www.ti.com/lit/an/slva991a/slva991a.pdf
