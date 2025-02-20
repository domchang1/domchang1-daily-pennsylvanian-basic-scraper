# Scrape Scheduling Explained

```
schedule:
    - cron: "30 8 * * *"  
    - cron: "0 21 * * *"
```
Here is my schedule for the scraper. Essentially, each item has a cron job (which is just one iteration of a web scrape) that runs at a certain schedule defined in quotations.
The first number is minutes, second is hours, third is day of the month, fourth is the month, and fifth is the day of the week. Also, * means it will run during any minute, hour, etc.
Therefore, for example, the first cron job will run at 8:30 AM every day of the month, every month, and every day of the week.
