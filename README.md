Expiry date validation AI project 
goal: The objective of this Expiry Date Validation AI project is to help prevent products in the store from expiring by alerting store personnel each month about items approaching their expiry date. 
We plan to implement monthly pop-ups to notify about soon-to-expire products, allowing us to prioritize their sale before they go out of date.


Approach:
1.We use self-tags of products for identification.

2.During cycle counts, we manually enter the product quantities and upload the expiry date, as expiry information is not embedded in the barcodes.

3.We use OCR technology to decode information from product labels, allowing for accurate data entry and tracking.

The manual process required due to the lack of expiry information in barcodes.


Analysis: 
The project adopted a phased approach:
Phase 1: Barcode decoding revealed product identifiers but not expiry dates.
Phase 2: QR code decoding contained promotional data but no expiry information.
Phase 3: OCR successfully extracted expiry dates from product labels but faced limitations with low-resolution images.
Phase 4: A structured dataset of 50 products was manually created, including attributes such as product name, price, quantity, and expiry date.
Phase 5: Machine learning models were employed to predict expiry dates, and recommendation techniques facilitated clearance sales.


Limitations:
1.	Barcodes and QR codes generally lack expiry date information.
2.	OCR accuracy is limited by image quality and text noise.
3.	Real-time scanning of all products is impractical for large inventories.
4.	Manual data entry is labor-intensive and prone to human error.


Results:
1.	OCR achieved moderate success in extracting expiry dates from labels.
2.	Decision Tree models provided accurate predictions for products nearing expiry, with the highest performance among tested algorithms.
3.	Recommendation systems effectively identified products suitable for clearance sales.

Conclusion/Discussion:
The project demonstrated that automated expiry date management is feasible with a combination of barcode decoding, OCR, and machine learning. However, the absence of expiry data in barcodes and QR codes remains a significant limitation. The integration of manual data entry and structured datasets proved crucial for effective tracking. Machine learning models and recommendation systems enhance decision-making for inventory management.

Future Work:
•	Explore the potential of integrating expiry dates into barcodes or QR codes.
•	Develop advanced OCR preprocessing techniques to improve accuracy.
•	Scale the system for real-time deployment in large retail stores.
•	Incorporate customer feedback into recommendation systems for personalized suggestions.
•	Investigate deep learning models for more accurate expiry prediction and text extraction.

