# ProtfolioProject
CleaningDataProject(NashvilleHousing)


Project Based on Data cleaning

The data used is a study on Nashville housing

1st Process was changing data formats(SaleDate)

2nd Process was populating the property Address Data , here we exchanged Null Values

Using a Self-Join to fill in the NULL values of property addresses that had the same Parcel ID

divided the full adresses intop three individual columns by Address, City, and State

 looked for a specific value in a cell(,) to identify each of the three categories
 
 3rd Procees was changing the values Y & N for YES and NO in the specific field "Sold as Vacant"
 
 Using DISTINCT and CASE functions as well as UPDATE
 
 4th Process was removing duplicates
 
 Creating  a CTE (Temp Table)
 
 Using Rwo_NUM , CASE, and Partition By functions
 
 to create a table that showed all duplicates, to then delete them
 
 5 and final proces was to eliminate unused colums
 Since the address, city, state column where created, the original address columns (PropertyAddress/OwnerAddress) where removed.
 
 As well as the SaleDate and TaxDistrict.
