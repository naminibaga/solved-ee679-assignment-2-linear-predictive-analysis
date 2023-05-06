Download Link: https://assignmentchef.com/product/solved-ee679-assignment-2-linear-predictive-analysis
<br>
Note: You may use library functions if you wish. Code written from scratch will be awarded bonus points.

Given the speech segment (aa.wav) extracted from the word “pani” in “machali.wav” (male voice), sampled at 8 kHz, do the following.

<ol>

 <li>Apply pre-emphasis to the signal.</li>

 <li>Compute and plot the narrowband magnitude spectrum slice using a Hamming window of duration = 30 ms on a segment near the centre of the given audio file.</li>

 <li>With the same 30 ms segment of part 2, compute the autocorrelation coefficients required for LPC calculation at various p = 2,4,6,8,10. Use the Levinson-Durbin recursion to compute the LP coefficients from the autocorrelation coefficients. Plot error signal energy (i.e. square of gain) vs p.</li>

 <li>Show the pole-zero plots of the estimated all-pole filter for p=6,10; comment.</li>

 <li>Compute the gain and plot the LPC spectrum magnitude (i.e. the dB magnitude frequency response of the estimated all-pole filter) for each order “p”. Comment on the characteristics of the spectral envelope estimates. Comment on their shapes with reference to the short-time magnitude spectrum computed in part 2.</li>

 <li>Based on the 10th-order LP coefficients, carry out the inverse filtering of the /a/ vowel segment to obtain the residual error signal. Can you measure the pitch period of the voiced sound from the residual waveform? Use the acf to detect the pitch. Compare the acf plots of the original speech and residual signals.</li>

 <li>(<u>Optional for bonus marks</u>) LP re-synthesis: We analysed a natural speech sound /a/ above. Using a suitable set of parameter estimates as obtained there, we wish to <u>reconstruct</u> the sound.</li>

</ol>

That is, use the best estimated LP filter with an ideal impulse train of the estimated pitch period as source excitation.  Carry out de-emphasis on the output waveform. Set the duration of the synthesized sound to be 300 ms at 8 kHz sampling frequency and view the waveform as well as listen to your created sound.




Comment on the similarity with the original sound. What would be a good application for this analysis-and-synthesis system, and how exactly does it help?


