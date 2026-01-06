# Scored Search for Magento 2

Scored Search is a Magento 2 extension that enhances product search by allowing scoring, custom ranking factors, and multiple search engines (MySQL, OpenSearch).

## Features
- Score products by attribute (e.g., price, created_at, custom attributes)
- Apply multipliers and normalization factors
- Support for MySQL and OpenSearch
- Configurable search result alignment and sorting
- Fully translatable (i18n support)

## Requirements
- Magento Open Source / Adobe Commerce 2.4.x or higher

## Installation
1. Copy the extension into `app/code/Ppl/ScoredSearch`  
   or install via Composer:
   ```bash
   composer require ppl/scored_search

Enable the module:
   ```bash
   bin/magento module:enable Pliou_ScoredSearch
   bin/magento setup:upgrade
   bin/magento cache:flush

2. Configuration

Go to Stores → Configuration → Scored Search to configure:
Scoring attribute
Multipliers
Root transformation
Search engine (MySQL / OpenSearch)

4. Usage

Use product search in the store frontend.

Search results will be ranked and scored according to your configuration.

Compatible with Layered Navigation and standard Magento sorting.

5. Support

For questions and support, please contact:
📧 pliousnin@gmail.com

##License

This extension is licensed under a proprietary license.
See LICENSE.txt
 for details.
