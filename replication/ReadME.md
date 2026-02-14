Documentation

Code:
Replication_clean_data.ipynb: Merges all data files into one aggregate dataset

table1.do: Uses Replication_clean_data.ipynb to replicate regressions

Data: 
Finint_df.csv: External financing data from Rajan and Zingales (1998)
https://www.jstor.org/stable/116849?seq=12 

OECD_trade.csv: Import export data from OECD
https://data-explorer.oecd.org/vis?fs[0]=Topic%2C1%7CTrade%23TRD%23%7CTrade%20in%20goods%20and%20services%23TRD_GDS%23&pg=0&fc=Topic&bp=true&snb=30&vw=tb&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_BTIGE%40DF_BTIGE&df[ag]=OECD.STI.PIE&df[vs]=1.0&dq=A.AUT%2BBEL%2BCAN%2BDNK%2BFIN%2BFRA%2BDEU%2BGRC%2BITA%2BJPN%2BMEX%2BNLD%2BNZL%2BNOR%2BPRT%2BESP%2BSWE%2BGBR%2BUSA%2BAUS.M%2BX.TOTAL.CPA_2_1_J59_60%2BCPA_2_1_B05%2BCPA_2_1_B06%2BCPA_2_1_M74%2BCPA_2_1_C31_32%2BCPA_2_1_C18%2BCPA_2_1_C21%2BCPA_2_1_C22%2BCPA_2_1_C23%2BCPA_2_1_C24FER%2BCPA_2_1_C24XFER%2BCPA_2_1_C25%2BCPA_2_1_C26%2BCPA_2_1_C27%2BCPA_2_1_C28%2BCPA_2_1_C29_30%2BCPA_2_1_C29%2BCPA_2_1_C301%2BCPA_2_1_C10%2BCPA_2_1_C11%2BCPA_2_1_C12%2BCPA_2_1_C13%2BCPA_2_1_C15%2BCPA_2_1_C14%2BCPA_2_1_C16%2BCPA_2_1_C17%2BCPA_2_1_C19%2BCPA_2_1_C20.W.&pd=1989%2C1995&to[TIME_PERIOD]=false 

OECD_notrade.csv: Data from OECD Structural Analysis Database (STAN)
https://data-explorer.oecd.org/vis?tm=DF_STAN_2025&snb=1&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_STAN%40DF_STAN_2025&df[ag]=OECD.STI.PIE&df[vs]=1.0&dq=A.AUS%2BAUT%2BBEL%2BCAN%2BDNK%2BFIN%2BFRA%2BDEU%2BITA%2BJPN%2BMEX%2BNLD%2BNZL%2BNOR%2BPRT%2BESP%2BSWE%2BGBR%2BUSA.C19%2BB05_06%2BC23%2BC242_2432%2BC301%2BC29%2BJ59_60%2BC10%2BC11%2BC12%2BC13%2BC14%2BC16%2BC17%2BC18%2BC15%2BC21%2BC20%2BC22%2BC241_2431%2BC25%2BC28%2BC27%2BC29_30%2BC31_32%2BM_N%2BC26.P2%2BP1%2BD1%2BEMP%2BB1G%2BP51G..&pd=1989%2C1991&to[TIME_PERIOD]=false&vw=tb 

FinancialStructureDatabase.xlsx: Stock market data from Beck et al. (2000)
https://thedocs.worldbank.org/en/doc/855381572291532619-0050022019/Financial-Structure-Database-2019-10-18 

Govt_borrow.xlsx: Government borrowing as % of GDP from IMF
https://www.imf.org/external/datamapper/GG_DEBT_GDP@GDD/CAN/FRA/DEU/ITA/JPN/GBR/USA 

Gross_savings.csv: Domestic saving as % of GDP from world bank
https://data.worldbank.org/indicator/NY.GDS.TOTL.ZS?view=map&year=1989 


Acstan.csv: Accounting standards 
https://www.jstor.org/stable/116849?seq=12 

Shareholder.csv: Shareholder data from La Porta et al. (1998).
https://faculty.tuck.dartmouth.edu/images/uploads/faculty/rafael-laporta/Law_and_Finance.pdf 

Creditor.csv: Creditor data from La Porta et al. (1998).
https://faculty.tuck.dartmouth.edu/images/uploads/faculty/rafael-laporta/Law_and_Finance.pdf 

Barro_lee.csv: Educational attainment (secondary schooling for pop aged 25+) from Barro and Lee (2000)
https://github.com/barrolee/BarroLeeDataSet/blob/master/BLData/BL2013_MF2599_v2.2.csv 

Arable_land.csv: Arable land data from the FAO
https://www.fao.org/4/y5473m/y5473m08a.pdf 

Forestry.xlsx: forestry data form ITTO
https://www.itto.int/biennal_review_statistics/?mode=searchdata 

Food_production.csv: Total daily supply of calories per person https://ourworldindata.org/explorers/global-food?Food=All+food&Metric=Production&Per+capita=false&country=OWID_WRL~USA~CHN~IND~BRA~GBR)
