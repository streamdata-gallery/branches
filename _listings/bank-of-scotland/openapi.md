swagger: "2.0"
x-collection-name: Bank of Scotland
x-complete: 1
info:
  title: Bank of Scotland
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapis-io-apis-for-the-bank-of-scotland-
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: api.bankofscotland.co.uk
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  branches/:
    get:
      summary: Get Branches
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple branches.
      operationId: getBranches
      x-api-path-slug: branches-get
      responses:
        200:
          description: OK
      tags:
      - Branches