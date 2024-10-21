ARG version
FROM mysql:${version:-8.0}
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1 
ADD scripts/*.sql  /docker-entrypoint-initdb.d
    # MYSQL_DATABASE=transcations \
    # MYSQL_USER=expense \
    # MYSQL_PASSWORD=ExpenseApp@1