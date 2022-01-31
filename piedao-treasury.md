1. Create Google Sheets

[Sheets.new](https://sheets.new){:target="_blank"}

2. Activate [API Connector](https://workspace.google.com/marketplace/app/api_connector/95804724197){:target="_blank"}
3. Upgrade Premium ($144 Annually) - can be tested 14 days trial for free
4. Refresh sheet
5. Start API Connector via "Extensions" > "API Connector"
   
### Settings

![](https://user-images.githubusercontent.com/98217124/151754942-19606777-09c0-4e0b-878e-b25bd7cc0de0.png)

API URL = https://openapi.debank.com/v1/user/token_list?id=0x3bCF3Db69897125Aa61496Fc8a8B55A5e3f245d5&is_all=true

Destination sheet = Set Current

Output Options = append

Run & Save

### Schedule

![](https://user-images.githubusercontent.com/98217124/151755075-5ca7ec5b-201d-4bb1-bb4b-fa863713ca4f.png)

API request name = select saved API

Run request = select "every day"

between = select a time-frame

Trigger name = select name
