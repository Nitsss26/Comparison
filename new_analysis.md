# Final Analysis Report: Missing Student Data Stats

# Enrollment Data Analysis

## Executive Summary Table

Reference: **Total** <br> M:Missing Mobile, E:Missing Email, B:Missing Both

| Category | Year | Course | BETUL | BHOPAL | HARDA | HOSHANGABAD | RAISEN | RAJGARH | SEHORE | VIDISHA |
|:---|:---:|:---:| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Admission | 2022 | PG | - | **26016**<br>M:5497 E:20211 B:5497 | **3033**<br>M:1998 E:2806 B:1998 | **5254**<br>M:3200 E:4760 B:3200 | **4027**<br>M:1621 E:2973 B:1621 | **3286**<br>M:2056 E:2886 B:2056 | **4082**<br>M:2192 E:3449 B:2192 | **5638**<br>M:3379 E:4871 B:3379 |
| Admission | 2022 | UG | - | **25151**<br>M:14310 E:15599 B:14310 | **4455**<br>M:2016 E:2172 B:2016 | **10683**<br>M:3173 E:4148 B:3173 | **8190**<br>M:4043 E:4409 B:4043 | **10141**<br>M:4197 E:5217 B:4197 | **12890**<br>M:5398 E:5951 B:5398 | **11024**<br>M:3744 E:4217 B:3744 |
| Admission | 2023 | PG | **5081**<br>M:1139 E:1231 B:1139 | **27095**<br>M:4278 E:9359 B:4278 | **2931**<br>M:860 E:1162 B:860 | **5291**<br>M:1135 E:1497 B:1135 | **4152**<br>M:573 E:1223 B:573 | **2820**<br>M:699 E:880 B:699 | **4558**<br>M:1032 E:1521 B:1032 | **5597**<br>M:1440 E:1803 B:1440 |
| Admission | 2023 | UG | **10347**<br>M:3770 E:3925 B:3770 | **26610**<br>M:14449 E:15028 B:14449 | **4745**<br>M:1779 E:1888 B:1779 | **10628**<br>M:2591 E:3268 B:2591 | **8288**<br>M:2861 E:3118 B:2861 | **10704**<br>M:3749 E:4691 B:3749 | **14501**<br>M:4919 E:5253 B:4919 | **11848**<br>M:2736 E:3071 B:2736 |
| Admission | 2024 | PG | **4318**<br>M:0 E:853 B:0 | **23040**<br>M:0 E:15129 B:0 | **2154**<br>M:0 E:764 B:0 | **3709**<br>M:0 E:1007 B:0 | **3695**<br>M:0 E:2045 B:0 | **2054**<br>M:0 E:579 B:0 | **3464**<br>M:0 E:1336 B:0 | **4400**<br>M:0 E:1550 B:0 |
| Admission | 2024 | UG | **10037**<br>M:0 E:436 B:0 | **23786**<br>M:10 E:2704 B:10 | **3846**<br>M:0 E:148 B:0 | **10262**<br>M:0 E:761 B:0 | **7801**<br>M:0 E:441 B:0 | **9134**<br>M:0 E:1302 B:0 | **12169**<br>M:0 E:579 B:0 | **9461**<br>M:0 E:217 B:0 |
| Enrollment | 2022 | PG | - | **26033**<br>M:5502 E:20236 B:5502 | **3038**<br>M:2002 E:2811 B:2002 | **5262**<br>M:3209 E:4770 B:3209 | **4029**<br>M:1622 E:2976 B:1622 | **3285**<br>M:2051 E:2886 B:2051 | **4087**<br>M:2197 E:3454 B:2197 | **5640**<br>M:3384 E:4873 B:3384 |
| Enrollment | 2022 | UG | - | **25144**<br>M:14305 E:15591 B:14305 | **4455**<br>M:2016 E:2172 B:2016 | **10683**<br>M:3174 E:4148 B:3174 | **8190**<br>M:4043 E:4409 B:4043 | **10141**<br>M:4197 E:5217 B:4197 | **12892**<br>M:5400 E:5953 B:5400 | **11025**<br>M:3745 E:4218 B:3745 |
| Enrollment | 2023 | PG | **5082**<br>M:1141 E:1233 B:1141 | **27119**<br>M:4286 E:9382 B:4286 | **2928**<br>M:857 E:1159 B:857 | **5297**<br>M:1140 E:1502 B:1140 | **4153**<br>M:572 E:1224 B:572 | **2818**<br>M:698 E:878 B:698 | **4560**<br>M:1034 E:1526 B:1034 | **5596**<br>M:1439 E:1802 B:1439 |
| Enrollment | 2023 | UG | **10346**<br>M:3770 E:3924 B:3770 | **26605**<br>M:14448 E:15024 B:14448 | **4745**<br>M:1779 E:1888 B:1779 | **10628**<br>M:2591 E:3268 B:2591 | **8289**<br>M:2862 E:3119 B:2862 | **10704**<br>M:3749 E:4691 B:3749 | **14500**<br>M:4919 E:5253 B:4919 | **11849**<br>M:2736 E:3072 B:2736 |
| Enrollment | 2024 | PG | **4318**<br>M:0 E:853 B:0 | **23026**<br>M:0 E:15123 B:0 | **2152**<br>M:0 E:765 B:0 | **3710**<br>M:0 E:1008 B:0 | **3689**<br>M:0 E:2044 B:0 | **2051**<br>M:0 E:578 B:0 | **3465**<br>M:0 E:1335 B:0 | **4396**<br>M:0 E:1549 B:0 |
| Enrollment | 2024 | UG | **10037**<br>M:0 E:436 B:0 | **23788**<br>M:10 E:2704 B:10 | **3846**<br>M:0 E:148 B:0 | **10264**<br>M:0 E:762 B:0 | **7802**<br>M:0 E:441 B:0 | **9134**<br>M:0 E:1302 B:0 | **12168**<br>M:0 E:579 B:0 | **9460**<br>M:0 E:217 B:0 |
| Enrollment | 2025 | PG | **6**<br>M:0 E:0 B:0 | **160**<br>M:0 E:0 B:0 | **16**<br>M:0 E:0 B:0 | **111**<br>M:0 E:0 B:0 | **5**<br>M:0 E:0 B:0 | **31**<br>M:0 E:0 B:0 | **7**<br>M:0 E:0 B:0 | **114**<br>M:0 E:0 B:0 |
| Enrollment | 2025 | UG | **26**<br>M:0 E:0 B:0 | **9**<br>M:0 E:0 B:0 | **4**<br>M:0 E:0 B:0 | - | - | **1**<br>M:0 E:0 B:0 | **3**<br>M:0 E:0 B:0 | **3**<br>M:0 E:0 B:0 |

