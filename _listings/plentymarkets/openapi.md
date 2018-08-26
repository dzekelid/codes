---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/orders/coupons/codes/contacts/{contactId}:
    get:
      summary: List redeemed coupon codes of a contact
      description: Lists the redeemed coupon codes of contact. The ID of the contact
        must be specified.
      operationId: getRestOrdersCouponsCodesContactsContact
      x-api-path-slug: restorderscouponscodescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of coupons to be displayed per page
      - in: query
        name: page
        description: The page to get
      responses:
        200:
          description: OK
      tags:
      - List
      - Redeemed
      - Coupon
      - Codes
      - Of
      - Contact
---