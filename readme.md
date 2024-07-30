# Web Scrapping Tokopedia Product using Selenium and BS4

## Objective

The goal is to web scrape all [tokopedia](https://tokopedia.com/) product (in this instance are 'seblak') and then transform all the information we gathered to tabular data for data analysis.

## Dataset Table Information

<center>

| Column     | Description                                                                              |
|------------|------------------------------------------------------------------------------------------|
| ID         | Unique identifier (format = age - row - item)                                            |
| Product    | Name of the product                                                                      |
| Seller     | Name of the seller                                                                       |
| City       | Where is the seller located. This might affect shipping price based on buyer's location. |
| Sell Count | How many times the item has been sold                                                    |
| Rating     | Rating of the product                                                                    |

</center>

## Sample Dataset

<center>

| ID       | Product                                           | Price   | Seller                   | City              | Sell Count | Rating |
|----------|---------------------------------------------------|---------|--------------------------|-------------------|------------|--------|
| P1-R1-B1 | Kylafood Seblak Original                          | 21375.0 | kylafood                 | Bandung           | 10000.0    | 4.9    |
| P1-R1-B2 | Seblak Rafael/Seblak Coet Instan Halal            | 26600.0 | Foodstocks               | Jakarta Selatan   | 100.0      | 5.0    |
| P1-R1-B3 | Seblak Instan Ceu Nthien Khas Bandung Rasana N... | 17000.0 | Central Seblak Nusantara | Tangerang Selatan | 2000.0     | 4.9    |
| P1-R1-B4 | KERUPUK SEBLAK MENTAH 1KG WARNA WARNI - Mawar ... | 26500.0 | BociKakang               | Jakarta Selatan   | 250.0      | 5.0    |
| P1-R1-B5 | KERUPUK MENTAH KERUPUK SEBLAK MENTAH 500 GR - ... | 14500.0 | BociKakang               | Jakarta Selatan   | 100.0      | 4.9    |
| P1-R1-B6 | Seblak Instan Pedas Home Made                     | 3500.0  | the Dhecip               | Tangerang Selatan | 3000.0     | 4.9    |

</center>
