Setpoint
Blackbox tuning analysis for Betaflight.

Setpoint takes a Betaflight blackbox log and turns it into the views you actually tune with: step response, noise, spectra, setpoint tracking and a filter preview, plus a read-only copy of the tune that was flying. It is free, it runs on Windows, Linux or in your browser, and it reads modern Betaflight logs, including 4.5, 2025.12 and the 2026.x releases.

It was built and checked against real flight logs, tuned side by side on real quads.

What it does
Step response. Averaged stick-step response for roll, pitch and yaw, with peak and latency for each log. Load several logs or runs and overlay them to see what a change really did.
Noise. Four heat maps, gyro and D-term against throttle and against time, with RPM and notch lines you can switch on. Use them to find where the noise comes from and set your RPM filter and dynamic notch.
Spectrum. Gyro and D-term spectra before and after filtering, on a true power scale, with a tip on what noise level to aim for.
Tracking. Setpoint against gyro with the F term, and tracking stats, to judge feedforward and lag.
Filter preview. Change the gyro and D-term lowpass filters and see the effect on your recorded noise before you fly again.
Tune. Every PID, slider and filter setting from the log header, laid out the Betaflight way, so you know exactly what was flying.
Details. A plain-text report of every number, ready to copy or share when you ask for help.
Every number is labelled as measured from the log, read from the log header, or worked out from Betaflight's own source, so you always know where it came from.

Setpoint never connects to your flight controller and needs no internet connection to analyse a log.

Get it
Windows (10 or 11, x64): download Setpoint-windows-x64.exe from the latest release.
Linux (x64): download Setpoint-linux-x64.tar.gz from the latest release, extract it and run ./launch.sh.
Browser: open app.scopecreepusa.com. Nothing to install, and your logs never leave your computer. The analysis runs in the browser and gives the same results as the desktop app.
Manual
The Pilot's Manual is built into the app: press F1 or click Manual. It covers setting up a test flight, reading every tab, and a full tuning workflow from first flight to final tune.

Support
Questions, bugs and feature requests: inigo@scopecreepusa.com or the contact form at www.scopecreepusa.com.

Licence
Setpoint is licensed under the GNU General Public License v3. Source code is available on request via www.scopecreepusa.com.