---


## Year: 2022

### PG

#### Location: BHOPAL

- **Total Students**: 26033
- **Missing Mobile**: 5502
- **Missing Email**: 20236
- **Missing Both (Mobile & Email)**: 5502
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 3038
- **Missing Mobile**: 2002
- **Missing Email**: 2811
- **Missing Both (Mobile & Email)**: 2002
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 5262
- **Missing Mobile**: 3209
- **Missing Email**: 4770
- **Missing Both (Mobile & Email)**: 3209
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 4029
- **Missing Mobile**: 1622
- **Missing Email**: 2976
- **Missing Both (Mobile & Email)**: 1622
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 3285
- **Missing Mobile**: 2051
- **Missing Email**: 2886
- **Missing Both (Mobile & Email)**: 2051
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 4087
- **Missing Mobile**: 2197
- **Missing Email**: 3454
- **Missing Both (Mobile & Email)**: 2197
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 5640
- **Missing Mobile**: 3384
- **Missing Email**: 4873
- **Missing Both (Mobile & Email)**: 3384
- **Missing DOB**: 0

---

### UG

#### Location: BHOPAL

- **Total Students**: 25144
- **Missing Mobile**: 14305
- **Missing Email**: 15591
- **Missing Both (Mobile & Email)**: 14305
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 4455
- **Missing Mobile**: 2016
- **Missing Email**: 2172
- **Missing Both (Mobile & Email)**: 2016
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10683
- **Missing Mobile**: 3174
- **Missing Email**: 4148
- **Missing Both (Mobile & Email)**: 3174
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 8190
- **Missing Mobile**: 4043
- **Missing Email**: 4409
- **Missing Both (Mobile & Email)**: 4043
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 10141
- **Missing Mobile**: 4197
- **Missing Email**: 5217
- **Missing Both (Mobile & Email)**: 4197
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 12892
- **Missing Mobile**: 5400
- **Missing Email**: 5953
- **Missing Both (Mobile & Email)**: 5400
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 11025
- **Missing Mobile**: 3745
- **Missing Email**: 4218
- **Missing Both (Mobile & Email)**: 3745
- **Missing DOB**: 0

