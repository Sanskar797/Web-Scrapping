# Web-Scrapping
Bata Retail Store Data Scrape - store name addess , phone no ,coordination 
 i select the BATA Retail store for web scraping 
- than i imported all required library where request is for extract the html code and beautifulsoup help me to extract data from that html code
- than hit the website with the help of request lib 
- than i created the variable called data that contain all the data that i need to extract in div object .where i use find all because i want all object inside div
- with the help of loop i extract and append my data in empty list .which data i want to append for that i specify the class 
- and text give me only text content and strip remove all the spaces 
- than i created a dataframe and store in csv file 
- know going to find longitude and latitude  with the help of inbuilt lib called geocode
- in geocode i give address as my input they give me longitude and latitude as output than append in list 
- what problem i faced here is for finding  longitude and latitude i have to give for accurate  address if not they give me error 
- how i solve that problem is by giving the input of two col together that contain city and pincode . with that my problem is solved 
- than i make the final data by combine all the col and store into csv file 
