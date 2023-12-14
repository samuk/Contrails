
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

robotics

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

robotics

# description

> This is the description of the feed.

Robotics feed. More info: https://github.com/samuk/bsky_robot_list open an issue there if you post mostly about robots and would like to be added to the list

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/scottsrobots.bsky.social/post/3jzit7o6bbg2k
- robotics
- https://bsky.app/profile/serdarabali.bsky.social
- https://bsky.app/profile/kevsmac.bsky.social
- https://bsky.app/profile/shurik179.bsky.social
- https://bsky.app/profile/orionrobots.bsky.social
- https://bsky.app/profile/did:plc:ruwu6z6o6dqsznteduxliky3
- https://bsky.app/profile/tlalexander.bsky.social
- https://bsky.app/profile/kamath.bsky.social
- https://bsky.app/profile/scottsrobots.bsky.social
- https://bsky.app/profile/audrow.bsky.social
- https://bsky.app/profile/neaveeng.bsky.social
- https://bsky.app/profile/rosmo.bsky.social
  


# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
