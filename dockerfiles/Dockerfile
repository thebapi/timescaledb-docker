FROM timescale/timescaledb:latest-pg11
MAINTAINER Sajib Sarkar <thebapi@gmail.com>

# Copy postgres config file into container
COPY config/postgresql.conf /etc/postgresql.conf

EXPOSE 5432

# "-c", "config_file=/etc/postgresql.conf"
CMD ["postgres"]

