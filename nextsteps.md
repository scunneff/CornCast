1. Dust-on-snow modifier — highest impact for the target geography and season. CAIC publishes dust layer data, the physics are well understood (albedo reduction → earlier onset, compressed window), and it fills the single biggest real-world gap in the model right now. Complexity is moderate.
   
2. SNOTEL temperature cross-check on overnight low — this is a present accuracy problem disguised as future work. Niwot Ridge (#663) already returns TMIN data from the same fetch architecture you have. The auto-filled overnight low is most wrong on exactly the nights that matter most (clear, calm, inversion-prone). Complexity is low — it's an addition to existing fetch logic.
   
3. Approach time uncertainty — adding a simple pace multiplier input (or at minimum a visible caveat that the regression is one person's data) would make the departure time output more honest. Complexity is very low.

4. Using terrain shading from shae map
   
5. Incorproating DEM data in order to better evaluate terrain conditions.
   
6. Looking back to January 1 for the begining of column coldness - we have had a very warm year and not counting it may affect the results.
   
7. Expanding this to an area larger than the front range 
