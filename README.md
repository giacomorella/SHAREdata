## Definitions of variables to construct ##

*Household or family*:

*Income*:

*Marketable wealth*: the value of a family’s easily tradable assets (namely, home equity, other real estate, financial securities, bank deposits, defined contribution wealth, and business equity) minus its nonmortgage debt (including credit card debt, vehicle loans, and student loans). Home equity is value of main residence less outstanding mortgage on main residence.

## SHARE DATA ##

Level capture whether the variable refers to the individual respondent or the family (work in progress).

# Interview information #
| Name | Label | Level | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| wave | Wave | | &check; | &check; | &check;|&check; |&check; |&check; |&check; | 
| implicat | Implicat number (GV_IMP) | | &check; | &check; | &check;|&check; |&check; |&check; |&check; | 
| sample1 | Imputation sample for single (GV_IMP) | |  &check; | &check; | &check;|&check; |&check; |&check; |&check; | 
| sample2 | Imputation sample for couples 2R (GV_IMP) | |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| sample3 | Imputation sample for all couples (GV_IMP) | |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| mergeid | Person identifier (fix across modules and waves) | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid1 | Household identifier (wave 1) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid2 | Household identifier (wave 2) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid4 | Household identifier (wave 4) | H |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid5 | Household identifier (wave 5) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid6 | Household identifier (wave 6) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid8 | Household identifier (wave 8) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhid9 | Household identifier (wave 9) | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| int_year | Interview year | I | &check; | &check; | &check;|&check;|&check; |&check; | &check; | 
| int_month | Interview month | I | &check; | &check; | &check;|&check;|&check; |&check; | &check; | 
| int_year_ca | COVID-19 CATI interview (ca) interview year | I | | | | | | &check;| | 
| int_month_ca | COVID-19 CATI interview (ca) interview month | I | | | | | | &check;| | 

# Geographical information #
| Name | Label | Level | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| country | Country identifier | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| region | NUTS1 region of residence from housing info | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| areabldgi | Area of building | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Personal information #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| deceased | Deceased | I | |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| age | Age (GV_IMP) | I |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| age2004 | Age in 2004 (wave 1) | I |&check; | | | | | | | 
| age2007 | Age in 2007 (wave 2) | I| |&check; | | | | | | 
| age2011 | Age in 2011 (wave 4) | I | | |&check; | | | | | 
| age2013 | Age in 2013 (wave 5) | I| | | |&check; | | | | 
| age2015 | Age in 2015 (wave 6) | I| | | | | &check;| | | 
| age2020 | Age in 2020 (wave 8) | I| | | | | |&check; | | 
| age2022 | Age in 2022 (wave 9) | I| | | | | | | &check;| 
| rsex | Male or female | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| gender | Gender (GV_IMP) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rbyear | Year of birth | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rbmonth | Month of birth | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rnat | Born in the country of interview |I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| riyear | Year came to live in country | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rcit | Citizenship country of interview | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Education #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| redu | Highest school degree obtained |I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yedu | Years of education (GV_IMP) |I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| isced | ISCED 1997 coding of education (GV_IMP) |I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Family composition and information #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| htype | Household type (GV_IMP) | H |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| single | Single (GV_IMP) | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| couple | Couple (GV_IMP) | I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| partner | Partner in the couple (GV_IMP) | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| age_p | Age of partner (GV_IMP) | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yedu_p | Years of education of partner (GV_IMP) | I|&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| hhsize | Household size | H | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rmstat | Marital status | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rmar | Marital status (4 categories) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| mstat | Marital status (GV_IMP) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| nchild | Number of children (GV_IMP) | H |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Employment and pensions #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| rlbrf | Labor Force status (4 categories) | I|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rwork | Working for pay (= 1) | I|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ret | Retired (= 1) | I|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ret_work | Retired and working for pay (= 1) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| rself | Self employed in main job (= 1) |I |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| retag_c1 | Retirement age: public old age | I|&check; | | | | | | | 
| retag_c2 | Retirement age: public early retirement | I|&check; | | | | | | | 
| retag_c3 | Retirement age: public disability | I|&check; | | | | | | | 
| retag_c4 | Retirement age: sickness, invalidity | I| &check;| | | | | | | 
| retag_c5 | Retirement age: private occupational  old age |I | &check;| | | | | | | 
| retag_c6 | Retirement age: private occupational early retirement | I|&check; | | | | | | | 
| retagexp_c1 | expected age to collect pension: public old age | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| retagexp_c2 | expected age to collect pension: public early retirement | I|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| retagexp_c3 | expected age to collect pension: public disability | I|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| retagexp_c4 | expected age to collect pension: sickness, invalidity |I |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| retagexp_c5 | expected age to collect pension: private occupation old age |I |  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| earlyret_c1 | Early retirement possibility: public old age | I| &check;| | | | | | | 
| earlyret_c2 | Early retirement possibility: public early retirement | I|&check; | | | | | | | 
| earlyret_c3 | Early retirement possibility: public disability | I| &check;| | | | | | | 
| earlyret_c4 | Early retirement possibility: sickness, invalidity |I | &check;| | | | | | | 
| earlyret_c5 | Early retirement possibility: private occupational  old age |I | &check;| | | | | | | 
| earlyret_c6 | Early retirement possibility: private occupational early retirement |I | &check;| | | | | | | 
| cjs | Current job situation (GV_IMP) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| pwork | Did any paid work (GV_IMP) | I| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| empstat | Employee or self-employed (GV_IMP) | I| &check;| | | | | | | 
| empstat1 | Employee or self-employed first job (GV_IMP) |I |&check; | | | | | | | 
| empstat2 | Employee or self-employed second job (GV_IMP) |I | | &check; | &check;|&check;|&check; |&check; |&check; | 

