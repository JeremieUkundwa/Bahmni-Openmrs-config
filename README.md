# Export-import_db
import and Export of mysql 

# Steps to overwrite Existing files

# change to pwd containing files to copy and type to overwrite bahmni_config and other files nedded 
 -->cp -avr bahmni_config/* /opt/bahmni-web/etc/bahmni_config/

# give privirage to copied files to be accessed

 --> chown -R bahmni:bahmni bahmni_config/
