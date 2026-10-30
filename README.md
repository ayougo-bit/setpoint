Setpoint: A Betaflight tuning application

Open BlackboxFlightLab.Desktop.slnx in Visual Studio 2026. Startup project: BlackboxFlightLab.Desktop. Requires .NET 10 SDK; restores Avalonia 11.3.22.
Build-Desktop.ps1 publishes self-contained Windows/Linux builds; on Linux, sh Build-Desktop.sh also rebuilds the decoder with a C compiler.
The Desktop, Core and Tests projects are current. Legacy WPF projects, old runtimes and analysis reports are excluded.
GPL-3.0; dependency licenses and decoder source are in ThirdParty.

Windows 2.1.1 is published as one self-contained EXE, including the decoder. Native runtime files are extracted to the user's temporary cache; the embedded decoder is cached under LocalAppData\BlackboxFlightLab. No .NET installation is required.
