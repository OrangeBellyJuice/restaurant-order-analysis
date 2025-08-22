
# 🛎️ Restaurant Order Analysis 🍽️
Analyze order data to identify the most and least popular menu items and types of cuisine.

## Tables
```mermaid
%%{
    init: {
        "theme" : "neutral",
        "fontFamily" : "JetBrains Mono"
    }
}%%
erDiagram
    menu_items {
        smallint menu_item_id
        varchar(45) item_name
        varchar(45) category
        decimal price
    }
    order_details {
        smallint order_details_id
        smallint order_id
        date order_date
        time order_time
        smallint item_id
    }
```     
## Instructions 
import *create_restaurant_db.sql* into respective IDE and run it.

## Tools
<p align="left">
    <a href="https://www.jetbrains.com/datagrip/">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/datagrip/datagrip-original.svg" alt="datagrip" width="45" height="45" /> 2025.3.1
    </a></br>
    <a href="https://dev.mysql.com/downloads/installer/">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="60" height="60" /> 8.0.42
    </a>
</p> 
