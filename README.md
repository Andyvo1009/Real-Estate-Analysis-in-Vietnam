# Vietnam Real Estate Dataset

## Overview
This dataset contains both **rental** and **sale** property listings from various cities and provinces across Vietnam. It includes information on location, pricing, property area, number of bedrooms, and number of bathrooms. The dataset is useful for analyzing trends in Vietnam’s real estate market, identifying price patterns, and comparing different property types.

## Dataset Description

### Files Included:
- **rental_real_estate_clean.csv**: Contains rental property listings across Vietnam.
- **sale_real_estate_clean.csv**: Contains property sale listings across Vietnam.

### Columns:
- **product_id**: Unique identifier for each listing.
- **address**: Location of the property (district, city, or province).
- **price**: Rental or sale price (usually in VND per month for rentals or total price for sales); some prices may be negotiable.
- **area**: Property size in square meters (m²).
- **bedrooms_num**: Number of bedrooms in the property.
- **bathrooms_num**: Number of bathrooms in the property.

### Property Classification:
- If both `bedrooms_num` and `bathrooms_num` are greater than zero, the listing is likely a **residential property** (e.g., apartment, house, villa).
- If both `bedrooms_num` and `bathrooms_num` are zero, the listing may represent **non-residential properties**, such as:
  - Office spaces
  - Commercial properties (shops, showrooms, retail spaces)
  - Warehouses or industrial facilities
  - Vacant land for lease or sale

## Example Listings

| product_id | address | price | area | bedrooms_num | bathrooms_num |
|------------|-----------------|-----------------|--------|--------------|--------------|
| 42131530 | Quận 1, Hồ Chí Minh | 26 triệu/tháng | 110 m² | 3 | 2 |
| 42128873 | Tân Bình, Hồ Chí Minh | 220 triệu/tháng | 320 m² | 0 | 0 |
| 41132814 | Quận 7, Hồ Chí Minh | Giá thỏa thuận | 14,500 m² | 0 | 0 |
| 40334597 | Quận 7, Hồ Chí Minh | Giá thỏa thuận | 42,000 m² | 0 | 0 |
| 51837281 | Hà Nội, Cầu Giấy | 5 tỷ | 80 m² | 2 | 1 | Sale |
| 52728394 | Bình Dương, Thuận An | 20 tỷ | 500 m² | 0 | 0 | Sale |

## Analysis Conducted
- **Price Distribution**: Analyzed the pricing trends of rental and sale properties across different cities.
- **Property Type Comparison**: Compared residential and commercial listings based on size, price, and location.
- **Geographic Trends**: Identified the most expensive and affordable regions in Vietnam for renting and buying properties.
- **Machine Learning Applications**: Built predictive models to estimate rental prices and property values based on features such as area, location, and number of rooms.

## Potential Use Cases
- **Investment Analysis**: Identify areas with high potential for real estate investment.
- **Real Estate Market Trends**: Understand rental and sale price fluctuations in different provinces.
- **Property Price Prediction**: Develop machine learning models to predict pricing based on various features.
- **Business Decision-Making**: Help real estate agents and investors make data-driven decisions.

## License & Citation
This dataset is provided for **educational and research purposes only**. If you use it in a project or publication, please credit the data source appropriately.

## Contact
For any questions or collaborations, feel free to reach out via Kaggle or GitHub.

