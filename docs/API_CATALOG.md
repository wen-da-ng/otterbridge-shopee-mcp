# Shopee Open API v2 catalogue

Generated from the [Shopee Open Platform docs](https://open.shopee.com/documents/v2) on 2026-11-24 by `scripts/build-api-registry.mjs`. Don't edit by hand.

**454 endpoints in 30 modules.** 363 of them can be called by a "Seller In House System" app. Every endpoint can be reached through `shopee_api_read` / `shopee_api_write` (`api: "v2.module.function"`); `shopee_search_api` and `shopee_describe_api` look them up. Many common jobs also have a dedicated tool (see README).

Legend: ✅ callable by a Seller In House System app · 🌏 cross-border sellers only · 📎 file upload · Type is the auth level (shop / merchant / public / user / principal).

## Modules

| Module | Endpoints | ✅ Callable |
| --- | ---: | ---: |
| [AccountHealth](#accounthealth) | 6 | 6 |
| [Add-On Deal](#add-on-deal) | 14 | 14 |
| [Ads](#ads) | 22 | 22 |
| [AMS](#ams) | 36 | 0 |
| [BrandPortal](#brandportal) | 11 | 0 |
| [Bundle Deal](#bundle-deal) | 10 | 10 |
| [Discount](#discount) | 12 | 12 |
| [FBS](#fbs) | 4 | 4 |
| [FirstMile](#firstmile) | 18 | 18 |
| [Follow Prize](#follow-prize) | 6 | 6 |
| [GlobalProduct](#globalproduct) | 33 | 33 |
| [Installation](#installation) | 2 | 0 |
| [Livestream](#livestream) | 25 | 0 |
| [Logistics](#logistics) | 50 | 50 |
| [Media](#media) | 6 | 6 |
| [MediaSpace](#mediaspace) | 6 | 6 |
| [Merchant](#merchant) | 6 | 6 |
| [Order](#order) | 22 | 22 |
| [Payment](#payment) | 18 | 18 |
| [Product](#product) | 64 | 62 |
| [Public](#public) | 6 | 6 |
| [Push](#push) | 4 | 4 |
| [Returns](#returns) | 15 | 15 |
| [SBS](#sbs) | 6 | 6 |
| [Shop](#shop) | 9 | 9 |
| [ShopCategory](#shopcategory) | 7 | 7 |
| [ShopFlashSale](#shopflashsale) | 11 | 11 |
| [TopPicks](#toppicks) | 4 | 4 |
| [Video](#video) | 15 | 0 |
| [Voucher](#voucher) | 6 | 6 |

## AccountHealth

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.account_health.get_late_orders`](https://open.shopee.com/documents/v2/v2.account_health.get_late_orders?module=103&type=1) | GET | shop | ✅ | Get the Late Orders to take action to avoid order cancellation and penalty points. |
| [`v2.account_health.get_listings_with_issues`](https://open.shopee.com/documents/v2/v2.account_health.get_listings_with_issues?module=103&type=1) | GET | shop | ✅ | Get the Problematic Listings to improve the listings to avoid incurring penalty points. |
| [`v2.account_health.get_metric_source_detail`](https://open.shopee.com/documents/v2/v2.account_health.get_metric_source_detail?module=103&type=1) | GET | shop | ✅ | Get the Affected Orders / Relevant Listings / Relevant Violations details of metrics. |
| [`v2.account_health.get_penalty_point_history`](https://open.shopee.com/documents/v2/v2.account_health.get_penalty_point_history?module=103&type=1) | GET | shop | ✅ | Get the penalty point records generated in the current quarter. |
| [`v2.account_health.get_punishment_history`](https://open.shopee.com/documents/v2/v2.account_health.get_punishment_history?module=103&type=1) | GET | shop | ✅ | Get the punishment records generated in the current quarter. |
| [`v2.account_health.get_shop_performance`](https://open.shopee.com/documents/v2/v2.account_health.get_shop_performance?module=103&type=1) | GET | shop | ✅ | The data metrics of shop performance. |

## Add-On Deal

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.add_on_deal.add_add_on_deal`](https://open.shopee.com/documents/v2/v2.add_on_deal.add_add_on_deal?module=111&type=1) | POST | shop | ✅ | Add Add-on Deal |
| [`v2.add_on_deal.add_add_on_deal_main_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.add_add_on_deal_main_item?module=111&type=1) | POST | shop | ✅ | Add Add-on Deal Main Item |
| [`v2.add_on_deal.add_add_on_deal_sub_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.add_add_on_deal_sub_item?module=111&type=1) | POST | shop | ✅ | Add Add-on Deal Sub Item |
| [`v2.add_on_deal.delete_add_on_deal`](https://open.shopee.com/documents/v2/v2.add_on_deal.delete_add_on_deal?module=111&type=1) | POST | shop | ✅ | Delete Add-on Deal |
| [`v2.add_on_deal.delete_add_on_deal_main_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.delete_add_on_deal_main_item?module=111&type=1) | POST | shop | ✅ | Delete Add-on Deal Main Item |
| [`v2.add_on_deal.delete_add_on_deal_sub_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.delete_add_on_deal_sub_item?module=111&type=1) | POST | shop | ✅ | Delete Add-on Deal Sub Item |
| [`v2.add_on_deal.end_add_on_deal`](https://open.shopee.com/documents/v2/v2.add_on_deal.end_add_on_deal?module=111&type=1) | POST | shop | ✅ | End Add-on Deal |
| [`v2.add_on_deal.get_add_on_deal`](https://open.shopee.com/documents/v2/v2.add_on_deal.get_add_on_deal?module=111&type=1) | GET | shop | ✅ | Get Add-on Deal |
| [`v2.add_on_deal.get_add_on_deal_list`](https://open.shopee.com/documents/v2/v2.add_on_deal.get_add_on_deal_list?module=111&type=1) | GET | shop | ✅ | Get Add-on Deal List |
| [`v2.add_on_deal.get_add_on_deal_main_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.get_add_on_deal_main_item?module=111&type=1) | GET | shop | ✅ | Get Add-on Deal Main Item |
| [`v2.add_on_deal.get_add_on_deal_sub_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.get_add_on_deal_sub_item?module=111&type=1) | GET | shop | ✅ | Get Add-on Deal Sub Item |
| [`v2.add_on_deal.update_add_on_deal`](https://open.shopee.com/documents/v2/v2.add_on_deal.update_add_on_deal?module=111&type=1) | POST | shop | ✅ | Update Add-on Deal |
| [`v2.add_on_deal.update_add_on_deal_main_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.update_add_on_deal_main_item?module=111&type=1) | POST | shop | ✅ | Update Add-on Deal Main Item |
| [`v2.add_on_deal.update_add_on_deal_sub_item`](https://open.shopee.com/documents/v2/v2.add_on_deal.update_add_on_deal_sub_item?module=111&type=1) | POST | shop | ✅ | Update Add-on Deal Sub Item |

## Ads

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.ads.check_create_gms_product_campaign_eligibility`](https://open.shopee.com/documents/v2/v2.ads.check_create_gms_product_campaign_eligibility?module=117&type=1) | GET | shop | ✅ | Check the seller's eligibility in creating a GMS campaign |
| [`v2.ads.create_gms_product_campaign`](https://open.shopee.com/documents/v2/v2.ads.create_gms_product_campaign?module=117&type=1) | POST | shop | ✅ | Create a GMS campaign |
| [`v2.ads.create_manual_product_ads`](https://open.shopee.com/documents/v2/v2.ads.create_manual_product_ads?module=117&type=1) | POST | shop | ✅ | Use this API to create Manual Selection Product Ads |
| [`v2.ads.edit_gms_item_product_campaign`](https://open.shopee.com/documents/v2/v2.ads.edit_gms_item_product_campaign?module=117&type=1) | POST | shop | ✅ | Add/remove items to/from the GMS Campaign |
| [`v2.ads.edit_gms_product_campaign`](https://open.shopee.com/documents/v2/v2.ads.edit_gms_product_campaign?module=117&type=1) | POST | shop | ✅ | Edit a GMS campaign |
| [`v2.ads.edit_manual_product_ad_keywords`](https://open.shopee.com/documents/v2/v2.ads.edit_manual_product_ad_keywords?module=117&type=1) | POST | shop | ✅ | Use this API to edit Manual Selection Product Ad Keywords |
| [`v2.ads.edit_manual_product_ads`](https://open.shopee.com/documents/v2/v2.ads.edit_manual_product_ads?module=117&type=1) | POST | shop | ✅ | Use this API to edit Manual Selection Product Ads |
| [`v2.ads.get_all_cpc_ads_daily_performance`](https://open.shopee.com/documents/v2/v2.ads.get_all_cpc_ads_daily_performance?module=117&type=1) | GET | shop | ✅ | Use this API to get Shop level CPC ads multiple-days daily performance. |
| [`v2.ads.get_all_cpc_ads_hourly_performance`](https://open.shopee.com/documents/v2/v2.ads.get_all_cpc_ads_hourly_performance?module=117&type=1) | GET | shop | ✅ | Use this API to get Shop level CPC ads single-date hourly performance. |
| [`v2.ads.get_create_product_ad_budget_suggestion`](https://open.shopee.com/documents/v2/v2.ads.get_create_product_ad_budget_suggestion?module=117&type=1) | GET | shop | ✅ | Call this API to get budget suggestion for product ads creation |
| [`v2.ads.get_gms_campaign_performance`](https://open.shopee.com/documents/v2/v2.ads.get_gms_campaign_performance?module=117&type=1) | POST | shop | ✅ | Get GMS Campaign performance |
| [`v2.ads.get_gms_item_performance`](https://open.shopee.com/documents/v2/v2.ads.get_gms_item_performance?module=117&type=1) | POST | shop | ✅ | Get GMS Item performance 1. The response returned is sorted by item_id 2. Only items with performance will be returned |
| [`v2.ads.get_product_campaign_daily_performance`](https://open.shopee.com/documents/v2/v2.ads.get_product_campaign_daily_performance?module=117&type=1) | GET | shop | ✅ | Use this API to get Product level ads multiple-days daily performance. |
| [`v2.ads.get_product_campaign_hourly_performance`](https://open.shopee.com/documents/v2/v2.ads.get_product_campaign_hourly_performance?module=117&type=1) | GET | shop | ✅ | Use this API to get Product level ads single-day hourly performance. |
| [`v2.ads.get_product_level_campaign_id_list`](https://open.shopee.com/documents/v2/v2.ads.get_product_level_campaign_id_list?module=117&type=1) | GET | shop | ✅ | Call this API to fetch all the product campaign ids displayed on advertiser platform under a specific Shop |
| [`v2.ads.get_product_level_campaign_setting_info`](https://open.shopee.com/documents/v2/v2.ads.get_product_level_campaign_setting_info?module=117&type=1) | GET | shop | ✅ | Call this API to fetch all the campaign setting info under this Shop. |
| [`v2.ads.get_product_recommended_roi_target`](https://open.shopee.com/documents/v2/v2.ads.get_product_recommended_roi_target?module=117&type=1) | GET | shop | ✅ | Get Product Recommended ROI Target |
| [`v2.ads.get_recommended_item_list`](https://open.shopee.com/documents/v2/v2.ads.get_recommended_item_list?module=117&type=1) | GET | shop | ✅ | Use this API to get the list of recommended SKU (Shop level) with the corresponding tag, i.e top search/best selling/best ROI tag. |
| [`v2.ads.get_recommended_keyword_list`](https://open.shopee.com/documents/v2/v2.ads.get_recommended_keyword_list?module=117&type=1) | GET | shop | ✅ | Use this API to get the list of Recommended keywords by item and optionally a search keyword |
| [`v2.ads.get_shop_toggle_info`](https://open.shopee.com/documents/v2/v2.ads.get_shop_toggle_info?module=117&type=1) | GET | shop | ✅ | Use this API to get Shop level info - i.e. seller's toggle status is on/off |
| [`v2.ads.get_total_balance`](https://open.shopee.com/documents/v2/v2.ads.get_total_balance?module=117&type=1) | GET | shop | ✅ | Use this API to return the seller's Real-time total balance of their ads credit including the paid credits and free credits. |
| [`v2.ads.list_gms_user_deleted_item`](https://open.shopee.com/documents/v2/v2.ads.list_gms_user_deleted_item?module=117&type=1) | POST | shop | ✅ | List GMS items that have been removed from the Campaign by seller |

## AMS

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.ams.add_all_products_to_open_campaign`](https://open.shopee.com/documents/v2/v2.ams.add_all_products_to_open_campaign?module=127&type=1) | POST | shop |  | Add all eligible products into the Open Campaign. We will only return the general error that caused the whole task failure, without returni… |
| [`v2.ams.batch_add_products_to_open_campaign`](https://open.shopee.com/documents/v2/v2.ams.batch_add_products_to_open_campaign?module=127&type=1) | POST | shop |  | Batch add products to the Open Campaign for a given list of product IDs |
| [`v2.ams.batch_edit_products_open_campaign_setting`](https://open.shopee.com/documents/v2/v2.ams.batch_edit_products_open_campaign_setting?module=127&type=1) | POST | shop |  | Batch update open campaign settings for a given list of product IDs |
| [`v2.ams.batch_get_products_suggested_rate`](https://open.shopee.com/documents/v2/v2.ams.batch_get_products_suggested_rate?module=127&type=1) | GET | shop |  | Fetch suggested rates for a given list of product IDs |
| [`v2.ams.batch_remove_products_open_campaign_setting`](https://open.shopee.com/documents/v2/v2.ams.batch_remove_products_open_campaign_setting?module=127&type=1) | POST | shop |  | Batch update products from Open Campaign for a given list of product IDs |
| [`v2.ams.create_new_targeted_campaign`](https://open.shopee.com/documents/v2/v2.ams.create_new_targeted_campaign?module=127&type=1) | POST | shop |  | Create a new campaign with custom product & affiliate selections, and basic info filling. |
| [`v2.ams.edit_affiliate_list_of_targeted_campaign`](https://open.shopee.com/documents/v2/v2.ams.edit_affiliate_list_of_targeted_campaign?module=127&type=1) | POST | shop |  | Modify the selected affiliate list in an existing target campaign |
| [`v2.ams.edit_all_products_open_campaign_setting`](https://open.shopee.com/documents/v2/v2.ams.edit_all_products_open_campaign_setting?module=127&type=1) | POST | shop |  | Update for all products in the Open Campaign. We will only return the general error that caused the whole task failure, without returning t… |
| [`v2.ams.edit_product_list_of_targeted_campaign`](https://open.shopee.com/documents/v2/v2.ams.edit_product_list_of_targeted_campaign?module=127&type=1) | POST | shop |  | Modify the selected product list in an existing target campaign |
| [`v2.ams.get_affiliate_performance`](https://open.shopee.com/documents/v2/v2.ams.get_affiliate_performance?module=127&type=1) | GET | shop |  | Retrieve affiliate performance of the shop. |
| [`v2.ams.get_auto_add_new_product_toggle_status`](https://open.shopee.com/documents/v2/v2.ams.get_auto_add_new_product_toggle_status?module=127&type=1) | GET | shop |  | Check if auto-add new product is currently enabled |
| [`v2.ams.get_campaign_key_metrics_performance`](https://open.shopee.com/documents/v2/v2.ams.get_campaign_key_metrics_performance?module=127&type=1) | GET | shop |  | Retrieve key metrics for Open and Targeted campaigns |
| [`v2.ams.get_content_performance`](https://open.shopee.com/documents/v2/v2.ams.get_content_performance?module=127&type=1) | GET | shop |  | Retrieve content performance of the shop |
| [`v2.ams.get_conversion_report`](https://open.shopee.com/documents/v2/v2.ams.get_conversion_report?module=127&type=1) | GET | shop |  | Retrieve the shop's conversion report with details about each order, item, affiliate, campaign.You can filter results using one or multiple… |
| [`v2.ams.get_managed_affiliate_list`](https://open.shopee.com/documents/v2/v2.ams.get_managed_affiliate_list?module=127&type=1) | GET | shop |  | Returns affiliates that are saved to managed affiliate list |
| [`v2.ams.get_open_campaign_added_product`](https://open.shopee.com/documents/v2/v2.ams.get_open_campaign_added_product?module=127&type=1) | GET | shop |  | Retrieve all products currently in the Open Campaign, including campaign status, commission rate, and promotion period |
| [`v2.ams.get_open_campaign_batch_task_result`](https://open.shopee.com/documents/v2/v2.ams.get_open_campaign_batch_task_result?module=127&type=1) | GET | shop |  | Get open campaign batch task result |
| [`v2.ams.get_open_campaign_not_added_product`](https://open.shopee.com/documents/v2/v2.ams.get_open_campaign_not_added_product?module=127&type=1) | GET | shop |  | Retrieve eligible products not yet added to the Open Campaign |
| [`v2.ams.get_open_campaign_performance`](https://open.shopee.com/documents/v2/v2.ams.get_open_campaign_performance?module=127&type=1) | GET | shop |  | Retrieve all products in the Open Campaign along with performance data |
| [`v2.ams.get_optimization_suggestion_product`](https://open.shopee.com/documents/v2/v2.ams.get_optimization_suggestion_product?module=127&type=1) | GET | shop |  | Retrieve products with suggestions to improve performance |
| [`v2.ams.get_performance_data_update_time`](https://open.shopee.com/documents/v2/v2.ams.get_performance_data_update_time?module=127&type=1) | GET | shop |  | Retrieve the latest date of AMS dashboard data metrics update. |
| [`v2.ams.get_product_performance`](https://open.shopee.com/documents/v2/v2.ams.get_product_performance?module=127&type=1) | GET | shop |  | Retrieve product performance of the shop. |
| [`v2.ams.get_recommended_affiliate_list`](https://open.shopee.com/documents/v2/v2.ams.get_recommended_affiliate_list?module=127&type=1) | GET | shop |  | Returns top 200 recommended affiliates that can be added to a campaign |
| [`v2.ams.get_shop_performance`](https://open.shopee.com/documents/v2/v2.ams.get_shop_performance?module=127&type=1) | GET | shop |  | Retrieve overall key metrics for all channels or specific channels. |
| [`v2.ams.get_shop_suggested_rate`](https://open.shopee.com/documents/v2/v2.ams.get_shop_suggested_rate?module=127&type=1) | GET | shop |  | Retrieve suggested rates for all eligible products |
| [`v2.ams.get_targeted_campaign_addable_product_list`](https://open.shopee.com/documents/v2/v2.ams.get_targeted_campaign_addable_product_list?module=127&type=1) | GET | shop |  | Returns a list of products that can be added to a targeted campaign |
| [`v2.ams.get_targeted_campaign_list`](https://open.shopee.com/documents/v2/v2.ams.get_targeted_campaign_list?module=127&type=1) | GET | shop |  | Retrieve all current targeted campaigns created by the seller |
| [`v2.ams.get_targeted_campaign_performance`](https://open.shopee.com/documents/v2/v2.ams.get_targeted_campaign_performance?module=127&type=1) | GET | shop |  | Retrieve a list of Targeted Campaigns and their performance data |
| [`v2.ams.get_targeted_campaign_settings`](https://open.shopee.com/documents/v2/v2.ams.get_targeted_campaign_settings?module=127&type=1) | GET | shop |  | For each campaign, return: campaign basic info (name, status, promotion period, message), selected product list (with product name & ID), s… |
| [`v2.ams.get_validation_list`](https://open.shopee.com/documents/v2/v2.ams.get_validation_list?module=127&type=1) | GET | shop |  | Retrieve the seller's AMS validation bill |
| [`v2.ams.get_validation_report`](https://open.shopee.com/documents/v2/v2.ams.get_validation_report?module=127&type=1) | GET | shop |  | Retrieve detailed information for a specific validation bill |
| [`v2.ams.query_affiliate_list`](https://open.shopee.com/documents/v2/v2.ams.query_affiliate_list?module=127&type=1) | GET | shop |  | Retrieve affiliate information by affiliate id. |
| [`v2.ams.remove_all_products_open_campaign_setting`](https://open.shopee.com/documents/v2/v2.ams.remove_all_products_open_campaign_setting?module=127&type=1) | POST | shop |  | Remove the entire product list of Open Campaign. We will only return the general error that caused the whole task failure, without returnin… |
| [`v2.ams.terminate_targeted_campaign`](https://open.shopee.com/documents/v2/v2.ams.terminate_targeted_campaign?module=127&type=1) | POST | shop |  | Change target campaign status to "terminated" to stop all affiliate promotion activity |
| [`v2.ams.update_auto_add_new_product_setting`](https://open.shopee.com/documents/v2/v2.ams.update_auto_add_new_product_setting?module=127&type=1) | POST | shop |  | Change auto-add toggle and default commission rate setting |
| [`v2.ams.update_basic_info_of_targeted_campaign`](https://open.shopee.com/documents/v2/v2.ams.update_basic_info_of_targeted_campaign?module=127&type=1) | POST | shop |  | Edit campaign name, promotion period, message, and budget (if the shop is whitelisted) of target campaign |

## BrandPortal

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.principal.get_clip_video_performance`](https://open.shopee.com/documents/v2/v2.principal.get_clip_video_performance?module=139&type=1) | POST | principal |  | Queries video clip performance data for the specified videos within the selected time range. Supports request granularity by day, week, mon… |
| [`v2.principal.get_content_affiliate_performance`](https://open.shopee.com/documents/v2/v2.principal.get_content_affiliate_performance?module=139&type=1) | POST | principal |  | Queries affiliate performance data for the specified content items within the selected time range. Supports request granularity by day, wee… |
| [`v2.principal.get_principal_affiliate_performance`](https://open.shopee.com/documents/v2/v2.principal.get_principal_affiliate_performance?module=139&type=1) | POST | principal |  | Queries affiliate performance data for the specified principal within the selected time range. Supports request granularity by day, week, m… |
| [`v2.principal.get_principal_livestream_performance`](https://open.shopee.com/documents/v2/v2.principal.get_principal_livestream_performance?module=139&type=1) | POST | principal |  | Queries livestream performance data for the specified principal within the selected time range. Supports request granularity by day, week, … |
| [`v2.principal.get_principal_sales_performance_detail`](https://open.shopee.com/documents/v2/v2.principal.get_principal_sales_performance_detail?module=139&type=1) | POST | principal |  | Queries the business performance data aggregated at principal level for the specified regions within the selected time range. Supports requ… |
| [`v2.principal.get_principal_video_performance`](https://open.shopee.com/documents/v2/v2.principal.get_principal_video_performance?module=139&type=1) | POST | principal |  | Queries video performance data for the specified principal within the selected time range. Supports request granularity by day, week, month… |
| [`v2.principal.get_session_livestream_performance`](https://open.shopee.com/documents/v2/v2.principal.get_session_livestream_performance?module=139&type=1) | POST | principal |  | Queries livestream session performance data for the specified sessions within the selected time range. Supports request granularity by day,… |
| [`v2.principal.get_shop_affiliate_performance`](https://open.shopee.com/documents/v2/v2.principal.get_shop_affiliate_performance?module=139&type=1) | POST | principal |  | Queries affiliate performance data for the specified shops within the selected time range. Supports request granularity by day, week, month… |
| [`v2.principal.get_shop_livestream_performance`](https://open.shopee.com/documents/v2/v2.principal.get_shop_livestream_performance?module=139&type=1) | POST | principal |  | Queries livestream performance data for the specified shops within the selected time range. Supports request granularity by day, week, mont… |
| [`v2.principal.get_shop_sales_performance_detail`](https://open.shopee.com/documents/v2/v2.principal.get_shop_sales_performance_detail?module=139&type=1) | POST | principal |  | Queries the business performance data of stores under the specified entity within the selected time range. Supports request granularity by … |
| [`v2.principal.get_shop_video_performance`](https://open.shopee.com/documents/v2/v2.principal.get_shop_video_performance?module=139&type=1) | POST | principal |  | Queries video performance data for the specified shops within the selected time range. Supports request granularity by day, week, month, qu… |

## Bundle Deal

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.bundle_deal.add_bundle_deal`](https://open.shopee.com/documents/v2/v2.bundle_deal.add_bundle_deal?module=110&type=1) | POST | shop | ✅ | create bundle deal. Relevant restrictions refer to FAQ：https://open.shopee.com/faq/254 |
| [`v2.bundle_deal.add_bundle_deal_item`](https://open.shopee.com/documents/v2/v2.bundle_deal.add_bundle_deal_item?module=110&type=1) | POST | shop | ✅ | add product to bundle deal |
| [`v2.bundle_deal.delete_bundle_deal`](https://open.shopee.com/documents/v2/v2.bundle_deal.delete_bundle_deal?module=110&type=1) | POST | shop | ✅ | delete bundle deal |
| [`v2.bundle_deal.delete_bundle_deal_item`](https://open.shopee.com/documents/v2/v2.bundle_deal.delete_bundle_deal_item?module=110&type=1) | POST | shop | ✅ | delete product in bundle deal |
| [`v2.bundle_deal.end_bundle_deal`](https://open.shopee.com/documents/v2/v2.bundle_deal.end_bundle_deal?module=110&type=1) | POST | shop | ✅ | end bundle deal |
| [`v2.bundle_deal.get_bundle_deal`](https://open.shopee.com/documents/v2/v2.bundle_deal.get_bundle_deal?module=110&type=1) | GET | shop | ✅ | get bundle deal detail |
| [`v2.bundle_deal.get_bundle_deal_item`](https://open.shopee.com/documents/v2/v2.bundle_deal.get_bundle_deal_item?module=110&type=1) | GET | shop | ✅ | get bundle deal item |
| [`v2.bundle_deal.get_bundle_deal_list`](https://open.shopee.com/documents/v2/v2.bundle_deal.get_bundle_deal_list?module=110&type=1) | GET | shop | ✅ | get bundle deal list |
| [`v2.bundle_deal.update_bundle_deal`](https://open.shopee.com/documents/v2/v2.bundle_deal.update_bundle_deal?module=110&type=1) | POST | shop | ✅ | update bundle deal. Relevant restrictions refer to FAQ：https://open.shopee.com/faq/254 |
| [`v2.bundle_deal.update_bundle_deal_item`](https://open.shopee.com/documents/v2/v2.bundle_deal.update_bundle_deal_item?module=110&type=1) | POST | shop | ✅ | update product in bundle deal |

## Discount

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.discount.add_discount`](https://open.shopee.com/documents/v2/v2.discount.add_discount?module=99&type=1) | POST | shop | ✅ | Use this api to add shop discount activity |
| [`v2.discount.add_discount_item`](https://open.shopee.com/documents/v2/v2.discount.add_discount_item?module=99&type=1) | POST | shop | ✅ | Use this api to add shop discount item. |
| [`v2.discount.delete_discount`](https://open.shopee.com/documents/v2/v2.discount.delete_discount?module=99&type=1) | POST | shop | ✅ | Use this api to delete one discount activity |
| [`v2.discount.delete_discount_item`](https://open.shopee.com/documents/v2/v2.discount.delete_discount_item?module=99&type=1) | POST | shop | ✅ | Use this api to delete items of the discount activity |
| [`v2.discount.delete_sip_discount`](https://open.shopee.com/documents/v2/v2.discount.delete_sip_discount?module=99&type=1) | POST | shop | ✅ | Delete SIP Overseas Discounts for SIP affiliate region. Please use Primary shop's Shop ID to request, and provide the region of the Affilia… |
| [`v2.discount.end_discount`](https://open.shopee.com/documents/v2/v2.discount.end_discount?module=99&type=1) | POST | shop | ✅ | Use this api to end shop discount activity |
| [`v2.discount.get_discount`](https://open.shopee.com/documents/v2/v2.discount.get_discount?module=99&type=1) | GET | shop | ✅ | Use this api to get one shop discount activity detail |
| [`v2.discount.get_discount_list`](https://open.shopee.com/documents/v2/v2.discount.get_discount_list?module=99&type=1) | GET | shop | ✅ | Use this api to get shop discount activity list |
| [`v2.discount.get_sip_discounts`](https://open.shopee.com/documents/v2/v2.discount.get_sip_discounts?module=99&type=1) | GET | shop | ✅ | Get SIP Overseas Discounts. Only regions that have upcoming/ongoing discounts will be returned. Please use Primary shop's Shop ID to reques… |
| [`v2.discount.set_sip_discount`](https://open.shopee.com/documents/v2/v2.discount.set_sip_discount?module=99&type=1) | POST | shop | ✅ | Set SIP Overseas Discount for SIP affiliate region. Please use Primary shop's Shop ID to request, and provide the region and discount rate … |
| [`v2.discount.update_discount`](https://open.shopee.com/documents/v2/v2.discount.update_discount?module=99&type=1) | POST | shop | ✅ | Use this api to update one discount information |
| [`v2.discount.update_discount_item`](https://open.shopee.com/documents/v2/v2.discount.update_discount_item?module=99&type=1) | POST | shop | ✅ | Use this api to update items of the discount promotion. |

## FBS

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.fbs.query_br_shop_block_status`](https://open.shopee.com/documents/v2/v2.fbs.query_br_shop_block_status?module=126&type=1) | GET | shop | ✅ | This API checks whether an FBS shop is blocked due to invoice-related issues. When blocked, the shop cannot create new Inbound Requests, an… |
| [`v2.fbs.query_br_shop_enrollment_status`](https://open.shopee.com/documents/v2/v2.fbs.query_br_shop_enrollment_status?module=126&type=1) | GET | shop | ✅ | This API checks whether a given shop_id is eligible to enroll in the Brazil Fulfilled-by-Shopee (FBS) service. |
| [`v2.fbs.query_br_shop_invoice_error`](https://open.shopee.com/documents/v2/v2.fbs.query_br_shop_invoice_error?module=126&type=1) | GET | shop | ✅ | This API handles failed invoice issuance for FBS-related processes, covering Inbound Requests, RTS Requests, Sales Orders, and Move Transfe… |
| [`v2.fbs.query_br_sku_block_status`](https://open.shopee.com/documents/v2/v2.fbs.query_br_sku_block_status?module=126&type=1) | GET | shop | ✅ | This API checks whether an FBS product is blocked due to invoice-related issues. When blocked, the product cannot be included in new Inboun… |

## FirstMile

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.first_mile.bind_courier_delivery_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.bind_courier_delivery_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to bind first mile tracking number for courier delivery method. |
| [`v2.first_mile.bind_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.bind_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to bind first mile tracking number. |
| [`v2.first_mile.cancel_courier_delivery_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.cancel_courier_delivery_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to cancel first mile tracking number for courier delivery method. |
| [`v2.first_mile.generate_and_bind_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.generate_and_bind_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to generate first mile tracking number for courier delivery method. |
| [`v2.first_mile.generate_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.generate_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to generate first mile tracking number. |
| [`v2.first_mile.get_channel_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_channel_list?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get first mile channel list. |
| [`v2.first_mile.get_courier_delivery_channel_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_courier_delivery_channel_list?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get courier information for courier delivery method. |
| [`v2.first_mile.get_courier_delivery_detail`](https://open.shopee.com/documents/v2/v2.first_mile.get_courier_delivery_detail?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get first mile detail for courier delivery method. |
| [`v2.first_mile.get_courier_delivery_tracking_number_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_courier_delivery_tracking_number_list?module=96&type=1) | POST | shop | ✅🌏 | Use this api to get tracking number for courier delivery method. |
| [`v2.first_mile.get_courier_delivery_waybill`](https://open.shopee.com/documents/v2/v2.first_mile.get_courier_delivery_waybill?module=96&type=1) | POST | shop | ✅🌏 | Use this api to get first mile waybill file for courier delivery method. |
| [`v2.first_mile.get_detail`](https://open.shopee.com/documents/v2/v2.first_mile.get_detail?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get first mile detail. |
| [`v2.first_mile.get_tracking_number_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_tracking_number_list?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get first mile tracking number list. |
| [`v2.first_mile.get_transit_warehouse_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_transit_warehouse_list?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get transit warehouse list which is used for first mile tracking number generation for courier delivery method. |
| [`v2.first_mile.get_unbind_order_list`](https://open.shopee.com/documents/v2/v2.first_mile.get_unbind_order_list?module=96&type=1) | GET | shop | ✅🌏 | Use this api to get unbind order list. It will only return orders unbound to first-mile that were created within the past 6 months. |
| [`v2.first_mile.get_waybill`](https://open.shopee.com/documents/v2/v2.first_mile.get_waybill?module=96&type=1) | POST | shop | ✅🌏 | Use this api to get first mile waybill file. |
| [`v2.first_mile.get_waybill_filelink`](https://open.shopee.com/documents/v2/v2.first_mile.get_waybill_filelink?module=96&type=1) | POST | shop | ✅🌏 | Use this api to get first mile waybill file link. |
| [`v2.first_mile.unbind_first_mile_tracking_number`](https://open.shopee.com/documents/v2/v2.first_mile.unbind_first_mile_tracking_number?module=96&type=1) | POST | shop | ✅🌏 | Use this api to unbind first mile. |
| [`v2.first_mile.unbind_first_mile_tracking_number_all`](https://open.shopee.com/documents/v2/v2.first_mile.unbind_first_mile_tracking_number_all?module=96&type=1) | POST | shop | ✅🌏 | Use this api to unbind orders from first mile tracking number or binding ID. |

## Follow Prize

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.follow_prize.add_follow_prize`](https://open.shopee.com/documents/v2/v2.follow_prize.add_follow_prize?module=113&type=1) | POST | shop | ✅ | OpenAPI add Follow Prize |
| [`v2.follow_prize.delete_follow_prize`](https://open.shopee.com/documents/v2/v2.follow_prize.delete_follow_prize?module=113&type=1) | POST | shop | ✅ | delete_follow_prize |
| [`v2.follow_prize.end_follow_prize`](https://open.shopee.com/documents/v2/v2.follow_prize.end_follow_prize?module=113&type=1) | POST | shop | ✅ | end follow prize |
| [`v2.follow_prize.get_follow_prize_detail`](https://open.shopee.com/documents/v2/v2.follow_prize.get_follow_prize_detail?module=113&type=1) | GET | shop | ✅ | get_follow_prize_detail |
| [`v2.follow_prize.get_follow_prize_list`](https://open.shopee.com/documents/v2/v2.follow_prize.get_follow_prize_list?module=113&type=1) | GET | shop | ✅ | OpenAPI get_follow_prize_list |
| [`v2.follow_prize.update_follow_prize`](https://open.shopee.com/documents/v2/v2.follow_prize.update_follow_prize?module=113&type=1) | POST | shop | ✅ | update_follow_prize |

## GlobalProduct

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.global_product.add_global_item`](https://open.shopee.com/documents/v2/v2.global_product.add_global_item?module=90&type=1) | POST | merchant | ✅🌏 | Add global item. Only for China mainland sellers using China Seller Centre(CNSC). More details in https://shopee.cn/cooperate/46/53/926. |
| [`v2.global_product.add_global_model`](https://open.shopee.com/documents/v2/v2.global_product.add_global_model?module=90&type=1) | POST | merchant | ✅🌏 | Add global model. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.category_recommend`](https://open.shopee.com/documents/v2/v2.global_product.category_recommend?module=90&type=1) | GET | merchant | ✅🌏 | Recommend category by item name. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.create_publish_task`](https://open.shopee.com/documents/v2/v2.global_product.create_publish_task?module=90&type=1) | POST | merchant | ✅🌏 | Create publish task for global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.delete_global_item`](https://open.shopee.com/documents/v2/v2.global_product.delete_global_item?module=90&type=1) | POST | merchant | ✅🌏 | Delete global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.delete_global_model`](https://open.shopee.com/documents/v2/v2.global_product.delete_global_model?module=90&type=1) | POST | merchant | ✅🌏 | Delete global model. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_attribute_tree`](https://open.shopee.com/documents/v2/v2.global_product.get_attribute_tree?module=90&type=1) | GET | merchant | ✅🌏 | Get the mtsku attribute trees for categories |
| [`v2.global_product.get_brand_list`](https://open.shopee.com/documents/v2/v2.global_product.get_brand_list?module=90&type=1) | GET | merchant | ✅🌏 | Use this call to get a list of brand. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_category`](https://open.shopee.com/documents/v2/v2.global_product.get_category?module=90&type=1) | GET | merchant | ✅🌏 | Get global category. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_global_item_id`](https://open.shopee.com/documents/v2/v2.global_product.get_global_item_id?module=90&type=1) | GET | merchant | ✅🌏 | Get get_global_item_id by item_id. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_global_item_info`](https://open.shopee.com/documents/v2/v2.global_product.get_global_item_info?module=90&type=1) | GET | merchant | ✅🌏 | Get global item info.Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_global_item_limit`](https://open.shopee.com/documents/v2/v2.global_product.get_global_item_limit?module=90&type=1) | GET | merchant | ✅🌏 | Get global item upload control. |
| [`v2.global_product.get_global_item_list`](https://open.shopee.com/documents/v2/v2.global_product.get_global_item_list?module=90&type=1) | GET | merchant | ✅🌏 | Get global item id list. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_global_model_list`](https://open.shopee.com/documents/v2/v2.global_product.get_global_model_list?module=90&type=1) | GET | merchant | ✅🌏 | Get global model list. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_local_adjustment_rate`](https://open.shopee.com/documents/v2/v2.global_product.get_local_adjustment_rate?module=90&type=1) | GET | merchant | ✅🌏 | Retrieves the adjustment rate that converts CB stock price into local-warehouse price for a specific shop. |
| [`v2.global_product.get_publish_task_result`](https://open.shopee.com/documents/v2/v2.global_product.get_publish_task_result?module=90&type=1) | GET | merchant | ✅🌏 | Get publish task result for global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_publishable_shop`](https://open.shopee.com/documents/v2/v2.global_product.get_publishable_shop?module=90&type=1) | GET | merchant | ✅🌏 | Get publishable shop list for global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_published_list`](https://open.shopee.com/documents/v2/v2.global_product.get_published_list?module=90&type=1) | GET | merchant | ✅🌏 | Get published item list of global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_recommend_attribute`](https://open.shopee.com/documents/v2/v2.global_product.get_recommend_attribute?module=90&type=1) | GET | merchant | ✅🌏 | Get recommend attributes. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.get_shop_publishable_status`](https://open.shopee.com/documents/v2/v2.global_product.get_shop_publishable_status?module=90&type=1) | GET | merchant | ✅🌏 | Get publishable shop list for global item in pages. |
| [`v2.global_product.get_size_chart_detail`](https://open.shopee.com/documents/v2/v2.global_product.get_size_chart_detail?module=90&type=1) | GET | merchant | ✅🌏 | Get new size chart detail |
| [`v2.global_product.get_size_chart_list`](https://open.shopee.com/documents/v2/v2.global_product.get_size_chart_list?module=90&type=1) | GET | merchant | ✅🌏 | Get size chart list |
| [`v2.global_product.get_variations`](https://open.shopee.com/documents/v2/v2.global_product.get_variations?module=90&type=1) | GET | merchant | ✅🌏 | Get the standardized tier variation defined by Shopee, which is currently a three-layer tree structure. The top layer is variations, the se… |
| [`v2.global_product.init_tier_variation`](https://open.shopee.com/documents/v2/v2.global_product.init_tier_variation?module=90&type=1) | POST | merchant | ✅🌏 | Only for China mainland sellers and Korean sellers. If you only define color, it is one tier, if you define color and size, it is two tier.… |
| [`v2.global_product.search_global_attribute_value_list`](https://open.shopee.com/documents/v2/v2.global_product.search_global_attribute_value_list?module=90&type=1) | POST | merchant | ✅🌏 | this api is for searching attribute value list for attribute with support_search_value flag |
| [`v2.global_product.set_sync_field`](https://open.shopee.com/documents/v2/v2.global_product.set_sync_field?module=90&type=1) | POST | merchant | ✅🌏 | Set auto sync field. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.support_size_chart`](https://open.shopee.com/documents/v2/v2.global_product.support_size_chart?module=90&type=1) | GET | merchant | ✅🌏 | Get category support size chart. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_global_item`](https://open.shopee.com/documents/v2/v2.global_product.update_global_item?module=90&type=1) | POST | merchant | ✅🌏 | Update global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_global_model`](https://open.shopee.com/documents/v2/v2.global_product.update_global_model?module=90&type=1) | POST | merchant | ✅🌏 | Update global model. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_price`](https://open.shopee.com/documents/v2/v2.global_product.update_price?module=90&type=1) | POST | merchant | ✅🌏 | Update global price. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_size_chart`](https://open.shopee.com/documents/v2/v2.global_product.update_size_chart?module=90&type=1) | POST | merchant | ✅🌏 | Update size chart for global item. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_stock`](https://open.shopee.com/documents/v2/v2.global_product.update_stock?module=90&type=1) | POST | merchant | ✅🌏 | Update global stock. Only for China mainland sellers and Korean sellers. |
| [`v2.global_product.update_tier_variation`](https://open.shopee.com/documents/v2/v2.global_product.update_tier_variation?module=90&type=1) | POST | merchant | ✅🌏 | Update global product tier variation. Only for China mainland sellers and Korean sellers.This api can only be used without changing the tie… |

## Installation

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.installation.receive_installation_order`](https://open.shopee.com/documents/v2/v2.installation.receive_installation_order?module=138&type=1) | POST | public |  | Receive installation order. Use this API to move installation status to PARCEL_PICKED_UP. |
| [`v2.installation.validate_installation_otp_code`](https://open.shopee.com/documents/v2/v2.installation.validate_installation_otp_code?module=138&type=1) | POST | public |  | Validate installation order OTP code. Use this API to validate OTP code when parcel status is PARCEL_PICKED_UP, PARCEL_REQUEST_CANCELLED, o… |

## Livestream

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.livestream.add_item_list`](https://open.shopee.com/documents/v2/v2.livestream.add_item_list?module=125&type=1) | POST | user |  | Add items to item bag. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.apply_item_set`](https://open.shopee.com/documents/v2/v2.livestream.apply_item_set?module=125&type=1) | POST | user |  | Add product set to item bag. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.ban_user_comment`](https://open.shopee.com/documents/v2/v2.livestream.ban_user_comment?module=125&type=1) | POST | user |  | Ban the user from posting comments. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.create_session`](https://open.shopee.com/documents/v2/v2.livestream.create_session?module=125&type=1) | POST | user |  | Create a new live stream, include basic information, like cover, title, description, type (test live or normal live). (For TW, ID, TH, PH, … |
| [`v2.livestream.delete_item_list`](https://open.shopee.com/documents/v2/v2.livestream.delete_item_list?module=125&type=1) | POST | user |  | Delete items from item bag. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.delete_show_item`](https://open.shopee.com/documents/v2/v2.livestream.delete_show_item?module=125&type=1) | POST | user |  | Unshow showing item. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.end_session`](https://open.shopee.com/documents/v2/v2.livestream.end_session?module=125&type=1) | POST | user |  | End Live. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_item_count`](https://open.shopee.com/documents/v2/v2.livestream.get_item_count?module=125&type=1) | GET | user |  | Get the number of items in the shopping bag, including the current number of items in the shopping bag, the upper limit of the number, etc.… |
| [`v2.livestream.get_item_list`](https://open.shopee.com/documents/v2/v2.livestream.get_item_list?module=125&type=1) | GET | user |  | Get the detail information of item in item bag, including item id, item serial number, etc.(For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_item_set_item_list`](https://open.shopee.com/documents/v2/v2.livestream.get_item_set_item_list?module=125&type=1) | GET | user |  | Get the item list of the product set, including item name, id, etc. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_item_set_list`](https://open.shopee.com/documents/v2/v2.livestream.get_item_set_list?module=125&type=1) | GET | user |  | Get the product set of the live stream, including the product set name, id, and item number. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_latest_comment_list`](https://open.shopee.com/documents/v2/v2.livestream.get_latest_comment_list?module=125&type=1) | GET | user |  | Get live stream room comments in the last 10 seconds, including user id, user name, comment id, comment content, and comment time. (For TW,… |
| [`v2.livestream.get_like_item_list`](https://open.shopee.com/documents/v2/v2.livestream.get_like_item_list?module=125&type=1) | GET | user |  | Get the item list of My Likes tab.(For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_recent_item_list`](https://open.shopee.com/documents/v2/v2.livestream.get_recent_item_list?module=125&type=1) | GET | user |  | Get the item list of the Recently tab. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_session_detail`](https://open.shopee.com/documents/v2/v2.livestream.get_session_detail?module=125&type=1) | GET | user |  | Get basic information about the live streaming room, including cover, title, description, type (test live or normal live), create time, upd… |
| [`v2.livestream.get_session_item_metric`](https://open.shopee.com/documents/v2/v2.livestream.get_session_item_metric?module=125&type=1) | GET | user |  | Get real-time indicator data of live stream products, including product clicks, add-to-cart, etc. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.get_session_metric`](https://open.shopee.com/documents/v2/v2.livestream.get_session_metric?module=125&type=1) | GET | user |  | Get real-time indicator data of the live stream room, including the number of likes, comments, shares, views, etc.(For TW, ID, TH, PH, MY, … |
| [`v2.livestream.get_show_item`](https://open.shopee.com/documents/v2/v2.livestream.get_show_item?module=125&type=1) | GET | user |  | Get the showing item. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.post_comment`](https://open.shopee.com/documents/v2/v2.livestream.post_comment?module=125&type=1) | POST | user |  | Post comment in the live stream as streamer. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.start_session`](https://open.shopee.com/documents/v2/v2.livestream.start_session?module=125&type=1) | POST | user |  | Start Live. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.unban_user_comment`](https://open.shopee.com/documents/v2/v2.livestream.unban_user_comment?module=125&type=1) | POST | user |  | Unban a user from posting comments. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.update_item_list`](https://open.shopee.com/documents/v2/v2.livestream.update_item_list?module=125&type=1) | POST | user |  | Update the order of items in item bag. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.update_session`](https://open.shopee.com/documents/v2/v2.livestream.update_session?module=125&type=1) | POST | user |  | Update live stream information, including cover, title, description, and type (test live or normal live). (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.update_show_item`](https://open.shopee.com/documents/v2/v2.livestream.update_show_item?module=125&type=1) | POST | user |  | Set the showing item. (For TW, ID, TH, PH, MY, SG, VN) |
| [`v2.livestream.upload_image`](https://open.shopee.com/documents/v2/v2.livestream.upload_image?module=125&type=1) | POST | user | 📎 | Upload an image as the live stream cover.(For TW, ID, TH, PH, MY, SG, VN) |

## Logistics

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.logistics.batch_ship_order`](https://open.shopee.com/documents/v2/v2.logistics.batch_ship_order?module=95&type=1) | POST | shop | ✅ | Use this api to batch initiate logistics including arrange pickup, dropoff or shipment for non-integrated logistic channels. Should call v2… |
| [`v2.logistics.batch_update_tpf_warehouse_tracking_status`](https://open.shopee.com/documents/v2/v2.logistics.batch_update_tpf_warehouse_tracking_status?module=95&type=1) | POST | shop | ✅ | For CB orders that fulfilled by 3PF, support 3PF Warehouse Vendors to update the tpf_tracking_status when 3PF warehouse receive the order a… |
| [`v2.logistics.check_polygon_update_status`](https://open.shopee.com/documents/v2/v2.logistics.check_polygon_update_status?module=95&type=1) | POST | shop | ✅ | Only available for Brazil sellers. Use this API to check the status of polygon file uploaded for BR Entrega Turbo channel (Channel ID: 9002… |
| [`v2.logistics.create_booking_shipping_document`](https://open.shopee.com/documents/v2/v2.logistics.create_booking_shipping_document?module=95&type=1) | POST | shop | ✅ | Use this api to create shipping document task for each booking and this API is only available after retrieving the tracking number. |
| [`v2.logistics.create_shipping_document`](https://open.shopee.com/documents/v2/v2.logistics.create_shipping_document?module=95&type=1) | POST | shop | ✅ | Use this api to create shipping document task for each order or package and this API is only available after retrieving the tracking number. |
| [`v2.logistics.create_shipping_document_job`](https://open.shopee.com/documents/v2/v2.logistics.create_shipping_document_job?module=95&type=1) | POST | shop | ✅ | This API creates a shipping document job for selected documents. The system receives requests and returns a job ID along with success and f… |
| [`v2.logistics.delete_address`](https://open.shopee.com/documents/v2/v2.logistics.delete_address?module=95&type=1) | POST | shop | ✅ | Use this api to delete address. |
| [`v2.logistics.delete_special_operating_hour`](https://open.shopee.com/documents/v2/v2.logistics.delete_special_operating_hour?module=95&type=1) | POST | shop | ✅ | This API is used to delete a specific special operating hour for a seller. This API allows sellers to manage their operating hours by remov… |
| [`v2.logistics.download_booking_shipping_document`](https://open.shopee.com/documents/v2/v2.logistics.download_booking_shipping_document?module=95&type=1) | POST | shop | ✅ | Use this api to download shipping_document. You have to call v2.logistics.create_booking_shipping_document to create a new shipping documen… |
| [`v2.logistics.download_shipping_document`](https://open.shopee.com/documents/v2/v2.logistics.download_shipping_document?module=95&type=1) | POST | shop | ✅ | Use this api to download shipping_document. You have to call v2.logistics.create_shipping_document to create a new shipping document task f… |
| [`v2.logistics.download_shipping_document_job`](https://open.shopee.com/documents/v2/v2.logistics.download_shipping_document_job?module=95&type=1) | POST | shop | ✅ | This API allows users to download the shipping document associated with a specific job ID. It checks the job status before proceeding with … |
| [`v2.logistics.download_shipping_document_job_filelink`](https://open.shopee.com/documents/v2/v2.logistics.download_shipping_document_job_filelink?module=95&type=1) | POST | shop | ✅ | This API allows users to download the shipping document associated with a specific job ID. It checks the job status before proceeding with … |
| [`v2.logistics.download_to_label`](https://open.shopee.com/documents/v2/v2.logistics.download_to_label?module=95&type=1) | POST | shop | ✅ | Use the API to download the TO label that should be attached to the carton before drop-off at the warehouse (Only for TW channel_id:30029). |
| [`v2.logistics.download_to_label_filelink`](https://open.shopee.com/documents/v2/v2.logistics.download_to_label_filelink?module=95&type=1) | POST | shop | ✅ | Use the API to download the TO label that should be attached to the carton before drop-off at the warehouse (Only for TW channel_id:30029).… |
| [`v2.logistics.get_address_list`](https://open.shopee.com/documents/v2/v2.logistics.get_address_list?module=95&type=1) | GET | shop | ✅ | For integrated logistics channel, use this call to get pickup address for pickup mode order. |
| [`v2.logistics.get_booking_shipping_document_data_info`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_shipping_document_data_info?module=95&type=1) | POST | shop | ✅ | Use this api to fetch the logistics information of a booking these info can be used for airwaybill printing. Dedicated for crossborder SLS … |
| [`v2.logistics.get_booking_shipping_document_parameter`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_shipping_document_parameter?module=95&type=1) | POST | shop | ✅ | Use this api to get the selectable shipping_document_type and suggested shipping_document_type. |
| [`v2.logistics.get_booking_shipping_document_result`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_shipping_document_result?module=95&type=1) | POST | shop | ✅ | Use this api to retrieve the status of the shipping document task. Document will be available for download only after the status change to … |
| [`v2.logistics.get_booking_shipping_parameter`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_shipping_parameter?module=95&type=1) | GET | shop | ✅ | Use this api to get the parameter "info_needed" from the response to check if the booking has pickup or dropoff. This api will also return … |
| [`v2.logistics.get_booking_tracking_info`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_tracking_info?module=95&type=1) | GET | shop | ✅ | Use this api to get the logistics tracking information of a booking. |
| [`v2.logistics.get_booking_tracking_number`](https://open.shopee.com/documents/v2/v2.logistics.get_booking_tracking_number?module=95&type=1) | GET | shop | ✅ | After arranging shipment (v2.logistics.ship_booking) for the integrated channel, use this api to get the tracking_number, which is a requir… |
| [`v2.logistics.get_channel_list`](https://open.shopee.com/documents/v2/v2.logistics.get_channel_list?module=95&type=1) | GET | shop | ✅ | Use this api to get all supported logistic channels. |
| [`v2.logistics.get_mart_packaging_info`](https://open.shopee.com/documents/v2/v2.logistics.get_mart_packaging_info?module=95&type=1) | GET | shop | ✅ | [Only for ID mart seller] The API allows sellers to retrieve their current packaging fee settings. |
| [`v2.logistics.get_mass_shipping_parameter`](https://open.shopee.com/documents/v2/v2.logistics.get_mass_shipping_parameter?module=95&type=1) | POST | shop | ✅ | Use this api to check if package support pickup, dropoff, non-integrated. For pickup, return address and pickup time id options. For dropof… |
| [`v2.logistics.get_mass_tracking_number`](https://open.shopee.com/documents/v2/v2.logistics.get_mass_tracking_number?module=95&type=1) | POST | shop | ✅ | After arranging shipment (v2.logistics.mass_ship_order) for the integrated channel, use this api to get the tracking_number, which is a req… |
| [`v2.logistics.get_operating_hour_restrictions`](https://open.shopee.com/documents/v2/v2.logistics.get_operating_hour_restrictions?module=95&type=1) | GET | shop | ✅ | This API is designed to retrieve all restrictions related to inputting operating hours for the v2.logistics.update_operating_hours function… |
| [`v2.logistics.get_operating_hours`](https://open.shopee.com/documents/v2/v2.logistics.get_operating_hours?module=95&type=1) | GET | shop | ✅ | This API is utilized to retrieve the existing operating hours of sellers including Pickup Operating Hours, Special Hours, Instant Operating… |
| [`v2.logistics.get_order_count_limit_outside_instant_operating_time`](https://open.shopee.com/documents/v2/v2.logistics.get_order_count_limit_outside_instant_operating_time?module=95&type=1) | GET | shop | ✅ | Use this API to retrieve the current order count limit configuration for orders outside the Instant operating time window if the daily orde… |
| [`v2.logistics.get_pause_status`](https://open.shopee.com/documents/v2/v2.logistics.get_pause_status?module=95&type=1) | GET | shop | ✅ | This API returns the pause status of logistics channels under the shop. Pausing allows the shop to temporarily prevent buyers from placing … |
| [`v2.logistics.get_shipping_document_data_info`](https://open.shopee.com/documents/v2/v2.logistics.get_shipping_document_data_info?module=95&type=1) | POST | shop | ✅ | Use this api to fetch the logistics information of an order, these info can be used for self-design AWB printing. Besides, this api support… |
| [`v2.logistics.get_shipping_document_job_status`](https://open.shopee.com/documents/v2/v2.logistics.get_shipping_document_job_status?module=95&type=1) | POST | shop | ✅ | This API retrieves the status of a shipping document job using the job ID provided. |
| [`v2.logistics.get_shipping_document_parameter`](https://open.shopee.com/documents/v2/v2.logistics.get_shipping_document_parameter?module=95&type=1) | POST | shop | ✅ | Use this api to get the selectable shipping_document_type and suggested shipping_document_type. |
| [`v2.logistics.get_shipping_document_result`](https://open.shopee.com/documents/v2/v2.logistics.get_shipping_document_result?module=95&type=1) | POST | shop | ✅ | Use this api to retrieve the status of the shipping document task. Document will be available for download only after the status change to … |
| [`v2.logistics.get_shipping_parameter`](https://open.shopee.com/documents/v2/v2.logistics.get_shipping_parameter?module=95&type=1) | GET | shop | ✅ | Use this api to check if the package support pickup, dropoff, or non-integrated method. For pickup, will return addresses and pickup time i… |
| [`v2.logistics.get_tracking_info`](https://open.shopee.com/documents/v2/v2.logistics.get_tracking_info?module=95&type=1) | GET | shop | ✅ | Use this api to get the logistics tracking information of an order. |
| [`v2.logistics.get_tracking_number`](https://open.shopee.com/documents/v2/v2.logistics.get_tracking_number?module=95&type=1) | GET | shop | ✅ | After arranging shipment (v2.logistics.ship_order) for the integrated channel, use this api to get the tracking_number, which is a required… |
| [`v2.logistics.mass_ship_order`](https://open.shopee.com/documents/v2/v2.logistics.mass_ship_order?module=95&type=1) | POST | shop | ✅ | Use this api to initiate logistics including arrange pickup, dropoff or shipment for non-integrated logistic channels. Should call v2.logis… |
| [`v2.logistics.set_address_config`](https://open.shopee.com/documents/v2/v2.logistics.set_address_config?module=95&type=1) | POST | shop | ✅ | Use this API to set address config of your shop. |
| [`v2.logistics.set_mart_packaging_info`](https://open.shopee.com/documents/v2/v2.logistics.set_mart_packaging_info?module=95&type=1) | POST | shop | ✅ | [Only for ID mart seller] This API allows sellers to set up their packaging fee info. Through this API, sellers can enable or disable packa… |
| [`v2.logistics.set_order_count_limit_outside_instant_operating_time`](https://open.shopee.com/documents/v2/v2.logistics.set_order_count_limit_outside_instant_operating_time?module=95&type=1) | POST | shop | ✅ | Use this API to configure how orders outside the Instant operating time window are accepted. This allows the shop to either accept all such… |
| [`v2.logistics.set_pause_status`](https://open.shopee.com/documents/v2/v2.logistics.set_pause_status?module=95&type=1) | POST | shop | ✅ | Use this API to set the pause status of logistics channels under the shop. Pausing allows the shop to temporarily prevent buyers from placi… |
| [`v2.logistics.ship_booking`](https://open.shopee.com/documents/v2/v2.logistics.ship_booking?module=95&type=1) | POST | shop | ✅ | Use this api to initiate logistics including arrange pickup, dropoff. Should call v2.logistics.get_booking_shipping_parameter to fetch all … |
| [`v2.logistics.ship_order`](https://open.shopee.com/documents/v2/v2.logistics.ship_order?module=95&type=1) | POST | shop | ✅ | Use this api to initiate logistics including arrange pickup, dropoff or shipment for non-integrated logistic channels. Should call v2.logis… |
| [`v2.logistics.update_address`](https://open.shopee.com/documents/v2/v2.logistics.update_address?module=95&type=1) | POST | shop | ✅ | Use this API to update the address of a shop. |
| [`v2.logistics.update_channel`](https://open.shopee.com/documents/v2/v2.logistics.update_channel?module=95&type=1) | POST | shop | ✅ | Use this api to update shop level logistics channel's configuration. |
| [`v2.logistics.update_operating_hours`](https://open.shopee.com/documents/v2/v2.logistics.update_operating_hours?module=95&type=1) | POST | shop | ✅ | This API is designed to allow sellers to update their operating hours. It is essential that the values provided in this API align with the … |
| [`v2.logistics.update_self_collection_order_logistics`](https://open.shopee.com/documents/v2/v2.logistics.update_self_collection_order_logistics?module=95&type=1) | POST | shop | ✅ | Use this api to update the order status for buyer to collect the orders directly from your pharmacy. This includes indicating that order is… |
| [`v2.logistics.update_shipping_order`](https://open.shopee.com/documents/v2/v2.logistics.update_shipping_order?module=95&type=1) | POST | shop | ✅ | For pickup method only, use this api to update pickup address and pickup time for packages meet: 1) package's fulfillment status is LOGISTI… |
| [`v2.logistics.update_tracking_status`](https://open.shopee.com/documents/v2/v2.logistics.update_tracking_status?module=95&type=1) | POST | shop | ✅ | Only available for Brazil sellers. This API is only available for orders/parcels which are fulfilled by BR Seller Logistics channel (logist… |
| [`v2.logistics.upload_serviceable_polygon`](https://open.shopee.com/documents/v2/v2.logistics.upload_serviceable_polygon?module=95&type=1) | POST | shop | ✅📎 | Only available for Brazil sellers. Use this API to upload KML file for shop level serviceability setting for BR Entrega Turbo channel (Chan… |

## Media

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.media.cancel_video_upload`](https://open.shopee.com/documents/v2/v2.media.cancel_video_upload?module=130&type=1) | POST | public | ✅ | Use this API to cancel an ongoing video upload task. If the upload has already succeeded, failed, or been cancelled, this operation will fa… |
| [`v2.media.complete_video_upload`](https://open.shopee.com/documents/v2/v2.media.complete_video_upload?module=130&type=1) | POST | public | ✅ | Use this API to finalize a video upload task. Once called, the system will transcode all uploaded video parts and prepare the video for use… |
| [`v2.media.get_video_upload_result`](https://open.shopee.com/documents/v2/v2.media.get_video_upload_result?module=130&type=1) | GET | public | ✅ | Use this API to retrieve the current status and result of a video upload task. You can also use video_upload_result_push to get notified im… |
| [`v2.media.init_video_upload`](https://open.shopee.com/documents/v2/v2.media.init_video_upload?module=130&type=1) | POST | public | ✅ | Use this API to initialize a new video upload task and obtain a unique upload session ID. |
| [`v2.media.upload_image`](https://open.shopee.com/documents/v2/v2.media.upload_image?module=130&type=1) | POST | public | ✅📎 | Use this API to upload images and support different business scenarios through business and scene parameters. |
| [`v2.media.upload_video_part`](https://open.shopee.com/documents/v2/v2.media.upload_video_part?module=130&type=1) | POST | public | ✅📎 | Use this API to upload a video file in parts. |

## MediaSpace

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.media_space.cancel_video_upload`](https://open.shopee.com/documents/v2/v2.media_space.cancel_video_upload?module=91&type=1) | POST | shop | ✅ | Cancel a video upload session |
| [`v2.media_space.complete_video_upload`](https://open.shopee.com/documents/v2/v2.media_space.complete_video_upload?module=91&type=1) | POST | public | ✅ | Complete the video upload and starts the transcoding process when all parts are uploaded successfully. |
| [`v2.media_space.get_video_upload_result`](https://open.shopee.com/documents/v2/v2.media_space.get_video_upload_result?module=91&type=1) | GET | shop | ✅ | Query the upload status and result of video upload. |
| [`v2.media_space.init_video_upload`](https://open.shopee.com/documents/v2/v2.media_space.init_video_upload?module=91&type=1) | POST | shop | ✅ | Initiate video upload session. Video duration should be between 10s and 60s (inclusive). |
| [`v2.media_space.upload_image`](https://open.shopee.com/documents/v2/v2.media_space.upload_image?module=91&type=1) | POST | public | ✅📎 | Use this API to upload multiple image files (less than 9 images). |
| [`v2.media_space.upload_video_part`](https://open.shopee.com/documents/v2/v2.media_space.upload_video_part?module=91&type=1) | POST | public | ✅📎 | Upload video file by part using the upload_id in initiate_video_upload. The request Content-Type of this API should be of multipart/form-da… |

## Merchant

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.merchant.get_merchant_info`](https://open.shopee.com/documents/v2/v2.merchant.get_merchant_info?module=93&type=1) | GET | merchant | ✅🌏 | Use this call to get information of merchant |
| [`v2.merchant.get_merchant_prepaid_account_list`](https://open.shopee.com/documents/v2/v2.merchant.get_merchant_prepaid_account_list?module=93&type=1) | GET | merchant | ✅🌏 | Use this api to get seller’s courier prepaid account. |
| [`v2.merchant.get_merchant_warehouse_list`](https://open.shopee.com/documents/v2/v2.merchant.get_merchant_warehouse_list?module=93&type=1) | POST | merchant | ✅🌏 | Get merchant warehouse with page |
| [`v2.merchant.get_merchant_warehouse_location_list`](https://open.shopee.com/documents/v2/v2.merchant.get_merchant_warehouse_location_list?module=93&type=1) | GET | merchant | ✅🌏 | get merchant warehouse location list |
| [`v2.merchant.get_shop_list_by_merchant`](https://open.shopee.com/documents/v2/v2.merchant.get_shop_list_by_merchant?module=93&type=1) | GET | merchant | ✅🌏 | Use this call to get shop_list bound to merchant_id. |
| [`v2.merchant.get_warehouse_eligible_shop_list`](https://open.shopee.com/documents/v2/v2.merchant.get_warehouse_eligible_shop_list?module=93&type=1) | POST | merchant | ✅🌏 | Get eligible shop list by warehouse id |

## Order

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.order.cancel_order`](https://open.shopee.com/documents/v2/v2.order.cancel_order?module=94&type=1) | POST | shop | ✅ | Use this api to cancel an order. This action can only be performed before the order has been shipped. |
| [`v2.order.download_fbs_invoices`](https://open.shopee.com/documents/v2/v2.order.download_fbs_invoices?module=94&type=1) | POST | shop | ✅ | This API allows you to download FBS invoices. To use this API, the client must first call v2.order.generate_fbs_invoices to create a new sh… |
| [`v2.order.download_invoice_doc`](https://open.shopee.com/documents/v2/v2.order.download_invoice_doc?module=94&type=1) | GET | shop | ✅ | This endpoint only for PH and BR local seller. Seller can download the invoice uploaded before through this endpoint. |
| [`v2.order.generate_fbs_invoices`](https://open.shopee.com/documents/v2/v2.order.generate_fbs_invoices?module=94&type=1) | POST | shop | ✅ | This API creates a task to download a specific tax document (e.g., sales invoice, remessa invoice) for the seller's account, available only… |
| [`v2.order.get_booking_detail`](https://open.shopee.com/documents/v2/v2.order.get_booking_detail?module=94&type=1) | GET | shop | ✅ | Use this api to get booking detail. |
| [`v2.order.get_booking_list`](https://open.shopee.com/documents/v2/v2.order.get_booking_list?module=94&type=1) | GET | shop | ✅ | Use this api to search bookings. You may also filter them by status, if needed. |
| [`v2.order.get_buyer_invoice_info`](https://open.shopee.com/documents/v2/v2.order.get_buyer_invoice_info?module=94&type=1) | POST | shop | ✅ | API to obtain buyer submitted invoice info for VN, TH and PH local sellers only. |
| [`v2.order.get_estimate_cancel_value`](https://open.shopee.com/documents/v2/v2.order.get_estimate_cancel_value?module=94&type=1) | POST | shop | ✅ | Returns the estimated refund value for a partial order cancellation given the specified items to cancel. |
| [`v2.order.get_fbs_invoices_result`](https://open.shopee.com/documents/v2/v2.order.get_fbs_invoices_result?module=94&type=1) | POST | shop | ✅ | This API allows you to consult the status of a previously requested batch download for FBS tax documents. |
| [`v2.order.get_order_detail`](https://open.shopee.com/documents/v2/v2.order.get_order_detail?module=94&type=1) | GET | shop | ✅ | Use this api to get order detail. |
| [`v2.order.get_order_list`](https://open.shopee.com/documents/v2/v2.order.get_order_list?module=94&type=1) | GET | shop | ✅ | Use this api to search orders. You may also filter them by status, if needed. |
| [`v2.order.get_package_detail`](https://open.shopee.com/documents/v2/v2.order.get_package_detail?module=94&type=1) | GET | shop | ✅ | Use this api to get package detail. |
| [`v2.order.get_pending_buyer_invoice_order_list`](https://open.shopee.com/documents/v2/v2.order.get_pending_buyer_invoice_order_list?module=94&type=1) | GET | shop | ✅ | This endpoint only for PH and BR local sellers only. This API is used for seller to retrieve a list of order IDs that are pending invoice u… |
| [`v2.order.get_shipment_list`](https://open.shopee.com/documents/v2/v2.order.get_shipment_list?module=94&type=1) | GET | shop | ✅ | Use this api to get order list which order_status is READY_TO_SHIP or RETRY_SHIP to start process the whole shipping progress. |
| [`v2.order.get_warehouse_filter_config`](https://open.shopee.com/documents/v2/v2.order.get_warehouse_filter_config?module=94&type=1) | GET | shop | ✅ | For multi-warehouse shops, return all warehouses with packages that have not been SHIPPED including product_location_id and address_id. Com… |
| [`v2.order.handle_buyer_cancellation`](https://open.shopee.com/documents/v2/v2.order.handle_buyer_cancellation?module=94&type=1) | POST | shop | ✅ | Use this api to handle buyer's cancellation application. |
| [`v2.order.handle_prescription_check`](https://open.shopee.com/documents/v2/v2.order.handle_prescription_check?module=94&type=1) | POST | shop | ✅ | Use this API to approve or reject a prescription |
| [`v2.order.search_package_list`](https://open.shopee.com/documents/v2/v2.order.search_package_list?module=94&type=1) | POST | shop | ✅ | Use this API to search the list of packages that have not been SHIPPED to proceed arranging shipment, and it supports various filters and s… |
| [`v2.order.set_note`](https://open.shopee.com/documents/v2/v2.order.set_note?module=94&type=1) | POST | shop | ✅ | Use this api to set note for an order. |
| [`v2.order.split_order`](https://open.shopee.com/documents/v2/v2.order.split_order?module=94&type=1) | POST | shop | ✅ | Use this api to split an order into multiple packages. Orders that include installation services cannot be split by quantity. |
| [`v2.order.unsplit_order`](https://open.shopee.com/documents/v2/v2.order.unsplit_order?module=94&type=1) | POST | shop | ✅ | Use this ai to undo split of order. After undo split, the order will have only one package. It can only be used when order status still at … |
| [`v2.order.upload_invoice_doc`](https://open.shopee.com/documents/v2/v2.order.upload_invoice_doc?module=94&type=1) | POST | shop | ✅📎 | This endpoint is for PH and BR local seller. Upload the invoice document |

## Payment

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.payment.generate_income_report`](https://open.shopee.com/documents/v2/v2.payment.generate_income_report?module=97&type=1) | GET | shop | ✅ | Trigger income report generation. |
| [`v2.payment.generate_income_statement`](https://open.shopee.com/documents/v2/v2.payment.generate_income_statement?module=97&type=1) | GET | shop | ✅ | Trigger income statement generation. |
| [`v2.payment.get_billing_transaction_info`](https://open.shopee.com/documents/v2/v2.payment.get_billing_transaction_info?module=97&type=1) | POST | shop | ✅ | This API is applicable for Cross Border (CB) sellers only to get the detailed payout transaction data, both released and to-be released tra… |
| [`v2.payment.get_escrow_detail`](https://open.shopee.com/documents/v2/v2.payment.get_escrow_detail?module=97&type=1) | GET | shop | ✅ | Use this API to fetch the accounting detail of order. |
| [`v2.payment.get_escrow_detail_batch`](https://open.shopee.com/documents/v2/v2.payment.get_escrow_detail_batch?module=97&type=1) | POST | shop | ✅ | Use this API to fetch the details of order income by batch. |
| [`v2.payment.get_escrow_list`](https://open.shopee.com/documents/v2/v2.payment.get_escrow_list?module=97&type=1) | GET | shop | ✅ | Use this API to fetch the accounting list of order. |
| [`v2.payment.get_income_detail`](https://open.shopee.com/documents/v2/v2.payment.get_income_detail?module=97&type=1) | GET | shop | ✅ | Retrieves detailed order-level income information across various income statuses for a specified time period. This API enables partners to … |
| [`v2.payment.get_income_overview`](https://open.shopee.com/documents/v2/v2.payment.get_income_overview?module=97&type=1) | GET | shop | ✅ | Retrieves a consolidated snapshot of the seller’s income amounts categorized by income status for a specified shop. This API provides a hol… |
| [`v2.payment.get_income_report`](https://open.shopee.com/documents/v2/v2.payment.get_income_report?module=97&type=1) | GET | shop | ✅ | To query income report status and provide file link if the income report is ready to be downloaded. |
| [`v2.payment.get_income_statement`](https://open.shopee.com/documents/v2/v2.payment.get_income_statement?module=97&type=1) | GET | shop | ✅ | To query income statement status and provide file link if the income statement is ready to be downloaded. |
| [`v2.payment.get_item_installment_status`](https://open.shopee.com/documents/v2/v2.payment.get_item_installment_status?module=97&type=1) | POST | shop | ✅ | Get item installment tenures.Only for TH、TW. |
| [`v2.payment.get_payment_method_list`](https://open.shopee.com/documents/v2/v2.payment.get_payment_method_list?module=97&type=1) | GET | public | ✅ | Obtain payment method (no authentication required) |
| [`v2.payment.get_payout_detail`](https://open.shopee.com/documents/v2/v2.payment.get_payout_detail?module=97&type=1) | GET | shop | ✅ | This API is applicable for Cross Border (CB) sellers only to get the shop's payout data, such as the payout amount, currency, FX rate, the … |
| [`v2.payment.get_payout_info`](https://open.shopee.com/documents/v2/v2.payment.get_payout_info?module=97&type=1) | GET | shop | ✅ | This is a new API which applicable for Cross Border (CB) sellers only to get the shop's payout data, will be used for the original API v2.g… |
| [`v2.payment.get_shop_installment_status`](https://open.shopee.com/documents/v2/v2.payment.get_shop_installment_status?module=97&type=1) | GET | shop | ✅ | Get the installment state of shop. |
| [`v2.payment.get_wallet_transaction_list`](https://open.shopee.com/documents/v2/v2.payment.get_wallet_transaction_list?module=97&type=1) | GET | shop | ✅ | Use this API to get the transaction records of wallet. Only applicable for local shops |
| [`v2.payment.set_item_installment_status`](https://open.shopee.com/documents/v2/v2.payment.set_item_installment_status?module=97&type=1) | POST | shop | ✅ | Set item installment.Only for TH、TW. |
| [`v2.payment.set_shop_installment_status`](https://open.shopee.com/documents/v2/v2.payment.set_shop_installment_status?module=97&type=1) | POST | shop | ✅ | Sets the staging capability of shop level. |

## Product

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.product.add_item`](https://open.shopee.com/documents/v2/v2.product.add_item?module=89&type=1) | POST | shop | ✅ | Add a new item. |
| [`v2.product.add_kit_item`](https://open.shopee.com/documents/v2/v2.product.add_kit_item?module=89&type=1) | POST | shop | ✅ | Create the kit item by selecting multiple items and setting main component and quantity per kit. |
| [`v2.product.add_model`](https://open.shopee.com/documents/v2/v2.product.add_model?module=89&type=1) | POST | shop | ✅ | Add model. More detail please check: https://open.shopee.com/developer-guide/219 |
| [`v2.product.batch_add_item`](https://open.shopee.com/documents/v2/v2.product.batch_add_item?module=89&type=1) | POST | shop | ✅ | Create asynchronous task to batch add item |
| [`v2.product.batch_publish_item_to_outlet_shop`](https://open.shopee.com/documents/v2/v2.product.batch_publish_item_to_outlet_shop?module=89&type=1) | POST | shop | ✅ | Create asynchronous task to batch publish outlet item |
| [`v2.product.batch_update_outlet_price`](https://open.shopee.com/documents/v2/v2.product.batch_update_outlet_price?module=89&type=1) | POST | shop | ✅ | Create asynchronous task to batch update outlet item's price |
| [`v2.product.batch_update_outlet_stock`](https://open.shopee.com/documents/v2/v2.product.batch_update_outlet_stock?module=89&type=1) | POST | shop | ✅ | Create asynchronous task to batch update outlet stock |
| [`v2.product.boost_item`](https://open.shopee.com/documents/v2/v2.product.boost_item?module=89&type=1) | POST | shop | ✅ | Boost item. |
| [`v2.product.category_recommend`](https://open.shopee.com/documents/v2/v2.product.category_recommend?module=89&type=1) | GET | shop | ✅ | Recommend category by item name. |
| [`v2.product.delete_item`](https://open.shopee.com/documents/v2/v2.product.delete_item?module=89&type=1) | POST | shop | ✅ | Use this call to delete a product item. |
| [`v2.product.delete_model`](https://open.shopee.com/documents/v2/v2.product.delete_model?module=89&type=1) | POST | shop | ✅ | Delete item model. |
| [`v2.product.generate_kit_image`](https://open.shopee.com/documents/v2/v2.product.generate_kit_image?module=89&type=1) | POST | shop | ✅ | This API generates a single consolidated image by combining the cover images of all selected items. It is typically used to create a unifie… |
| [`v2.product.get_aitem_by_pitem_id`](https://open.shopee.com/documents/v2/v2.product.get_aitem_by_pitem_id?module=89&type=1) | GET | shop | ✅ | Get the list of A Items under SIP Affiliate Shop corresponding to P Items under SIP Primary Shop. |
| [`v2.product.get_all_vehicle_list`](https://open.shopee.com/documents/v2/v2.product.get_all_vehicle_list?module=89&type=1) | GET | shop | ✅ | Use this Open API to get all vehicle list. |
| [`v2.product.get_attribute_tree`](https://open.shopee.com/documents/v2/v2.product.get_attribute_tree?module=89&type=1) | GET | shop | ✅ | Get the attribute tree for categories |
| [`v2.product.get_batch_task_result`](https://open.shopee.com/documents/v2/v2.product.get_batch_task_result?module=89&type=1) | GET | shop | ✅ | Query batch task result |
| [`v2.product.get_boosted_list`](https://open.shopee.com/documents/v2/v2.product.get_boosted_list?module=89&type=1) | GET | shop | ✅ | Get boosted item list. |
| [`v2.product.get_brand_list`](https://open.shopee.com/documents/v2/v2.product.get_brand_list?module=89&type=1) | GET | shop | ✅ | Get the brand data of a leaf category. More detail please check: https://open.shopee.com/developer-guide/209 |
| [`v2.product.get_category`](https://open.shopee.com/documents/v2/v2.product.get_category?module=89&type=1) | GET | shop | ✅ | Get category tree data. More detail please check https://open.shopee.com/developer-guide/209 |
| [`v2.product.get_comment`](https://open.shopee.com/documents/v2/v2.product.get_comment?module=89&type=1) | GET | shop | ✅ | Use this api to get comment by shop_id, item_id, or comment_id, get up to 1000 comments. |
| [`v2.product.get_direct_item_list`](https://open.shopee.com/documents/v2/v2.product.get_direct_item_list?module=89&type=1) | GET | shop | ✅ | get direct item by main item. |
| [`v2.product.get_direct_shop_recommended_price`](https://open.shopee.com/documents/v2/v2.product.get_direct_shop_recommended_price?module=89&type=1) | GET | shop | ✅ | get recommend price for direct shop. |
| [`v2.product.get_item_base_info`](https://open.shopee.com/documents/v2/v2.product.get_item_base_info?module=89&type=1) | GET | shop | ✅ | Use this api to get basic info of item by item_id list. |
| [`v2.product.get_item_content_diagnosis_result`](https://open.shopee.com/documents/v2/v2.product.get_item_content_diagnosis_result?module=89&type=1) | POST | shop | ✅ | Get the content quality details (including content quality level, content issues, and system suggestions) for specific product list. |
| [`v2.product.get_item_extra_info`](https://open.shopee.com/documents/v2/v2.product.get_item_extra_info?module=89&type=1) | GET | shop | ✅ | Use this api to get extra info of item by item_id list. |
| [`v2.product.get_item_limit`](https://open.shopee.com/documents/v2/v2.product.get_item_limit?module=89&type=1) | GET | shop | ✅ | Get item upload control. |
| [`v2.product.get_item_list`](https://open.shopee.com/documents/v2/v2.product.get_item_list?module=89&type=1) | GET | shop | ✅ | Use this call to get a list of items. |
| [`v2.product.get_item_list_by_content_diagnosis`](https://open.shopee.com/documents/v2/v2.product.get_item_list_by_content_diagnosis?module=89&type=1) | POST | shop | ✅ | Query the list of products and their content quality details by content quality level or content issues. |
| [`v2.product.get_item_promotion`](https://open.shopee.com/documents/v2/v2.product.get_item_promotion?module=89&type=1) | GET | shop | ✅ | Get item promotion info. |
| [`v2.product.get_item_tenure_info`](https://open.shopee.com/documents/v2/v2.product.get_item_tenure_info?module=89&type=1) | POST | shop |  | Retrieves the current tenure configuration for an item. The item must belong to the authorized shop. Response fields: response.tenure_setti… |
| [`v2.product.get_item_violation_info`](https://open.shopee.com/documents/v2/v2.product.get_item_violation_info?module=89&type=1) | GET | shop | ✅ | get item violation info |
| [`v2.product.get_kit_item_info`](https://open.shopee.com/documents/v2/v2.product.get_kit_item_info?module=89&type=1) | GET | shop | ✅ | Get the kit basic information and kit components. |
| [`v2.product.get_kit_item_limit`](https://open.shopee.com/documents/v2/v2.product.get_kit_item_limit?module=89&type=1) | GET | shop | ✅ | Get the limit of Kit item. |
| [`v2.product.get_main_item_list`](https://open.shopee.com/documents/v2/v2.product.get_main_item_list?module=89&type=1) | GET | shop | ✅ | get main item by direct item. |
| [`v2.product.get_mart_item_by_outlet_item_id`](https://open.shopee.com/documents/v2/v2.product.get_mart_item_by_outlet_item_id?module=89&type=1) | POST | shop | ✅ | Get the mapping information between a Mart item and its corresponding outlet item by outlet item ID. |
| [`v2.product.get_mart_item_mapping_by_id`](https://open.shopee.com/documents/v2/v2.product.get_mart_item_mapping_by_id?module=89&type=1) | POST | shop | ✅ | Get the mapping information between a Mart item and its corresponding outlet item by item ID. |
| [`v2.product.get_model_list`](https://open.shopee.com/documents/v2/v2.product.get_model_list?module=89&type=1) | GET | shop | ✅ | Get model list of an item. |
| [`v2.product.get_product_certification_rule`](https://open.shopee.com/documents/v2/v2.product.get_product_certification_rule?module=89&type=1) | POST | shop | ✅ | Get product certification rule |
| [`v2.product.get_recommend_attribute`](https://open.shopee.com/documents/v2/v2.product.get_recommend_attribute?module=89&type=1) | GET | shop | ✅ | Get recommend attributes. |
| [`v2.product.get_size_chart_detail`](https://open.shopee.com/documents/v2/v2.product.get_size_chart_detail?module=89&type=1) | GET | shop | ✅ | Get new size chart detail. Now only local shop support to use this api to get new size chart detail. |
| [`v2.product.get_size_chart_list`](https://open.shopee.com/documents/v2/v2.product.get_size_chart_list?module=89&type=1) | GET | shop | ✅ | Get new size chart list. Now only support local shop to use new size chart. |
| [`v2.product.get_ssp_detail`](https://open.shopee.com/documents/v2/v2.product.get_ssp_detail?module=89&type=1) | GET | shop | ✅ | Get the details of an SSP or CSSP. At least one of ssp_id and cssp_id is required, and cssp_id takes priority when both are provided. The r… |
| [`v2.product.get_ssp_recommendation`](https://open.shopee.com/documents/v2/v2.product.get_ssp_recommendation?module=89&type=1) | GET | shop | ✅ | Get the SSP enrollment recommendations of the authorized shop, separating items that can be enrolled automatically from items that may be e… |
| [`v2.product.get_variations`](https://open.shopee.com/documents/v2/v2.product.get_variations?module=89&type=1) | GET | shop | ✅ | Get the standardized tier variation defined by Shopee, which is currently a three-layer tree structure. The top layer is variations, the se… |
| [`v2.product.get_vehicle_list_by_compatibility_detail`](https://open.shopee.com/documents/v2/v2.product.get_vehicle_list_by_compatibility_detail?module=89&type=1) | GET | shop | ✅ | Use this Open API to get vehicle list by brand, model, year, and version. |
| [`v2.product.get_weight_recommendation`](https://open.shopee.com/documents/v2/v2.product.get_weight_recommendation?module=89&type=1) | POST | shop | ✅ | Get recommended weight. Now only BR shop support to use this api to get recommended weight. |
| [`v2.product.init_tier_variation`](https://open.shopee.com/documents/v2/v2.product.init_tier_variation?module=89&type=1) | POST | shop | ✅ | This API allows you to update the tier structure of a product. Defining only color creates one tier, while color + size creates two tiers (… |
| [`v2.product.link_item_to_ssp`](https://open.shopee.com/documents/v2/v2.product.link_item_to_ssp?module=89&type=1) | POST | shop | ✅ | Link one or more models of an item to their country-specific SSPs. item_id and model_cssp_pairs are required, and each pair must contain mo… |
| [`v2.product.register_brand`](https://open.shopee.com/documents/v2/v2.product.register_brand?module=89&type=1) | POST | shop | ✅ | Use this call to register a brand. |
| [`v2.product.reply_comment`](https://open.shopee.com/documents/v2/v2.product.reply_comment?module=89&type=1) | POST | shop | ✅ | Use this api to reply comments from buyers in batch. |
| [`v2.product.search_attribute_value_list`](https://open.shopee.com/documents/v2/v2.product.search_attribute_value_list?module=89&type=1) | POST | shop | ✅ | this api is for searching attribute value list for attribute with support_search_value flag |
| [`v2.product.search_item`](https://open.shopee.com/documents/v2/v2.product.search_item?module=89&type=1) | GET | shop | ✅ | Use this call to search item. |
| [`v2.product.search_ssp_list`](https://open.shopee.com/documents/v2/v2.product.search_ssp_list?module=89&type=1) | POST | shop | ✅ | Search SSPs by title or by image. At most 50 results are returned. When image_id_list is provided, the search is based on image similarity … |
| [`v2.product.search_unpackaged_model_list`](https://open.shopee.com/documents/v2/v2.product.search_unpackaged_model_list?module=89&type=1) | POST | shop | ✅ | Use this API to retrieve Unpackaged SKU ID information for items that toggle on logistics channel 30029. |
| [`v2.product.set_item_tenure_info`](https://open.shopee.com/documents/v2/v2.product.set_item_tenure_info?module=89&type=1) | POST | shop |  | Updates the SSPL tenure configuration for an item. Method: POST Request fields item_id, tenure key. Required flag: true: Opts the item out … |
| [`v2.product.unlink_item_from_ssp`](https://open.shopee.com/documents/v2/v2.product.unlink_item_from_ssp?module=89&type=1) | POST | shop | ✅ | Remove the SSP links of one or more models of an item. item_id and model_cssp_pairs are required, and each pair must contain model_id and c… |
| [`v2.product.unlist_item`](https://open.shopee.com/documents/v2/v2.product.unlist_item?module=89&type=1) | POST | shop | ✅ | Unlist item. |
| [`v2.product.update_item`](https://open.shopee.com/documents/v2/v2.product.update_item?module=89&type=1) | POST | shop | ✅ | Update item. |
| [`v2.product.update_kit_item`](https://open.shopee.com/documents/v2/v2.product.update_kit_item?module=89&type=1) | POST | shop | ✅ | Update the kit basic information and kit components, only support adding kit variations and updating existing kit variation’s image, price,… |
| [`v2.product.update_model`](https://open.shopee.com/documents/v2/v2.product.update_model?module=89&type=1) | POST | shop | ✅ | Update seller sku/ pre order/ model status for model. BCRS container settings can be updated using model[].bcrs_setting with model_id for e… |
| [`v2.product.update_price`](https://open.shopee.com/documents/v2/v2.product.update_price?module=89&type=1) | POST | shop | ✅ | Update price. |
| [`v2.product.update_sip_item_price`](https://open.shopee.com/documents/v2/v2.product.update_sip_item_price?module=89&type=1) | POST | shop | ✅ | Update sip item price. |
| [`v2.product.update_stock`](https://open.shopee.com/documents/v2/v2.product.update_stock?module=89&type=1) | POST | shop | ✅ | Use this API to update one item_id for each call, but still can support updating multiple model_ids stock of the same item_id (If you need … |
| [`v2.product.update_tier_variation`](https://open.shopee.com/documents/v2/v2.product.update_tier_variation?module=89&type=1) | POST | shop | ✅ | This api can only be used without changing the tier structure, you can add options, delete options, and update the option image by this api… |

## Public

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.public.get_access_token`](https://open.shopee.com/documents/v2/v2.public.get_access_token?module=104&type=1) | POST | public | ✅ | Use the code from the authorization step to call this API to obtain the authorized shop_id, merchant_id, supplier_id, or user_id, and its c… |
| [`v2.public.get_merchants_by_partner`](https://open.shopee.com/documents/v2/v2.public.get_merchants_by_partner?module=104&type=1) | GET | public | ✅ | Use this API to get basic info of merchants which have authorized to the partner. |
| [`v2.public.get_shopee_ip_ranges`](https://open.shopee.com/documents/v2/v2.public.get_shopee_ip_ranges?module=104&type=1) | GET | public | ✅ | You can get shopee ip address ranges through this open api. |
| [`v2.public.get_shops_by_partner`](https://open.shopee.com/documents/v2/v2.public.get_shops_by_partner?module=104&type=1) | GET | public | ✅ | get basic info of shops which have authorized to the partner. |
| [`v2.public.get_token_by_resend_code`](https://open.shopee.com/documents/v2/v2.public.get_token_by_resend_code?module=104&type=1) | POST | public | ✅ | Use the resend code to get access token and refresh token. When you lost your access token or refresh token, you can go to authorization ma… |
| [`v2.public.refresh_access_token`](https://open.shopee.com/documents/v2/v2.public.refresh_access_token?module=104&type=1) | POST | public | ✅ | Use this API to refresh the access_token after it expires. Refresh_token can be used once only, this API will also return a new refresh_tok… |

## Push

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.push.confirm_consumed_lost_push_message`](https://open.shopee.com/documents/v2/v2.push.confirm_consumed_lost_push_message?module=105&type=1) | POST | public | ✅ | Confirm consumed lost push message |
| [`v2.push.get_app_push_config`](https://open.shopee.com/documents/v2/v2.push.get_app_push_config?module=105&type=1) | GET | public | ✅ | you can get your app current push config setting through this api |
| [`v2.push.get_lost_push_message`](https://open.shopee.com/documents/v2/v2.push.get_lost_push_message?module=105&type=1) | GET | public | ✅ | Get the lost push messages that were lost within 3 days of the current time and not confirmed to have been consumed |
| [`v2.push.set_app_push_config`](https://open.shopee.com/documents/v2/v2.push.set_app_push_config?module=105&type=1) | POST | public | ✅ | you can turn on or turn off your app push config setting through this open api |

## Returns

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.returns.accept_offer`](https://open.shopee.com/documents/v2/v2.returns.accept_offer?module=102&type=1) | POST | shop | ✅ | v2.returns.accept_offer |
| [`v2.returns.cancel_dispute`](https://open.shopee.com/documents/v2/v2.returns.cancel_dispute?module=102&type=1) | POST | shop | ✅ | Sellers can only cancel compensation disputes, not normal disputes. This means that sellers can only cancel disputes when the return_status… |
| [`v2.returns.confirm`](https://open.shopee.com/documents/v2/v2.returns.confirm?module=102&type=1) | POST | shop | ✅ | Confirm refund |
| [`v2.returns.convert_image`](https://open.shopee.com/documents/v2/v2.returns.convert_image?module=102&type=1) | POST | shop | ✅📎 | Convert a specific format and pictures within 10M into url. |
| [`v2.returns.dispute`](https://open.shopee.com/documents/v2/v2.returns.dispute?module=102&type=1) | POST | shop | ✅ | Dispute return. Support to raise dispute when return_status in REQUESTED / PROCESSING/ACCEPTED |
| [`v2.returns.get_available_solutions`](https://open.shopee.com/documents/v2/v2.returns.get_available_solutions?module=102&type=1) | GET | shop | ✅ | Get the available solutions offered to buyers. |
| [`v2.returns.get_return_detail`](https://open.shopee.com/documents/v2/v2.returns.get_return_detail?module=102&type=1) | GET | shop | ✅ | Use this api to get detail information of a return by return sn. |
| [`v2.returns.get_return_dispute_reason`](https://open.shopee.com/documents/v2/v2.returns.get_return_dispute_reason?module=102&type=1) | GET | shop | ✅ | To get the dispute return reason. |
| [`v2.returns.get_return_list`](https://open.shopee.com/documents/v2/v2.returns.get_return_list?module=102&type=1) | GET | shop | ✅ | Use this api to get detail information of many return by shop id. |
| [`v2.returns.get_reverse_tracking_info`](https://open.shopee.com/documents/v2/v2.returns.get_reverse_tracking_info?module=102&type=1) | GET | shop | ✅ | Get reverse and post-return logistics information of return request. For Normal RR, return complete reverse logistics information, for In-t… |
| [`v2.returns.get_shipping_carrier`](https://open.shopee.com/documents/v2/v2.returns.get_shipping_carrier?module=102&type=1) | GET | shop | ✅ | Use this API to get the list of shipping carriers and request parameters needed before calling v2.returns.upload_shipping_proof. Only for T… |
| [`v2.returns.offer`](https://open.shopee.com/documents/v2/v2.returns.offer?module=102&type=1) | POST | shop | ✅ | v2.returns.offer |
| [`v2.returns.query_proof`](https://open.shopee.com/documents/v2/v2.returns.query_proof?module=102&type=1) | GET | shop | ✅ | Support sellers to query the evidence uploaded through the upload evidence API. |
| [`v2.returns.upload_proof`](https://open.shopee.com/documents/v2/v2.returns.upload_proof?module=102&type=1) | POST | shop | ✅ | Support sellers to upload evidence, including text and pictures and videos converted into URLs. |
| [`v2.returns.upload_shipping_proof`](https://open.shopee.com/documents/v2/v2.returns.upload_shipping_proof?module=102&type=1) | POST | shop | ✅ | Use this API to upload shipping proof (Only for TW and BR returns with is_seller_arrange = true). This is not to upload evidence for disput… |

## SBS

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.sbs.get_bound_whs_info`](https://open.shopee.com/documents/v2/v2.sbs.get_bound_whs_info?module=124&type=1) | GET | shop | ✅ | get bound warehouse by shop id |
| [`v2.sbs.get_current_inventory`](https://open.shopee.com/documents/v2/v2.sbs.get_current_inventory?module=124&type=1) | GET | shop | ✅ | Get Seller Center Current Inventory Page Data |
| [`v2.sbs.get_expiry_report`](https://open.shopee.com/documents/v2/v2.sbs.get_expiry_report?module=124&type=1) | GET | shop | ✅ | Seller Center Expiry Report page data |
| [`v2.sbs.get_fulfillment_mapping_inventory_list`](https://open.shopee.com/documents/v2/v2.sbs.get_fulfillment_mapping_inventory_list?module=124&type=1) | GET | shop | ✅ | This API is designed for sellers using Fulfillment Mapping and their ERP systems. It allows callers to query the corresponding mapping and … |
| [`v2.sbs.get_stock_aging`](https://open.shopee.com/documents/v2/v2.sbs.get_stock_aging?module=124&type=1) | GET | shop | ✅ | Get Seller Center Stock Aging page data |
| [`v2.sbs.get_stock_movement`](https://open.shopee.com/documents/v2/v2.sbs.get_stock_movement?module=124&type=1) | GET | shop | ✅ | Get Seller Center，Stock Movement page data |

## Shop

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.shop.get_authorised_reseller_brand`](https://open.shopee.com/documents/v2/v2.shop.get_authorised_reseller_brand?module=92&type=1) | GET | shop | ✅ | Get the authorised reseller brand list for the shop. |
| [`v2.shop.get_br_shop_onboarding_info`](https://open.shopee.com/documents/v2/v2.shop.get_br_shop_onboarding_info?module=92&type=1) | GET | shop | ✅ | [For BR Shop Only] Use this API to get shop KYC registration and qualification information. |
| [`v2.shop.get_profile`](https://open.shopee.com/documents/v2/v2.shop.get_profile?module=92&type=1) | GET | shop | ✅ | This API support to get information of shop. |
| [`v2.shop.get_shop_holiday_mode`](https://open.shopee.com/documents/v2/v2.shop.get_shop_holiday_mode?module=92&type=1) | GET | shop | ✅ | Use this API to check whether a shop has enabled holiday mode and its ongoing and upcoming holiday mode period. |
| [`v2.shop.get_shop_info`](https://open.shopee.com/documents/v2/v2.shop.get_shop_info?module=92&type=1) | GET | shop | ✅ | Use this call to get information of shop |
| [`v2.shop.get_shop_notification`](https://open.shopee.com/documents/v2/v2.shop.get_shop_notification?module=92&type=1) | GET | shop | ✅ | get Seller Center notification, the permission is controlled by App type |
| [`v2.shop.get_warehouse_detail`](https://open.shopee.com/documents/v2/v2.shop.get_warehouse_detail?module=92&type=1) | GET | shop | ✅ | For given shop id and region, return warehouse info including warehouse id, address id and location id, return all warehouse with once call. |
| [`v2.shop.set_shop_holiday_mode`](https://open.shopee.com/documents/v2/v2.shop.set_shop_holiday_mode?module=92&type=1) | POST | shop | ✅ | Use this API to set holiday periods in advance for automatic on/off of holiday mode and there are two holiday modes allowing sellers to cho… |
| [`v2.shop.update_profile`](https://open.shopee.com/documents/v2/v2.shop.update_profile?module=92&type=1) | POST | shop | ✅ | This API support to let sellers to update the shop name, shop logo, and shop description. |

## ShopCategory

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.shop_category.add_item_list`](https://open.shopee.com/documents/v2/v2.shop_category.add_item_list?module=101&type=1) | POST | shop | ✅ | Use this call to add items list to certain shop_category |
| [`v2.shop_category.add_shop_category`](https://open.shopee.com/documents/v2/v2.shop_category.add_shop_category?module=101&type=1) | POST | shop | ✅ | Use this call to add a new shop collecion |
| [`v2.shop_category.delete_item_list`](https://open.shopee.com/documents/v2/v2.shop_category.delete_item_list?module=101&type=1) | POST | shop | ✅ | Use this api to delete items from shop category |
| [`v2.shop_category.delete_shop_category`](https://open.shopee.com/documents/v2/v2.shop_category.delete_shop_category?module=101&type=1) | POST | shop | ✅ | Use this call to delete a existing shop collecion |
| [`v2.shop_category.get_item_list`](https://open.shopee.com/documents/v2/v2.shop_category.get_item_list?module=101&type=1) | GET | shop | ✅ | Use this call to get items list of certain shop_category |
| [`v2.shop_category.get_shop_category_list`](https://open.shopee.com/documents/v2/v2.shop_category.get_shop_category_list?module=101&type=1) | GET | shop | ✅ | Use this call to get list of shop categories |
| [`v2.shop_category.update_shop_category`](https://open.shopee.com/documents/v2/v2.shop_category.update_shop_category?module=101&type=1) | POST | shop | ✅ | Use this call to update a existing collecion |

## ShopFlashSale

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.shop_flash_sale.add_shop_flash_sale_items`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.add_shop_flash_sale_items?module=123&type=1) | POST | shop | ✅ | add shop flash sale item |
| [`v2.shop_flash_sale.create_shop_flash_sale`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.create_shop_flash_sale?module=123&type=1) | POST | shop | ✅ | creat shop flash sale |
| [`v2.shop_flash_sale.delete_shop_flash_sale`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.delete_shop_flash_sale?module=123&type=1) | POST | shop | ✅ | delete shop flash sale |
| [`v2.shop_flash_sale.delete_shop_flash_sale_items`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.delete_shop_flash_sale_items?module=123&type=1) | POST | shop | ✅ | delete shop flash sale items |
| [`v2.shop_flash_sale.get_item_criteria`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.get_item_criteria?module=123&type=1) | GET | shop | ✅ | get shop flash sale item criteria |
| [`v2.shop_flash_sale.get_shop_flash_sale`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.get_shop_flash_sale?module=123&type=1) | GET | shop | ✅ | get shop flash sale detail |
| [`v2.shop_flash_sale.get_shop_flash_sale_items`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.get_shop_flash_sale_items?module=123&type=1) | GET | shop | ✅ | get shop flash sale items and item detail |
| [`v2.shop_flash_sale.get_shop_flash_sale_list`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.get_shop_flash_sale_list?module=123&type=1) | GET | shop | ✅ | get shop flash sale list |
| [`v2.shop_flash_sale.get_time_slot_id`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.get_time_slot_id?module=123&type=1) | GET | shop | ✅ | get time slot id |
| [`v2.shop_flash_sale.update_shop_flash_sale`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.update_shop_flash_sale?module=123&type=1) | POST | shop | ✅ | edit shop flash sale(enable, disable) |
| [`v2.shop_flash_sale.update_shop_flash_sale_items`](https://open.shopee.com/documents/v2/v2.shop_flash_sale.update_shop_flash_sale_items?module=123&type=1) | POST | shop | ✅ | edit shop flash sale item, you can only edit the models in disbaled or enabled status |

## TopPicks

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.top_picks.add_top_picks`](https://open.shopee.com/documents/v2/v2.top_picks.add_top_picks?module=100&type=1) | POST | shop | ✅ | add one collection |
| [`v2.top_picks.delete_top_picks`](https://open.shopee.com/documents/v2/v2.top_picks.delete_top_picks?module=100&type=1) | POST | shop | ✅ | delete a collection |
| [`v2.top_picks.get_top_picks_list`](https://open.shopee.com/documents/v2/v2.top_picks.get_top_picks_list?module=100&type=1) | GET | shop | ✅ | get one TopPicks |
| [`v2.top_picks.update_top_picks`](https://open.shopee.com/documents/v2/v2.top_picks.update_top_picks?module=100&type=1) | POST | shop | ✅ | update a collection info |

## Video

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.video.delete_video`](https://open.shopee.com/documents/v2/v2.video.delete_video?module=129&type=1) | POST | user |  | Use this API to delete video. You can delete the video for both draft and post status. |
| [`v2.video.edit_video_info`](https://open.shopee.com/documents/v2/v2.video.edit_video_info?module=129&type=1) | POST | user |  | You need to call v2.media.init_video_upload, v2.media.upload_video_part, and v2.media.complete_video_upload to upload the video, and call t… |
| [`v2.video.get_cover_list`](https://open.shopee.com/documents/v2/v2.video.get_cover_list?module=129&type=1) | GET | user |  | You need to call v2.media.init_video_upload, v2.media.upload_video_part, and v2.media.complete_video_upload to upload the video, and call t… |
| [`v2.video.get_metric_trend`](https://open.shopee.com/documents/v2/v2.video.get_metric_trend?module=129&type=1) | GET | user |  | Query video data indicator trends. |
| [`v2.video.get_overview_performance`](https://open.shopee.com/documents/v2/v2.video.get_overview_performance?module=129&type=1) | GET | user |  | Get overall performance data for all post Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_prodcut_performance_list`](https://open.shopee.com/documents/v2/v2.video.get_prodcut_performance_list?module=129&type=1) | GET | user |  | Get specific performance data for products linked with Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_user_demographics`](https://open.shopee.com/documents/v2/v2.video.get_user_demographics?module=129&type=1) | GET | user |  | Get user demographics data to better understand the types of viewers that watch your Shopee Video. |
| [`v2.video.get_video_detail`](https://open.shopee.com/documents/v2/v2.video.get_video_detail?module=129&type=1) | GET | user |  | Get the detail information of video. |
| [`v2.video.get_video_detail_audience_distribution`](https://open.shopee.com/documents/v2/v2.video.get_video_detail_audience_distribution?module=129&type=1) | GET | user |  | Get detailed audience distribution data for individual post Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_video_detail_metric_trend`](https://open.shopee.com/documents/v2/v2.video.get_video_detail_metric_trend?module=129&type=1) | GET | user |  | Get detailed metric trend data for individual post Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_video_detail_performance`](https://open.shopee.com/documents/v2/v2.video.get_video_detail_performance?module=129&type=1) | GET | user |  | Get detailed performance data for individual post Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_video_detail_product_performance`](https://open.shopee.com/documents/v2/v2.video.get_video_detail_product_performance?module=129&type=1) | GET | user |  | Get performance data for products linked with individual post Shopee Video. There is at least a one-day delay. |
| [`v2.video.get_video_list`](https://open.shopee.com/documents/v2/v2.video.get_video_list?module=129&type=1) | GET | user |  | Get the list of video in draft status or video already post to Shopee Video. |
| [`v2.video.get_video_performance_list`](https://open.shopee.com/documents/v2/v2.video.get_video_performance_list?module=129&type=1) | GET | user |  | Get specific performance data for individual post Shopee Video. There is at least a one-day delay. |
| [`v2.video.post_video`](https://open.shopee.com/documents/v2/v2.video.post_video?module=129&type=1) | POST | user |  | You need to call v2.media.init_video_upload, v2.media.upload_video_part, and v2.media.complete_video_upload to upload the video, then call … |

## Voucher

| API | Method | Type | | Summary |
| --- | --- | --- | --- | --- |
| [`v2.voucher.add_voucher`](https://open.shopee.com/documents/v2/v2.voucher.add_voucher?module=112&type=1) | POST | shop | ✅ | Add voucher |
| [`v2.voucher.delete_voucher`](https://open.shopee.com/documents/v2/v2.voucher.delete_voucher?module=112&type=1) | POST | shop | ✅ | Delete voucher |
| [`v2.voucher.end_voucher`](https://open.shopee.com/documents/v2/v2.voucher.end_voucher?module=112&type=1) | POST | shop | ✅ | End Voucher |
| [`v2.voucher.get_voucher`](https://open.shopee.com/documents/v2/v2.voucher.get_voucher?module=112&type=1) | GET | shop | ✅ | Get Voucher Detail |
| [`v2.voucher.get_voucher_list`](https://open.shopee.com/documents/v2/v2.voucher.get_voucher_list?module=112&type=1) | GET | shop | ✅ | Get Voucher List |
| [`v2.voucher.update_voucher`](https://open.shopee.com/documents/v2/v2.voucher.update_voucher?module=112&type=1) | POST | shop | ✅ | Update voucher |
