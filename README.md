# ScrapyBeginner
This is beginner practice project to learn about Scrapy.<hr>

<h3>Commands</h3><br>

<ol>
    <li>pip install scrapy</li> (install scrapy)
    <li>scrapy startproject projectname</li> (create scrapy project)
    <li>scrapy shell</li> (open scrapy shell to interrogate page structure)
    <li>>>> fetch('https://www.whiskyshop.com/scotch-whisky')</li> (I use fetch command to see response, we get 200 so it's mean it's working)
    <li>response</li> (When we fetch information then it's response saved in response variable, type response in shell and see what it gives)
    <li> response  ->  200 https://www.whiskyshop.com/scotch-whisky></li>
    <li>response.css('div.product-item-info')</li> (it will give us all div from response of this class 'product-item-info')
    <li>response.css('div.product-item-info').get() it will get first response</li> 
    <li>To run your scrapy follow this command <strong> scrapy crawl nameofspider</strong><li>
    <li>If u want to save your output in Json file follow this command<li><strong> scrapy crawl nameofspider -o filename.json</strong>
    <li>capital O overwrite file completeley and small o will append</li>
</ol>













