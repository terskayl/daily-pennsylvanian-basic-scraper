Here was the original cron expression:  
cron: "0 20 * * *"   
The expression order goes minute, hour, day of the month, month, and day of the week  
The first two terms means that 0 minutes after the hour, at 20:00 UTC, which is 8:00 pm UTC or 3:00 am EST, it will perform the scrape.  
The asterisks mean that it will do this on every day of the month, on every month, and every day of the week  
