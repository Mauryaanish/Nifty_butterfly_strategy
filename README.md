# Nifty_butterfly_strategy

## Data Preparation
:- I am taking an NSE  derivatives Dataset for a one-minute time frame. 9 columns are present in the data set.
   ticker, Exp_date, Date/time, open, high, close, low, oi, volume
## Create New DataFrame
### Symbol
- Using the Split Function, I  split the ticker column to  create a new symbol column.

### Strike Price
- Create a new column and put the strike price, and strike price available in the ticker column I split the ticker column.
  
### Instrument
- Future Index :- FUTIDX  &  Option Index :- OPTIDX

### Option Type 
- CE & PE

### Timestamp
- Trading Day

### Raw Data Image
 ![Raw Data Image](https://github.com/Mauryaanish/Nifty_butterfly_strategy/blob/main/Raw_Data.txt/raw%20data.PNG)

### After Data Cleaning & Data Preparation Image
 ![After Data Cleaning & Data Prepration](https://github.com/Mauryaanish/Nifty_butterfly_strategy/blob/main/Raw_Data.txt/main%20data.PNG)

 ### Butter_fly_Monthly_Backtesing
 - The Nifty Butterfly Strategy involves simultaneously buying and selling three options with different strike prices to profit from a limited price range in the Nifty 50 index. This 
    strategy seeks to maximize gains in a narrow price range while limiting losses, making it a popular choice for traders with a neutral outlook on the index's performance
