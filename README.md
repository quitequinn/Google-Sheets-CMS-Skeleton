# Google-Sheets-CMS-Skeleton

We use [Papa Parse](https://www.papaparse.com/) to link our spreadsheet to the website. I've already created a demo in the `index.html` file so you can get started.

## The Basic Setup

Make a [Google Spreadsheet](http://drive.google.com). Give it some column headers, give it some content. Please makesure to use a private account, not an organizational one (eg. NOT your ECUAD email).

    Name                Category         Healthiness 
    Carrot              Vegetable        Adequate
    Pork Shoulder       Meat             Questionable
    Bubblegum           Candy            Super High
  
Now go up to the `File` menu and pick `Publish to the web`. Just publish it as a CSV.
Now that you've published your sheet, grab the link provided and use it in your javascript. Your URL should look something like `https://docs.google.com/spreadsheets/d/e/2PACX-1vQRjCK4PfiSWsRfFrE8qhFY9qjP0WZaTuDZ_DV-D3ph8WbTAyjmOBLyNJIgTEy8treec_bjqiGc7huc/pub?output=csv`.

Now you should be able to retrieve all the data in your Google sheet as use it as you want.
