# Project 002 — Sales & Commercial Performance Dashboard

**Stack:** Power BI · DAX · Power Query  
**Domain:** Commercial Performance & Discount Analysis  
**Industry:** Sports Retail — Global Markets

---

## Business Context

A global sports retail company operating across five markets (Europe, LATAM, Pacific Asia, USCA and Africa) needed a unified view of its commercial performance across product categories, markets and payment channels.

The finance and commercial teams were working with fragmented data and had two key unresolved questions: which markets and categories were driving revenue, and whether the company’s discount strategy was generating incremental sales or simply eroding margin.

**The goal:** build a single interactive Power BI dashboard that consolidates all commercial KPIs — sales, transactions and discount impact — into one view, with a dynamic button panel that lets the user switch between perspectives without navigating between pages.

**Key business questions answered:**
- What is the total sales volume, transaction count and discount spend?
- - Which markets generate the most revenue?
  - - How do sales trend year over year and month by month?
    - - Which product categories drive the most transactions and revenue?
      - - How is revenue distributed across payment types (Cash, Debit, Payment, Transfer)?
        - - What is the real impact of discounts on net benefit?
         
          - ---

          ## Dashboard Overview

          A single-page dashboard with an interactive button panel that switches between three views: **Total Sales**, **Transactions** and **Discount analysis** — allowing the user to explore the same dataset from different commercial angles without changing pages.

          ### Key KPI Cards
          - **Transactions:** 181K total orders
          - - **Discount:** $3.730K total discount amount
            - - **Benefit:** $3.966K net benefit
              - - **Total Sales:** $36.784K gross revenue
               
                - ### Visuals
                - - **Sales by Year** — multi-year line chart tracking revenue progression
                  - - **Sales by Market** — horizontal bar chart comparing Europe, LATAM, Pacific Asia, USCA and Africa
                    - - **Sales by Payment Type** — stacked bar chart showing Cash, Debit, Payment and Transfer over time
                      - - **Sales by Category** — horizontal bar chart ranking product categories by revenue
                       
                        - ![Dashboard Overview](./Dashboard%20General%20Overview.pdf)
                       
                        - ---

                        ## What Was Built

                        - **Data model:** relationships between sales facts, products, markets, segments and a custom date table
                        - - **DAX measures:** Total Sales, Net Benefit, Total Discount Amount, Transaction Count, dynamic measures switching via button panel
                          - - **Power Query:** data cleaning, null handling, country name standardisation, date table with English locale
                            - - **Interactive button panel:** user-controlled toggle between Sales, Transactions and Discount views on a single page
                              - - **Cross-filtering:** all visuals respond to market, category, year and payment type selections
                               
                                - ---

                                ## Key KPIs

                                | KPI | Value | Description |
                                |---|---|---|
                                | Total Sales | $36.78M | Gross revenue across all markets and categories |
                                | Total Transactions | 181K | Total order volume |
                                | Total Discount | $3.73M | Absolute discount spend |
                                | Net Benefit | $3.97M | Revenue contribution after discounts |

                                ---

                                ## Files

                                | File | Description |
                                |---|---|
                                | `dashboard.pbix` | Power BI source file |
                                | `Dashboard General Overview.pdf` | Dashboard export |

                                ---

                                ## Stack

                                ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
                                ![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square)
                                ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square)
