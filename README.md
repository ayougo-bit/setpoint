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

Setpoint only connects to your flight controller to streamline the log download process and needs no internet connection to analyze a log.

Get it
Windows (10 or 11, x64): download Setpoint-windows-x64.exe from the latest release.
Linux (x64): download Setpoint-linux-x64.tar.gz from the latest release, extract it and run ./launch.sh.
Browser: open app.scopecreepusa.com. Nothing to install, and your logs never leave your computer. The analysis runs in the browser and gives the same results as the desktop app.
Manual
The Pilot's Manual is built into the app: press F1 or click Manual. It covers setting up a test flight, reading every tab, and a full tuning workflow from first flight to final tune.

Support
Questions, bugs and feature requests: inigo@scopecreepusa.com or the contact form at www.scopecreepusa.com.

### Licence

Setpoint is free software from ScopeCreep USA LLC, licensed under the GNU General Public License version 3 (GPL-3.0). Every release on this page has its source code attached as `Setpoint-X.Y.Z-source.zip`, right next to the downloads. Third-party parts and their licences are listed in the app under About › Third-party notices.

The Setpoint name and icon are not covered by the GPL. If you change the code and share it, give it a different name. Setpoint is not affiliated with Betaflight.

### Check your download (optional)

Every release includes `SHA256SUMS.txt`, signed with our release key.

Release key fingerprint: `21C2 0E2B C7BC C2C5 629D 46FB DF25 797B B8F9 DC0F`

1. Import the key once: `gpg --import setpoint-release-key.asc`
2. Check the signature: `gpg --verify SHA256SUMS.txt.asc SHA256SUMS.txt`. You should see "Good signature" and the fingerprint above.
3. Check the file you downloaded:
   - Linux: `sha256sum -c SHA256SUMS.txt --ignore-missing`
   - Windows (PowerShell): `Get-FileHash .\Setpoint-windows-x64.exe -Algorithm SHA256`, then compare the result with the line for that file in `SHA256SUMS.txt`.

If the signature or a checksum doesn't match, don't run the file. Let us know at inigo@scopecreepusa.com.
