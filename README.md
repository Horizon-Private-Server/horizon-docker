# horizon-docker

Example environment variables
```
export HORIZON_MSSQL_SA_PASSWORD=YOUR_DB_PASSWORD
export HORIZON_DB_USER=YOUR_DB_USERNAME
export HORIZON_DB_NAME=Medius_Database
export HORIZON_DB_SERVER=YOUR_DB_PUBLIC_IP,YOUR_DB_PORT
export HORIZON_ASPNETCORE_ENVIRONMENT=Prod
export HORIZON_MIDDLEWARE_SERVER=http://0.0.0.0:10000
export HORIZON_MIDDLEWARE_SERVER_IP=http://YOUR_MIDDELWARE_PUBLIC_IP:10000
export HORIZON_MIDDLEWARE_USER=MIDDLEWARE_ADMIN_USERNAME
export HORIZON_MIDDLEWARE_PASSWORD=MIDDLEWARE_ADMIN_PASSWORD
export HORIZON_APP_ID=COMMA_SEPARATED_LIST_OF_APP_IDS

# If you are using plugins/patch
export HORIZON_MEDIUS_PLUGIN_PATH=/root/horizon-uya-prod/horizon-uya-plugin/out/medius/
export HORIZON_DME_PLUGIN_PATH=/root/horizon-uya-prod/horizon-uya-plugin/out/dme/
export HORIZON_PATCH_MISC_PATH=/root/horizon-uya-prod/horizon-uya-patch/misc
export HORIZON_PATCH_BIN_PATH=/root/horizon-uya-prod/horizon-uya-patch/bin
```