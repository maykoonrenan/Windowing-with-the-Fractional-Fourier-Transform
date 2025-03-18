Applications based on sensor data collection, such as respiration and heartbeat
monitoring, rely on accurate frequency-domain analysis. Fields such as digital communication
and pattern recognition also rely on spectral analysis of sensor-derived
data, often leveraging the Fourier Transform (FT) as a key tool. However, FT presents
drawbacks, such as spectral leakage, which can be partially mitigated by applying
window functions. For critical applications, though, window functions alone may not
be enough for optimal performance. Recent studies have explored combining window
functions with the Fractional Fourier Transform (FrFT) to enhance results, though
success depends on the chosen window function. Among existing options, Nuttall
windows offer high attenuation of side lobes, reducing spectral leakage but also presenting
a wide main lobe, leading to signal distortion. In this article, we propose a
new mathematical model combining Nuttall windows with FrFT. This model provides
a closed-form expression, utilizing a parameter to control the main lobe width while
maintaining reduced side lobe size, thereby enhancing adaptability for various sensorbased
applications. Results show that adjusting the main lobe width using the FrFT
expands Nuttall windows’ applications, such as in spectral analysis of respiratory signals,
where it improves frequency recognition, as well as in Filtered-OFDM to address
Out-of-Band Emission, offering an effective solution to one of the major challenges
in ensuring spectral efficiency.
