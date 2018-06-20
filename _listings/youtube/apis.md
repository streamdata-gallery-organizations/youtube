---
name: YouTube
x-slug: youtube
description: YouTube allows billions of people to discover, watch and share originally-created
  videos. YouTube provides a forum for people to connect, inform, and inspire others
  across the globe and acts as a distribution platform for original content creators
  and advertisers large and small.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: YouTube
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/apis.md
specificationVersion: "0.14"
apis:
- name: Youtube Get Jobs
  x-api-slug: youtube
  description: Lists jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs
  tags: V1, Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobs-get-openapi.md
- name: Youtube Add Jobs
  x-api-slug: youtube
  description: Creates a job and returns it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs
  tags: V1, Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobs-post-openapi.md
- name: Youtube Delete Jobs Job
  x-api-slug: youtube
  description: Delete v1 jobs job
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs/{jobId}
  tags: V1, Jobs, Job
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobid-delete-openapi.md
- name: Youtube Get Jobs Job
  x-api-slug: youtube
  description: Get v1 jobs job
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs/{jobId}
  tags: V1, Jobs, Job
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobid-get-openapi.md
- name: Youtube Get Jobs Job Reports
  x-api-slug: youtube
  description: |-
    Lists reports created by a specific job.
    Returns NOT_FOUND if the job does not exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs/{jobId}/reports
  tags: V1, Jobs, Job, Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobidreports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobidreports-get-openapi.md
- name: Youtube Get Jobs Job Reports Report
  x-api-slug: youtube
  description: Gets the metadata of a specific report.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/jobs/{jobId}/reports/{reportId}
  tags: V1, Jobs, Job, Reports, Report
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobidreportsreportid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1jobsjobidreportsreportid-get-openapi.md
- name: Youtube Get Media Resource Name
  x-api-slug: youtube
  description: |-
    Method for media download. Download is supported
    on the URI `/v1/media/{+name}?alt=media`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/media/{resourceName}
  tags: V1, Media, Resourcename
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1mediaresourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1mediaresourcename-get-openapi.md
- name: Youtube Get Reporttypes
  x-api-slug: youtube
  description: Lists report types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//v1/reportTypes
  tags: V1, Reporttypes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1reporttypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/v1reporttypes-get-openapi.md
- name: Youtube Get Activities
  x-api-slug: youtube
  description: Returns a list of channel activity events that match the request criteria.
    For example, you can retrieve events associated with a particular channel, events
    associated with the user's subscriptions and Google+ friends, or the YouTube home
    page feed, which is customized for each user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//activities
  tags: Activities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/activities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/activities-get-openapi.md