---

## Year: 2023

### PG

#### Location: BETUL

- **Total Students**: 5082
- **Missing Mobile**: 1141
- **Missing Email**: 1233
- **Missing Both (Mobile & Email)**: 1141
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 27119
- **Missing Mobile**: 4286
- **Missing Email**: 9382
- **Missing Both (Mobile & Email)**: 4286
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 2928
- **Missing Mobile**: 857
- **Missing Email**: 1159
- **Missing Both (Mobile & Email)**: 857
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 5297
- **Missing Mobile**: 1140
- **Missing Email**: 1502
- **Missing Both (Mobile & Email)**: 1140
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 4153
- **Missing Mobile**: 572
- **Missing Email**: 1224
- **Missing Both (Mobile & Email)**: 572
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 2818
- **Missing Mobile**: 698
- **Missing Email**: 878
- **Missing Both (Mobile & Email)**: 698
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 4560
- **Missing Mobile**: 1034
- **Missing Email**: 1526
- **Missing Both (Mobile & Email)**: 1034
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 5596
- **Missing Mobile**: 1439
- **Missing Email**: 1802
- **Missing Both (Mobile & Email)**: 1439
- **Missing DOB**: 0

---

### UG

#### Location: BETUL

- **Total Students**: 10346
- **Missing Mobile**: 3770
- **Missing Email**: 3924
- **Missing Both (Mobile & Email)**: 3770
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 26605
- **Missing Mobile**: 14448
- **Missing Email**: 15024
- **Missing Both (Mobile & Email)**: 14448
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 4745
- **Missing Mobile**: 1779
- **Missing Email**: 1888
- **Missing Both (Mobile & Email)**: 1779
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10628
- **Missing Mobile**: 2591
- **Missing Email**: 3268
- **Missing Both (Mobile & Email)**: 2591
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 8289
- **Missing Mobile**: 2862
- **Missing Email**: 3119
- **Missing Both (Mobile & Email)**: 2862
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 10704
- **Missing Mobile**: 3749
- **Missing Email**: 4691
- **Missing Both (Mobile & Email)**: 3749
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 14500
- **Missing Mobile**: 4919
- **Missing Email**: 5253
- **Missing Both (Mobile & Email)**: 4919
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 11849
- **Missing Mobile**: 2736
- **Missing Email**: 3072
- **Missing Both (Mobile & Email)**: 2736
- **Missing DOB**: 0

---

## Year: 2024

### PG

#### Location: BETUL

- **Total Students**: 4318
- **Missing Mobile**: 0
- **Missing Email**: 853
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 23026
- **Missing Mobile**: 0
- **Missing Email**: 15123
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 2152
- **Missing Mobile**: 0
- **Missing Email**: 765
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 3710
- **Missing Mobile**: 0
- **Missing Email**: 1008
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 3689
- **Missing Mobile**: 0
- **Missing Email**: 2044
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 2051
- **Missing Mobile**: 0
- **Missing Email**: 578
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 3465
- **Missing Mobile**: 0
- **Missing Email**: 1335
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 4396
- **Missing Mobile**: 0
- **Missing Email**: 1549
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

