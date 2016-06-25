# ramso/seeddms

Unofficial docker iamge of [SeedDms](http://www.seeddms.org/) .
# Usage
`docker run -d --name seeddms -p 9080:80 ramso/seeddms`

# Volumes
There are two volumes available for configuration and data
`/home/www-data/seeddms43x/data/ for storage your data
/home/www-data/seeddms43x/seeddms-4.3.13/conf/ for storage the configuration`