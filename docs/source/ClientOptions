Client Options
==============

.. list-table:: Type: Object
   :widths: 25 25 50
   :header-rows: 1

   * - Parameter
     - Type
     - Description
   * - shards
     - number or array
     - ID of the shard to run, or an array of shard IDs. If not specified, the client will spawn ClientOptions#shardCount shards.
   * - shardCount
     - number
     - The total amount of shards used by all processes of this bot
   * - messageCacheMaxSize
     - number
     - Maximum number of messages to cache per channel (-1 or Infinity for unlimited - don't do this without message sweeping, otherwise memory usage will climb indefinitely)
   * - messageCacheLifetime
     - number
     - How long a message should stay in the cache until it is considered sweepable (in seconds, 0 for forever)
   * - messageSweepInterval
     - number
     - How frequently to remove messages from the cache that are older than the message cache lifetime (in seconds, 0 for never)
   * - fetchAllMembers
     - boolean
     - Whether to cache all guild members and users upon startup, as well as upon joining a guild (should be avoided whenever possible)
   * - disableMentions
     - disableMentionType
     - Whether to ignore @everyone/@here mention
   * - allowedMentions
     - MessageMentionType
     - Parse what mention is allowed in message
   * - partials
     - Array
     - Structures allowed to be partial. This means events can be emitted even when they're missing all the data for a particular structure. See the "Partials" topic listed in the sidebar for some important usage information, as partials require you to put checks in place when handling data.
   * - restWsBridgeTimeout
     - number
     - Maximum time permitted between REST responses and their corresponding websocket events. Default: 5000
   * - restTimeOffset
     - number
     - Extra time in millseconds to wait before continuing to make REST requests (higher values will reduce rate-limiting errors on bad connections)
   * - restRequestTimeout
     - number
     - Time to wait before cancelling a REST request, in milliseconds. Default: 15000     
   * - restSweepInterval
     - number
     - How frequently to delete inactive request buckets, in seconds (or 0 for never)
   * - retryLimit
     - number
     - How many times to retry on 5XX errors (Infinity for indefinite amount of retries)
   * - presence
     - presenceData
     - Presence data to use upon login
   * - ws
     - websocketOptions
     - Options for the WebSocket
   * - http
     - HTTPOptions
     - HTTP options
