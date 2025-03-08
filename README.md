# liberty-plugins
Plugins for Liberty Framework

## ✅ Dags

### **Daily DAGs**
- **`airflow-purge-daily-1`**: Purges old Airflow logs and metadata on a daily schedule (`@daily`).
- **`database-backup-daily-1`**: Backs up databases every day at 01:00 AM (`00 1 * * *`).

### **Weekly DAGs**
- **`database-purge-weekly-1`**: Performs database cleanup and purging on a weekly schedule (`@weekly`).

### **Unscheduled DAGs**
- **`airflow-sync-1`**: Synchronizes repositories as needed (manually triggered).
