---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Add Live Broadcasts Control
  description: Controls the settings for a slate that can be displayed in the broadcast
    stream.
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
    post:
      summary: Add Channel Banners Insert
      description: |-
        Uploads a channel banner image to YouTube. This method represents the first two steps in a three-step process to update the banner image for a channel:

        - Call the channelBanners.insert method to upload the binary image data to YouTube. The image must have a 16:9 aspect ratio and be at least 2120x1192 pixels.
        - Extract the url property's value from the response that the API returns for step 1.
        - Call the channels.update method to update the channel's branding settings. Set the brandingSettings.image.bannerExternalUrl property's value to the URL obtained in step 2.
      operationId: postChannelbannersInsert
      x-api-path-slug: channelbannersinsert-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: channelId
        description: The channelId parameter identifies the YouTube channel to which
          the banner is uploaded
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      responses:
        200:
          description: OK
      tags:
      - Channelbanners
      - Insert
  /channelSections:
    delete:
      summary: Delete Channel Sections
      description: Deletes a channelSection.
      operationId: deleteChannelsections
      x-api-path-slug: channelsections-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube channelSection ID for
          the resource that is being deleted
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      responses:
        200:
          description: OK
      tags:
      - Channelsections
    get:
      summary: Get Channel Sections
      description: Returns channelSection resources that match the API request criteria.
      operationId: getChannelsections
      x-api-path-slug: channelsections-get
      parameters:
      - in: query
        name: channelId
        description: The channelId parameter specifies a YouTube channel ID
      - in: query
        name: hl
        description: The hl parameter indicates that the snippet
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of the YouTube
          channelSection ID(s) for the resource(s) that are being retrieved
      - in: query
        name: mine
        description: Set this parameters value to true to retrieve a feed of the authenticated
          users channelSections
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more channelSection resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Channelsections
    parameters:
      summary: Parameters Channel Sections
      description: Parameters channelsections
      operationId: parametersChannelsections
      x-api-path-slug: channelsections-parameters
      responses:
        200:
          description: OK
      tags:
      - Channelsections
    post:
      summary: Add Channel Sections
      description: Adds a channelSection for the authenticated user's channel.
      operationId: postChannelsections
      x-api-path-slug: channelsections-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Channelsections
    put:
      summary: Put Channel Sections
      description: Update a channelSection.
      operationId: putChannelsections
      x-api-path-slug: channelsections-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Channelsections
  /channels:
    get:
      summary: Get Channels
      description: Returns a collection of zero or more channel resources that match
        the request criteria.
      operationId: getChannels
      x-api-path-slug: channels-get
      parameters:
      - in: query
        name: categoryId
        description: The categoryId parameter specifies a YouTube guide category,
          thereby requesting YouTube channels associated with that category
      - in: query
        name: forUsername
        description: The forUsername parameter specifies a YouTube username, thereby
          requesting the channel associated with that username
      - in: query
        name: hl
        description: The hl parameter should be used for filter out the properties
          that are not in the given language
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of the YouTube
          channel ID(s) for the resource(s) that are being retrieved
      - in: query
        name: managedByMe
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: mine
        description: Set this parameters value to true to instruct the API to only
          return channels owned by the authenticated user
      - in: query
        name: mySubscribers
        description: Use the subscriptions
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more channel resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Channels
    parameters:
      summary: Parameters Channels
      description: Parameters channels
      operationId: parametersChannels
      x-api-path-slug: channels-parameters
      responses:
        200:
          description: OK
      tags:
      - Channels
    put:
      summary: Put Channels
      description: Updates a channel's metadata. Note that this method currently only
        supports updates to the channel resource's brandingSettings and invideoPromotion
        objects and their child properties.
      operationId: putChannels
      x-api-path-slug: channels-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: The onBehalfOfContentOwner parameter indicates that the authenticated
          user is acting on behalf of the content owner specified in the parameter
          value
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Channels
  /commentThreads:
    get:
      summary: Get Comment Threads
      description: Returns a list of comment threads that match the API request parameters.
      operationId: getCommentthreads
      x-api-path-slug: commentthreads-get
      parameters:
      - in: query
        name: allThreadsRelatedToChannelId
        description: The allThreadsRelatedToChannelId parameter instructs the API
          to return all comment threads associated with the specified channel
      - in: query
        name: channelId
        description: The channelId parameter instructs the API to return comment threads
          containing comments about the specified channel
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of comment
          thread IDs for the resources that should be retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: moderationStatus
        description: Set this parameter to limit the returned comment threads to a
          particular moderation state
      - in: query
        name: order
        description: The order parameter specifies the order in which the API response
          should list comment threads
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more commentThread resource properties that the API response will include
      - in: query
        name: searchTerms
        description: The searchTerms parameter instructs the API to limit the API
          response to only contain comments that contain the specified search terms
      - in: query
        name: textFormat
        description: Set this parameters value to html or plainText to instruct the
          API to return the comments left by users in html formatted or in plain text
      - in: query
        name: videoId
        description: The videoId parameter instructs the API to return comment threads
          associated with the specified video ID
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
    parameters:
      summary: Parameters Comment Threads
      description: Parameters commentthreads
      operationId: parametersCommentthreads
      x-api-path-slug: commentthreads-parameters
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
    post:
      summary: Add Comment Threads
      description: Creates a new top-level comment. To add a reply to an existing
        comment, use the comments.insert method instead.
      operationId: postCommentthreads
      x-api-path-slug: commentthreads-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
    put:
      summary: Put Comment Threads
      description: Modifies the top-level comment in a comment thread.
      operationId: putCommentthreads
      x-api-path-slug: commentthreads-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of commentThread
          resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
  /comments:
    delete:
      summary: Delete Comments
      description: Deletes a comment.
      operationId: deleteComments
      x-api-path-slug: comments-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the comment ID for the resource that
          is being deleted
      responses:
        200:
          description: OK
      tags:
      - Comments
    get:
      summary: Get Comments
      description: Returns a list of comments that match the API request parameters.
      operationId: getComments
      x-api-path-slug: comments-get
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of comment
          IDs for the resources that are being retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: parentId
        description: The parentId parameter specifies the ID of the comment for which
          replies should be retrieved
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more comment resource properties that the API response will include
      - in: query
        name: textFormat
        description: This parameter indicates whether the API should return comments
          formatted as HTML or as plain text
      responses:
        200:
          description: OK
      tags:
      - Comments
    parameters:
      summary: Parameters Comments
      description: Parameters comments
      operationId: parametersComments
      x-api-path-slug: comments-parameters
      responses:
        200:
          description: OK
      tags:
      - Comments
    post:
      summary: Add Comments
      description: 'Creates a reply to an existing comment. Note: To create a top-level
        comment, use the commentThreads.insert method.'
      operationId: postComments
      x-api-path-slug: comments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Comments
    put:
      summary: Put Comments
      description: Modifies a comment.
      operationId: putComments
      x-api-path-slug: comments-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Comments
  /comments/markAsSpam:
    parameters:
      summary: Parameters Comments Mark as SPAM
      description: Parameters comments markasspam
      operationId: parametersCommentsMarkasspam
      x-api-path-slug: commentsmarkasspam-parameters
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Markasspam
    post:
      summary: Add Comments Mark as SPAM
      description: Expresses the caller's opinion that one or more comments should
        be flagged as spam.
      operationId: postCommentsMarkasspam
      x-api-path-slug: commentsmarkasspam-post
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs of comments
          that the caller believes should be classified as spam
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Markasspam
  /comments/setModerationStatus:
    parameters:
      summary: Parameters Comments Set Moderation Status
      description: Parameters comments setmoderationstatus
      operationId: parametersCommentsSetmoderationstatus
      x-api-path-slug: commentssetmoderationstatus-parameters
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Setmoderationstatus
    post:
      summary: Add Comments Set Moderation Status
      description: Sets the moderation status of one or more comments. The API request
        must be authorized by the owner of the channel or video associated with the
        comments.
      operationId: postCommentsSetmoderationstatus
      x-api-path-slug: commentssetmoderationstatus-post
      parameters:
      - in: query
        name: banAuthor
        description: The banAuthor parameter lets you indicate that you want to automatically
          reject any additional comments written by the comments author
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs that
          identify the comments for which you are updating the moderation status
      - in: query
        name: moderationStatus
        description: Identifies the new moderation status of the specified comments
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Setmoderationstatus
  /fanFundingEvents:
    get:
      summary: Get Fanfundingevents
      description: Lists fan funding events for a channel.
      operationId: getFanfundingevents
      x-api-path-slug: fanfundingevents-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter instructs the API to retrieve localized resource
          metadata for a specific application language that the YouTube website supports
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the fanFundingEvent resource parts
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Fanfundingevents
    parameters:
      summary: Parameters Fanfundingevents
      description: Parameters fanfundingevents
      operationId: parametersFanfundingevents
      x-api-path-slug: fanfundingevents-parameters
      responses:
        200:
          description: OK
      tags:
      - Fanfundingevents
  /guideCategories:
    get:
      summary: Get Guecategories
      description: Returns a list of categories that can be associated with YouTube
        channels.
      operationId: getGuecategories
      x-api-path-slug: guidecategories-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter specifies the language that will be used for
          text values in the API response
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of the YouTube
          channel category ID(s) for the resource(s) that are being retrieved
      - in: query
        name: part
        description: The part parameter specifies the guideCategory resource properties
          that the API response will include
      - in: query
        name: regionCode
        description: The regionCode parameter instructs the API to return the list
          of guide categories available in the specified country
      responses:
        200:
          description: OK
      tags:
      - Guecategories
    parameters:
      summary: Parameters Guecategories
      description: Parameters guecategories
      operationId: parametersGuecategories
      x-api-path-slug: guidecategories-parameters
      responses:
        200:
          description: OK
      tags:
      - Guecategories
  /i18nLanguages:
    get:
      summary: Get Languages
      description: Returns a list of application languages that the YouTube website
        supports.
      operationId: getI18nlanguages
      x-api-path-slug: i18nlanguages-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter specifies the language that should be used for
          text values in the API response
      - in: query
        name: part
        description: The part parameter specifies the i18nLanguage resource properties
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Languages
    parameters:
      summary: Parameters Languages
      description: Parameters i18nlanguages
      operationId: parametersI18nlanguages
      x-api-path-slug: i18nlanguages-parameters
      responses:
        200:
          description: OK
      tags:
      - Languages
  /i18nRegions:
    get:
      summary: Get Regions
      description: Returns a list of content regions that the YouTube website supports.
      operationId: getI18nregions
      x-api-path-slug: i18nregions-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter specifies the language that should be used for
          text values in the API response
      - in: query
        name: part
        description: The part parameter specifies the i18nRegion resource properties
          that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Regions
    parameters:
      summary: Parameters Regions
      description: Parameters i18nregions
      operationId: parametersI18nregions
      x-api-path-slug: i18nregions-parameters
      responses:
        200:
          description: OK
      tags:
      - Regions
  /liveBroadcasts:
    delete:
      summary: Delete Live Broadcasts
      description: Delete livebroadcasts
      operationId: deleteLivebroadcasts
      x-api-path-slug: livebroadcasts-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube live broadcast ID for
          the resource that is being deleted
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
    get:
      summary: Get Live Broadcasts
      description: Returns a list of YouTube broadcasts that match the API request
        parameters.
      operationId: getLivebroadcasts
      x-api-path-slug: livebroadcasts-get
      parameters:
      - in: query
        name: broadcastStatus
        description: The broadcastStatus parameter filters the API response to only
          include broadcasts with the specified status
      - in: query
        name: broadcastType
        description: The broadcastType parameter filters the API response to only
          include broadcasts with the specified type
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of YouTube
          broadcast IDs that identify the broadcasts being retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: mine
        description: The mine parameter can be used to instruct the API to only return
          broadcasts owned by the authenticated user
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more liveBroadcast resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
    parameters:
      summary: Parameters Live Broadcasts
      description: Parameters livebroadcasts
      operationId: parametersLivebroadcasts
      x-api-path-slug: livebroadcasts-parameters
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
    post:
      summary: Add Live Broadcasts
      description: Creates a broadcast.
      operationId: postLivebroadcasts
      x-api-path-slug: livebroadcasts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
    put:
      summary: Put Live Broadcasts
      description: Updates a broadcast. For example, you could modify the broadcast
        settings defined in the liveBroadcast resource's contentDetails object.
      operationId: putLivebroadcasts
      x-api-path-slug: livebroadcasts-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
  /liveBroadcasts/bind:
    parameters:
      summary: Parameters Live Broadcasts Bind
      description: Parameters livebroadcasts bind
      operationId: parametersLivebroadcastsBind
      x-api-path-slug: livebroadcastsbind-parameters
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
      - Bind
    post:
      summary: Add Live Broadcasts Bind
      description: Binds a YouTube broadcast to a stream or removes an existing binding
        between a broadcast and a stream. A broadcast can only be bound to one video
        stream, though a video stream may be bound to more than one broadcast.
      operationId: postLivebroadcastsBind
      x-api-path-slug: livebroadcastsbind-post
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the unique ID of the broadcast that
          is being bound to a video stream
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more liveBroadcast resource properties that the API response will include
      - in: query
        name: streamId
        description: The streamId parameter specifies the unique ID of the video stream
          that is being bound to a broadcast
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
      - Bind
  /liveBroadcasts/control:
    parameters:
      summary: Parameters Live Broadcasts Control
      description: Parameters livebroadcasts control
      operationId: parametersLivebroadcastsControl
      x-api-path-slug: livebroadcastscontrol-parameters
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
      - Control
    post:
      summary: Add Live Broadcasts Control
      description: Controls the settings for a slate that can be displayed in the
        broadcast stream.
      operationId: postLivebroadcastsControl
      x-api-path-slug: livebroadcastscontrol-post
      parameters:
      - in: query
        name: displaySlate
        description: The displaySlate parameter specifies whether the slate is being
          enabled or disabled
      - in: query
        name: id
        description: The id parameter specifies the YouTube live broadcast ID that
          uniquely identifies the broadcast in which the slate is being updated
      - in: query
        name: offsetTimeMs
        description: The offsetTimeMs parameter specifies a positive time offset when
          the specified slate change will occur
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: onBehalfOfContentOwnerChannel
        description: This parameter can only be used in a properly authorized request
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more liveBroadcast resource properties that the API response will include
      - in: query
        name: walltime
        description: The walltime parameter specifies the wall clock time at which
          the specified slate change will occur
      responses:
        200:
          description: OK
      tags:
      - Livebroadcasts
      - Control
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