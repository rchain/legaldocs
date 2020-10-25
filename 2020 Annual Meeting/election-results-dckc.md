Independent Tally by [@dckc](https://github.com/dckc) \
[tally.sh `aea85b4`](https://github.com/rchain-community/rv2020/blob/aea85b4221013b02f07343da1299d49bdb4d951a/src/cli/tally.sql)

```
questions   voters      vote_time_min        vote_time_max      
----------  ----------  -------------------  -------------------
5           53          2020-10-21 12:21:32  2020-10-23 21:42:56
qid         sentiment   qty      
----------  ----------  ----------
Board: CR   yes         33        
Board: CR   no          17        
Board: CR   abstain     3        
Board: GM   yes         49        
Board: GM   abstain     2        
Board: GM   no          2        
Board: KL   no          27        
Board: KL   yes         21        
Board: KL   abstain     5        
Board: RB   yes         52        
Board: RB   no          1        
Monetary P  yes         34        
Monetary P  no          12        
Monetary P  abstain     7


tally.sql rev aea85b4 

operator notes:

~/projects/rv2020/src/cli
09:26 connolly@jambox$ node tally.js ../web/ballotexample.json status.rchain.coop --save agmtx.json
downloading transactions from 15 choices listed in the ballot...
downloading transactions from 75 voters...
~/projects/rv2020/src/cli
09:31 connolly@jambox$ python3 load_votes.py agmtx.json agm.db
INFO:__main__:looking up set rho:id:admzpibb3gxxp18idri7h6eneg4io6myfmcmjhufc6asy73bgrojop
INFO:__main__:looking up rho:id:po68mejh9y9cx8n3htiejpqrjch9deq6rxhq45jnegsyyahrtmaxm5
INFO:__main__:in: <module 'json' from '/home/connolly/opt/miniconda3/lib/python3.7/json/__init__.py'> out: agm.db
INFO:__main__:(re-)created table: tx
INFO:__main__:(re-)created table: choice
INFO:__main__:(re-)created table: voter
INFO:__main__:inserted 15 records into choice
INFO:__main__:inserted 124 records into voter
INFO:__main__:inserted 1436 records into tx
~/projects/rv2020/src/cli
09:31 connolly@jambox$ sqlite3 -header -column agm.db <tally.sql```
