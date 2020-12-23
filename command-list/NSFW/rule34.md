# Rule34

## Description

This command allows users to search for images from [Rule34](https://rule34.xxx) and will output them in a NSFW Channel. Tags are supported.

{% hint style="warning" %}
This command only works in channels that are marked as NSFW.
{% endhint %}

## Usages

### 1 - Fetching a random image from Rule34

```text
!!rule34
```

This will fetch a random image from Rule34 and post it in the channel.

### 2 - Searching using tags

```text
!!rule34 <term>
```

This will search for a random image on Rule34 with them tags. Please note that tags must be seperated using commas and you can use spaces in tags as they are automatically changed into `_`'s apart from when a comma precedes it.

So for example:
```text
!!rule34 lara croft
```
The "lara croft" will be perceived as one tag.

and also
```text
!!rule34 lara croft, tagme
```
will be percieved as two tags. "lara croft" and "tagme" and will be treated appropriately.
