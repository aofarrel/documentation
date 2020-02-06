---
description: >-
  An explanation for the interactive Data Dictionary page on Gen3 BioData
  Catalyst.
---

# Dictionary

The Gen3 BioData Catalyst Data Dictionary contains the visualization of the data model for the BioData Catalyst Dictionary. This graph view will display the relationships between nodes, specifically required relationships and node types, which are noted in the legend in the right corner.

![The interactive BioData Catalyst Data Dictionary without anything selected.](../../.gitbook/assets/image%20%2816%29.png)

## Graph View

To learn more about the node in the Graph View, a user can click on a node. This will initially highlight the relational paths that can be taken to connect to the node to the program node. A "Data Model Structure" list will also appear on the left side toolbar. This will write the node path that is required to reach the node from the program node.

![An example of a node being selected in the interactive graph view.](../../.gitbook/assets/image%20%285%29.png)

When another node in the path is selected, it will then gray out the other possible paths and only highlight the selected path. It will also change the node path on the left side toolbar.

![An example of a second node being selected in the path of the first selected node.](../../.gitbook/assets/image%20%2813%29.png)

The left side toolbar has two options available, `Open properties` and `Download templates`. The `Download templates` option will download the submission files for all the nodes in the chain. The `Open properties` option, will open the node properties in a new pop-up window.

![A node&apos;s property window.](../../.gitbook/assets/image%20%2821%29.png)

This property view will display all properties in the node and information about each property:

* **Property**: Name of the property
* **Type**: The type of input for the node. Examples of this are string, integer, boolean and enumerated values, which are displayed as preset strings.
* **Required**: This field will display whether the property is required for the submission of the node into the data model.
* **Description**: This field will display further information about the property.
* **Terms**: This field can be populated with external resources that have further information about the property.





## Table View

The Table View is similar to the Properties view and nodes are instead displayed grouped by their node category.

![Table View of the Gen3 BioData Catalyst Data Dictionary.](../../.gitbook/assets/image%20%2811%29.png)
