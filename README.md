# EDDY_Z_OFFSET

Hello, I still couldn't get Z alignment right and in the new version of klipper (v0.13.0-562) it's a little different. Eddy has the disadvantage that temperature drift is a big factor. I uploaded the eddy calibration and temperature drift calibration (calibrated after 1 degree Celsius from cold start) to AI Grok. This resulted in a graph of eddy coil temperatures and measurement distances. The height can be moved in the conditions. Try the first print at 55 degrees of the eddy coil and measure the first layer. Recalculate all the values ​​in the conditions accordingly and insert them into them. AI should handle everything quickly. The pictures show macros that contain conditions. The division of macros for the current eddy coil temperature reading before measuring Z is important.

Accuracy is also achieved by careful measurement with stainless steel feeler gauges instead of using paper.

Added use of just one fine_tune variable to adjust z-offset as needed.
