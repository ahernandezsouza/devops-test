FROM wodby/drupal-php:7.2-dev-4.14.3

WORKDIR /var/www/html

RUN drush dl drupal-7 --drupal-project-rename=docroot -y; \
  cd docroot; \
#  drush si standard --db-url=mysql://drupal:drupal@mariadb/drupal \
#  --db-su=drupal --db-su-pw=password --site-name="AWS Translate"  \
#  --account-name=admin --account-pass=Mbod2027= -y;
