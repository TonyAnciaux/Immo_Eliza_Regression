__**10/02/2022:**__

- First logical step: *Feature Engineering* 
- dropped redondant or useless columns (34 -> 16 columns)
- Divided the data into 4 categories: *qualitative & nominal*, *qualitative & ordinal*, 
*numerical & discrete*, *numerical & continuous*
- Turned *Kitchen Equipment* and *State of Property* into ordinal values
- Replaced following empty values: 
	- *Number of bedrooms* -> default *1*
	- *Surface terrace* -> default *0*
	- *Surface garden* -> default *0*


__**14/02/2022:**__

- Replaced following empty values with Series's mean:
	- Livable surface
	- Living-room surface
	- master bedroom surface
- One-Hot Encoded:
	- property types
	- localities
- Linear Regression


__** 15/02/2022:**__

- Polynomial Regressions:
	- different variations of features selection:
		- all (39 features)
		- without OHE regions (28 features)
		- without OHE regions and property types (13 features)
- Standardization data:
	- slightly decreased accuracy
- pairplots on original data
- scatter plot on Polynomial Regressions

