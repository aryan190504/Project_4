FROM tomcat:9

# Copy the WAR file to the Tomcat webapps directory
COPY target/ORS_Project4.war /usr/local/tomcat/webapps/

# Expose port 8080 for the Tomcat server
EXPOSE 8080

# Start Tomcat using the correct script name
CMD ["catalina.sh", "run"]
