# TrackLin.es for TRMNL

Shows your open TrackLin.es tickets (the same list as **My work**) on a TRMNL. It polls
`GET https://api.tracklin.es/api/search?assignee=me&status=open` with your API key.

## Install

Install it from [the TrackLin.es recipe](https://trmnl.com/recipes/tracklin-es-511430). Make a **read-only personal key** in TrackLin.es (Your settings → API keys), add the plugin in TRMNL and paste the key. A personal key is you, so the plugin shows your tickets; read-only means TRMNL can never change anything.

## Develop

```sh
gem install trmnl_preview
TRACKLINES_API_KEY=tl_p_… trmnlp serve   # http://localhost:4567
trmnlp login && trmnlp push              # upload to your TRMNL account
```
