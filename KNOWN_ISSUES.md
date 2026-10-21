# Known issues

Updated 21 October 2026. A prepared change is not a released or hardware-verified fix.

| Report | Status |
| --- | --- |
| D200X on Windows stays Basic/Offline despite installed Remote Script and Ulanzi/None/None configuration; custom library/reboot trouble also reported | Custom library auto-discovery path defect corrected in the unreleased 1.1.3 candidate with a filesystem regression. Continued Offline at the default path remains unexplained. Need logs, exact versions and native Windows testing. No user-error finding. |
| Non-English setup instructions say Dial instead of Ulanzi | Confirmed; corrected in the unreleased 1.1.3 candidate. |
| Marketplace fails to parse multiple D200 model presets | Ulanzi corrected the existing listing; reporter confirmed download works. Future uploads contain one D200X preset per OS. |
| Deck preset appears for Dial | Reported; not reproduced in current local Studio. Candidate excludes undeclared Deck presets from the Plugin package. Clean store-install verification pending. |
| Large macOS scroll increments with the Vibe coding profile | Outside this plugin: generic mouse-wheel/profile behavior. Requires Ulanzi investigation; no confirmed trackpad-related cause. |

Windows testing and physical D200/D200H import checks are pending. Please add matching reproductions to the existing issue rather than opening duplicates.
