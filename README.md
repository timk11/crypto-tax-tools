# crypto-tax-tools
This repository contains tools for compiling cryptocurrency transactions into CSV files compatible with Koinly crypto tax software, for selected chains that are not integrated or not easily managed with Koinly. The resulting files can also be modified for compatibility with other tax software packages.  

NFTs in these tools will be identified as "NULL" with the token name and ID appearing in the "Description" column. This is to ensure that the transactions are not rejected but may result in capital gains not being calculated correctly.  

See also https://github.com/holgern/hive-reports/blob/master/koinly/liquid-hive-report.py for a similar tool that has been developed for the HIVE blockchain. You'll need to change `ops["reward_steem"]` to `ops["reward_hive"]` and `ops["reward_sbd"]` to `ops["reward_hbd"]` in lines 337 and 339 respectively.
