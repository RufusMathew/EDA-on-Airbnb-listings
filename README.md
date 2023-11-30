
# Airbnb Listings Exploratory Data Analysis (EDA)

## Overview

This project involves Exploratory Data Analysis (EDA) on the Airbnb Listings dataset. The dataset comprises various attributes related to Airbnb property listings, including host information, property details, pricing, and reviews.

## Contents

1. `Data`: Contains the raw Airbnb Listings dataset.
2. `Cleaned_Data`: Contains the cleaned dataset after preprocessing.
3. `Visualizations`: Holds the visual representations generated from the data.

## Process

### 1. Learning About the Dataset

- Columns Overview: Familiarized myself with the dataset by understanding the meaning and relevance of each column.
- Data Types: Examined the data types to ensure they align with the nature of the information they represent.

### 2. Dataset Exploration

- Basic Statistics: Computed descriptive statistics (mean, median, mode, etc.) to understand the central tendency of numerical features.
- Data Distribution: Investigated the distribution of variables to identify patterns and outliers.

### 3. Data Cleaning

- Type Casting: Ensured appropriate data types for each column.
- Handling Missing Values: Identified and addressed missing values through imputation or removal.
- Dealing with Duplicates: Removed duplicate entries to maintain data integrity.
- Zero and Near-Zero Variance**: Eliminated features with minimal variability as they contribute little to the analysis.

### 4. Exploratory Data Analysis (EDA)

- First Moment Business Decision: Explored the mean values to make initial business decisions.
- Second Moment Analysis (Variance): Examined variance to understand the spread of data.
- Third Moment Analysis (Skewness): Investigated skewness for insights into the symmetry of distributions.
- Fourth Moment Analysis (Kurtosis): Studied kurtosis to understand the tails of distributions.

### 5. Data Visualization

- Auto EDA with SweetViz: Utilized SweetViz for automated exploratory data analysis, providing comprehensive insights into the dataset.
- Visualization Techniques: Employed various visualization techniques, such as histograms, scatter plots, and correlation matrices, to identify patterns and relationships.


## Column Description

1. id: Unique identifier for each listing.
2. listing_url: URL link to the listing.
3. scrape_id: Identifier for the data scrape.
4. last_scraped: Date when the listing was last scraped.
5. name: Name of the listing.
6. summary: A brief summary or description of the listing.
7. space: Information about the space available in the listing.
8. description: Detailed description of the listing.
9. experiences_offered: Type of experiences offered by the host.
10. neighborhood_overview: Overview of the neighborhood.
11. notes: Additional notes about the listing.
12. transit: Details about transportation options in the area.
13. thumbnail_url: URL for the thumbnail image of the listing.
14. medium_url: URL for the medium-sized image of the listing.
15. picture_url: URL for the main picture of the listing.
16. xl_picture_url: URL for the extra-large picture of the listing.
17. host_id: Unique identifier for the host.
18. host_url: URL link to the host's profile.
19. host_name: Name of the host.
20. host_since: Date when the host joined Airbnb.
21. host_location: Location of the host.
22. host_about: Information about the host.
23. host_response_time: Time taken by the host to respond.
24. host_response_rate: Response rate of the host.
25. host_acceptance_rate: Acceptance rate of booking requests by the host.
26. host_is_superhost: Indicates if the host is a superhost.
27. host_thumbnail_url: URL for the host's thumbnail image.
28. host_picture_url: URL for the host's main picture.
29. host_neighbourhood: Neighborhood of the host.
30. host_listings_count: Number of listings by the host.
31. host_total_listings_count: Total number of listings by the host.
32. host_verifications: Verification methods used by the host.
33. host_has_profile_pic: Indicates if the host has a profile picture.
34. host_identity_verified: Indicates if the host's identity is verified.
35. street: Street address of the listing.
36. neighbourhood: General neighborhood information.
37. neighbourhood_cleansed: Neighborhood information after cleansing.
38. neighbourhood_group_cleansed: Cleansed neighborhood group information.
39. city: City where the listing is located.
40. state: State where the listing is located.
41. zipcode: ZIP code of the listing.
42. market: The market where the listing is present.
43. smart_location: Smart location information.
44. country_code: Country code of the listing.
45. country: Country where the listing is located.
46. latitude: Latitude coordinates of the listing.
47. longitude: Longitude coordinates of the listing.
48. is_location_exact: Indicates if the location is exact.
49. property_type: Type of property (e.g., apartment, house).
50. room_type: Type of room available for booking.
51. accommodates: Number of guests the listing can accommodate.
52. bathrooms: Number of bathrooms in the listing.
53. bedrooms: Number of bedrooms in the listing.
54. beds: Number of beds in the listing.
55. bed_type: Type of bed in the listing.
56. amenities: Amenities provided in the listing.
57. square_feet: Area of the listing in square feet.
58. price: Listing price per night.
59. weekly_price: Price for a week's stay.
60. monthly_price: Price for a month's stay.
61. security_deposit: Security deposit required.
62. cleaning_fee: Cleaning fee charged.
63. guests_included: Number of guests included in the base price.
64. extra_people: Additional fee for extra guests.
65. minimum_nights: Minimum number of nights required for booking.
66. maximum_nights: Maximum number of nights allowed for booking.
67. calendar_updated: Date when the calendar was last updated.
68. has_availability: Indicates if the listing has availability.
69. availability_30: Availability for the next 30 days.
70. availability_60: Availability for the next 60 days.
71. availability_90: Availability for the next 90 days.
72. availability_365: Availability for the next 365 days.
73. calendar_last_scraped: Date when the calendar was last scraped.
74. number_of_reviews: Total number of reviews for the listing.
75. first_review: Date of the first review.
76. last_review: Date of the last review.
77. review_scores_rating: Overall rating given by guests.
78. review_scores_accuracy: Accuracy rating given by guests.
79. review_scores_cleanliness: Cleanliness rating given by guests.
80. review_scores_checkin: Check-in rating given by guests.
81. review_scores_communication: Communication rating given by guests.
82. review_scores_location: Location rating given by guests.
83. review_scores_value: Value rating given by guests.
84. requires_license: Indicates if a license is required.
85. license: License information.
86. jurisdiction_names: Jurisdiction names related to the listing.
87. instant_bookable: Indicates if instant booking is available.
88. cancellation_policy: Policy for canceling bookings.
89. require_guest_profile_picture: Requires guests to have a profile picture.
90. require_guest_phone_verification: Requires guests to verify their phone number.
91. calculated_host_listings_count: Number of listings by the host.
92. reviews_per_month: Average number of reviews received per month.


