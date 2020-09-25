# Section 3 Notes

### Docker commands

-

- Assignment: Manage Multiple container
  - Run a nginx, a mysql and a httpd (apache) server
  - Commands
    - `docker container run -d -p 80:80 --name my-nginx nginx`
    - `docker container run -d -p 8080:80 --name my-apache httpd`
    - `docker container run -d -p 3306:3306 --name my-mysql -e MYSQL_RANDOM_ROOT_PASSWORD=true mysql`
