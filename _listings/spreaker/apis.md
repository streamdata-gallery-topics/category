---
name: Spreaker
x-slug: spreaker
description: Discover and listen to your favorite podcasts for free or sign up to
  create your own!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
x-kinRank: "8"
x-alexaRank: "12286"
tags: Category
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/spreaker/apis.md
specificationVersion: "0.14"
apis:
- name: Spreaker API Explore Category Items
  x-api-slug: spreaker-api
  description: 'This API returns information and items of a specific category. The
    response contains two properties at root level:'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////explore/{category_id}
  tags: Explore,Category,Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/spreaker/explorecategory-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/spreaker/explorecategory-id-get-openapi.md
- name: Spreaker API
  x-api-slug: spreaker-api
  description: Spreaker platform enables you to host and listen thousands of radio
    shows. Spreaker provides a REST web service that enables developers to read and
    write data to Spreaker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com//
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/spreaker/openapi.md
x-common:
- type: x-base
  url: http://api.spreaker.com/
- type: x-blog
  url: http://blog.spreaker.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/spreaker
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spreaker
- type: x-developer
  url: http://developers.spreaker.com
- type: x-email
  url: info@spreaker.com
- type: x-email
  url: support@spreaker.com
- type: x-email
  url: advertise@spreaker.com
- type: x-email
  url: tonia.maffeo@spreaker.com
- type: x-email
  url: press@spreaker.com
- type: x-email
  url: legal@Spreaker.com
- type: x-github
  url: https://github.com/spreaker
- type: x-linkedin
  url: https://www.linkedin.com/company/spreaker/
- type: x-pricing
  url: http://www.spreaker.com/plans
- type: x-twitter
  url: https://twitter.com/spreaker
- type: x-website
  url: http://spreaker.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---