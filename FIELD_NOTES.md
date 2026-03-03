# Field Notes: Implementation Realities

These notes document the practical constraints and solutions derived from field work in fragile states and low-resource settings, aligned with UNICEF and UNDP implementation standards.

## 1. Biometric Degradation & Exception Handling
* **The Reality**: Manual labor in rural environments often leads to degraded fingerprints, causing standard biometric enrollment to fail for a significant percentage of the population.
* **The Solution**: The Maternal Digital Bridge implements an "Assisted Enrollment" workflow, allowing health workers to use multi-factor verification (Fayda ID + Visual Confirmation) as a secondary protocol.

## 2. The "Last Mile" Connectivity Gap
* **The Reality**: Constant 4G/5G connectivity is often unavailable in rural Ethiopia; systems requiring "always-on" internet will exclude the most vulnerable mothers.
* **The Solution**: Data collection utilizes asynchronous syncing, allowing for offline patient intake that pushes to the Information Mediator building block once the health worker reaches a service area.

## 3. Sovereign Infrastructure vs. Vendor Lock-In
* **The Reality**: Proprietary systems often "tax" governments for every new citizen registered, leading to unsustainable long-term costs.
* **The Solution**: By using Certified Digital Public Goods (DPGs) like MOSIP and OpenCRVS, we ensure the infrastructure is owned by the sovereign state and remains interoperable.

## 4. The Gender-Digital Divide
* **The Reality**: Women in rural areas are statistically less likely to own personal smartphones, creating a barrier to digital health services.
* **The Solution**: The inclusion of a mandatory Hardware Kit (Digital Bridge Kit) ensures technology reaches the mother directly, rather than assuming access to a family-shared device.
