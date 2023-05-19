# Myntra-Preprocessing

This is raw dataset which is scraped from Official [Myntra](https://www.myntra.com/) Website. I need someone who can find insight from raw data and need pure data structure in form of **CSV**.

## Task
1. Need Preprocess data by removing noise/wantless things (no need to do for Null values)
2. Improve Quality of data by added some feature if possible (Need Data Walkthrough, Analysis & Visit on [Myntra](https://www.myntra.com/))
3. Document your work in excel file provide to you here is link
4. Save CSV File in **output** File

## Future Scope
1. Data Visualisation using plotly, pandasAI, PivitTableJS

## Dataset

This dataset consist of 3 categories for now in **men.json** file
* [Topwear](https://www.myntra.com/men-topwear)
* [T-Shirts](https://www.myntra.com/men-tshirts)
* [Casual Shirts](https://www.myntra.com/men-casual-shirts)

## JSON FILE Structure

```python
data = {
    'category': {}, # Dictionary data contains list of category and dumpy values ( Not required for this analysis)
    'products': {
          
        'url_link_1': {
            'name':'value',                      
            'brand':'value',
            'size':'value',
            'image':'value',
            'actual_price':'value',
            'discount_price' :'value',
            'discount_percentage':'value',
            'sub_category':[]
        },
        'url_link_2' : { ... },
        ...
    }
}
```
| name                | description                           | 
|---------------------|---------------------------------------|
| url_link_1          | relative path link of myntra website  |
| name                | Name of product                       |
| brand               | Name of brand                         |                       
| size                | Available size                        | 
| image               | IMage of Product                      |
| actual_price        | Acttual Price of product              |
| discount_price      | Discount Price of product             |
| discount_percentage | Discount Percentage of product        |
| sub_category        | List of Subcategory of product        |