# Financial transfers #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| ever_inher | Ever received gift or inheritance (worth 5000 euros or more) | H| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_1inher | Year, inheritance or large gift 1 received | H|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_2inher | Year, inheritance or large gift 2 received | H| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_3inher | Year, inheritance or large gift 3 received | H|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_4inher | Year, inheritance or large gift 4 received | H|  &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_5inher | Year, inheritance or large gift 5 received | H| &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| value_1inher | Value inheritance 1 | H|&check; | &check;| | | | | | 
| value_2inher | Value inheritance 2 | H| &check;| &check;| | | | | | 
| value_3inher | Value inheritance 3 | H|&check; | &check;| | | | | | 
| value_4inher | Value inheritance 4 | H| &check;| &check;| | | | | | 
| value_5inher | Value inheritance 5 | H|&check; | &check;| | | | | | 
| aftgiv | Financial transfers given (GV_IMP) | H|&check; | &check;| | | | | | 
| aftrec | Financial transfers received (GV_IMP) | H|&check; |&check; | | | | | | 
| aftinh | Inheritance received (GV_IMP) | H| &check;| &check;| | | | | | 

Question for `ever_inher`: Have you [or] [your] [husband/wife/partner] ever received a gift or inherited money, goods, or property worth more than 5000 euro (in local currency)?



