HackGT Fall 2014
================

GT Thrift Shop @ HackGT - Fall 2014
Submission: http://challengepost.com/software/gt-thrift-shop

Idea
-----

Currently, students sell their items (books, furniture etc), through a Facebook group called GT Thrift Shop (https://www.facebook.com/groups/199456403537988/?ref=br_tf). This can get inefficient due to the lack of a catalog and search functionality. The aim of the new Thrift Shop is to use eBay's Finding API, along with the Milo API to create this service for Georgia Tech students.

Features
--------

- Selling functionality - Make a post on eBay (visible only to GT students (limit by location)) through the app. Currently implemented by passing sellerIDs registered with app, and restricting results to those sellers.
- Buying functionality - Catalog of items being sold, organized in departments. Bidding. Buy it Now.

ebay API Usage
--------------

- Trading API: AddItem, GetItem, GetSellerList
- Finding API: findItemsByKeywords, findItemsAdvanced
- Sandbox usage for test transactions and demo listings.
