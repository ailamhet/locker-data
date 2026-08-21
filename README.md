# locker-data

Static pickup-point datasets for KIDORAX landing pages.

- Source: euShipments (inout.bg) courier offices API
- `locker-{cc}-index.json` — region list per country
- `locker-{cc}-{region}.json` — points per region: `n` name, `c` city, `a` address, `z` postal code, `t` 1=automated locker, `d` 1=COD supported
- RO = SameDay/Easybox, COD-supported points only. ES = Correos offices + Citypaq.

Served via jsDelivr: `https://cdn.jsdelivr.net/gh/ailamhet/locker-data@main/<file>`
