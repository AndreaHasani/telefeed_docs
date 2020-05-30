# FAQ

Here you will find answers to every questions you might have about the bot and the way it works.

#### Q: Why do I have to give account access to your bot?

There are many reasons why our bot needs account access and to cover them all here would be a long read so instead we will show you an example of features between a bot which can be used without account connection and our bot.

<table style="margin-bottom: 20px;">
  <tr>
    <th style="padding:10px 20px;">Features</th>
    <th style="padding:10px 20px;">Without Account</th>
    <th style="padding:10px 20px;">Our Bot</th>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Forward from channels</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Forward Private Channel</td>
    <td style="padding:10px 20px; text-align:center;">Yes (if you can get the bot to join)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Forward channel without join</td>
    <td style="padding:10px 20px; text-align:center;">No</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Forward User/Bot</td>
    <td style="padding:10px 20px; text-align:center;">No</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Forward in Rewrite Mode</td>
    <td style="padding:10px 20px; text-align:center;">No (its a bot after all)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Read/Send message to every channel</td>
    <td style="padding:10px 20px; text-align:center;">No (Needs admin access)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">One-Many, Many-One Redirections</td>
    <td style="padding:10px 20px; text-align:center;">No</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Filtering</td>
    <td style="padding:10px 20px; text-align:center;">Probably (depends on the bot)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Whitelist/Blacklist</td>
    <td style="padding:10px 20px; text-align:center;">Probably (depends on the bot)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
  <tr>
    <td style="padding:10px 20px;">Text Manipulation</td>
    <td style="padding:10px 20px; text-align:center;">Probably (depends on the bot)</td>
    <td style="padding:10px 20px; text-align:center;">Yes</td>
  </tr>
</table>  


If you just need a bot to forward messages without <b>Rewrite Mode</b> and you have access to the channels you want to Forward From and To (you need to be a admin there) than you can use a bot without account access if that worries you. Our bot has many more advance features than any other bot but we do understand that users have their own privacy concerns.


#### Q: Can I forward from a channel I don't have access?

<B>No.</B> This bot can only see channels you as a user can see. So basically if you don't have access to a channel, the bot cannnot forward from it.

#### Q: Can I forward from a private channel?

Yes. You can forward from a private channel as long as you as a user are joined on that channel.

#### Q: Can I add my own text format (beginning, end, change words, add words) of the forwarded message?

<B>Yes.</B> There are many features that allow you to have total control on how the forwarded message look. You can change the text format however you want using [/transformation](/commands/#transformation)</b>

#### Q: Do I have control over what messages gets forwarded?

<b>Yes.</b> You have features such as [/settings](/commands/#settings)</b> where you can filter out which messages you want to <b>pass</b> or <b>not pass.</b> There's [/whitelist](/commands/#whitelist)</b> and [/blacklist](/commands/#blacklist)</b> which allows you to filter messages out based on <b>keywords</b> and [/selectusers](/commands/#selectusers)</b> which allows you to filter messages based on the user who sent them.

#### Q: Sometimes bot stops forwarding messages. Why does this happens?

Once in a while we are updating the bot. Usually it takes around 30 seconds to 1 minute. In very rare cases this can stay for 5 minutes. If the bot has stopped for more than 5 minutes without any notification do contact support.

#### Q: Can I choose which user (users) I want to allow messages from within a channel?

<b>Yes.</b> You can do that using [/selectusers](/commands/#selectusers)</b>

#### Q: Can I filter out duplicates?

<b>Yes.</b> Use /settings -> phone_number -> group_nickname -> redirection -> Process Duplicates Off

#### Q: Can I filter out myself?

<b>Yes.</b> Use /settings -> phone_number -> group_nickname -> redirection -> Process Me Off

#### Q: I want to remove all links from source channel. How do I do that?

Use /settings -> phone_number -> group_nickname -> Cleaner -> Urls On

#### Q: I want to remove all mentions from source channel. How do I do that?

Use /settings -> phone_number -> group_nickname -> Cleaner -> Mention On

#### Q: I need to do some complex filtering, I think I need to use a regular expression. Could you please help me to set it up?

Sorry but we don't have time to consult you on regular expressions. Read an article online or just google your case and find a ready solution.

There is a very convenient instrument to test regular expressions: https://regex101.com. Set the Flavor to "python" and set the flag "Single line: Dot matches the new line". This will make it work in the same way as @tg_feedbot's matcher


#### Q: Does this bot have any message limitation?

<b>No.</b> We don't have any message limitations in place.

#### Q: Does this bot delay messages?

<b>No.</b> Our bot does not delay messages apart from user specified delay.