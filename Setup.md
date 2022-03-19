# Setup

1. initialize IDS4Sail
   1. Upload clean .db (KUDU drag and drop)
   2. Login *install* user
   3. Upload seed file `IdS4Sail\Seeds\dev-data.json`
2. initialize api
   1. login with *install*
   2. ensure clear dev DB
   3. https://4sail-dev.azurewebsites.net/swagger/index.html
      1. `curl -X GET "https://localhost:5003/Application" -H  "accept: */*" -H  "Authorization: Bearer TODO"`
3. generate data
   1. https://4sail-dev.azurewebsites.net/swagger/index.html
      1. `curl -X POST "https://localhost:5003/Application" -H  "accept: */*" -H  "Authorization: Bearer TODO"`

## Common erros

If there is some problem with connection between services, check the ip address restrictions.