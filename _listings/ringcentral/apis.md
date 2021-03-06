---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Favorite
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorite/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Favorite Contacts
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfavorite-get
  description: "Returns favorite contacts of the current extension. Favorite contacts
    include both company contacts (extensions) and personal contacts (address book
    records).\nApp Permission\nReadContacts\nUser Permission\nReadPersonalContacts\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadContacts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadPersonalContacts] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorite/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorite/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Favorite Contacts
  x-api-slug: restapiv1-0accountaccountidextensionextensionidfavorite-put
  description: "Updates favorite contacts of the current extension. Favorite contacts
    include both company contacts (extensions) and personal contacts (address book
    records).**Please note**: currently personal address book size is limited to 10
    000 contacts.\nApp Permission\nContacts\nUser Permission\nEditPersonalContacts\nUsage
    Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [records.extensionId] value is invalid\n\n\n400\nFAV-100\nContact
    not found\n\n\n400\nFAV-101\nMore than one contact with the same [records.extensionId]\n\n\n400\nFAV-102\n[records.extensionId]
    and [records.contactId] could not be specified for one contact simultaneously\n\n\n400\nFAV-103\nMore
    than one contact with the same [records.id]\n\n\n400\nFAV-104\nContact limit exceeded\n\n\n400\nFAV-105\nContact
    not found in federated directory\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [Contacts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorite/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidfavorite-put-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---