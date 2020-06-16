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

*channels* - all of the channels the client is handling. Type: channelManager

*emojis* - all custom emojis a client have access to. Type: guildEmojiManager

*guilds* - all of the guilds the client is handling. Type: guildManager

*options* - all of the client options. Type: `ClientOptions <https://dhy.readthedocs.io/en/latest/ClientOptions.html>`_

*readyAt* - the time the client fires the ready event. Type: ?Date

*readyTimestamp* - the unix timestamp of when the client fires the ready event. Type: ?number

*shard* - Shard helpers for the client. Type: ?shardClientUtil

*token* - Bot token used to login the bot. Should be kept secret at all times. Type: ?string

*uptime* - How long the bot has been up. Type: ?number

*user* - the user the client is logged in as. Type: ?ClientUser

*users* - all of the users available to the client. Type: userManager

*voice* - the voice manager of the client. Type: voice

*ws* - the websocket manager of the client. Type: websocketManager
