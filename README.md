# AGOL_Management
Notebooks you can use to manage your AGOL content.

### AGOL_Items_Find_URLS_Shared.ipynb
If you must update content in your AGOL Org or in a Portal this notebook can help you find what needs to change.
it will find all url instances containing a keyword and then write details to an excel spreadsheet.  Below are the configurable parameters:

item_df_columns is a list of column names that will appear in the exported spreadsheet.

excel_file is the name and location of the exported excel file.

url_key_word is key word that you will search for within item URLs in your org.

agol_user is the user who is logging into AGOL. This user must have admin privileges within the org. You will be prompted to enter this value.

agol_pass is the password of the admin user who is logging in.

### If you are behind a proxy you can do one of two things:

Option one:
Set two environmental variables:
The first for http requests:
Variable = http_proxy
Value = http://[proxyaddress]:[proxyport]

The second for https requests:
Variable = https_proxy
Value = http://[proxyaddress]:[proxyport]

Instead of using environment valuables you can set the proxy when creating the GIS object:

gis = GIS(url='https://www.arcgis.com', 
          username = [username], 
          password = [userpass], 
          proxy_host=[proxyaddress],
          proxy_port=[proxyport])
