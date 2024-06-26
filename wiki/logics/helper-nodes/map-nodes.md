---
description: >-
  Implement map nodes in Blup for key-value pair data management within your
  application.
---

# Map Nodes

![](../../../.gitbook/assets/helper-map.gif)

This section consists of all the helper function nodes of map.

### Map | Remove

![](../../../.gitbook/assets/map-remove.png)

This node removes the key and its associated value from the map, if present. If the key is not found, no changes are made to the map.

For example, map {“athul”: “chaudhary”}, key = “atul”, so node removes the key-value pairs that have key matching with the provided key. In this case, the node returns an empty map because there is only one value in the map.

### Map | Clear

![](../../../.gitbook/assets/map-clear.png)

This node removes all the values that are present in the provided map, and then it returns the empty map.

For example, map = {“atul” : “chaudhary”}, this node return the map ={} which is the empty map.

### Map | Add All

![](../../../.gitbook/assets/map-andall.png)

This node helps you to Add all key/value pairs of others to this map. And If a key of other is already in the provided map, its value is overwritten \[make sure that both map have unique keys].

For example, map = {“CSE”:”atul”}, other map = {“IT”: “ashutosh”}, then the node return new map = {“CSE”: “atul”, “IT”: “ashutosh”}.

### Map | Contains Key

![](../../../.gitbook/assets/map-containskey.png)

This node checks if the provided key is present in the map.

For example, map = {“CSE”: “atul”}, key = “CSE”, then the node return true. If the key = “IT”, then the node return false.

### Map | Contains Value

![](../../../.gitbook/assets/map-containsvalue.png)

This node checks if the provided value is present in the map.

For example, Input map: {"CSE": "atul"}, value: "atul" Output: true

Input map: {"CSE": "atul"}, value: "ashutosh" Output: false

### Map | Is Empty

![](../../../.gitbook/assets/map-isempty.png)

This node checks if the provided map is empty or not if empty then it return true, if not then it returns false.

For example,Input map: {} Output: true Input map: {"CSE": "atul"} Output: false \[because map consists of some value ].

### Map | Length

![](../../../.gitbook/assets/map-length.png)

This node calculates the number of key-value pairs in the map.

For example,Input map: {"CSE": "atul", "IT": "ashutosh"} Output length: 2 \[because two key-values pairs are present].

### Map | Add Key Value

![](../../../.gitbook/assets/map-addkeyvalu.png)

This node adds a new key-value pair to the map to the existing map.

For example,Input map: {"CSE": "atul"}, key: "IT", value: "ashutosh" Output map: {"CSE": "atul", "IT": "ashutosh"}

### Map | Add Multiple Key Value

This node helps you to add multiple key-value pairs in a single go, this node returns the updated mao with all the newly added key-value pairs.

For example, Input map: {"atul": "chaudhary"}, keys: "sahaj", "ashutosh", values: "rana", "agarwal" Output map: {"atul": "chaudhary", "sahaj": "rana", "ashutosh": "agarwal"}

### Map | Get Value

![](../../../.gitbook/assets/map-getvalue.png)

This node retrieves the value associated with a specified key from the map.

For example, Input map: {"CSE": "atul"}, key: "CSE" Output value: "atul"

### Map | Get All Keys

![](../../../.gitbook/assets/map-getallkey.png)

This node retrieves all the keys present in the map.

For example, Input map: {"CSE": "atul", "IT": "ashutosh"} Output keys: \["CSE", "IT"]

### Map | Get All Values

![](../../../.gitbook/assets/map-getallvalue.png)

This node retrieves all the values present in the map.

For example, Input map: {"CSE": "atul", "IT": "ashutosh"} Output values: \["atul", "ashutosh"]

If you have any ideas to make Blup better you can share them through our [Discord community channel](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.

{% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
Lofi music
{% endembed %}