### UG

#### Location: BETUL

- **Total Students**: 10037
- **Missing Mobile**: 0
- **Missing Email**: 436
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 23788
- **Missing Mobile**: 10
- **Missing Email**: 2704
- **Missing Both (Mobile & Email)**: 10
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 3846
- **Missing Mobile**: 0
- **Missing Email**: 148
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10264
- **Missing Mobile**: 0
- **Missing Email**: 762
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 7802
- **Missing Mobile**: 0
- **Missing Email**: 441
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 9134
- **Missing Mobile**: 0
- **Missing Email**: 1302
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 12168
- **Missing Mobile**: 0
- **Missing Email**: 579
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 9460
- **Missing Mobile**: 0
- **Missing Email**: 217
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

## Year: 2025

### PG

#### Location: BETUL

- **Total Students**: 6
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 160
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 16
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 111
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 5
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 31
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 7
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 114
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

### UG

#### Location: BETUL

- **Total Students**: 26
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 9
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 4
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 1
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 3
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 3
- **Missing Mobile**: 0
- **Missing Email**: 0
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

# Admission Data Analysis

## Year: 2022

### PG

#### Location: BHOPAL

- **Total Students**: 26016
- **Missing Mobile**: 5497
- **Missing Email**: 20211
- **Missing Both (Mobile & Email)**: 5497
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 3033
- **Missing Mobile**: 1998
- **Missing Email**: 2806
- **Missing Both (Mobile & Email)**: 1998
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 5254
- **Missing Mobile**: 3200
- **Missing Email**: 4760
- **Missing Both (Mobile & Email)**: 3200
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 4027
- **Missing Mobile**: 1621
- **Missing Email**: 2973
- **Missing Both (Mobile & Email)**: 1621
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 3286
- **Missing Mobile**: 2056
- **Missing Email**: 2886
- **Missing Both (Mobile & Email)**: 2056
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 4082
- **Missing Mobile**: 2192
- **Missing Email**: 3449
- **Missing Both (Mobile & Email)**: 2192
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 5638
- **Missing Mobile**: 3379
- **Missing Email**: 4871
- **Missing Both (Mobile & Email)**: 3379
- **Missing DOB**: 0

---

### UG

#### Location: BHOPAL

- **Total Students**: 25151
- **Missing Mobile**: 14310
- **Missing Email**: 15599
- **Missing Both (Mobile & Email)**: 14310
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 4455
- **Missing Mobile**: 2016
- **Missing Email**: 2172
- **Missing Both (Mobile & Email)**: 2016
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10683
- **Missing Mobile**: 3173
- **Missing Email**: 4148
- **Missing Both (Mobile & Email)**: 3173
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 8190
- **Missing Mobile**: 4043
- **Missing Email**: 4409
- **Missing Both (Mobile & Email)**: 4043
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 10141
- **Missing Mobile**: 4197
- **Missing Email**: 5217
- **Missing Both (Mobile & Email)**: 4197
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 12890
- **Missing Mobile**: 5398
- **Missing Email**: 5951
- **Missing Both (Mobile & Email)**: 5398
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 11024
- **Missing Mobile**: 3744
- **Missing Email**: 4217
- **Missing Both (Mobile & Email)**: 3744
- **Missing DOB**: 0

---

## Year: 2023

### PG

#### Location: BETUL

