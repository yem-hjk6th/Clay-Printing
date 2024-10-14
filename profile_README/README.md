### North Naug pinup wall profile

##### **3 SEGMENTS**
<p align="center">
<img src="./README_pic/ZONE.jpg" alt="zone" width="1200"/>
</p>

- **Zone**
    - *Zone 1*: the pinup wall neighboring to the spiral stairs
    - *Zone 2*: the pinup wall inbetween 2 doors
    - *Zone 3*: the pinup wall near the corner and face to the elevators
        - *Zone 3a*: with HVAC cabinet underneath
        - *Zone 3b*: without HVAC cabinet underneath

- **File**： Profile.3dm
<p align="center">
<img src="./README_pic/profile_img1.jpg" alt="anno_dh" width="100"/>
<img src="./README_pic/profile_img2.jpg" alt="anno_3d" width="162"/>
</p>


- **Focus: the dimension of the profile**
    - The brick wall
    - The deco
    - The steel plate
    - The HVAC cabinet
    - The pipe

- **Dimension**
    - 1st: Above the steel plate
        - thickness of steel plate: $$ \frac{3}{8}" $$
        - thickness of deco plate: $$ \frac{7}{8}" $$
    - 2nd: At the connection
        - D: $$ 1\frac{3}{4}" $$
    - 3rd: Below the steel plate
        - H: $$ 18\frac{1}{4}" $$
        - spec of HVAC box:
            - Width: $$ 5\frac{5}{8}" $$
            - Height: $$ 6" $$
            - Height off ground: $$ 3" $$
<p align="center">
<img src="./README_pic/dim1-1.png" alt="dim" width="600"/>
<img src="./README_pic/dim2.png" alt="dim" width="600"/>
<img src="./README_pic/dim3.png" alt="dim" width="600"/>
</p>

- **Similarity**
    - The specs of parts: steel plate and HVAC cabinet, are all same in three zones
    - The two main distances of different zones are the same within the tolerance: $$ \frac{1}{8}" $$
        - deco plate to brick wall -- Depth: D
        - steel plate to floor -- Height: H

- **Difference**
    - The tolerance is: $$ \frac{1}{8}" $$
    - Zone 2 & 3 vs Zone 1: 
        - Height off ground for zone 2 & 3: $$ 3" $$
        - H for zone 1: $$ 3\frac{1}{8}" $$
        - The difference is within tolerance
    - Zone 1 & 2 vs Zone 3:
        - The pipe is across the whole spread of zone 1 and zone 2
        - The zone 3 can be divided into 2 parts: zone 3a(with pipe beneath) and zone 3b(without pipe beneath)
            - their dimension is the same

- **Note**
    - The existing element is not listed in the diagram but may hinder the measurement:
        - The plugin board:
        - Dim: from the pic, its depth can be roughly estimated as the same depth from outer face of deco to brick wall surface: $$ 2\frac{5}{8}" $$
    <p align="center">
    <img src="./README_pic/plugin.png" alt="note" width="200"/>
    <img src="./README_pic/pipe.png" alt="note" width="120"/>
    </p>

    - The pipes are not all at the same height on the profile, but its relative distance to brick wall is fixed as: $$ \frac{1}{4}" $$


    