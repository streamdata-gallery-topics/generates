swagger: "2.0"
x-collection-name: DonorsChoose
x-complete: 1
info:
  title: Donors Choose
  description: our-api-serves-up-project-titles-descriptions-classroom-photos-geotags-full-teacherwritten-essays-and-more--
  termsOfService: http://www.donorschoose.org/help/user_agreement.html
  version: "1"
host: api.donorschoose.org
basePath: common/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /json_api.html:
    post:
      summary: Generate Gift Code
      description: Generate Gift Code
      operationId: generate-gift-code
      x-api-path-slug: json-api-html-post
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Gift
      - Code