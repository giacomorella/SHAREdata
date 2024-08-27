## SHARE DATA ##

I report here the core module we need to extract, together with the core variables. I start by reporting them wave by wave, so that we can highlight the variable definitions, harmonization, and differences across waves.

## Wave 1 ##

Variables common to all modules

| Symbol | Description (label) | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| mergeid | Row 1, Col 2 |  | mergeid|
| hhidpn1 | Row 2, Col 2 |  | hhid1|
| country | Row 3, Col 2 |  |country|
| waveid | Row 3, Col 2 |  | waveid|
| language | Row 3, Col 2 |  |language|

Module CV: COVERSCREEN ON INDIVIDUAL LEVEL (CV_R)

| Symbol | Description  | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| hhsize | Household size |   Numeric | hhsize  |
| age2004 | Age in 2004 |    Numeric| age2004 |
| rsex | Gender |  male = 1, female = 0 | gender |
| ... |   | |   | 

Module DN: DEMOGRAPHIC MODULE (DN)

| Symbol | Description  | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| rbyear | Birth year  | Numeric | dn003_  |
| rbmonth | Month of birth   |  Numeric| dn002_ |
| rnat |  Born in country |  | dn004_ |
| riyear |   Year immigrated | Numeric | dn006_ |
| rcit | Citizen of country  |  | dn007_ |
| redu | Education | |   dn010_ |
| rmar | Marital status  | married/partner = 1 <br>  divorced/separated = 2 <br>  widowed = 3 <br> never married = 4  | dn014_  = 1, 2, 3  <br> dn014_  = 5 <br> dn014_  = 6 <br> dn014_  = 4|


Module EP: EMPLOYMENT AND PENSIONS MODULE (EP)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| ret | Retirement |    retired = 1 <br> not retired = 0 | ep005_ = 1 <br> ep005_ != 1 |
| rwork | Working for pay   |  working for pay = 1 <br> not working for pay = 0| ep002_=1 \| ep005_=2 \| ep003_=1 <br> ep002_ = 0 \| ep005_=1 \| ep005_=3 \| ep005_=4 \| ep005_=5 \| ep002_=5 \| ep003_=0 |
| rlbrf | Labor force status  | working = 1 <br> disabled = 2 <br> unemp = 3 <br> not working = 4 | rwork = 1 <br> rlbrf = 0 \& ep005_ = 4  <br> rlbrf=0 \& ep005_=3  <br> rlbrf=0 \& rwork=0 |
| rself | Self employed in main job |  self employedin main job = 1  | ep009_1 = 3 |
| ep104_1 | Retir. age: public old age | | retag_c1 |
| ep104_2 | Retir. age: public early retirement | | retag_c2 |
| ep104_3 | Retir. age: public disability | | retag_c3 |
| ep104_4 | Retir. age: sickness, invalidity | | retag_c4 |
| ep104_5 | Retir. age: priv. occup. old age | | retag_c5 |
| ep104_6 | Retir. age: priv. occup. early retir. | | retag_c5 |
| ep105_1 | Early ret. possibility: public old age | | earlyret_c1 |
| ep105_2 | Early ret. possibility: public early ret.  | | earlyret_c2 |
| ep105_3 | Early ret. possibility: public disability | | earlyret_c3 |
| ep105_4 | Early ret. possibility: sickness, invalidity | | earlyret_c4 |
| ep105_5 | Early ret. possibility: priv. occup. old age | | earlyret_c5 |
| ep105_6 | Early ret. possibility: priv. occup. early retir. | | earlyret_c6 |	
| ep106_1 | Exp. age collection: public old age | | retagexp_c1 |
| ep106_2 | Exp. age collection: public early ret.  | | retagexp_c2 |
| ep106_3 | Exp. age collection: public disability | | retagexp_c3 |
| ep106_4 | Exp. age collection: sickness, invalidity | | retagexp_c4 |
| ep106_5 | Exp. age collection: priv. occup. old age | | retagexp_c5 |
| ep106_6 | Exp. age collection: priv. occup. early retir. | | retagexp_c6 |	


