---
description: >-
  Implement duration nodes in Blup for precise time interval calculations in
  your application.
---

# Duration Nodes

![](../../../.gitbook/assets/helper-duration.gif)

### Duration | Abs

![](../../../.gitbook/assets/duration-abs.png)

This node returns a Duration that has the same length as the provided one but is always positive. If the duration is negative, this node converts it to a positive duration.

### Duration | Compare To

![](../../../.gitbook/assets/duration-compareto.png)

This node compares two durations and returns:

This node returns -

1\. Zero if both durations are the same.

2\. A negative integer if the first duration is shorter than the second.

3\. A positive integer if the first duration is greater than the second.

{% hint style="info" %}
<mark style="color:blue;">Note - A negative Duration is always considered shorter than a positive one.</mark>
{% endhint %}

### Duration | Is Negative

![](../../../.gitbook/assets/duration-isnegative.png)

This node returns true if the duration provided is negative. If the duration is negative then this node returns true, if the duration is not negative then this node returns false.

### Duration | Conversion

![](../../../.gitbook/assets/duration-conversion.png)

This node helps you to convert the duration into the required format for example, hours into minutes.

If you have any ideas to make Blup better you can share them through our [Discord community channel](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.

{% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
Lofi music
{% endembed %}
