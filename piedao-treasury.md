1. Create Google Sheets

[Sheets.new](https://sheets.new)

1. Activate [API Connector](https://workspace.google.com/marketplace/app/api_connector/95804724197)
2. Upgrade Premium ($144 Annually) - can be tested 14 days trial for free
3. Refresh sheet
4. Start API Connector via "Extensions" > "API Connector"
   
### Settings

![](https://user-images.githubusercontent.com/98217124/151754942-19606777-09c0-4e0b-878e-b25bd7cc0de0.png)

API URL = https://openapi.debank.com/v1/user/token_list?id=0x3bCF3Db69897125Aa61496Fc8a8B55A5e3f245d5&is_all=true

* Destination sheet = Set Current

* Output Options = append

* Click `More Options`

![](https://user-images.githubusercontent.com/98217124/151761832-eed6badb-a693-44dc-b9dc-ae675147dddf.png)

* Mark `Add timestamp` and `Each Row`

![](https://user-images.githubusercontent.com/98217124/151778958-f2551c9e-732a-4e94-ac52-27bdd19e35ae.png)

* Add Name & Click `Save`

### Schedule

![](https://user-images.githubusercontent.com/98217124/151779129-7e806dfb-f102-44a7-967f-b128f9f0146b.png)

* Click `Add Trigger`

![](https://user-images.githubusercontent.com/98217124/151755075-5ca7ec5b-201d-4bb1-bb4b-fa863713ca4f.png)

* API request name = select saved API name
* Run request = select "every day"
* between = select a time-frame
* Trigger name = select name

In the tab `Requests` you can run the query manually if needed