- **Total Students**: 5081
- **Missing Mobile**: 1139
- **Missing Email**: 1231
- **Missing Both (Mobile & Email)**: 1139
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 27095
- **Missing Mobile**: 4278
- **Missing Email**: 9359
- **Missing Both (Mobile & Email)**: 4278
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 2931
- **Missing Mobile**: 860
- **Missing Email**: 1162
- **Missing Both (Mobile & Email)**: 860
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 5291
- **Missing Mobile**: 1135
- **Missing Email**: 1497
- **Missing Both (Mobile & Email)**: 1135
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 4152
- **Missing Mobile**: 573
- **Missing Email**: 1223
- **Missing Both (Mobile & Email)**: 573
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 2820
- **Missing Mobile**: 699
- **Missing Email**: 880
- **Missing Both (Mobile & Email)**: 699
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 4558
- **Missing Mobile**: 1032
- **Missing Email**: 1521
- **Missing Both (Mobile & Email)**: 1032
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 5597
- **Missing Mobile**: 1440
- **Missing Email**: 1803
- **Missing Both (Mobile & Email)**: 1440
- **Missing DOB**: 0

---

### UG

#### Location: BETUL

- **Total Students**: 10347
- **Missing Mobile**: 3770
- **Missing Email**: 3925
- **Missing Both (Mobile & Email)**: 3770
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 26610
- **Missing Mobile**: 14449
- **Missing Email**: 15028
- **Missing Both (Mobile & Email)**: 14449
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 4745
- **Missing Mobile**: 1779
- **Missing Email**: 1888
- **Missing Both (Mobile & Email)**: 1779
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10628
- **Missing Mobile**: 2591
- **Missing Email**: 3268
- **Missing Both (Mobile & Email)**: 2591
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 8288
- **Missing Mobile**: 2861
- **Missing Email**: 3118
- **Missing Both (Mobile & Email)**: 2861
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 10704
- **Missing Mobile**: 3749
- **Missing Email**: 4691
- **Missing Both (Mobile & Email)**: 3749
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 14501
- **Missing Mobile**: 4919
- **Missing Email**: 5253
- **Missing Both (Mobile & Email)**: 4919
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 11848
- **Missing Mobile**: 2736
- **Missing Email**: 3071
- **Missing Both (Mobile & Email)**: 2736
- **Missing DOB**: 0

---

## Year: 2024

### PG

#### Location: BETUL

- **Total Students**: 4318
- **Missing Mobile**: 0
- **Missing Email**: 853
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 23040
- **Missing Mobile**: 0
- **Missing Email**: 15129
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 2154
- **Missing Mobile**: 0
- **Missing Email**: 764
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 3709
- **Missing Mobile**: 0
- **Missing Email**: 1007
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 3695
- **Missing Mobile**: 0
- **Missing Email**: 2045
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 2054
- **Missing Mobile**: 0
- **Missing Email**: 579
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 3464
- **Missing Mobile**: 0
- **Missing Email**: 1336
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 4400
- **Missing Mobile**: 0
- **Missing Email**: 1550
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

### UG

#### Location: BETUL

- **Total Students**: 10037
- **Missing Mobile**: 0
- **Missing Email**: 436
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: BHOPAL

- **Total Students**: 23786
- **Missing Mobile**: 10
- **Missing Email**: 2704
- **Missing Both (Mobile & Email)**: 10
- **Missing DOB**: 0

---

#### Location: HARDA

- **Total Students**: 3846
- **Missing Mobile**: 0
- **Missing Email**: 148
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: HOSHANGABAD

- **Total Students**: 10262
- **Missing Mobile**: 0
- **Missing Email**: 761
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAISEN

- **Total Students**: 7801
- **Missing Mobile**: 0
- **Missing Email**: 441
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: RAJGARH

- **Total Students**: 9134
- **Missing Mobile**: 0
- **Missing Email**: 1302
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: SEHORE

- **Total Students**: 12169
- **Missing Mobile**: 0
- **Missing Email**: 579
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

#### Location: VIDISHA

- **Total Students**: 9461
- **Missing Mobile**: 0
- **Missing Email**: 217
- **Missing Both (Mobile & Email)**: 0
- **Missing DOB**: 0

---

