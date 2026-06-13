# Profile Geolocation Enhancements

## Overview

This project contains enhancements made to the customer profile management module, focusing on location-based address auto-fill and improved login user experience.

## Features Implemented

### 1. Show/Hide Password Functionality

* Added password visibility toggle using Eye / Eye-Off icons.
* Improved user experience during login and password reset.
* Allows users to verify entered passwords before submission.

### 2. Current Location Detection

* Integrated Browser Geolocation API.
* Captures user's current latitude and longitude.
* Handles location permission requests.

### 3. Google Geocoding API Integration

* Converts GPS coordinates into a readable address.
* Automatically fetches:

  * Street Address
  * City
  * Postal Code

### 4. Address Parsing Improvements

* Enhanced extraction of address components from Google Geocoding response.
* Improved handling of locality and postal code information.
* Added debugging logs for troubleshooting location issues.

### 5. City Mapping Enhancement

* Improved city mapping for Konaseema region.
* Example:

  * Village: Uppalaguptam
  * City: Amalapuram
  * District: Dr. B. R. Ambedkar Konaseema
  * PIN: 533222

### 6. Error Handling

* Permission denied handling.
* Location unavailable handling.
* Request timeout handling.
* User-friendly toast notifications.

## Technologies Used

* React.js
* Redux Toolkit
* Axios
* Google Geocoding API
* React Toastify

## Benefits

* Faster profile completion.
* Improved address accuracy.
* Better delivery location identification.
* Enhanced login experience.
* Reduced manual address entry errors.

## Future Enhancements

* Village field support.
* District field support.
* Location selection using Google Maps.
* Serviceability validation based on PIN code.
* Delivery zone auto-detection.
