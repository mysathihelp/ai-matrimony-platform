# Cron Jobs Configuration

- Payout automation: 0 2 5 * * php /var/www/html/wp-content/plugins/commission/payout.php
- Tier recalculation: 0 3 * * * php /var/www/html/wp-content/plugins/tier/recalc.php
- Database backup: 0 4 * * * mysqldump ...
