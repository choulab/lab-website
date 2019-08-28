---
title: Ordering supplies
linktitle: Ordering supplies
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu: 
  handbook:
    parent: Getting Started
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 60
---

## Finding the item

If you are looking for a reagent or supply, you can follow these steps:

- First consult the ``Master Inventory`` spreadsheet. The item might have been ordered before and is still available in the lab. If it is no longer available, at least the spreadsheet can guide your choice of vendors and brands. When selecting vendors, be cognizant of price vs. quality. Practice best judgment.
- Login to USource and see if the item is available with UofT's list of preferred vendors
- If it's a reagent used in other papers, consult literature for vendor, catalog no., and lot no.


## Placing an order
Fill out item information in the `Lab Purchasing YYYY` spreadsheet, where YYYY is the current year. For example, if the year is 2020, the spreadsheet would be `Lab Purchasing 2020`. (This sheet is updated every year, and is used to generate the Master Inventory sheet). Once you've done that, use one of the following ways to order the item:

- **uSource**: This is UofT's eProcurement platform with a list of preferred vendors. Use this whenever possible as it's the fastest way. Log into [Usource](https://www.procurement.utoronto.ca/programs-and-services/usource) using your account and a request will be sent to Leo for approval. Once approved, the item will be ordered automatically and arrive in a few days.

- **Purchase Order (PO)**: For vendors not on uSource and accepts POs, fill out this [template](/) and send it to Leo for ordering

- **Credit Card (CC)**: For vendors not accepting POs, the lab has a CC that can be used to order reagents. Email Leo with an URL to the relevant items in the `Lab Purchasing YYYY` spreadsheet to order.

{{% alert note %}}
If you need something urgent (e.g. same day), you can try to find it on [Medstore](https://www.uoftmedstore.com/index.sz). They will accept PO from our lab. 
{{% /alert %}}


## Receiving items
After the order has been placed, Leo will move the item record from the ‘request’ tab to the ‘month’ tab in the `Lab Purchasing YYYY` spreadsheet. When you receive the item, do the following:

- Place the packing list that comes with the item into the shared lab folder ‘PACKING LIST’. This is required for departmental auditing purposes
- Use a permanent marker to record the receipt date on the item itself
- Find the item and record its lot no. on google sheet ‘Lab Purchasing YYYY’

{{% alert note %}}
This is important! A python script will periodically update our `Master Inventory` spreadsheet using the `Lab Purchasing YYYY` spreadsheet ONLY if the lot no. is recorded
{{% /alert %}}

## Depleted items

When an item has been depleted, and you’re the one throwing it out, do the following:

- Find the item record in the `Master Inventory` spreadsheet using a combination of its lot no. and catalog no.
- Change its availability box from ‘available’ to ‘unavailable’
- This will be critical for keeping the lab inventory up to date!!!
- P.S. the python script will automatically delete any items from the Master Inventory that is marked ‘unavailable’ and >5 years old from purchase date
