# Prisma Photon GraphQL with MySQL Example

... deployed to [Now](https://zeit.co)

copied from... [Postgres Example](https://github.com/prisma/photonjs/tree/master/examples/deployment-platforms/zeit-now)

## Usage
```bash
yarn install

echo `MYSQL_CLOUD_URL="mysql://user:password@mysql.server.com:3306/myDatabase?sslmode=preferred"` > .env

now secret add MYSQL_CLOUD_URL "mysql://user:password@mysql.server.com:3306/myDatabase?sslmode=preferred"

now -e MYSQL_CLOUD_URL=@mysql_cloud_url
```

