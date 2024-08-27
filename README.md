## Definitions of variables to construct ##

*Household or family*:

*Income*:

*Marketable wealth*: the value of a family’s easily tradable assets (namely, home equity, other real estate, financial securities, bank deposits, defined contribution wealth, and business equity) minus its nonmortgage debt (including credit card debt, vehicle loans, and student loans). Home equity is value of main residence less outstanding mortgage on main residence.

## SHARE DATA ##

I report here the core module we need to extract, together with the core variables. I start by reporting them wave by wave, so that we can highlight the variable definitions, harmonization, and differences across waves.

## Wave 1 ##

*Variables common to all modules*

| Symbol | Description (label) | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| mergeid | Person identifier *fix across modules and waves) |  | mergeid|
| hhidpn1 | Respondent ID - wave specific|  | hhid1|
| country | Country identifier |  |country|
| waveid | Identifier of original wave (person) |  | waveid |
| waveid_hh | Identifier of original wave (household) |  | waveid_hh |
| language | Row 3, Col 2 |  |language|

*Module CV: COVERSCREEN ON INDIVIDUAL LEVEL (CV_R)*

| Symbol | Description  | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| hhsize | Household size |   Numeric | hhsize  |
| age2004 | Age in 2004 |    Numeric| age2004 |
| rsex | Gender |  male = 1, female = 0 | gender |
| int_year | Interview year | Numeric | int_year  | 
| int_month | Interview month | Numeric | int_month  | 

*Module DN: DEMOGRAPHIC MODULE (DN)*

| Symbol | Description  | Content | Construction using SHARE original symbols |
|----------|----------|----------|----------|
| rbyear | Birth year  | Numeric | dn003_  |
| rbmonth | Month of birth   |  Numeric| dn002_ |
| rnat |  Born in country |  | dn004_ |
| riyear |   Year immigrated | Numeric | dn006_ |
| rcit | Citizen of country  |  | dn007_ |
| redu | Education | |   dn010_ |
| rmar | Marital status  | married/partner = 1 <br>  divorced/separated = 2 <br>  widowed = 3 <br> never married = 4  | dn014_  = 1, 2, 3  <br> dn014_  = 5 <br> dn014_  = 6 <br> dn014_  = 4|


*Module EP: EMPLOYMENT AND PENSIONS MODULE (EP)*

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


*Module EP: FINANCIAL TRANFERS (FT)*

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

*Module HO: HOUSING (HO)*

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


*Module GV_HO: GENERATED VARIABLES HOUSING (GV_HO)*

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| nuts1_2003 | NUTS level 1  | | nuts1_2003 |	


Module CO: CONSUMPTION (CO)

