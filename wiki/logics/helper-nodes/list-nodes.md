---
description: >-
  Manage and use list nodes in Blup for handling collections and data arrays
  effectively.
---

# List Nodes

This sub-section provides helper functions related to lists.

![](../../../.gitbook/assets/helper-list.gif)

### List | First Item

![](../../../.gitbook/assets/list-firstitem.png)

This node returns the first element of the provided list \[the first element is the element which is stored at 0 index in list].

For example – list = \[1,2,3,4,5] then this node return result = 1.

### List | Last Item

![](../../../.gitbook/assets/list-lastitem.png)

This node returns the last element of the provided list.

For example, list = \[1,2,3,4,5] then this node return result = 5.

### List | Reverse

![](../../../.gitbook/assets/list-reverse.png)

This node reverses the provided list.

For example, list = \[1,2,3,4,5] , node result = \[5,4,3,2,1].

### List | Remove At

![](../../../.gitbook/assets/list-removeat.png)

This node removes the element at the provided index from the list.

The provided index should be between 0 <= index < list Length.

For example, list = \[1,2,3,4,5], index = 1 result list = \[1,3,4,5];

{% hint style="info" %}
<mark style="color:blue;">Note: Indexing in list starts from zero.</mark>
{% endhint %}

### List | Remove Value

![](../../../.gitbook/assets/list-removevalue.png)

This node removes the first occurrence of the given value from the list.

For example, list = \[1,2,3,4,5,1], and value = 1, so this node will return: \[2,3,4,5,1].

### List | Add Value

![](../../../.gitbook/assets/list-addvalue.png)

This node adds a value to the end of the list, extending the length by one.

For example, list = \[1,2,3,4,5] and value = 6, so the node return = \[1,2,3,4,5,6].

### List | Add List

![](../../../.gitbook/assets/list-addlist.png)

This node combines two lists into a single list. The length of the resultant list is the sum of the length of the first and second lists.

For example, Input list1 = \[1,2,3] and Input list2 = \[4,5,6] and the Output list: \[1,2,3,4,5,6].

### List | Insert At

![](../../../.gitbook/assets/list-insertat.png)

This node helps you to insert at a particular position or index in the list, inserting an item into the list can cause the increase in the length of the list by one and shifts all objects at or after the index towards the end of the list.

For example, Input list: \[1, 2, 3, 4], index: 2, element: 10 Output list: \[1, 2, 10, 3, 4].

### List | Remove Range

![](../../../.gitbook/assets/list-removerange.png)

This node helps you to remove multiple sets of consecutive elements from the list at once.

Removes the elements with positions greater than or equal to start and less than the end, from the list. This reduces the list's length by the end - start.

For example, Input list = \[1,2,3,4,5,6] , start index: 0, end index: 2 and the Output list: \[3,4,5,6] because end is not included.

### List | Clear

![](../../../.gitbook/assets/list-clear.png)

This node helps you to Removes all objects from this list; the length of the list becomes zero.

This node returns the empty list which can be used again for adding items or elements.

For example Input list: \[1,2,3,4,5], Output list: \[].

### List | Length

![](../../../.gitbook/assets/list-length.png)

This node calculates the length of the list, indicating how many elements are present.

For example, Input list: \[1,2,3,4,5], Output length: 5 total 5 elements are present.

### List | Is Empty

![](../../../.gitbook/assets/list-isempty.png)

This node helps you to check whether the provided list is empty or not, if the provided list is empty then the node returns True else it returns false.

For example, Input list: \[1,2,3,4], Output: false, if Input list: \[], Output: true.

### List | Index Of

![](../../../.gitbook/assets/list-indexof.png)

This node finds the index of a particular element in the list. It returns the index of the first occurrence of the element.

For example, Input list: \[1,2,3,4], element: 3, then node Output index: 2.

{% hint style="info" %}
<mark style="color:blue;">Note: The index in the list starts from zero.</mark>
{% endhint %}

### List | Element At

![](../../../.gitbook/assets/list-elementat.png)

This node helps you to get the element at a particular index. This node returns the value of the item or element present at the given index.

For example, list = \[1,2,3,4,5,6] , index =2, then the node return 3, as indexing in list starts from zero.

If you have any ideas to make Blup better you can share them through our [Discord community channel](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.

{% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
Lofi music
{% endembed %}
