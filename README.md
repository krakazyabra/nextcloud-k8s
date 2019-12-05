# nextcloud-k8s
Nextcloud manifests for kubernetes

Some manifests for deploy nextcloud in kubernetes with nginx and redis. 
DB was deployed by helm-chart charts/percona-xtradb-cluster

Clone the repo into your directory, change some values (almost inside `<>`), deploy your favorite DB. After first running you will be able to create DB and admin user.
Local S3 is using as default storage for NC (deploy not included into these manifests).
