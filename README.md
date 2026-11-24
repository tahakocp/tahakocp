### Hi, I'm Taha

I build small, tested tools: a webcam eye-gaze keyboard, a robot policy you can read in an evening, pool robot navigation, a braille display controller, crash diagnostics for microcontrollers, checks for robots and FPGAs, and things you can print. Each repo tries to do one job, says what was measured, and says what was not.

| project | what it does |
|---|---|
| [lookspeak](https://github.com/tahakocp/lookspeak) | Type and speak with your eyes, one switch or a long blink, using any webcam, in the browser. Optional on-device language model, seven languages, nothing leaves the device. |
| [picovla](https://github.com/tahakocp/picovla) | A vision-language-action robot policy from scratch in ~470 lines of PyTorch. Trains on a CPU, runs in the browser. |
| [brailleline](https://github.com/tahakocp/brailleline) | Controller core for DIY refreshable braille displays: moves only the dots that change, within your power budget. C99, 1.8 KB on a Cortex-M0+, browser simulator. Nothing built in hardware yet. |
| [poolnav](https://github.com/tahakocp/poolnav) | Coverage navigation for a pool cleaning robot that only has a gyro and motor current. no_std Rust, 4 KB on an RP2040, simulator and browser demo. |
| [lifecited](https://github.com/tahakocp/lifecited) | Practical life guide in plain English, every claim quoted from WHO, NHS, CDC, Cochrane or a regulator. |
| [lastwords](https://github.com/tahakocp/lastwords) | The last log lines and the fault that killed your Cortex-M or RV32 core, still in RAM after the reset. TrustZone-aware on ARMv8-M (Secure handler, Non-secure faults, SecureFault). Crash loops collapse into 17-byte repeats. Two C files, plus a [browser symbolizer](https://tahakocp.github.io/lastwords/) (ELF + export in, function and line out, nothing uploaded). |
| [urdflint](https://github.com/tahakocp/urdflint) | Catches broken URDF robot descriptions before your simulator does. One Rust binary. |
| [hollowstar](https://github.com/tahakocp/hollowstar) | Tells whether a GitHub repo's stars were earned or bought, from public data only. |
| [tinyraster](https://github.com/tahakocp/tinyraster) | Triangle rasterizer in SystemVerilog, pixel-exact against a C model. |
| [planet17](https://github.com/tahakocp/planet17) | Parametric 3D-printable planetary gearbox for NEMA 17 steppers, with collision checks in CI. |
| [alertpages](https://github.com/tahakocp/alertpages) | Earthquake and disaster alerts relayed by GitHub Actions to an offline web page and Telegram. No server. |

Hardware projects here are verified in simulation unless the README says otherwise. If you build one for real, or try lookspeak with a real webcam, I would like to hear how it went: open an issue in that repo.
