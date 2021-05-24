#### Market Feed

```py
# NOTE : Symbol has to be in the same format as specified in the example below.

req_list_=[{"Exch":"N","ExchType":"C","ScripCode":"22"},
            {"Exch":"N","ExchType":"C","ScripCode":"2885"}]
            
client.fetch_market_feed(req_list=req_list_, count=2,client_id="client_code")
```
