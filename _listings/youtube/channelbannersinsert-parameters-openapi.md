---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Parameters Channel Banners Insert
  description: Parameters channelbanners insert
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/jobs:
    get:
      summary: Get Jobs
      description: Lists jobs.
      operationId: getV1Jobs
      x-api-path-slug: v1jobs-get
      parameters:
      - in: query
        name: includeSystemManaged
        description: If set to true, also system-managed jobs will be returned; otherwise
          onlyuser-created jobs will be returned
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results the server should return
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
    parameters:
      summary: Parameters Jobs
      description: Parameters v1 jobs
      operationId: parametersV1Jobs
      x-api-path-slug: v1jobs-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
    post:
      summary: Add Jobs
      description: Creates a job and returns it.
      operationId: postV1Jobs
      x-api-path-slug: v1jobs-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
  /v1/jobs/{jobId}:
    delete:
      summary: Delete Jobs Job
      description: Delete v1 jobs job
      operationId: deleteV1JobsJob
      x-api-path-slug: v1jobsjobid-delete
      parameters:
      - in: path
        name: jobId
        description: The ID of the job to delete
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
    get:
      summary: Get Jobs Job
      description: Get v1 jobs job
      operationId: getV1JobsJob
      x-api-path-slug: v1jobsjobid-get
      parameters:
      - in: path
        name: jobId
        description: The ID of the job to retrieve
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
    parameters:
      summary: Parameters Jobs Job
      description: Parameters v1 jobs job
      operationId: parametersV1JobsJob
      x-api-path-slug: v1jobsjobid-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
  /v1/jobs/{jobId}/reports:
    get:
      summary: Get Jobs Job Reports
      description: |-
        Lists reports created by a specific job.
        Returns NOT_FOUND if the job does not exist.
      operationId: getV1JobsJobReports
      x-api-path-slug: v1jobsjobidreports-get
      parameters:
      - in: query
        name: createdAfter
        description: If set, only reports created after the specified date/time are
          returned
      - in: path
        name: jobId
        description: The ID of the job
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results the server should return
      - in: query
        name: startTimeAtOrAfter
        description: If set, only reports whose start time is greater than or equal
          thespecified date/time are returned
      - in: query
        name: startTimeBefore
        description: If set, only reports whose start time is smaller than the specifieddate/time
          are returned
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
      - Reports
    parameters:
      summary: Parameters Jobs Job Reports
      description: Parameters v1 jobs job reports
      operationId: parametersV1JobsJobReports
      x-api-path-slug: v1jobsjobidreports-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
      - Reports
  /v1/jobs/{jobId}/reports/{reportId}:
    get:
      summary: Get Jobs Job Reports Report
      description: Gets the metadata of a specific report.
      operationId: getV1JobsJobReportsReport
      x-api-path-slug: v1jobsjobidreportsreportid-get
      parameters:
      - in: path
        name: jobId
        description: The ID of the job
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      - in: path
        name: reportId
        description: The ID of the report to retrieve
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
      - Reports
      - Report
    parameters:
      summary: Parameters Jobs Job Report
      description: Parameters v1 jobs job reports report
      operationId: parametersV1JobsJobReportsReport
      x-api-path-slug: v1jobsjobidreportsreportid-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Jobs
      - Job
      - Reports
      - Report
  /v1/media/{resourceName}:
    get:
      summary: Get Media Resource Name
      description: |-
        Method for media download. Download is supported
        on the URI `/v1/media/{+name}?alt=media`.
      operationId: getV1MediaResourcename
      x-api-path-slug: v1mediaresourcename-get
      parameters:
      - in: path
        name: resourceName
        description: Name of the media that is being downloaded
      responses:
        200:
          description: OK
      tags:
      - V1
      - Media
      - Resourcename
    parameters:
      summary: Parameters Media Resource Name
      description: Parameters v1 media resourcename
      operationId: parametersV1MediaResourcename
      x-api-path-slug: v1mediaresourcename-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Media
      - Resourcename
  /v1/reportTypes:
    get:
      summary: Get Reporttypes
      description: Lists report types.
      operationId: getV1Reporttypes
      x-api-path-slug: v1reporttypes-get
      parameters:
      - in: query
        name: includeSystemManaged
        description: If set to true, also system-managed report types will be returned;otherwise
          only the report types that can be used to create new reportingjobs will
          be returned
      - in: query
        name: onBehalfOfContentOwner
        description: The content owners external ID on which behalf the user is acting
          on
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results the server should return
      responses:
        200:
          description: OK
      tags:
      - V1
      - Reporttypes
    parameters:
      summary: Parameters Reporttypes
      description: Parameters v1 reporttypes
      operationId: parametersV1Reporttypes
      x-api-path-slug: v1reporttypes-parameters
      responses:
        200:
          description: OK
      tags:
      - V1
      - Reporttypes
  /activities:
    get:
      summary: Get Activities
      description: Returns a list of channel activity events that match the request
        criteria. For example, you can retrieve events associated with a particular
        channel, events associated with the user's subscriptions and Google+ friends,
        or the YouTube home page feed, which is customized for each user.
      operationId: getActivities
      x-api-path-slug: activities-get
      parameters:
      - in: query
        name: channelId
        description: The channelId parameter specifies a unique YouTube channel ID
      - in: query
        name: home
        description: Set this parameters value to true to retrieve the activity feed
          that displays on the YouTube home page for the currently authenticated user
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: mine
        description: Set this parameters value to true to retrieve a feed of the authenticated
          users activities
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more activity resource properties that the API response will include
      - in: query
        name: publishedAfter
        description: The publishedAfter parameter specifies the earliest date and
          time that an activity could have occurred for that activity to be included
          in the API response
      - in: query
        name: publishedBefore
        description: The publishedBefore parameter specifies the date and time before
          which an activity must have occurred for that activity to be included in
          the API response
      - in: query
        name: regionCode
        description: The regionCode parameter instructs the API to return results
          for the specified country
      responses:
        200:
          description: OK
      tags:
      - Activities
    parameters:
      summary: Parameters Activities
      description: Parameters activities
      operationId: parametersActivities
      x-api-path-slug: activities-parameters
      responses:
        200:
          description: OK
      tags:
      - Activities
    post:
      summary: Add Activities
      description: |-
        Posts a bulletin for a specific channel. (The user submitting the request must be authorized to act on the channel's behalf.)

        Note: Even though an activity resource can contain information about actions like a user rating a video or marking a video as a favorite, you need to use other API methods to generate those activity resources. For example, you would use the API's videos.rate() method to rate a video and the playlistItems.insert() method to mark a video as a favorite.
      operationId: postActivities
      x-api-path-slug: activities-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Activities
  /captions:
    delete:
      summary: Delete Captions
      description: Deletes a specified caption track.
      operationId: deleteCaptions
      x-api-path-slug: captions-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the caption track that is being deleted
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      responses:
        200:
          description: OK
      tags:
      - Captions
    get:
      summary: Get Captions
      description: Returns a list of caption tracks that are associated with a specified
        video. Note that the API response does not contain the actual captions and
        that the captions.download method provides the ability to retrieve a caption
        track.
      operationId: getCaptions
      x-api-path-slug: captions-get
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs that
          identify the caption resources that should be retrieved
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is on
          behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more caption resource parts that the API response will include
      - in: query
        name: videoId
        description: The videoId parameter specifies the YouTube video ID of the video
          for which the API should return caption tracks
      responses:
        200:
          description: OK
      tags:
      - Captions
    parameters:
      summary: Parameters Captions
      description: Parameters captions
      operationId: parametersCaptions
      x-api-path-slug: captions-parameters
      responses:
        200:
          description: OK
      tags:
      - Captions
    post:
      summary: Add Captions
      description: Uploads a caption track.
      operationId: postCaptions
      x-api-path-slug: captions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter specifies the caption resource parts that
          the API response will include
      - in: query
        name: sync
        description: The sync parameter indicates whether YouTube should automatically
          synchronize the caption file with the audio track of the video
      responses:
        200:
          description: OK
      tags:
      - Captions
    put:
      summary: Put Captions
      description: Updates a caption track. When updating a caption track, you can
        change the track's draft status, upload a new caption file for the track,
        or both.
      operationId: putCaptions
      x-api-path-slug: captions-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      - in: query
        name: sync
        description: 'Note: The API server only processes the parameter value if the
          request contains an updated caption file'
      responses:
        200:
          description: OK
      tags:
      - Captions
  /captions/{id}:
    get:
      summary: Get Captions
      description: Downloads a caption track. The caption track is returned in its
        original format unless the request specifies a value for the tfmt parameter
        and in its original language unless the request specifies a value for the
        tlang parameter.
      operationId: getCaptions
      x-api-path-slug: captionsid-get
      parameters:
      - in: path
        name: id
        description: The id parameter identifies the caption track that is being retrieved
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: tfmt
        description: The tfmt parameter specifies that the caption track should be
          returned in a specific format
      - in: query
        name: tlang
        description: The tlang parameter specifies that the API response should return
          a translation of the specified caption track
      responses:
        200:
          description: OK
      tags:
      - Captions
    parameters:
      summary: Parameters Captions
      description: Parameters captions
      operationId: parametersCaptions
      x-api-path-slug: captionsid-parameters
      responses:
        200:
          description: OK
      tags:
      - Captions
  /channelBanners/insert:
    parameters:
      summary: Parameters Channel Banners Insert
      description: Parameters channelbanners insert
      operationId: parametersChannelbannersInsert
      x-api-path-slug: channelbannersinsert-parameters
      responses:
        200:
          description: OK
      tags:
      - Channelbanners
      - Insert
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---