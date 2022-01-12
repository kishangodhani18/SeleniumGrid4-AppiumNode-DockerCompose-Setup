# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM selenium/hub:4.1.1-20211217
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium Hub Configuration
#========================

COPY start-selenium-grid-hub.sh \
    /opt/bin/

COPY selenium-grid-hub.conf /etc/supervisor/conf.d/