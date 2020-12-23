# Danbooru

### Description

This command allows users to search for images from [Danbooru](https://danbooru.donmai.us/) and will output them in a NSFW Channel. Tags are supported.

{% hint style="warning" %}
This command only works in channels that are marked as NSFW.
{% endhint %}

### Usages

#### 1 - Fetching a random image from Danbooru

```text
!!danbooru
```

This will fetch a random image from Danbooru and post it in the channel.

#### 2 - Searching using tags

```text
!!danbooru <term>
```

This will search for a random image on Danbooru with them tags. Please note that tags must be seperated using commas and you can use spaces in tags as they are automatically changed into `_`'s apart from when a comma precedes it.

So for example:

```text
!!danbooru lara croft
```

The "lara croft" will be perceived as one tag.

and also

```text
!!danbooru lara croft, tagme
```

will be percieved as two tags. "lara croft" and "tagme" and will be treated appropriately.

