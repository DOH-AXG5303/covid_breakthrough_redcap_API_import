# covid_breakthrough_redcap_API_import
Automating import of covid breakthrough data from WDRS to REDCap.

Daily data pipeline from WDRS to REDCap. Files to be imported are first broken into chunks of 200 rows
and imported into REDCap in batches. 

## Requirements
- python=3.8*
- pandas=1.2*
- pycap=1.1*
- requests=2.25*

## Installing
No installation required except required libraries. 
