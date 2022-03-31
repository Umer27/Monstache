# Monstache
Sync Mongo data to Elasticsearch. Nest application that generate data through rest API's in Mongodb. Using Monstache ship all the incoming data from mongo to Elasticsearch in realtime. Mongodb must be run in repica mode in order to generate **oplog** file which other Mongo replicas and Monstache observe to sync data.
