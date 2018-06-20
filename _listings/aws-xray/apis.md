---
name: AWS X-Ray
x-slug: aws-xray
description: AWS X-Ray helps developers analyze and debug production, distributed
  applications, such as those built using a microservices architecture. With X-Ray,
  you can understand how your application and its underlying services are performing
  to identify and troubleshoot the root cause of performance issues and errors. X-Ray
  provides an end-to-end view of requests as they travel through your application,
  and shows a map of your applications underlying components. You can use X-Ray to
  analyze both applications in development and in production, from simple three-tier
  applications to complex microservices applications consisting of thousands of services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS X-Ray
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/apis.md
specificationVersion: "0.14"
apis:
- name: AWS X-Ray API Batch Get Traces
  x-api-slug: aws-xray-api
  description: Retrieves a list of traces specified by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=BatchGetTraces
  tags: Traces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actionbatchgettraces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actionbatchgettraces-get-openapi.md
- name: AWS X-Ray API Get Service Graph
  x-api-slug: aws-xray-api
  description: |-
    Retrieves a document that describes services that process incoming requests, and
          downstream services that they call as a result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=GetServiceGraph
  tags: Service Graph
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongetservicegraph-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongetservicegraph-get-openapi.md
- name: AWS X-Ray API Get Trace Graph
  x-api-slug: aws-xray-api
  description: Retrieves a service graph for one or more specific trace IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=GetTraceGraph
  tags: Trace Graph
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongettracegraph-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongettracegraph-get-openapi.md
- name: AWS X-Ray API Get Trace Summaries
  x-api-slug: aws-xray-api
  description: |-
    Retrieves IDs and metadata for traces available for a specified time frame using an
          optional filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=GetTraceSummaries
  tags: Trace Summaries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongettracesummaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actiongettracesummaries-get-openapi.md
- name: AWS X-Ray API Put Telemetry Records
  x-api-slug: aws-xray-api
  description: Used by the AWS X-Ray daemon to upload telemetry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=PutTelemetryRecords
  tags: Telemetry Records
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actionputtelemetryrecords-get-openapi.md
- name: AWS X-Ray API Put Trace Segments
  x-api-slug: aws-xray-api
  description: Uploads segment documents to AWS X-Ray.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: ://///?Action=PutTraceSegments
  tags: Trace Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/actionputtracesegments-get-openapi.md
- name: AWS X-Ray API
  x-api-slug: aws-xray-api
  description: AWS X-Ray helps developers analyze and debug production, distributed
    applications, such as those built using a microservices architecture. With X-Ray,
    you can understand how your application and its underlying services are performing
    to identify and troubleshoot the root cause of performance issues and errors.
    X-Ray provides an end-to-end view of requests as they travel through your application,
    and shows a map of your applications underlying components. You can use X-Ray
    to analyze both applications in development and in production, from simple three-tier
    applications to complex microservices applications consisting of thousands of
    services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: :///
  tags: AWS X-Ray
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-x-ray/master/_listings/aws-xray/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/xray/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/xray/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/xray/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/xray/pricing/
- type: x-website
  url: https://aws.amazon.com/xray/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---