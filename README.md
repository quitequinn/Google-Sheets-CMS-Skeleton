# Google-Sheets-CMS-Skeleton

We use [Papa Parse](https://www.papaparse.com/) to link our spreadsheet to the website. I've already created a demo in the `index.html` file so you can get started.

## The Basic Setup

Make a [Google Spreadsheet](http://drive.google.com). Give it some column headers, give it some content. Please makesure to use a private account, not an organizational one (eg. NOT your ECUAD email).

<img width="807" alt="Screen Shot 2022-03-28 at 9 18 35 AM" src="https://user-images.githubusercontent.com/2885870/160442803-a5f54548-f203-4d0c-9681-2ff24e3894a8.png">
  
  
Now go up to the `File` menu and pick `Publish to the web`. 

<img width="602" alt="Screen Shot 2022-03-28 at 9 21 17 AM" src="https://user-images.githubusercontent.com/2885870/160443189-8503a28f-cb92-4cb5-bd45-a2ddf5779062.png">


And then publish it as a CSV.

<img width="527" alt="Screen Shot 2022-03-28 at 9 21 39 AM" src="https://user-images.githubusercontent.com/2885870/160443233-2a1db06f-c742-4306-8466-280839424690.png">


Now that you've published your sheet, grab the link provided and use it in your javascript. Your URL should look something like `https://docs.google.com/spreadsheets/d/e/2PACX-1vQRjCK4PfiSWsRfFrE8qhFY9qjP0WZaTuDZ_DV-D3ph8WbTAyjmOBLyNJIgTEy8treec_bjqiGc7huc/pub?output=csv`.

<img width="538" alt="Screen Shot 2022-03-28 at 9 21 56 AM" src="https://user-images.githubusercontent.com/2885870/160443293-352fa863-daa4-4d77-b4b0-d2746d6ae110.png">
<img width="734" alt="Screen Shot 2022-03-28 at 9 23 44 AM" src="https://user-images.githubusercontent.com/2885870/160443394-ef90cc35-91c2-4219-8a9a-db0c2ca37ad1.png">

The last step is that you need a server to retieve the data. That can be anything you want it to be, but for the purposes of this example we are just going to start MAMP.

<img width="604" alt="Screen Shot 2022-03-28 at 9 25 27 AM" src="https://user-images.githubusercontent.com/2885870/160443720-6a596d58-df4f-432f-bb41-cf42ae457b2e.png">


Now you should be able to retrieve all the data in your Google sheet as use it as you want. Just go to your MAMP root and select the project.

<img width="783" alt="Screen Shot 2022-03-28 at 9 28 18 AM" src="https://user-images.githubusercontent.com/2885870/160444177-b542037a-d280-4553-b78d-2e1347e41674.png">

