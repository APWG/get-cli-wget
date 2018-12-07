```
wget --quiet \
  --method GET \
  --header 'Authorization: <your eCX API token goes here>' \
  --header 'Content-Type: application/json' \
  --output-document \
  - https://api.ecrimex.net/phish
```