Module GV_IMPUTATIONS: IMPUTATIONS (GV_IMPUTATIONS)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| implicat | Implicat number | implicat = 1, 2, 3, 4, 5| implicat |
| htype | Household type | 1 = 1 S <br> 2 = 1 CNRP  <br> 3 = 1 C2R <br> 4 = 1 CNRP + 1 S <br> 5 = Multi S<br> 6 = 1 C2R + 1 S <br> 7 = 1 C2R + 1 CNRP <br> 8 = Multi C2R <br> 9 = Multi CNRP <br> 10 = Multi S + 1 C2R <br> 11 = Multi S + 1 CNRP  <br> 12 =  1 S + Multi C2R | htype |
| exrate | Exchange rate | Numeric | exrate |
| single | Single | no=1 <br> yes=1 | single |
| couple | Couple | no=1 <br> yes=1 | couple |
| partner | Partner in the couple | no=1 <br> yes=1 | partner |
| sample1 | Imputation sample for single | no=1 <br> yes=1  | sample1 |
| sample2 | Imputation sample for couples with two partners interviewed | no=1 <br> yes=1  | sample2 |
| sample3 | Imputation sample for all couples | no=1 <br> yes=1  | sample3 |
| ydip | Earnings from employment | Numeric | ydip |
| yind | Earnings from self-employment | Numeric | yind |
| ypen1 | Old age, early retirement, and survisor pensions | Numeric | ypen1 |
| ypen2 | Private and occupational pensions | Numeric| ypen2 |
| ypen3 | Disability pensions and benefits | Numeric| ypen3 |
| ypen4 | Unemployment benefits and insurances | Numeric| ypen4 |
| ypen5 | Social assistance | Numeric | ypen5 |
| ypen6 | Sickness benefits and pensions |Numeric | ypen6 |
| yreg1 | Other private pensions |Numeric | yreg1 |
| yreg2 | Private transfers | Numeric| yreg2 |
| ybabsmf | Interest/dividend from financial assett |Numeric | ybabsmf |
| y_e | Earning from employment and self-employment | Numeric | max(ydip + yind,0)  |
| y_p | Total pension income | Numeric | max(ypen1 + ypen2,0)  |
| y_px | Total pension income, incl. disability pension | | max(ypen1 + ypen2 + ypen3,0)  |
| aftgiv | Financial transfers given | Numeric | aftgiv |
| aftrec | Financial transfers received | Numeric | aftrec |
| aftinh | Inheritance received | Numeric | aftinh |
| rhre | Rent and home-related expenditures | Numeric| rhre |
| home | Value of main residence | Numeric (non-owner=0) | home |
| mort | Mortgage on main residence | Numeric | mort |
| ores | Value of other real estate - Amount | Numeric| ores |
| yrent | Income from rent | Numeric | yrent |
| yaohm | Income from other household members | Numeric| yaohm |
| otrf | Owner, tenant or rent free |  owner=1 <br> cooperative=1 <br> tenant=3 <br> subtenant=4 <br> rent-free=5 <br> usufruct=6 | otrf |
| fahc | Food at home consumption |Numeric | fahc |
| fohc | Food outside home consumption |Numeric | fohc |
| telc | Amount spent on telephones | Numeric| telc |
| bacc | Bank accounts | Numeric | bacc |
| bsmf | Bond, stock and mutual funds |Numeric | bsmf |
| slti | Savings for long-term investments | Numeric| slti |
| vbus | Value of own business | Numeric| vbus |
| sbus | Share of own business | Numeric| sbus |
| car | Value of cars | Numeric| car |
| liab | Financial liabilities | Numeric| liab |
| thinc | Total household income | ydip+ypen1+ypen2+ypen3<br> +ypen4+ypen5+ypen6+yreg1 <br>+yreg2+yind+ysrent+yaohm<br>+ybabsmf| thinc |
| thexp | Total household expenditure | rhre+fahc+fohc+hprf<br> +inpat+outpa+drugs+nurs| thexp |
| yincnrp | Income from nonresponding partner | Numeric| yincnrp |
| hrass | Household real assets | (home x perho/100) + (vbus x sbus/100) + car + ores – mort | hrass |
| hgfass | Household gross financial assets | bacc+bsmf+slti | hgfass |
| hnfass | Household net financial assets | hgfass – liab | hgfass |
| hnetw | Household net worth | hnfass + hrass| hnetw |
| gender | Gender | no=1 <br> yes=2 | gender |
| age | Age |Numeric | age |
| age_p | Age of partner | Numeric | age_p |
| yedu | Years of education | Numeric| yedu |
| yedu_p | Years of education of partner | Numeric| yedu_p |
| isced | ISCED 1997 coding of education | String | isced |
| mstat | Marital status |Married, living with spouse=1<br> Registered partnership=1<br> Married, not living with spouse=3<br> Never married=4<br> Divorced=5<br> Widowed  | mstat |
| nchild | Number of children | Numeric| nchild |
| cjs | Current job situation | Retired=1<br>Employed or self-employed=2<br>Unemployed=3<br>Permanently sick=4<br>Homemaker=5<br>Other=97| cjs |
| pwork | Did any paid work | no=1 <br> yes=2 | pwork |
| afwork | Away from work during last month | | afwork |
| empstat1 | Employee or self-employed first job | | empstat1 |
| empstat2 | Employee or self-employed second job | | empstat2 |
| mtoj | More than one job | | mtoj |
| currency | currency | | currency |
| nomx2003 | Nominal exchange rate (national currency/Euro), annual average, 2003 | | nomx2003 |
| nomx2004 | Nominal exchange rate (national currency/Euro), annual average, 2004 | | nomx2004 |
| nomx2005 | Nominal exchange rate (national currency/Euro), annual average, 2005 | | nomx2005 |
| pppc2003 | Current PPP exchange rate (national currency/Euro), 2003 | | pppc2003 |
| pppc2004 | Current PPP exchange rate (national currency/Euro), 2004 | | pppc2004 |
| pppc2005 | Current PPP exchange rate (national currency/Euro), 2005 | | pppc2005 |
| pppk2004 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2004 | | pppk2004 |
| pppk2003 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2003 | | pppk2003 |
| pppk2005 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2005 | | pppk2005 |



    
Module WH: WEIGHTS (WH)

| Symbol | Description  | Content | Construction using SHARE original or new symbols |
|----------|----------|----------|----------|
| cchw_w1 |   | | wghh |	
| cciw_w1 |   | | wgid |
