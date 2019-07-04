# govhk_election_reports

provide gov hk election reports in a computer friendly format

## Setup dev machine


```
npm install
```


## Validate json using schema

```
./scripts/ajv.sh
```


## Glossary

```
EAC 選管會
RO 選舉主任
ICAC 廉政公署
PROs 投票站主任
DPSs 懲教院所
```

## TODO

### Tech

- [X] Json Schema validation at git commit


### Data Structure Planning

Other Data Sources to be Reviewed
- [ ] https://data.gov.hk/en-datasets/search/election%20result
- [ ] https://zh.wikipedia.org/wiki/2018%E5%B9%B411%E6%9C%88%E9%A6%99%E6%B8%AF%E7%AB%8B%E6%B3%95%E6%9C%83%E4%B9%9D%E9%BE%8D%E8%A5%BF%E5%9C%B0%E6%96%B9%E9%81%B8%E5%8D%80%E8%A3%9C%E9%81%B8
- [ ] include complaints breakdown
- [ ] include candidate application details
  - DQ-ed
  - withdraw application
- [ ] include 獲准進行票站調查的人士和機構的名單
- [ ]

### Data Sources

#### Legco

2018 LCBE KW
- [X] extract data from https://www.eac.hk/en/legco/2018lcbe_kw_detailreport.htm
- [ ] extract candidate application data from https://www.elections.gov.hk/legco2018kwby/chi/nominat.html?1562211985539

2018 LCBE
- [X] extract data from https://www.eac.hk/pdf/legco/2018lcbe_report/en/2018lcbe_full_report(Eng).pdf

2016 LCE
- [ ] extract data from https://www.eac.hk/pdf/legco/2016LCE_Report/ch/2016lce_full_report.pdf

2016 LCBE NTE
- [ ] extract data from https://www.eac.hk/pdf/legco/2016lcbe_nte_report/ch/2016lcbe_nte_full_report.pdf

2012 LCE
- [ ] extract data from https://www.eac.hk/ch/legco/2012lce_detailreport.htm

2010 LCBE
- [ ] extract data from https://www.eac.hk/ch/legco/2010lcbe_detailreport.htm

2008 LCE
- [ ] extract data from https://www.eac.hk/ch/legco/2008lce_report1.htm

2007 LCBE
- [ ] extract data from https://www.eac.hk/ch/legco/2007lcbe_hki_detailreport.htm

2004 LCE
- [ ] extract data from https://www.eac.hk/ch/legco/2004_report1.htm

2001 LCBE
- [ ] extract data from https://www.eac.hk/ch/legco/2001_report.htm

2000 LCBE
- [ ] extract data from https://www.eac.hk/ch/legco/2000_report_2.htm

2000 LCE
- [ ] extract data from https://www.eac.hk/ch/legco/2000_report.htm

1998 LCE
- [ ] extract data from https://www.info.gov.hk/chinfo/98eac-c.htm

#### Distco

##### District map

- [ ] https://www.eac.hk/ch/distco/2019dc_boundary.htm
- [ ] https://www.eac.hk/ch/distco/2015dc_boundary.htm
- [ ] https://www.eac.hk/ch/distco/2011dc_boundary.htm
- [ ] https://www.eac.hk/ch/distco/2007dc_boundary.htm
- [ ] https://www.eac.hk/ch/distco/2003dc_boundary.htm
- [ ] https://www.eac.hk/ch/distco/boundary.htm

##### Election Result

https://www.eac.hk/ch/distco/dce.htm

- [ ] 2019年元朗區議會補選
- [ ] 2019年油尖旺區議會大南選區補選
- [ ] 2018年東區區議會佳曉選區補選
- [ ] 2017年中西區區議會補選
- [ ] 2015年區議會一般選舉
- [ ] 2015年大埔區議會新富選區補選
- [ ] 2014年離島區議會坪洲及喜靈洲選區補選
- [ ] 2014年東區區議會南豐選區補選
- [ ] 2014年離島區議會東涌北選區補選
- [ ] 2014年南區區議會海怡西選區補選
- [ ] 2013年油尖旺區議會京士柏選區補選
- [ ] 2013年觀塘區議會坪石選區補選
- [ ] 2013年沙田區議會田心選區補選
- [ ] 2012年沙田區議會鞍泰選區補選
- [ ] 2011年區議會選舉
- [ ] 2011年荃灣區議會福來選區補選
- [ ] 2011年元朗區議會十八鄉北選區補選
- [ ] 2010年南區區議會薄扶林選區補選
- [ ] 2009年葵青區議會葵盛東邨選區補選
- [ ] 2009年灣仔區議會鵝頸選區補選
- [ ] 2009年沙田區議會大圍選區補選
- [ ] 2008年黃大仙區議會慈雲西選區補選
- [ ] 2008年油尖旺區議會佐敦東選區補選
- [ ] 2007年區議會選舉
- [ ] 2007年九龍城區議會紅磡灣選區補選
- [ ] 2007年大埔區議會康樂園選區補選
- [ ] 2007年觀塘區議會啓業選區補選
- [ ] 2007年沙田區議會錦英選區補選
- [ ] 2006年東區區議會翠灣選區補選
- [ ] 2006年中西區區議會正街選區補選
- [ ] 2005年觀塘區議會景田選區補選
- [ ] 2005年南區區議會鴨脷洲北選區補選
- [ ] 2005年深水埗區議會南昌中選區補選
- [ ] 2005年東區區議會堡壘選區補選
- [ ] 2004年南區區議會田灣選區補選
- [ ] 2003年區議會選舉
- [ ] 2003年深水埗區議會麗閣選區補選
- [ ] 2003年深水埗區議會美孚選區補選
- [ ] 2003年九龍城區議會海心選區補選
- [ ] 2002年九龍城區議會啟德選區補選
- [ ] 2000年北區區議會鳳翠選區補選
- [ ] 1999年區議會選舉

#### Rural

https://www.eac.hk/ch/rural/rre.htm

#### Age and Sex distribution

- [ ] https://www.voterregistration.gov.hk/chi/statistic2018.html
- [ ] https://www.voterregistration.gov.hk/chi/statistic2017.html
- [ ] https://www.eac.hk/ch/legco/lce.htm