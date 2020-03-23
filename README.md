# Google-Sheets-CMS-Skeleton

We use [Tabletop](https://github.com/jsoma/tabletop) to link our spreadsheet to the website. I've already created a demo in the `index.html` file so you can get started.

## The Basic Setup

Make a [Google Spreadsheet](http://drive.google.com). Give it some column headers, give it some content.

    Name                Category         Healthiness 
    Carrot              Vegetable        Adequate
    Pork Shoulder       Meat             Questionable
    Bubblegum           Candy            Super High
  
Now go up to the `File` menu and pick `Publish to the web`. Just publish it.
Now that you've published your sheet, you now need to share it, too.

1. Click the **Share** link in the upper right-hand corner
2. Click the very pale **Advanced** button
3. **Change...** access to "On - Anyone with a link"
4. Make sure **Access: Anyone** says **Can view**, since you don't want strangers editing your data
5. Click **Save**

Copy the **Link to Share**. Your URL should look something like `https://docs.google.com/spreadsheets/d/1Io6W5XitNvifEXER9ECTsbHhAjXsQLq6VEz7kSPDPiQ/edit?usp=sharing`. It should **not** have a `/d/e` in it. This is the link you will use as the key in Tabletop.

Now you should be able to retrieve all the data in your Google sheet as use it as you want.
