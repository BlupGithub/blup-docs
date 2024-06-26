---
description: >-
  Implement logical operators in Blup to perform logical operations and control
  your app's behavior.
---

# Logical Operators Section

![](../../.gitbook/assets/logical-operator.png)

## Logical Operator Nodes

This section encompasses all nodes for logical comparisons between values. There are three major logical operators in Blup:

1. **AND**: Returns true if both provided values are true. For example: `X<5 AND X<10`.
2. **OR**: Returns true if any of the provided values is true. For example: `X<40 OR X<50`.
3. **NOT**: Inverts the provided value. For example, if true is provided, it returns false and vice versa.

## AND Node

This node facilitates the implementation of logical AND between two boolean values. It returns true only if both provided values are true; otherwise, it returns false.

![](../../.gitbook/assets/logical-and.png)

### Components of Node

| Component           | Description                                                                                          |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| **A**               | Input node point for the first boolean value.                                                        |
| **B**               | Input node point for the second boolean value.                                                       |
| **Use Run Trigger** | Checkbox to add a run function node point to the node. Checking this box displays the function node. |

## OR Node

This node implements logical OR between two boolean values. It returns true if either A or B is true; otherwise, it returns false.

![](../../.gitbook/assets/logical-or.png)

### Components of Node

| Component           | Description                                                                                          |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| **A**               | Input node point for the first boolean value.                                                        |
| **B**               | Input node point for the second boolean value.                                                       |
| **Use Run Trigger** | Checkbox to add a run function node point to the node. Checking this box displays the function node. |
| **A OR B**          | Output node providing the result.                                                                    |

## NOT Node

This node applies logical NOT to a provided boolean value. It negates the provided value, returning true if the provided value is false, and false if it is true.

![](../../.gitbook/assets/logical-not.png)

### Components of Node

| Component           | Description                                                                                          |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| **A**               | Input node point for the boolean value.                                                              |
| **Use Run Trigger** | Checkbox to add a run function node point to the node. Checking this box displays the function node. |
| **NOT A**           | Output node providing the result.                                                                    |

If you have any ideas to make Blup better you can share them through our [Discord community channel](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.

{% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
Lofi music
{% endembed %}
