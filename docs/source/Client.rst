Client
======

Constructor
-----------
.. code-block:: javascript

   new Discord.Client(options)

.. list-table:: Options
   :widths: 25 25 50
   :header-rows: 1

   * - Heading Parameter
     - Heading Type
     - Heading Description
   * - options
     - `clientOptions <https://dhy.readthedocs.io/en/latest/ClientOptions.html>`_
     - Options For the Client


**Properties**
--------------

*channels* - all of the channels the client is handling. Type: `channelManager <https://discord.js.org/#/docs/main/stable/class/ChannelManager>`_

*emojis* - all custom emojis a client have access to. Type: `guildEmojiManager <https://discord.js.org/#/docs/main/stable/class/GuildEmojiManager>`_

*guilds* - all of the guilds the client is handling. Type: `guildManager <https://discord.js.org/#/docs/main/stable/class/GuildManager>`_

*options* - all of the client options. Type: `ClientOptions <https://discord.js.org/#/docs/main/stable/typedef/ClientOptions>`_

*readyAt* - the time the client fires the ready event. Type: ?`Date <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date>`_

*readyTimestamp* - the unix timestamp of when the client fires the ready event. Type: ?`number <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number>`_

*shard* - Shard helpers for the client. Type: ?`shardClientUtil <https://discord.js.org/#/docs/main/stable/class/ShardClientUtil>`_

*token* - Bot token used to login the bot. Should be kept secret at all times. Type: ?string

*uptime* - How long the bot has been up. Type: ?number

*user* - the user the client is logged in as. Type: ?ClientUser

*users* - all of the users available to the client. Type: userManager

*voice* - the voice manager of the client. Type: voice

*ws* - the websocket manager of the client. Type: websocketManager

**Methods**

*clearImmediate* - Clears an immediate - returns Void
.. list-table:: Parameters
   :widths: 25 25 50
   :header-rows: 1

   * - Parameter
     - Type
     - Description
   * - imediate
     - Immediate
     - Immediate to cancel
