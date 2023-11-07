# Bike Facilities
## GIS File Name
RECREATION_BikeFacilities
## Description
<DIV STYLE="text-align:Left;"><DIV><DIV><P><SPAN>This line layer indicates streets within the City of Cambridge that have pavement markings or construction features that facilitate bicycle use. It also contains multi-purpose paths where bicycles can be used off the street.</SPAN></P></DIV></DIV></DIV>

## Purpose
Created for planning purposes, map making, and for public distribution.
## Last Modified
11-06-2023
## Attributes
|Name|Type Details|Description|
|----|------------|-----------|
|LENGTH|type: Double<br/>width: 8<br/>precision: 19|Length of feature in internal units. |
|STREET|type: String<br/>width: 40<br/>precision: 0|Street name|
|ST_TYPE|type: String<br/>width: 20<br/>precision: 0|Street type|
|COMMENTS|type: String<br/>width: 50<br/>precision: 0|Comments|
|BIKE_FAC|type: SmallInteger<br/>width: 2<br/>precision: 5|Bicycle facility code<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>No existing facility; see PBIKE_FAC for planned facility</td></tr><tr><td>1</td><td>Bike Lane on both sides of a two-way street</td></tr><tr><td>2</td><td>Edge Line on both sides of a two-way street</td></tr><tr><td>3</td><td>Contra-flow</td></tr><tr><td>4</td><td>Grade-Separated Bike Lane on both sides of a two-way street</td></tr><tr><td>5</td><td>Bike Path/Multi-Use Path</td></tr><tr><td>6</td><td>Shared Lane Pavement Marking on both sides of a two-way street</td></tr><tr><td>7</td><td>Shared Street on both sides of a two-way street</td></tr><tr><td>8</td><td>Separated Bike Lane on both sides of a two-way street</td></tr><tr><td>9</td><td>Buffered Bike Lane on both sides of a two-way street</td></tr><tr><td>10</td><td>Bus/Bike Lane on both sides of a two-way street</td></tr><tr><td>11</td><td>Bike Lane on one side of a two-way street</td></tr><tr><td>12</td><td>Bike Lane on a one-way street</td></tr><tr><td>22</td><td>Edge Line on a one-way street</td></tr><tr><td>41</td><td>Grade-Separated Bike Lane on one side of a two-way street</td></tr><tr><td>42</td><td>Grade-Separated Bike Lane on a one-way street</td></tr><tr><td>61</td><td>Shared Lane Pavement Marking on one side of a two-way street</td></tr><tr><td>62</td><td>Shared Lane Pavement Marking on a one-way street</td></tr><tr><td>72</td><td>Shared Street on a one-way street</td></tr><tr><td>81</td><td>Separated Bike Lane on one side of a two-way street</td></tr><tr><td>82</td><td>Separated Bike Lane on a one-way street</td></tr><tr><td>83</td><td>Separated Bike Lane with Contra-flow</td></tr><tr><td>91</td><td>Buffered Bike Lane on one side of a two-way street</td></tr><tr><td>101</td><td>Bus/Bike Lane on one side of a two-way street</td></tr></table>|
|PBIKE_FAC|type: SmallInteger<br/>width: 2<br/>precision: 5|Planned bicycle facility code<br/><br /><table><tr><th style="font-weight:bold;">Value</th><th style="font-weight:bold;">Description</th></tr><tr><td>0</td><td>No existing facility</td></tr><tr><td>1</td><td>Planned Bike Lane on both sides of a two-way street</td></tr><tr><td>2</td><td>Planned Edge Line on both sides of a two-way street</td></tr><tr><td>3</td><td>Planned Contra-flow</td></tr><tr><td>4</td><td>Planned Grade-Separated Bike Lane on both sides of a two-way street</td></tr><tr><td>5</td><td>Planned Bike Path/Multi-Use Path</td></tr><tr><td>6</td><td>Planned Shared Lane Pavement Marking on both sides of a two-way street</td></tr><tr><td>7</td><td>Planned Shared Street on both sides of a two-way street</td></tr><tr><td>8</td><td>Planned Separated Bike Lane on both sides of a two-way street</td></tr><tr><td>9</td><td>Planned Buffered Bike Lane on both sides of a two-way street</td></tr><tr><td>10</td><td>Planned Bus/Bike Lane on both sides of a two-way street</td></tr><tr><td>11</td><td>Planned Bike Lane on one side of a two-way street</td></tr><tr><td>12</td><td>Planned Bike Lane on a one-way street</td></tr><tr><td>22</td><td>Planned Edge Line on a one-way street</td></tr><tr><td>41</td><td>Planned Grade-Separated Bike Lane on one side of a two-way street</td></tr><tr><td>42</td><td>Planned Grade-Separated Bike Lane on a one-way street</td></tr><tr><td>61</td><td>Planned Shared Lane Pavement Marking on one side of a two-way street</td></tr><tr><td>62</td><td>Planned Shared Lane Pavement Marking on a one-way street</td></tr><tr><td>72</td><td>Planned Shared Street on a one-way street</td></tr><tr><td>81</td><td>Planned Separated Bike Lane on one side of a two-way street</td></tr><tr><td>82</td><td>Planned Separated Bike Lane on a one-way street</td></tr><tr><td>83</td><td>Planned Separated Bike Lane with Contra-flow</td></tr><tr><td>91</td><td>Planned Buffered Bike Lane on one side of a two-way street</td></tr><tr><td>101</td><td>Planned Bus/Bike Lane on one side of a two-way street</td></tr></table>|
|EditDate|type: String<br/>width: 4<br/>precision: 0||
|Editor|type: String<br/>width: 8<br/>precision: 0|GIS editor|