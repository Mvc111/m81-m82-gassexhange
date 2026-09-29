## Method

1. **Loading and Calibrating the Data:** We used our telescopes to make images of the M82&M82, and used Python to read the astronomical FITS image of the Cigar Galaxy (M82) and extract its metadata. This allowed us to verify the Astrometry.net coordinate mappings and ensure our spatial scales were perfectly aligned.
2. **Measuring Luminosity:** Next, we measured the actual brightness of the galaxy across the image. By extracting the flux values and factoring in the distance to M82, we calculated its total intrinsic luminosity.
3. **Estimating the Galaxy's Mass:** We used the mass-luminosity relation. This step allowed us to convert our total brightness measurement into a estimate of M82's total stellar mass.
4. **Calculating the Roche Limit:** Finally, we modeled the gravitational tug-of-war between M82 and its massive neighbor, M81. Using our derived mass, M81's mass, and their orbital separation, we calculated the Roche limit:

   $$d_R \approx R \left( 2 \frac{M_{\text{primary}}}{M_{\text{secondary}}} \right)^{1/3}$$

