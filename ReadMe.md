# Extract TAQ data from WRDS Cloud via terminal

---

## Description

A simple SAS program that can extract TAQ data from WRDS cloud for a list of companies on particular dates during specific time periods.  



## How to use

1. Upload to your WRDS cloud the txt file that includes ticker and date for which you need TAQ data (Check [here](https://wrds-www.wharton.upenn.edu/pages/support/the-wrds-cloud/managing-data/accessing-wrds-remotely-sftp/) for how to transfer file via SFTP)

2. Upload to your WRDS cloud the code file "WRDS_batch_ticker_*.sas". (Please remember to change to your txt file path in the code).

3. Connect to your WRDS Cloud via SSH. (Check [here](https://wrds-www.wharton.upenn.edu/pages/support/the-wrds-cloud/using-ssh-connect-wrds-cloud) for how to connect to WRDS Cloud via SSH)

4. Submit command on your terminal: 

   ```
   qsas WRDS_batch_ticker_*.sas 
   ```

   (check [here](https://wrds-www.wharton.upenn.edu/pages/support/the-wrds-cloud/running-jobs/batch-jobs-wrds-cloud/) for how to use batch jobs on the WRDS Cloud)





---

[Gen Li](mailto:gen.li@yale.edu) &copy; 2019 