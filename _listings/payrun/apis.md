---
name: PayRun
x-slug: payrun
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Codes
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO - Deletes the nominal codes
  x-api-slug: employeremployeridnominalcodenominalcodeid-delete
  description: Deletes the nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/employeremployeridnominalcodenominalcodeid-delete-openapi.md
- name: Pay Run.IO - Gets the nominal codes
  x-api-slug: employeremployeridnominalcodes-get
  description: Gets the nominal code links
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/employeremployeridnominalcodes-get-openapi.md
- name: Pay Run.IO - Gets the pay codes from the employer
  x-api-slug: employeremployeridpaycodes-get
  description: Get links to all the pay codes for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/employeremployeridpaycodes-get-openapi.md
- name: Pay Run.IO - Get pay codes with tag
  x-api-slug: employeremployeridpaycodestagtagid-get
  description: Gets the pay codes with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Payments, API Provider, Technology, SaaS, Profiles, Service API, Relative
    Data, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/codes/master/_listings/payrun/employeremployeridpaycodestagtagid-get-openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-api-gallery
  url: http://paypal.api.gallery.streamdata.io
- type: x-api-stack
  url: http://payrun.stack.network
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---