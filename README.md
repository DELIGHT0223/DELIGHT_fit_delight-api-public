# DELIGHT_fit_delight-api-public

-   GET /users/ranking

Getting User Step Ranking
```
\$ curl -s GET https://api.genki.fit/users/ranking
```

#### Parameters

#### Response

```text
{
    "message": "top 30 balances of users.",
    "users": [
        {
            "address": "0xf334ce6ca2d6d7bd5f2ab4b056eb82186c3c07c7",
            "username": "Hiroyuki ANNO",
            "total_step": 58319,
            "genki": "1.8",
            "shogai": "1.8"
        },
        {
            "address": null,
            "username": null,
            "total_step": 12386,
            "genki": "0.4",
            "shogai": "0.4"
        },
        {
            "address": "0x5f435e6dd88a01c93f721ac85297f731969bd35a",
            "username": "sample3",
            "total_step": 6004,
            "genki": "0.1",
            "shogai": "0.2"
        }
    ],
    "status": 200
}
