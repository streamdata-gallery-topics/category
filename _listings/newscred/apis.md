---
name: NewsCred
x-slug: newscred
description: NewsCred is the leading enterprise content marketing company. NewsCred
  delivers content marketing solutions that drive business results for top brands
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
x-kinRank: "7"
x-alexaRank: "91598"
tags: Category
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/apis.md
specificationVersion: "0.14"
apis:
- name: News Cred Category Sources
  x-api-slug: news-cred
  description: Gets a list of sources that write most frequently about the category
    specified by the dashed name
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/dashed-name/sources/
  tags: News,Category,Dashed-name,Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednamesources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednamesources-get-openapi.md
- name: News Cred Category Topics
  x-api-slug: news-cred
  description: Gets a list of topics within the category specified by the dashed name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/dashed-name/topics/
  tags: News,Category,Dashed-name,Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednametopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednametopics-get-openapi.md
- name: News Cred Category Stories
  x-api-slug: news-cred
  description: Find the top news stories related to a given category. A story is a
    collection of similar articles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/{category-name]/stories/
  tags: News,Category,Category-name],Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorycategorynamestories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorycategorynamestories-get-openapi.md
- name: News Cred Category Articles
  x-api-slug: news-cred
  description: Search for articles within the category specified by dashed name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/{dashed-name}/articles/
  tags: Category,Dashed-name,Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednamearticles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednamearticles-get-openapi.md
- name: News Cred Category Images
  x-api-slug: news-cred
  description: Gets images related to the specified category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com///category/{dashed-name}/images/
  tags: News,Category,Dashed-name,Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednameimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/categorydashednameimages-get-openapi.md
- name: News Cred
  x-api-slug: news-cred
  description: NewsCred is the leading enterprise content marketing company. NewsCred
    delivers content marketing solutions that drive business results for top brands
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/869-newscred.jpg
  humanURL: http://newscred.com
  baseURL: https://api.newscred.com//
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/newscred/openapi.md
x-common:
- type: x-base
  url: http://api.newscred.com
- type: x-blog
  url: http://blog.newscred.com/
- type: x-blog-rss
  url: http://blog.newscred.com/feed/rss/
- type: x-case-studies
  url: http://www.newscred.com/casestudies
- type: x-crunchbase
  url: https://crunchbase.com/organization/newscred
- type: x-crunchbase
  url: http://www.crunchbase.com/company/newscred
- type: x-developer
  url: http://www.newscred.com/developer/docs
- type: x-drupal-plugin
  url: http://www.newscred.com/developer/drupal_integration
- type: x-email
  url: legal@newscred.com
- type: x-email
  url: sales@newscred.com
- type: x-faq
  url: http://www.newscred.com/developer/faq
- type: x-github
  url: https://github.com/newscred
- type: x-pricing
  url: http://newscred.com/pricing
- type: x-privacy
  url: http://www.newscred.com/legal/privacy
- type: x-selfservice-registration
  url: http://www.newscred.com/developer/accesskey
- type: x-terms-of-service
  url: http://www.newscred.com/legal/tos
- type: x-twitter
  url: https://twitter.com/newscred
- type: x-website
  url: http://newscred.com
- type: x-website
  url: https://newscred.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---