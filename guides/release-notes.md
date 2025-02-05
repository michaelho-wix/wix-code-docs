# Release Notes

We're always adding and updating the Velo APIs, and we want you to have one place to find all of our latest changes and cool additions.

An orange dot <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="10" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> appears next to the **Release Notes** section in the left tree when new release notes are added, and the latest updates are tagged with a <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="10" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> in the heading.

We love hearing your feedback!
Lots of our bugs come from users like you and you can help us improve the docs by reporting them to us. You can report bugs and other feedback through these links found at the bottom of our docs.

![](../media/feedback.png)

We also keep a list of **doc bugs** that are in our backlog, with information that can be helpful to our users even before they are fixed. You can see them [here](https://view.monday.com/97005963-d254f39325f60e6d86ffb64c39192f84).

---

##

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Added Velo Package Readmes

By popular requests we've added the [readme files](https://www.wix.com/velo/reference/velo-package-readmes/about-velo-packages) for [Velo Packages](https://support.wix.com/en/article/velo-about-packages) to the API Reference. This will allow you to keep the readme file open side by side with your code file.

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Updated: Clarified Path and Prefix

`wix-location`

We updated the [path](https://www.wix.com/corvid/reference/wix-location/path) graphics to show the correct path and included a statement that prefix is for dynamic pages only. (June 14, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New API: Multi File Upload

`Wix Editor Elements ($w)`

You can now upload multiple image, video, and gallery (images and video) files at a time. This [function](https://www.wix.com/velo/reference/$w/uploadbutton/uploadfiles) replaces the now deprecated startUpload function. (June 14, 2021)


### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Updated: Stores: Add "ribbon" Field to Product Entity

`wix-stores-backend`

On the Product entity, the `ribbons` field, which took an array and was read-only, has been deprecated. The new field [`ribbon`](https://www.wix.com/velo/reference/wix-stores-backend/createproduct), which takes a string and is writable upon product creation, replaces it. (June 13, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Updated: Fixed Bookings hasNext Example

`wix-bookings`

We fixed the import statement in the examples. (June 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Update: onBeforeSave Returns a Promise

`wix-data`

We fixed the description of [`onBeforeSave`](https://www.wix.com/velo/reference/wix-dataset/dataset/onbeforesave) to say it returns a promise that resolves to a boolean not a boolean. (June 6, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New API: Manage Bookings Resources and Sessions

`wix-bookings-backend`

The bookings backend API now includes functionality to add, delete, manage, and query [resources](https://www.wix.com/velo/reference/wix-bookings-backend/resources) and [sessions](https://www.wix.com/velo/reference/wix-bookings-backend/sessions). (May 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New APIs: Stores showMinicart and hideMinicart

`wix-stores`

With the new [`cart.showMiniCart()`](https://www.wix.com/velo/reference/wix-stores/cart/hideminicart) and [`cart.hideMiniCart()`](https://www.wix.com/velo/reference/wix-stores/cart/hideminicart) APIs you can easily show and hide the Mini Cart from appearing on the page. (May 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New API: Stores updateLineItemQuantity

`wix-stores`
With the new [`cart.updateLineItemQuantity()`](https://www.wix.com/velo/reference/wix-stores/cart/updatelineitemquantity) function you can set the quantity of a certain line item of the store cart. (May 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New API: Stores addProducts

`wix-stores`

With the new [`cart.addProducts()`](https://www.wix.com/velo/reference/wix-stores/cart/addproducts) function you can add one or more products to the store cart by passing the productId, the desired quantity, and if necessary, any specific product options. (May 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> Update: Stores: Migrate to wix-stores.cart/product

`wix-stores`

As part of a redesign of the Wix-Stores API, several new functions have been added and existing functions have been migrated to either the Cart or Product modules.

The API ref has been updated with migration instructions for users using the old functions.

Several new functions have been added as well: cart.addProducts(), cart.apply/removeCoupon(), cart.showMiniCart, cart.hideMiniCart(), and cart.updateLineItemQuantity().

Learn more:

* [https://www.wix.com/velo/reference/wix-stores/cart/introduction](https://www.wix.com/velo/reference/wix-stores/cart/introduction)

* [https://www.wix.com/velo/reference/wix-stores/product/introduction](https://www.wix.com/velo/reference/wix-stores/product/introduction)

(May 10, 2021)

### <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="12" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> New API: Stores Apply & Remove Coupon

`wix-stores`

With the new [`cart.applyCoupon()`](https://www.wix.com/velo/reference/wix-stores/cart/applycoupon) and [`cart.removeCoupon()`](https://www.wix.com/velo/reference/wix-stores/cart/applycoupon) functions you can add a coupon to the store cart by passing the coupon code, or remove a previously applied coupon. (May 10, 2021)

### Updated: Removed tip to use onInput with richTextBox

`Wix Editor Elements ($w)`

onInput is not supported for richTextBox. We removed a [tip](https://www.wix.com/velo/reference/$w/richtextbox/onkeypress) to use onInput to get the value of the latest keyboard event for a richTextBox. (May 5, 2021)

### Updated: Effect options for show and hide are optional

`Wix Editor Elements ($w)`

We updated the [show and hide functions](https://www.wix.com/velo/reference/$w/hiddenmixin) to indicate that the effectOptions are optional. (May 5, 2021)

### Updated: afterUpdate supports the currentItem property

`wix-data`

We added back information that the [`afterUpdate`](https://www.wix.com/velo/reference/wix-data/hooks/afterupdate) hook supports the currentItem property in the updateHookContext parameter. (May 5, 2021)

### Updated: isReferenced supports the wixDataOptions parameter

`wix-data`

We added information that [`isReferenced`](https://www.wix.com/velo/reference/wix-data/isreferenced) supports the wixDataOptions parameter, which enables suppressAuth and suppressHooks. (May 5, 2021)

### Updated: queryReferenced options parameter is listed as optional

`wix-data`

The options parameter of [`queryReferenced()`](https://www.wix.com/velo/reference/wix-data/queryreferenced) was mistakenly listed as required. We fixed it to be optional. (May 5, 2021)

### Updated: New env property added to WixRouterRequest object

`wix-router`

We added a new [`env`](https://www.wix.com/velo/reference/wix-router/wixrouterrequest/env) property to WixRouterRequest.

When possible, the rendering process is split in two, to improve performance. The first cycle in the process is initiated from backend rendering, and the second cycle is initiated from client-side rendering. You can use the env property to check whether the current rendering cycle is occurring on the backend or the client side. (May 5, 2021)

### Updated: Size property of File object for UploadButton is Number

`Wix Editor Elements ($w)`

We changed the type of the size property of the object that is returned by the [`value`](https://www.wix.com/velo/reference/w/uploadbutton/value) property from string to number. (May 5, 2021)

### Updated: Pricing Plans setPlanVisibility returns a complete pricing plan

`wix-pricing-plans-backend`

The [`setPlanVisibility`](https://www.wix.com/velo/reference/wix-pricing-plans-backend/setplanvisibility) function now returns a complete pricing plan object when its visibility is set. (May 5, 2021)

### New API: warmupData

`wix-window`

With the new [`warmupData`](https://www.wix.com/velo/reference/wix-window/warmupdata-obj) API, you can optimize data loading for sites that render both in the backend code and in the client-side code, allowing costly data fetching operations to be done only once. (April 13, 2021)

### Updated: insertReference() only works with multi-reference fields

`wix-data`

We added a note that [`insertReference()`](https://www.wix.com/velo/reference/wix-data/insertreference) only works with multi-reference fields. (April 13, 2021)

### Update: 512 kb limit for http functions

`wix-http-functions`

We added note that [http function requests](https://www.wix.com/velo/reference/wix-http-functions/wixhttpfunctionrequest-obj/body) have a request payload limit of 512 kb. (April 12, 2021)

### New API: Login as a popup option

`wix-users`

With the new [modal option](https://www.wix.com/velo/reference/wix-users/promptlogin) for the wix-users [`promptLogin()`](https://www.wix.com/velo/reference/wix-users/promptlogin) function, you can let visitors log in using a modal popup. (April 12, 2021)

### New API: CRM Contacts

`wix-crm-backend`

We released new [CRM Contacts APIs](https://www.wix.com/velo/reference/wix-crm-backend) allowing you to:

- Create, update, get, query, and delete contacts
- Label/unlabel contacts
- Manage labels
- Manage custom fields

This replaces most of the existing Contacts functions, and those functions have been updated with migration instructions. Existing functions are supported so you don't need to migrate immediately. (April 12,2021)

### Updated: Added the suppressAuth option to createInvoicePreviewUrl()

`wix-billing-backend`

We added suppressAuth options to [`createInvoicePreviewUrl()`](https://www.wix.com/velo/reference/wix-billing-backend/invoices-obj/createinvoicepreviewurl) to allow customers to generate the invoice preview link. (April 12, 2021)

### Updated: Added note that setFilter() on a read-write dataset saves changes in the input field

`wix-dataset`

When you call [`setFilter()`](https://www.wix.com/velo/reference/wix-dataset/dataset/setfilter) on a dataset with a connected input field, any changes made in the input field are also saved. (April 11, 2021)

### Update: Remove read-only fields from updateUserFields parameters

`wix-users-backend`

We removed the read-only fields from the list of parameters for [`updateUserFields()`](https://www.wix.com/velo/reference/wix-users-backend/updateuserfields). (April 11, 2021)

### New Wix Stores Variants Collection in the Content Manager and Velo Databases

`wix-stores`

Alongside Orders, Products, and other Stores collections, Variants are now available for access and query using Velo and the Content Manager.

Variants are combinations of product options, and until now they were only accessible per product. The new Variants collection includes all of a store's variants.

Learn more about the new [Wix Stores Variants Collection](https://support.wix.com/en/article/velo-wix-stores-variants-collection-fields). (April 1, 2021)

### Updated: Added updatedItemsIds to WixDataBulkResult

We added the `updatedItemIds` property to the `WixDataBulkResult` object,  which is returned by the [`bulkInsert()`](https://www.wix.com/velo/reference/wix-data/bulkinsert), [`bulkSave()`](https://www.wix.com/velo/reference/wix-data/bulksave), and [`bulkUpdate()`](https://www.wix.com/velo/reference/wix-data/bulkupdate) functions. (March 15, 2021)

### Updated: Added information when getItem() returns null

We added information that if an item doesn't exist, [`getItem()`](https://www.wix.com/velo/reference/wix-storage/storage/getitem) returns null. (March 15, 2021)

### New API: onAudioTranscoded

`wix-media-backend`

In addition to video files, audio files that are imported or uploaded to the Media Manager require transcoding, and are not immediately available until the transcoding has completed.

Similar to the onVideoTranscoded() API, the new [`onAudioTranscoded`](https://www.wix.com/velo/reference/wix-media-backend/events/onaudiotranscoded) API event handler runs when an uploaded audio file has finished transcoding. (March 10, 2021)

### New API Reference Feature: Show Members open by default
The table that lists the properties in a returned object used to be closed by default and would require you to click **Show Members** to view it. The expandable is now open by default. You can see an example in the **Returns** table for [`createProduct`](https://www.wix.com/velo/reference/wix-stores-backend/createproduct). (March 7, 2021)

### New Release Notes information 

We will now label the latest updates in the Release Notes with &nbsp; <svg viewBox="0 0 6 6" fill="currentColor" width="6" height="10" data-hook="changelog-pimple" class="_28uM4"><circle cx="3" cy="12" r="3" transform="translate(0 -9)" fill="#EA5F0E" fill-rule="evenodd"></circle></svg> &nbsp; in the heading to make it easier to find the latest changes. (March 7, 2021)

### Remove mention of currentItem from the context of some data hooks

`wix-data`

The `context.currentItem` parameter is only relevant for `beforeUpdate()` and `beforeRemove()` hooks. The property was removed from the documentation for all other hooks. (March 4, 2021)

### New API: Bookings Events

`wix-bookings-backend`

[Backend events](https://www.wix.com/velo/reference/wix-bookings-backend/events) have been added to Wix Bookings.
The events  are fired for the following actions:

* A new booking request is created.
* A booking request is confirmed or declined.
* A booking is canceled.
* A booking  schedule is updated.
* Booking attendance information is updated.

(March 2, 2021)

### Clarified opacity and hidden for timeline

`wix-animations`

* Updated the target parameter type to `Element` from `mixin`.  
* Clarified that only elements that mix in the `hiddenMixin` can be the target.
* Clarified that the unit for opacity is from 0.0 - 1.0.

(March 2, 2021)

### New API: Price per unit data fields added to product object

`wix-stores-backend`

Price Per Unit data fields were added to APIs returning product objects and product variant objects. These APIs mirror the Dashboard feature that allows you to display a product's base and total quantity/weight/area. Complies with requirements in the German market. (February 22, 2021)

### New API: Pricing Plans: Plan management

`wix-pricing-plans-backend`

With the new [pricing-plans-backend](https://www.wix.com/velo/reference/wix-pricing-plans-backend) APIs, you can manage your APIs in ways that before, you could only do from the Dashboard.

Now you can create, update, hide, and archive pricing plans. You can set and clear which pricing plan is the primary plan and rearrange the order in which plans are displayed on the site. And we now supply different ways for you to get information about existing plans, such as getting a single plan, getting statistics for a plan, listing public/all plans, and performing queries. (February 7, 2021)

### New API Reference Feature: Release Notes change indicator

A red dot now appears next to the **Release Notes** section in the left tree when it is updated. More enhancements on the way. (February 3, 2021)

### Updated: getSecret does not require Members Area

`wix-secret-backend`

We removed a note that said you need the Members Area on your site to work with the [`getSecret()`](https://www.wix.com/velo/reference/wix-secrets-backend/getsecret) API. (February 3, 2021)

### Updated: Slot Id parameter fixed

`wix-bookings`

We changed `slot_id` to `slotId` in [`getCheckoutOptions()`](https://www.wix.com/velo/reference/wix-bookings/getcheckoutoptions). (February 3, 2021)

### Updated: getCurrentMemberOrders returns a promise

`wix-paid-plans`

[`getCurrentMemberOrders()`](https://www.wix.com/velo/reference/wix-paid-plans/getcurrentmemberorders) returns a promise that resolves to an array. We previously stated that the function returns an array.  (February 3, 2021)

### Updated: cancelOrder throws an error

`wix-paid-plans`

We clarified that [`cancelOrder`](https://www.wix.com/velo/reference/wix-paid-plans/cancelorder) throws an error when **[Allow Plan Cancellation](https://support.wix.com/en/article/pricing-plans-allowing-clients-to-cancel-plans)** is set to False in the Dashboard. (February 3, 2021)

### Updated: Recommend using getCurrentGeolocation with setTimeout 

`wix-window`

In cases where the site visitor's browser is set to not detect locale, the promise does not resolve or reject. We added a note recommending using [`getCurrentGeoLocation()`](https://www.wix.com/velo/reference/wix-window/getcurrentgeolocation) with `setTimeout` to handle the unresolved Promise. (February 3, 2021)

### Updated: Hooks run when data is imported

`wix-data`

We added a note that the [`beforeInsert`](https://www.wix.com/velo/reference/wix-data/hooks/beforeinsert) and [`afterInsert`](https://www.wix.com/velo/reference/wix-data/hooks/afterinsert) hooks run when data is imported to either Live or Sandbox collections. (February 3, 2021)

### Updated: queryReferenced() only works with multiple-item reference fields

`wix-data`

We added a note that you can only use the [`queryReferenced()`](https://www.wix.com/velo/reference/wix-data/queryreferenced) function with multiple-item reference fields and not with single-item (regular) reference fields. (February 3, 2021)

### Updated: Use the checked property with the Switch element

`Wix Editor Elements ($w)`

The `value` property does not work with the [`Switch`](https://www.wix.com/velo/reference/w/switch) element. We added a note to use the `checked` property instead. We also added an example for using the `checked` property to set the `Switch` state. (February 3, 2021)

### Updated: RichTextBox does not support KeyboardEvent and onInput

`Wix Editor Elements ($w)`

`KeyboardEvent` doesn’t fire and `onInput` is not supported for [`RichTextBox`](https://www.wix.com/velo/reference/w/richtextbox) elements. We removed a reference to the `RichTextBox` element from the `KeyboardEvent` documentation and added a note to `onInput` that it is not supported for `RichTextBox` elements. (February 3, 2021)

### Updated: SelectionTags options property changes

`Wix Editor Elements ($w)`

Setting the [`options`](https://www.wix.com/velo/reference/$w/selectiontags/options) property no longer clears the `value` and `selectedIndices` of the selection tags. This allows users to add and reorder choices without clearing the visitor's selection. Only values that no longer match the new options are cleared.

Setting `value` no longer lets you set values that do not match any of the options. (February 3, 2021)

### Updated: formattedPrice and formattedDiscountedPrice are read-only

`wix-stores-backend`

We removed a reference to `formattedPrice` and `formattedDiscountedPrice` fields for [`updateVariantData()`](https://www.wix.com/velo/reference/wix-stores-backend/updatevariantdata) since they are read-only and can't be set. (February 3, 2021)

### Updated: SSL note in wixWindow.openModal() 

`wix-window`

It is not possible to turn SSL off with Velo. We removed a part of the note that was misleading. (January 20, 2021)

### New API: Coupons events

`wix-marketing-backend`

With the new [Coupon backend events](https://www.wix.com/velo/reference/wix-marketing-backend/events) you can write code that is triggered when a coupon is created, updated, deleted, or applied. (January 19, 2021)

### New API: Added appID to Coupons API

`wix-marketing-backend`

Added the `appID` property to the CouponEvent object. The ID of the app that created the coupon. Empty if created by the site owner. (January 19, 2021)

### Updated: update

erInfo deletes any non-updated properties

`wix-bookings-backend`

Updated an example and added a note that [`updateCustomerInfo`](https://www.wix.com/velo/reference/wix-bookings-backend/bookings/updatecustomerinfo) updates the entire object and that any properties not included in the object passed will be deleted. (January 14, 2021)

### New API: Cancel & Refund events

`wix-stores-backend`

With the new [`onOrderRefunded()`](https://www.wix.com/velo/reference/wix-stores-backend/events/onorderrefunded) & [`onOrderCanceled()`](https://www.wix.com/velo/reference/wix-stores-backend/events/onorderrefunded) backend events you can now write code that is triggered when an order is refunded and/or canceled. (January 14, 2021)

### New API: Bookings backend

`wix-bookings-backend`

Backend APIs are now available to manage Bookings. The [`wix-bookings-backend`](https://www.wix.com/velo/reference/wix-bookings-backend) API provides bookings functionality allowing you to:

- List and query booking information.
- Confirm pending booking requests.
- Decline pending booking requests.
- Cancel a booking.
- Set attendance for booked sessions.
- Mark a booking as paid.
- Update the customer's booking information.

(January 12, 2021)

### New API: Increment inventory

`wix-stores-backend`

With the new Wix Stores [`incrementInventory()`](https://www.wix.com/velo/reference/wix-stores-backend/incrementinventory) API you can increment a product variant's stock in the store's inventory. Pass a variantId and either a productID or an inventoryId, as well as the integer to increment by. (December 31, 2020)

### Updated: Added multiple locations to ServiceAvailability object

`wix-bookings`

The `ServiceAvailability` object returned by [`getServiceAvailability`](https://www.wix.com/velo/reference/wix-bookings/getserviceavailability) now includes a location property. If the service is offered in multiple locations, a slot is returned for each location. (December 30, 2020)

### Updated: Upload button now indicates if a file fails to upload

`Wix Editor Elements ($w)`

The `valid` property of [`UploadButton`](https://www.wix.com/velo/reference/$w/uploadbutton) is set to `false` when a file fails to upload. Previously this was only set if `required == TRUE`. (December 27, 2020)

### Updated: openLightbox requires onReady

`wix-window`

Even though [`openLightbox`](https://www.wix.com/velo/reference/wix-window/openlightbox) is not part of `$w` it can only be called after the `onReady` event has fired. (December 27, 2020)

### Updated: Wix Data is eventually consistent

`wix-data`

The wix-data API is [eventually consistent](https://www.wix.com/velo/reference/wix-data/introduction#wix-data_introduction_wix-data-and-eventual-consistency), meaning that sometimes updates to your database collection are not immediate. There may be a short delay until the system is up-to-date with your recent changes. During the delay, the data you get back may not reflect those changes. (December 27, 2020)

### API Updated: Added seoData field to the Product object

We added the `seoData` field to the Product object. This mirrors the SEO data added in the dashboard and allows for adding custom SEO tags when using [`createProduct()`](https://www.wix.com/velo/reference/wix-stores-backend/createproduct). (December 27, 2020)

### Updated: Editor elements ($w) progressBar.value is a get or set

`Wix Editor Elements ($w)`

We incorrectly stated that you could only “get” the `value` of the [`ProgressBar`](https://www.wix.com/velo/reference/$w/progressbar/value) element. We clarified that you can both “get” and “set” the `value` property. (December 24, 2020)

### Updated: bulkUpdate clarification

`wix-data`

We were a bit vague about how [`bulkUpdate`](https://www.wix.com/velo/reference/wix-data/bulkupdate) works. We now stress in the explanation that `bulkUpdate` replaces all properties of the existing, matching items. When specifying which properties you want to update, the values of any properties that are not specified are lost. (December 24, 2020)

### New API: privacyStatus property for register function in wix-users and wix-users-backend

`wix-users`

`wix-users-backend`

There is a new privacyStatus parameter for the [`register`](https://www.wix.com/velo/reference/wix-users/register) function. Options are `PUBLIC` and `PRIVATE`. (December 24, 2020)

### Updated: Clarified creation of routers.js file

`wix-router`

The [introduction](https://www.wix.com/velo/reference/wix-router/introduction) implied that the user needs to create the `routers.js` file. Actually, when you set up your router, the file is created for you. We clarified that you do not need to manually create the `routers.js` file.

We also reviewed the existing explanations and made some updates, including: 

- How to work with routers, based on changes made in the Editor. 
- How we explain the URL needed for [WixRouterRequest](https://www.wix.com/velo/reference/wix-router/wixrouterrequest/introduction). 
- Adding and fixing links.
- Fixing a typo in an example.

(December 24, 2020)

### New API: wix-users-backend Roles

`wix-users-backend`

We added the [`assignRole()`](https://www.wix.com/velo/reference/wix-users-backend/roles-obj/assignrole) and [`removeRole()`](https://www.wix.com/velo/reference/wix-users-backend/roles-obj/removerole) functions to the new `Roles` API in `wix-users-backend`, allowing you to manage site member access to restricted pages. (December 24, 2020)

### New API: VideoBox

`Wix Editor Elements ($w)`

Velo's APIs are now available to control how videos play in [`VideoBox`](https://www.wix.com/velo/reference/$w/videobox) elements on your site. Video boxes allow you to showcase your videos in beautifully-designed video containers. Unlike VideoPlayer elements, VideoBox elements do not have controls, text descriptions, titles and cannot be displayed in full screen mode. This gives video boxes a clean look.
You can use the APIs to manage video boxes for: 

- Videos uploaded to your site
- Transparent videos uploaded to your site
- Videos/Transparent videos from the  Wix Media library

(December 7, 2020)

### Updated: textInput.maxLength remove max length

`Wix Editor Elements ($w)`

The instructions to remove the [`maximum length`](https://www.wix.com/velo/reference/$w/textinput/maxlength) restriction incorrectly stated to set maxLength to 0. We clarified that you can format the text using the html property. (December 7, 2020)

### Updated: text styles

We listed the supported styles and formats for [`text type elements`](https://www.wix.com/velo/reference/$w/text/introduction) but did not explain how to use them. We clarified that you can format the text using the html property. (December 7, 2020)

### Updated: uploadButton.reset 

`Wix Editor Elements ($w)`

We clarified that the [`reset()`](https://www.wix.com/velo/reference/$w/uploadbutton/reset) function clears the files in the value property. (December 7, 2020)

### Updated: radioButtonGroup options 

`Wix Editor Elements ($w)`

The description incorrectly stated that [`options`](https://www.wix.com/velo/reference/$w/radiobuttongroup/options) is an object. We clarified that options is an array of option objects. (December 7, 2020)

### Updated: getCheckoutOptions slotID

`wix-bookings`

In the [`getCheckoutOptions`](https://www.wix.com/velo/reference/wix-bookings/getcheckoutoptions) parameter table, slot_ID was formatted incorrectly. The correct format is slotID. (December 7, 2020)

### Updated: wixWindow.scrollTo coordinates

`wix-window`

In the [`scrollTo`](https://www.wix.com/velo/reference/wix-window/scrollto) function we didn’t mention how to get the coordinates of a given location. We added how to get the coordinates of a location on the page using the Editor toolbar. (December 7, 2020)

### Updated: wixLocation URL structure

`wix-location`

The layout for describing the different parts of the [`URL`](https://www.wix.com/velo/reference/wix-location/introduction) was a bit confusing. We changed the URL breakdown to match the same layout as the wixHttpFunctionRequest object in the wix-http-functions API for consistency. (December 7, 2020)

### New API: Wix Forum Backend Event APIs

`wix-forum-backend`

With the new [Forum Backend Events](https://www.wix.com/velo/reference/wix-forum-backend) you can react to activity on your forum. You can run custom code when forum categories, posts, and comments are created, updated, deleted, posted, pinned, voted on, liked, reported, and more. For example, you can send a custom email to a poster when their post is liked, display a message when a comment is marked as best, or set up an alert when a post or comment is reported. (November 1, 2020)

### New API: removeProductFromCart

`wix-stores`

With [`removeProductFromCart()`](https://www.wix.com/velo/reference/wix-stores/removeproductfromcart) you can remove a line item/product from the cart. (November 1, 2020)

### New API: onWixFormSubmit() event handler in the WixForms API

`wix-crm`

With the new [`onWixFormSubmit()`](https://www.wix.com/velo/reference/wix-crm/$w-wixforms/onwixformsubmit) event handler in the WixForms API, you can perform validations on your forms immediately after visitors submit the form yet before the server starts any processing. (October 20, 2020)

### Updated: wixLocation.to() does not work in preview

`wix-location`

Added a note that [`wixLocation.to()`](https://www.wix.com/velo/reference/wix-location/to) only works on a published site and not while previewing. (October 13, 2020)

### Updated: htmlComponent can only embed a PDF file with a Premium account

`$w.HtmlComponent`

To embed a PDF in an [HtmlComponent](https://www.wix.com/velo/reference/$w/htmlcomponent/introduction) you must upgrade your site to a Premium Plan. (October 13, 2020)

### New API: Decrement inventory

`wix-stores-backend`

Manually [decrement](https://www.wix.com/velo/reference/wix-stores-backend/decrementinventory) a product variant's stock in inventory. This functionality is helpful for creating an inventory management page on your site. (October 11, 2020)

### Updated: Added Stackdriver information to Site Monitoring introduction

`site-monitoring`

Added [information](https://www.wix.com/velo/reference/spis/site-monitoring/introduction) about connecting Wix site events to Google's Stackdriver external monitoring tool. (September 16, 2020)

### Updated: Changed slider.value from read only to read & write

`$w.slider` 

The [`value`](https://www.wix.com/velo/reference/$w/slider/value) property for the Slider element was described as read only but it should be read and write. (September 15, 2020)

### Updated: Added more information for returned object properties from Validity property

`ValidatableMixin`

Added more content to the table that displays details of the object returned by [`validity`](https://www.wix.com/velo/reference/$w/validatablemixin/validity). (September 15, 2020)

### Updated: Added information that some getProductVariants() parameter fields are optional

`wix-stores`

Added information that some of the parameter fields for [getProductVariants()](https://www.wix.com/velo/reference/wix-stores/getproductvariants) are optional. (September 14, 2020)

### Updated: createProduct() SKU is a string

`stores-backend`

The `sku` property for [createProduct()](https://www.wix.com/velo/reference/wix-stores-backend/createproduct) was described as a number, but it is a string. (September 14, 2020)

### Updated: Added information about getFileURL token expiring

`wix-media-backend`

Added information that the token returned by [`getFileUrl()`](https://www.wix.com/velo/reference/wix-media-backend/mediamanager-obj/getfileurl) expires after 600 minutes. Described the alternative of creating a static URL without a token. (September 10, 2020)

### Updated: The URL table for wixHttpFunctionRequest

`wix-http-functions`

The table that described the URL structure of a [wixHttpFunctionRequest](https://www.wix.com/velo/reference/wix-http-functions/wixhttpfunctionrequest) was difficult to parse. We've updated the content to make it easier to understand. (September 10, 2020)

### New API: On cart changed event

`wix-stores`

With the new [`onCartChanged()`](https://www.wix.com/velo/reference/wix-stores/oncartchanged) client-side event in wix-stores, you can access information about the site's shopping cart every time an item is added or removed. Useful for creating a promotional lightbox - if product X is added to the cart, offer product Y. (September 7, 2020)

### New API: Consent policy (privacy laws)

`wix-users`

To help your site conform to GDPR and CCPA standards, we now provide Velo APIs for [checking](https://www.wix.com/velo/reference/wix-users/getcurrentconsentpolicy) and [setting](https://www.wix.com/velo/reference/wix-users/setconsentpolicy) visitors' current consent policies. These policies include which cookies the visitor allows and if the visitor allows data transfer to third parties. (September 7, 2020)

### Updated: Added examples to listMemberBadges()

`wix-users-backend`

Added more robust examples to [`listMemberBadges()`](https://www.wix.com/velo/reference/wix-users-backend/badges-obj/listmemberbadges) for how to handle the results. (August 30, 2020)

### New API: Coupon limit per customer

`wix-marketing-backend`

Use the new [limitPerCustomer](https://www.wix.com/velo/reference/wix-marketing-backend/coupons-obj/createcoupon) property that allows for limiting coupon use per customer. Helpful if you'd like to create a coupon to be used only once, or any number of times per customer. (August 23, 2020)

### New API: Custom fulfiller email 

`wix-stores-backend`

Use the new [`sendFulfillmentEmail()`](https://www.wix.com/velo/reference/wix-stores-backend/sendfulfillmentemail) function to send an email containing fulfillment details (products to ship, shipping details, etc.) to a custom fulfiller (a fulfiller not integrated with Wix, like ShipBob or ShipStation). (August 20, 2020)

### New API: Order paid event 

`wix-stores-backend`

Added a new [event](https://www.wix.com/velo/reference/wix-stores-backend/events/onorderpaid) that fires when an order is marked as paid. (August 20, 2020)

### Updated: New array and object data types

`wix-data`

Added information about new array and object types to the [wix-data Introduction](https://www.wix.com/velo/reference/wix-data/introduction). (August 12, 2020)

### New API: Print packing slip

`wix-stores-backend`

Use the new [`getPackingSlipLink()`](https://www.wix.com/velo/reference/wix-stores-backend/getpackingsliplink) function to generate and print a PDF file of an order's packing slip. Especially useful in the ThankYouPage, after an order is completed. (August 11, 2020)

### Updated: New validations for file upload

`wix-media-backend`

The [Upload](https://www.wix.com/velo/reference/wix-media-backend/mediamanager-obj/upload) button can now perform certain validations right after file selection. (August 9, 2020)

### Updated: Mark createContact() parameters as optional

`wix-crm`

Changed the `contactInfo` parameters for [`createContact()`](https://www.wix.com/velo/reference/wix-crm/createcontact) to be optional. (August 9, 2020)

### New API: Print orders

`wix-stores-backend`

Use the new [`getOrdersLink()`](https://www.wix.com/velo/reference/wix-stores-backend/getorderslink) function to generate a PDF file containing information about one of more of your store's orders. (August 6, 2020)

### Updated: New example for onItemReady()

`$w.repeater`

Added a simple [`onItemReady()`](https://www.wix.com/velo/reference/$w/repeater/onitemready) example where `onItemReady()` is triggered when repeater data is set. (August 3, 2020)

### Updated: New example for WixDataQuery.include()

`wix-data`

Added new example in [`WixData.query.include()`](https://www.wix.com/velo/reference/wix-data/wixdataquery/include) to show how to use a reference field from another collection when populating a table with DataPath. (August 3, 2020)

### Updated: Router examples should use https for imageSite links

`wix-router`

The **A router with static data** example for the [`router()`](https://www.wix.com/velo/reference/wix-router/router) function used http URLs in the example for imageSite. They were updated to use https. (August 3, 2020)

### Updated: Secrets API

`wix-secrets-backend`

With the new [Secrets API functions](https://www.wix.com/velo/reference/wix-secrets-backend) you can manage your site secrets with code. Create, update, and delete secrets in the Secrets Manager programmatically without opening the UI. List all your site secrets to find the one you need. (August 2, 2020)

### New API: Fulfillment

`wix-stores-backend`

Use the [`createFulfillment()`](https://www.wix.com/velo/reference/wix-stores-backend/createfulfillment) function to create, update, and delete order fulfillments (as well as set up events for each). (July 30, 2020)

### New API: Create order

`wix-stores-backend`

Use the [`createOrder()`](https://www.wix.com/velo/reference/wix-stores-backend/createorder) function to have more control over various order properties, allowing for more custom order flows. (July 30, 2020)

### New API: Form Builder

`wix-crm` `wix-crm-backend`

With the new Wix Forms APIs,  you can access Wix Form app functionality with code. You can customize how site visitors work with the Wix Form, while taking advantage of the Wix Forms app's ease of design, automatic creation of submission collections, payment receipt, automatic setup of email notifications, and more. You can perform actions both on the [client side](https://www.wix.com/velo/reference/wix-crm/$w-wixforms) and in the [backend](https://www.wix.com/velo/reference/wix-crm-backend/events/onformsubmit). (July 28, 2020)

### Updated: Badges

`wix-users-backend`

With the new [Badges APIs](https://www.wix.com/velo/reference/wix-users-backend/badges)  you can manage your member badges with code. Create, update, and delete badges, assign and remove badges from members, and see which members are associated with each badge. (July 9, 2020)

### Updated: Add information about import and export triggering before and after query hooks 

`wix-data`

Added information that [before](https://www.wix.com/velo/reference/wix-data/hooks/beforequery) and [after](https://www.wix.com/velo/reference/wix-data/hooks/afterquery) query hooks are triggered when items are exported from a collection. (July 9, 2020)