Module EP: FINANCIAL TRANFERS (FT)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| ever_inher | Ever received gift/inheritance (>5k)  | refusal=-2 <br> don't know=-1 <br> yes=1 <br> no=5| ft015=-2 <br> ft015=-1 <br> ft015=1 <br> ft015=5 |	
| year_1inher | Year received gift/inheritance 1 | Numeric | ft016_1 |	
| year_2inher | Year received gift/inheritance 2 | Numeric | ft016_2 |	
| year_3inher | Year received gift/inheritance 3 | Numeric | ft016_3 |	
| year_4inher | Year received gift/inheritance 4 | Numeric | ft016_4 |	
| year_5inher | Year received gift/inheritance 5 | Numeric| ft016_5 |	
| value_1inher | Value received gift/inheritance 1 | Numeric | ft018e_1 |	
| value_2inher | Value received gift/inheritance 2 | Numeric| ft018e_2 |	
| value_3inher | Value received gift/inheritance 3 | Numeric| ft018e_3 |	
| value_4inher | Value received gift/inheritance 4 | Numeric| ft018e_4 |	
| value_5inher | Value received gift/inheritance 5 | Numeric | ft018e_5 |	

Module HO: HOUSING (HO)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| ho_status | Housing status  | owner=1 <br> tenant/subtenant=2 <br> cooperative=3 <br> rent free/usufruct=4| ho002_=1 <br> ho002_=2 \| ho002_=4<br> ho002_=3 <br> ho002_=5 \| ho002_=6 |	
| how_property | How property acquired |  | ho011_ |	
| year_property | Year acquired property |  | ho012_ |	
| loan_property | Mortgages/loans on property | yes=1 <br> no=2| ho013_=1 <br> ho013_=5|	
| value_property1 | Value of property | Numeric  | ho024e |	
| status_property2 | Own other real estate | yes=1 <br> no=2| ho026_=1 <br> ho026_=5|	
| value_property2 | Value of other real estate | Numeric  | ho027e |	
| income_property2 | Received income/rent of other real estate | yes=1 <br> no=2| ho029_=1 <br> ho029_=5|	
| incomev_property2 | Income/rent of other real estate last year | Numeric  | ho030e |	


Module GV_HO: GENERATED VARIABLES HOUSING (GV_HO)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| nuts1_2003 | NUTS level 1  | | nuts1_2003 |	



Module CO: CONSUMPTION (CO)

Module GV_IMPUTATIONS: IMPUTATIONS (GV_IMPUTATIONS)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| ydip |   | |  |	
| yind |   | |  |	
| ypen1 |   | |  |	
| ypen2 |   | |  |	
| ypen3 |   | |  |	
| ypen4 |   | |  |	
| ypen5 |   | |  |	
| ypen6 |   | |  |	
| yreg1 |   | |  |	
| yreg2 |   | |  |	
| ybabsmf |   | |  |	
| aftgiv |   | |  |	
| aftrec |   | |  |	
| aftinh |   | |  |	
| rhre |   | |  |	
| home |   | |  |	
| mort |   | |  |	
| ores |   | |  |	
| yrent |   | |  |	
| yaohm |   | |  |	
| otrf |   | |  |	
| fahc |   | |  |	
| fohc |   | |  |	
| telc |   | |  |	
| bacc |   | |  |	
| bsmf |   | |  |	
| slti |   | |  |	
| vbus |   | |  |	
| sbus |   | |  |	
| car |   | |  |	
| liab |   | |  |	
| thinc |   | |  |	
| thexp |   | |  |	
| hnetw |   | |  |	
| yincnrp |   | |  |	
| hrass |   | |  |	
| hgfass |   | |  |	
| gender |   | |  |	
| age |   | |  |	
| age_p |   | |  |	
| yedu_p |   | |  |	
| isced |   | |  |	
| mstat |   | |  |	
| nchild |   | |  |	
| cjs |   | |  |	
| pwork |   | |  |	
| afwork |   | |  |	
| empstat1 |   | |  |	
| empstat2 |   | |  |	
| mtoj |   | |  |	
| currency |   | |  |	
| nomx2003 |   | |  |	
| nomx2004 |   | |  |	
| nomx2005 |   | |  |	
| pppc2003 |   | |  |	
| pppc2004 |   | |  |	
| pppc2005 |   | |  |	
| pppk2004 |   | |  |	
| pppk2003 |   | |  |	
| pppk2005 |   | |  |	

    
Module WH: WEIGHTS (WH)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| cchw_w1 |   | | wghh |	
| cciw_w1 |   | | wgid |
