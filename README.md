# AGOL_Management
Notebooks you can use to manage your AGOL content.

### AGOL_Items_Find_URLS_Shared.ipynb
If you must update content in your AGOL Org or in a Portal this notebook can help you find what needs to change.
it will find all url instances containing a keyword and then write details to an excel spreadsheet.  Below are the configurable parameters:

item_df_columns is a list of column names that will appear in the exported spreadsheet.

excel_file is the name and location of the exported excel file.

url_key_word is key word that you will search for within item URLs in your org.

proxy is the proxy to set if you are behaind a corporate firewall and must use a proxy to see out to the interwebs.

agol_user is the user who is logging into AGOL. This user must have admin privileges within the org. You will be prompted to enter this value.

agol_pass is the password of the admin user who is logging in.
