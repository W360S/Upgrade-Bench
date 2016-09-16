# Step 1
cd /home/frappe/.bench/ && git reset --hard && git pull
# Step 2
cd /home/frappe/frappe-bench/apps/frappe/ && git reset --hard && git pull
# Step 3
cd /home/frappe/frappe-bench/apps/erpnext/ && git reset --hard && git pull
# Step 4
cd /home/frappe/frappe-bench && bench update --upgrade
