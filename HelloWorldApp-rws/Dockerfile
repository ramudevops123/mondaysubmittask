FROM jboss/wildfly
ADD target/HelloWorldApp-rws.war /opt/jboss/wildfly/standlone/developments/
RUN /opt/jboss/wildfly/bin/add-user.sh admin admin --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]