# Housing status and assets #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| ho_status | Housing status: owner, tenant or rent free | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| how_property | How property acquired | |I  &check; | &check; | &check;|&check;| | | | 
| loan_property | Mortgages or loans on property | I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| year_property | Year acquired property | I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| value_property1 | Value of property | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| status_property2 | Own other real estate | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| value_property2 | Value of other real estate |I  |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| otrf | Owner, tenant or rent free (GV_IMP) | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| perho | Percentage of house owned (GV_IMP) | I | | | &check;|&check; |&check; | &check;| &check;| 
| home | Value of main residence (GV_IMP) | I |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| mort | Mortgage on main residence (GV_IMP) | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ores | Value of other real estate - Amount (GV_IMP) | I | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Income from labour #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| ydip | Earnings from employment (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yind | Earnings from self-employment (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Income from pensions #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| ypen1 | Old age, early retirement, and survisor pensions (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ypen2 | Private and occupational pensions (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ypen3 | Disability pensions and benefits (GV_IMP) | |&check; | | | |&check; | &check;| &check;| 
| ypen36 | Disability/sickness pensions/benefits (GV_IMP) | | | &check;| &check;| &check;| | | | 
| ypen4 | Unemployment benefits and insurances (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ypen5 | Social assistance (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ypen6 | Sickness benefits and pensions (GV_IMP)| |&check; | | | |&check; | &check;| &check;

# Other incomes #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| yreg1 | Other private pensions (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yreg2 | Private transfers (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yaohm | Income from other household members (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yincnrp | Income from nonresponding partner (GV_IMP) | | &check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsp1 | LS payments from old age, early retirement, and survivor pensions (GV_IMP) | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsp2 | LS payments from private and occupational pensions (GV_IMP) | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsp3 | LS payments from disability pensions/benefits (GV_IMP) | | | | | | &check;| &check;| &check;| 
| ylsp36 | LS payments from disability/sickness pensions/benefits (GV_IMP) | | | &check; | &check;|&check;| | | | 
| ylsp4 | LS payments from unemployment benefits/insurances (GV_IMP) | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsp5 | LS payments from social assistance (GV_IMP)  | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsp6 | LS payments from sickness benefits (GV_IMP)| | | | | | &check;| &check;| &check;| 
| ylsr1 | LS from private payments (GV_IMP)  | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| ylsr2 | LS from other private transfers (GV_IMP)  | | | &check; | &check;|&check;|&check; |&check; |&check; | 

# Capital incomes #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| income_property2 | Received income or rent of other real estate | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| incomev_property2 | Amount income or rent of other real estate last year | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| yrent | Income from rent (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| ybabsmf | Interest/dividend from financial assett (GV_IMP)  | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 

# Non-housing assets and liabilities #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| bacc | Bank accounts (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| bsmf | Bond, stock and mutual funds (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| slti | Savings for long-term investments (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| vbus | Value of own business (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| sbus | Share of own business (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| car | Value of cars (GV_IMP)| |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| liab | Financial liabilities (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 


# Consumption and expenditures #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| hprf | Value of home produced food (GV_IMP) | | | &check; | &check;|&check;|&check; |&check; |&check; | 
| rhre | Rent and home-related expenditures (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| fahc | Food at home consumption (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; | 
| fohc | Food outside home consumption (GV_IMP)| |&check; | &check; | &check;|&check;| |&check; |&check; | 
| telc | Amount spent on telephones (GV_IMP) | | &check; |&check;  | | | | | | 

# Total household income and expenditure #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| thinc | Total household income (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; |
| thinc2 | Total household income - Version B (GV_IMP) | | | &check; | &check;|&check;|&check; |&check; |&check; |
| thexp | Total household expenditure (GV_IMP) | |&check; | &check; | &check;|&check;|&check; |&check; |&check; |

# Currency and exchange rate #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| currency | currency | |&check; | &check; | &check;|&check;|&check; |&check; |&check; |
| exrate | Exchange rate (GV_IMP)| |&check; | &check; | &check;|&check;|&check; |&check; |&check; |
| nomx2003 | Nominal exchange rate (national currency/Euro), annual average, 2003 | |&check; | | | | | | | 
| nomx2004 | Nominal exchange rate (national currency/Euro), annual average, 2004 | | &check;| | | | | | | 
| nomx2005 | Nominal exchange rate (national currency/Euro), annual average, 2005 | | &check;| &check;| | | | | | 
| nomx2006 | Nominal exchange rate (national currency/Euro), annual average, 2006 | | |&check; | | | | | | 
| nomx2007 | Nominal exchange rate (national currency/Euro), annual average, 2007 | | |&check; | | | | | | 
| nomx2008 | Nominal exchange rate (national currency/Euro), annual average, 2008 | | |&check; | | | | | | 
| nomx2009 | Nominal exchange rate (national currency/Euro), annual average, 2009 | | |&check; | | | | | | 
| nomx2010 | Nominal exchange rate (national currency/Euro), annual average, 2010 | | | &check;| &check;| | | | | 
| nomx2011 | Nominal exchange rate (national currency/Euro), annual average, 2011 | | | |&check; | | | | | 
| nomx2012 | Nominal exchange rate (national currency/Euro), annual average, 2012 | | | | &check;|&check; | | | | 
| nomx2013 | Nominal exchange rate (national currency/Euro), annual average, 2013 | | | | |&check; | | | | 
| nomx2014 | Nominal exchange rate (national currency/Euro), annual average, 2014 | | | | | |&check; | | | 
| nomx2015 | Nominal exchange rate (national currency/Euro), annual average, 2015 | | | | | | &check;| | | 
| nomx2018 | Nominal exchange rate (national currency/Euro), annual average, 2018 | | | | | | |&check; | | 
| nomx2019 | Nominal exchange rate (national currency/Euro), annual average, 2019 | | | | | | |&check; | | 
| nomx2020 | Nominal exchange rate (national currency/Euro), annual average, 2020 | | | | | | |&check; | &check;| 
| nomx2021 | Nominal exchange rate (national currency/Euro), annual average, 2021 | | | | | | | | &check;| 
| nomx2022 | Nominal exchange rate (national currency/Euro), annual average, 2022 | | | | | | | | &check;| 
| pppc2003 | Current PPP exchange rate (national currency/Euro), 2003 | | &check;| | | | | | | 
| pppc2004 | Current PPP exchange rate (national currency/Euro), 2004 | | &check;| | | | | | | 
| pppc2005 | Current PPP exchange rate (national currency/Euro), 2005 | | &check;| &check;| | | | | | 
| pppc2006 | Current PPP exchange rate (national currency/Euro), 2006 | | | &check;| | | | | | 
| pppc2007 | Current PPP exchange rate (national currency/Euro), 2007 | | | &check;| | | | | | 
| pppc2008 | Current PPP exchange rate (national currency/Euro), 2008 | | |&check; | | | | | | 
| pppc2009 | Current PPP exchange rate (national currency/Euro), 2009 | | |&check; | | | | | | 
| pppc2010 | Current PPP exchange rate (national currency/Euro), 2010 | | | &check;| &check;| | | | | 
| pppc2011 | Current PPP exchange rate (national currency/Euro), 2011 | | | |&check; | | | | | 
| pppc2012 | Current PPP exchange rate (national currency/Euro), 2012 | | | |&check; | &check;| | | | 
| pppc2013 | Current PPP exchange rate (national currency/Euro), 2013 | | | | | &check;| | | | 
| pppc2014 | Current PPP exchange rate (national currency/Euro), 2014 | | | | | | &check;| | | 
| pppc2015 | Current PPP exchange rate (national currency/Euro), 2015 | | | | | | &check;| | | 
| pppc2018 | Current PPP exchange rate (national currency/Euro), 2018 | | | | | | | &check;| | 
| pppc2019 | Current PPP exchange rate (national currency/Euro), 2019 | | | | | | | &check;| | 
| pppc2020 | Current PPP exchange rate (national currency/Euro), 2020 | | | | | | | &check;| &check;| 
| pppc2021 | Current PPP exchange rate (national currency/Euro), 2021 | | | | | | | | &check;| 
| pppc2022 | Current PPP exchange rate (national currency/Euro), 2022 | | | | | | | | &check;| 
| pppk2003 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2003 | |&check; | | | | | | | 
| pppk2004 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2004 | |&check;| | | | | | | 
| pppk2005 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2005 | |&check;| &check;| | | | | | 
| pppk2006 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2006 | | | &check;| | | | | | 
| pppk2007 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2007 | | | &check;| | | | | | 
| pppk2008 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2008 | | | &check;| | | | | | 
| pppk2009 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2009 | | | &check;| | | | | | 
| pppk2010 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2010 | | | &check;| &check;| | | | | 
| pppk2011 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2011 | | | | &check;| | | | | 
| pppk2012 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2012 | | | | &check;|&check; | | | | 
| pppk2013 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2013 | | | | | &check;| | | | 
| pppk2014 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2014 | | | | | | &check;| | | 
| pppk2015 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2015 | | | | | | &check;| | | 
| pppk2018 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2018 | | | | | | | &check;| | 
| pppk2019 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2019 | | | | | | | &check;| | 
| pppk2020 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2020 | | | | | | | &check;|&check; | 
| pppk2021 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2021 | | | | | | | | &check;| 
| pppk2022 | Constant PPP exchange rate (national currency/Euro), (Germany 2015=1), 2022 | | | | | | | | &check; |

# Weights #
| Name | Label | Refer to | W1 | W2 | W4 | W5 | W6 | W8 | W9 |  
|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| wghh | Calibrated cross-sectional household weight | |&check; | &check; | &check;|&check;|&check; |&check; |&check; |
| wgid | Calibrated cross-sectional individual weight| |&check; | &check; | &check;|&check;|&check; |&check; |&check; |



