# Relational model

CUSTOMER (CustomerID, StoreName, PhoneNumber, StreetAddress, Suburb, State, Postcode)

ORDER (OrderID, CustomerID FK)

ORDER_LINE (OrderID FK, ShoeID FK, QuantityCases)

SHOE (ShoeID, Description, PromoPhoto, Category, CostPerCase, OverheadCost, SellingPricePerCase, ShoesPerCase, SupplierID FK)

SUPPLIER (SupplierID, SupplierName, StreetAddress, City, StateOrProvince, Postcode, Country)

SUPPLIER_PHONENUMBERS (SupplierID FK, PhoneNumber)

SUPPLIER_EMAILS (SupplierID FK, Email)
