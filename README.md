The 3D scene data and associated query data cannot be made publicly available due to legal and proprietary restrictions.

Due to the restriction on compressed files in the submission system, the data can be accessed by: https://drive.google.com/file/d/1M3AF7Ef8AgpxaaKCPoL-rnkzkAj8ln3G/view?usp=drive_link.

-------------------------------------------------------------------------------------------------------------------------------------------------------

The following outlines the proposed workflow using the Beijing CBD area as a case study.

Relative Localization

1.Execute the PP-OCRv5 code to detect and extract the position and semantic meaning of each text unit from the query map image.

2. Match the detected text-unit positions with the corresponding place names from OpenStreetMap data.


Absolute Localization

1.Run demo.ipynb from the HLOC GitHub repository.

2. Replace the default datasets with the compressed photo set.

3. Reconstruct a 3D model of the CCTV building using a random subset of 80–100 photos.

4. Execute the 3D mapping and localization section within demo.ipynb to estimate the position and pose of the query photo.