- name: Youtube Add Activities
  x-api-slug: youtube
  description: |-
    Posts a bulletin for a specific channel. (The user submitting the request must be authorized to act on the channel's behalf.)

    Note: Even though an activity resource can contain information about actions like a user rating a video or marking a video as a favorite, you need to use other API methods to generate those activity resources. For example, you would use the API's videos.rate() method to rate a video and the playlistItems.insert() method to mark a video as a favorite.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//activities
  tags: Activities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/activities-post-openapi.md
- name: Youtube Delete Captions
  x-api-slug: youtube
  description: Deletes a specified caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-delete-openapi.md
- name: Youtube Get Captions
  x-api-slug: youtube
  description: Returns a list of caption tracks that are associated with a specified
    video. Note that the API response does not contain the actual captions and that
    the captions.download method provides the ability to retrieve a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-get-openapi.md
- name: Youtube Add Captions
  x-api-slug: youtube
  description: Uploads a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-post-openapi.md
- name: Youtube Put Captions
  x-api-slug: youtube
  description: Updates a caption track. When updating a caption track, you can change
    the track's draft status, upload a new caption file for the track, or both.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captions-put-openapi.md
- name: Youtube Get Captions
  x-api-slug: youtube
  description: Downloads a caption track. The caption track is returned in its original
    format unless the request specifies a value for the tfmt parameter and in its
    original language unless the request specifies a value for the tlang parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions/{id}
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/captionsid-get-openapi.md
- name: Youtube Add Channel Banners Insert
  x-api-slug: youtube
  description: |-
    Uploads a channel banner image to YouTube. This method represents the first two steps in a three-step process to update the banner image for a channel:

    - Call the channelBanners.insert method to upload the binary image data to YouTube. The image must have a 16:9 aspect ratio and be at least 2120x1192 pixels.
    - Extract the url property's value from the response that the API returns for step 1.
    - Call the channels.update method to update the channel's branding settings. Set the brandingSettings.image.bannerExternalUrl property's value to the URL obtained in step 2.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channelBanners/insert
  tags: Channelbanners, Insert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelbannersinsert-post-openapi.md
- name: Youtube Delete Channel Sections
  x-api-slug: youtube
  description: Deletes a channelSection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channelSections
  tags: Channelsections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-delete-openapi.md
- name: Youtube Get Channel Sections
  x-api-slug: youtube
  description: Returns channelSection resources that match the API request criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channelSections
  tags: Channelsections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-get-openapi.md
- name: Youtube Add Channel Sections
  x-api-slug: youtube
  description: Adds a channelSection for the authenticated user's channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channelSections
  tags: Channelsections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-post-openapi.md
- name: Youtube Put Channel Sections
  x-api-slug: youtube
  description: Update a channelSection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channelSections
  tags: Channelsections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channelsections-put-openapi.md
- name: Youtube Get Channels
  x-api-slug: youtube
  description: Returns a collection of zero or more channel resources that match the
    request criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channels
  tags: Channels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channels-get-openapi.md
- name: Youtube Put Channels
  x-api-slug: youtube
  description: Updates a channel's metadata. Note that this method currently only
    supports updates to the channel resource's brandingSettings and invideoPromotion
    objects and their child properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//channels
  tags: Channels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/channels-put-openapi.md
- name: Youtube Get Comment Threads
  x-api-slug: youtube
  description: Returns a list of comment threads that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//commentThreads
  tags: Commentthreads
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentthreads-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentthreads-get-openapi.md
- name: Youtube Add Comment Threads
  x-api-slug: youtube
  description: Creates a new top-level comment. To add a reply to an existing comment,
    use the comments.insert method instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//commentThreads
  tags: Commentthreads
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentthreads-post-openapi.md
- name: Youtube Put Comment Threads
  x-api-slug: youtube
  description: Modifies the top-level comment in a comment thread.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//commentThreads
  tags: Commentthreads
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentthreads-put-openapi.md
- name: Youtube Delete Comments
  x-api-slug: youtube
  description: Deletes a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-delete-openapi.md
- name: Youtube Get Comments
  x-api-slug: youtube
  description: Returns a list of comments that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-get-openapi.md
- name: Youtube Add Comments
  x-api-slug: youtube
  description: 'Creates a reply to an existing comment. Note: To create a top-level
    comment, use the commentThreads.insert method.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments
  tags: Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-post-openapi.md
- name: Youtube Put Comments
  x-api-slug: youtube
  description: Modifies a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments
  tags: Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/comments-put-openapi.md
- name: Youtube Add Comments Mark as SPAM
  x-api-slug: youtube
  description: Expresses the caller's opinion that one or more comments should be
    flagged as spam.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments/markAsSpam
  tags: Comments, Markasspam
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentsmarkasspam-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentsmarkasspam-post-openapi.md
- name: Youtube Add Comments Set Moderation Status
  x-api-slug: youtube
  description: Sets the moderation status of one or more comments. The API request
    must be authorized by the owner of the channel or video associated with the comments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//comments/setModerationStatus
  tags: Comments, Setmoderationstatus
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentssetmoderationstatus-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/commentssetmoderationstatus-post-openapi.md
- name: Youtube Get Fanfundingevents
  x-api-slug: youtube
  description: Lists fan funding events for a channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//fanFundingEvents
  tags: Fanfundingevents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/fanfundingevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/fanfundingevents-get-openapi.md
- name: Youtube Get Guecategories
  x-api-slug: youtube
  description: Returns a list of categories that can be associated with YouTube channels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//guideCategories
  tags: Guecategories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/guidecategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/guidecategories-get-openapi.md
- name: Youtube Get Languages
  x-api-slug: youtube
  description: Returns a list of application languages that the YouTube website supports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//i18nLanguages
  tags: Languages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/i18nlanguages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/i18nlanguages-get-openapi.md
- name: Youtube Get Regions
  x-api-slug: youtube
  description: Returns a list of content regions that the YouTube website supports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//i18nRegions
  tags: Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/i18nregions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/i18nregions-get-openapi.md
- name: Youtube Delete Live Broadcasts
  x-api-slug: youtube
  description: Delete livebroadcasts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts
  tags: Livebroadcasts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-delete-openapi.md
- name: Youtube Get Live Broadcasts
  x-api-slug: youtube
  description: Returns a list of YouTube broadcasts that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts
  tags: Livebroadcasts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-get-openapi.md
- name: Youtube Add Live Broadcasts
  x-api-slug: youtube
  description: Creates a broadcast.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts
  tags: Livebroadcasts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-post-openapi.md
- name: Youtube Put Live Broadcasts
  x-api-slug: youtube
  description: Updates a broadcast. For example, you could modify the broadcast settings
    defined in the liveBroadcast resource's contentDetails object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts
  tags: Livebroadcasts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcasts-put-openapi.md
- name: Youtube Add Live Broadcasts Bind
  x-api-slug: youtube
  description: Binds a YouTube broadcast to a stream or removes an existing binding
    between a broadcast and a stream. A broadcast can only be bound to one video stream,
    though a video stream may be bound to more than one broadcast.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts/bind
  tags: Livebroadcasts, Bind
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcastsbind-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcastsbind-post-openapi.md
- name: Youtube Add Live Broadcasts Control
  x-api-slug: youtube
  description: Controls the settings for a slate that can be displayed in the broadcast
    stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts/control
  tags: Livebroadcasts, Control
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcastscontrol-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcastscontrol-post-openapi.md
- name: Youtube Add Live Broadcasts Transition
  x-api-slug: youtube
  description: Changes the status of a YouTube live broadcast and initiates any processes
    associated with the new status. For example, when you transition a broadcast's
    status to testing, YouTube starts to transmit video to that broadcast's monitor
    stream. Before calling this method, you should confirm that the value of the status.streamStatus
    property for the stream bound to your broadcast is active.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveBroadcasts/transition
  tags: Livebroadcasts, Transition
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcaststransition-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livebroadcaststransition-post-openapi.md
- name: Youtube Delete Live Chat Bans
  x-api-slug: youtube
  description: Delete livechat bans
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/bans
  tags: Chat, Bans
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatbans-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatbans-delete-openapi.md
- name: Youtube Add Live Chat Bans
  x-api-slug: youtube
  description: Adds a new ban to the chat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/bans
  tags: Chat, Bans
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatbans-post-openapi.md
- name: Youtube Delete Live Chat Messages
  x-api-slug: youtube
  description: Delete livechat messages
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/messages
  tags: Chat, Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmessages-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmessages-delete-openapi.md
- name: Youtube Get Live Chat Messages
  x-api-slug: youtube
  description: Lists live chat messages for a specific chat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/messages
  tags: Chat, Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmessages-get-openapi.md
- name: Youtube Add Live Chat Messages
  x-api-slug: youtube
  description: Adds a message to a live chat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/messages
  tags: Chat, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmessages-post-openapi.md
- name: Youtube Delete Live Chat Moderators
  x-api-slug: youtube
  description: Delete livechat moderators
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/moderators
  tags: Chat, Moderators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmoderators-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmoderators-delete-openapi.md
- name: Youtube Get Live Chat Moderators
  x-api-slug: youtube
  description: Lists moderators for a live chat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/moderators
  tags: Chat, Moderators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmoderators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmoderators-get-openapi.md
- name: Youtube Add Live Chat Moderators
  x-api-slug: youtube
  description: Adds a new moderator for the chat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveChat/moderators
  tags: Chat, Moderators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livechatmoderators-post-openapi.md
- name: Youtube Delete Livestreams
  x-api-slug: youtube
  description: Deletes a video stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveStreams
  tags: Livestreams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-delete-openapi.md
- name: Youtube Get Livestreams
  x-api-slug: youtube
  description: Returns a list of video streams that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveStreams
  tags: Livestreams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-get-openapi.md
- name: Youtube Add Livestreams
  x-api-slug: youtube
  description: Creates a video stream. The stream enables you to send your video to
    YouTube, which can then broadcast the video to your audience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveStreams
  tags: Livestreams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-post-openapi.md
- name: Youtube Put Livestreams
  x-api-slug: youtube
  description: Updates a video stream. If the properties that you want to change cannot
    be updated, then you need to create a new stream with the proper settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//liveStreams
  tags: Livestreams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/livestreams-put-openapi.md
- name: Youtube Delete Play List Items
  x-api-slug: youtube
  description: Deletes a playlist item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlistItems
  tags: Playlistitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlistitems-delete-openapi.md
- name: Youtube Get Play List Items
  x-api-slug: youtube
  description: Returns a collection of playlist items that match the API request parameters.
    You can retrieve all of the playlist items in a specified playlist or retrieve
    one or more playlist items by their unique IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlistItems
  tags: Playlistitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlistitems-get-openapi.md
- name: Youtube Add Play List Items
  x-api-slug: youtube
  description: Adds a resource to a playlist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlistItems
  tags: Playlistitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlistitems-post-openapi.md
- name: Youtube Put Play List Items
  x-api-slug: youtube
  description: Modifies a playlist item. For example, you could update the item's
    position in the playlist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlistItems
  tags: Playlistitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlistitems-put-openapi.md
- name: Youtube Delete Playlists
  x-api-slug: youtube
  description: Deletes a playlist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlists
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-delete-openapi.md
- name: Youtube Get Playlists
  x-api-slug: youtube
  description: Returns a collection of playlists that match the API request parameters.
    For example, you can retrieve all playlists that the authenticated user owns,
    or you can retrieve one or more playlists by their unique IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlists
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-get-openapi.md
- name: Youtube Add Playlists
  x-api-slug: youtube
  description: Creates a playlist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlists
  tags: Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-post-openapi.md
- name: Youtube Put Playlists
  x-api-slug: youtube
  description: Modifies a playlist. For example, you could change a playlist's title,
    description, or privacy status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//playlists
  tags: Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/playlists-put-openapi.md
- name: Youtube Get Search
  x-api-slug: youtube
  description: Returns a collection of search results that match the query parameters
    specified in the API request. By default, a search result set identifies matching
    video, channel, and playlist resources, but you can also configure queries to
    only retrieve a specific type of resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//search
  tags: Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/search-get-openapi.md
- name: Youtube Get Sponsors
  x-api-slug: youtube
  description: Lists sponsors for a channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//sponsors
  tags: Sponsors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/sponsors-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/sponsors-get-openapi.md
- name: Youtube Delete Subscriptions
  x-api-slug: youtube
  description: Deletes a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/subscriptions-delete-openapi.md
- name: Youtube Get Subscriptions
  x-api-slug: youtube
  description: Returns subscription resources that match the API request criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/subscriptions-get-openapi.md
- name: Youtube Add Subscriptions
  x-api-slug: youtube
  description: Adds a subscription for the authenticated user's channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/subscriptions-post-openapi.md
- name: Youtube Get Superchatevents
  x-api-slug: youtube
  description: Lists Super Chat events for a channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//superChatEvents
  tags: Chat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/superchatevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/superchatevents-get-openapi.md
- name: Youtube Add Thumbnails Set
  x-api-slug: youtube
  description: Uploads a custom video thumbnail to YouTube and sets it for a video.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//thumbnails/set
  tags: Thumbnails, Set
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/thumbnailsset-post-openapi.md
- name: Youtube Get Video Abuse Report Reasons
  x-api-slug: youtube
  description: Returns a list of abuse reasons that can be used for reporting abusive
    videos.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videoAbuseReportReasons
  tags: Veoabusereportreasons
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videoabusereportreasons-get-openapi.md
- name: Youtube Get Veocategories
  x-api-slug: youtube
  description: Returns a list of categories that can be associated with YouTube videos.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videoCategories
  tags: Veocategories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videocategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videocategories-get-openapi.md
- name: Youtube Delete Videos
  x-api-slug: youtube
  description: Deletes a YouTube video.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos
  tags: Veos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videos-delete-openapi.md
- name: Youtube Get Videos
  x-api-slug: youtube
  description: Returns a list of videos that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos
  tags: Veos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videos-get-openapi.md
- name: Youtube Add Videos
  x-api-slug: youtube
  description: Uploads a video to YouTube and optionally sets the video's metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos
  tags: Veos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videos-post-openapi.md
- name: Youtube Put Videos
  x-api-slug: youtube
  description: Updates a video's metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos
  tags: Veos
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videos-put-openapi.md
- name: Youtube Get Videos Get Rating
  x-api-slug: youtube
  description: Retrieves the ratings that the authorized user gave to a list of specified
    videos.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos/getRating
  tags: Veos, Getrating
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videosgetrating-get-openapi.md
- name: Youtube Add Videos Rate
  x-api-slug: youtube
  description: Add a like or dislike rating to a video or remove a rating from a video.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos/rate
  tags: Veos, Rate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videosrate-post-openapi.md
- name: Youtube Add Videos Report Abuse
  x-api-slug: youtube
  description: Report abuse for a video.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//videos/reportAbuse
  tags: Veos, Reportabuse
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/videosreportabuse-post-openapi.md
- name: Youtube Add Watermarks Set
  x-api-slug: youtube
  description: Uploads a watermark image to YouTube and sets it for a channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//watermarks/set
  tags: Watermarks, Set
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/watermarksset-post-openapi.md
- name: Youtube Add Watermarks Unset
  x-api-slug: youtube
  description: Deletes a channel's watermark image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//watermarks/unset
  tags: Watermarks, Unset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/watermarksunset-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/watermarksunset-post-openapi.md
- name: Youtube Delete Groupitems
  x-api-slug: youtube
  description: Removes an item from a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groupItems
  tags: Groupitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groupitems-delete-openapi.md
- name: Youtube Get Groupitems
  x-api-slug: youtube
  description: Returns a collection of group items that match the API request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groupItems
  tags: Groupitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groupitems-get-openapi.md
- name: Youtube Add Groupitems
  x-api-slug: youtube
  description: Creates a group item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groupItems
  tags: Groupitems
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groupitems-post-openapi.md
- name: Youtube Delete Groups
  x-api-slug: youtube
  description: Deletes a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-delete-openapi.md
- name: Youtube Get Groups
  x-api-slug: youtube
  description: Returns a collection of groups that match the API request parameters.
    For example, you can retrieve all groups that the authenticated user owns, or
    you can retrieve one or more groups by their unique IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-get-openapi.md
- name: Youtube Add Groups
  x-api-slug: youtube
  description: Creates a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groups
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-post-openapi.md
- name: Youtube Put Groups
  x-api-slug: youtube
  description: Modifies a group. For example, you could change a group's title.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//groups
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/groups-put-openapi.md
- name: Youtube Get Reports
  x-api-slug: youtube
  description: Retrieve your YouTube Analytics reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//reports
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/reports-get-openapi.md
- name: Youtube
  x-api-slug: youtube
  description: YouTube allows billions of people to discover, watch and share originally-created
    videos. YouTube provides a forum for people to connect, inform, and inspire others
    across the globe and acts as a distribution platform for original content creators
    and advertisers large and small.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: YouTube
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/youtube/master/_listings/youtube/openapi.md
x-common:
- type: x-articles
  url: https://developers.google.com/youtube/articles/
- type: x-authentication
  url: https://developers.google.com/youtube/v3/guides/authentication
- type: x-blog
  url: https://youtube-eng.googleblog.com/
- type: x-blog-rss
  url: https://youtube-eng.googleblog.com/feeds/posts/default?alt=rss
- type: x-branding
  url: https://developers.google.com/youtube/branding_guidelines
- type: x-bug-report
  url: https://code.google.com/p/gdata-issues/issues/entry
- type: x-bug-report
  url: https://code.google.com/p/gdata-issues/issues/list?q=label:API-YouTube
- type: x-buttons
  url: https://developers.google.com/youtube/youtube_subscribe_button
- type: x-deprecation-policy
  url: https://developers.google.com/youtube/youtube-api-list
- type: x-developer
  url: https://developers.google.com/youtube/
- type: x-getting-started
  url: https://developers.google.com/youtube/v3/getting-started
- type: x-github
  url: https://github.com/youtube
- type: x-github
  url: https://github.com/youtube/
- type: x-terms-of-service
  url: https://developers.google.com/youtube/terms
- type: x-training
  url: https://developers.google.com/youtube/training/
- type: x-twitter
  url: https://twitter.com/YouTubeDev
- type: x-website
  url: https://www.youtube.com/
- type: x-widgets
  url: https://developers.google.com/youtube/youtube_upload_widget
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---