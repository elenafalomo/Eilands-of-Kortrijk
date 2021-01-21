# Eilands-of-Kortrijk
### A work in progress database which documents the historic moated farmsteads of Kortrijk

In [Islands Inventory](https://github.com/elenafalomo/Eilands-of-Kortrijk/tree/main/Islands%20Inventory) you will find our own database in csv and xlsx format, for each moated farmstead you will find the following values:
- **id:** a numeric id that uniquely identifies each island
- **xcoord:** latitude coordinate
- **ycoord:** longitude coordinate
- **name:** name by which the farmstead is known by
- **address:** the place where the farmsteads is located in the format "Street nr, ZIP City" (e.g. Izegemsestraat 362, 8501 Kortrijk)
- **isolation:** proximity towards urban agglomeration (i.e. urban morphological zone), the values can be:
  - isolated: far from urban fabric
  - semi-isolated: in a peri-urban area
  - not-isolated: close to the city
- **moat situation:** 
  - intact moat: moat in the original status
  - eroded moat: parts of the moat landfilled
  - no moat: moat has been completely landfilled
- **open area:** the farmstead ground has transformed to an open area such as a park or a field
- **water retention basin:** indicates the presence of a water retention basin close to the moat or made out of what remains of the original moat
- **relevant buildings:** indicates the presence of buildings related their original use

In [Islands Documentation](https://github.com/elenafalomo/Eilands-of-Kortrijk/tree/main/Islands%20Documentation) you will find a folder for each island named after the "name" field of the database, it contains pdf scans of books on the history of the farmsteads and images from our field trips
