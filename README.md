# Az_storage_reservations
Az_storage_reservations

----
# SUPPORTED FEATURES & LIMITATIONS
1.	Discounts applicable for only storage block blobs & Az Data Lake Storage Gen2 (ADLS Gen2); Azure files has separate reservations 
2.	Applies only for standard storage accounts (not for premium)
3.	Reservation is for 1 year and 3 years; minimum is 100 TB and in units; geo restrictions applies 
4.	Reservation scope -> { shared, single subs, single resource group and management group } 
5.	Save up to ~38% of our cost comparing pay as you go 
6.	Reservation discount applies to storage capacity only| Bandwidth and request rate are charged at pay-as-you-go rates
7.	Discount is applied to supported storage resources on an hourly basis. Reserved capacity discount is a "use-it-or-lose-it" discount; if we don’t have matching accounts, then pay-as-you-go would be applied 
8.	When we delete a resource, the reservation discount automatically applies to another matching resource in the specified scope
9.	let’s say, if we reserve 100 TB of storage blobs (minimum to start) 
i.	100 TB reservation costs $22,152 - pay-as-you-go (1846 x 12 months) 
ii.	100 TB reservation costs $16,594 - 1-year reserved cost 
iii.	100 TB reservation costs $13,205 - 3-year reserved cost 
payment is monthly split/yearly upfront but its same 
10.	Hot, cool, and archive tier are supported for reservations
11.	All types of redundancy are supported for reservations
12.	Not available for premium storage accounts, general-purpose v1 (GPv1), page blobs, Az Queue storage, or Az Table storage
13.	You may cancel an Azure Storage reservation at any time. When you cancel, you'll receive a prorated refund based on the remaining term of the reservation. The maximum refund per year is $50,000.
14.	Reservations don't renew automatically. You will receive an email notification 30 days prior to the expiration of the reservation, and again on the expiration date

----
# BUYING PROCESS
  * Buy in portal – based on region, access tier and redundancy options.
  * Pay upfront or monthly. 
  * Buy in blocks of 100TB or 1PB. You can combine blocks. 
    Example: 2 x 100TB= 200TB reservation
  * No splitting capacity across subscriptions.
  * No auto renewals. You receive 30-day and day of expiration notifications.
